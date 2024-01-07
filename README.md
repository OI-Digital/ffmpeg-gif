# ffmpeg-gif

ffmpeg -ss 00:00:12 -t 00:00:03 -i video.mp4 -r 5 -filter:v scale=320:-1 -c:a copy video.gif

Takes a video and converts it into a 3 second gif, 320px wide with a frame rate of 5 fps
