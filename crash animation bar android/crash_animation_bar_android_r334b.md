## Problem description

Construct crashes. I have already reported this: https://github.com/Scirra/Construct-bugs/issues/6585

## Attach a .c3p

save open project: [New project.zip](https://github.com/WilsonPercival/WilsonPercival/files/10998970/New.project.zip)

## Steps to reproduce

1. Create a new project.
2. Add 3D shape.
3. Pull the right ear and slide the animation panel all the way out.
4. Click on the animation bar.

## Observed result

https://user-images.githubusercontent.com/91274932/225843170-200453f5-33cb-47ef-9ade-6067afb944d9.mp4

## Expected result

Construct does not crash.

## More details

Error report information
Type: assertion failure
Message: no matching icon view item for animation frame
Stack: Error at qa.bXa (https://editor.construct.net/r334/main.js:1104:289) at window.assert (https://editor.construct.net/r334/main.js:1019:353) at yB (https://editor.construct.net/r334/projectResources.js:292:261) at https://editor.construct.net/r334/projectResources.js:2482:375
Construct version: r334
URL: https://editor.construct.net/r334/
Date: Fri Mar 17 2023 09:33:34 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 15 s
Platform information
Product: Construct 3 r334 (beta)
Browser: Chrome 111.0.5563.58
Browser engine: Chromium
Context: browser
Operating system: Android 12.0.0
Device type: mobile
Device pixel ratio: 1.3312500715255737
Logical CPU cores: 8
Approx. device memory: 2 GB
User agent: Mozilla/5.0 (Linux; Android 12; SM-T500) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/111.0.0.0 Safari/537.36
Language setting: en-US
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
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_float_blend, EXT_texture_filter_anisotropic, EXT_texture_norm16, OES_texture_float_linear, WEBGL_compressed_texture_astc, WEBGL_compressed_texture_etc, WEBGL_compressed_texture_etc1, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw

**Affected browsers/platforms:** Chrome (Android)

**First affected release:** broke in r334b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r334 (beta)
Browser: Chrome 111.0.5563.58
Browser engine: Chromium
Context: browser
Operating system: Android 12.0.0
Device type: mobile
Device pixel ratio: 1.3312500715255737
Logical CPU cores: 8
Approx. device memory: 2 GB
User agent: Mozilla/5.0 (Linux; Android 12; SM-T500) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/111.0.0.0 Safari/537.36
Language setting: en-US
Local storage
Storage quota (approx): 13 gb
Storage usage (approx): 25 mb (0.2%)
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
H.265 (video/mp4; codecs=hev1.1.2.L93.B0)
H.264 (video/mp4; codecs=avc1.42E01E)
Supported encode formats:
WebM VP9 (video/webm; codecs=vp9)
WebM VP8 (video/webm; codecs=vp8)

</details>
