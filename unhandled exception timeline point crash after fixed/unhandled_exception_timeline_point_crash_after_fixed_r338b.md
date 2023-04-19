## Problem description

Construct crashes. I have already reported this: https://github.com/Scirra/Construct-bugs/issues/6570

## Attach a .c3p

Construct didn't let me save the project after a crash.

## Steps to reproduce

1. Create a new project.
2. Create a new sprite.
3. Drag the sprite to the `Timeline` panel.
4. Press the `Editing mode` button.
5. Hold and continue to hold the red flag. Move him slowly to the right.
6. Press the `S` key to create a point.
7. Press the `S` key to create the point again.
8. Release the red flag.
9. Drag the last created point far to the right.
10. Delete the sprite instance.
11. Click `Undo`.
12. Drag the last created point to the left so that it is in the same place as the previous point.

## Observed result

https://user-images.githubusercontent.com/91274932/233193077-bda435fb-bf89-45dd-ac42-cb287326ded0.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r338b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r338/projectResources.js, line 1192, col 194
Message: Uncaught TypeError: Cannot read properties of null (reading 'aa')
Stack: TypeError: Cannot read properties of null (reading 'aa') at d.aa (https://editor.construct.net/r338/projectResources.js:1192:194) at d.Om (https://editor.construct.net/r338/projectResources.js:1173:292) at Om.next () at d.Mta (https://editor.construct.net/r338/projectResources.js:1175:17) at d.oo (https://editor.construct.net/r338/projectResources.js:1178:398) at d.Qzc (https://editor.construct.net/r338/components/editors/layoutView/layoutView.js:168:42) at d.rQ (https://editor.construct.net/r338/components/editors/layoutView/layoutView.js:162:272) at Array. (https://editor.construct.net/r338/components/editors/layoutView/layoutView.js:157:48) at window.Wl.dispatchEvent (https://editor.construct.net/r338/main.js:1235:42) at F6b (https://editor.construct.net/r338/components/editors/layoutView/layoutView.js:91:460)
Construct version: r338
URL: https://editor.construct.net/r338/
Date: Wed Apr 19 2023 21:11:49 GMT+0300 (Восточная Европа, летнее время)
Uptime: 58.5 s

Platform information
Product: Construct 3 r338 (beta)
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
