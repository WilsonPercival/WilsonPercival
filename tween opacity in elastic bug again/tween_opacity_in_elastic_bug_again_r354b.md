## Problem description

I'm talking about this report: https://github.com/Scirra/Construct-bugs/issues/7069

I think we did not understand each other. I modified the source a bit to show the problem differently. I changed the tween time from 0.2 to 0.4. Please note that if you run and press `1`, then the transparency of the sprite will stop at `0.47`. I expect `0`.

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/82c7c32e-19e6-4284-988f-1adab0af2946

It works well if I change the curve to `linear`:

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/95da0fa7-9f83-4dbb-9b16-b18b58db3924

Please take a close look at the code in the project. I think you think I'm doing something that goes against the normal use of the tween behavior, but I'm not.

## Attach a .c3p

[tween_opacity_in_elastic_bug_again_r354b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12363853/tween_opacity_in_elastic_bug_again_r354b.zip)

## Steps to reproduce

1. Open and run the project.
2. Press `1`.

## Observed result

The sprite's final transparency value is `0.47`.

## Expected result

The sprite's final transparency value is `0`.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r354b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r354 (beta)
Browser: Chrome 115.0.5790.171
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/115.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 283 gb
Storage usage (approx): 92 mb (0%)
Persistant storage: No

Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.

Nothing is missing. Everything is OK!
WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (AMD)
Renderer: ANGLE (AMD, AMD Radeon(TM) Graphics Direct3D11 vs_5_0 ps_5_0, D3D11)
Major performance caveat: no
Maximum texture size: 16384
Point size range: 1 to 1024
Extensions:

EXT_color_buffer_float
EXT_color_buffer_half_float
EXT_disjoint_timer_query_webgl2
EXT_float_blend
EXT_texture_compression_bptc
EXT_texture_compression_rgtc
EXT_texture_filter_anisotropic
EXT_texture_norm16
KHR_parallel_shader_compile
OES_draw_buffers_indexed
OES_texture_float_linear
OVR_multiview2
WEBGL_compressed_texture_s3tc
WEBGL_compressed_texture_s3tc_srgb
WEBGL_debug_renderer_info
WEBGL_debug_shaders
WEBGL_lose_context
WEBGL_multi_draw
WEBGL_provoking_vertex
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
H.265 (video/mp4; codecs=hev1.1.2.L93.B0)
H.264 (video/mp4; codecs=avc1.42E01E)
Supported encode formats:

WebM AV1 (video/webm; codecs=av1)
WebM VP9 (video/webm; codecs=vp9)
WebM VP8 (video/webm; codecs=vp8)

</details>
