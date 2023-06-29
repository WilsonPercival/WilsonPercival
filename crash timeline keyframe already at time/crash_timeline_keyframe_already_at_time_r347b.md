## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_keyframe_already_at_time_r347b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11901509/crash_timeline_keyframe_already_at_time_r347b.zip)

## Steps to reproduce

1. Open a project.
2. Select all points except the first ones.
3. Move the selected points one position to the right.
4. Click `Undo`.
5. Click `Redo`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/57279898-aa2a-4608-9a5f-8ab4823ea5af

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r347b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: keyframe already at time @ Error: keyframe already at time at d.EMa (https://editor.construct.net/r347/projectResources.js:1152:163) at https://editor.construct.net/r347/projectResources.js:1155:26 at d.pLc (https://editor.construct.net/r347/projectResources.js:1054:175) at d.X5a (https://editor.construct.net/r347/projectResources.js:1054:239) at d.EIa (https://editor.construct.net/r347/projectResources.js:1054:402) at d.Ha (https://editor.construct.net/r347/projectResources.js:1154:497) at IZa.Gm.nf (https://editor.construct.net/r347/projectResources.js:1913:41) at self.wj.nf (https://editor.construct.net/r347/projectResources.js:1899:494) at window.yc.xj (https://editor.construct.net/r347/projectResources.js:1904:143) at d.xj (https://editor.construct.net/r347/projectResources.js:1778:311)
Stack: Error: keyframe already at time at d.EMa (https://editor.construct.net/r347/projectResources.js:1152:163) at https://editor.construct.net/r347/projectResources.js:1155:26 at d.pLc (https://editor.construct.net/r347/projectResources.js:1054:175) at d.X5a (https://editor.construct.net/r347/projectResources.js:1054:239) at d.EIa (https://editor.construct.net/r347/projectResources.js:1054:402) at d.Ha (https://editor.construct.net/r347/projectResources.js:1154:497) at IZa.Gm.nf (https://editor.construct.net/r347/projectResources.js:1913:41) at self.wj.nf (https://editor.construct.net/r347/projectResources.js:1899:494) at window.yc.xj (https://editor.construct.net/r347/projectResources.js:1904:143) at d.xj (https://editor.construct.net/r347/projectResources.js:1778:311)
Construct version: r347
URL: https://editor.construct.net/r347/
Date: Thu Jun 29 2023 05:38:14 GMT+0300 (Восточная Европа, летнее время)
Uptime: 37.3 s

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
