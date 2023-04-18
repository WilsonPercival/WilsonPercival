## Problem description

Construct crashes.

## Attach a .c3p

[crash_lossy_9_patch_r338b.zip](https://github.com/WilsonPercival/WilsonPercival/files/11265784/crash_lossy_9_patch_r338b.zip)

## Steps to reproduce

1. Open a project.
2. Open the sprite image editor.
3. Click `Set export image format` and select `Lossy`.
4. Click `OK`.

## Observed result

https://user-images.githubusercontent.com/91274932/232888016-a936f3a1-2040-4193-8bc5-e019cc0d6087.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r338b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: unexpected type @ TypeError: unexpected type at O.i (https://editor.construct.net/r338/main.js:1035:147) at x0a.QRb.eI (https://editor.construct.net/r338/projectResources.js:2014:381) at e (https://editor.construct.net/r338/projectResources.js:434:67) at Array. (https://editor.construct.net/r338/projectResources.js:434:123) at window.ufb.dispatchEvent (https://editor.construct.net/r338/main.js:1235:42) at window.ufb.iN (https://editor.construct.net/r338/main.js:2521:32) at d.X0a (https://editor.construct.net/r338/projectResources.js:770:448) at d.HXb (https://editor.construct.net/r338/projectResources.js:780:414) at d.bMa (https://editor.construct.net/r338/projectResources.js:782:158) at d.pwa (https://editor.construct.net/r338/projectResources.js:772:53)
Stack: TypeError: unexpected type at O.i (https://editor.construct.net/r338/main.js:1035:147) at x0a.QRb.eI (https://editor.construct.net/r338/projectResources.js:2014:381) at e (https://editor.construct.net/r338/projectResources.js:434:67) at Array. (https://editor.construct.net/r338/projectResources.js:434:123) at window.ufb.dispatchEvent (https://editor.construct.net/r338/main.js:1235:42) at window.ufb.iN (https://editor.construct.net/r338/main.js:2521:32) at d.X0a (https://editor.construct.net/r338/projectResources.js:770:448) at d.HXb (https://editor.construct.net/r338/projectResources.js:780:414) at d.bMa (https://editor.construct.net/r338/projectResources.js:782:158) at d.pwa (https://editor.construct.net/r338/projectResources.js:772:53)
Construct version: r338
URL: https://editor.construct.net/r338/
Date: Tue Apr 18 2023 22:16:44 GMT+0300 (Восточная Европа, летнее время)
Uptime: 83.8 s

Platform information
Product: Construct 3 r338 (beta)
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
