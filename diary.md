## MP4 compression
ffmpeg -i iStock-474550200.mov -vcodec libx264 -f mp4 -vb 3000k -preset slow -an intro.mp4