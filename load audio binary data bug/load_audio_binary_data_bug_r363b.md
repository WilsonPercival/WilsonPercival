## Problem description

If I load both files first and then try to play the first one, an error will appear in the console and I will not hear any sound.

If I load the first file, then play the first file, and then load the second file, and then play the second file, then I have no problem playing any of those files.

## Attach a .c3p

[load_audio_binary_data_bug_r363b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12936721/load_audio_binary_data_bug_r363b.zip)

[Cannon.webm](https://github.com/WilsonPercival/WilsonPercival/assets/91274932/18fe26d9-4910-4fac-8634-39bd46f16626)

[Collectible_1.webm](https://github.com/WilsonPercival/WilsonPercival/assets/91274932/74a33025-597f-4b9d-ba5a-9994ac340a02)

## Steps to reproduce

1. Open a project.
2. Launch and open the console.
3. Click on the `Load 1` button and select the `Cannon.webm` file.
4. Click on the `Load 2` button and select the `Collectible_1.webm` file.
5. Click on the `Play 1` button. Please note that there is an error in the console and we cannot hear any sound.

6. Reload the page.
7. Click on the `Load 1` button and select the `Cannon.webm` file.
8. Click on the `Play 1` button.
9. Click on the `Load 2` button and select the `Collectible_1.webm` file.
10. Click on the `Play 2` button. Please note that we now have no problem playing any of the sounds.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/bb8dc41c-4233-478e-bc8a-594ab3ca788b

## Expected result

I need to be able to play sounds no matter how I load them.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r363b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r363 (beta)
Browser: Chrome 118.0.5993.71
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/118.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 283 gb
Storage usage (approx): 1.8 gb (0.6%)
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
