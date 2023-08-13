## Problem description

Construct crashes.

## Attach a .c3p

[crash_returning_invalid_layer_index_r353b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12330317/crash_returning_invalid_layer_index_r353b.zip)

## Steps to reproduce

1. Open a project.
2. Remove `Layout 1`.
3. Move the sprite from the right ear to the layout editor.
4. In the right ear, click on the sprite and select `Select all in project`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/bb777849-13a7-4a3f-9228-176a2288c4a5

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r353b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: returning invalid layer index
Stack: Error at oa.Z_a (https://editor.construct.net/r353/main.js:1119:314) at window.assert (https://editor.construct.net/r353/main.js:1034:353) at d.ve (https://editor.construct.net/r353/projectResources.js:1375:212) at jfa (https://editor.construct.net/r353/projectResources.js:878:414) at Array.sort () at CCG.ba.FU (https://editor.construct.net/r353/components/bars/propertiesBar/propertiesBar.js:145:160) at Vgb (https://editor.construct.net/r353/components/bars/projectBar/projectBar.js:23:440) at https://editor.construct.net/r353/components/bars/projectBar/projectBar.js:23:291 at https://editor.construct.net/r353/main.js:1905:410
Construct version: r353
URL: https://editor.construct.net/r353/
Date: Sun Aug 13 2023 22:57:00 GMT+0300 (Восточная Европа, летнее время)
Uptime: 20.9 s

Platform information
Product: Construct 3 r353 (beta)
Browser: Chrome 115.0.5790.171
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
