## Problem description

Construct crashes when importing scripts like Flash :zap:

## Attach a .c3p

Save project before crash: [fast_import_scripts_bug_r302s.zip](https://github.com/WilsonPercival/WilsonPercival/files/9146269/fast_import_scripts_bug_r302s.zip)

Folder with my scripts: https://www.dropbox.com/sh/j5s4d0g0urho5r9/AABwQF6IDBSStxohISTqDXwKa?dl=1

## Steps to reproduce



## Observed result

![bug](https://user-images.githubusercontent.com/91274932/179891121-97dd88d5-e007-43f2-8a7c-573af6eae4c4.gif)

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r302s

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: no changes given @ Error: no changes given at new NYa.xCb (https://editor.construct.net/r302/projectResources.js:1823:74) at dbb (https://editor.construct.net/r302/components/bars/projectBar/projectBar.js:61:180) at https://editor.construct.net/r302/components/bars/projectBar/projectBar.js:60:409
Stack: Error: no changes given at new NYa.xCb (https://editor.construct.net/r302/projectResources.js:1823:74) at dbb (https://editor.construct.net/r302/components/bars/projectBar/projectBar.js:61:180) at https://editor.construct.net/r302/components/bars/projectBar/projectBar.js:60:409
Construct version: r302
URL: https://editor.construct.net/
Date: Wed Jul 20 2022 06:19:41 GMT+0300 (Восточная Европа, летнее время)
Uptime: 131.2 s

Platform information
Product: Construct 3 r302 (stable)
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

</details>
