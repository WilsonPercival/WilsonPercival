## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_no_master_keyframe_was_found_for_property_keyframe_r351b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12209899/crash_timeline_no_master_keyframe_was_found_for_property_keyframe_r351b.zip)

## Steps to reproduce

1. Open a project.
2. Copy `Timeline 1`.
3. Remove `Layer 1`.
4. Insert a timeline.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/0ef625ba-8f7d-4607-a005-47ff3ed618fa

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r351b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: no master keyframe was found for property keyframe
Stack: Error at oa.T_a (https://editor.construct.net/r351/main.js:1119:314) at window.assert (https://editor.construct.net/r351/main.js:1034:353) at d.Vma (https://editor.construct.net/r351/projectResources.js:1209:104) at d.Izc (https://editor.construct.net/r351/projectResources.js:1209:181) at d.z4b (https://editor.construct.net/r351/projectResources.js:1210:13) at https://editor.construct.net/r351/projectResources.js:1214:481 at d.fMc (https://editor.construct.net/r351/projectResources.js:1056:175) at d.m6a (https://editor.construct.net/r351/projectResources.js:1056:239) at d.XIa (https://editor.construct.net/r351/projectResources.js:1056:402) at d.Ha (https://editor.construct.net/r351/projectResources.js:1214:447)
Construct version: r351
URL: https://editor.construct.net/r351/
Date: Sun Jul 30 2023 21:55:23 GMT+0300 (Восточная Европа, летнее время)
Uptime: 39 s

Platform information
Product: Construct 3 r351 (beta)
Browser: Chrome 115.0.5790.110
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
