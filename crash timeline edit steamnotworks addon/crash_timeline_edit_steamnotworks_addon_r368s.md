## Problem description

Construct crashes.

Related reports: https://github.com/Scirra/Construct-bugs/issues/7542

The crash occurs because the project contains a third-party addon. Please note that this crash most likely occurs with any third-party addon.

Third party addon taken from this site: https://www.construct.net/en/make-games/addons/1105/steamworks-webview2

## Attach a .c3p

[crash_timeline_edit_steamnotworks_addon_r368s.zip](https://github.com/WilsonPercival/WilsonPercival/files/13452344/crash_timeline_edit_steamnotworks_addon_r368s.zip)

## Steps to reproduce

1. Open a project.
2. Drag the sprite onto the timeline.
3. Click `Editing mode`.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/bd062d3d-45b3-4f21-ae8d-8b9416849622

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r368s

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r368/main.js, line 1049, col 141
Message: Uncaught TypeError: unexpected type
Stack: TypeError: unexpected type at Q.i (https://editor.construct.net/r368/main.js:1049:147) at d.qL (https://editor.construct.net/r368/projectResources.js:1051:94) at Es.KZb.KPa (https://editor.construct.net/r368/main.js:2603:200) at Array.oHb (https://editor.construct.net/r368/main.js:2602:118) at window.Akb.dispatchEvent (https://editor.construct.net/r368/main.js:1257:42) at window.Akb.Nk (https://editor.construct.net/r368/main.js:2956:422) at d.KU (https://editor.construct.net/r368/projectResources.js:1043:300) at u1.tLc (https://editor.construct.net/r368/components/bars/timelineBar/timelineBar.js:69:66) at Xq.g.J.kk.Ska.azb (https://editor.construct.net/r368/components/bars/timelineBar/timelineBar.js:53:443) at Zh (https://editor.construct.net/r368/main.js:396:253)
Construct version: r368
URL: https://editor.construct.net/
Date: Thu Nov 23 2023 18:43:29 GMT+0200 (Восточная Европа, стандартное время)
Uptime: 20.1 s

Platform information
Product: Construct 3 r368 (stable)
Browser: Chrome 119.0.6045.160
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
