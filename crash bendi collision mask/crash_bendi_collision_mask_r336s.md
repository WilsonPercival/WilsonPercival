## Problem description

Construct crashes.

## Attach a .c3p

[crash_bendi_collision_mask_r336s.zip](https://github.com/WilsonPercival/WilsonPercival/files/11183660/crash_bendi_collision_mask_r336s.zip)

## Steps to reproduce

1. Open a project.
2. Open the sprite image editor.
3. Click `Edit the collision polygon`.
4. Right-click on the `Rectangle` tool.
5. Press `R`.
6. Drag the top of the collision mask down.
7. Click Undo.
8. Click Redo.
9. Pull on the edge.

## Observed result

https://user-images.githubusercontent.com/91274932/230731770-e1b4ea11-976d-46ae-9e29-0b878beb5940.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r336s

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r336/main.js, line 1029, col 401
Message: Uncaught TypeError: expected finite number
Stack: TypeError: expected finite number at O.m (https://editor.construct.net/r336/main.js:1029:407) at d.ZWb (https://editor.construct.net/r336/projectResources.js:725:476) at d.XB (https://editor.construct.net/r336/projectResources.js:726:171) at sHa (https://editor.construct.net/r336/projectResources.js:239:129) at HA.ufc.Jc (https://editor.construct.net/r336/projectResources.js:2397:408) at HTMLElement.Uwb (https://editor.construct.net/r336/projectResources.js:2387:284)
Construct version: r336
URL: https://editor.construct.net/
Date: Sat Apr 08 2023 18:32:42 GMT+0300 (Восточная Европа, летнее время)
Uptime: 57.7 s

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
