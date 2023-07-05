## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_swap_copy_undo_r348b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11960403/crash_timeline_swap_copy_undo_r348b.zip)

## Steps to reproduce

1. Open a project.
2. Click `Editing mode`.
3. Move the sprite.
4. Create `Sprite2`.
5. In the timeline panel, click on `Sprite` and select `Swap instance`. A window will open, select `Sprite2` in it and click `OK`.
6. On the timeline panel, select all points except the first ones.
7. Click `Copy a selection of keyframes`.
8. Press `Ctrl + Z` 4 times. Please note that if you click the `Undo` button with the cursor, the crash will not occur.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/3c0f5e49-5419-4ede-953f-95ea9d48c6d0

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r348b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: g.ra is not a function @ TypeError: g.ra is not a function at d.uc (https://editor.construct.net/r348/components/bars/propertiesBar/propertiesBar.js:114:159) at d.fN (https://editor.construct.net/r348/components/bars/propertiesBar/propertiesBar.js:114:421) at d.jO (https://editor.construct.net/r348/components/bars/propertiesBar/propertiesBar.js:114:470) at Array. (https://editor.construct.net/r348/components/bars/propertiesBar/propertiesBar.js:105:55) at window.rjb.dispatchEvent (https://editor.construct.net/r348/main.js:1261:42) at ev (https://editor.construct.net/r348/projectResources.js:45:319) at d.gi (https://editor.construct.net/r348/projectResources.js:675:501) at d.gi (https://editor.construct.net/r348/projectResources.js:696:28) at d.Li (https://editor.construct.net/r348/projectResources.js:585:6) at d.Li (https://editor.construct.net/r348/projectResources.js:671:129)
Stack: TypeError: g.ra is not a function at d.uc (https://editor.construct.net/r348/components/bars/propertiesBar/propertiesBar.js:114:159) at d.fN (https://editor.construct.net/r348/components/bars/propertiesBar/propertiesBar.js:114:421) at d.jO (https://editor.construct.net/r348/components/bars/propertiesBar/propertiesBar.js:114:470) at Array. (https://editor.construct.net/r348/components/bars/propertiesBar/propertiesBar.js:105:55) at window.rjb.dispatchEvent (https://editor.construct.net/r348/main.js:1261:42) at ev (https://editor.construct.net/r348/projectResources.js:45:319) at d.gi (https://editor.construct.net/r348/projectResources.js:675:501) at d.gi (https://editor.construct.net/r348/projectResources.js:696:28) at d.Li (https://editor.construct.net/r348/projectResources.js:585:6) at d.Li (https://editor.construct.net/r348/projectResources.js:671:129)
Construct version: r348
URL: https://editor.construct.net/r348/
Date: Wed Jul 05 2023 20:07:40 GMT+0300 (Восточная Европа, летнее время)
Uptime: 51.9 s

Platform information
Product: Construct 3 r348 (beta)
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
