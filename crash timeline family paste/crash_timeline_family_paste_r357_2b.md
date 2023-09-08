## Problem description

Construct crashes.

## Attach a .c3p

[project_one.zip](https://github.com/WilsonPercival/WilsonPercival/files/12560264/project_one.zip)

[project_two.zip](https://github.com/WilsonPercival/WilsonPercival/files/12560265/project_two.zip)

## Steps to reproduce

1. Open `project_one.zip`.
2. Copy `Timeline 1`.
3. Open `project_two.zip`.
4. Insert a timeline.
5. Make a clone of the `Sprite` object.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/44dd3ec8-f0aa-4af5-b3b0-ea7f7b145248

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r357-2b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: name already in object class namespace @ Error: name already in object class namespace at new d (https://editor.construct.net/r357-2/projectResources.js:625:241) at oa.j (https://editor.construct.net/r357-2/main.js:1127:44) at d.gD (https://editor.construct.net/r357-2/projectResources.js:633:388) at d.NU (https://editor.construct.net/r357-2/projectResources.js:693:182) at d.NU (https://editor.construct.net/r357-2/projectResources.js:722:223) at Rhb.Mjb (https://editor.construct.net/r357-2/components/bars/projectBar/projectBar.js:125:305)
Stack: Error: name already in object class namespace at new d (https://editor.construct.net/r357-2/projectResources.js:625:241) at oa.j (https://editor.construct.net/r357-2/main.js:1127:44) at d.gD (https://editor.construct.net/r357-2/projectResources.js:633:388) at d.NU (https://editor.construct.net/r357-2/projectResources.js:693:182) at d.NU (https://editor.construct.net/r357-2/projectResources.js:722:223) at Rhb.Mjb (https://editor.construct.net/r357-2/components/bars/projectBar/projectBar.js:125:305)
Construct version: r357.2
URL: https://editor.construct.net/r357-2/
Date: Fri Sep 08 2023 16:14:11 GMT+0300 (Восточная Европа, летнее время)
Uptime: 46.2 s

Platform information
Product: Construct 3 r357.2 (beta)
Browser: Chrome 116.0.5845.180
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/116.0.0.0 Safari/537.36
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
