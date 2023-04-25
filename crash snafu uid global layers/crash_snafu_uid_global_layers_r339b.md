## Problem description

Construct crashes.

## Attach a .c3p

[crash_snafu_uid_global_layers_r339b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11327045/crash_snafu_uid_global_layers_r339b.zip)

## Steps to reproduce

1. Open a project.
2. Cut out `Layout 1`.
3. Delete the sprite instance.
4. Insert `Layout 1`.
5. Click `Undo` twice.

## Observed result

https://user-images.githubusercontent.com/91274932/234409986-384a4ac7-7d0d-4682-a15f-c5576285dc0b.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r339b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: reserving UID that is already in use
Stack: Error at pa.q_a (https://editor.construct.net/r339/main.js:1130:314) at window.assert (https://editor.construct.net/r339/main.js:1045:353) at d.h3a (https://editor.construct.net/r339/projectResources.js:1741:290) at d.Th (https://editor.construct.net/r339/projectResources.js:794:261) at d.Th (https://editor.construct.net/r339/projectResources.js:812:299) at d.Ji (https://editor.construct.net/r339/projectResources.js:578:121) at d.Ji (https://editor.construct.net/r339/projectResources.js:794:166) at d.Yi (https://editor.construct.net/r339/projectResources.js:577:420) at gZa.Tz.lf (https://editor.construct.net/r339/projectResources.js:1891:74) at window.vc.Ch (https://editor.construct.net/r339/projectResources.js:1888:319)
Construct version: r339
URL: https://editor.construct.net/r339/
Date: Wed Apr 26 2023 00:13:21 GMT+0300 (Восточная Европа, летнее время)
Uptime: 35.8 s

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
