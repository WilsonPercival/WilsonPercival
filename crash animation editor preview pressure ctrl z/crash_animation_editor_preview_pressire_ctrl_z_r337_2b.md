## Problem description

Construct crashes.

## Attach a .c3p

[crash_animation_editor_preview_pressure_ctrl_z_r337_2b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11226810/crash_animation_editor_preview_pressure_ctrl_z_r337_2b.zip)

## Steps to reproduce

1. Open a project.
2. Open the sprite animation editor.
3. Create 9 new animations. If you can't repeat the crash, create 100 new animations.
4. Click `Preview`.
5. Hold `Ctrl + Z`.

## Observed result

https://user-images.githubusercontent.com/91274932/231892647-40626307-2e0b-43f5-ac8f-679b26d2db0f.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r337-2b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: animation frame has no content @ Error: animation frame has no content at d.yI (https://editor.construct.net/r337-2/projectResources.js:777:341) at d.mb (https://editor.construct.net/r337-2/projectResources.js:782:182) at https://editor.construct.net/r337-2/projectResources.js:359:164 at async hKa (https://editor.construct.net/r337-2/projectResources.js:349:366)
Stack: Error: animation frame has no content at d.yI (https://editor.construct.net/r337-2/projectResources.js:777:341) at d.mb (https://editor.construct.net/r337-2/projectResources.js:782:182) at https://editor.construct.net/r337-2/projectResources.js:359:164 at async hKa (https://editor.construct.net/r337-2/projectResources.js:349:366)
Construct version: r337.2
URL: https://editor.construct.net/r337-2/
Date: Fri Apr 14 2023 00:51:36 GMT+0300 (Восточная Европа, летнее время)
Uptime: 110.9 s

Platform information
Product: Construct 3 r337.2 (beta)
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
