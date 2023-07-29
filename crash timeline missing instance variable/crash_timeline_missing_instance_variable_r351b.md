## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_missing_instance_variable_r351b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12204588/crash_timeline_missing_instance_variable_r351b.zip)

## Steps to reproduce

1. Open a project.
2. Click `Editing mode`.
3. Click `Set keyframes`.
4. Select all key points except the first ones.
5. Click `Copy a selection of keyframes`.
6. On the timeline, delete the private variable.
7. In the timeline, click on the sprite and select `Swap instance`. A window will open, select `Sprite2` and click `OK`.
8. Click `Paste a selection of keyframes at the current time marker`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/9d8c7b62-40fa-4110-abed-218b35377852

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r351b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: missing instance variable
Stack: Error at oa.T_a (https://editor.construct.net/r351/main.js:1119:314) at window.assert (https://editor.construct.net/r351/main.js:1034:353) at UJ.cw (https://editor.construct.net/r351/projectResources.js:1239:471) at UJ.EC (https://editor.construct.net/r351/projectResources.js:1238:275) at STa.df (https://editor.construct.net/r351/projectResources.js:1286:304) at d.E7a (https://editor.construct.net/r351/projectResources.js:1207:77) at d.Eg (https://editor.construct.net/r351/projectResources.js:1205:289) at https://editor.construct.net/r351/components/bars/timelineBar/timelineBar.js:31:402 at Array.map () at Stb (https://editor.construct.net/r351/components/bars/timelineBar/timelineBar.js:31:384)
Construct version: r351
URL: https://editor.construct.net/r351/
Date: Sat Jul 29 2023 02:06:06 GMT+0300 (Восточная Европа, летнее время)
Uptime: 33.7 s

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
