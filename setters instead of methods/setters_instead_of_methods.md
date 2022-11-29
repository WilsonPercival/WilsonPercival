## Problem description

Why setters instead of methods? After all, I am constantly mistaken, for example, writing

```javascript
runtime.layout.scrolX = 13;
```

instead of

```javascript
runtime.layout.scrollX = 13;
```

If there was a method instead of a setter, I would see an error in the console:

`runtime.layout.setScrolX(13);` - there is no such method, great! I don't spend a lot of time looking for a bug.

You've already done well by adding the `scrollTo(x, y)` method, but what about the rest? `instance.width` instead of `instance.setWidth()`, `text.fontFace` instead of `text.setFontFace()`. Please tell me how can I get rid of the waste of time when on writing the wrong setter name I'm just looking for where I went wrong?

I have already reported a similar case

https://github.com/Scirra/Construct-3-bugs/issues/5702

This saves a lot of time, thanks a lot for this.

I noticed that a wonderful thing was introduced into JS - private fields. Now, if I suddenly make a mistake in the name of the field, they will inform me about it immediately, before the game starts, and this is wonderful.

## Attach a .c3p

There is not.

## Steps to reproduce



## Observed result

```javascript
runtime.layout.scrolX = 13;
```

![observed](https://user-images.githubusercontent.com/91274932/204441366-49079540-8109-4b9f-8c32-524eb4ea6c6a.png)

I don't get any error or working code.

## Expected result

```javascript
runtime.layout.setScrolX(13);
```

![expected](https://user-images.githubusercontent.com/91274932/204441503-3c2847f3-8486-4990-843d-7b1f4973bef9.png)

I see the mistake right away and understand where I made it and go to fix it right away, without spending a lot of time figuring out the reasons.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r319-2b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r319.2 (beta)
Browser: Chrome 107.0.5304.121
Browser engine: Chromium
Context: browser
Operating system: Windows NT 0.1.0
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 2
Approx. device memory: 4 GB
User agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/107.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 59 gb
Storage usage (approx): 267 mb (0.4%)
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
Renderer: ANGLE (Intel, Intel(R) HD Graphics Direct3D9Ex vs_3_0 ps_3_0, igdumdim64.dll)
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
EXT_sRGB
KHR_parallel_shader_compile
OES_element_index_uint
OES_fbo_render_mipmap
OES_standard_derivatives
OES_texture_float
OES_texture_float_linear
OES_texture_half_float
OES_texture_half_float_linear
OES_vertex_array_object
WEBGL_color_buffer_float
WEBGL_compressed_texture_s3tc
WEBGL_compressed_texture_s3tc_srgb
WEBGL_debug_renderer_info
WEBGL_debug_shaders
WEBGL_depth_texture
WEBGL_lose_context
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
