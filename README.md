# iOS-App-Store-Preview-Video-Upscale
Instructions to upscale iOS App Store Preview Video

Create App Store Preview video using iMovie or similar.

Download FFMPEG.

`ffmpeg -i "input_video.mp4" -acodec copy -color_primaries 1 -color_trc 1 -colorspace 1 -crf 6 -vf scale=1080:1920,setsar=1:1 "output_video.mp4"`
