## Problem description

Construct crashes.

## Attach a .c3p

[unhandled_exception_layers_crash_r329b_easy.zip](https://github.com/WilsonPercival/WilsonPercival/files/10852386/unhandled_exception_layers_crash_r329b_easy.zip)

save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/10852387/save_open_project.zip)

## Steps to reproduce



## Observed result

https://user-images.githubusercontent.com/91274932/221910771-10548e1f-3f7a-4c89-9170-d982f511c7b7.mp4

## Expected result

Construct does not crash.

## More details

Error report information
Type: unhandled exception
File: https://editor.construct.net/r332/projectResources.js, line 1377, col 146
Message: Uncaught Error: layer name 'Layer 1' already used
Stack: Error: layer name 'Layer 1' already used at window.zjb.dVa (https://editor.construct.net/r332/projectResources.js:1377:152) at d.pAc (https://editor.construct.net/r332/projectResources.js:1342:266) at window.Ajb.mla (https://editor.construct.net/r332/components/bars/layersBar/layersBar.js:17:175) at Array. (https://editor.construct.net/r332/components/bars/layersBar/layersBar.js:6:411) at CCG.oh.g.K.UJa.dispatchEvent (https://editor.construct.net/r332/main.js:1233:399) at rh (https://editor.construct.net/r332/main.js:377:372) at d.Fd (https://editor.construct.net/r332/main.js:1617:1) at Vb.je (https://editor.construct.net/r332/main.js:1608:89)
Construct version: r332
URL: https://editor.construct.net/r332/
Date: Tue Feb 28 2023 18:01:18 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 56.6 s

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

https://user-images.githubusercontent.com/91274932/221910212-e6c57faf-ab56-4392-9d31-20b708ed83a3.mp4

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r331b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r331 (beta)
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
Storage usage (approx): 198 mb (0.3%)
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
