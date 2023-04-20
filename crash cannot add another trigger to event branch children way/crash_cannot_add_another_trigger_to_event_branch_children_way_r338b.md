## Problem description

Construct crashes. I have already reported this: https://github.com/Scirra/Construct-bugs/issues/6914

You refused to fix it, citing that the steps in it try to bypass the checks and are not similar to those that other users could repeat. I found easier steps to reproduce.

## Attach a .c3p

[crash_cannot_add_another_trigger_to_event_branch_children_way_r338b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11289089/crash_cannot_add_another_trigger_to_event_branch_children_way_r338b.zip)

## Steps to reproduce

1. Open a project.
2. Go to the event editor.
3. Copy the condition.
4. Insert a condition.
5. Drag the second event sub-event below the first event.

## Observed result

https://user-images.githubusercontent.com/91274932/233448542-aa43eff3-4f46-4b98-bcbe-d0ac0dd9219d.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r338b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r338/projectResources.js, line 1415, col 127
Message: Uncaught Error: cannot add another trigger to event branch
Stack: Error: cannot add another trigger to event branch at d.Wf (https://editor.construct.net/r338/projectResources.js:1415:133) at d.kQ (https://editor.construct.net/r338/components/editors/eventSheetView/eventSheetView.js:206:473) at d.vDc (https://editor.construct.net/r338/components/editors/eventSheetView/eventSheetView.js:202:186) at d.Ed (https://editor.construct.net/r338/components/editors/eventSheetView/eventSheetView.js:194:211) at HTMLDocument.ie (https://editor.construct.net/r338/components/editors/eventSheetView/eventSheetView.js:156:118)
Construct version: r338
URL: https://editor.construct.net/r338/
Date: Thu Apr 20 2023 20:39:24 GMT+0300 (Восточная Европа, летнее время)
Uptime: 45.1 s

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
