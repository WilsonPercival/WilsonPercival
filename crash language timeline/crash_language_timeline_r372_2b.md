## Problem description

Construct crashes.

## Attach a .c3p

[crash_language_timeline_r372_2b.zip](https://github.com/WilsonPercival/WilsonPercival/files/13753455/crash_language_timeline_r372_2b.zip)

## Steps to reproduce

1. Make sure that the `Language` settings are set to `Українська`, otherwise a failure will not occur.
2. Open the project.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/cad4325b-32de-4eba-80d3-0d711dfa7c2d

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r372-2b

## System details

<details><summary>View details</summary>

Error report information
Type: assertion failure
Message: addon initial-frame is not registered
Stack: Error at pa.c4a (https://editor.construct.net/r372-2/main.js:1121:314) at window.assert (https://editor.construct.net/r372-2/main.js:1036:353) at d.g3 (https://editor.construct.net/r372-2/projectResources.js:1242:149) at d.Fvc (https://editor.construct.net/r372-2/projectResources.js:1242:129) at async d.WEc (https://editor.construct.net/r372-2/projectResources.js:1251:254) at async d.Da (https://editor.construct.net/r372-2/projectResources.js:1250:500) at async d.kRc (https://editor.construct.net/r372-2/projectResources.js:1252:471) at async d.Da (https://editor.construct.net/r372-2/projectResources.js:1229:184) at async d.g9b (https://editor.construct.net/r372-2/projectResources.js:1233:185) at async d.bBb (https://editor.construct.net/r372-2/projectResources.js:1233:300)
Construct version: r372.2
URL: https://editor.construct.net/r372-2/
Date: Fri Dec 22 2023 16:27:49 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 9 s

Platform information
Product: Construct 3 r372.2 (beta)
Browser: Chrome 120.0.6099.111
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Safari/537.36
Language setting: uk-UA

WebGPU information
Renderer: WebGPU
Supports GPU profiling: no
Major performance caveat: no
Maximum texture size: 8192
Adapter vendor: amd
Adapter architecture: gcn-5
Adapter device: (unavailable)
Adapter description: (unavailable)
Adapter type: (unavailable)
Adapter backend: (unavailable)
Adapter features: bgra8unorm-storage, depth-clip-control, depth32float-stencil8, float32-filterable, indirect-first-instance, rg11b10ufloat-renderable, shader-f16, texture-compression-bc

</details>
