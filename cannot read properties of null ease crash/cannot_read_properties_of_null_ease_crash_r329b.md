## Problem description

Construct crashes.

## Attach a .c3p

save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/10714227/save_open_project.zip)

## Steps to reproduce

1. Create a new project.
2. Create ease.
3. Move the point.
4. Click `Undo`.
5. Click `Redo`.
6. Click `Undo`.
7. Exit the editor.
8. Click `Redo`.

## Observed result

https://user-images.githubusercontent.com/91274932/218270817-18d7fe63-63f0-4564-9db3-33de8e58ff75.mp4

## Expected result

Construct does not crash.

## More details

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of null (reading 'innerWidth') @ TypeError: Cannot read properties of null (reading 'innerWidth') at $ia (https://editor.construct.net/r329/main.js:427:235) at aja (https://editor.construct.net/r329/main.js:425:325) at new Xi.g.Notification (https://editor.construct.net/r329/main.js:1903:467) at qa.j (https://editor.construct.net/r329/main.js:1111:44) at Xi.g.Notification.Oa (https://editor.construct.net/r329/main.js:1906:243) at window.ceb.fj (https://editor.construct.net/r329/main.js:2508:325)
Stack: TypeError: Cannot read properties of null (reading 'innerWidth') at $ia (https://editor.construct.net/r329/main.js:427:235) at aja (https://editor.construct.net/r329/main.js:425:325) at new Xi.g.Notification (https://editor.construct.net/r329/main.js:1903:467) at qa.j (https://editor.construct.net/r329/main.js:1111:44) at Xi.g.Notification.Oa (https://editor.construct.net/r329/main.js:1906:243) at window.ceb.fj (https://editor.construct.net/r329/main.js:2508:325)
Construct version: r329
URL: https://editor.construct.net/r329/
Date: Sat Feb 11 2023 18:52:24 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 63.5 s

Platform information
Product: Construct 3 r329 (beta)
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

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r329b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r329 (beta)
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
Storage usage (approx): 167 mb (0.3%)
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
