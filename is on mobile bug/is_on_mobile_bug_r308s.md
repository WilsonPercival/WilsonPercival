## Problem description

The documentation says that the `Platform Info` object condition `Is on mobile` should always return `true` if the device is `Android`. But I have an android tablet and does not return the truth.

## Attach a .c3p

[is_on_mobile_bug_308s.zip](https://github.com/WilsonPercival/WilsonPercival/files/9534702/is_on_mobile_bug_308s.zip)

## Steps to reproduce

1. Open and run a project on Galaxy Tab A7.

## Observed result

![Screenshot_20220909-132643_Chrome](https://user-images.githubusercontent.com/91274932/189333908-d1b70cc0-3e90-4134-bb2e-9797786705f7.png)

## Expected result

![Screenshot_20220909-132834_Chrome](https://user-images.githubusercontent.com/91274932/189333919-f586fc2c-868d-47a7-a533-571ba5803e29.png)

## More details

https://www.construct.net/en/make-games/manuals/construct-3/plugin-reference/platform-info

**Affected browsers/platforms:** Chrome

**First affected release:** broke in r308s

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r308 (stable)
Browser: Chrome 105.0.5195.79
Browser engine: Chromium
Context: webapp
Operating system: Android 12.0.0
Device type: desktop
Device pixel ratio: 1.3312500715255737
Logical CPU cores: 8
Approx. device memory: 2 GB
User agent: Mozilla/5.0 (Linux; Android 12; SM-T500) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/105.0.0.0 Safari/537.36
Language setting: en-US
Local storage
Storage quota (approx): 13 gb
Storage usage (approx): 25 mb (0.2%)
Persistant storage: No
Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.
UI effects are disabled in settings.
WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: no
Supports highp precision: yes
Vendor: Qualcomm
Renderer: Adreno (TM) 610
Major performance caveat: no
Maximum texture size: 4096
Point size range: 1 to 1023
Extensions:
EXT_color_buffer_float
EXT_color_buffer_half_float
EXT_float_blend
EXT_texture_filter_anisotropic
EXT_texture_norm16
OES_texture_float_linear
WEBGL_compressed_texture_astc
WEBGL_compressed_texture_etc
WEBGL_compressed_texture_etc1
WEBGL_debug_renderer_info
WEBGL_debug_shaders
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
H.265 (video/mp4; codecs=hev1.1.2.L93.B0)
H.264 (video/mp4; codecs=avc1.42E01E)
Supported encode formats:
WebM VP9 (video/webm; codecs=vp9)
WebM VP8 (video/webm; codecs=vp8)

</details>
