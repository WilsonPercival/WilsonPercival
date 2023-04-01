## Problem description

Construct crashes.

## Attach a .c3p

[crash_event_sheet_tween_ease_delete_r335b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11130778/crash_event_sheet_tween_ease_delete_r335b.zip)

## Steps to reproduce

1. Open a project.
2. Cut out the event.
3. Remove `Ease 1`.
4. Insert an event.
5. Copy the event.

## Observed result

https://user-images.githubusercontent.com/91274932/229320048-893ff702-5c5a-479b-9609-a9950adfe3e8.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r335b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r335/projectResources.js, line 1623, col 129
Message: Uncaught Error: unsupported object
Stack: Error: unsupported object at window.Bfb.uq (https://editor.construct.net/r335/projectResources.js:1623:135) at window.Bfb.la (https://editor.construct.net/r335/projectResources.js:1623:365) at d.RYb (https://editor.construct.net/r335/projectResources.js:1480:446) at MCa (https://editor.construct.net/r335/projectResources.js:99:376) at d.la (https://editor.construct.net/r335/projectResources.js:1480:338) at https://editor.construct.net/r335/projectResources.js:1449:155 at Array.map () at d.la (https://editor.construct.net/r335/projectResources.js:1449:146) at https://editor.construct.net/r335/components/editors/eventSheetView/eventSheetView.js:229:31 at Array.map ()
Construct version: r335
URL: https://editor.construct.net/r335/
Date: Sun Apr 02 2023 01:57:47 GMT+0300 (Восточная Европа, летнее время)
Uptime: 49.4 s

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
