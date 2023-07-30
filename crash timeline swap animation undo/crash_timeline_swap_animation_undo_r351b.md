## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_swap_animation_undo_r351b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12209415/crash_timeline_swap_animation_undo_r351b.zip)

## Steps to reproduce

1. Open a project.
2. Open the `Sprite2` animation editor.
3. Rename the animation to `lol`.
4. Close the animation editor.
5. In the timeline, click on the sprite and select `Swap instance`. A window will open, select `Sprite2` and click `OK`.
6. Click `Undo` twice.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/1cb9fdf9-6199-4304-ac67-e015e0145980

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r351b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of null (reading 'pg') @ TypeError: Cannot read properties of null (reading 'pg') at Array.LGb (https://editor.construct.net/r351/components/bars/timelineBar/timelineBar.js:288:185) at d.dispatchEvent (https://editor.construct.net/r351/main.js:1257:42) at d.YFc (https://editor.construct.net/r351/projectResources.js:812:478) at d.kc (https://editor.construct.net/r351/projectResources.js:809:353) at uHb (https://editor.construct.net/r351/plugins/allEditorPlugins.js:24:144) at Array.lfb (https://editor.construct.net/r351/plugins/allEditorPlugins.js:262:419) at window.Ijb.dispatchEvent (https://editor.construct.net/r351/main.js:1257:42) at window.Ijb.Kr (https://editor.construct.net/r351/main.js:2944:87) at d.ib (https://editor.construct.net/r351/projectResources.js:761:292) at OZa.Xq.mf (https://editor.construct.net/r351/projectResources.js:1913:276)
Stack: TypeError: Cannot read properties of null (reading 'pg') at Array.LGb (https://editor.construct.net/r351/components/bars/timelineBar/timelineBar.js:288:185) at d.dispatchEvent (https://editor.construct.net/r351/main.js:1257:42) at d.YFc (https://editor.construct.net/r351/projectResources.js:812:478) at d.kc (https://editor.construct.net/r351/projectResources.js:809:353) at uHb (https://editor.construct.net/r351/plugins/allEditorPlugins.js:24:144) at Array.lfb (https://editor.construct.net/r351/plugins/allEditorPlugins.js:262:419) at window.Ijb.dispatchEvent (https://editor.construct.net/r351/main.js:1257:42) at window.Ijb.Kr (https://editor.construct.net/r351/main.js:2944:87) at d.ib (https://editor.construct.net/r351/projectResources.js:761:292) at OZa.Xq.mf (https://editor.construct.net/r351/projectResources.js:1913:276)
Construct version: r351
URL: https://editor.construct.net/r351/
Date: Sun Jul 30 2023 17:08:10 GMT+0300 (Восточная Европа, летнее время)
Uptime: 79 s

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
