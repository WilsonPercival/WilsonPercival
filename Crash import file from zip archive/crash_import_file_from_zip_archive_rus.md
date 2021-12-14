## Problem description

Констракт крашится после импорта файлов из zip-архива.

## Attach a .c3p

[crash_import_file_from_zip_archive_r276s.zip](https://github.com/WilsonPercival/WilsonPercival/files/7714380/crash_import_file_from_zip_archive_r276s.zip)

## Steps to reproduce

1. Создайте новый проект.
2. Нажмите на папку "Sounds" и выберите "Import sounds".
3. Откройте zip-архив и перетащите из него файл на поле "Drag and drop audio files here".

## Observed result

![xxxz](https://user-images.githubusercontent.com/91274932/146069895-e22344e6-0556-41eb-b41b-e41ca13cd276.png)

Error report information
Type: unhandled rejection
Reason: Error: The requested file could not be read, typically due to permission problems that have occurred after a reference to a file was acquired.
Construct 3 version: r276
URL: https://editor.construct.net/r276/
Date: Tue Dec 14 2021 21:51:43 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 129 s

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
C3 release: r276 (stable)
Language setting: en-US

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
Extensions: ANGLE_instanced_arrays, EXT_blend_minmax, EXT_color_buffer_half_float, EXT_float_blend, EXT_frag_depth, EXT_shader_texture_lod, EXT_texture_filter_anisotropic, WEBKIT_EXT_texture_filter_anisotropic, EXT_sRGB, KHR_parallel_shader_compile, OES_element_index_uint, OES_standard_derivatives, OES_texture_float, OES_texture_float_linear, OES_texture_half_float, OES_texture_half_float_linear, OES_vertex_array_object, WEBGL_color_buffer_float, WEBGL_compressed_texture_s3tc, WEBKIT_WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_depth_texture, WEBKIT_WEBGL_depth_texture, WEBGL_lose_context, WEBKIT_WEBGL_lose_context, WEBGL_multi_draw

## Expected result

Констракт не крашится.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r276s

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
C3 release: r276 (stable)
Language setting: en-US

Local storage
Storage quota (approx): 59 gb
Storage usage (approx): 253 mb (0.4%)
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
