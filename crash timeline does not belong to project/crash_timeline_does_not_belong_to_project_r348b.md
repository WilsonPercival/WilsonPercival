## Problem description

Construct crashes.

## Attach a .c3p

[crash_timeline_delete_instance_r338b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11950176/crash_timeline_delete_instance_r338b.zip)

## Steps to reproduce

1. Open a project. Note that the `Timeline Bar` must be open, otherwise the crash will not occur.
2. Duplicate `Timeline 1`.
3. Click `Undo`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/f1e0c514-40ed-47fd-ad29-2f7449c38342

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r348b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: timeline does not belong to project
Stack: Error at pa.D_a (https://editor.construct.net/r348/main.js:1129:314) at window.assert (https://editor.construct.net/r348/main.js:1044:353) at d.Fma (https://editor.construct.net/r348/projectResources.js:1803:494) at d.Fma (https://editor.construct.net/r348/components/bars/timelineBar/timelineBar.js:44:150) at d.Mc (https://editor.construct.net/r348/components/bars/timelineBar/timelineBar.js:47:9) at f2.dO (https://editor.construct.net/r348/components/bars/timelineBar/timelineBar.js:190:381) at https://editor.construct.net/r348/components/bars/timelineBar/timelineBar.js:169:269 at Array. (https://editor.construct.net/r348/components/bars/timelineBar/timelineBar.js:50:447) at wca (https://editor.construct.net/r348/main.js:212:254) at CCG.xca (https://editor.construct.net/r348/main.js:210:282)
Construct version: r348
URL: https://editor.construct.net/r348/
Date: Tue Jul 04 2023 17:06:35 GMT+0300 (Восточная Европа, летнее время)
Uptime: 87.4 s

Platform information
Product: Construct 3 r348 (beta)
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
