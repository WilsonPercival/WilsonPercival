## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_paste_toaster_r359b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12702247/crash_timeline_paste_toaster_r359b.zip)

## Steps to reproduce

1. Open `Make animations with Construct`.
2. Copy the timeline.
3. Open the project `crash_timeline_paste_toaster_r359b.zip`.
4. Insert a timeline.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/b205e72d-a001-4619-8fc2-e86a23e81028

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r359b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r359/projectResources.js, line 821, col 144
Message: Uncaught TypeError: Cannot read properties of null (reading 'U2')
Stack: TypeError: Cannot read properties of null (reading 'U2') at d.vi (https://editor.construct.net/r359/projectResources.js:821:144) at d.ei (https://editor.construct.net/r359/projectResources.js:842:393) at https://editor.construct.net/r359/projectResources.js:1395:248 at Array.sort () at d.m8a (https://editor.construct.net/r359/projectResources.js:1395:227) at d.ag (https://editor.construct.net/r359/projectResources.js:1406:347) at d.ag (https://editor.construct.net/r359/projectResources.js:1363:320) at Rbc (https://editor.construct.net/r359/components/editors/layoutView/layoutView.js:91:303)
Construct version: r359
URL: https://editor.construct.net/r359/
Date: Fri Sep 22 2023 18:12:07 GMT+0300 (Восточная Европа, летнее время)
Uptime: 42.8 s

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
