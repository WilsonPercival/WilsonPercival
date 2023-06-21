## Problem description

I'm on about this: https://github.com/Scirra/Construct-bugs/issues/7112

Forced to disagree with you.

You said that this is not a bug, but the result of `Resolution mode` `Automatic`. But if I set it to `Fixed` the problem still remains.

Why do I think that in fact the whole picture is shifted one pixel to the left up: I counted the number of black pixels horizontally in the left column and in the right one. Note that the right column has 15 black pixels, while the left column has 16 pixels:

![observed1](https://github.com/WilsonPercival/WilsonPercival/assets/91274932/0a1a4722-b597-4905-89bb-405a0488f667)

The bug will also remain if we set `Fixed`. Note that the right column has 11 black pixels, while the left column has 12 pixels:

![observed2](https://github.com/WilsonPercival/WilsonPercival/assets/91274932/a559f16b-b670-48e2-ad1b-948e2c5e4a6a)

## Attach a .c3p

![c3p](https://github.com/WilsonPercival/WilsonPercival/assets/91274932/05174370-a055-4b03-822f-f427857eabf2)

## Steps to reproduce

1. Open and run `QR code maker`.
2. Click `Download`.

## Observed result

The columns have a different number of pixels due to the fact that the picture is shifted to the right up. This also confirms the fact why there is an empty line on the right and bottom.

## Expected result

Each column must have the same number of pixels in width and height.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r346b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r346 (beta)
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
Storage usage (approx): 428 mb (0.7%)
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
