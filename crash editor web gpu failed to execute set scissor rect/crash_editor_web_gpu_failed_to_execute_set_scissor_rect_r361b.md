## Problem description

Construct crashes.

## Attach a .c3p

[crash_editor_web_gpu_failed_to_execute_set_scissor_rect_r361b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12859961/crash_editor_web_gpu_failed_to_execute_set_scissor_rect_r361b.zip)

## Steps to reproduce

1. Open a project.
2. Make sure the editor is running in `WebGPU`.
3. Click on the sprite in the right ear.
4. Click the checkbox next to the `Preview` option in the left ear. Please note that the instance must not be in the visible area of the layout editor, otherwise the crash will not occur.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/c8b4232e-be3f-494a-a5d1-8e40576c757a

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r361b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r361/main.js, line 478, col 99
Message: Uncaught TypeError: Failed to execute 'setScissorRect' on 'GPURenderPassEncoder': Value is outside the 'unsigned long' value range.
Stack: TypeError: Failed to execute 'setScissorRect' on 'GPURenderPassEncoder': Value is outside the 'unsigned long' value range. at xk (https://editor.construct.net/r361/main.js:478:99) at CCG.Jk (https://editor.construct.net/r361/main.js:482:383) at pla (https://editor.construct.net/r361/main.js:657:73) at CCG.Uk (https://editor.construct.net/r361/main.js:657:188) at $va.ac.yI.QU.Vpc.CMa (https://editor.construct.net/r361/main.js:2455:290) at FBa (https://editor.construct.net/r361/projectResources.js:42:83) at d.tGc (https://editor.construct.net/r361/projectResources.js:1418:496) at d.ag (https://editor.construct.net/r361/projectResources.js:1417:425) at d.ag (https://editor.construct.net/r361/projectResources.js:1374:320) at dcc (https://editor.construct.net/r361/components/editors/layoutView/layoutView.js:91:331)
Construct version: r361
URL: https://editor.construct.net/r361/
Date: Tue Oct 10 2023 19:54:41 GMT+0300 (Восточная Европа, летнее время)
Uptime: 60.6 s

Platform information
Product: Construct 3 r361 (beta)
Browser: Chrome 117.0.5938.150
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/117.0.0.0 Safari/537.36
Language setting: en-US

WebGPU information
Renderer: WebGPU
Supports GPU profiling: no
Major performance caveat: no
Maximum texture size: 8192
Adapter vendor: amd
Adapter architecture: gcn-5
Adapter device: (unavailable)
Adapter description: (unavailable)
Adapter features: bgra8unorm-storage, depth-clip-control, depth32float-stencil8, indirect-first-instance, rg11b10ufloat-renderable, texture-compression-bc

</details>
