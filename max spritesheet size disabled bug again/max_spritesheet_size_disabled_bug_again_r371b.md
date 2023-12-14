## Problem description

I have a puzzle with `5600` puzzle pieces. I made sure that each puzzle was in its own sprite animation frame. When I export the game and launch it, it freezes at the loading stage. If you wait a little, there will be a lot of errors in the console. Also, I can’t load the page again - it seems that the computer has remembered this and doesn’t want to access it anymore.

This works great in preview. The error occurs only after export.

Please note that the `Max spritesheet size` parameter is set to `Disabled (not recommended)`.

## Attach a .c3p

https://www.dropbox.com/scl/fi/gcw9kj6cirpknygyh7rfy/max_spritesheet_size_disabled_bug_again_r371b.c3p?rlkey=t819yzlggj7m95g5lw2k0xnvq&dl=1

export: https://www.dropbox.com/scl/fi/tgjuo5x9iudpvxtgpvnug/max_spritesheet_size_disabled_bug_again_r371b-export.zip?rlkey=jt78dxev11pv8tha2g66sc2aa&dl=1

## Steps to reproduce

1. Open a project.
2. Export it to `Web (HTML5)` or use the ready-made export `max_spritesheet_size_disabled_bug_again_r371b export.zip`.
3. Upload the game to `netlify` or follow the link:
https://657b08a647df8a1e68c1d05e--endearing-piroshki-57eaf3.netlify.app/.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/d244e4b0-151b-43e7-a724-7795094064d1

## Expected result

The game is loading.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r371b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r371 (beta)
Browser: Chrome 120.0.6099.71
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
Storage usage (approx): 223 mb (0.1%)
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
