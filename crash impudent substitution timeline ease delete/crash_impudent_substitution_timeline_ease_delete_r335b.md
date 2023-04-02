## Problem description

Construct crashes.

## Attach a .c3p

[crash_impudent_substitution_timeline_ease_delete_r335b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11132754/crash_impudent_substitution_timeline_ease_delete_r335b.zip)

## Steps to reproduce

1. Open a project.
2. Cut out the timeline.
3. Remove `Ease 1`.
4. Insert a timeline.

## Observed result

https://user-images.githubusercontent.com/91274932/229366602-12bc4be4-c787-4179-88b7-078ddd7e544a.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r335b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: unsupported ease mode
Stack: Error at qa.bXa (https://editor.construct.net/r335/main.js:1104:289) at window.assert (https://editor.construct.net/r335/main.js:1019:353) at d.Swc (https://editor.construct.net/r335/projectResources.js:1036:352) at d.gr (https://editor.construct.net/r335/projectResources.js:966:40) at d.gr (https://editor.construct.net/r335/projectResources.js:997:136) at d.wh (https://editor.construct.net/r335/projectResources.js:977:425) at d.wh (https://editor.construct.net/r335/projectResources.js:1029:65) at d.Ha (https://editor.construct.net/r335/projectResources.js:1032:9) at u (https://editor.construct.net/r335/components/bars/projectBar/projectBar.js:74:485) at mfb (https://editor.construct.net/r335/components/bars/projectBar/projectBar.js:75:343)
Construct version: r335
URL: https://editor.construct.net/r335/
Date: Sun Apr 02 2023 19:33:20 GMT+0300 (Восточная Европа, летнее время)
Uptime: 357.3 s

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
