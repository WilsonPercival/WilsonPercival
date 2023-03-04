## Problem description

Construct crashes.

## Attach a .c3p

[Dormammu I have come to bargain.zip](https://github.com/WilsonPercival/WilsonPercival/files/10889815/Dormammu.I.have.come.to.bargain.zip)

## Steps to reproduce

1. Open a project.
2. Select the sprite on the left.
3. Hold down `Ctrl`.
4. Select the sprite on the right with the right button and click `Hierarchy -> Add selection to this instance`.

## Observed result

https://user-images.githubusercontent.com/91274932/222931860-47001c6b-1360-43d3-95cd-17b44b4d9946.mp4

## Expected result

Construct does not crash.

## More details

Error report information
Type: unhandled exception
File: https://editor.construct.net/r332/projectResources.js, line 818, col 290
Message: Uncaught RangeError: Maximum call stack size exceeded
Stack: RangeError: Maximum call stack size exceeded at d.FH (https://editor.construct.net/r332/projectResources.js:818:290) at d.bba (https://editor.construct.net/r332/projectResources.js:825:265) at DOb.Instance.OEc (https://editor.construct.net/r332/plugins/allEditorPlugins.js:228:463) at DOb.Instance.yCa (https://editor.construct.net/r332/plugins/allEditorPlugins.js:223:263) at DOb.Instance.Hpa (https://editor.construct.net/r332/plugins/allEditorPlugins.js:223:381) at Array. (https://editor.construct.net/r332/plugins/allEditorPlugins.js:226:149) at d.dispatchEvent (https://editor.construct.net/r332/main.js:1234:42) at d.xz (https://editor.construct.net/r332/projectResources.js:782:485) at d.pf (https://editor.construct.net/r332/projectResources.js:803:236) at d.pf (https://editor.construct.net/r332/projectResources.js:803:277)
Construct version: r332
URL: https://editor.construct.net/r332/
Date: Sat Mar 04 2023 23:45:30 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 25.8 s

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

https://user-images.githubusercontent.com/91274932/222931887-79730427-825f-43f1-8d5a-f976a5dfd86f.mp4

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
