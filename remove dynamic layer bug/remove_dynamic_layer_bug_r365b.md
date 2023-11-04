## Problem description

When I delete a dynamic layer, errors appear in the console.

Please note that if we display the number of objects in the console, we will see `1`, which indicates that the canvas was not destroyed.

## Attach a .c3p

[remove_dynamic_layer_bug_r365b.zip](https://github.com/WilsonPercival/WilsonPercival/files/13219801/remove_dynamic_layer_bug_r365b.zip)

## Steps to reproduce

1. Open a project.
2. Launch and open the console.
3. Click `1` to create a dynamic layer.
4. Press `2` to create objects on the dynamic layer.
5. Click `3` to delete the dynamic layer. Please note that there are many errors in the console.

## Observed result

<img width="939" alt="observed" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/fb3fc918-3c30-4a61-853b-962244779978">

## Expected result

There should be no errors in the console.

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
