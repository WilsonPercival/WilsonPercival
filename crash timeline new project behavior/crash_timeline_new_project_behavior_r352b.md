## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_new_project_behavior_r352b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12269631/crash_timeline_new_project_behavior_r352b.zip)

## Steps to reproduce

1. Open a project.
2. On the timeline, add the `Wave` property.
3. Copy `Timeline 1`.
4. Remove the behavior.
5. Insert a timeline. A window will open, click `OK`.
6. Close the project.
7. Open the project.
8. On the timeline, add the `Wave` property.
9. Click `Undo`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/ae3a51e9-7863-4caa-b816-526cf854961a

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r352b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of null (reading 'fc') @ TypeError: Cannot read properties of null (reading 'fc') at d.aa (https://editor.construct.net/r352/projectResources.js:1095:213) at d.aa (https://editor.construct.net/r352/projectResources.js:1163:484) at d.aa (https://editor.construct.net/r352/projectResources.js:1164:11) at d.awb (https://editor.construct.net/r352/projectResources.js:1179:18) at Array.Lra (https://editor.construct.net/r352/projectResources.js:1175:311) at window.Mjb.dispatchEvent (https://editor.construct.net/r352/main.js:1257:42) at CCG.ho (https://editor.construct.net/r352/main.js:923:417) at d.Li (https://editor.construct.net/r352/projectResources.js:586:486) at d.Li (https://editor.construct.net/r352/projectResources.js:1179:262) at d.Ma (https://editor.construct.net/r352/projectResources.js:586:398)
Stack: TypeError: Cannot read properties of null (reading 'fc') at d.aa (https://editor.construct.net/r352/projectResources.js:1095:213) at d.aa (https://editor.construct.net/r352/projectResources.js:1163:484) at d.aa (https://editor.construct.net/r352/projectResources.js:1164:11) at d.awb (https://editor.construct.net/r352/projectResources.js:1179:18) at Array.Lra (https://editor.construct.net/r352/projectResources.js:1175:311) at window.Mjb.dispatchEvent (https://editor.construct.net/r352/main.js:1257:42) at CCG.ho (https://editor.construct.net/r352/main.js:923:417) at d.Li (https://editor.construct.net/r352/projectResources.js:586:486) at d.Li (https://editor.construct.net/r352/projectResources.js:1179:262) at d.Ma (https://editor.construct.net/r352/projectResources.js:586:398)
Construct version: r352
URL: https://editor.construct.net/r352/
Date: Sun Aug 06 2023 14:47:39 GMT+0300 (Восточная Европа, летнее время)
Uptime: 30.6 s

Platform information
Product: Construct 3 r352 (beta)
Browser: Chrome 115.0.5790.170
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
