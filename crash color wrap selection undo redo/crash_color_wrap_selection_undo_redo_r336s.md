## Problem description

Construct crashes.

## Attach a .c3p

[crash_color_wrap_selection_undo_redo_r336s.zip](https://github.com/WilsonPercival/WilsonPercival/files/11178838/crash_color_wrap_selection_undo_redo_r336s.zip)

## Steps to reproduce

1. Open a project.
2. Duplicate the sprite instance.
3. Select both instances and hit `Wrap selection`.
4. In the left ear, click on the white rectangle, which opens the `Color picker`.
5. Don't pick a color. Instead, trick Construct and click on the `Color` text. `Color picker` will close.
6. Press `Ctrl + Z`. Please note that if you click with the mouse, the bug will not work.
7. Press `Ctrl + Y`. Please note that if you click with the mouse, the bug will not work.
8. Drag the edge of the selection.

## Observed result



## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r336s

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r336/components/editors/layoutView/layoutView.js, line 252, col 506
Message: Uncaught TypeError: Cannot read properties of null (reading 'width')
Stack: TypeError: Cannot read properties of null (reading 'width') at ccb.X7 (https://editor.construct.net/r336/components/editors/layoutView/layoutView.js:252:506) at ccb.m7 (https://editor.construct.net/r336/components/editors/layoutView/layoutView.js:251:248) at ccb.Tf (https://editor.construct.net/r336/components/editors/layoutView/layoutView.js:250:267) at Array.sf (https://editor.construct.net/r336/components/editors/layoutView/layoutView.js:246:368) at window.Pl.dispatchEvent (https://editor.construct.net/r336/main.js:1233:399) at window.Pl.Tf (https://editor.construct.net/r336/components/editors/layoutView/layoutView.js:109:253) at HTMLDocument.sf (https://editor.construct.net/r336/components/editors/layoutView/layoutView.js:92:435)
Construct version: r336
URL: https://editor.construct.net/
Date: Thu Apr 06 2023 22:39:57 GMT+0300 (Восточная Европа, летнее время)
Uptime: 61.7 s

Platform information
Product: Construct 3 r336 (stable)
Browser: Chrome 109.0.5414.120
Browser engine: Chromium
Context: browser
Operating system: Windows NT 0.1.0
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/109.0.0.0 Safari/537.36
Language setting: en-US

WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (Google)
Renderer: ANGLE (Google, Vulkan 1.3.0 (SwiftShader Device (Subzero) (0x0000C0DE)), SwiftShader driver)
Major performance caveat: yes
Maximum texture size: 8192
Point size range: 1 to 1023
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, OES_draw_buffers_indexed, OES_texture_float_linear, WEBGL_compressed_texture_astc, WEBGL_compressed_texture_etc, WEBGL_compressed_texture_etc1, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_lose_context, WEBGL_multi_draw, OVR_multiview2

</details>
