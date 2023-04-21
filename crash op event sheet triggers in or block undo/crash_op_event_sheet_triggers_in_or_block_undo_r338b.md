## Problem description

Construct crashes.

## Attach a .c3p

[crash_op_event_sheet_triggers_in_or_block_undo_r338b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11299471/crash_op_event_sheet_triggers_in_or_block_undo_r338b.zip)

## Steps to reproduce

1. Open a project.
2. Go to the event editor.
3. Cut out the variable. A window will open, click `Delete`.
4. Click `Make AND block`.
5. Insert a variable.
6. Click `Make OR block`.
7. Move the variable above the event block.
8. Click `Undo` twice.

## Observed result

https://user-images.githubusercontent.com/91274932/233740170-490328f1-8d36-41d4-825d-e42097673137.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r338b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: too many triggers for normal block @ Error: too many triggers for normal block at d.Bwa (https://editor.construct.net/r338/projectResources.js:1455:175) at EZa.yfc.jf (https://editor.construct.net/r338/projectResources.js:1950:203) at window.tc.Ah (https://editor.construct.net/r338/projectResources.js:1888:319) at d.Ah (https://editor.construct.net/r338/projectResources.js:1763:62) at https://editor.construct.net/r338/main.js:2516:359 at window.ufb.Ah (https://editor.construct.net/r338/main.js:2516:403)
Stack: Error: too many triggers for normal block at d.Bwa (https://editor.construct.net/r338/projectResources.js:1455:175) at EZa.yfc.jf (https://editor.construct.net/r338/projectResources.js:1950:203) at window.tc.Ah (https://editor.construct.net/r338/projectResources.js:1888:319) at d.Ah (https://editor.construct.net/r338/projectResources.js:1763:62) at https://editor.construct.net/r338/main.js:2516:359 at window.ufb.Ah (https://editor.construct.net/r338/main.js:2516:403)
Construct version: r338
URL: https://editor.construct.net/r338/
Date: Sat Apr 22 2023 00:00:51 GMT+0300 (Восточная Европа, летнее время)
Uptime: 286 s

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
