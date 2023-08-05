## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_and_failed_to_open_project_audio_r351b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12267181/crash_timeline_and_failed_to_open_project_audio_r351b.zip)

## Steps to reproduce

1. Open a project.
2. Close `Timeline Bar`. Please note that if you do not have it open, then you will not be able to close it. And this means that the crash will not happen.
3. Extract `map.webm` from `fun` folder.
4. Copy `Timeline 1`.
5. Insert a timeline. A window will pop up, click `OK`.
6. Close the project.
7. Open the project.
8. Double click on `Timeline 1` to open the `Timeline Bar`.
9. Close the project.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/a8d1f13f-42c5-4b08-a5b2-6b94817d8550

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r352b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of null (reading '$i') @ TypeError: Cannot read properties of null (reading '$i') at window.Jb.DK.A (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:320:365) at window.Jb.Bi.A (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:307:268) at G1.ou (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:135:130) at G1.kYb (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:139:87) at d.U3b (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:48:90) at d.Mc (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:47:119) at e2.ZG (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:174:192) at Array. (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:169:9) at window.Mjb.dispatchEvent (https://editor.construct.net/r352/main.js:1257:42) at CCG.Un (https://editor.construct.net/r352/main.js:900:438)
Stack: TypeError: Cannot read properties of null (reading '$i') at window.Jb.DK.A (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:320:365) at window.Jb.Bi.A (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:307:268) at G1.ou (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:135:130) at G1.kYb (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:139:87) at d.U3b (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:48:90) at d.Mc (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:47:119) at e2.ZG (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:174:192) at Array. (https://editor.construct.net/r352/components/bars/timelineBar/timelineBar.js:169:9) at window.Mjb.dispatchEvent (https://editor.construct.net/r352/main.js:1257:42) at CCG.Un (https://editor.construct.net/r352/main.js:900:438)
Construct version: r352
URL: https://editor.construct.net/r352/
Date: Sat Aug 05 2023 16:17:38 GMT+0300 (Восточная Европа, летнее время)
Uptime: 23.9 s

Platform information
Product: Construct 3 r352 (beta)
Browser: Chrome 115.0.5790.170
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
