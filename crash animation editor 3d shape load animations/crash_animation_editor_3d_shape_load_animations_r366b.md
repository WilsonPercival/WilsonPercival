## Problem description

Construct crashes.

## Attach a .c3p

[crash_animation_editor_3d_shape_load_animations_r366b.zip](https://github.com/WilsonPercival/WilsonPercival/files/13290495/crash_animation_editor_3d_shape_load_animations_r366b.zip)

## Steps to reproduce

1. Open a project.
2. Open the animation editor `3DShape`.
3. Click `Load animations`. A dialog box will open, select the file and click `Open`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/53753028-c928-4603-a35d-c5c5737db8f3

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r366b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of null (reading 'Ax') @ TypeError: Cannot read properties of null (reading 'Ax') at KB (https://editor.construct.net/r366/projectResources.js:273:101) at oO.yma.nub (https://editor.construct.net/r366/projectResources.js:2312:314)
Stack: TypeError: Cannot read properties of null (reading 'Ax') at KB (https://editor.construct.net/r366/projectResources.js:273:101) at oO.yma.nub (https://editor.construct.net/r366/projectResources.js:2312:314)
Construct version: r366
URL: https://editor.construct.net/r366/
Date: Wed Nov 08 2023 02:12:10 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 15.3 s

Platform information
Product: Construct 3 r366 (beta)
Browser: Chrome 119.0.6045.123
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/119.0.0.0 Safari/537.36
Language setting: en-US

WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (AMD)
Renderer: ANGLE (AMD, AMD Radeon(TM) Graphics (0x00001638) Direct3D11 vs_5_0 ps_5_0, D3D11)
Major performance caveat: no
Maximum texture size: 16384
Point size range: 1 to 1024
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_disjoint_timer_query_webgl2, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, EXT_texture_norm16, KHR_parallel_shader_compile, OES_draw_buffers_indexed, OES_texture_float_linear, OVR_multiview2, WEBGL_clip_cull_distance, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw, WEBGL_provoking_vertex

</details>
