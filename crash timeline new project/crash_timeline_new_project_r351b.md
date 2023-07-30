## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_new_project_r351b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12209778/crash_timeline_new_project_r351b.zip)

## Steps to reproduce

1. Open a project.
2. Click `Editing mode`.
3. Click `Set keyframes`.
4. Select all keyframes except the first ones.
5. Click `Copy a selection of keyframes`.
6. Click `Undo`.
7. Click `Paste a selection of keyframes at the current time marker`.
8. Close the project.
9. Create a new project.
10. Create a sprite.
11. Remove the sprite from the project.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/a42122e1-8679-45d5-81ec-5a6294a2d889

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r351b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of null (reading 'dc') @ TypeError: Cannot read properties of null (reading 'dc') at d.dc (https://editor.construct.net/r351/projectResources.js:1180:155) at Dw (https://editor.construct.net/r351/projectResources.js:97:500) at Array.tAb (https://editor.construct.net/r351/projectResources.js:1304:109) at window.Ijb.dispatchEvent (https://editor.construct.net/r351/main.js:1257:42) at window.Ijb.Kr (https://editor.construct.net/r351/main.js:2944:87) at d.gi (https://editor.construct.net/r351/projectResources.js:760:311) at d.Li (https://editor.construct.net/r351/projectResources.js:586:6) at d.Li (https://editor.construct.net/r351/projectResources.js:759:491) at d.Li (https://editor.construct.net/r351/projectResources.js:696:92) at d.Ma (https://editor.construct.net/r351/projectResources.js:585:398)
Stack: TypeError: Cannot read properties of null (reading 'dc') at d.dc (https://editor.construct.net/r351/projectResources.js:1180:155) at Dw (https://editor.construct.net/r351/projectResources.js:97:500) at Array.tAb (https://editor.construct.net/r351/projectResources.js:1304:109) at window.Ijb.dispatchEvent (https://editor.construct.net/r351/main.js:1257:42) at window.Ijb.Kr (https://editor.construct.net/r351/main.js:2944:87) at d.gi (https://editor.construct.net/r351/projectResources.js:760:311) at d.Li (https://editor.construct.net/r351/projectResources.js:586:6) at d.Li (https://editor.construct.net/r351/projectResources.js:759:491) at d.Li (https://editor.construct.net/r351/projectResources.js:696:92) at d.Ma (https://editor.construct.net/r351/projectResources.js:585:398)
Construct version: r351
URL: https://editor.construct.net/r351/
Date: Sun Jul 30 2023 20:22:18 GMT+0300 (Восточная Европа, летнее время)
Uptime: 23.2 s

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
