## Problem description

I have two archives with animation. `work.zip` imports fine. And `no_work.zip` does not import. Why?

[work.zip](https://github.com/WilsonPercival/WilsonPercival/files/10408277/work.zip)

[no_work.zip](https://github.com/WilsonPercival/WilsonPercival/files/10408279/no_work.zip)

https://user-images.githubusercontent.com/91274932/212240797-1530df33-2913-468f-9e71-afba266a3ed4.mp4

I also noticed that in `r317-2s` the `no_work.zip` archive is imported, but the frame sort order is broken:

https://user-images.githubusercontent.com/91274932/212240812-53a3baaf-2a81-4ab9-8862-44886ad115cb.mp4

## Attach a .c3p

There is not.

## Steps to reproduce



## Observed result



## Expected result



## More details

https://www.construct.net/en/make-games/manuals/construct-3/interface/animations-editor

**Affected browsers/platforms:** Mozilla

**First affected release:** broke in r325b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r325 (beta)
Browser: Chrome 109.0.5414.74
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
Storage usage (approx): 566 mb (0.9%)
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
