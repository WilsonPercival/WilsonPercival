## Problem description

Construct crashes.

## Attach a .c3p

https://www.dropbox.com/scl/fi/n9sucbehbsn6af372gglw/crash_copy_files_invalid_string_length_r212b.zip?rlkey=vrc76y669rcrnmqxd0s4cx0d3&dl=1

## Steps to reproduce

1. Open a project.
2. Select the files in the `Files` folder and click `Copy`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/2b7d55ca-2c37-488e-8399-093a3d511eff

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** It broke in `r212b` because it was the first version that added the ability to copy files.

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: Invalid string length @ RangeError: Invalid string length at JSON.stringify () at https://editor.construct.net/r383/components/bars/projectBar/projectBar.js:69:315
Stack: RangeError: Invalid string length at JSON.stringify () at https://editor.construct.net/r383/components/bars/projectBar/projectBar.js:69:315
Construct version: r383
URL: https://editor.construct.net/r383/
Date: Tue Mar 12 2024 17:20:58 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 16.5 s

Platform information
Product: Construct 3 r383 (beta)
Browser: Chrome 122.0.6261.112
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
