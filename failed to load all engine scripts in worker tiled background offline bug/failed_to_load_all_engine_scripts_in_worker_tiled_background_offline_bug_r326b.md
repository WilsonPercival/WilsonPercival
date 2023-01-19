## Problem description

I caught a bug that only reproduces if the power is turned off abruptly. I have a Wi-Fi router and a laptop that catches this network. The router is plugged into an outlet. The electricity goes out in the whole house. After that, the project does not load.

I tried to repeat the error by disconnecting from the Wi-Fi network. The project is still working well. I tried pressing a button on the keyboard that disables the network connection driver (I don't understand this) and the project still works well. The project does not work only if my electricity is cut off abruptly.

This is not the only error that I have caught during a sudden power outage. But since I couldn't reproduce them when I had electricity - I didn't report them.

## Attach a .c3p

[failed_to_load_all_engine_scripts_in_worker_tiled_background_offline_bug_r326b.zip](https://github.com/WilsonPercival/WilsonPercival/files/10459563/failed_to_load_all_engine_scripts_in_worker_tiled_background_offline_bug_r326b.zip)

## Steps to reproduce

1. Turn off the electricity to which the router is connected.
2. Create a new project.
3. Add `TiledBackground`.
4. Run the project.
5. Open the console.

## Observed result

![observed](https://user-images.githubusercontent.com/91274932/213521913-7e3bc570-5005-47c9-b1e2-dcec987faa00.png)

## Expected result

The project is loading.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r326b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r326 (beta)
Browser: Chrome 109.0.5414.75
Browser engine: Chromium
Context: browser
Operating system: Windows NT 0.1.0
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/109.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 59 gb
Storage usage (approx): 620 mb (1%)
Persistant storage: No

Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.

UI effects are disabled in settings.
WebGL 2+ is not supported. Rendering quality and features may be affected.
WebGL indicates a major performance caveat. It is probably using software rendering.
WebGL information
Version string: WebGL 1.0 (OpenGL ES 2.0 Chromium)
Numeric version: 1
Supports NPOT textures: partial
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (Google)
Renderer: ANGLE (Google, Vulkan 1.3.0 (SwiftShader Device (Subzero) (0x0000C0DE)), SwiftShader driver)
Major performance caveat: yes
Maximum texture size: 8192
Point size range: 1 to 1023
Extensions:

ANGLE_instanced_arrays
EXT_blend_minmax
EXT_color_buffer_half_float
EXT_float_blend
EXT_frag_depth
EXT_shader_texture_lod
EXT_texture_compression_bptc
EXT_texture_compression_rgtc
EXT_texture_filter_anisotropic
EXT_sRGB
OES_element_index_uint
OES_fbo_render_mipmap
OES_standard_derivatives
OES_texture_float
OES_texture_float_linear
OES_texture_half_float
OES_texture_half_float_linear
OES_vertex_array_object
WEBGL_color_buffer_float
WEBGL_compressed_texture_astc
WEBGL_compressed_texture_etc
WEBGL_compressed_texture_etc1
WEBGL_compressed_texture_s3tc
WEBGL_compressed_texture_s3tc_srgb
WEBGL_debug_renderer_info
WEBGL_depth_texture
WEBGL_draw_buffers
WEBGL_lose_context
WEBGL_multi_draw
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
H.264 (video/mp4; codecs=avc1.42E01E)
Supported encode formats:

WebM VP9 (video/webm; codecs=vp9)
WebM VP8 (video/webm; codecs=vp8)

</details>
