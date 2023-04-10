## Problem description

Construct crashes.

## Attach a .c3p

[crash_maxwell_tilemap_tile_editor_and_tilemap_editor_r336s.zip](https://github.com/WilsonPercival/WilsonPercival/files/11193908/crash_maxwell_tilemap_tile_editor_and_tilemap_editor_r336s.zip)

## Steps to reproduce

1. Open a project.
2. Select the instance of the tilemap.
3. Double click on the tile and double click on the tilemap (this should be fast).

## Observed result

https://user-images.githubusercontent.com/91274932/230996163-7d0031b0-3f36-486d-a160-a811bb1337c6.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r336s

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of null (reading 'qHa') @ TypeError: Cannot read properties of null (reading 'qHa') at m0a.ixa (https://editor.construct.net/r336/projectResources.js:771:266) at m0a.DPb (https://editor.construct.net/r336/projectResources.js:772:344)
Stack: TypeError: Cannot read properties of null (reading 'qHa') at m0a.ixa (https://editor.construct.net/r336/projectResources.js:771:266) at m0a.DPb (https://editor.construct.net/r336/projectResources.js:772:344)
Construct version: r336
URL: https://editor.construct.net/
Date: Mon Apr 10 2023 23:21:48 GMT+0300 (Восточная Европа, летнее время)
Uptime: 27.2 s

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
