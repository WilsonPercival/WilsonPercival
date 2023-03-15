## Problem description

Construct crashes.

## Attach a .c3p

save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/10976585/save_open_project.zip)

## Steps to reproduce

1. Create a new project.
2. Create a `Tilemap`.
3. Remove the `Tilemap` instance.
4. Move the `Tilemap Bar` to the center of the screen.
5. Click `Undo`.
6. Allocate the `Tilemap` instance.
7. Click `Redo`.
8. Return the `Tilemap Bar` to its original location.
9. Remove `Tilemap` from the project.
10. Double click on a tile to open the tile editor.
11. Get creative.

## Observed result

https://user-images.githubusercontent.com/91274932/225223054-ad1bd060-4158-4345-a1e9-39f2207675ca.mp4

## Expected result

Construct does not crash.

## More details

Error report information
Type: unhandled rejection
Reason: Error: animation frame has no content @ Error: animation frame has no content at d.qI (https://editor.construct.net/r334/projectResources.js:770:341) at d.la (https://editor.construct.net/r334/projectResources.js:779:6) at d.la (https://editor.construct.net/r334/projectResources.js:702:157) at new SXa.qm (https://editor.construct.net/r334/projectResources.js:1888:427) at $y (https://editor.construct.net/r334/projectResources.js:322:427) at EJa (https://editor.construct.net/r334/projectResources.js:323:32) at Array. (https://editor.construct.net/r334/projectResources.js:407:237) at Dx.g.K.Qb.dispatchEvent (https://editor.construct.net/r334/main.js:1234:42) at Array. (https://editor.construct.net/r334/projectResources.js:2166:295) at H1a.H_a.dispatchEvent (https://editor.construct.net/r334/main.js:1234:42)
Stack: Error: animation frame has no content at d.qI (https://editor.construct.net/r334/projectResources.js:770:341) at d.la (https://editor.construct.net/r334/projectResources.js:779:6) at d.la (https://editor.construct.net/r334/projectResources.js:702:157) at new SXa.qm (https://editor.construct.net/r334/projectResources.js:1888:427) at $y (https://editor.construct.net/r334/projectResources.js:322:427) at EJa (https://editor.construct.net/r334/projectResources.js:323:32) at Array. (https://editor.construct.net/r334/projectResources.js:407:237) at Dx.g.K.Qb.dispatchEvent (https://editor.construct.net/r334/main.js:1234:42) at Array. (https://editor.construct.net/r334/projectResources.js:2166:295) at H1a.H_a.dispatchEvent (https://editor.construct.net/r334/main.js:1234:42)
Construct version: r334
URL: https://editor.construct.net/r334/
Date: Wed Mar 15 2023 07:57:45 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 43 s

Platform information
Product: Construct 3 r334 (beta)
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

**First affected release:** broke in r334b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r334 (beta)
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
Storage usage (approx): 174 mb (0.3%)
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
