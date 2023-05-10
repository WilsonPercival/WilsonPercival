## Problem description

Construct crashes.

## Attach a .c3p

[crash_primary_selected_instance_must_be_in_selection_r341b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11446355/crash_primary_selected_instance_must_be_in_selection_r341b.zip)

## Steps to reproduce

1. Open a project.
2. Make `Layer 1` global.
3. Go to `Layout 1`.
4. Drag the sprite onto the layout.
5. Click on an instance.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/477e2e7f-ee1c-4017-985d-4be3ef1e56ae

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r341b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: primary selected instance must be in selection
Stack: Error at pa.t_a (https://editor.construct.net/r341/main.js:1130:314) at window.assert (https://editor.construct.net/r341/main.js:1045:353) at FR (https://editor.construct.net/r341/components/editors/layoutView/layoutView.js:65:254) at Vdb.fR (https://editor.construct.net/r341/components/editors/layoutView/layoutView.js:256:300) at Vdb.PD (https://editor.construct.net/r341/components/editors/layoutView/layoutView.js:247:228) at window.fm.dispatchEvent (https://editor.construct.net/r341/main.js:1261:42) at Gac (https://editor.construct.net/r341/components/editors/layoutView/layoutView.js:93:385)
Construct version: r341
URL: https://editor.construct.net/r341/
Date: Thu May 11 2023 00:02:31 GMT+0300 (Восточная Европа, летнее время)
Uptime: 34.7 s

Platform information
Product: Construct 3 r341 (beta)
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
