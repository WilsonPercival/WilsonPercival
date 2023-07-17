## Problem description

Construct crashes.

## Attach a .c3p

[crash_cannot_unselect_inactive_instance_r350s.zip](https://github.com/WilsonPercival/WilsonPercival/files/12072301/crash_cannot_unselect_inactive_instance_r350s.zip)

## Steps to reproduce

1. Create a sprite.
2. Press and hold the `Ctrl` key.
3. Click on the sprite and move the cursor down. Note that a copy of the instance will be created.
3. Click on the top sprite and don't release the mouse button. Note that both sprites are highlighted.
4. Press the `Z` key. Please note that there will be a rollback.
5. Drag the cursor to the side.

## Observed result

[observed.webm](https://github.com/WilsonPercival/WilsonPercival/assets/91274932/24296390-6f0a-4cf1-b746-b59da6418429)

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r350s

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r350/components/editors/layoutView/layoutView.js, line 213, col 399
Message: Uncaught Error: cannot unselect inactive instance
Stack: Error: cannot unselect inactive instance at aeb.KLa (https://editor.construct.net/r350/components/editors/layoutView/layoutView.js:213:405) at feb.ag (https://editor.construct.net/r350/components/editors/layoutView/layoutView.js:230:476) at Array.uf (https://editor.construct.net/r350/components/editors/layoutView/layoutView.js:227:277) at window.jm.dispatchEvent (https://editor.construct.net/r350/main.js:1260:399) at window.jm.ag (https://editor.construct.net/r350/components/editors/layoutView/layoutView.js:111:172) at HTMLDocument.uf (https://editor.construct.net/r350/components/editors/layoutView/layoutView.js:94:381)
Construct version: r350
URL: https://editor.construct.net/
Date: Mon Jul 17 2023 20:24:09 GMT+0300 (Восточная Европа, летнее время)
Uptime: 16 s

Platform information
Product: Construct 3 r350 (stable)
Browser: Chrome 114.0.5735.199
Browser engine: Chromium
Context: webapp
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
