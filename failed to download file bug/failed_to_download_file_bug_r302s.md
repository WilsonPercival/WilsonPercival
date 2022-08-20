## Problem description

I can't download a project file with the same name after I delete it.

## Attach a .c3p

[Test.zip](https://github.com/WilsonPercival/WilsonPercival/files/9387889/Test.zip)

## Steps to reproduce

1. Create a new project.
2. Press Menu -> Project -> Save as -> Download a copy.
3. Give some name to the file, for example `Test`.
4. Save it.
5. Remove it.
6. Repeat steps 2, 3 and 4.

## Observed result

https://www.dropbox.com/s/6bnr8kd3d5pogv6/mobizen_20220820_121015.mp4?dl=0

## Expected result

I can download the file.

## More details

If I call it differently after deletion, everything works fine.

**Affected browsers/platforms:** Android

**First affected release:** broke in r302s

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r302 (stable)
Browser: Chrome 104.0.5112.69
Browser engine: Chromium
Context: webapp
Operating system: Android 12.0.0
Device type: desktop
Device pixel ratio: 1.3312500715255737
Logical CPU cores: 8
Approx. device memory: 2 GB
User agent: Mozilla/5.0 (Linux; Android 12; SM-T500) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/104.0.0.0 Safari/537.36
Language setting: en-US
Local storage
Storage quota (approx): 13 gb
Storage usage (approx): 2.1 mb (0%)
Persistant storage: No
Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.
UI effects are disabled in settings.
WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Qualcomm
Renderer: Adreno (TM) 610
Major performance caveat: no
Maximum texture size: 4096
Point size range: 1 to 1023
Extensions:
EXT_color_buffer_float
EXT_color_buffer_half_float
EXT_float_blend
EXT_texture_filter_anisotropic
EXT_texture_norm16
OES_texture_float_linear
WEBGL_compressed_texture_astc
WEBGL_compressed_texture_etc
WEBGL_compressed_texture_etc1
WEBGL_debug_renderer_info
WEBGL_debug_shaders
WEBGL_lose_context
WEBGL_multi_draw
Audio information
System sample rate: 48000 Hz
Output channels: 2
Output interpretation: speakers
Supported decode formats:
WebM Opus (audio/webm; codecs=opus)
Ogg Opus (audio/ogg; codecs=opus)
WebM Vorbis (audio/webm; codecs=vorbis)
Ogg Vorbis (audio/ogg; codecs=vorbis)
MPEG-4 AAC (audio/mp4; codecs=mp4a.40.5)
MP3 (audio/mpeg)
FLAC (audio/flac)
PCM WAV (audio/wav; codecs=1)
Supported encode formats:
WebM Opus (audio/webm; codecs=opus)
Video information
Supported decode formats:
WebM AV1 (video/webm; codecs=av01.0.00M.08)
MP4 AV1 (video/mp4; codecs=av01.0.00M.08)
WebM VP9 (video/webm; codecs=vp9)
WebM VP8 (video/webm; codecs=vp8)
H.264 (video/mp4; codecs=avc1.42E01E)
Supported encode formats:
WebM VP9 (video/webm; codecs=vp9)
WebM VP8 (video/webm; codecs=vp8)

</details>
