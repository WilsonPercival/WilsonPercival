## Problem description

Construct crashes.

## Attach a .c3p

https://www.dropbox.com/s/taazqzhgak3ye59/crash_timeline_audio_delete_timeline_r335b.c3p?dl=1

## Steps to reproduce

1. Open a project.
2. Click `Add -> Track -> Add audio`.
3. Right click on the audio track and select `Add file`.
4. Select a music file.
5. Remove `Timeline 1` from the project.
6. Wait for the crash.

## Observed result

https://user-images.githubusercontent.com/91274932/226565674-e65dbf02-8cdf-470a-8610-2dcbecac7afe.mp4

## Expected result

Construct does not crash.

## More details

Error report information
Type: unhandled exception
File: https://editor.construct.net/r335/components/bars/timelineBar/timelineBar.js, line 180, col 86
Message: Uncaught TypeError: Cannot read properties of null (reading 'vta')
Stack: TypeError: Cannot read properties of null (reading 'vta') at n2.JDc (https://editor.construct.net/r335/components/bars/timelineBar/timelineBar.js:180:86) at Array. (https://editor.construct.net/r335/components/bars/timelineBar/timelineBar.js:162:124) at window.afb.dispatchEvent (https://editor.construct.net/r335/main.js:1234:42) at window.afb.qk (https://editor.construct.net/r335/main.js:2515:250) at d.Oca (https://editor.construct.net/r335/projectResources.js:990:415) at n2.eDc (https://editor.construct.net/r335/components/bars/timelineBar/timelineBar.js:184:289) at Array. (https://editor.construct.net/r335/components/bars/timelineBar/timelineBar.js:168:184) at window.afb.dispatchEvent (https://editor.construct.net/r335/main.js:1234:42) at window.afb.oE (https://editor.construct.net/r335/main.js:2515:477) at AudioContext. (https://editor.construct.net/r335/projectResources.js:1237:30)
Construct version: r335
URL: https://editor.construct.net/r335/
Date: Tue Mar 21 2023 11:26:03 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 60.9 s

Platform information
Product: Construct 3 r335 (beta)
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

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r335b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r335 (beta)
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
Storage usage (approx): 203 mb (0.3%)
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
