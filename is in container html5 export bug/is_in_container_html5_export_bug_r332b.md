## Problem description

I don't know why you closed this report: https://github.com/Scirra/Construct-3-bugs/issues/5894

I see that many in the comments have the same problem. I decided to try this as well. I uploaded to netlify and to the local server. Uploaded to the local server on the first try, so caching should be excluded. Both options give an error.

## Attach a .c3p

[AnD4DGlitch.zip](https://github.com/WilsonPercival/WilsonPercival/files/10885677/AnD4DGlitch.zip)

[BUILDER.zip](https://github.com/WilsonPercival/WilsonPercival/files/10885679/BUILDER.zip)

## Steps to reproduce

1. Open the `AnD4DGlitch.zip` project.
2. Export it to Web (HTML5) or download `BUILDER.zip`.
3. Upload the export folder to `https://app.netlify.com/drop` or go to `https://willowy-palmier-978ac7.netlify.app`.
4. Open the game. Open the console. There will be an error and the game will not load.

## Observed result

Netlify:

https://user-images.githubusercontent.com/91274932/222815124-a2060341-b3e3-49b2-8041-e30fb6515cdf.mp4

Local server:

https://user-images.githubusercontent.com/91274932/222815199-b5f028e9-52cf-4aba-80a5-198375846c32.mp4

## Expected result

The game loads well and there are no errors in the console.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r332b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r332 (beta)
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
Storage usage (approx): 253 mb (0.4%)
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
