## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_unexpected_type_private_variable_r351b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12088497/crash_timeline_unexpected_type_private_variable_r351b.zip)

## Steps to reproduce

1. Open a project.
2. Cut out `Timeline 1`.
3. Change the sprite's private variable type to `Boolean`.
4. Insert `Timeline 1`.

## Observed result

[observed.webm](https://github.com/WilsonPercival/WilsonPercival/assets/91274932/bf6981ed-9f10-4258-b3de-05ead8004888)

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r351b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: unexpected type
Stack: Error at oa.T_a (https://editor.construct.net/r351/main.js:1119:314) at window.assert (https://editor.construct.net/r351/main.js:1034:353) at NTa.df (https://editor.construct.net/r351/projectResources.js:1282:155) at NTa.NQ (https://editor.construct.net/r351/projectResources.js:1282:279) at d.E7a (https://editor.construct.net/r351/projectResources.js:1207:148) at d.oL (https://editor.construct.net/r351/projectResources.js:1211:68) at https://editor.construct.net/r351/projectResources.js:1215:105 at d.fMc (https://editor.construct.net/r351/projectResources.js:1056:175) at d.m6a (https://editor.construct.net/r351/projectResources.js:1056:239) at d.sva (https://editor.construct.net/r351/projectResources.js:1056:344)
Construct version: r351
URL: https://editor.construct.net/r351/
Date: Tue Jul 18 2023 22:34:01 GMT+0300 (Восточная Европа, летнее время)
Uptime: 70.9 s

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
