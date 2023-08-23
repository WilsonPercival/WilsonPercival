## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_track_already_in_look_up_map_r355b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12419345/crash_timeline_track_already_in_look_up_map_r355b.zip)

## Steps to reproduce

1. Open a project. Note that the `Timeline Bar` must be open, otherwise the crash will not occur.
2. Cut out `Timeline 1`.
3. Insert `Timeline 1`.
4. Click `Undo` twice.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/b038f453-573e-4f95-b5a5-c8f202c867b8

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r355b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: track already in look up map
Stack: Error at oa.$_a (https://editor.construct.net/r355/main.js:1119:314) at window.assert (https://editor.construct.net/r355/main.js:1034:353) at d.$ua (https://editor.construct.net/r355/projectResources.js:1030:248) at d.Wub (https://editor.construct.net/r355/projectResources.js:1126:473) at d.h1b (https://editor.construct.net/r355/projectResources.js:1049:342) at d.cj (https://editor.construct.net/r355/projectResources.js:1049:254) at GZa.Wz.mf (https://editor.construct.net/r355/projectResources.js:1917:76) at window.zc.Jh (https://editor.construct.net/r355/projectResources.js:1914:319) at d.Jh (https://editor.construct.net/r355/projectResources.js:1787:440) at https://editor.construct.net/r355/main.js:2939:95
Construct version: r355
URL: https://editor.construct.net/r355/
Date: Wed Aug 23 2023 15:46:52 GMT+0300 (Восточная Европа, летнее время)
Uptime: 14.3 s

Platform information
Product: Construct 3 r355 (beta)
Browser: Chrome 116.0.5845.97
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
