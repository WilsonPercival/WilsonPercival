## Problem description

Construct crashes.

## Attach a .c3p

[crash_project_bar_over_object_r372_2b.zip](https://github.com/WilsonPercival/WilsonPercival/files/13781025/crash_project_bar_over_object_r372_2b.zip)

## Steps to reproduce

1. Open a project.
2. In the right ear, in the `Search` field, write `k`.
3. Drag `Keyboard` onto the project folder.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/bee572dc-6e79-49c3-b60b-3a266e2e23a5

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r372-2b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r372-2/components/bars/projectBar/projectBar.js, line 122, col 107
Message: Uncaught TypeError: f.H is not a function
Stack: TypeError: f.H is not a function at CCG.aa.qG (https://editor.construct.net/r372-2/components/bars/projectBar/projectBar.js:122:107) at CCG.aa.Baa (https://editor.construct.net/r372-2/components/bars/projectBar/projectBar.js:117:88) at Array. (https://editor.construct.net/r372-2/components/bars/projectBar/projectBar.js:101:426) at CCG.uh.g.J.LQa.dispatchEvent (https://editor.construct.net/r372-2/main.js:1264:399) at xh (https://editor.construct.net/r372-2/main.js:382:372) at d.eg (https://editor.construct.net/r372-2/main.js:1646:58) at Tb.jf (https://editor.construct.net/r372-2/main.js:1638:67)
Construct version: r372.2
URL: https://editor.construct.net/r372-2/
Date: Wed Dec 27 2023 21:57:31 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 11.1 s

Platform information
Product: Construct 3 r372.2 (beta)
Browser: Chrome 120.0.6099.130
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Safari/537.36
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
