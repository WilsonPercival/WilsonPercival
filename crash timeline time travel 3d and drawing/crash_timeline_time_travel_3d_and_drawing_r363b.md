## Problem description

Construct crashes.

## Attach a .c3p

<img width="312" alt="attach1" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/85908435-c717-46e9-95bd-462c52caa9e2">

<img width="320" alt="attach2" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/aeafe438-f3cb-4a2f-a197-33e63347300e">

## Steps to reproduce

1. Open `Time Travel Template`.
2. Close the project.
3. Open `TimelinesDemo`.
4. Open the `Write` timeline.
5. Click `Play (Space)`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/cc36d81d-69a2-4937-accb-e1195ba417b1

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r363b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r363/plugins/allEditorPlugins.js, line 287, col 317
Message: Uncaught TypeError: Cannot read properties of null (reading 'Wa')
Stack: TypeError: Cannot read properties of null (reading 'Wa') at $Ob.Instance.HPa (https://editor.construct.net/r363/plugins/allEditorPlugins.js:287:317) at Array.jsa (https://editor.construct.net/r363/plugins/allEditorPlugins.js:285:148) at window.vkb.dispatchEvent (https://editor.construct.net/r363/main.js:1258:42) at window.vkb.Nk (https://editor.construct.net/r363/main.js:2952:422) at d.KU (https://editor.construct.net/r363/projectResources.js:1042:300) at u1.jLc (https://editor.construct.net/r363/components/bars/timelineBar/timelineBar.js:69:66) at Xq.g.J.kk.Rka.Wyb (https://editor.construct.net/r363/components/bars/timelineBar/timelineBar.js:53:443) at Zh (https://editor.construct.net/r363/main.js:396:253) at Xq.g.J.kk.Rka.r7a (https://editor.construct.net/r363/main.js:1739:248) at Xq.g.J.kk.Rka.x3 (https://editor.construct.net/r363/main.js:1736:403)
Construct version: r363
URL: https://editor.construct.net/r363/
Date: Fri Oct 20 2023 20:10:38 GMT+0300 (Восточная Европа, летнее время)
Uptime: 37.3 s

Platform information
Product: Construct 3 r363 (beta)
Browser: Chrome 118.0.5993.89
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/118.0.0.0 Safari/537.36
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
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_disjoint_timer_query_webgl2, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, EXT_texture_norm16, KHR_parallel_shader_compile, OES_draw_buffers_indexed, OES_texture_float_linear, OVR_multiview2, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw, WEBGL_provoking_vertex

</details>
