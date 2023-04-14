## Problem description

Construct crashes.

## Attach a .c3p

[crash_barbossa_advanced_timeline_keyframe_r337_2b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11236593/crash_barbossa_advanced_timeline_keyframe_r337_2b.zip)

## Steps to reproduce

1. Open a project.
2. Move the sprite to create a rollback point.
3. Step on the black dot and pull it to the side. Do not release the mouse button.
4. Press `Ctrl + Z`.
5. Release the mouse.

## Observed result

https://user-images.githubusercontent.com/91274932/232142944-e8e49b6f-3297-4990-b12c-848edfb5fa1e.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r337-2b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: keyframe view has no associated track view
Stack: Error at qa.pXa (https://editor.construct.net/r337-2/main.js:1106:314) at window.assert (https://editor.construct.net/r337-2/main.js:1021:353) at Y_ (https://editor.construct.net/r337-2/components/bars/timelineBar/timelineBar.js:7:139) at window.Jb.ctc.iB (https://editor.construct.net/r337-2/components/bars/timelineBar/timelineBar.js:533:3) at HTMLDocument.YI (https://editor.construct.net/r337-2/components/bars/timelineBar/timelineBar.js:529:385)
Construct version: r337.2
URL: https://editor.construct.net/r337-2/
Date: Fri Apr 14 2023 22:40:53 GMT+0300 (Восточная Европа, летнее время)
Uptime: 48.5 s

Platform information
Product: Construct 3 r337.2 (beta)
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
