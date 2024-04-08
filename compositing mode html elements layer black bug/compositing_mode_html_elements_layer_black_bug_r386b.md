## Problem description

When I launch the game, the layer with the `HTML elements layer` property appears black. The project also sets the `Compositing mode` parameter to `Low latency (desynchronized)`.

I specifically set the `User worker` parameter to `No` to work around the bug https://github.com/Scirra/Construct-bugs/issues/7315.

Everything works well if you enable `WebGPU`.

## Attach a .c3p

[compositing_mode_html_elements_layer_black_bug_r369b.zip](https://github.com/WilsonPercival/WilsonPercival/files/14911564/compositing_mode_html_elements_layer_black_bug_r369b.zip)

## Steps to reproduce

1. Open and run the project.

## Observed result

<img width="611" alt="observed" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/18101977-0cc4-48d5-a406-b23add8fd30f">

## Expected result

<img width="584" alt="expected" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/97e22a5b-c5a7-4de5-b0ea-c9c97b47843b">

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** Broke in `r369b` because it was the first version to add `HTML elements layer`.

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r386 (beta)
Browser: Chrome 123.0.6312.86
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/123.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 283 gb
Storage usage (approx): 248 mb (0.1%)
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
