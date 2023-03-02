## Problem description

Construct crashes.

## Attach a .c3p

save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/10866725/save_open_project.zip)

## Steps to reproduce

1. Create a new project.
2. Create a tilemap.
3. Detach the `Tilemap bar`.
4. Click `Open to popup window`.
5. Click the `Save tilemap to ZIP file` button.
6. Drag the downloaded archive onto the `Tilemap bar` and press `Ctrl + Z` (this should be fast, almost instantaneous). Note that the tilemap instance does not exist in the layout editor. At the same time, the tiles are drawn in the `Tilemap bar`. It's time to move on to the next item.
7. Remove the tilemap from the project.
8. Double click on a tile to open the tile editor.
9. Get creative.

## Observed result

https://user-images.githubusercontent.com/91274932/222306729-00f5d3c1-03b6-4a8b-9f94-ce56a77901a9.mp4

## Expected result

Construct does not crash.

## More details

Error report information
Type: unhandled rejection
Reason: Error: animation frame has no content @ Error: animation frame has no content at d.mI (https://editor.construct.net/r332/projectResources.js:765:341) at d.la (https://editor.construct.net/r332/projectResources.js:774:6) at d.la (https://editor.construct.net/r332/projectResources.js:699:157) at new PXa.Hm (https://editor.construct.net/r332/projectResources.js:1881:427) at $y (https://editor.construct.net/r332/projectResources.js:319:427) at BJa (https://editor.construct.net/r332/projectResources.js:320:32) at Array. (https://editor.construct.net/r332/projectResources.js:404:237) at Dx.g.K.Pb.dispatchEvent (https://editor.construct.net/r332/main.js:1234:42) at Array. (https://editor.construct.net/r332/projectResources.js:2158:295) at z1a.GVa.dispatchEvent (https://editor.construct.net/r332/main.js:1234:42)
Stack: Error: animation frame has no content at d.mI (https://editor.construct.net/r332/projectResources.js:765:341) at d.la (https://editor.construct.net/r332/projectResources.js:774:6) at d.la (https://editor.construct.net/r332/projectResources.js:699:157) at new PXa.Hm (https://editor.construct.net/r332/projectResources.js:1881:427) at $y (https://editor.construct.net/r332/projectResources.js:319:427) at BJa (https://editor.construct.net/r332/projectResources.js:320:32) at Array. (https://editor.construct.net/r332/projectResources.js:404:237) at Dx.g.K.Pb.dispatchEvent (https://editor.construct.net/r332/main.js:1234:42) at Array. (https://editor.construct.net/r332/projectResources.js:2158:295) at z1a.GVa.dispatchEvent (https://editor.construct.net/r332/main.js:1234:42)
Construct version: r332
URL: https://editor.construct.net/r332/
Date: Thu Mar 02 2023 02:40:08 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 94.8 s

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
