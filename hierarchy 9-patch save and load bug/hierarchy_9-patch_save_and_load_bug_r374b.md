## Problem description

When I load the game, it doesn't restore the saved state correctly.

Please note that if you want to recreate the project from scratch, you will need to create a folder and then drag `Sprite2` and then `Sprite` into it.

## Attach a .c3p

[hierarchy_9_patch_save_and_loag_bug_r304b.zip](https://github.com/WilsonPercival/WilsonPercival/files/13884919/hierarchy_9_patch_save_and_loag_bug_r304b.zip)

## Steps to reproduce

1. Open and run the project.
2. Press `1` to create objects.
3. Press `2` to save the game.
4. Reload the page.
5. Press `3` to load the game.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/4aa92057-75bb-4815-bda3-f92a1d2f428f

## Expected result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/8b4aae88-35a3-4bd5-8c3e-63dc0340de55

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** This worked well in `r304b`. In `r305b` and `r306b` there was an error in the console when loading. It was fixed in `r307b`, but there was a problem that I'm reporting now. Still doesn't work in `r374b`.

<img width="275" alt="bug fixes" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/4e8ee078-89c8-4bed-8b10-fffe96c9836b">

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r374 (beta)
Browser: Chrome 120.0.6099.200
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 283 gb
Storage usage (approx): 331 mb (0.1%)
Persistant storage: Yes

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
Renderer: ANGLE (AMD, AMD Radeon(TM) Graphics (0x00001638) Direct3D11 vs_5_0 ps_5_0, D3D11)
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
WEBGL_clip_cull_distance
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
H.265 (video/mp4; codecs=hev1.1.2.L93.B0)
H.264 (video/mp4; codecs=avc1.42E01E)
Supported encode formats:

WebM AV1 (video/webm; codecs=av1)
WebM VP9 (video/webm; codecs=vp9)
WebM VP8 (video/webm; codecs=vp8)

</details>
