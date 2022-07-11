## Problem description

When the mobile keyboard is present, the condition `On tap object` fires, but when the tap is not on a sprite, but on an empty area below it.
The tap on sprite itself doesn't trigger the action.

## Attach a .c3p

[mobile_keyboard_on_tap_bug_r301b.zip](https://github.com/WilsonPercival/WilsonPercival/files/9082339/mobile_keyboard_on_tap_bug_r301b.zip)

## Steps to reproduce

1. Open the project and click "Remote preview".
2. Open the link on a mobile device.
3. Tap on the input field.
4. The keyboard shows up.
5. Tap on the sprite. No action occurs. The keyboard disappears.
6. Tap on the input field again. The keyboard shows up.
7. Tap on the area where the sprite was before the appearance of the keyboard (a red zone in the screenshot).
8. Action (increment the number) occurs.

## Observed result

![photo_2022-07-11_10-50-56](https://user-images.githubusercontent.com/91274932/178225635-855b5424-5aa6-45c3-aca5-0300f68fb7ae.jpg)

![photo_2022-07-11_10-50-56 (2)](https://user-images.githubusercontent.com/91274932/178225628-fdd9656e-e03a-4405-8f69-ceabe4ee95d9.jpg)

## Expected result

When the keyboard is active, tap on the sprite triggers the action. No other areas trigger the action.

## More details

1. It seems that the collision mask stayed on the original place, whereas the sprite moved up.
2. On a side note, when tapping on the area around the canvas (black one), the keyboard doesn't disappear.

**Affected browsers/platforms:** Chrome (Android)

**First affected release:** broke in r301b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r301 (beta)
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
Storage usage (approx): 335 mb (0.6%)
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
