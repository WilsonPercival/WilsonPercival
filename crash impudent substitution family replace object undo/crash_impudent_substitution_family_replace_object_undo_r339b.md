## Problem description

Construct crashes.

## Attach a .c3p

[crash_impudent_substitution_family_replace_object_r335b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11324527/crash_impudent_substitution_family_replace_object_r335b.zip)

## Steps to reproduce

1. Open a project.
2. Cut out the family.
3. Remove `Sprite` from the project.
4. Add `Browser`.
5. Rename the `Browser` object to `Sprite`.
6. Insert a family.
7. Press `Undo` to the end.

## Observed result

https://user-images.githubusercontent.com/91274932/234337010-20aa5dbf-7241-4a64-a8bb-5ab86eb48958.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r339b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: object class name already in use @ Error: object class name already in use at d.y6a (https://editor.construct.net/r339/projectResources.js:1739:264) at d.Th (https://editor.construct.net/r339/projectResources.js:668:380) at d.Th (https://editor.construct.net/r339/projectResources.js:718:368) at d.Ji (https://editor.construct.net/r339/projectResources.js:578:121) at d.Ji (https://editor.construct.net/r339/projectResources.js:664:145) at d.Ji (https://editor.construct.net/r339/projectResources.js:668:323) at d.Yi (https://editor.construct.net/r339/projectResources.js:577:420) at d.Yi (https://editor.construct.net/r339/projectResources.js:668:249) at gZa.Tz.lf (https://editor.construct.net/r339/projectResources.js:1891:74) at window.vc.Ch (https://editor.construct.net/r339/projectResources.js:1888:319)
Stack: Error: object class name already in use at d.y6a (https://editor.construct.net/r339/projectResources.js:1739:264) at d.Th (https://editor.construct.net/r339/projectResources.js:668:380) at d.Th (https://editor.construct.net/r339/projectResources.js:718:368) at d.Ji (https://editor.construct.net/r339/projectResources.js:578:121) at d.Ji (https://editor.construct.net/r339/projectResources.js:664:145) at d.Ji (https://editor.construct.net/r339/projectResources.js:668:323) at d.Yi (https://editor.construct.net/r339/projectResources.js:577:420) at d.Yi (https://editor.construct.net/r339/projectResources.js:668:249) at gZa.Tz.lf (https://editor.construct.net/r339/projectResources.js:1891:74) at window.vc.Ch (https://editor.construct.net/r339/projectResources.js:1888:319)
Construct version: r339
URL: https://editor.construct.net/r339/
Date: Tue Apr 25 2023 18:55:10 GMT+0300 (Восточная Европа, летнее время)
Uptime: 67.4 s

Platform information
Product: Construct 3 r339 (beta)
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
