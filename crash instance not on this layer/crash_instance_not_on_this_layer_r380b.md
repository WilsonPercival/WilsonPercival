## Problem description

Construct crashes.

## Attach a .c3p

[crash_instance_not_on_this_layer_r376b.zip](https://github.com/WilsonPercival/WilsonPercival/files/14345184/crash_instance_not_on_this_layer_r376b.zip)

## Steps to reproduce

1. Open a project.
2. Copy the sprite instance.
3. Go to `Layout 2`.
4. Insert an instance onto the layout.
5. In the left ear, change the value of the `Layer` parameter to `Layer 0`, which is located on `Layout 2`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/4b4d89ce-88d4-454e-81b9-a4d99e503c9f

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** Worked in `r376b`, broke in `r377b`. Still doesn't work in `r380b`.

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r380/projectResources.js, line 1429, col 242
Message: Uncaught Error: instance not on this layer
Stack: Error: instance not on this layer at d.iDc (https://editor.construct.net/r380/projectResources.js:1429:248) at d.kub (https://editor.construct.net/r380/projectResources.js:855:48) at https://editor.construct.net/r380/components/bars/propertiesBar/propertiesBar.js:19:24 at hh (https://editor.construct.net/r380/main.js:375:99) at Lq.g.J.fpb.ZW (https://editor.construct.net/r380/main.js:1561:418) at Lq.g.J.fpb.AI (https://editor.construct.net/r380/main.js:1562:71) at HTMLSelectElement.du (https://editor.construct.net/r380/main.js:1560:344)
Construct version: r380
URL: https://editor.construct.net/r380/
Date: Tue Feb 20 2024 15:33:27 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 118.5 s

Platform information
Product: Construct 3 r380 (beta)
Browser: Chrome 121.0.6167.185
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/121.0.0.0 Safari/537.36
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
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_depth_clamp, EXT_disjoint_timer_query_webgl2, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, EXT_texture_norm16, KHR_parallel_shader_compile, OES_draw_buffers_indexed, OES_texture_float_linear, OVR_multiview2, WEBGL_clip_cull_distance, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw, WEBGL_polygon_mode, WEBGL_provoking_vertex

</details>
