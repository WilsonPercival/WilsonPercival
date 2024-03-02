## Problem description

I already reported this: https://github.com/Scirra/Construct-bugs/issues/7855

I consider, that you are mistaken. Let's try to calculate the number of vertical circles using this formula:

`(spriteSheetSize / (spriteSize * spriteCount)) / effectParam` where

`spriteSheetSize` - spritesheet size;
`spriteSize` - sprite size;
`spriteCount` - number of sprites on the spritelist;
`effectParam` - the value of the `Dot size` parameter of the `Polka dot` effect.

The sprite sheet is 32x32 in size.

<img width="295" alt="spritesheet1" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/e15bd096-d70d-4edf-9ce4-002f8c880fdd">

With `5%` value of the effect parameter, let's try to calculate the number of circles vertically:

`(32 / (32 * 1)) / 0.05 = 20`

We see that in the layout editor there are indeed 20 circles in height. Now let's make a clone of this sprite. The sprite sheet becomes 32x128 in size.

<img width="310" alt="spritesheet2" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/630e0c97-1a21-4dfc-b9f6-73d573e69a24">

Let's now try to calculate the number of circles vertically:

`(128 / (32 * 2)) / 0.05 = 40`

We see that in the layout editor there are indeed 40 circles in height. Do you really still think that a difference of 2 times is an error in floating point calculations?

## Attach a .c3p

[polka_dot_spritesheet_bug_r42b.zip](https://github.com/WilsonPercival/WilsonPercival/files/14468671/polka_dot_spritesheet_bug_r42b.zip)

## Steps to reproduce

1. Open a project.
2. Make a clone of the sprite.

## Observed result

<img width="294" alt="observed" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/8e594bab-52de-4133-b188-333aed9a2b26">

## Expected result

<img width="293" alt="expected" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/665f2d33-361b-4819-a40f-5b1d9844f23a">

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** Broke in `r42b` because it's the oldest version I can test.

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r381 (beta)
Browser: Chrome 122.0.6261.69
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/122.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 283 gb
Storage usage (approx): 1.2 gb (0.4%)
Persistant storage: Yes

Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.

Nothing is missing. Everything is OK!
WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Google Inc. (AMD)
Renderer: ANGLE (AMD, AMD Radeon(TM) Graphics (0x00001638) Direct3D11 vs_5_0 ps_5_0, D3D11)
Major performance caveat: no
Maximum texture size: 16384
Point size range: 1 to 1024
Extensions:

EXT_clip_control
EXT_color_buffer_float
EXT_color_buffer_half_float
EXT_conservative_depth
EXT_depth_clamp
EXT_disjoint_timer_query_webgl2
EXT_float_blend
EXT_polygon_offset_clamp
EXT_texture_compression_bptc
EXT_texture_compression_rgtc
EXT_texture_filter_anisotropic
EXT_texture_norm16
KHR_parallel_shader_compile
NV_shader_noperspective_interpolation
OES_draw_buffers_indexed
OES_texture_float_linear
OVR_multiview2
WEBGL_blend_func_extended
WEBGL_clip_cull_distance
WEBGL_compressed_texture_s3tc
WEBGL_compressed_texture_s3tc_srgb
WEBGL_debug_renderer_info
WEBGL_debug_shaders
WEBGL_lose_context
WEBGL_multi_draw
WEBGL_polygon_mode
WEBGL_provoking_vertex
Audio information
System sample rate: 48000 Hz
Output channels: 2
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
MPEG-4 H.265 (video/mp4;codecs=hev1.1.2.L93.B0)
MPEG-4 H.264 (video/mp4;codecs=avc1.420034)
Supported encode formats:

WebM AV1 (video/webm;codecs=av01.0.00M.08)
WebM VP9 (video/webm;codecs=vp9)
WebM VP8 (video/webm;codecs=vp8)
WebM H.264 (video/webm;codecs=avc1.420034)

</details>
