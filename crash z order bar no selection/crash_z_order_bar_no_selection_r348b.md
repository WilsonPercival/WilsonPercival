## Problem description

Construct crashes.

## Attach a .c3p

[crash_z_order_bar_no_selection_r348b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11950990/crash_z_order_bar_no_selection_r348b.zip)

## Steps to reproduce

1. Open a project. Note that the `Z Order Bar` must be open, otherwise the crash will not occur.
2. Duplicate `Layout 1`.
3. On `Layout 1` make `Layer 1` non-global.
4. Click `Undo` twice.
5. Click on the sprite and select `Z Order -> Move to layer -> Layer 1`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/572657f9-2ca2-4295-9f95-ccbd47e49b66

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r348b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r348/components/editors/layoutView/layoutView.js, line 214, col 277
Message: Uncaught Error: no selection
Stack: Error: no selection at aeb.Dwa (https://editor.construct.net/r348/components/editors/layoutView/layoutView.js:214:283) at CY (https://editor.construct.net/r348/components/bars/zOrderBar/zOrderBar.js:1:47) at xnb (https://editor.construct.net/r348/components/bars/zOrderBar/zOrderBar.js:1:501) at Array.iFb (https://editor.construct.net/r348/components/bars/zOrderBar/zOrderBar.js:17:317) at window.rjb.dispatchEvent (https://editor.construct.net/r348/main.js:1261:42) at vab (https://editor.construct.net/r348/components/editors/layoutView/layoutView.js:2:120) at ER (https://editor.construct.net/r348/components/editors/layoutView/layoutView.js:25:266) at https://editor.construct.net/r348/components/editors/layoutView/layoutView.js:9:473 at https://editor.construct.net/r348/main.js:1909:388
Construct version: r348
URL: https://editor.construct.net/r348/
Date: Tue Jul 04 2023 18:36:51 GMT+0300 (Восточная Европа, летнее время)
Uptime: 65 s

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
