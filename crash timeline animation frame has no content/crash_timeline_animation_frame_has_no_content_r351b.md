## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_animation_frame_has_no_content_r351b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12207408/crash_timeline_animation_frame_has_no_content_r351b.zip)

## Steps to reproduce

1. Open a project.
2. Click `Editing mode`.
3. Click `Set keyframes`.
4. Open the sprite animation editor.
5. Delete the zero frame.
6. Close the animation editor.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/1580f64e-ee3e-4455-89bf-c966a3512afe

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r351b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r351/projectResources.js, line 786, col 437
Message: Uncaught Error: animation frame has no content
Stack: Error: animation frame has no content at d.lJ (https://editor.construct.net/r351/projectResources.js:786:443) at d.Yla (https://editor.construct.net/r351/projectResources.js:792:187) at nOb.Instance.rf (https://editor.construct.net/r351/main.js:2474:87) at nOb.Instance.rf (https://editor.construct.net/r351/plugins/allEditorPlugins.js:269:423) at nOb.Instance.Zf (https://editor.construct.net/r351/plugins/allEditorPlugins.js:269:154) at d.Zf (https://editor.construct.net/r351/projectResources.js:858:9) at d.Zf (https://editor.construct.net/r351/projectResources.js:1395:471) at d.Zf (https://editor.construct.net/r351/projectResources.js:1352:320) at ubc (https://editor.construct.net/r351/components/editors/layoutView/layoutView.js:91:303)
Construct version: r351
URL: https://editor.construct.net/r351/
Date: Sat Jul 29 2023 17:22:16 GMT+0300 (Восточная Европа, летнее время)
Uptime: 27.2 s

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
