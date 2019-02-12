# for convert 

this good method
```
ffmpeg.exe -i input.mp3 -map_metadata 0 -codec:a libvorbis -qscale:a 5 output.oga
```