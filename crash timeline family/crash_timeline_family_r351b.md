## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_family_r351b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12188226/crash_timeline_family_r351b.zip)

## Steps to reproduce

1. Open a project.
2. Cut out `Layout 2`.
3. Remove `Sprite` from the project.
4. Insert layout.
5. Click `Undo` twice.
6. Duplicate `Timeline 1`.

## Observed result

[observed.webm](https://github.com/WilsonPercival/WilsonPercival/assets/91274932/6a39d925-b66f-4a43-865a-f17e7f89bdd7)

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r351b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: behavior type not found @ Error: behavior type not found at d.nOa (https://editor.construct.net/r351/projectResources.js:1197:112) at d.Ha (https://editor.construct.net/r351/projectResources.js:1194:501) at d.L3b (https://editor.construct.net/r351/projectResources.js:1199:132) at d.kLc (https://editor.construct.net/r351/projectResources.js:1171:62) at d.Ha (https://editor.construct.net/r351/projectResources.js:1169:448) at d.Ha (https://editor.construct.net/r351/projectResources.js:1174:180) at d.kLc (https://editor.construct.net/r351/projectResources.js:1170:501) at d.Ha (https://editor.construct.net/r351/projectResources.js:1169:448) at d.Ha (https://editor.construct.net/r351/projectResources.js:1127:330) at d.M3b (https://editor.construct.net/r351/projectResources.js:1134:9)
Stack: Error: behavior type not found at d.nOa (https://editor.construct.net/r351/projectResources.js:1197:112) at d.Ha (https://editor.construct.net/r351/projectResources.js:1194:501) at d.L3b (https://editor.construct.net/r351/projectResources.js:1199:132) at d.kLc (https://editor.construct.net/r351/projectResources.js:1171:62) at d.Ha (https://editor.construct.net/r351/projectResources.js:1169:448) at d.Ha (https://editor.construct.net/r351/projectResources.js:1174:180) at d.kLc (https://editor.construct.net/r351/projectResources.js:1170:501) at d.Ha (https://editor.construct.net/r351/projectResources.js:1169:448) at d.Ha (https://editor.construct.net/r351/projectResources.js:1127:330) at d.M3b (https://editor.construct.net/r351/projectResources.js:1134:9)
Construct version: r351
URL: https://editor.construct.net/r351/
Date: Thu Jul 27 2023 23:47:27 GMT+0300 (Восточная Европа, летнее время)
Uptime: 113.3 s

Platform information
Product: Construct 3 r351 (beta)
Browser: Chrome 115.0.5790.110
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/115.0.0.0 Safari/537.36
Language setting: en-US

WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (AMD)
Renderer: ANGLE (AMD, AMD Radeon(TM) Graphics Direct3D11 vs_5_0 ps_5_0, D3D11)
Major performance caveat: no
Maximum texture size: 16384
Point size range: 1 to 1024
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_disjoint_timer_query_webgl2, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, EXT_texture_norm16, KHR_parallel_shader_compile, OES_draw_buffers_indexed, OES_texture_float_linear, OVR_multiview2, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw, WEBGL_provoking_vertex

</details>
