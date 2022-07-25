## Problem description

When I launch the game in the browser on android, the player appears in my notifications.

## Attach a .c3p

[music_notification_r302s.zip](https://github.com/WilsonPercival/WilsonPercival/files/9179597/music_notification_r302s.zip)

Export Web (HTML5): [New project.zip](https://github.com/WilsonPercival/WilsonPercival/files/9179595/New.project.zip)

https://music-notification.netlify.app/

## Steps to reproduce

1. Open a project.
2. Export to the Web (HTML5), either use the ready-made export that I attached, or follow the link - I threw the export there.
3. Open the game.

## Observed result

![photo_2022-07-25_11-50-53](https://user-images.githubusercontent.com/91274932/180740314-164ab1bf-16c9-4cd8-9a4c-5185fdf95836.jpg)

## Expected result

![photo_2022-07-25_12-05-41](https://user-images.githubusercontent.com/91274932/180741398-cacdc46e-eda0-42e9-85c4-2ec832f43361.jpg)

## More details

If I press the pause button, the music will stop playing.

If I minimize the browser with the game - the notification bar will remain.

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r302s

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r302 (stable)
Browser: Chrome 103.0.5060.114
Browser engine: Chromium
Context: browser
Operating system: Windows NT 0.1.0
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/103.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 59 gb
Storage usage (approx): 213 mb (0.4%)
Persistant storage: No

Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.

UI effects are disabled in settings.
WebGL 2+ is not supported. Rendering quality and features may be affected.
WebGL information
Version string: WebGL 1.0 (OpenGL ES 2.0 Chromium)
Numeric version: 1
Supports NPOT textures: partial
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (Intel)
Renderer: ANGLE (Intel, Intel(R) HD Graphics Direct3D9Ex vs_3_0 ps_3_0, igdumdim64.dll)
Major performance caveat: no
Maximum texture size: 8192
Point size range: 1 to 256
Extensions:

ANGLE_instanced_arrays
EXT_blend_minmax
EXT_color_buffer_half_float
EXT_float_blend
EXT_frag_depth
EXT_shader_texture_lod
EXT_texture_filter_anisotropic
WEBKIT_EXT_texture_filter_anisotropic
EXT_sRGB
KHR_parallel_shader_compile
OES_element_index_uint
OES_fbo_render_mipmap
OES_standard_derivatives
OES_texture_float
OES_texture_float_linear
OES_texture_half_float
OES_texture_half_float_linear
OES_vertex_array_object
WEBGL_color_buffer_float
WEBGL_compressed_texture_s3tc
WEBKIT_WEBGL_compressed_texture_s3tc
WEBGL_compressed_texture_s3tc_srgb
WEBGL_debug_renderer_info
WEBGL_debug_shaders
WEBGL_depth_texture
WEBKIT_WEBGL_depth_texture
WEBGL_lose_context
WEBKIT_WEBGL_lose_context
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
