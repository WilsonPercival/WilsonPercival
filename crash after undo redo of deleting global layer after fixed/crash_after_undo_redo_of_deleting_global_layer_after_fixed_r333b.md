## Problem description

Construct crashes. I have already reported this: https://github.com/Scirra/Construct-bugs/issues/6621

## Attach a .c3p

[steal_the_astral_book_crash_r331b.zip](https://github.com/WilsonPercival/WilsonPercival/files/10940994/steal_the_astral_book_crash_r331b.zip)

## Steps to reproduce

1. Open a project.
2. On `Layout 2`: create a sprite on `Layer 1`.
3. On `Layout 1`: delete `Layer 1`.
4. Click `Undo`.
5. Select the sprite.
6. Click `Redo`.
7. Go to `Layout 2`.
8. Go to `Layout 1`.
9. Go to `Layout 2`.

## Observed result

https://user-images.githubusercontent.com/91274932/224289989-b6020d05-662e-4cfe-a5ad-2780eebf77da.mp4

## Expected result

Construct does not crash.

## More details

Error report information
Type: unhandled exception
File: https://editor.construct.net/r333/projectResources.js, line 1359, col 345
Message: Uncaught Error: instance not on this layer
Stack: Error: instance not on this layer at d.dpc (https://editor.construct.net/r333/projectResources.js:1359:351) at d.ckb (https://editor.construct.net/r333/projectResources.js:810:395) at https://editor.construct.net/r333/components/bars/propertiesBar/propertiesBar.js:18:424 at ah (https://editor.construct.net/r333/main.js:369:492) at tq.g.K.Veb.tX (https://editor.construct.net/r333/main.js:1530:418) at tq.g.K.Veb.cG (https://editor.construct.net/r333/main.js:1531:71) at HTMLSelectElement.Qs (https://editor.construct.net/r333/main.js:1529:343)
Construct version: r333
URL: https://editor.construct.net/r333/
Date: Fri Mar 10 2023 12:04:53 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 75.6 s

Platform information
Product: Construct 3 r333 (beta)
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

![overclocking](https://user-images.githubusercontent.com/91274932/224290142-63bc0864-beca-4604-8d52-a17fca4b2634.gif)

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r333b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r333 (beta)
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
Storage usage (approx): 144 mb (0.2%)
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
