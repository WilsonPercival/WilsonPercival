## Problem description

Construct crashes.

## Attach a .c3p

<img width="308" alt="attach" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/6347a1cf-e502-4fa1-b15f-5b882c5d384b">

## Steps to reproduce

1. Open `Make animations with Construct`.
2. Click on `Timeline 1` in the right ear.
3. Change the value of the `Animation mode` parameter to `Step` in the left ear.
4. Click `Play (Space)`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/760f475c-afac-49f3-a4a4-fdfff6149a7a

## Expected result

Construct doesn't crash.

## More details

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/d9f88aa0-afee-4c76-a9c2-7c57d101d605

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r360b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r360/main.js, line 1163, col 119
Message: Uncaught RangeError: Maximum call stack size exceeded
Stack: RangeError: Maximum call stack size exceeded at d.V6 (https://editor.construct.net/r360/main.js:1163:119) at window.vva.km (https://editor.construct.net/r360/projectResources.js:1333:431) at https://editor.construct.net/r360/main.js:1176:376 at zK.km (https://editor.construct.net/r360/projectResources.js:1286:330) at d.Sxa (https://editor.construct.net/r360/projectResources.js:1200:453) at d.i2b (https://editor.construct.net/r360/components/editors/layoutView/layoutView.js:170:240) at d.i2b (https://editor.construct.net/r360/components/editors/layoutView/layoutView.js:170:305) at d.i2b (https://editor.construct.net/r360/components/editors/layoutView/layoutView.js:170:305) at d.i2b (https://editor.construct.net/r360/components/editors/layoutView/layoutView.js:170:305) at d.i2b (https://editor.construct.net/r360/components/editors/layoutView/layoutView.js:170:305)
Construct version: r360
URL: https://editor.construct.net/r360/
Date: Fri Sep 29 2023 19:57:50 GMT+0300 (Восточная Европа, летнее время)
Uptime: 41.6 s

Platform information
Product: Construct 3 r360 (beta)
Browser: Chrome 117.0.5938.92
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/117.0.0.0 Safari/537.36
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
