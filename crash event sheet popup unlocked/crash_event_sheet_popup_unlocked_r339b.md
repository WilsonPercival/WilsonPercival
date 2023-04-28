## Problem description

Construct crashes.

## Attach a .c3p

[project.zip](https://github.com/WilsonPercival/WilsonPercival/files/11356113/project.zip)

## Steps to reproduce

1. Open a project.
2. Drag the event sheet tab to the right side of the screen to open it in a new window.
3. Click `Add event` in the left window.
4. Select the `System` object. Note that the window on the right has become unlocked.
5. Click `Add event` in the right window.
6. Click `Next` in the left window.

## Observed result

https://user-images.githubusercontent.com/91274932/235219903-3f87634e-f518-488b-aa73-c398eb467b87.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r339b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: unexpected type @ TypeError: unexpected type at Q.i (https://editor.construct.net/r339/main.js:1060:147) at gG.g.K.Bob.R (https://editor.construct.net/r339/projectResources.js:3016:170) at fQa (https://editor.construct.net/r339/projectResources.js:538:57) at bQa (https://editor.construct.net/r339/projectResources.js:536:117) at cQa (https://editor.construct.net/r339/projectResources.js:535:390) at https://editor.construct.net/r339/projectResources.js:535:453 at async d.sK (https://editor.construct.net/r339/components/editors/eventSheetView/eventSheetView.js:222:103)
Stack: TypeError: unexpected type at Q.i (https://editor.construct.net/r339/main.js:1060:147) at gG.g.K.Bob.R (https://editor.construct.net/r339/projectResources.js:3016:170) at fQa (https://editor.construct.net/r339/projectResources.js:538:57) at bQa (https://editor.construct.net/r339/projectResources.js:536:117) at cQa (https://editor.construct.net/r339/projectResources.js:535:390) at https://editor.construct.net/r339/projectResources.js:535:453 at async d.sK (https://editor.construct.net/r339/components/editors/eventSheetView/eventSheetView.js:222:103)
Construct version: r339
URL: https://editor.construct.net/r339/
Date: Fri Apr 28 2023 21:47:57 GMT+0400 (Samara Standard Time)
Uptime: 20.7 s

Platform information
Product: Construct 3 r339 (beta)
Browser: Chrome 113.0.5672.63
Browser engine: Chromium
Context: webapp
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.25
Logical CPU cores: 12
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/113.0.0.0 Safari/537.36
Language setting: en-US

WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (NVIDIA)
Renderer: ANGLE (NVIDIA, NVIDIA GeForce GTX 1650 Direct3D11 vs_5_0 ps_5_0, D3D11)
Major performance caveat: no
Maximum texture size: 16384
Point size range: 1 to 1024
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_disjoint_timer_query_webgl2, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, EXT_texture_norm16, KHR_parallel_shader_compile, OES_draw_buffers_indexed, OES_texture_float_linear, OVR_multiview2, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw, WEBGL_provoking_vertex

</details>
