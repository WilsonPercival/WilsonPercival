## Problem description

The longer I scroll through `Tiled Background`, the more unnatural it behaves.

I can only reproduce this problem on an android phone. My friend can also reproduce the problem on his Android phone. I can't reproduce the problem on my computer and on my Android tablet.

## Attach a .c3p

[tiled_background_image_offset_android_bug_r122b.zip](https://github.com/WilsonPercival/WilsonPercival/files/14001576/tiled_background_image_offset_android_bug_r122b.zip)

## Steps to reproduce

1. Open a project.
2. Open the remote preview and launch the game on your Android phone.
3. Tap on the left side of the screen to scroll more.
4. Tap on the right side of the screen to scroll less.
5. The problem is most noticeable when the text value is more than 300000. If you cannot reproduce the problem, try all the android phones you have.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/61d23812-9958-4491-9bce-0faa5ba8bd46

## Expected result

`Tiled Background` should work well.

## More details



**Affected browsers/platforms:** Chrome (Android)

**First affected release:** Broke in `r122b` because it is the oldest version in which I can recreate the project. Still doesn't work in `r375b`.

## System details

<details><summary>View details</summary>

Platform informationProduct: Construct 3 r368.2 (stable)
Browser: Chrome 120.0.6099.144
Browser engine: Chromium
Context: browser
Operating system: Android 12.0.0
Device type: mobile
Device pixel ratio: 3
Logical CPU cores: 8
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Mobile Safari/537.36
Language setting: uk-UALocal storageStorage quota (approx): 137 ГБ
Storage usage (approx): 217 КБ (0%)
Persistant storage: NoBrowser support notesThis list contains missing features that are not required, but could improve performance or user experience if supported.Nothing is missing. Everything is OK!WebGL informationVersion string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (ARM)
Renderer: ANGLE (ARM, Mali-G57 MC2, OpenGL ES 3.2)
Major performance caveat: no
Maximum texture size: 4096
Point size range: 1 to 1024
Extensions:EXT_color_buffer_floatEXT_color_buffer_half_floatEXT_float_blendEXT_texture_filter_anisotropicOES_draw_buffers_indexedOES_texture_float_linearWEBGL_compressed_texture_astcWEBGL_compressed_texture_etcWEBGL_compressed_texture_etc1WEBGL_debug_renderer_infoWEBGL_debug_shadersWEBGL_lose_contextWEBGL_multi_drawAudio informationSystem sample rate: 48000 Hz
Output channels: 2
Output interpretation: speakers
Supported decode formats:WebM Opus (audio/webm; codecs=opus)Ogg Opus (audio/ogg; codecs=opus)WebM Vorbis (audio/webm; codecs=vorbis)Ogg Vorbis (audio/ogg; codecs=vorbis)MPEG-4 AAC (audio/mp4; codecs=mp4a.40.5)MP3 (audio/mpeg)FLAC (audio/flac)PCM WAV (audio/wav; codecs=1)Supported encode formats:WebM Opus (audio/webm; codecs=opus)Video informationSupported decode formats:WebM AV1 (video/webm; codecs=av01.0.00M.08)MP4 AV1 (video/mp4; codecs=av01.0.00M.08)WebM VP9 (video/webm; codecs=vp9)WebM VP8 (video/webm; codecs=vp8)H.265 (video/mp4; codecs=hev1.1.2.L93.B0)H.264 (video/mp4; codecs=avc1.42E01E)Supported encode formats:WebM VP9 (video/webm; codecs=vp9)WebM VP8 (video/webm; codecs=vp8)

</details>
