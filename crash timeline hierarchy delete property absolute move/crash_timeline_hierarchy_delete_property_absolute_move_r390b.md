## Problem description

Construct crashes.

Please note that the `Result mode` parameter is set to `Absolute`. Also included is the `Auto keyframes (A)` button.

## Attach a .c3p

[crash_timeline_hierarchy_delete_property_absolute_move_r345b.zip](https://github.com/WilsonPercival/WilsonPercival/files/15285571/crash_timeline_hierarchy_delete_property_absolute_move_r345b.zip)

## Steps to reproduce

1. Open a project.
2. Click `Editing mode (E)`.
3. Remove the `X` property from the child sprite.
4. Move the child sprite.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/8c73d17d-e179-49f3-97e6-559969dbfd55

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** Worked in `r345b`, broke in `r346b`.

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r390/projectResources.js, line 1280, col 298
Message: Uncaught TypeError: Cannot read properties of undefined (reading 'tc')
Stack: TypeError: Cannot read properties of undefined (reading 'tc') at pI.wI (https://editor.construct.net/r390/projectResources.js:1280:298) at kEa (https://editor.construct.net/r390/projectResources.js:110:203) at pI.P$ (https://editor.construct.net/r390/projectResources.js:1283:148) at d.P$ (https://editor.construct.net/r390/projectResources.js:1248:282) at d.k6 (https://editor.construct.net/r390/projectResources.js:1160:151) at d.WNc (https://editor.construct.net/r390/projectResources.js:1162:442) at d.nTa (https://editor.construct.net/r390/projectResources.js:1158:64) at d.gXb (https://editor.construct.net/r390/projectResources.js:1075:412) at https://editor.construct.net/r390/components/bars/timelineBar/timelineBar.js:219:156 at o2.MNc (https://editor.construct.net/r390/components/bars/timelineBar/timelineBar.js:219:290)
Construct version: r390
URL: https://editor.construct.net/r390/
Date: Sun May 12 2024 11:22:50 GMT+0300 (Восточная Европа, летнее время)
Uptime: 22 s

Platform information
Product: Construct 3 r390 (beta)
Browser: Chrome 124.0.6367.158
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/124.0.0.0 Safari/537.36
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
Extensions: EXT_clip_control, EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_conservative_depth, EXT_depth_clamp, EXT_disjoint_timer_query_webgl2, EXT_float_blend, EXT_polygon_offset_clamp, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, EXT_texture_mirror_clamp_to_edge, EXT_texture_norm16, KHR_parallel_shader_compile, NV_shader_noperspective_interpolation, OES_draw_buffers_indexed, OES_texture_float_linear, OVR_multiview2, WEBGL_blend_func_extended, WEBGL_clip_cull_distance, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw, WEBGL_polygon_mode, WEBGL_provoking_vertex, WEBGL_stencil_texturing

</details>
