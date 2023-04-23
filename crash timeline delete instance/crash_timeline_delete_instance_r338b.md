## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_delete_instance_r338b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11303804/crash_timeline_delete_instance_r338b.zip)

## Steps to reproduce

1. Open a project.
2. Delete the sprite instance in the timeline.
3. Click `Undo`.

## Observed result

https://user-images.githubusercontent.com/91274932/233841639-edef303d-30b0-4d55-bef6-fcaf6cb41e13.mp4

## Expected result

Construct does not crash.

## More details

https://user-images.githubusercontent.com/91274932/233851861-53fbfa6e-8916-45bc-a13e-a4ddc77e9574.mp4

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r338b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: track already in look up map
Stack: Error at qa.tXa (https://editor.construct.net/r338/main.js:1105:314) at window.assert (https://editor.construct.net/r338/main.js:1020:353) at d.psa (https://editor.construct.net/r338/projectResources.js:1014:225) at d.rqb (https://editor.construct.net/r338/projectResources.js:1109:473) at d.Qh (https://editor.construct.net/r338/projectResources.js:1110:80) at d.bi (https://editor.construct.net/r338/projectResources.js:579:122) at d.Ri (https://editor.construct.net/r338/projectResources.js:578:421) at d.Ri (https://editor.construct.net/r338/projectResources.js:1109:379) at j_a.Fnb.jf (https://editor.construct.net/r338/projectResources.js:1968:430) at window.tc.Ah (https://editor.construct.net/r338/projectResources.js:1888:319)
Construct version: r338
URL: https://editor.construct.net/r338/
Date: Sun Apr 23 2023 15:44:24 GMT+0300 (Восточная Европа, летнее время)
Uptime: 49.6 s

Platform information
Product: Construct 3 r338 (beta)
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
