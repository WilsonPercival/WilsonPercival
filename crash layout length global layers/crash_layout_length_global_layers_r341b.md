## Problem description

Construct crashes.

## Attach a .c3p

[crash_layout_length_global_layers_r341b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11435153/crash_layout_length_global_layers_r341b.zip)

## Steps to reproduce

1. Open a project.
2. Drag the sprite to `Layer 1`. This is done by grabbing an instance of the sprite on the layout and dragging it onto the layer with the cursor. Please note that if you move the instance to the layer through the left ear, the crash will not work.
3. Go to `Layout 2`.
4. Cut out `Layout 1`.
5. Make `Layer 1` non-global.
6. Insert layout and open it.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/076b95c7-fb5d-4753-9be3-470b48fb78a1

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r341b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of null (reading 'length') @ TypeError: Cannot read properties of null (reading 'length') at d.xza (https://editor.construct.net/r341/projectResources.js:1861:184) at d.hLc (https://editor.construct.net/r341/projectResources.js:1858:224) at d.Tq (https://editor.construct.net/r341/projectResources.js:1852:303) at d.Tq (https://editor.construct.net/r341/projectResources.js:1343:267) at window.fm.jLa (https://editor.construct.net/r341/components/editors/layoutView/layoutView.js:121:472) at eS (https://editor.construct.net/r341/components/editors/layoutView/layoutView.js:49:289) at window.SVb.NC (https://editor.construct.net/r341/components/editors/layoutView/layoutView.js:139:30)
Stack: TypeError: Cannot read properties of null (reading 'length') at d.xza (https://editor.construct.net/r341/projectResources.js:1861:184) at d.hLc (https://editor.construct.net/r341/projectResources.js:1858:224) at d.Tq (https://editor.construct.net/r341/projectResources.js:1852:303) at d.Tq (https://editor.construct.net/r341/projectResources.js:1343:267) at window.fm.jLa (https://editor.construct.net/r341/components/editors/layoutView/layoutView.js:121:472) at eS (https://editor.construct.net/r341/components/editors/layoutView/layoutView.js:49:289) at window.SVb.NC (https://editor.construct.net/r341/components/editors/layoutView/layoutView.js:139:30)
Construct version: r341
URL: https://editor.construct.net/r341/
Date: Tue May 09 2023 21:44:44 GMT+0300 (Восточная Европа, летнее время)
Uptime: 108.6 s

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
