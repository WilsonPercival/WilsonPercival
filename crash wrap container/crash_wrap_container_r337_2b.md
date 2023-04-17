## Problem description

Construct crashes.

## Attach a .c3p

[crash_wrap_container_r337_2b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11255568/crash_wrap_container_r337_2b.zip)

## Steps to reproduce

1. Open a project.
2. Select the sprite.
3. In the left ear, change `Select mode` to `Wrap`.
4. Deselect the sprite.
5. Select the sprite.
6. Drag the edge of the selection.

## Observed result

https://user-images.githubusercontent.com/91274932/232605326-e694db2e-e822-4eec-b0db-b306738d8f02.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r337-2b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r337-2/main.js, line 1031, col 401
Message: Uncaught TypeError: expected finite number
Stack: TypeError: expected finite number at O.A (https://editor.construct.net/r337-2/main.js:1031:407) at d.qg (https://editor.construct.net/r337-2/projectResources.js:824:464) at dbb.Zob (https://editor.construct.net/r337-2/components/editors/layoutView/layoutView.js:242:16) at dbb.Lnb (https://editor.construct.net/r337-2/components/editors/layoutView/layoutView.js:241:485) at abb (https://editor.construct.net/r337-2/components/editors/layoutView/layoutView.js:72:258) at mbb (https://editor.construct.net/r337-2/components/editors/layoutView/layoutView.js:76:242) at pbb (https://editor.construct.net/r337-2/components/editors/layoutView/layoutView.js:76:134) at qcb.j8 (https://editor.construct.net/r337-2/components/editors/layoutView/layoutView.js:253:337) at qcb.x7 (https://editor.construct.net/r337-2/components/editors/layoutView/layoutView.js:251:248) at qcb.Uf (https://editor.construct.net/r337-2/components/editors/layoutView/layoutView.js:250:267)
Construct version: r337.2
URL: https://editor.construct.net/r337-2/
Date: Mon Apr 17 2023 23:22:25 GMT+0300 (Восточная Европа, летнее время)
Uptime: 42.2 s

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
