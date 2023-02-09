## Problem description

Construct crashes.

## Attach a .c3p

save open project: [New project.zip](https://github.com/WilsonPercival/WilsonPercival/files/10695637/New.project.zip) 


## Steps to reproduce

1. Create a new project.
2. Add a sprite.
3. Turn on animation preview.
4. Close the animation editor.

## Observed result

https://user-images.githubusercontent.com/91274932/217774902-acf0e827-a153-47f0-bfb7-ce47d9dd8885.mp4

## Expected result

Construct does not crash.

## More details

Error report information

Type: unhandled rejection
Reason: Error: unexpected type @ O.i@https://editor.construct.net/r329/main.js:1035:147 IB@https://editor.construct.net/r329/projectResources.js:303:33 cJa@https://editor.construct.net/r329/projectResources.js:299:286 $Ia@https://editor.construct.net/r329/projectResources.js:301:109
Stack: O.i@https://editor.construct.net/r329/main.js:1035:147 IB@https://editor.construct.net/r329/projectResources.js:303:33 cJa@https://editor.construct.net/r329/projectResources.js:299:286 $Ia@https://editor.construct.net/r329/projectResources.js:301:109
Construct version: r329
URL: https://editor.construct.net/r329/
Date: Thu Feb 09 2023 11:34:22 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 59.9 s
Platform information

Product: Construct 3 r329 (beta)
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
Extensions: EXT_color_buffer_float, EXT_float_blend, EXT_texture_compression_bptc, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, OES_draw_buffers_indexed, OES_texture_float_linear, OVR_multiview2, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context

**Affected browsers/platforms:** Mozilla

**First affected release:** broke in r329b

## System details

<details><summary>View details</summary>


Platform information

Product: Construct 3 r329 (beta)
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
Storage usage (approx): 29 mb (0.3%)
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
