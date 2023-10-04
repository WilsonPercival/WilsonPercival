## Problem description

Construct crashes.

## Attach a .c3p

[crash_editor_web_gpu_dxgi_error_device_removed_r361b.zip](https://github.com/WilsonPercival/WilsonPercival/files/12805239/crash_editor_web_gpu_dxgi_error_device_removed_r361b.zip)

## Steps to reproduce

1. Open a project.
2. Make sure the editor is running on `WebGPU`.
3. Run the project.
4. Close the preview tab.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/694727ea-8995-4351-be69-1d4adaede58c

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r361b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled rejection
Reason: Error: D3D12 create command queue failed with DXGI_ERROR_DEVICE_REMOVED (0x887A0005) at CheckHRESULTImpl (..\..\third_party\dawn\src\dawn\native\d3d\D3DError.cpp:94) at Initialize (..\..\third_party\dawn\src\dawn\native\d3d12\DeviceD3D12.cpp:84) at Create (..\..\third_party\dawn\src\dawn\native\d3d12\DeviceD3D12.cpp:69)
Construct version: r361
URL: https://editor.construct.net/r361/
Date: Wed Oct 04 2023 18:09:56 GMT+0300 (Восточная Европа, летнее время)
Uptime: 32.2 s

Platform information
Product: Construct 3 r361 (beta)
Browser: Chrome 117.0.5938.132
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
