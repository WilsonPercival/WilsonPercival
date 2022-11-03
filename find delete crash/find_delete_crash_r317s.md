## Problem description

I am working in Construct and getting a crash.

## Attach a .c3p

[save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/9931358/save_open_project.zip)

## Steps to reproduce

1. Create a new project.
2. Add a global variable.
3. Create 25 `System evaluate: Variable1` events.
4. Click search.
5. Enter a variable name.
6. Double click on the first found value and delete it.
7. Repeat the previous paragraph.

## Observed result

https://user-images.githubusercontent.com/91274932/199784625-60b56b92-9a3d-4f96-91b7-b3b99f64231b.mp4

## Expected result

No crash.

## More details

Error report information
Type: assertion failure
Message: cannot select detached view
Stack: Error at ta.OTa (https://editor.construct.net/r317/main.js:973:289) at window.assert (https://editor.construct.net/r317/main.js:889:353) at d.$n (https://editor.construct.net/r317/components/editors/eventSheetView/eventSheetView.js:169:185) at d.Xe (https://editor.construct.net/r317/components/editors/eventSheetView/eventSheetView.js:166:291) at d.Ax (https://editor.construct.net/r317/components/editors/eventSheetView/eventSheetView.js:168:81) at window.ycb.Nja (https://editor.construct.net/r317/components/bars/findResultsBar/findResultsBar.js:13:469)
Construct version: r317
URL: https://editor.construct.net/
Date: Thu Nov 03 2022 18:48:09 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 78.3 s

Platform information
Product: Construct 3 r317 (stable)
Browser: Chrome 107.0.5304.88
Browser engine: Chromium
Context: webapp
Operating system: Windows NT 0.1.0
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/107.0.0.0 Safari/537.36
Language setting: en-US

WebGL information
Version string: WebGL 1.0 (OpenGL ES 2.0 Chromium)
Numeric version: 1
Supports NPOT textures: partial
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (Intel)
Renderer: ANGLE (Intel, Intel(R) HD Graphics Direct3D9Ex vs_3_0 ps_3_0, igdumdim64.dll)
Major performance caveat: no
Maximum texture size: 8192
Point size range: 1 to 256
Extensions: ANGLE_instanced_arrays, EXT_blend_minmax, EXT_color_buffer_half_float, EXT_float_blend, EXT_frag_depth, EXT_shader_texture_lod, EXT_texture_filter_anisotropic, EXT_sRGB, KHR_parallel_shader_compile, OES_element_index_uint, OES_fbo_render_mipmap, OES_standard_derivatives, OES_texture_float, OES_texture_float_linear, OES_texture_half_float, OES_texture_half_float_linear, OES_vertex_array_object, WEBGL_color_buffer_float, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_depth_texture, WEBGL_lose_context, WEBGL_multi_draw

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r317s

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r317 (stable)
Browser: Chrome 107.0.5304.88
Browser engine: Chromium
Context: browser
Operating system: Windows NT 0.1.0
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/107.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 59 gb
Storage usage (approx): 87 mb (0.1%)
Persistant storage: No

Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.

UI effects are disabled in settings.
WebGL 2+ is not supported. Rendering quality and features may be affected.
WebGL information
Version string: WebGL 1.0 (OpenGL ES 2.0 Chromium)
Numeric version: 1
Supports NPOT textures: partial
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (Intel)
Renderer: ANGLE (Intel, Intel(R) HD Graphics Direct3D9Ex vs_3_0 ps_3_0, igdumdim64.dll)
Major performance caveat: no
Maximum texture size: 8192
Point size range: 1 to 256
Extensions:

ANGLE_instanced_arrays
EXT_blend_minmax
EXT_color_buffer_half_float
EXT_float_blend
EXT_frag_depth
EXT_shader_texture_lod
EXT_texture_filter_anisotropic
EXT_sRGB
KHR_parallel_shader_compile
OES_element_index_uint
OES_fbo_render_mipmap
OES_standard_derivatives
OES_texture_float
OES_texture_float_linear
OES_texture_half_float
OES_texture_half_float_linear
OES_vertex_array_object
WEBGL_color_buffer_float
WEBGL_compressed_texture_s3tc
WEBGL_compressed_texture_s3tc_srgb
WEBGL_debug_renderer_info
WEBGL_debug_shaders
WEBGL_depth_texture
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
