## Problem description

I have `Advanced Random` in my project. Its `Seed` parameter value is `42`. The checkbox next to the `Replace system random` parameter is also enabled. When I save and load the game, I see that the random number generation iteration is not saved.

## Attach a .c3p

[advanced_random_seed_save_and_load_bug_r126b.zip](https://github.com/WilsonPercival/WilsonPercival/files/14234939/advanced_random_seed_save_and_load_bug_r126b.zip)

## Steps to reproduce

1. Open a project.
2. Launch and open the console.
3. Press `1` three times to generate 3 numbers. Please note that these numbers will be `38`, `57` and `2`.
4. Reload the page to start again.
5. Press `1` twice. Please note that there are two numbers in the console: `38` and `57`.
6. Press `S` to save the game.
7. Press `1` to generate a new random number. Notice that we got the number `2` as expected. This is correct behavior.
8. Press `L` to load the game.
9. Press `1` to generate a new random number. Notice that we got the number `88`. This is wrong behavior. I expected the number `2` to be generated since we loaded a saved state.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/ca1f92bd-baa7-43d0-9a35-0b08b7a1c31e

## Expected result

The console should contain the numbers `38`, `57`, `2` and `2`.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** Broke in `r126b` because this is the first version in which the `Replace system random` option became available. Still doesn't work in `r378b`.

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r378 (beta)
Browser: Chrome 121.0.6167.140
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/121.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 283 gb
Storage usage (approx): 2.5 gb (0.9%)
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
EXT_depth_clamp
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
WEBGL_polygon_mode
WEBGL_provoking_vertex
Audio information
System sample rate: 48000 Hz
Output channels: 2
Output interpretation: speakers
Supported decode formats:

WebM Opus (audio/webm;codecs=opus)
WebM Vorbis (audio/webm;codecs=vorbis)
MPEG-4 Opus (audio/mp4;codecs=opus)
MPEG-4 AAC (audio/mp4;codecs=mp4a.40.2)
MP3 (audio/mpeg)
FLAC (audio/flac)
PCM WAV (audio/wav;codecs=1)
Supported encode formats:

WebM Opus (audio/webm;codecs=opus)
Video information
Supported decode formats:

WebM AV1 (video/webm;codecs=av01.0.00M.08)
WebM VP9 (video/webm;codecs=vp9)
WebM VP8 (video/webm;codecs=vp8)
MPEG-4 AV1 (video/mp4;codecs=av01.0.00M.08)
MPEG-4 H.265 (video/mp4;codecs=hev1.1.2.L93.B0)
MPEG-4 H.264 (video/mp4;codecs=avc1.420034)
Supported encode formats:

WebM AV1 (video/webm;codecs=av01.0.00M.08)
WebM VP9 (video/webm;codecs=vp9)
WebM VP8 (video/webm;codecs=vp8)
WebM H.264 (video/webm;codecs=avc1.420034)

</details>
