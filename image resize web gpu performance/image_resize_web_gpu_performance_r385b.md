## Problem description

When I run the game in `WebGPU` I see that the game runs at `30 FPS`. The game works well when I run it in `WebGL`. All testing was carried out on my Android tablet.

I think the problem is that the original size of the blue sprite is smaller than its size on the layout.

## Attach a .c3p

[image_resize_web_gpu_performance_r337b.zip](https://github.com/WilsonPercival/WilsonPercival/files/14827498/image_resize_web_gpu_performance_r337b.zip)

## Steps to reproduce

1. Open a project.
2. Launch remote preview and open the game on your Android device.

## Observed result

<img width="1000" alt="webgpu" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/c8e39bbd-2fa2-422c-a788-df7082097f3f">

<img width="1000" alt="webgl" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/5fbdb15c-551c-43ca-b7bf-4fcbe024e4ee">

## Expected result

The game should run fine if I run it in `WebGPU`.

## More details



**Affected browsers/platforms:** Chrome (Android)

**First affected release:** Broke in `r337b` because it was the first version to add `WebGPU` support.

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r379 (stable)
Browser: Chrome 123.0.6312.80
Browser engine: Chromium
Context: webapp
Operating system: Android 12.0.0
Device type: mobile
Device pixel ratio: 1.3312500715255737
Logical CPU cores: 8
Approx. device memory: 2 GB
User agent: Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/123.0.0.0 Safari/537.36
Language setting: en-US
Local storage
Storage quota (approx): 13 gb
Storage usage (approx): 32 mb (0.2%)
Persistant storage: Yes
Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.
UI effects are disabled in settings.
WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (Qualcomm)
Renderer: ANGLE (Qualcomm, Adreno (TM) 610, OpenGL ES 3.2)
Major performance caveat: no
Maximum texture size: 4096
Point size range: 1 to 1023
Extensions:
EXT_clip_control
EXT_color_buffer_float
EXT_color_buffer_half_float
EXT_float_blend
EXT_texture_filter_anisotropic
EXT_texture_norm16
NV_shader_noperspective_interpolation
OES_draw_buffers_indexed
OES_texture_float_linear
WEBGL_clip_cull_distance
WEBGL_compressed_texture_astc
WEBGL_compressed_texture_etc
WEBGL_compressed_texture_etc1
WEBGL_debug_renderer_info
WEBGL_debug_shaders
WEBGL_lose_context
WEBGL_multi_draw
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
WebM VP9 (video/webm;codecs=vp9)
WebM VP8 (video/webm;codecs=vp8)
WebM H.264 (video/webm;codecs=avc1.420034)

</details>
