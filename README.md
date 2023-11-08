# fastdownload-ytdlp
Copy and paste command for yt-dlp &amp; Useful for video editing user

## Download MP3 Max Quality
`yt-dlp -x --audio-quality 0 --audio-format mp3 "youtube link" -P "save location"`

## Download MP4 H.264 Max Quality
`yt-dlp -f "bv*[ext=mp4]+ba[ext=m4a]/b[ext=mp4] / bv*+ba/b" -S vcodec:h264 "youtube link" -P "save location"`

