## Problem description

Construct crashes.

## Attach a .c3p

save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/12061269/save_open_project.zip)

## Steps to reproduce

1. Create a new project.
2. Add a sprite.
3. In the right ear, click `Tools -> View used addons`.
4. Right click on the sprite and select `Find all references...`.
5. A window will open, double click on the instance.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/93079a2f-ab5e-4938-bef5-56ba4e592b96

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r350s

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: d.$ is not a function @ TypeError: d.$ is not a function at pqb (https://editor.construct.net/r350/components/bars/findReferencesBar/findReferencesBar.js:8:123) at qqb (https://editor.construct.net/r350/components/bars/findReferencesBar/findReferencesBar.js:8:355) at window.AE.Una (https://editor.construct.net/r350/components/bars/findReferencesBar/findReferencesBar.js:16:273) at Array. (https://editor.construct.net/r350/components/bars/findReferencesBar/findReferencesBar.js:12:164) at CCG.qi.g.K.Table.dispatchEvent (https://editor.construct.net/r350/main.js:1261:42) at wi (https://editor.construct.net/r350/main.js:411:250) at CCG.xi.g.K.Table.hL.$q (https://editor.construct.net/r350/main.js:1855:142) at HTMLElement.hl (https://editor.construct.net/r350/main.js:1852:168) at HTMLDocument. (https://editor.construct.net/r350/main.js:207:475)
Stack: TypeError: d.$ is not a function at pqb (https://editor.construct.net/r350/components/bars/findReferencesBar/findReferencesBar.js:8:123) at qqb (https://editor.construct.net/r350/components/bars/findReferencesBar/findReferencesBar.js:8:355) at window.AE.Una (https://editor.construct.net/r350/components/bars/findReferencesBar/findReferencesBar.js:16:273) at Array. (https://editor.construct.net/r350/components/bars/findReferencesBar/findReferencesBar.js:12:164) at CCG.qi.g.K.Table.dispatchEvent (https://editor.construct.net/r350/main.js:1261:42) at wi (https://editor.construct.net/r350/main.js:411:250) at CCG.xi.g.K.Table.hL.$q (https://editor.construct.net/r350/main.js:1855:142) at HTMLElement.hl (https://editor.construct.net/r350/main.js:1852:168) at HTMLDocument. (https://editor.construct.net/r350/main.js:207:475)
Construct version: r350
URL: https://editor.construct.net/
Date: Sat Jul 15 2023 19:15:44 GMT+0300 (Восточная Европа, летнее время)
Uptime: 66.2 s

Platform information
Product: Construct 3 r350 (stable)
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
