## Problem description

Construct crashes.

## Attach a .c3p

save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/11325608/save_open_project.zip)

## Steps to reproduce

1. Create a new project.
2. Create a new event sheet.
3. Drag the event sheet down to unpin it.
4. Drag the unpinned event sheet off the screen to open it in a new window. While it is opening, quickly switch to the previous window by clicking on it and pressing `E` to open the window for creating a new event.
5. When the popup opens, click `Add event`.
6. On the last window, click `Cancel`.

## Observed result

https://user-images.githubusercontent.com/91274932/234366181-8e08b72a-ac8e-4f13-82c3-af1d18e5cb7d.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r339b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r339/main.js, line 1350, col 369
Message: Uncaught Error: cannot pop last context
Stack: Error: cannot pop last context at csa.L (https://editor.construct.net/r339/main.js:1350:375) at bsa.L (https://editor.construct.net/r339/main.js:1349:163) at nG.g.K.RXc.PQ (https://editor.construct.net/r339/main.js:1388:260) at nG.g.K.RXc.Jg (https://editor.construct.net/r339/main.js:1391:179) at nG.g.K.RXc.Ud (https://editor.construct.net/r339/main.js:1390:428) at Fc.onclick (https://editor.construct.net/r339/projectResources.js:3024:189)
Construct version: r339
URL: https://editor.construct.net/r339/
Date: Tue Apr 25 2023 20:54:47 GMT+0300 (Восточная Европа, летнее время)
Uptime: 43.6 s

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
