## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_copy_paste_subfolder_r360b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12738154/crash_timeline_copy_paste_subfolder_r360b.zip)

## Steps to reproduce

1. Open a project.
2. Move `Timeline 1` to the `fun` folder.
3. Copy the timeline.
4. Paste the timeline into the `fun` folder. A window will appear, click `OK`.
5. Click `Undo`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/de6d1fdb-add4-47a5-8c71-b8e63352730c

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r360b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of null (reading 'cc') @ TypeError: Cannot read properties of null (reading 'cc') at d.U (https://editor.construct.net/r360/projectResources.js:1024:3) at d.ZMa (https://editor.construct.net/r360/projectResources.js:590:148) at d.ZMa (https://editor.construct.net/r360/projectResources.js:590:117) at I_a.Jka.pf (https://editor.construct.net/r360/projectResources.js:1956:423) at self.nj.pf (https://editor.construct.net/r360/projectResources.js:1916:408) at window.Ac.Kh (https://editor.construct.net/r360/projectResources.js:1920:319) at d.Kh (https://editor.construct.net/r360/projectResources.js:1793:440) at https://editor.construct.net/r360/main.js:2941:95 at window.akb.Kh (https://editor.construct.net/r360/main.js:2941:146)
Stack: TypeError: Cannot read properties of null (reading 'cc') at d.U (https://editor.construct.net/r360/projectResources.js:1024:3) at d.ZMa (https://editor.construct.net/r360/projectResources.js:590:148) at d.ZMa (https://editor.construct.net/r360/projectResources.js:590:117) at I_a.Jka.pf (https://editor.construct.net/r360/projectResources.js:1956:423) at self.nj.pf (https://editor.construct.net/r360/projectResources.js:1916:408) at window.Ac.Kh (https://editor.construct.net/r360/projectResources.js:1920:319) at d.Kh (https://editor.construct.net/r360/projectResources.js:1793:440) at https://editor.construct.net/r360/main.js:2941:95 at window.akb.Kh (https://editor.construct.net/r360/main.js:2941:146)
Construct version: r360
URL: https://editor.construct.net/r360/
Date: Wed Sep 27 2023 14:37:28 GMT+0300 (Восточная Европа, летнее время)
Uptime: 162.2 s

Platform information
Product: Construct 3 r360 (beta)
Browser: Chrome 117.0.5938.92
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/117.0.0.0 Safari/537.36
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
