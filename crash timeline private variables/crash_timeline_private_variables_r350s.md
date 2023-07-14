## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_private_variables_r350s.zip](https://github.com/WilsonPercival/WilsonPercival/files/12050481/crash_timeline_private_variables_r350s.zip)

## Steps to reproduce

1. Open a project.
2. Click `Editing mode`.
3. Click `Set keyframes`.
4. Click on the sprite in the layout editor.
5. In the left ear, click `Instance variables`.
6. A window will open, select a variable and change its type to `String` and click `OK`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/f71f9de2-9aeb-4a65-8c52-3867f80d8a73

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r350s

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r350/main.js, line 1136, col 65
Message: Uncaught TypeError: d.replace is not a function
Stack: TypeError: d.replace is not a function at lha (https://editor.construct.net/r350/main.js:366:253) at Aq.g.K.iob.z9 (https://editor.construct.net/r350/main.js:1553:93) at Aq.g.K.iob.A9 (https://editor.construct.net/r350/main.js:1552:450) at new Aq.g.K.iob (https://editor.construct.net/r350/main.js:1550:343) at pa.j (https://editor.construct.net/r350/main.js:1136:44) at Hq.g.K.V1.eka (https://editor.construct.net/r350/main.js:1583:266) at eib (https://editor.construct.net/r350/components/bars/propertiesBar/propertiesBar.js:23:3) at CCG.ba.GU (https://editor.construct.net/r350/components/bars/propertiesBar/propertiesBar.js:147:291) at d.m1b (https://editor.construct.net/r350/components/bars/propertiesBar/propertiesBar.js:116:14) at Sc.eu.vV (https://editor.construct.net/r350/components/bars/propertiesBar/propertiesBar.js:102:497)
Construct version: r350
URL: https://editor.construct.net/
Date: Fri Jul 14 2023 15:27:35 GMT+0300 (Восточная Европа, летнее время)
Uptime: 87.9 s

Platform information
Product: Construct 3 r350 (stable)
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
