## Problem description

After renaming the object - Construct crashes.

## Attach a .c3p

https://www.dropbox.com/s/lxbznii1foy0laj/a50.c3p?dl=1

Save open project after crash: https://www.dropbox.com/s/36728hgfmvl6pgh/save_open_project.c3p?dl=1

## Steps to reproduce

1. Open a project.
2. Start making object clones. Tilt approximately 40-50 copies. I needed to make 38 copies.
3. Rename one of the objects.

## Observed result

![bug](https://user-images.githubusercontent.com/91274932/192295917-1468e773-df9e-43e7-a00b-3608fc098f4e.gif)

## Expected result

Construct does not crash, why all of a sudden.

## More details

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of null (reading 'xq') @ TypeError: Cannot read properties of null (reading 'xq') at d.Ye (https://editor.construct.net/r308-2/main.js:1471:495) at d.S2 (https://editor.construct.net/r308-2/main.js:1477:6) at jV (https://editor.construct.net/r308-2/components/bars/projectBar/projectBar.js:7:49) at https://editor.construct.net/r308-2/components/bars/projectBar/projectBar.js:21:114 at https://editor.construct.net/r308-2/main.js:1723:100
Stack: TypeError: Cannot read properties of null (reading 'xq') at d.Ye (https://editor.construct.net/r308-2/main.js:1471:495) at d.S2 (https://editor.construct.net/r308-2/main.js:1477:6) at jV (https://editor.construct.net/r308-2/components/bars/projectBar/projectBar.js:7:49) at https://editor.construct.net/r308-2/components/bars/projectBar/projectBar.js:21:114 at https://editor.construct.net/r308-2/main.js:1723:100
Construct version: r308.2
URL: https://editor.construct.net/
Date: Mon Sep 26 2022 16:50:44 GMT+0300 (Восточная Европа, летнее время)
Uptime: 109.8 s

Platform information
Product: Construct 3 r308.2 (stable)
Browser: Chrome 105.0.5195.54
Browser engine: Chromium
Context: browser
Operating system: Windows NT 0.1.0
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/105.0.0.0 Safari/537.36
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

**First affected release:** broke in r308-2s

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r308.2 (stable)
Browser: Chrome 105.0.5195.54
Browser engine: Chromium
Context: browser
Operating system: Windows NT 0.1.0
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/105.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 59 gb
Storage usage (approx): 673 mb (1.1%)
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
