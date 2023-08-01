## Problem description

Construct crashes.

## Attach a .c3p

[crash_this_is_fine_timeline_r346b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12231965/crash_this_is_fine_timeline_r346b.zip)

## Steps to reproduce

1. Open a project.
2. In the timeline panel, click on the sprite and select `Add subfolder`.
3. Click on a folder and select `Add subfolder`.
4. Move the bottom folder onto the sprite so that it comes out of the top folder.
5. Click on the bottom folder and select `Rename`.
6. Press `A` on your keyboard to add the letter `a` to the end of the folder name.
7. Click `Undo`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/acabc83e-95a6-4099-a359-26aaf98524e0

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r352b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: folder name 'Property Track Folder' already used @ Error: folder name 'Property Track Folder' already used at d.ib (https://editor.construct.net/r352/projectResources.js:590:68) at d.ib (https://editor.construct.net/r352/projectResources.js:1168:77) at NZa.Xq.mf (https://editor.construct.net/r352/projectResources.js:1916:276) at window.zc.Ih (https://editor.construct.net/r352/projectResources.js:1912:319) at d.Ih (https://editor.construct.net/r352/projectResources.js:1785:440) at https://editor.construct.net/r352/main.js:2940:9 at window.Mjb.Ih (https://editor.construct.net/r352/main.js:2940:60)
Stack: Error: folder name 'Property Track Folder' already used at d.ib (https://editor.construct.net/r352/projectResources.js:590:68) at d.ib (https://editor.construct.net/r352/projectResources.js:1168:77) at NZa.Xq.mf (https://editor.construct.net/r352/projectResources.js:1916:276) at window.zc.Ih (https://editor.construct.net/r352/projectResources.js:1912:319) at d.Ih (https://editor.construct.net/r352/projectResources.js:1785:440) at https://editor.construct.net/r352/main.js:2940:9 at window.Mjb.Ih (https://editor.construct.net/r352/main.js:2940:60)
Construct version: r352
URL: https://editor.construct.net/r352/
Date: Tue Aug 01 2023 19:11:06 GMT+0300 (Восточная Европа, летнее время)
Uptime: 55.2 s

Platform information
Product: Construct 3 r352 (beta)
Browser: Chrome 115.0.5790.110
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/115.0.0.0 Safari/537.36
Language setting: en-US

WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (AMD)
Renderer: ANGLE (AMD, AMD Radeon(TM) Graphics Direct3D11 vs_5_0 ps_5_0, D3D11)
Major performance caveat: no
Maximum texture size: 16384
Point size range: 1 to 1024
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_disjoint_timer_query_webgl2, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, EXT_texture_norm16, KHR_parallel_shader_compile, OES_draw_buffers_indexed, OES_texture_float_linear, OVR_multiview2, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw, WEBGL_provoking_vertex

</details>
