## Problem description

If the font file name contains `[` or `.` then fonts will not be loaded in Mozilla. But this bug only happens once. If you reload the page, then after loading the game, the fonts will be loaded. If you close and open Mozilla again, the bug can be repeated again.

I also tested this bug on version r317-2s and after changing the font size in the game, it changed to the correct one.

Everything works fine in chrome.

## Attach a .c3p

[font_face_mozilla_bug_r326b.zip](https://github.com/WilsonPercival/WilsonPercival/files/10474183/font_face_mozilla_bug_r326b.zip)

## Steps to reproduce

1. Close the mozilla.
2. Open mozilla.
3. Open the project.
4. Run the project and open the console.

## Observed result

As we can see, the `bla.ck` and `bo[ld` fonts did not load. The console also reports this.

![ob](https://user-images.githubusercontent.com/91274932/213911518-f127b3a8-55f1-4cb2-92c5-676250a03ad4.png)

## Expected result

All fonts should load.

## More details



**Affected browsers/platforms:** Mozilla

**First affected release:** broke in r326b

## System details

<details><summary>View details</summary>


Platform information

Product: Construct 3 r326 (beta)
Browser: Firefox 109.0
Browser engine: Gecko
Context: browser
Operating system: Windows 7
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: (unavailable)
User agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64; rv:109.0) Gecko/20100101 Firefox/109.0
Language setting: en-US
Local storage

Storage quota (approx): 9.8 gb
Storage usage (approx): 123 mb (1.2%)
Persistant storage: No
Browser support notes

This list contains missing features that are not required, but could improve performance or user experience if supported.

    Rendering multiple on-screen Layout Views is slow in Firefox due to bug 1163426
    The Clipboard API is not supported. Some clipboard features may be unavailable.
    UI effects are disabled in settings.
    Determining input device capabilities is not supported.

WebGL information

Version string: WebGL 2.0
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (Intel)
Renderer: ANGLE (Intel, Intel(R) HD Graphics Direct3D11 vs_5_0 ps_5_0)
Major performance caveat: no
Maximum texture size: 16384
Point size range: 1 to 1024
Extensions:

    EXT_color_buffer_float
    EXT_float_blend
    EXT_texture_compression_bptc
    EXT_texture_compression_rgtc
    EXT_texture_filter_anisotropic
    OES_draw_buffers_indexed
    OES_texture_float_linear
    OVR_multiview2
    WEBGL_compressed_texture_s3tc
    WEBGL_compressed_texture_s3tc_srgb
    WEBGL_debug_renderer_info
    WEBGL_debug_shaders
    WEBGL_lose_context

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
    Ogg Opus (audio/ogg; codecs=opus)

Video information

Supported decode formats:

    WebM AV1 (video/webm; codecs=av01.0.00M.08)
    MP4 AV1 (video/mp4; codecs=av01.0.00M.08)
    WebM VP9 (video/webm; codecs=vp9)
    WebM VP8 (video/webm; codecs=vp8)
    Ogg Theora (video/ogg; codecs=theora)
    H.264 (video/mp4; codecs=avc1.42E01E)

Supported encode formats:

    WebM VP8 (video/webm; codecs=vp8)



</details>
