## Problem description

I have a sprite with physics behavior. When I create and delete it many times, I see that the game loses FPS.

## Attach a .c3p

[memory_leak_create_and_destroy_physics_bug_r374b.zip](https://github.com/WilsonPercival/WilsonPercival/files/13882402/memory_leak_create_and_destroy_physics_bug_r374b.zip)

## Steps to reproduce

1. Open and run the project.
2. Watch the FPS drop (it will start after half a minute of waiting).

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/dc1035f1-d616-4dd8-91f1-6dec3223fb87

## Expected result

The game should work well.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** `r82b`, since this is the first version in which a memory leak bug was fixed when creating and deleting a large number of sprites with physics behavior. Still doesn't work in `r374b`.

<img width="274" alt="bug fixes" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/14f68f9d-9846-48cd-8c37-a2b266147684">

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
