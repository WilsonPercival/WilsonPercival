## Problem description

The Сonstruct crashes if you scroll through the expressions.

## Attach a .c3p

[android_scroll_expressions_crash.zip](https://github.com/WilsonPercival/WilsonPercival/files/8491000/android_scroll_expressions_crash.zip)

## Steps to reproduce

1. Create a new project.
2. Create an "evaluate expression" condition.
3. Touch on the "Find Expression" button.
4. Select the "CanvasToLayerX" expression.
5. Repeat the third step.
6. Scroll down.

## Observed result

https://user-images.githubusercontent.com/91274932/163438389-e92ed705-696a-4c47-be56-29d633563409.mp4

Error report information

Type: unhandled exception
File: https://editor.construct.net/r285-3/main.js, line 1462, col 24
Message: Uncaught TypeError: Cannot read properties of null (reading 'removeAttribute')
Stack: TypeError: Cannot read properties of null (reading 'removeAttribute') at Fq.g.I.DX.cq (https://editor.construct.net/r285-3/main.js:1462:24) at HTMLDocument.Uk (https://editor.construct.net/r285-3/main.js:1458:338)
Construct 3 version: r285.3
URL: https://editor.construct.net/
Date: Thu Mar 17 2022 13:12:36 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 124.2 s

Platform information

Browser: Chrome
Browser version: 99.0.4844.58
Browser engine: Chromium
Context: browser
Operating system: Android
Operating system version: 11
Device type: mobile
Device pixel ratio: 1.3312500715255737
Logical CPU cores: 8
Approx. device memory: 2 GB
User agent: Mozilla/5.0 (Linux; Android 11; SM-T500) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/99.0.4844.58 Safari/537.36
C3 release: r285.3 (stable)
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

## Expected result

The crash doesn't happen.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r285-3b and r290b

## System details

<details><summary>View details</summary>

Platform information

Browser: Chrome
Browser version: 99.0.4844.58
Browser engine: Chromium
Context: browser
Operating system: Android
Operating system version: 11
Device type: mobile
Device pixel ratio: 1.3312500715255737
Logical CPU cores: 8
Approx. device memory: 2 GB
User agent: Mozilla/5.0 (Linux; Android 11; SM-T500) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/99.0.4844.58 Safari/537.36
C3 release: r285.3 (stable)
Language setting: en-US

Local storage

Storage quota (approx): 13 gb
Storage usage (approx): 3.3 mb (0%)
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
