## Problem description

Construct crashes.

## Attach a .c3p

[crash_pointer_already_captured_r355b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12419536/crash_pointer_already_captured_r355b.zip)

## Steps to reproduce

1. Open a project.
2. Duplicate `Layout 1`.
3. Open `Layout 2`.
4. Hold down the sprite instance in the Layout Editor and hold down the mouse button.
5. Move the instance to the side.
6. Press `Ctrl + Z` twice. Now you can release the left mouse button.
7. Click `Redo`.
8. Open `Layout 2`.
9. Click on the sprite instance in the layout editor.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/20d4e67a-ae67-455d-9d00-b0f331b231b9

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r355b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r355/components/editors/layoutView/layoutView.js, line 1, col 50
Message: Uncaught Error: pointer already captured
Stack: Error: pointer already captured at zab (https://editor.construct.net/r355/components/editors/layoutView/layoutView.js:1:56) at bS (https://editor.construct.net/r355/components/editors/layoutView/layoutView.js:54:10) at leb.Oc (https://editor.construct.net/r355/components/editors/layoutView/layoutView.js:230:466) at Array.Ac (https://editor.construct.net/r355/components/editors/layoutView/layoutView.js:228:207) at window.jm.dispatchEvent (https://editor.construct.net/r355/main.js:1256:399) at window.jm.Oc (https://editor.construct.net/r355/components/editors/layoutView/layoutView.js:110:51) at HTMLDivElement. (https://editor.construct.net/r355/components/editors/layoutView/layoutView.js:98:151)
Construct version: r355
URL: https://editor.construct.net/r355/
Date: Wed Aug 23 2023 16:02:02 GMT+0300 (Восточная Европа, летнее время)
Uptime: 21.8 s

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
