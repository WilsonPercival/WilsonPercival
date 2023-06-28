## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_add_properties_enable_collisions_r346b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11891203/crash_timeline_add_properties_enable_collisions_r346b.zip)

## Steps to reproduce

1. Open a project.
2. In the timeline panel, click on the sprite and select `Add properties`.
3. A window will open, select `Enable collisions` and click `Ok`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/a3c8497d-41fa-48bf-84fb-21f21865dbef

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r347b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: expected function @ TypeError: expected function at Q.Nb (https://editor.construct.net/r347/main.js:1058:38) at pa.j (https://editor.construct.net/r347/main.js:1136:26) at d.Qsb (https://editor.construct.net/r347/projectResources.js:1180:190) at new d (https://editor.construct.net/r347/projectResources.js:1175:262) at pa.j (https://editor.construct.net/r347/main.js:1136:44) at d.fI (https://editor.construct.net/r347/projectResources.js:1104:92) at d.IOb (https://editor.construct.net/r347/projectResources.js:1105:40) at d.pjc (https://editor.construct.net/r347/projectResources.js:1105:161) at https://editor.construct.net/r347/components/bars/timelineBar/timelineBar.js:258:393
Stack: TypeError: expected function at Q.Nb (https://editor.construct.net/r347/main.js:1058:38) at pa.j (https://editor.construct.net/r347/main.js:1136:26) at d.Qsb (https://editor.construct.net/r347/projectResources.js:1180:190) at new d (https://editor.construct.net/r347/projectResources.js:1175:262) at pa.j (https://editor.construct.net/r347/main.js:1136:44) at d.fI (https://editor.construct.net/r347/projectResources.js:1104:92) at d.IOb (https://editor.construct.net/r347/projectResources.js:1105:40) at d.pjc (https://editor.construct.net/r347/projectResources.js:1105:161) at https://editor.construct.net/r347/components/bars/timelineBar/timelineBar.js:258:393
Construct version: r347
URL: https://editor.construct.net/r347/
Date: Wed Jun 28 2023 09:53:54 GMT+0300 (Восточная Европа, летнее время)
Uptime: 34.7 s

Platform information
Product: Construct 3 r347 (beta)
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
