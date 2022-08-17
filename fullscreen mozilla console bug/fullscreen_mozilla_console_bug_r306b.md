## Problem description

If I press very fast `F11` and click the mouse - the image will move to the right.

## Attach a .c3p

[fullscreen_mozilla_console_bug_r306b.zip](https://github.com/WilsonPercival/WilsonPercival/files/9365773/fullscreen_mozilla_console_bug_r306b.zip)

## Steps to reproduce

1. Open a project.
2. Run it and open the console.
3. Press `F11` and immediately click on the screen with the mouse. These actions should be with minimal delay.

## Observed result

![bug](https://user-images.githubusercontent.com/91274932/185232952-b5a1bd3b-4345-4dec-b747-d3b382d24682.gif)

## Expected result

![expected](https://user-images.githubusercontent.com/91274932/185234578-3110bcfb-f4b8-4ccd-b238-44bd77e888c6.gif)

## More details

Everything works fine in chrome.

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r306b

## System details

<details><summary>View details</summary>


Platform information

Product: Construct 3 r306 (beta)
Browser: Firefox 103.0
Browser engine: Gecko
Context: browser
Operating system: Windows 7
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: (unavailable)
User agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64; rv:103.0) Gecko/20100101 Firefox/103.0
Language setting: en-US
Local storage

Storage quota (approx): 9.8 gb
Storage usage (approx): 18 mb (0.2%)
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
