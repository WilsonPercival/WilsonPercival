## Problem description

Construct crashes.

## Attach a .c3p

fun.capx: [fun.zip](https://github.com/WilsonPercival/WilsonPercival/files/11840329/fun.zip)

save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/11840326/save_open_project.zip)

## Steps to reproduce

1. Create a new project in Construct 2.
2. Drag an image from a folder on your computer to the layout editor.
3. Save the project and open it in Construct 3.
4. Open the sprite image editor.
5. Copy the animation.
6. Insert animation.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/27928627-6d3a-44f1-ac2b-25d9e76aad38

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r346b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: frame not found @ Error: frame not found at d.stb (https://editor.construct.net/r346/projectResources.js:764:434) at d.bp (https://editor.construct.net/r346/projectResources.js:776:342) at https://editor.construct.net/r346/projectResources.js:2057:393 at bh (https://editor.construct.net/r346/main.js:371:235) at CCG.Sg.g.K.gnb.ju (https://editor.construct.net/r346/main.js:1533:148) at new CCG.Sg.g.K.gnb (https://editor.construct.net/r346/main.js:1533:97) at pa.j (https://editor.construct.net/r346/main.js:1136:44) at CCG.Zg.g.K.Uxa.ce (https://editor.construct.net/r346/main.js:1601:422) at q2a.Aoc.ga (https://editor.construct.net/r346/projectResources.js:2057:325) at Oy (https://editor.construct.net/r346/projectResources.js:155:465)
Stack: Error: frame not found at d.stb (https://editor.construct.net/r346/projectResources.js:764:434) at d.bp (https://editor.construct.net/r346/projectResources.js:776:342) at https://editor.construct.net/r346/projectResources.js:2057:393 at bh (https://editor.construct.net/r346/main.js:371:235) at CCG.Sg.g.K.gnb.ju (https://editor.construct.net/r346/main.js:1533:148) at new CCG.Sg.g.K.gnb (https://editor.construct.net/r346/main.js:1533:97) at pa.j (https://editor.construct.net/r346/main.js:1136:44) at CCG.Zg.g.K.Uxa.ce (https://editor.construct.net/r346/main.js:1601:422) at q2a.Aoc.ga (https://editor.construct.net/r346/projectResources.js:2057:325) at Oy (https://editor.construct.net/r346/projectResources.js:155:465)
Construct version: r346
URL: https://editor.construct.net/r346/
Date: Thu Jun 22 2023 23:10:00 GMT+0300 (Восточная Европа, летнее время)
Uptime: 631.9 s

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
