## Problem description

Construct crashes. I have already reported this: https://github.com/Scirra/Construct-bugs/issues/6533

## Attach a .c3p

[baba.zip](https://github.com/WilsonPercival/WilsonPercival/files/11243038/baba.zip)

## Steps to reproduce

1. Open a project.
2. Create a folder in the `Sounds` folder.
3. Drag the file to the new folder.
4. Right click on the new folder to open the context menu.
5. Click `Cut` in the context menu. You will notice that the new folder is still selected and there is a huge window to take the next step.
6. Press `Ctrl + V`.

## Observed result

https://user-images.githubusercontent.com/91274932/232332066-7d72b9aa-9de9-46f3-bc03-99868e86bebf.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r337-2b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: unexpected type @ TypeError: unexpected type at O.i (https://editor.construct.net/r337-2/main.js:1036:147) at CCG.qh (https://editor.construct.net/r337-2/main.js:378:410) at AU (https://editor.construct.net/r337-2/components/bars/projectBar/projectBar.js:1:156) at ufb (https://editor.construct.net/r337-2/components/bars/projectBar/projectBar.js:69:236) at async window.qfb.Uc (https://editor.construct.net/r337-2/main.js:2524:205)
Stack: TypeError: unexpected type at O.i (https://editor.construct.net/r337-2/main.js:1036:147) at CCG.qh (https://editor.construct.net/r337-2/main.js:378:410) at AU (https://editor.construct.net/r337-2/components/bars/projectBar/projectBar.js:1:156) at ufb (https://editor.construct.net/r337-2/components/bars/projectBar/projectBar.js:69:236) at async window.qfb.Uc (https://editor.construct.net/r337-2/main.js:2524:205)
Construct version: r337.2
URL: https://editor.construct.net/r337-2/
Date: Sun Apr 16 2023 20:33:10 GMT+0300 (Восточная Европа, летнее время)
Uptime: 90 s

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
