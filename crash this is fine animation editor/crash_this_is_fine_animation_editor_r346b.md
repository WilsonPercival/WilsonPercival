## Problem description

Construct crashes.

## Attach a .c3p

save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/11829005/save_open_project.zip)

## Steps to reproduce

1. Create a new project.
2. Create a sprite.
3. Create `Animation 2`.
4. Fill in the image.
5. Add a folder.
6. Drag `Animation 2` to the folder.
7. Delete the folder.
8. Click `Undo`.
9. Delete the folder.
10. Close the animation editor.
11. Click `Undo`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/a807cce3-9e32-4bbf-a5d1-1b72a47cda13

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r346b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: animation frame has no content @ Error: animation frame has no content at d.kJ (https://editor.construct.net/r346/projectResources.js:781:341) at d.Nka (https://editor.construct.net/r346/projectResources.js:774:92) at p_a.Dua.nf (https://editor.construct.net/r346/projectResources.js:1933:234) at B1a.Xuc.nf (https://editor.construct.net/r346/projectResources.js:1891:408) at B1a.Xuc.nf (https://editor.construct.net/r346/projectResources.js:1988:209) at window.wc.Fh (https://editor.construct.net/r346/projectResources.js:1895:319) at d.Fh (https://editor.construct.net/r346/projectResources.js:1770:242) at https://editor.construct.net/r346/main.js:2931:359 at window.hjb.Fh (https://editor.construct.net/r346/main.js:2931:410)
Stack: Error: animation frame has no content at d.kJ (https://editor.construct.net/r346/projectResources.js:781:341) at d.Nka (https://editor.construct.net/r346/projectResources.js:774:92) at p_a.Dua.nf (https://editor.construct.net/r346/projectResources.js:1933:234) at B1a.Xuc.nf (https://editor.construct.net/r346/projectResources.js:1891:408) at B1a.Xuc.nf (https://editor.construct.net/r346/projectResources.js:1988:209) at window.wc.Fh (https://editor.construct.net/r346/projectResources.js:1895:319) at d.Fh (https://editor.construct.net/r346/projectResources.js:1770:242) at https://editor.construct.net/r346/main.js:2931:359 at window.hjb.Fh (https://editor.construct.net/r346/main.js:2931:410)
Construct version: r346
URL: https://editor.construct.net/r346/
Date: Thu Jun 22 2023 08:06:23 GMT+0300 (Восточная Европа, летнее время)
Uptime: 142.3 s

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
