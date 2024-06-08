## Problem description

Text looks bad on a tablet. Please note that the text looks fine on a computer. The text also looks good on the phone. Only one of my devices looks bad.

## Attach a .c3p

[text_bbcode_outline_android_bug_r115b.zip](https://github.com/user-attachments/files/15747759/text_bbcode_outline_android_bug_r115b.zip)

## Steps to reproduce

1. Open and run the project.

## Observed result

<img width="600" alt="observed" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/676246f5-db02-4098-a11d-99be0417fa4b">

## Expected result

<img width="445" alt="windows" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/5e24f19d-5d3a-45fb-a7c8-674745b4778d">

## More details



**Affected browsers/platforms:** Chrome (Android)

**First affected release:** Broke in `r115b` because it was the first version to add `C3 runtime` and make it possible to use `Text` with `BBCode`.

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r379 (stable)
Browser: Chrome 125.0.6422.165
Browser engine: Chromium
Context: webapp
Operating system: Android 12.0.0
Device type: mobile
Device pixel ratio: 1.3312500715255737
Logical CPU cores: 8
Approx. device memory: 2 GB
User agent: Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/125.0.0.0 Safari/537.36
Language setting: en-US
Local storage
Storage quota (approx): 13 gb
Storage usage (approx): 33 mb (0.2%)
Persistant storage: No
Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.
UI effects are disabled in settings.
WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Qualcomm
Renderer: Adreno (TM) 610
Major performance caveat: no
Maximum texture size: 4096
Point size range: 1 to 1023
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
System sample rate: 48000 Hz
Output channels: 2
Output interpretation: speakers
Supported decode formats:
WebM Opus (audio/webm;codecs=opus)
WebM Vorbis (audio/webm;codecs=vorbis)
MPEG-4 Opus (audio/mp4;codecs=opus)
MPEG-4 AAC (audio/mp4;codecs=mp4a.40.2)
MP3 (audio/mpeg)
FLAC (audio/flac)
PCM WAV (audio/wav;codecs=1)
Supported encode formats:
WebM Opus (audio/webm;codecs=opus)
Video information
Supported decode formats:
WebM AV1 (video/webm;codecs=av01.0.00M.08)
WebM VP9 (video/webm;codecs=vp9)
WebM VP8 (video/webm;codecs=vp8)
MPEG-4 AV1 (video/mp4;codecs=av01.0.00M.08)
MPEG-4 H.265 (video/mp4;codecs=hev1.1.2.L93.B0)
MPEG-4 H.264 (video/mp4;codecs=avc1.420034)
Supported encode formats:
WebM VP9 (video/webm;codecs=vp9)
WebM VP8 (video/webm;codecs=vp8)
WebM H.264 (video/webm;codecs=avc1.420034)

</details>
