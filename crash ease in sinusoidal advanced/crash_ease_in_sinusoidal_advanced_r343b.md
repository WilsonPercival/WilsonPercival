## Problem description

Construct crashes.

## Attach a .c3p

save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/11547377/save_open_project.zip)

## Steps to reproduce

1. Create a new project.
2. In the right ear, click on `Timeline 1`.
3. In the left ear, select `Ease` `In Sinusoidal`.
4. Click `Edit`.
5. Click `Invert`.
6. Click `Undo`.
7. Close `Ease editor`.
8. Select `Ease` `In Sinusoidal 1`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/d433e10a-e45a-49ec-9324-baf5a05a5183

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r343b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: unsupported ease mode
Stack: Error at pa.t_a (https://editor.construct.net/r343/main.js:1130:314) at window.assert (https://editor.construct.net/r343/main.js:1045:353) at d.mCc (https://editor.construct.net/r343/projectResources.js:1044:352) at d.Ar (https://editor.construct.net/r343/projectResources.js:974:40) at d.Ar (https://editor.construct.net/r343/projectResources.js:1005:137) at Aq.g.K.bjb.oo (https://editor.construct.net/r343/components/bars/propertiesBar/propertiesBar.js:63:413) at Aq.g.K.bjb.VU (https://editor.construct.net/r343/main.js:1557:450) at Aq.g.K.bjb.MG (https://editor.construct.net/r343/main.js:1558:71) at HTMLSelectElement.nt (https://editor.construct.net/r343/main.js:1556:343)
Construct version: r343
URL: https://editor.construct.net/r343/
Date: Tue May 23 2023 21:19:32 GMT+0300 (Восточная Европа, летнее время)
Uptime: 43.9 s

Platform information
Product: Construct 3 r343 (beta)
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
