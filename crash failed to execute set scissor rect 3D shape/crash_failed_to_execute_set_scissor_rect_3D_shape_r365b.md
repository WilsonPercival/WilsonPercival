## Problem description

Construct crashes.

Please note that the `3DShape` has the `AdjustHSL` effect.

## Attach a .c3p

[crash_failed_to_execute_set_scissor_rect_3d_shape_r365b.zip](https://github.com/WilsonPercival/WilsonPercival/files/13273337/crash_failed_to_execute_set_scissor_rect_3d_shape_r365b.zip)

## Steps to reproduce

1. Open a project.
2. Make sure the editor is running on `WebGPU`.
3. Zoom in so that you are inside the cube.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/1f0147b1-df02-4a5c-b062-18dc2da9450c

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r365b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r365/main.js, line 475, col 328
Message: Uncaught TypeError: Failed to execute 'setScissorRect' on 'GPURenderPassEncoder': Value is not of type 'unsigned long'.
Stack: TypeError: Failed to execute 'setScissorRect' on 'GPURenderPassEncoder': Value is not of type 'unsigned long'. at Lka (https://editor.construct.net/r365/main.js:475:328) at xk (https://editor.construct.net/r365/main.js:477:88) at CCG.Dk (https://editor.construct.net/r365/main.js:478:329) at vk.Sb.iOa.hJ (https://editor.construct.net/r365/main.js:2271:352) at ula (https://editor.construct.net/r365/main.js:657:51) at CCG.Uk (https://editor.construct.net/r365/main.js:657:203) at ewa.Sb.DI.SU.ryc.LMa (https://editor.construct.net/r365/main.js:2457:474) at MBa (https://editor.construct.net/r365/projectResources.js:43:128) at d.UGc (https://editor.construct.net/r365/projectResources.js:1427:496) at d.ag (https://editor.construct.net/r365/projectResources.js:1426:425)
Construct version: r365
URL: https://editor.construct.net/r365/
Date: Tue Nov 07 2023 00:41:44 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 13.5 s

Platform information
Product: Construct 3 r365 (beta)
Browser: Chrome 119.0.6045.105
Browser engine: Chromium
Context: browser
Operating system: Windows 11
Device type: desktop
Device pixel ratio: 1.5
Logical CPU cores: 16
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/119.0.0.0 Safari/537.36
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
Adapter features: bgra8unorm-storage, depth-clip-control, depth32float-stencil8, float32-filterable, indirect-first-instance, rg11b10ufloat-renderable, texture-compression-bc

</details>
