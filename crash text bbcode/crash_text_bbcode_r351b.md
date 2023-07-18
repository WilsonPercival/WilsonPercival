## Problem description

Construct crashes.

## Attach a .c3p

<img width="310" alt="attach" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/7da4c230-1416-41ff-a969-73209e03bd13">

## Steps to reproduce

1. Open `Icons in text`.
2. Click on the text in the layout editor.
3. In the left ear, uncheck the `Enable BBCode` option.

## Observed result

[observed.webm](https://github.com/WilsonPercival/WilsonPercival/assets/91274932/ee5efcf7-b84a-4a07-82e2-5778c051dd75)

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r351b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r351/main.js, line 1977, col 106
Message: Uncaught TypeError: Cannot read properties of null (reading 'fc')
Stack: TypeError: Cannot read properties of null (reading 'fc') at Lj.Zb.KQ.x4a (https://editor.construct.net/r351/main.js:1977:106) at JOb.Instance.CL (https://editor.construct.net/r351/plugins/allEditorPlugins.js:308:133) at JOb.Instance.Zf (https://editor.construct.net/r351/plugins/allEditorPlugins.js:306:279) at d.Zf (https://editor.construct.net/r351/projectResources.js:858:9) at d.Zf (https://editor.construct.net/r351/projectResources.js:1395:471) at d.Zf (https://editor.construct.net/r351/projectResources.js:1352:320) at ubc (https://editor.construct.net/r351/components/editors/layoutView/layoutView.js:91:303)
Construct version: r351
URL: https://editor.construct.net/r351/
Date: Tue Jul 18 2023 18:31:05 GMT+0300 (Восточная Европа, летнее время)
Uptime: 9.2 s

Platform information
Product: Construct 3 r351 (beta)
Browser: Chrome 114.0.5735.199
Browser engine: Chromium
Context: browser
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
