## Problem description

Construct crashes.

## Attach a .c3p



## Steps to reproduce

1. Create a new project.
2. Create a sprite. The Animation Editor will open automatically.
3. Click `Preview`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/fb4ff904-0776-4f40-bacd-3e4fd06d2a33

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r344s

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: CSS style for dialog min-height must specify the size in units of 'px' @ ifa@https://editor.construct.net/r344/main.js:289:279 af@https://editor.construct.net/r344/main.js:284:120 @https://editor.construct.net/r344/projectResources.js:10:486 asyncFunctionResume@[native code] Promise@[native code] lu@https://editor.construct.net/r344/projectResources.js:10:451 promiseReactionJob@[native code]
Stack: ifa@https://editor.construct.net/r344/main.js:289:279 af@https://editor.construct.net/r344/main.js:284:120 @https://editor.construct.net/r344/projectResources.js:10:486 asyncFunctionResume@[native code] Promise@[native code] lu@https://editor.construct.net/r344/projectResources.js:10:451 promiseReactionJob@[native code]
Construct version: r344
URL: https://editor.construct.net/
Date: Tue May 30 2023 21:56:01 GMT+0400 (Самара, стандартное время)
Uptime: 128.2 s
Platform information
Product: Construct 3 r344 (stable)
Browser: Safari 16.1
Browser engine: WebKit
Context: browser
Operating system: macOS 10.15.7
Device type: desktop
Device pixel ratio: 2
Logical CPU cores: 8
Approx. device memory: (unavailable)
User agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/16.1 Safari/605.1.15
Language setting: en-US
WebGL information
Version string: WebGL 2.0
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Apple Inc.
Renderer: Apple GPU
Major performance caveat: no
Maximum texture size: 16384
Point size range: 1 to 511
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, EXT_texture_norm16, KHR_parallel_shader_compile, OES_draw_buffers_indexed, OES_texture_float_linear, WEBGL_compressed_texture_astc, WEBGL_compressed_texture_etc, WEBGL_compressed_texture_etc1, WEBGL_compressed_texture_pvrtc, WEBKIT_WEBGL_compressed_texture_pvrtc, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context, WEBGL_multi_draw

</details>
