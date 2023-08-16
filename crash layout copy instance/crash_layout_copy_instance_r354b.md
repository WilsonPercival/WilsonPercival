## Problem description

Construct crashes.

## Attach a .c3p

No.

## Steps to reproduce

1. Create a new project.
2. Create a sprite.
3. Hold `Ctrl + D`.
4. Click on the sprite with the left mouse button and continue to hold. Note that the sprite will become selected for a moment, and then the selection will disappear. You need to wait until it disappears.
5. Drag the mouse to the side.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/70db46f6-fdf4-45f4-9d87-8b178926fc03

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r354b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r354/main.js, line 1049, col 141
Message: Uncaught TypeError: unexpected type
Stack: TypeError: unexpected type at Q.i (https://editor.construct.net/r354/main.js:1049:147) at peb.bg (https://editor.construct.net/r354/components/editors/layoutView/layoutView.js:232:410) at Array.vf (https://editor.construct.net/r354/components/editors/layoutView/layoutView.js:228:277) at window.jm.dispatchEvent (https://editor.construct.net/r354/main.js:1256:399) at window.jm.bg (https://editor.construct.net/r354/components/editors/layoutView/layoutView.js:111:172) at HTMLDocument.vf (https://editor.construct.net/r354/components/editors/layoutView/layoutView.js:94:382)
Construct version: r354
URL: https://editor.construct.net/r354/
Date: Wed Aug 16 2023 14:49:05 GMT+0300 (Восточная Европа, летнее время)
Uptime: 26 s

Platform information
Product: Construct 3 r354 (beta)
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
