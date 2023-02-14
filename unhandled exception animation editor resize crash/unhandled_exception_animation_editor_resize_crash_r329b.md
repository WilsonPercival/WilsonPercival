## Problem description

Construct crashes.

## Attach a .c3p

save open project: [save_open_project.zip](https://github.com/WilsonPercival/WilsonPercival/files/10734425/save_open_project.zip)

## Steps to reproduce



## Observed result

https://user-images.githubusercontent.com/91274932/218792376-958018ec-bd86-49d9-b04a-2bb201724f9c.mp4

## Expected result

Construct does not crash.

## More details

Error report information
Type: unhandled exception
File: https://editor.construct.net/r329/projectResources.js, line 174, col 129
Message: Uncaught RangeError: Failed to execute 'getImageData' on 'CanvasRenderingContext2D': Out of memory at ImageData creation
Stack: RangeError: Failed to execute 'getImageData' on 'CanvasRenderingContext2D': Out of memory at ImageData creation at Vy (https://editor.construct.net/r329/projectResources.js:174:129) at uz.eaa.pl (https://editor.construct.net/r329/projectResources.js:2202:3) at uz.eaa.Umb (https://editor.construct.net/r329/projectResources.js:2188:354) at gz (https://editor.construct.net/r329/projectResources.js:180:183) at uz.eaa.BV (https://editor.construct.net/r329/projectResources.js:2199:496) at VFa (https://editor.construct.net/r329/projectResources.js:176:117) at uz.eaa.Yo (https://editor.construct.net/r329/projectResources.js:2187:452) at hO.$l (https://editor.construct.net/r329/projectResources.js:2144:289) at lO.NWb (https://editor.construct.net/r329/projectResources.js:2155:388) at Array. (https://editor.construct.net/r329/projectResources.js:2155:59)
Construct version: r329
URL: https://editor.construct.net/r329/
Date: Tue Feb 14 2023 17:57:11 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 143.5 s

Platform information
Product: Construct 3 r329 (beta)
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

**First affected release:** broke in r329b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r329 (beta)
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
Storage usage (approx): 167 mb (0.3%)
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
