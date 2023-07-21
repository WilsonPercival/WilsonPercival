## Problem description

Construct crashes.

## Attach a .c3p

<img width="312" alt="attach" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/af13aae5-85bd-454e-9279-cffb02a44264">

## Steps to reproduce

1. Open `Rain Demo`.
2. Click on `Construct2Logo` to open the animation editor.
3. Copy the animation.
4. Insert animation.

## Observed result

[observed.webm](https://github.com/WilsonPercival/WilsonPercival/assets/91274932/e6caeca9-59b2-404f-9cf2-a3e062163160)

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r351b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: frame not found @ Error: frame not found at d.Xtb (https://editor.construct.net/r351/projectResources.js:769:436) at d.Do (https://editor.construct.net/r351/projectResources.js:781:468) at https://editor.construct.net/r351/projectResources.js:2071:393 at eh (https://editor.construct.net/r351/main.js:372:235) at CCG.Vg.g.K.Enb.lu (https://editor.construct.net/r351/main.js:1530:148) at new CCG.Vg.g.K.Enb (https://editor.construct.net/r351/main.js:1530:97) at oa.j (https://editor.construct.net/r351/main.js:1126:44) at CCG.bh.g.K.oya.$d (https://editor.construct.net/r351/main.js:1598:422) at N2a.opc.ga (https://editor.construct.net/r351/projectResources.js:2071:325) at Uy (https://editor.construct.net/r351/projectResources.js:154:465)
Stack: Error: frame not found at d.Xtb (https://editor.construct.net/r351/projectResources.js:769:436) at d.Do (https://editor.construct.net/r351/projectResources.js:781:468) at https://editor.construct.net/r351/projectResources.js:2071:393 at eh (https://editor.construct.net/r351/main.js:372:235) at CCG.Vg.g.K.Enb.lu (https://editor.construct.net/r351/main.js:1530:148) at new CCG.Vg.g.K.Enb (https://editor.construct.net/r351/main.js:1530:97) at oa.j (https://editor.construct.net/r351/main.js:1126:44) at CCG.bh.g.K.oya.$d (https://editor.construct.net/r351/main.js:1598:422) at N2a.opc.ga (https://editor.construct.net/r351/projectResources.js:2071:325) at Uy (https://editor.construct.net/r351/projectResources.js:154:465)
Construct version: r351
URL: https://editor.construct.net/r351/
Date: Fri Jul 21 2023 21:05:15 GMT+0300 (Восточная Европа, летнее время)
Uptime: 81.8 s

Platform information
Product: Construct 3 r351 (beta)
Browser: Chrome 114.0.5735.248
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
