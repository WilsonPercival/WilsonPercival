## Problem description

When I try to download an export archive, Windows defender prevents me from doing so.

## Attach a .c3p

No.

## Steps to reproduce

1. Create a new project.
2. Export to `Web (HTML5)`. A window will appear, download the export archive. Please note that the file was successfully downloaded.
3. In the left ear, change the value of the `Enable WebGPU` parameter to `No`.
4. 2. Export to `Web (HTML5)`. A window will appear, download the export archive. Please note that the file was not downloaded because it was flagged as dangerous.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/791878da-71db-4e4f-b02e-7316a5d44134

## Expected result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/7403e062-fc36-4523-b1af-b6717bbd23ee

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** Worked in `r381b`, broke in `r382b`.

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r382 (beta)
Browser: Chrome 122.0.6261.95
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/122.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 283 gb
Storage usage (approx): 96 mb (0%)
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

EXT_clip_control
EXT_color_buffer_float
EXT_color_buffer_half_float
EXT_conservative_depth
EXT_depth_clamp
EXT_disjoint_timer_query_webgl2
EXT_float_blend
EXT_polygon_offset_clamp
EXT_texture_compression_bptc
EXT_texture_compression_rgtc
EXT_texture_filter_anisotropic
EXT_texture_norm16
KHR_parallel_shader_compile
NV_shader_noperspective_interpolation
OES_draw_buffers_indexed
OES_texture_float_linear
OVR_multiview2
WEBGL_blend_func_extended
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
