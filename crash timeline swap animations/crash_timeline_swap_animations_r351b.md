## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_swap_animations_r351b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12209232/crash_timeline_swap_animations_r351b.zip)

## Steps to reproduce

1. Open a project.
2. Click on the sprite in the layout editor.
3. Click `Editing mode`.
4. Click `Set keyframes`.
5. Move the red flag to `1.10s`.
6. In the left ear, change the `Initial animation` parameter to `Animation 2`.
7. In the left ear, change the `Initial frame` parameter to `1`.
8. Select all key points except the first ones.
9. Click `Copy a selection of keyframes`.
10. Click on the sprite in the timeline and select `Swap instance`. A window will open, select `Sprite2` and click `OK`.
11. Move the red flag to `1.40s`.
12. Click `Paste a selection of keyframes at the current time marker`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/ef31999d-5270-4d65-86c9-bf1f21af7ae1

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r351b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r351/projectResources.js, line 1303, col 14
Message: Uncaught TypeError: Cannot read properties of null (reading 'ck')
Stack: TypeError: Cannot read properties of null (reading 'ck') at QK.qxc.wpb (https://editor.construct.net/r351/projectResources.js:1303:14) at d.df (https://editor.construct.net/r351/projectResources.js:1211:419) at d.Eg (https://editor.construct.net/r351/projectResources.js:1205:341) at https://editor.construct.net/r351/projectResources.js:1034:113 at Array.map () at https://editor.construct.net/r351/projectResources.js:1033:508 at d.Rub (https://editor.construct.net/r351/projectResources.js:1033:260) at d.nka (https://editor.construct.net/r351/projectResources.js:1033:353) at S2.nka (https://editor.construct.net/r351/components/bars/timelineBar/timelineBar.js:263:388) at k (https://editor.construct.net/r351/components/bars/timelineBar/timelineBar.js:30:372)
Construct version: r351
URL: https://editor.construct.net/r351/
Date: Sun Jul 30 2023 15:37:22 GMT+0300 (Восточная Европа, летнее время)
Uptime: 37.2 s

Platform information
Product: Construct 3 r351 (beta)
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
