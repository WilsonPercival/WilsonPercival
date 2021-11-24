## Problem description

The app doesn't load after reloading the page. In fact, the app doesn't work at all anymore, even after clearing the cache. 

PLEASE, take this seriously. If the bug happens, users will never be able to access the app again!!!

## Attach a .c3p

Version1.c3p https://drive.google.com/file/d/1rydfscWlpdTuMrGS7dk8V1Ax3Ue6OwCa/view?usp=sharing

Version2.c3p https://drive.google.com/file/d/1lHnC4i4pEfaPXg0JqfLvwPnulbo9D2Ph/view?usp=sharing

## Steps to reproduce

1. Upload the app (version1) to the hosting (HTML5 export)
2. Open the app in any browser. Keep it open
3. Delete the app (version1) and upload the app (version2). It's heavy on purpose to delay "On update ready" event. Wait untill all the files are uploaded.
4. Reload the tab from step 2. 
5. The app will automatically reload 5 seconds after "On update found" event. But before "On update ready" event.
6. The app doesn't load anymore. The black screen.

## Observed result

![a4](https://user-images.githubusercontent.com/91274932/143244492-361ef706-c3e8-47e0-97cc-8d2d9a0c3e34.jpg)

![a1](https://user-images.githubusercontent.com/91274932/143244507-6398f123-b5dd-4845-9188-9acba988d38a.jpg)

![a2](https://user-images.githubusercontent.com/91274932/143244518-395afdac-4b3a-4d6a-a7c3-94ef5fc4308d.jpg)

![a3](https://user-images.githubusercontent.com/91274932/143244530-33635ac1-8dc2-41f9-8d1c-0efa23049f72.jpg)

## Expected result

The app loads as usual.

## More details

1. After updating the project I show users the screen that says, "Please, wait! The new version is loading". On "Update ready" I reload the page and users get a new version.
But I was wondering what if an impatient user updates the page manually before downloading is finished.
I did exactly this and the app crashed.

Moreover, I can't even recover the app after this crash. I delete the cache and cookies, nothing helps. From this point on, there is no way to use this app further.
The only solution is to donwgrade the project on the hosting.

2. I couldn't reproduce the problem on mobile though. Then I increased the size of the update from 25 to 146mb just to be sure. I caught the bug on mobile as well. Now I can't repeat it on mobile.

**Affected browsers/platforms:** Chrome (Windows), Opera (Windows)

**First affected release:** broke in r272-2

## System details

<details><summary>View details</summary>

Platform information
Browser: Chrome
Browser version: 96.0.4664.45
Browser engine: Chromium
Context: browser
Operating system: Windows
Operating system version: 10
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 8
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/96.0.4664.45 Safari/537.36
C3 release: r272.2 (beta)
Language setting: en-US

Local storage
Storage quota (approx): 67 gb
Storage usage (approx): 146 mb (0.2%)
Persistant storage: No

Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.

Nothing is missing. Everything is OK!
WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: yes
Supports highp precision: yes
Vendor: Google Inc. (NVIDIA)
Renderer: ANGLE (NVIDIA, NVIDIA GeForce GTX 1050 Ti Direct3D11 vs_5_0 ps_5_0, D3D11-27.21.14.5671)
Major performance caveat: no
Maximum texture size: 16384
Point size range: 1 to 1024
Extensions:

EXT_color_buffer_float
EXT_color_buffer_half_float
EXT_disjoint_timer_query_webgl2
EXT_float_blend
EXT_texture_compression_bptc
EXT_texture_compression_rgtc
EXT_texture_filter_anisotropic
EXT_texture_norm16
KHR_parallel_shader_compile
OES_texture_float_linear
WEBGL_compressed_texture_s3tc
WEBGL_compressed_texture_s3tc_srgb
WEBGL_debug_renderer_info
WEBGL_debug_shaders
WEBGL_lose_context
WEBGL_multi_draw
OVR_multiview2
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
