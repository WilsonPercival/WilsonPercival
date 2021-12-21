## Problem description

Поломанный интерфейс в Mac OS X.

## Attach a .c3p



## Steps to reproduce



## Observed result

Кнопки в окне "Properties" в разделе "Instance variables" и "Effects" без текста и не двигаются:

https://user-images.githubusercontent.com/91274932/146971545-b355c0a6-2f96-4080-8639-c2c6f008fc2f.mp4

Текст вылезает за окно:

![photo_2021-12-21_12-29-13](https://user-images.githubusercontent.com/91274932/146971763-caeb539e-4287-4150-8d1a-c5c385250b9f.jpg)

Ячейки цветов в редакторе анимаций выходят за границы:

![photo_2021-12-21_12-31-53](https://user-images.githubusercontent.com/91274932/146971766-665d4ff0-aa8c-4595-b47b-f796c617a041.jpg)

В редакторе тайловых карт невозможно изменить масштаб:

https://user-images.githubusercontent.com/91274932/146972739-3c5e1a94-2965-4df5-98bb-8dc6da978b94.mp4

## Expected result

Рабочий интерфейс.

## More details

![photo_2021-12-21_12-28-24](https://user-images.githubusercontent.com/91274932/146971863-78e4e13f-3d64-417c-9013-e0ae970eacb7.jpg)

![photo_2021-12-21_12-28-13](https://user-images.githubusercontent.com/91274932/146971866-44c45f63-a894-40ce-b711-05fc06eb18a6.jpg)

**Affected browsers/platforms:** Safari

**First affected release:** broke in r276-2s

## System details

<details><summary>View details</summary>

Platform information
Browser: Safari
Browser version: 15.2
Browser engine: WebKit
Context: browser
Operating system: Mac OS X
Operating system version: 10.15_7
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: (unavailable, defaulting to 2)
Approx. device memory: (unavailable)
User agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/15.2 Safari/605.1.15
C3 release: r276.2 (stable)
Language setting: en-US
Local storage
Storage quota (approx): (status unavailable)
Storage usage (approx): (status unavailable)
Persistant storage: No
Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.
 • Rendering multiple on-screen Layout Views is slow in Safari due to bug 177132 (https://bugs.webkit.org/show_bug.cgi?id=177132)
 • CSS containment is not supported. Editor performance may be significantly degraded.
 • The <dialog> element is not supported. A polyfill is in use.
 • Web Animations are not supported. Animations are disabled.
 • WebGL 2+ is not supported. Rendering quality and features may be affected.
 • ImageBitmap is not supported. Texture loading performance may be degraded.
 • Idle callbacks are not supported. Background loading performance may be degraded.
 • Determining input device capabilities is not supported.
 • Storage quota estimate is unavailable.
WebGL information
Version string: WebGL 1.0
Numeric version: 1
Supports NPOT textures: partial
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Apple Inc.
Renderer: Apple GPU
Major performance caveat: no
Maximum texture size: 8192
Point size range: 1 to 255.875
Extensions:
 • EXT_blend_minmax
 • EXT_sRGB
 • EXT_frag_depth
 • OES_texture_float
 • OES_texture_float_linear
 • OES_texture_half_float
 • OES_texture_half_float_linear
 • OES_standard_derivatives
 • EXT_shader_texture_lod
 • EXT_texture_compression_rgtc
 • EXT_texture_filter_anisotropic
 • OES_vertex_array_object
 • OES_element_index_uint
 • OES_fbo_render_mipmap
 • WEBGL_lose_context
 • WEBGL_compressed_texture_s3tc
 • WEBGL_compressed_texture_s3tc_srgb
 • WEBGL_depth_texture
 • WEBGL_draw_buffers
 • ANGLE_instanced_arrays
 • WEBGL_debug_shaders
 • WEBGL_debug_renderer_info
 • EXT_color_buffer_half_float
 • EXT_float_blend
 • WEBGL_color_buffer_float
 • KHR_parallel_shader_compile
 • WEBGL_multi_draw
Audio information
System sample rate: 44100 Hz
Output channels: 2
Output interpretation: speakers
Supported decode formats:
 • MPEG-4 AAC (audio/mp4; codecs=mp4a.40.5)
 • MP3 (audio/mpeg)
 • FLAC (audio/flac)
Supported encode formats:
 • MPEG-4 AAC (audio/mp4; codecs=mp4a.40.5)
Video information
Supported decode formats:
 • H.264 (video/mp4; codecs=avc1.42E01E)
Supported encode formats:
 • H.264 (video/mp4; codecs=avc1.42E01E)

</details>
