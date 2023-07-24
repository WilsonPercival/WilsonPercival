## Problem description

Construct crashes. I think it has something to do with the clipboard. I tested 3 devices and only one of them can repeat this crash.

## Attach a .c3p

No.

## Steps to reproduce

1. Create a new project.
2. Create a sprite. The Animation Editor will open automatically.
3. Click `Print Screen` to place the image on the clipboard.
4. Press `Ctrl + V` to paste the image. A window will open, click `Fit to canvas`.

## Observed result

Construct crashes.

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r351b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of undefined (reading 'smooth') @ TypeError: Cannot read properties of undefined (reading 'smooth') at https://editor.construct.net/r351/projectResources.js:203:513 at https://editor.construct.net/r351/projectResources.js:10:485 at new Promise () at qu (https://editor.construct.net/r351/projectResources.js:10:440) at nA (https://editor.construct.net/r351/projectResources.js:201:161) at SHa (https://editor.construct.net/r351/projectResources.js:203:461) at async https://editor.construct.net/r351/projectResources.js:10:479
Stack: TypeError: Cannot read properties of undefined (reading 'smooth') at https://editor.construct.net/r351/projectResources.js:203:513 at https://editor.construct.net/r351/projectResources.js:10:485 at new Promise () at qu (https://editor.construct.net/r351/projectResources.js:10:440) at nA (https://editor.construct.net/r351/projectResources.js:201:161) at SHa (https://editor.construct.net/r351/projectResources.js:203:461) at async https://editor.construct.net/r351/projectResources.js:10:479
Construct version: r351
URL: https://editor.construct.net/r351/
Date: Mon Jul 24 2023 13:54:47 GMT+0300 (Москва, стандартное время)
Uptime: 45.3 s

Platform information
Product: Construct 3 r351 (beta)
Browser: Chrome 114.0.5735.248
Browser engine: Chromium
Context: browser
Operating system: Windows 10
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 6
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36
Language setting: en-US

WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (NVIDIA)
Renderer: ANGLE (NVIDIA, NVIDIA GeForce RTX 2060 Direct3D11 vs_5_0 ps_5_0, D3D11)
Major performance caveat: no
Maximum texture size: 16384
Point size range: 1 to 1024
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_disjoint_timer_query_webgl2, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, EXT_texture_norm16, KHR_parallel_shader_compile, OES_draw_buffers_indexed, OES_texture_float_linear, OVR_multiview2, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw, WEBGL_provoking_vertex

</details>
