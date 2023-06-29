## Problem description

Construct crashes.

## Attach a .c3p

https://www.dropbox.com/s/997h7cjn5z5o7fk/crash_timeline_audio_delete_timeline_easy_r338b.c3p?dl=1

## Steps to reproduce

1. Open a project.
2. Click `Add -> Track -> Add audio`.
3. Right click on the audio track and select `Add file`.

The next steps need to be done quickly.

4. Select a music file.
6. Close the project. A window will open, click `Don't save`.
7. Wait for the crash. I assume you will wait about one second.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/e643eb32-7ac3-47a8-b48e-bab0fc7b1549

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r347b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: unexpected type @ TypeError: unexpected type at Q.i (https://editor.construct.net/r347/main.js:1059:147) at d.yca (https://editor.construct.net/r347/projectResources.js:1006:462) at https://editor.construct.net/r347/components/bars/timelineBar/timelineBar.js:261:172
Stack: TypeError: unexpected type at Q.i (https://editor.construct.net/r347/main.js:1059:147) at d.yca (https://editor.construct.net/r347/projectResources.js:1006:462) at https://editor.construct.net/r347/components/bars/timelineBar/timelineBar.js:261:172
Construct version: r347
URL: https://editor.construct.net/r347/
Date: Thu Jun 29 2023 05:16:10 GMT+0300 (Восточная Европа, летнее время)
Uptime: 91.9 s

Platform information
Product: Construct 3 r347 (beta)
Browser: Chrome 109.0.5414.120
Browser engine: Chromium
Context: browser
Operating system: Windows NT 0.1.0
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/109.0.0.0 Safari/537.36
Language setting: en-US

WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (Google)
Renderer: ANGLE (Google, Vulkan 1.3.0 (SwiftShader Device (Subzero) (0x0000C0DE)), SwiftShader driver)
Major performance caveat: yes
Maximum texture size: 8192
Point size range: 1 to 1023
Extensions: EXT_color_buffer_float, EXT_color_buffer_half_float, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, OES_draw_buffers_indexed, OES_texture_float_linear, WEBGL_compressed_texture_astc, WEBGL_compressed_texture_etc, WEBGL_compressed_texture_etc1, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_lose_context, WEBGL_multi_draw, OVR_multiview2

</details>
