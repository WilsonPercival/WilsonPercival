## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_copy_paste_keyframes_out_of_bounds_r350s.zip](https://github.com/WilsonPercival/WilsonPercival/files/12070283/crash_timeline_copy_paste_keyframes_out_of_bounds_r350s.zip)

## Steps to reproduce

1. Open a project.
2. Click `Editing mode`.
3. Click `Set keyframes`.
4. Move the red flag to `2.00s`.
5. Click `Set keyframes`.
6. Select all key points except the first ones.
7. Click `Copy a selection of keyframes`.
8. Move the red flag to `4.50s`.
9. Click `Paste a selection of keyframes at the current time marker`.
10. Select the red key points and move them to the right one position.

## Observed result

[observed.webm](https://github.com/WilsonPercival/WilsonPercival/assets/91274932/8b7cb7fc-b7a9-4ac1-a985-5a1d992ed9ec)

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r350s

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of null (reading '$') @ TypeError: Cannot read properties of null (reading '$') at d.$ (https://editor.construct.net/r350/projectResources.js:1204:241) at d.eNb (https://editor.construct.net/r350/projectResources.js:1184:495) at eNb.next () at d.e0a (https://editor.construct.net/r350/projectResources.js:1185:217) at d.Om (https://editor.construct.net/r350/projectResources.js:1190:208) at d.Om (https://editor.construct.net/r350/projectResources.js:1119:157) at d.SE (https://editor.construct.net/r350/projectResources.js:1037:190) at d.SE (https://editor.construct.net/r350/projectResources.js:1037:277) at d.Cla (https://editor.construct.net/r350/components/bars/timelineBar/timelineBar.js:43:464) at f2.gO (https://editor.construct.net/r350/components/bars/timelineBar/timelineBar.js:191:277)
Stack: TypeError: Cannot read properties of null (reading '$') at d.$ (https://editor.construct.net/r350/projectResources.js:1204:241) at d.eNb (https://editor.construct.net/r350/projectResources.js:1184:495) at eNb.next () at d.e0a (https://editor.construct.net/r350/projectResources.js:1185:217) at d.Om (https://editor.construct.net/r350/projectResources.js:1190:208) at d.Om (https://editor.construct.net/r350/projectResources.js:1119:157) at d.SE (https://editor.construct.net/r350/projectResources.js:1037:190) at d.SE (https://editor.construct.net/r350/projectResources.js:1037:277) at d.Cla (https://editor.construct.net/r350/components/bars/timelineBar/timelineBar.js:43:464) at f2.gO (https://editor.construct.net/r350/components/bars/timelineBar/timelineBar.js:191:277)
Construct version: r350
URL: https://editor.construct.net/
Date: Mon Jul 17 2023 17:03:06 GMT+0300 (Восточная Европа, летнее время)
Uptime: 22.1 s

Platform information
Product: Construct 3 r350 (stable)
Browser: Chrome 114.0.5735.199
Browser engine: Chromium
Context: webapp
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36
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
