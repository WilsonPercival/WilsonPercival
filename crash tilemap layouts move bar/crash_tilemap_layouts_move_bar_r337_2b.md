## Problem description

Construct crashes.

## Attach a .c3p

save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/11255992/save_open_project.zip)

## Steps to reproduce

1. Create a new project.
2. Create a `Tilemap`.
3. Open `Tilemap Bar`.
4. Add a new layout.
5. Attach the tilemap panel.
6. Remove the tilemap from the project.
7. Remove `Tilemap` from the project.
8. Double click on a tile to open the tile editor.
9. Get creative.

## Observed result

https://user-images.githubusercontent.com/91274932/232614919-bb6efc4a-7d39-451f-951e-bb757dbf9d01.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r337-2b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: animation frame has no content @ Error: animation frame has no content at d.yI (https://editor.construct.net/r337-2/projectResources.js:777:341) at d.la (https://editor.construct.net/r337-2/projectResources.js:786:6) at d.la (https://editor.construct.net/r337-2/projectResources.js:709:376) at new $Xa.tm (https://editor.construct.net/r337-2/projectResources.js:1896:427) at dz (https://editor.construct.net/r337-2/projectResources.js:329:427) at MJa (https://editor.construct.net/r337-2/projectResources.js:330:32) at Array. (https://editor.construct.net/r337-2/projectResources.js:414:237) at Hx.g.K.Rb.dispatchEvent (https://editor.construct.net/r337-2/main.js:1236:42) at Array. (https://editor.construct.net/r337-2/projectResources.js:2174:295) at S1a.cWa.dispatchEvent (https://editor.construct.net/r337-2/main.js:1236:42)
Stack: Error: animation frame has no content at d.yI (https://editor.construct.net/r337-2/projectResources.js:777:341) at d.la (https://editor.construct.net/r337-2/projectResources.js:786:6) at d.la (https://editor.construct.net/r337-2/projectResources.js:709:376) at new $Xa.tm (https://editor.construct.net/r337-2/projectResources.js:1896:427) at dz (https://editor.construct.net/r337-2/projectResources.js:329:427) at MJa (https://editor.construct.net/r337-2/projectResources.js:330:32) at Array. (https://editor.construct.net/r337-2/projectResources.js:414:237) at Hx.g.K.Rb.dispatchEvent (https://editor.construct.net/r337-2/main.js:1236:42) at Array. (https://editor.construct.net/r337-2/projectResources.js:2174:295) at S1a.cWa.dispatchEvent (https://editor.construct.net/r337-2/main.js:1236:42)
Construct version: r337.2
URL: https://editor.construct.net/r337-2/
Date: Tue Apr 18 2023 00:14:51 GMT+0300 (Восточная Европа, летнее время)
Uptime: 242.8 s

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
