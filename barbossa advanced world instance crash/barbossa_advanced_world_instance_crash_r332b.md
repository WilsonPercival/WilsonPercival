## Problem description

Construct crashes.

## Attach a .c3p

save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/10887370/save_open_project.zip)

## Steps to reproduce

1. Create a new project.
2. Create a `3D shape`.
3. Hold down Ctrl.
4. Step on the sprite with the mouse. Do not release the clamp.
5. Press `Z`. Note that the layout instance no longer exists.
6. Drag the mouse.

## Observed result

https://user-images.githubusercontent.com/91274932/222873771-9cf829e2-b0c7-4be4-812c-651d450db368.mp4

## Expected result

Construct does not crash.

## More details

Error report information
Type: unhandled exception
File: https://editor.construct.net/r332/components/editors/layoutView/layoutView.js, line 211, col 444
Message: Uncaught Error: cannot unselect inactive instance
Stack: Error: cannot unselect inactive instance at Lbb.HIa (https://editor.construct.net/r332/components/editors/layoutView/layoutView.js:211:450) at Qbb.Sf (https://editor.construct.net/r332/components/editors/layoutView/layoutView.js:229:324) at Qbb.sf (https://editor.construct.net/r332/components/editors/layoutView/layoutView.js:225:291) at window.Nl.dispatchEvent (https://editor.construct.net/r332/main.js:1233:399) at window.Nl.Sf (https://editor.construct.net/r332/components/editors/layoutView/layoutView.js:109:253) at HTMLDocument.sf (https://editor.construct.net/r332/components/editors/layoutView/layoutView.js:92:435)
Construct version: r332
URL: https://editor.construct.net/r332/
Date: Sat Mar 04 2023 05:18:27 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 79.7 s

Platform information
Product: Construct 3 r332 (beta)
Browser: Chrome 109.0.5414.120
Browser engine: Chromium
Context: browser
Operating system: Windows NT 0.1.0
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/109.0.0.0 Safari/537.36
Language setting: en-US

WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (Google)
Renderer: ANGLE (Google, Vulkan 1.3.0 (SwiftShader Device (Subzero) (0x0000C0DE)), SwiftShader driver)
Major performance caveat: yes
Maximum texture size: 8192
Point size range: 1 to 1023
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, OES_draw_buffers_indexed, OES_texture_float_linear, WEBGL_compressed_texture_astc, WEBGL_compressed_texture_etc, WEBGL_compressed_texture_etc1, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_lose_context, WEBGL_multi_draw, OVR_multiview2

![puuuuuull](https://user-images.githubusercontent.com/91274932/222873777-022c4d30-6c2f-429e-95eb-e90f082b6a11.png)

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r332b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r332 (beta)
Browser: Chrome 109.0.5414.120
Browser engine: Chromium
Context: browser
Operating system: Windows NT 0.1.0
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/109.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 59 gb
Storage usage (approx): 253 mb (0.4%)
Persistant storage: No

Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.

UI effects are disabled in settings.
WebGL indicates a major performance caveat. It is probably using software rendering.
WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (Google)
Renderer: ANGLE (Google, Vulkan 1.3.0 (SwiftShader Device (Subzero) (0x0000C0DE)), SwiftShader driver)
Major performance caveat: yes
Maximum texture size: 8192
Point size range: 1 to 1023
Extensions:

EXT_color_buffer_float
EXT_color_buffer_half_float
EXT_float_blend
EXT_texture_compression_bptc
EXT_texture_compression_rgtc
EXT_texture_filter_anisotropic
OES_draw_buffers_indexed
OES_texture_float_linear
WEBGL_compressed_texture_astc
WEBGL_compressed_texture_etc
WEBGL_compressed_texture_etc1
WEBGL_compressed_texture_s3tc
WEBGL_compressed_texture_s3tc_srgb
WEBGL_debug_renderer_info
WEBGL_lose_context
WEBGL_multi_draw
OVR_multiview2
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
Ogg Theora (video/ogg; codecs=theora)
H.264 (video/mp4; codecs=avc1.42E01E)
Supported encode formats:

WebM VP9 (video/webm; codecs=vp9)
WebM VP8 (video/webm; codecs=vp8)

</details>
