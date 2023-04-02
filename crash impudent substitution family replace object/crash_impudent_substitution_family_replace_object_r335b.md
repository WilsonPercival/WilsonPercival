## Problem description

Construct crashes.

## Attach a .c3p

[crash_impudent_substitution_family_replace_object_r335b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11132206/crash_impudent_substitution_family_replace_object_r335b.zip)

## Steps to reproduce

1. Open a project.
2. Cut out the family.
3. Remove `Sprite` from the project.
4. Add `Browser`.
5. Rename the `Browser` object to `Sprite`.
6. Insert a family.

## Observed result

https://user-images.githubusercontent.com/91274932/229353326-c29fa798-bade-4dda-9a2d-d442044022bf.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r335b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: d.E5 is not a function @ TypeError: d.E5 is not a function at Xdb (https://editor.construct.net/r335/components/bars/projectBar/projectBar.js:2:167) at window.XS.wLa (https://editor.construct.net/r335/components/bars/projectBar/projectBar.js:96:129) at Array. (https://editor.construct.net/r335/components/bars/projectBar/projectBar.js:92:136) at CCG.oh.g.K.aKa.dispatchEvent (https://editor.construct.net/r335/main.js:1233:399) at CCG.oh.g.K.aKa.ZM (https://editor.construct.net/r335/main.js:1602:339) at CCG.oh.g.K.aKa.fG (https://editor.construct.net/r335/main.js:1597:24) at d.yk (https://editor.construct.net/r335/main.js:1625:321) at DU (https://editor.construct.net/r335/components/bars/projectBar/projectBar.js:1:166) at Deb (https://editor.construct.net/r335/components/bars/projectBar/projectBar.js:37:231) at async window.afb.gd (https://editor.construct.net/r335/main.js:2517:205)
Stack: TypeError: d.E5 is not a function at Xdb (https://editor.construct.net/r335/components/bars/projectBar/projectBar.js:2:167) at window.XS.wLa (https://editor.construct.net/r335/components/bars/projectBar/projectBar.js:96:129) at Array. (https://editor.construct.net/r335/components/bars/projectBar/projectBar.js:92:136) at CCG.oh.g.K.aKa.dispatchEvent (https://editor.construct.net/r335/main.js:1233:399) at CCG.oh.g.K.aKa.ZM (https://editor.construct.net/r335/main.js:1602:339) at CCG.oh.g.K.aKa.fG (https://editor.construct.net/r335/main.js:1597:24) at d.yk (https://editor.construct.net/r335/main.js:1625:321) at DU (https://editor.construct.net/r335/components/bars/projectBar/projectBar.js:1:166) at Deb (https://editor.construct.net/r335/components/bars/projectBar/projectBar.js:37:231) at async window.afb.gd (https://editor.construct.net/r335/main.js:2517:205)
Construct version: r335
URL: https://editor.construct.net/r335/
Date: Sun Apr 02 2023 15:24:45 GMT+0300 (Восточная Европа, летнее время)
Uptime: 62.6 s

Platform information
Product: Construct 3 r335 (beta)
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
