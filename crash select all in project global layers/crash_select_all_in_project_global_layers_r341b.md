## Problem description

Construct crashes.

## Attach a .c3p

[crash_select_all_in_project_global_layers_r341b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11433407/crash_select_all_in_project_global_layers_r341b.zip)

## Steps to reproduce

1. Open a project.
2. Select the sprite.
3. Rename `Layer 0` to `Layer 1`.
4. In the right ear, click on the sprite and select `Select all in project`.
5. In the left ear, change the value of the `Layer` parameter to `Layer 0`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/74c9fcc2-3dc4-4214-876f-2c70994986ac

## Expected result

Construct does not crash.

## More details

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/0e6a203b-acf2-4b6c-b2ba-83788a20a95a

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r341b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r341/projectResources.js, line 1369, col 365
Message: Uncaught Error: instance not on this layer
Stack: Error: instance not on this layer at d.Iuc (https://editor.construct.net/r341/projectResources.js:1369:371) at d.gob (https://editor.construct.net/r341/projectResources.js:819:477) at https://editor.construct.net/r341/components/bars/propertiesBar/propertiesBar.js:18:424 at ch (https://editor.construct.net/r341/main.js:371:492) at Aq.g.K.ajb.TU (https://editor.construct.net/r341/main.js:1557:418) at Aq.g.K.ajb.MG (https://editor.construct.net/r341/main.js:1558:71) at HTMLSelectElement.nt (https://editor.construct.net/r341/main.js:1556:343)
Construct version: r341
URL: https://editor.construct.net/r341/
Date: Tue May 09 2023 19:00:10 GMT+0300 (Восточная Европа, летнее время)
Uptime: 30.9 s

Platform information
Product: Construct 3 r341 (beta)
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
