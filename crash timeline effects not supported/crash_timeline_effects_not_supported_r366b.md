## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_effects_not_supported_r366b.zip](https://github.com/WilsonPercival/WilsonPercival/files/13330729/crash_timeline_effects_not_supported_r366b.zip)

## Steps to reproduce

1. Open a project.
2. Open `Timeline Bar`.
3. Drag the button onto the timeline.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/dba6a00c-f925-4c17-a393-ac5435e8924b

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r366b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r366/main.js, line 1126, col 65
Message: Uncaught Error: effects not supported
Stack: Error: effects not supported at d.Gy (https://editor.construct.net/r366/projectResources.js:727:212) at Gy.next () at d.oFc (https://editor.construct.net/r366/projectResources.js:1146:348) at d.sOa (https://editor.construct.net/r366/projectResources.js:1140:118) at d.rva (https://editor.construct.net/r366/projectResources.js:1135:485) at new d (https://editor.construct.net/r366/projectResources.js:1118:115) at oa.j (https://editor.construct.net/r366/main.js:1126:44) at d.hQb (https://editor.construct.net/r366/projectResources.js:1052:255) at d.iQb (https://editor.construct.net/r366/projectResources.js:1052:437) at ybb (https://editor.construct.net/r366/components/editors/layoutView/layoutView.js:23:355)
Construct version: r366
URL: https://editor.construct.net/r366/
Date: Mon Nov 13 2023 06:21:17 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 40.9 s

Platform information
Product: Construct 3 r366 (beta)
Browser: Chrome 119.0.6045.124
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/119.0.0.0 Safari/537.36
Language setting: en-US

WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (AMD)
Renderer: ANGLE (AMD, AMD Radeon(TM) Graphics (0x00001638) Direct3D11 vs_5_0 ps_5_0, D3D11)
Major performance caveat: no
Maximum texture size: 16384
Point size range: 1 to 1024
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_disjoint_timer_query_webgl2, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, EXT_texture_norm16, KHR_parallel_shader_compile, OES_draw_buffers_indexed, OES_texture_float_linear, OVR_multiview2, WEBGL_clip_cull_distance, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw, WEBGL_provoking_vertex

</details>
