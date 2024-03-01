## Problem description

Construct crashes.

## Attach a .c3p

Save open project: [save open project.zip](https://github.com/WilsonPercival/WilsonPercival/files/14462485/save.open.project.zip)

## Steps to reproduce

1. Create a new project.
2. Create a sprite. The animation editor will open.
3. Click `Resize`. A window will open. Pay attention to the color of the title - if it is white, it means the window is active and there will be no crash.
4. Click `Escape` to close the `Resize Image Canvas` window.
5. Press `Escape` to close the animation editor.
6. Open the animation editor.
7. Repeat steps 3, 4 and 5 until the title bar on the `Resize Image Canvas` window turns gray - this means that the window is not in focus and can now be crashed.
8. Click `Escape`. Instead of closing the `Resize Image Canvas` window, the animation editor will close because it was the one that had the focus.
9. Click `OK`.

In the video I was able to do it on the second try, but it may take you an average of 20 tries. This is independent of the dark theme.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/e42e62ef-0a44-42c7-aea9-61d4c6bfafc5

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** It's hard to say because the bug reproduces randomly. But I can say that I was able to reproduce it in `r292b`.

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: Cannot read properties of undefined (reading 'length') @ TypeError: Cannot read properties of undefined (reading 'length') at xD.Me.Ya (https://editor.construct.net/r381/projectResources.js:2719:165) at ZLa (https://editor.construct.net/r381/projectResources.js:342:81) at QA.Sha.uyb (https://editor.construct.net/r381/projectResources.js:2348:66) at jA (https://editor.construct.net/r381/projectResources.js:206:185) at QA.Sha.So (https://editor.construct.net/r381/projectResources.js:2387:487) at VIa (https://editor.construct.net/r381/projectResources.js:223:324)
Stack: TypeError: Cannot read properties of undefined (reading 'length') at xD.Me.Ya (https://editor.construct.net/r381/projectResources.js:2719:165) at ZLa (https://editor.construct.net/r381/projectResources.js:342:81) at QA.Sha.uyb (https://editor.construct.net/r381/projectResources.js:2348:66) at jA (https://editor.construct.net/r381/projectResources.js:206:185) at QA.Sha.So (https://editor.construct.net/r381/projectResources.js:2387:487) at VIa (https://editor.construct.net/r381/projectResources.js:223:324)
Construct version: r381
URL: https://editor.construct.net/r381/
Date: Fri Mar 01 2024 16:24:55 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 24.3 s

Platform information
Product: Construct 3 r381 (beta)
Browser: Chrome 122.0.6261.70
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/122.0.0.0 Safari/537.36
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
Extensions: EXT_clip_control, EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_conservative_depth, EXT_depth_clamp, EXT_disjoint_timer_query_webgl2, EXT_float_blend, EXT_polygon_offset_clamp, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, EXT_texture_norm16, KHR_parallel_shader_compile, NV_shader_noperspective_interpolation, OES_draw_buffers_indexed, OES_texture_float_linear, OVR_multiview2, WEBGL_blend_func_extended, WEBGL_clip_cull_distance, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw, WEBGL_polygon_mode, WEBGL_provoking_vertex

</details>
