## Problem description

I have a pink sprite that acts as the parent of the hierarchy. I also have other sprites that I add to the hierarchy through events, inheriting the visibility of the parent. After several steps including saving and loading, I end up with a situation where the parent is invisible and its child sprites are visible. It is not right.

## Attach a .c3p

[hierarchy_save_and_load_visible_pink_bug_r375b.zip](https://github.com/WilsonPercival/WilsonPercival/files/14185347/hierarchy_save_and_load_visible_pink_bug_r375b.zip)

## Steps to reproduce

1. Open and run the project.
2. Press `1` to call the function.
3. Press `2` to add the green sprite to the hierarchy.
4. Press `3` to save the game.
5. Press `4` to make the pink sprite invisible. Please note that all sprites have become invisible - this is correct behavior.
6. Press `5` to call the function and delete the blue sprite.
7. Press `6` to load the game.
8. Press `7` to make the pink sprite invisible. Note that the pink sprite has disappeared, but its child sprites are still visible - this is incorrect behavior.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/55bf1216-af11-458e-87a6-494502c5e99c

## Expected result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/40ec1c0e-4a29-4ded-affb-71579b6bde87

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** Worked in `r375b`, broke in `r376b`. Still doesn't work in `r378b`.

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
