## Problem description

Construct crashes. I caught two different errors at the same steps.

## Attach a .c3p

[crash_ease_editor_popup_r333b.zip](https://github.com/WilsonPercival/WilsonPercival/files/10919369/crash_ease_editor_popup_r333b.zip)

## Steps to reproduce

1. Open a project.
2. Open `Ease editor`.
3. Press `Ctrl + P`.
4. Close the popup.
5. Notice that a window has popped up in the Construct editor. Pretend you don't notice it and keep pressing `Ctrl + P` and closing the popup until the editor gets angry and crashes.

## Observed result

https://user-images.githubusercontent.com/91274932/223681347-d20268fd-15fe-4d94-a881-e6d7df3f323b.mp4

https://user-images.githubusercontent.com/91274932/223681370-7609fa77-f7fb-4f39-816e-9ea939a424f1.mp4

## Expected result

Construct does not crash.

## More details

<details><summary>already awaiting popup window</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r333/main.js, line 1440, col 417
Message: Uncaught Error: already awaiting popup window
Stack: Error: already awaiting popup window at Mf.g.kb.Bsa.n0 (https://editor.construct.net/r333/main.js:1440:423) at d.QRb (https://editor.construct.net/r333/components/editors/eventSheetView/eventSheetView.js:161:180) at Array. (https://editor.construct.net/r333/components/editors/eventSheetView/eventSheetView.js:158:161) at window.Xeb.dispatchEvent (https://editor.construct.net/r333/main.js:1233:399) at jo (https://editor.construct.net/r333/main.js:913:214) at dr.g.$h.hx (https://editor.construct.net/r333/main.js:2522:397) at Wi.g.moc.Td (https://editor.construct.net/r333/main.js:1893:334) at https://editor.construct.net/r333/main.js:1892:139
Construct version: r333
URL: https://editor.construct.net/r333/
Date: Wed Mar 08 2023 11:43:29 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 117.6 s

Platform information
Product: Construct 3 r333 (beta)
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

<details><summary>Cannot read properties of null</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r333/main.js, line 267, col 213
Message: Uncaught TypeError: Cannot read properties of null (reading 'postMessage')
Stack: TypeError: Cannot read properties of null (reading 'postMessage') at wea (https://editor.construct.net/r333/main.js:267:213) at De.g.Dqc.Ixa (https://editor.construct.net/r333/main.js:1342:347) at https://editor.construct.net/r333/main.js:1340:498
Construct version: r333
URL: https://editor.construct.net/r333/
Date: Wed Mar 08 2023 11:45:01 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 38.1 s

Platform information
Product: Construct 3 r333 (beta)
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

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r333b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r333 (beta)
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
Storage usage (approx): 144 mb (0.2%)
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
