## Problem description

Construct crashes.

## Attach a .c3p

save open project: [New project.zip](https://github.com/WilsonPercival/WilsonPercival/files/10777496/New.project.zip)

## Steps to reproduce



## Observed result

https://user-images.githubusercontent.com/91274932/219964257-e90a35eb-d0a5-4e64-817b-0d276bd9b33f.mp4

## Expected result

Construct does not crash.

## More details

Error report information
Type: unhandled exception
File: https://editor.construct.net/r327-2/projectResources.js, line 247, col 197
Message: Uncaught TypeError: Cannot read properties of null (reading 'ya')
Stack: TypeError: Cannot read properties of null (reading 'ya') at WA (https://editor.construct.net/r327-2/projectResources.js:247:197) at https://editor.construct.net/r327-2/projectResources.js:2413:175
Construct version: r327.2
URL: https://editor.construct.net/
Date: Sun Feb 19 2023 18:09:39 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 25.7 s
Platform information
Product: Construct 3 r327.2 (stable)
Browser: Chrome 109.0.5414.118
Browser engine: Chromium
Context: webapp
Operating system: Android 12.0.0
Device type: mobile
Device pixel ratio: 1.3312500715255737
Logical CPU cores: 8
Approx. device memory: 2 GB
User agent: Mozilla/5.0 (Linux; Android 12; SM-T500) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/109.0.0.0 Safari/537.36
Language setting: en-US
WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (Qualcomm)
Renderer: ANGLE (Qualcomm, Adreno (TM) 610, OpenGL ES 3.2)
Major performance caveat: no
Maximum texture size: 4096
Point size range: 1 to 1023
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_float_blend, EXT_texture_filter_anisotropic, EXT_texture_norm16, KHR_parallel_shader_compile, OES_draw_buffers_indexed, OES_texture_float_linear, WEBGL_compressed_texture_astc, WEBGL_compressed_texture_etc, WEBGL_compressed_texture_etc1, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw

**Affected browsers/platforms:** Chrome (Android)

**First affected release:** broke in r327-2s

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r327.2 (stable)
Browser: Chrome 109.0.5414.118
Browser engine: Chromium
Context: webapp
Operating system: Android 12.0.0
Device type: mobile
Device pixel ratio: 1.3312500715255737
Logical CPU cores: 8
Approx. device memory: 2 GB
User agent: Mozilla/5.0 (Linux; Android 12; SM-T500) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/109.0.0.0 Safari/537.36
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
Vendor: Google Inc. (Qualcomm)
Renderer: ANGLE (Qualcomm, Adreno (TM) 610, OpenGL ES 3.2)
Major performance caveat: no
Maximum texture size: 4096
Point size range: 1 to 1023
Extensions:
EXT_color_buffer_float
EXT_color_buffer_half_float
EXT_float_blend
EXT_texture_filter_anisotropic
EXT_texture_norm16
KHR_parallel_shader_compile
OES_draw_buffers_indexed
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
