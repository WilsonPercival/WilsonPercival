## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_copy_paste_keyframes_after_width_angle_r346b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11844060/crash_timeline_copy_paste_keyframes_after_width_angle_r346b.zip)

## Steps to reproduce

1. Open a project.
2. Click on the sprite.
3. On the timeline panel, click `Editing mode`.
4. Change the width of the sprite.
5. Change the angle of the sprite.
6. Click `Set keyframes`.
7. Select the key points that are in the same position as the red flag.
8. Click `Copy a selection of keyframes`.
9. Move the red flag to the right.
10. Click `Paste a selection of keyframes at the current time marker`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/8fc0e358-5089-48c2-b1d6-66bbdd6eef79

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r346b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r346/main.js, line 1136, col 65
Message: Uncaught TypeError: expected finite number
Stack: TypeError: expected finite number at Q.B (https://editor.construct.net/r346/main.js:1054:407) at EJ.KC (https://editor.construct.net/r346/projectResources.js:1220:135) at EJ.DC (https://editor.construct.net/r346/projectResources.js:1217:317) at JTa.cf (https://editor.construct.net/r346/projectResources.js:1275:304) at d.Lwb (https://editor.construct.net/r346/projectResources.js:1198:77) at new d (https://editor.construct.net/r346/projectResources.js:1195:172) at pa.j (https://editor.construct.net/r346/main.js:1136:44) at d.Eg (https://editor.construct.net/r346/projectResources.js:1196:183) at https://editor.construct.net/r346/projectResources.js:1027:469 at Array.map ()
Construct version: r346
URL: https://editor.construct.net/r346/
Date: Fri Jun 23 2023 06:48:50 GMT+0300 (Восточная Европа, летнее время)
Uptime: 33.6 s

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
