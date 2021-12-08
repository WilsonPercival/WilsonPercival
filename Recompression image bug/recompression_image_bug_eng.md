## Problem description

PNG-8 compression doesn't occur.

## Attach a .c3p

[recompression_image_bug_r269s.zip](https://github.com/WilsonPercival/WilsonPercival/files/7667635/recompression_image_bug_r269s.zip)

## Steps to reproduce

1. Open the project.
2. Export to web (HTML5).
3. Check the following: Deduplicate images, Recompress images, Minify mode: simple.
4. Wait for the end of exporting.
5. Open the folder "Images" in the exported zip-file.

## Observed result

Construct merged two images in one spritesheet which size is 8,02 KB.

![shared-0-sheet0](https://user-images.githubusercontent.com/91274932/145014370-ef0ce5e9-a304-456d-98cb-94a8a5ea1bcf.png)

## Expected result

There should be two images: one is 156 byte, the other is 5,74 KB totaling less than 8,02 KB.

![shared-0-sheet0](https://user-images.githubusercontent.com/91274932/145014395-23b840bd-3c06-4fcd-8d1a-2f74475e8e98.png)

![sprite2-animation 1-000](https://user-images.githubusercontent.com/91274932/145014412-ca37e9b7-846e-44da-9c7b-ff766130d817.png)

## More details

According to this article: https://www.construct.net/en/tutorials/construct-3s-export-4

Next, all PNG images are run through a tool called OptiPNG, which tries lots of different ways to compress the image and picks whichever results in the smallest file size. This often gets an automatic and lossless 10-15% saving on the download size, but can take a long time. It's also able to losslessly palette-reduce 32-bit PNGs to 8-bit PNGs when the image has 256 colors or fewer, resulting in a much smaller file size, which is particularly effective for art styles which don't use many colors, like retro style pixel art. If you turn off the image recompression option on export, this step is skipped. This can make exports very quick, but can also make the download size significantly larger.

Is there a chance that the way Construct did this uses less memory in a game?

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r268s

## System details

<details><summary>View details</summary>

Platform information
Browser: Chrome
Browser version: 95.0.4638.54
Browser engine: Chromium
Context: browser
Operating system: Windows
Operating system version: 7
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/95.0.4638.54 Safari/537.36
C3 release: r268 (stable)
Language setting: en-US

Local storage
Storage quota (approx): 59 gb
Storage usage (approx): 602 mb (1%)
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
Renderer: ANGLE (Intel, Intel(R) HD Graphics Direct3D9Ex vs_3_0 ps_3_0, igdumdim64.dll-10.18.10.4653)
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
