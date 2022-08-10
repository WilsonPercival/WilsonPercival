## Problem description

Construct crashes when I change the name of the animation.

## Attach a .c3p

[change_animation_name_bug_r305b.zip](https://github.com/WilsonPercival/WilsonPercival/files/9304551/change_animation_name_bug_r305b.zip)

## Steps to reproduce

1. Create a new project.
2. Create a sprite.
3. Change the name of the animation.

## Observed result

![bug](https://user-images.githubusercontent.com/91274932/184035965-49516dd9-d422-4b72-9418-321d4f897ce4.gif)

## Expected result

Like the good old ones.

## More details

Error report information
Type: unhandled exception
File: https://editor.construct.net/r305/main.js, line 900, col 29
Message: Uncaught TypeError: expected string
Stack: TypeError: expected string at P.l (https://editor.construct.net/r305/main.js:900:35) at https://editor.construct.net/r305/projectResources.js:1910:491 at bh (https://editor.construct.net/r305/main.js:368:408) at CCG.Sg.g.J.xeb.PV (https://editor.construct.net/r305/main.js:1356:225) at CCG.Sg.g.J.xeb.ME (https://editor.construct.net/r305/main.js:1365:445) at HTMLInputElement.Ur (https://editor.construct.net/r305/main.js:1350:303) at CCG.Sg.g.J.xeb.Vd (https://editor.construct.net/r305/main.js:1368:131) at HTMLInputElement.mD (https://editor.construct.net/r305/main.js:1354:400)
Construct version: r305
URL: https://editor.construct.net/r305/
Date: Thu Aug 11 2022 01:47:05 GMT+0300 (Восточная Европа, летнее время)
Uptime: 17.8 s

Platform information
Product: Construct 3 r305 (beta)
Browser: Chrome 103.0.5060.114
Browser engine: Chromium
Context: browser
Operating system: Windows NT 0.1.0
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/103.0.0.0 Safari/537.36
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
Extensions: ANGLE_instanced_arrays, EXT_blend_minmax, EXT_color_buffer_half_float, EXT_float_blend, EXT_frag_depth, EXT_shader_texture_lod, EXT_texture_filter_anisotropic, WEBKIT_EXT_texture_filter_anisotropic, EXT_sRGB, KHR_parallel_shader_compile, OES_element_index_uint, OES_fbo_render_mipmap, OES_standard_derivatives, OES_texture_float, OES_texture_float_linear, OES_texture_half_float, OES_texture_half_float_linear, OES_vertex_array_object, WEBGL_color_buffer_float, WEBGL_compressed_texture_s3tc, WEBKIT_WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_depth_texture, WEBKIT_WEBGL_depth_texture, WEBGL_lose_context, WEBKIT_WEBGL_lose_context, WEBGL_multi_draw

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r305b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r305 (beta)
Browser: Chrome 103.0.5060.114
Browser engine: Chromium
Context: browser
Operating system: Windows NT 0.1.0
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/103.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 59 gb
Storage usage (approx): 342 mb (0.6%)
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
WEBKIT_EXT_texture_filter_anisotropic
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
WEBKIT_WEBGL_compressed_texture_s3tc
WEBGL_compressed_texture_s3tc_srgb
WEBGL_debug_renderer_info
WEBGL_debug_shaders
WEBGL_depth_texture
WEBKIT_WEBGL_depth_texture
WEBGL_lose_context
WEBKIT_WEBGL_lose_context
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
