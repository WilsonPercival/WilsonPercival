## Problem description

Construct crashes.

## Attach a .c3p

[crash_sine_preview_angle_r359b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12705619/crash_sine_preview_angle_r359b.zip)

## Steps to reproduce

1. Open a project.
2. Add `Sine` behavior to the sprite.
3. Change the `Movement` parameter to `Angle`.
4. Click the `Preview` checkbox.
5. Pull down on the field next to the `Angle` parameter to change the value.
6. Click `Undo` three times.
7. Click `Redo` three times.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/eed4491e-ba13-4a22-8e40-7853814eb862

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r359b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: expected finite number @ TypeError: expected finite number at Q.B (https://editor.construct.net/r359/main.js:1045:407) at d.j5a (https://editor.construct.net/r359/projectResources.js:853:437) at t_a.s3a.pf (https://editor.construct.net/r359/projectResources.js:1950:244) at window.Ac.Bj (https://editor.construct.net/r359/projectResources.js:1921:143) at d.Bj (https://editor.construct.net/r359/projectResources.js:1793:509) at https://editor.construct.net/r359/main.js:2942:142 at window.akb.Bj (https://editor.construct.net/r359/main.js:2942:193)
Stack: TypeError: expected finite number at Q.B (https://editor.construct.net/r359/main.js:1045:407) at d.j5a (https://editor.construct.net/r359/projectResources.js:853:437) at t_a.s3a.pf (https://editor.construct.net/r359/projectResources.js:1950:244) at window.Ac.Bj (https://editor.construct.net/r359/projectResources.js:1921:143) at d.Bj (https://editor.construct.net/r359/projectResources.js:1793:509) at https://editor.construct.net/r359/main.js:2942:142 at window.akb.Bj (https://editor.construct.net/r359/main.js:2942:193)
Construct version: r359
URL: https://editor.construct.net/r359/
Date: Sat Sep 23 2023 07:31:38 GMT+0300 (Восточная Европа, летнее время)
Uptime: 71.6 s

Platform information
Product: Construct 3 r359 (beta)
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
