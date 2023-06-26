## Problem description

Construct crashes.

## Attach a .c3p

[crash_copy_paste_animation_r346b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11870949/crash_copy_paste_animation_r346b.zip)

## Steps to reproduce

1. Open a project.
2. Open the sprite animation editor.
3. Copy the animation.
4. Insert animation.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/54ab1907-217d-4688-8cac-c6240386fda8

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
Date: Mon Jun 26 2023 18:17:15 GMT+0300 (Восточная Европа, летнее время)
Uptime: 53.6 s

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
