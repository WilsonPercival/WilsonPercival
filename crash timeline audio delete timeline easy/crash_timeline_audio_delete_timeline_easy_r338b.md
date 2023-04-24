## Problem description

Construct crashes. I have already reported this: https://github.com/Scirra/Construct-bugs/issues/6811

You couldn't repeat it. Perhaps because your track loads quickly. So I enlarged the track to increase the time window. I think the crash is due to the fact that I deleted the timeline without waiting for the audio track to load.

## Attach a .c3p

https://www.dropbox.com/s/997h7cjn5z5o7fk/crash_timeline_audio_delete_timeline_easy_r338b.c3p?dl=1

## Steps to reproduce

1. Open a project.
2. Click `Add -> Track -> Add audio`.
3. Right click on the audio track and select `Add file`.

The next steps need to be done quickly.

4. Select a music file.
5. Remove `Timeline 1` from the project. You can press the `Delete` keys, then `Enter` to do this faster.
6. Wait for the crash. I assume you will wait about one second.

## Observed result

https://user-images.githubusercontent.com/91274932/234105043-25963abc-c49c-4320-b3d8-2cd1c58ead3c.mp4

## Expected result

Construct does not crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r338b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r338/components/bars/timelineBar/timelineBar.js, line 181, col 86
Message: Uncaught TypeError: Cannot read properties of null (reading 'Cta')
Stack: TypeError: Cannot read properties of null (reading 'Cta') at k2.oEc (https://editor.construct.net/r338/components/bars/timelineBar/timelineBar.js:181:86) at Array. (https://editor.construct.net/r338/components/bars/timelineBar/timelineBar.js:162:194) at window.ufb.dispatchEvent (https://editor.construct.net/r338/main.js:1235:42) at window.ufb.uk (https://editor.construct.net/r338/main.js:2521:250) at d.Wca (https://editor.construct.net/r338/projectResources.js:997:415) at k2.KDc (https://editor.construct.net/r338/components/bars/timelineBar/timelineBar.js:185:289) at Array. (https://editor.construct.net/r338/components/bars/timelineBar/timelineBar.js:168:331) at window.ufb.dispatchEvent (https://editor.construct.net/r338/main.js:1235:42) at window.ufb.AE (https://editor.construct.net/r338/main.js:2521:477) at AudioContext. (https://editor.construct.net/r338/projectResources.js:1244:30)
Construct version: r338
URL: https://editor.construct.net/r338/
Date: Mon Apr 24 2023 22:57:45 GMT+0300 (Восточная Европа, летнее время)
Uptime: 206.7 s

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
