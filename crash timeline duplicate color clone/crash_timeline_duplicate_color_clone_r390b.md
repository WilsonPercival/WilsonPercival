## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_duplicate_color_clone_r358s.zip](https://github.com/WilsonPercival/WilsonPercival/files/15283642/crash_timeline_duplicate_color_clone_r358s.zip)

## Steps to reproduce

1. Open a project.
2. Duplicate `Timeline 1`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/4cd4b1aa-2699-4b43-8331-55e98bdb2512

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** Worked in `r358s`, broke in `r359b`.

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of null (reading 'clone') @ TypeError: Cannot read properties of null (reading 'clone') at nXa.fG (https://editor.construct.net/r390/projectResources.js:1333:346) at d.fG (https://editor.construct.net/r390/projectResources.js:1259:250) at d.ws (https://editor.construct.net/r390/projectResources.js:1258:268) at d.za (https://editor.construct.net/r390/projectResources.js:1263:65) at d.RUc (https://editor.construct.net/r390/projectResources.js:1265:479) at d.za (https://editor.construct.net/r390/projectResources.js:1242:198) at async d.Cbc (https://editor.construct.net/r390/projectResources.js:1246:185) at async d.MDb (https://editor.construct.net/r390/projectResources.js:1246:300) at async d.za (https://editor.construct.net/r390/projectResources.js:1173:297) at async d.Dbc (https://editor.construct.net/r390/projectResources.js:1179:401)
Stack: TypeError: Cannot read properties of null (reading 'clone') at nXa.fG (https://editor.construct.net/r390/projectResources.js:1333:346) at d.fG (https://editor.construct.net/r390/projectResources.js:1259:250) at d.ws (https://editor.construct.net/r390/projectResources.js:1258:268) at d.za (https://editor.construct.net/r390/projectResources.js:1263:65) at d.RUc (https://editor.construct.net/r390/projectResources.js:1265:479) at d.za (https://editor.construct.net/r390/projectResources.js:1242:198) at async d.Cbc (https://editor.construct.net/r390/projectResources.js:1246:185) at async d.MDb (https://editor.construct.net/r390/projectResources.js:1246:300) at async d.za (https://editor.construct.net/r390/projectResources.js:1173:297) at async d.Dbc (https://editor.construct.net/r390/projectResources.js:1179:401)
Construct version: r390
URL: https://editor.construct.net/r390/
Date: Sat May 11 2024 20:08:56 GMT+0300 (Восточная Европа, летнее время)
Uptime: 265.5 s

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
