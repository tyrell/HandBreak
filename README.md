# HandBreak Encoding Presets

HandBreak (https://handbrake.fr) is an Open Source video transcoder. 

This reposirtory contains HandBreak presets that can be used to compress large video files into smaller sizes for portability. The presets use a combination of H.265 encoding, resolution tweaking and video bitrate throttling to achieve the smaller storage footprint. 

Needless to say that this is lossy compression and will result in the introduction of compression artifacts to a video file. It's worthwhile to play  with various options to customise these presets to match your taste and tolerance before commiting.  

Eg: "Small HD Episodes 720p.json" preset can reduce a 1.15GB source video file to 159.3MB (13.8 % of the source file). 

Preset Name | Test Source File Size | Test Output File Size | Percentge (final size vs source)
---|---|---|---
Small HD Episodes 720p.json | 1.5GB | 228.4MB | 5.15% 
Small HD Episodes 1080p.json | 6.31GB | 1.03GB | 6.37%
Small HD Episodes 10-bit 720p.json | 1.22GB | 308.8 MB | 25.35% (with 5.1 Surround Sound)
Small Movies 4K UHD (2160p 10-bit).json | 23.8GB | 4.47GB | 18.74% 



# License
MIT
