## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_keyframe_effect_copy_undo_paste_r350s.zip](https://github.com/WilsonPercival/WilsonPercival/files/12064821/crash_timeline_keyframe_effect_copy_undo_paste_r350s.zip)

## Steps to reproduce

1. Open a project.
2. Click `Editing mode`.
3. Click `Set keyframes`.
4. Select the key point opposite `Hue`.
5. Click `Copy a selection of keyframes`.
6. Click `Undo`.
7. Click `Paste a selection of keyframes at the current time marker`.

## Observed result

[observed.webm](https://github.com/WilsonPercival/WilsonPercival/assets/91274932/9afdf758-1459-40d1-b79f-c66ea08a40c0)

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r350s

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r350/main.js, line 1059, col 141
Message: Uncaught TypeError: unexpected type
Stack: TypeError: unexpected type at Q.i (https://editor.construct.net/r350/main.js:1059:147) at d.wub (https://editor.construct.net/r350/projectResources.js:1031:193) at d.Iqc (https://editor.construct.net/r350/projectResources.js:1033:496) at T2.dka (https://editor.construct.net/r350/components/bars/timelineBar/timelineBar.js:263:304) at k (https://editor.construct.net/r350/components/bars/timelineBar/timelineBar.js:30:466) at Itb (https://editor.construct.net/r350/components/bars/timelineBar/timelineBar.js:31:330) at window.Jb.Pob.Ei (https://editor.construct.net/r350/components/bars/timelineBar/timelineBar.js:543:175) at u1.T6a (https://editor.construct.net/r350/components/bars/timelineBar/timelineBar.js:68:402) at Sq.g.K.dk.jka.Mxb (https://editor.construct.net/r350/components/bars/timelineBar/timelineBar.js:54:6) at Wh (https://editor.construct.net/r350/main.js:395:253)
Construct version: r350
URL: https://editor.construct.net/
Date: Sun Jul 16 2023 21:42:42 GMT+0300 (Восточная Европа, летнее время)
Uptime: 57.3 s

Platform information
Product: Construct 3 r350 (stable)
Browser: Chrome 114.0.5735.199
Browser engine: Chromium
Context: webapp
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
