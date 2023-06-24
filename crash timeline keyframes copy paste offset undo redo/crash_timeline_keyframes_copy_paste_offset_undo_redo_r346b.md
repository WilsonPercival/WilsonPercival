## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_keyframes_copy_paste_offset_undo_redo_r346b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11856850/crash_timeline_keyframes_copy_paste_offset_undo_redo_r346b.zip)

## Steps to reproduce

1. Open a project.
2. Click on the sprite.
3. Click `Editing mode`
4. Click `Set keyframes`.
5. Select the key points that are in the same position as the red flag.
6. Click `Copy a selection of keyframes`.
7. Move the red flag to `0.90s`.
8. Click `Paste a selection of keyframes at the current time marker`.
9. Select all points except the first ones.
10. Click `Copy a selection of keyframes`.
11. Move the red flag to `0.80s`.
12. Click `Paste a selection of keyframes at the current time marker`.
13. Move the red flag to `0.70s`.
14. Click `Paste a selection of keyframes at the current time marker`.
15. Select all points except the first ones.
16. Move the selected points one position to the right.
17. Click `Undo`.
18. Click `Redo`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/cfd45dc4-7ac1-4d21-9974-9c173ff94ebd

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r346b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: keyframe already at time @ Error: keyframe already at time at d.yMa (https://editor.construct.net/r346/projectResources.js:1147:163) at https://editor.construct.net/r346/projectResources.js:1150:26 at d.gLc (https://editor.construct.net/r346/projectResources.js:1049:325) at d.P5a (https://editor.construct.net/r346/projectResources.js:1049:389) at d.yIa (https://editor.construct.net/r346/projectResources.js:1050:51) at d.Ha (https://editor.construct.net/r346/projectResources.js:1149:497) at AZa.Dm.nf (https://editor.construct.net/r346/projectResources.js:1905:41) at self.vj.nf (https://editor.construct.net/r346/projectResources.js:1891:494) at window.wc.wj (https://editor.construct.net/r346/projectResources.js:1896:143) at d.wj (https://editor.construct.net/r346/projectResources.js:1770:311)
Stack: Error: keyframe already at time at d.yMa (https://editor.construct.net/r346/projectResources.js:1147:163) at https://editor.construct.net/r346/projectResources.js:1150:26 at d.gLc (https://editor.construct.net/r346/projectResources.js:1049:325) at d.P5a (https://editor.construct.net/r346/projectResources.js:1049:389) at d.yIa (https://editor.construct.net/r346/projectResources.js:1050:51) at d.Ha (https://editor.construct.net/r346/projectResources.js:1149:497) at AZa.Dm.nf (https://editor.construct.net/r346/projectResources.js:1905:41) at self.vj.nf (https://editor.construct.net/r346/projectResources.js:1891:494) at window.wc.wj (https://editor.construct.net/r346/projectResources.js:1896:143) at d.wj (https://editor.construct.net/r346/projectResources.js:1770:311)
Construct version: r346
URL: https://editor.construct.net/r346/
Date: Sat Jun 24 2023 14:53:16 GMT+0300 (Восточная Европа, летнее время)
Uptime: 107.9 s

Platform information
Product: Construct 3 r346 (beta)
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
