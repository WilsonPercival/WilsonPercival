## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_and_failed_to_open_project_audio_r351b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12210295/crash_timeline_and_failed_to_open_project_audio_r351b.zip)

## Steps to reproduce

1. Open a project.
2. Remove `map.webm` from the project.
3. Close the project.
4. Open the project.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/3e1f6d60-e32f-425a-9d4d-13f4a97bb3a5

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r351b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r351/components/bars/timelineBar/timelineBar.js, line 467, col 74
Message: Uncaught TypeError: Cannot set properties of undefined (setting 'state')
Stack: TypeError: Cannot set properties of undefined (setting 'state') at F4.jOa (https://editor.construct.net/r351/components/bars/timelineBar/timelineBar.js:467:74) at F4.uNa (https://editor.construct.net/r351/components/bars/timelineBar/timelineBar.js:468:84) at window.Jb.Bi.ga (https://editor.construct.net/r351/components/bars/timelineBar/timelineBar.js:309:70) at G1.LCc (https://editor.construct.net/r351/components/bars/timelineBar/timelineBar.js:145:326) at pub.IFc (https://editor.construct.net/r351/components/bars/timelineBar/timelineBar.js:71:268) at d (https://editor.construct.net/r351/components/bars/timelineBar/timelineBar.js:69:397)
Construct version: r351
URL: https://editor.construct.net/r351/
Date: Mon Jul 31 2023 01:44:25 GMT+0300 (Восточная Европа, летнее время)
Uptime: 16.9 s

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
