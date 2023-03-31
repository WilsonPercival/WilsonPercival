## Problem description

Construct crashes.

## Attach a .c3p

[crash_family_layouts_undo_r335b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11122849/crash_family_layouts_undo_r335b.zip)

## Steps to reproduce

1. Open a project.
2. Cut out `Layout 2`.
3. Remove `Joey` from the project.
4. Add a private variable to the family.
5. Insert layout. A window will appear, click `OK`.
6. Press `Undo` two times.

## Observed result

https://user-images.githubusercontent.com/91274932/229149470-b9beade7-d7ed-4945-bb1e-8d0eb7251f7a.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r335b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: object class name already in use @ Error: object class name already in use at d.b3a (https://editor.construct.net/r335/projectResources.js:1730:264) at d.Mh (https://editor.construct.net/r335/projectResources.js:661:380) at d.Mh (https://editor.construct.net/r335/projectResources.js:711:371) at d.bWb (https://editor.construct.net/r335/projectResources.js:711:500) at d.Mh (https://editor.construct.net/r335/projectResources.js:680:425) at d.Ai (https://editor.construct.net/r335/projectResources.js:572:122) at d.Ai (https://editor.construct.net/r335/projectResources.js:657:145) at d.Ai (https://editor.construct.net/r335/projectResources.js:661:323) at d.Ai (https://editor.construct.net/r335/projectResources.js:680:148) at d.Ni (https://editor.construct.net/r335/projectResources.js:571:421)
Stack: Error: object class name already in use at d.b3a (https://editor.construct.net/r335/projectResources.js:1730:264) at d.Mh (https://editor.construct.net/r335/projectResources.js:661:380) at d.Mh (https://editor.construct.net/r335/projectResources.js:711:371) at d.bWb (https://editor.construct.net/r335/projectResources.js:711:500) at d.Mh (https://editor.construct.net/r335/projectResources.js:680:425) at d.Ai (https://editor.construct.net/r335/projectResources.js:572:122) at d.Ai (https://editor.construct.net/r335/projectResources.js:657:145) at d.Ai (https://editor.construct.net/r335/projectResources.js:661:323) at d.Ai (https://editor.construct.net/r335/projectResources.js:680:148) at d.Ni (https://editor.construct.net/r335/projectResources.js:571:421)
Construct version: r335
URL: https://editor.construct.net/r335/
Date: Fri Mar 31 2023 17:16:30 GMT+0300 (Восточная Европа, летнее время)
Uptime: 43.8 s

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
