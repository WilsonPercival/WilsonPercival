## Problem description

I have an svg file that I'm trying to display via `SVG Picture`. The problem is that on `MacOS` in the `Mozilla` browser this svg file is not displayed correctly. The problem is not reproduced if we try `MacOS` and the `Chrome` browser. The problem does not reproduce if we try `Windows 11` and `Mozilla` browser.

## Attach a .c3p

[mac_mozilla_svg_bug_r393b.zip](https://github.com/WilsonPercival/WilsonPercival/files/15483991/mac_mozilla_svg_bug_r393b.zip)

## Steps to reproduce

1. Open a project. The problem is observed in both the layout editor and preview.

## Observed result

![observed](https://github.com/WilsonPercival/WilsonPercival/assets/91274932/05cc8358-396c-48d0-9e51-6406ecd958a5)

## Expected result

The svg file should display correctly.

## More details



**Affected browsers/platforms:** MacOS Mozilla

**First affected release:** broke in 

## System details

<details><summary>View details</summary>

Platform information

Product: Construct 3 r393 (beta)
Browser: Firefox 124.0
Browser engine: Gecko
Context: browser
Operating system: macOS 10.15
Device type: desktop
Device pixel ratio: 2.4
Logical CPU cores: 2
Approx. device memory: (unavailable)
User agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.15; rv:124.0) Gecko/20100101 Firefox/124.0
Language setting: en-US
Local storage

Storage quota (approx): 10 gb
Storage usage (approx): 104 mb (1%)
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
Vendor: Apple
Renderer: Apple M1, or similar
Major performance caveat: no
Maximum texture size: 8192
Point size range: 1 to 64
Extensions:

    EXT_color_buffer_float
    EXT_float_blend
    EXT_texture_compression_rgtc
    EXT_texture_filter_anisotropic
    OES_draw_buffers_indexed
    OES_texture_float_linear
    WEBGL_compressed_texture_s3tc
    WEBGL_compressed_texture_s3tc_srgb
    WEBGL_debug_renderer_info
    WEBGL_debug_shaders
    WEBGL_lose_context
    WEBGL_provoking_vertex

Audio information

System sample rate: 24000 Hz
Output channels: 1
Output interpretation: speakers
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
    MPEG-4 VP9 (video/mp4;codecs=vp9)
    MPEG-4 H.264 (video/mp4;codecs=avc1.420034)

Supported encode formats:

    WebM VP8 (video/webm;codecs=vp8)

</details>
