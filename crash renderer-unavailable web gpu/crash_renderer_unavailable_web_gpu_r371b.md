## Problem description

Construct crashes. I also get this message until I restart the browser:

<img width="389" alt="webgpu" src="https://github.com/WilsonPercival/WilsonPercival/assets/91274932/1b70cc77-aefc-4111-926b-0448f32c5dbe">

## Attach a .c3p

[crash_renderer_unavailable_web_gpu_r371b.zip](https://github.com/WilsonPercival/WilsonPercival/files/13685247/crash_renderer_unavailable_web_gpu_r371b.zip)

## Steps to reproduce

1. Open and run the project.
2. When the screen blinks, close the game.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/8be943bc-e5e2-4be3-891e-81c8ec4440af

## Expected result

Everything works stably.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r371b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: renderer-unavailable (no WebGPU adapter available) @ Error: renderer-unavailable (no WebGPU adapter available) at Fka (https://editor.construct.net/r371/main.js:468:97) at async Gka (https://editor.construct.net/r371/main.js:467:451) at async Hka (https://editor.construct.net/r371/main.js:470:170)
Stack: Error: renderer-unavailable (no WebGPU adapter available) at Fka (https://editor.construct.net/r371/main.js:468:97) at async Gka (https://editor.construct.net/r371/main.js:467:451) at async Hka (https://editor.construct.net/r371/main.js:470:170)
Construct version: r371
URL: https://editor.construct.net/r371/
Date: Fri Dec 15 2023 14:20:29 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 7.4 s

Platform information
Product: Construct 3 r371 (beta)
Browser: Chrome 120.0.6099.109
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Safari/537.36
Language setting: en-US

WebGPU information
Renderer: WebGPU
Supports GPU profiling: no
Major performance caveat: no
Maximum texture size: 8192
Adapter vendor: (unavailable)
Adapter architecture: (unavailable)
Adapter device: (unavailable)
Adapter description: (unavailable)
Adapter type: (unavailable)
Adapter backend: (unavailable)
Adapter features:

</details>
