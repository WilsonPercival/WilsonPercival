## Problem description

When I click on `Text input` the game behaves differently depending on whether I'm playing the game in the browser or through the app.

## Attach a .c3p

[text_input_y_android_bug_r385b.zip](https://github.com/WilsonPercival/WilsonPercival/files/14817889/text_input_y_android_bug_r385b.zip)

[text_input_y_android_bug_r385b.android.debug.zip](https://github.com/WilsonPercival/WilsonPercival/files/14817891/text_input_y_android_bug_r385b.android.debug.zip)

## Steps to reproduce

1. Open the project and export to `Debug APK` or use my export.
2. Install the game on your Android device and launch it.
3. Click on `Text input`. Notice that the entire playing space has risen up. Also `Text input` remains at the bottom of the screen.

4. Launch remote preview on Android.
5. Click on `Text input`. Note that the game space has not changed, and the `Text input` has moved to the top of the screen.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/a1d67b89-7921-422d-9fc7-08b0f634e92a

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/80aec625-2e34-460a-b7d8-1538a747c94d

## Expected result

There should be the same behavior both when running in the browser and when running the application.

## More details



**Affected browsers/platforms:** Chrome (Android)

**First affected release:** Broke in `r354b` because it is the oldest version that allows export to debug apk.

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r379 (stable)
Browser: Chrome 123.0.6312.80
Browser engine: Chromium
Context: webapp
Operating system: Android 12.0.0
Device type: mobile
Device pixel ratio: 1.3312500715255737
Logical CPU cores: 8
Approx. device memory: 2 GB
User agent: Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/123.0.0.0 Safari/537.36
Language setting: en-US
Local storage
Storage quota (approx): 13 gb
Storage usage (approx): 32 mb (0.2%)
Persistant storage: Yes
Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.
UI effects are disabled in settings.
WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (Qualcomm)
Renderer: ANGLE (Qualcomm, Adreno (TM) 610, OpenGL ES 3.2)
Major performance caveat: no
Maximum texture size: 4096
Point size range: 1 to 1023
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
System sample rate: 48000 Hz
Output channels: 2
Output interpretation: speakers
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
