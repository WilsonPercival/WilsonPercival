## Problem description

I have a puzzle game in which there is a `2000` puzzle. I made it so that each puzzle is in its own sprite animation frame. When I export the game and launch it, there are a lot of errors in the console. I don't think the problem is memory usage because the sprite isn't even loaded into memory.

This works great in preview. The error occurs only after export.

Please note that the `Max spritesheet size` parameter is set to `Disabled (not recommended)`.

## Attach a .c3p

https://www.dropbox.com/scl/fi/spt2atctmotn1ith9p59m/max_spritesheet_size_disabled_bug_r370b.c3p?rlkey=5eg3f9dkyha5m2rtvpi42phru&dl=1

export: [max_spritesheet_size_disabled_bug_r370b expoert.zip](https://github.com/WilsonPercival/WilsonPercival/files/13615173/max_spritesheet_size_disabled_bug_r370b.expoert.zip)

## Steps to reproduce

1. Open a project.
2. Export it to `Web (HTML5)` or use the ready-made file `max_spritesheet_size_disabled_bug_r370b expoert.zip`.
3. Download the game on `netlify` or go to the already downloaded game using the link: https://65731303c999e50c1a826a3a--magical-khapse-7d8beb.netlify.app/
4. You can press `1` to create sprites, but this is not necessary.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/f6c24e53-7940-46c0-a024-60f190b38eb1

## Expected result

There shouldn't be any mistakes.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r370b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r370 (beta)
Browser: Chrome 119.0.6045.200
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/119.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 283 gb
Storage usage (approx): 182 mb (0.1%)
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
