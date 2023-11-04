## Problem description

The `ImageData` that I received from the canvas is upside down. Everything works well in `WebGL`.

## Attach a .c3p

[drawing_canvas_get_image_pixel_data_flipped_web_gpu_bug_r365b.zip](https://github.com/WilsonPercival/WilsonPercival/files/13257679/drawing_canvas_get_image_pixel_data_flipped_web_gpu_bug_r365b.zip)

## Steps to reproduce

1. Open and run the project.

## Observed result

<img width="508" alt="observed" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/ef5213cb-11ac-41da-ab63-c2e17ebdd0b0">

## Expected result

<img width="509" alt="expected" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/fa9bde27-2bd7-4f48-84fb-e22e05905a34">

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r365b

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r365 (beta)
Browser: Chrome 118.0.5993.118
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/118.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 283 gb
Storage usage (approx): 658 mb (0.2%)
Persistant storage: Yes

Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.

Nothing is missing. Everything is OK!
WebGPU information
Renderer: WebGPU
Supports GPU profiling: no
Major performance caveat: no
Maximum texture size: 8192
Adapter vendor: amd
Adapter architecture: gcn-5
Adapter device: (unavailable)
Adapter description: (unavailable)
Adapter features:

bgra8unorm-storage
depth-clip-control
depth32float-stencil8
indirect-first-instance
rg11b10ufloat-renderable
texture-compression-bc
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

WebM AV1 (video/webm; codecs=av1)
WebM VP9 (video/webm; codecs=vp9)
WebM VP8 (video/webm; codecs=vp8)

</details>
