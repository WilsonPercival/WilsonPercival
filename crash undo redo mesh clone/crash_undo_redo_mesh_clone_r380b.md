## Problem description

Construct crashes.

## Attach a .c3p

[crash_undo_redo_mesh_clone_r228b.zip](https://github.com/WilsonPercival/WilsonPercival/files/14391942/crash_undo_redo_mesh_clone_r228b.zip)

## Steps to reproduce

1. Open a project.
2. Click on the pig and select `Mesh -> Create mesh...`. A window will open, click `OK`.
3. Make 7 clones of the object (more is better).
4. Hold `Ctrl + Z` until you roll back to the very beginning.
5. Hold `Ctrl + Y` until you return to the very end.
6. If no crash occurs, repeat steps 4 and 5.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/8874d811-d441-4648-abb0-d3ae207f1d99

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** Broke in `r228b` because it was the first version to add a mesh editor.

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r380/plugins/allEditorPlugins.js, line 278, col 108
Message: Uncaught TypeError: Cannot read properties of null (reading 'pg')
Stack: TypeError: Cannot read properties of null (reading 'pg') at TUb.Instance.pg (https://editor.construct.net/r380/plugins/allEditorPlugins.js:278:108) at d.pg (https://editor.construct.net/r380/projectResources.js:884:88) at d.pg (https://editor.construct.net/r380/projectResources.js:1439:488) at d.pg (https://editor.construct.net/r380/projectResources.js:1395:320) at uic (https://editor.construct.net/r380/components/editors/layoutView/layoutView.js:92:303)
Construct version: r380
URL: https://editor.construct.net/r380/
Date: Sat Feb 24 2024 08:03:42 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 23.5 s

Platform information
Product: Construct 3 r380 (beta)
Browser: Chrome 122.0.6261.57
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/122.0.0.0 Safari/537.36
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
Extensions: EXT_clip_control, EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_conservative_depth, EXT_depth_clamp, EXT_disjoint_timer_query_webgl2, EXT_float_blend, EXT_polygon_offset_clamp, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, EXT_texture_norm16, KHR_parallel_shader_compile, NV_shader_noperspective_interpolation, OES_draw_buffers_indexed, OES_texture_float_linear, OVR_multiview2, WEBGL_blend_func_extended, WEBGL_clip_cull_distance, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw, WEBGL_polygon_mode, WEBGL_provoking_vertex

</details>
