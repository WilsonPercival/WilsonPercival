## Problem description

Construct crashes.

## Attach a .c3p

Save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/12774417/save_open_project.zip)

## Steps to reproduce

1. Create a new project.
2. Go to `Event sheet editor`.
3. Press `J` to create a new script block. It will open automatically. Remove the selection by clicking on the empty space.
4. Press and hold `Ctrl`.
5. Double click on the script block and press `Z` (this should be instant).

Don't be discouraged if you don't get it right the first time.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/ef181c34-0add-49fc-812c-2c866e4c4c84

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r360b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: cannot select detached view
Stack: Error at oa.r0a (https://editor.construct.net/r360/main.js:1120:314) at window.assert (https://editor.construct.net/r360/main.js:1035:353) at d.ep (https://editor.construct.net/r360/components/editors/eventSheetView/eventSheetView.js:176:64) at d.UCc (https://editor.construct.net/r360/components/editors/eventSheetView/eventSheetView.js:177:145) at d.YJc (https://editor.construct.net/r360/components/editors/eventSheetView/eventSheetView.js:201:454) at d.Kd (https://editor.construct.net/r360/components/editors/eventSheetView/eventSheetView.js:193:474) at HTMLDocument.me (https://editor.construct.net/r360/components/editors/eventSheetView/eventSheetView.js:155:118)
Construct version: r360
URL: https://editor.construct.net/r360/
Date: Sat Sep 30 2023 13:10:57 GMT+0300 (Восточная Европа, летнее время)
Uptime: 391.9 s

Platform information
Product: Construct 3 r360 (beta)
Browser: Chrome 117.0.5938.92
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
