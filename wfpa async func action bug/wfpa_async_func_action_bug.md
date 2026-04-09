## Problem description

The `Browser: Log in console` action is not executed.

## Attach a .c3p

[wfpa_async_func_action_bug_r178b.zip](https://github.com/user-attachments/files/26583403/wfpa_async_func_action_bug_r178b.zip)

## Steps to reproduce

1. Open the project.
2. Run and open the console.
3. Press `1`.

## Observed result

<img width="748" height="126" alt="observed" src="https://github.com/user-attachments/assets/8bb095c5-fefa-4913-8284-d8fe8d64e5bb" />

## Expected result

<img width="739" height="161" alt="expected" src="https://github.com/user-attachments/assets/e09ecfd4-fc8b-47ee-bcaf-fc067f7c39e4" />

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in `r178b`, because this is the first version that introduced asynchronous functions.

## System details

<details><summary>View details</summary>

Platform information
Product: Construct 3 r480.2 (beta)
Browser: Chrome 146.0.7680.178
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/146.0.0.0 Safari/537.36
Language setting: en-US

Local storage
Storage quota (approx): 10 GB
Storage usage (approx): 450 MB (4.2%)
Persistent storage: Yes

Browser support notes
This list contains missing features that are not required, but could improve performance or user experience if supported.

Nothing is missing. Everything is OK!
WebGPU information
Renderer: WebGPU
Compatibility mode: no
Supports GPU profiling: yes
Major performance caveat: no
Maximum texture size: 16384
Adapter vendor: amd
Adapter architecture: gcn-5
Adapter device: (unavailable)
Adapter description: (unavailable)
Adapter type: (unavailable)
Adapter backend: (unavailable)
Adapter features:

bgra8unorm-storage
clip-distances
core-features-and-limits
depth-clip-control
depth32float-stencil8
dual-source-blending
float32-blendable
float32-filterable
indirect-first-instance
primitive-index
rg11b10ufloat-renderable
shader-f16
subgroups
texture-component-swizzle
texture-compression-bc
texture-compression-bc-sliced-3d
texture-formats-tier1
texture-formats-tier2
timestamp-query
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
MPEG-4 Opus (audio/mp4;codecs=opus)
MPEG-4 AAC (audio/mp4;codecs=mp4a.40.2)
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
MPEG-4 AV1 (video/mp4;codecs=av01.0.00M.08)
MPEG-4 VP9 (video/mp4;codecs=vp9)
MPEG-4 H.265 (video/mp4;codecs=hev1.1.2.L93.B0)
MPEG-4 H.264 (video/mp4;codecs=avc1.420034)

</details>
