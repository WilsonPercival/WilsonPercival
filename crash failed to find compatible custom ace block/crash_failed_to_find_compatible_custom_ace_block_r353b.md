## Problem description

Construct crashes.

## Attach a .c3p

[crash_failed_to_find_compatible_custom_ace_block_r353b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12337972/crash_failed_to_find_compatible_custom_ace_block_r353b.zip)

## Steps to reproduce

1. Open a project.
2. Go to the event sheet editor.
3. Click on `DeeDee action Fun` and select `Replace object`. A window will open, click `OK`.
4. Click on `DeeDee Fun` and select `Replace object`. A window will open, click `OK`.
5. Click `Undo`.
6. In `Cockroaches` click on `DeeDee` and select `Remove from family`.
7. Click on `DeeDee Fun` and select `Replace object`. A window will open, click `OK`.
8. Click `Undo`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/cea99296-54ec-4e39-8fac-8aad0f934d38

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r353b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: failed to find compatible custom ACE block @ Error: failed to find compatible custom ACE block at d.A9 (https://editor.construct.net/r353/projectResources.js:1531:368) at window.BYb.TKb (https://editor.construct.net/r353/projectResources.js:1586:71) at window.BYb.Hja (https://editor.construct.net/r353/projectResources.js:1584:57) at d.accept (https://editor.construct.net/r353/projectResources.js:1426:445) at d.accept (https://editor.construct.net/r353/projectResources.js:1504:437) at S0a.ryc.mf (https://editor.construct.net/r353/projectResources.js:1979:267) at window.zc.Ih (https://editor.construct.net/r353/projectResources.js:1913:319) at d.Ih (https://editor.construct.net/r353/projectResources.js:1786:440) at https://editor.construct.net/r353/main.js:2940:9 at window.Rjb.Ih (https://editor.construct.net/r353/main.js:2940:60)
Stack: Error: failed to find compatible custom ACE block at d.A9 (https://editor.construct.net/r353/projectResources.js:1531:368) at window.BYb.TKb (https://editor.construct.net/r353/projectResources.js:1586:71) at window.BYb.Hja (https://editor.construct.net/r353/projectResources.js:1584:57) at d.accept (https://editor.construct.net/r353/projectResources.js:1426:445) at d.accept (https://editor.construct.net/r353/projectResources.js:1504:437) at S0a.ryc.mf (https://editor.construct.net/r353/projectResources.js:1979:267) at window.zc.Ih (https://editor.construct.net/r353/projectResources.js:1913:319) at d.Ih (https://editor.construct.net/r353/projectResources.js:1786:440) at https://editor.construct.net/r353/main.js:2940:9 at window.Rjb.Ih (https://editor.construct.net/r353/main.js:2940:60)
Construct version: r353
URL: https://editor.construct.net/r353/
Date: Mon Aug 14 2023 19:57:49 GMT+0300 (Восточная Европа, летнее время)
Uptime: 128.1 s

Platform information
Product: Construct 3 r353 (beta)
Browser: Chrome 115.0.5790.171
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
