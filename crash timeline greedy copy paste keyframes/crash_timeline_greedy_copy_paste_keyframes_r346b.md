## Problem description

Construct crashes.

## Attach a .c3p

save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/11827279/save_open_project.zip)

## Steps to reproduce

1. Create a new project.
2. Create a sprite.
3. Drag the sprite to the timeline panel.
4. Select all key points.
5. Click `Copy a selection of keyframes`.
6. Click on the red flag and continue to hold without releasing.
7. Press `Ctrl + V` to paste the copied keypoints.
8. Release the red flag.
9. Move the cursor over the key point, which is located on the right in the middle. Note that the cursor should take the form of a finger pointer. This means that the cursor is hovering over the key point, and not at the red flag (when the cursor is in the form of a palm squeeze).
10. Click and hold the mouse without releasing.
11. Press `Ctrl + Z`.
12. Release the cursor. Note that it is now always in the shape of a palm squeeze, and you can move the red flag by clicking, even outside of the timeline panel.
13. Press `Ctrl + Z` until you roll back to the very beginning.
14. Click on the layout editor.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/6b0e062c-cac6-4068-ba30-3298a3445ab5

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r346b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r346/components/bars/timelineBar/timelineBar.js, line 202, col 507
Message: Uncaught TypeError: Cannot read properties of null (reading 'left')
Stack: TypeError: Cannot read properties of null (reading 'left') at j2.Mvb (https://editor.construct.net/r346/components/bars/timelineBar/timelineBar.js:202:507) at HTMLDivElement. (https://editor.construct.net/r346/components/bars/timelineBar/timelineBar.js:192:360) at ea.a8 (https://editor.construct.net/r346/main.js:1080:283) at HTMLDivElement.QW (https://editor.construct.net/r346/components/bars/timelineBar/timelineBar.js:118:280)
Construct version: r346
URL: https://editor.construct.net/r346/
Date: Thu Jun 22 2023 03:00:28 GMT+0300 (Восточная Европа, летнее время)
Uptime: 66.7 s

Platform information
Product: Construct 3 r346 (beta)
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
