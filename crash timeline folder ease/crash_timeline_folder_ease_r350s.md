## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_folder_ease_r350s.zip](https://github.com/WilsonPercival/WilsonPercival/files/12062108/crash_timeline_folder_ease_r350s.zip)

## Steps to reproduce

1. Open a project.
2. On the timeline panel, click on the folder.
3. In the left ear, next to the `Ease` parameter, select `Linear`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/420eee19-b1ef-4ac6-80b1-3749e17ab3dc

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r350s

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r350/components/bars/propertiesBar/propertiesBar.js, line 81, col 157
Message: Uncaught TypeError: d.vWc is not a function
Stack: TypeError: d.vWc is not a function at Bq.g.K.pjb.rn (https://editor.construct.net/r350/components/bars/propertiesBar/propertiesBar.js:81:157) at Bq.g.K.pjb.pp (https://editor.construct.net/r350/main.js:1557:482) at Bq.g.K.pjb.TG (https://editor.construct.net/r350/main.js:1558:48) at HTMLSelectElement.ot (https://editor.construct.net/r350/main.js:1556:343)
Construct version: r350
URL: https://editor.construct.net/
Date: Sun Jul 16 2023 00:09:31 GMT+0300 (Восточная Европа, летнее время)
Uptime: 122.4 s

Platform information
Product: Construct 3 r350 (stable)
Browser: Chrome 114.0.5735.199
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36
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
