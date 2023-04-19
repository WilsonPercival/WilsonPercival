## Problem description

Construct crashes.

## Attach a .c3p

[crash_particles_delete_object_r338b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11276060/crash_particles_delete_object_r338b.zip)

## Steps to reproduce

1. Open a project.
2. Select the `Particles` instance.
3. In the left ear, set `Object` to `Text`.
4. Remove the sprite from the project.

## Observed result

https://user-images.githubusercontent.com/91274932/233153847-6be326fb-a3b1-4f7f-83c9-59eb1331c058.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r338b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r338/projectResources.js, line 777, col 335
Message: Uncaught Error: animation frame has no content
Stack: Error: animation frame has no content at d.zI (https://editor.construct.net/r338/projectResources.js:777:341) at d.Kja (https://editor.construct.net/r338/projectResources.js:782:464) at sKb.Instance.zg (https://editor.construct.net/r338/main.js:2052:87) at sKb.Instance.zg (https://editor.construct.net/r338/plugins/allEditorPlugins.js:169:330) at sKb.Instance.Xf (https://editor.construct.net/r338/plugins/allEditorPlugins.js:167:323) at d.Xf (https://editor.construct.net/r338/projectResources.js:847:336) at d.Xf (https://editor.construct.net/r338/projectResources.js:1378:489) at d.Xf (https://editor.construct.net/r338/projectResources.js:1335:324) at F6b (https://editor.construct.net/r338/components/editors/layoutView/layoutView.js:89:318)
Construct version: r338
URL: https://editor.construct.net/r338/
Date: Wed Apr 19 2023 15:48:55 GMT+0300 (Восточная Европа, летнее время)
Uptime: 61.4 s

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
