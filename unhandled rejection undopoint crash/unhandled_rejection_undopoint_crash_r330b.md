## Problem description

Construct crashes.

## Attach a .c3p

Construct didn't let me save the project after a crash.

## Steps to reproduce

1. Create a new project.
2. Create a JS file in the `Files` folder.
3. Write in this file 7.
4. Create a new script.
5. Press Ctrl + Z. Please note that if you click with the mouse, the bug will not work.
6. Create a new script.
7. Press Ctrl + Z.

## Observed result

https://user-images.githubusercontent.com/91274932/218866318-f33eaf7b-8cfd-4736-8d04-edf7fe3ec761.mp4

## Expected result

Construct does not crash.

## More details

Error report information
Type: unhandled rejection
Reason: Error: Undopoint not present in buffer @ Error: Undopoint not present in buffer at window.sc.xf (https://editor.construct.net/r330/projectResources.js:1858:263) at vEa (https://editor.construct.net/r330/projectResources.js:131:207) at window.sc.KL (https://editor.construct.net/r330/projectResources.js:1857:214) at d.KL (https://editor.construct.net/r330/projectResources.js:1736:215) at Tlb (https://editor.construct.net/r330/components/misc/mainMenu/mainMenu.js:16:160) at Array. (https://editor.construct.net/r330/components/misc/mainMenu/mainMenu.js:22:391) at rca (https://editor.construct.net/r330/main.js:211:254) at CCG.sca (https://editor.construct.net/r330/main.js:209:281) at $oa (https://editor.construct.net/r330/main.js:909:178) at window.ueb.Ch (https://editor.construct.net/r330/main.js:2509:333)
Stack: Error: Undopoint not present in buffer at window.sc.xf (https://editor.construct.net/r330/projectResources.js:1858:263) at vEa (https://editor.construct.net/r330/projectResources.js:131:207) at window.sc.KL (https://editor.construct.net/r330/projectResources.js:1857:214) at d.KL (https://editor.construct.net/r330/projectResources.js:1736:215) at Tlb (https://editor.construct.net/r330/components/misc/mainMenu/mainMenu.js:16:160) at Array. (https://editor.construct.net/r330/components/misc/mainMenu/mainMenu.js:22:391) at rca (https://editor.construct.net/r330/main.js:211:254) at CCG.sca (https://editor.construct.net/r330/main.js:209:281) at $oa (https://editor.construct.net/r330/main.js:909:178) at window.ueb.Ch (https://editor.construct.net/r330/main.js:2509:333)
Construct version: r330
URL: https://editor.construct.net/r330/
Date: Tue Feb 14 2023 23:12:33 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 16.2 s

Platform information
Product: Construct 3 r330 (beta)
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

![galaga](https://user-images.githubusercontent.com/91274932/218877933-b1995941-e009-4898-8e6a-574a887675e7.png)

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r330b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r330 (beta)
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

Local storage
Storage quota (approx): 59 gb
Storage usage (approx): 193 mb (0.3%)
Persistant storage: No

Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.

UI effects are disabled in settings.
WebGL indicates a major performance caveat. It is probably using software rendering.
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
Extensions:

EXT_color_buffer_float
EXT_color_buffer_half_float
EXT_float_blend
EXT_texture_compression_bptc
EXT_texture_compression_rgtc
EXT_texture_filter_anisotropic
OES_draw_buffers_indexed
OES_texture_float_linear
WEBGL_compressed_texture_astc
WEBGL_compressed_texture_etc
WEBGL_compressed_texture_etc1
WEBGL_compressed_texture_s3tc
WEBGL_compressed_texture_s3tc_srgb
WEBGL_debug_renderer_info
WEBGL_lose_context
WEBGL_multi_draw
OVR_multiview2
Audio information
System sample rate: 48000 Hz
Output channels: 2
Output interpretation: speakers
Supported decode formats:

WebM Opus (audio/webm; codecs=opus)
Ogg Opus (audio/ogg; codecs=opus)
WebM Vorbis (audio/webm; codecs=vorbis)
Ogg Vorbis (audio/ogg; codecs=vorbis)
MPEG-4 AAC (audio/mp4; codecs=mp4a.40.5)
MP3 (audio/mpeg)
FLAC (audio/flac)
PCM WAV (audio/wav; codecs=1)
Supported encode formats:

WebM Opus (audio/webm; codecs=opus)
Video information
Supported decode formats:

WebM AV1 (video/webm; codecs=av01.0.00M.08)
MP4 AV1 (video/mp4; codecs=av01.0.00M.08)
WebM VP9 (video/webm; codecs=vp9)
WebM VP8 (video/webm; codecs=vp8)
Ogg Theora (video/ogg; codecs=theora)
H.264 (video/mp4; codecs=avc1.42E01E)
Supported encode formats:

WebM VP9 (video/webm; codecs=vp9)
WebM VP8 (video/webm; codecs=vp8)

</details>
