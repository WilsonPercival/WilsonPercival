## Problem description

Construct crashes.

## Attach a .c3p

[crash_z_order_bar_instance_is_not_part_of_layer_r347b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11903851/crash_z_order_bar_instance_is_not_part_of_layer_r347b.zip)

## Steps to reproduce

1. Open a project.
2. On the `Z Order` panel, click on `Marky`.
3. Press and hold `Shift`.
4. On the `Z Order` panel, click on `Joey`.
5. Release `Shift`.
6. On the `Z Order` panel, drag the selected instances to your mutual friend `DeeDee` on `Layer 2`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/ffc99d87-616a-4875-8cf0-8750ff2dea9d

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r347b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r347/projectResources.js, line 1381, col 103
Message: Uncaught Error: instance is not part of layer
Stack: Error: instance is not part of layer at d.oxc (https://editor.construct.net/r347/projectResources.js:1381:109) at d.vWb (https://editor.construct.net/r347/projectResources.js:1383:61) at Mnb (https://editor.construct.net/r347/components/bars/zOrderBar/zOrderBar.js:6:437) at CCG.ba.Qna (https://editor.construct.net/r347/components/bars/zOrderBar/zOrderBar.js:33:247) at Array.mFb (https://editor.construct.net/r347/components/bars/zOrderBar/zOrderBar.js:17:401) at CCG.qh.g.K.ZMa.dispatchEvent (https://editor.construct.net/r347/main.js:1260:399) at th (https://editor.construct.net/r347/main.js:379:372) at d.Jd (https://editor.construct.net/r347/main.js:1644:13) at Ub.me (https://editor.construct.net/r347/main.js:1635:89)
Construct version: r347
URL: https://editor.construct.net/r347/
Date: Thu Jun 29 2023 11:40:41 GMT+0300 (Восточная Европа, летнее время)
Uptime: 141.4 s

Platform information
Product: Construct 3 r347 (beta)
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
