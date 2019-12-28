# ffmpgf

## FFmpeg commands available:

### Cut:

ffmpeg -ss 00:10:00.0 -i in.avi -c copy -t 00:02:00.0 out.avi

### Join:

ffmpeg -f concat -c copy -i list.txt out.avi 

### Merge AV:

ffmpeg -i in.avi -i in.mp3 -c copy out.avi 

### Resize:

ffmpeg -i in.avi -vf scale=320:200 out.avi 