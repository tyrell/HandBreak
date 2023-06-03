# HandBreak Encoding Presets

HandBreak (https://handbrake.fr) is an Open Source video transcoder. 

This reposirtory contains HandBreak presets that can be used to compress large video files into smaller sizes for portability. The presets use a combination of H.265 encoding, resolution tweaking and video bitrate throttling to achieve the smaller storage footprint. 

Needless to say that this is lossy compression and will result in the introduction of compression artifacts to a video file. It's worthwhile to play  with various options to customise these presets to match your taste and tolerance before commiting.  

Eg: "Small HD Episodes 720p.json" preset can reduce a 1.15GB source video file to 159.3MB (13.8 % of the source file). 

Preset Name | Test Source File Size | Test Output File Size | Percentge
---|---|---|---
Small HD Episodes 720p.json | 1.15GB | 159.3MB | 13.8 %
Small HD Episodes 1080p.json | 6.31GB | 1.03GB | 6.37 %


# License
MIT
