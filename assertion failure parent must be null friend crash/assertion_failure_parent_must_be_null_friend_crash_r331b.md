## Problem description

Construct crashes.

It seems to me that this crash has the same bug as here: https://github.com/Scirra/Construct-3-bugs/issues/6545

But the repro steps are from this report: https://github.com/Scirra/Construct-3-bugs/issues/6569

I, repeating these steps, catch crash 6569. And my friend, repeating the same steps, catches this crash, which, it seems to me, is similar to 6545. I think it will be useful to you.

## Attach a .c3p

No.

## Steps to reproduce

Same as here: https://github.com/Scirra/Construct-3-bugs/issues/6569

## Observed result

https://user-images.githubusercontent.com/91274932/220425615-bb183494-535c-4e14-8c48-c3d095bda86a.mp4

## Expected result

Construct does not crash.

## More details

Error report information
Type: assertion failure
Message: _parent must be null
Stack: Error at qa.GWa (https://editor.construct.net/r331/main.js:1105:289) at window.assert (https://editor.construct.net/r331/main.js:1020:353) at ffa (https://editor.construct.net/r331/main.js:281:311) at Xx.g.K.iSc.xb (https://editor.construct.net/r331/main.js:1363:28) at https://editor.construct.net/r331/projectResources.js:2493:346 at https://editor.construct.net/r331/projectResources.js:10:487 at new Promise () at Vt (https://editor.construct.net/r331/projectResources.js:10:442) at https://editor.construct.net/r331/projectResources.js:2493:333
Construct version: r331
URL: https://editor.construct.net/r331/
Date: Tue Feb 21 2023 22:03:25 GMT+0400 (Самарское стандартное время)
Uptime: 11.8 s

Platform information
Product: Construct 3 r331 (beta)
Browser: Chrome 110.0.5481.104
Browser engine: Chromium
Context: webapp
Operating system: Windows 10
Device type: desktop
Device pixel ratio: 1.25
Logical CPU cores: 12
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/110.0.0.0 Safari/537.36
Language setting: en-US

WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: yes
Supports highp precision: yes
Vendor: Google Inc. (NVIDIA Corporation)
Renderer: ANGLE (NVIDIA Corporation, NVIDIA GeForce GTX 1650/PCIe/SSE2, OpenGL 4.5.0)
Major performance caveat: no
Maximum texture size: 32768
Point size range: 1 to 2047
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_disjoint_timer_query_webgl2, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, EXT_texture_norm16, KHR_parallel_shader_compile, OES_draw_buffers_indexed, OES_texture_float_linear, OVR_multiview2, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r331b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r331 (beta)
Browser: Chrome 110.0.5481.104
Browser engine: Chromium
Context: webapp
Operating system: Windows 10
Device type: desktop
Device pixel ratio: 1.25
Logical CPU cores: 12
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/110.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 286 gb
Storage usage (approx): 66 mb (0%)
Persistant storage: Yes

Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.

Nothing is missing. Everything is OK!
WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: yes
Supports highp precision: yes
Vendor: Google Inc. (NVIDIA Corporation)
Renderer: ANGLE (NVIDIA Corporation, NVIDIA GeForce GTX 1650/PCIe/SSE2, OpenGL 4.5.0)
Major performance caveat: no
Maximum texture size: 32768
Point size range: 1 to 2047
Extensions:

EXT_color_buffer_float
EXT_color_buffer_half_float
EXT_disjoint_timer_query_webgl2
EXT_float_blend
EXT_texture_compression_bptc
EXT_texture_compression_rgtc
EXT_texture_filter_anisotropic
EXT_texture_norm16
KHR_parallel_shader_compile
OES_draw_buffers_indexed
OES_texture_float_linear
OVR_multiview2
WEBGL_compressed_texture_s3tc
WEBGL_compressed_texture_s3tc_srgb
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
Ogg Theora (video/ogg; codecs=theora)
H.264 (video/mp4; codecs=avc1.42E01E)
Supported encode formats:

WebM VP9 (video/webm; codecs=vp9)
WebM VP8 (video/webm; codecs=vp8)

</details>
