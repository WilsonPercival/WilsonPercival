## Problem description

When I launch the game, `SVGPicture` does not display any content. There are also errors in the console.

`Chrome` works well.

## Attach a .c3p

[svg_picture_mozilla_bug_r368_2s.zip](https://github.com/WilsonPercival/WilsonPercival/files/13479243/svg_picture_mozilla_bug_r368_2s.zip)

## Steps to reproduce

1. Open and run the project.

## Observed result

<img width="937" alt="observed" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/d5739666-ed93-4dbf-9429-9cdae80ab81e">

## Expected result

`Chrome`:

<img width="939" alt="chrome" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/c1746af6-3ccf-4d55-b10c-c1d4c1e40e1f">

## More details



**Affected browsers/platforms:** Mozilla

**First affected release:** broke in r368-2s

## System details

<details><summary>View details</summary>


Platform information

Product: Construct 3 r368.2 (stable)
Browser: Firefox 120.0
Browser engine: Gecko
Context: browser
Operating system: Windows 10
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: (unavailable)
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:120.0) Gecko/20100101 Firefox/120.0
Language setting: en-US
Local storage

Storage quota (approx): 10 gb
Storage usage (approx): 68 mb (0.7%)
Persistant storage: No
Browser support notes

This list contains missing features that are not required, but could improve performance or user experience if supported.

    Rendering multiple on-screen Layout Views is slow in Firefox due to bug 1163426
    The Clipboard API is not supported. Some clipboard features may be unavailable.
    Determining input device capabilities is not supported.

WebGL information

Version string: WebGL 2.0
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (AMD)
Renderer: ANGLE (AMD, Radeon HD 3200 Graphics Direct3D11 vs_5_0 ps_5_0)
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
    Ogg Opus (audio/ogg; codecs=opus)

Video information

Supported decode formats:

    WebM AV1 (video/webm; codecs=av01.0.00M.08)
    MP4 AV1 (video/mp4; codecs=av01.0.00M.08)
    WebM VP9 (video/webm; codecs=vp9)
    WebM VP8 (video/webm; codecs=vp8)
    H.264 (video/mp4; codecs=avc1.42E01E)

Supported encode formats:

    WebM VP8 (video/webm; codecs=vp8)



</details>
