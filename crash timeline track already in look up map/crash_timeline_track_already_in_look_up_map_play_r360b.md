## Problem description

Construct crashes.

## Attach a .c3p

<img width="314" alt="attach" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/bedb53af-e53b-4042-b1c5-df7cd81b913b">

## Steps to reproduce

1. Open `Make animations with Construct`.
2. Open `Timeline 1`.
3. Click `Play (Space)`.
4. Delete `Timeline 1`. This step must be done while the animation is playing.
5. Click `Undo`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/554d54a1-20a2-4523-87f5-e98bce17d163

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r360b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: track already in look up map
Stack: Error at oa.r0a (https://editor.construct.net/r360/main.js:1120:314) at window.assert (https://editor.construct.net/r360/main.js:1035:353) at d.jva (https://editor.construct.net/r360/projectResources.js:1031:248) at d.gvb (https://editor.construct.net/r360/projectResources.js:1128:471) at d.u1b (https://editor.construct.net/r360/projectResources.js:1050:342) at d.ej (https://editor.construct.net/r360/projectResources.js:1050:254) at LZa.cA.pf (https://editor.construct.net/r360/projectResources.js:1923:74) at window.Ac.Kh (https://editor.construct.net/r360/projectResources.js:1920:319) at d.Kh (https://editor.construct.net/r360/projectResources.js:1793:440) at https://editor.construct.net/r360/main.js:2941:95
Construct version: r360
URL: https://editor.construct.net/r360/
Date: Tue Sep 26 2023 16:05:19 GMT+0300 (Восточная Европа, летнее время)
Uptime: 42.4 s

Platform information
Product: Construct 3 r360 (beta)
Browser: Chrome 117.0.5938.89
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
