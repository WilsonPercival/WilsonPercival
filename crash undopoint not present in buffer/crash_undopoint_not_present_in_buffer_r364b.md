## Problem description

Construct crashes.

## Attach a .c3p

[crash_undopoint_not_present_in_buffer_r364b.zip](https://github.com/WilsonPercival/WilsonPercival/files/13196877/crash_undopoint_not_present_in_buffer_r364b.zip)

## Steps to reproduce

1. Open a project.
2. Open `file.txt`.
3. Delete the symbol.
4. Click `Undo`.
5. Open `main.js`.
6. Write the symbol.
7. Open `file.txt`.
8. Close the file.

## Observed result

https://github.com/WilsonPercival/WilsonPercival/assets/91274932/40815d33-83c1-4698-8897-3c5bcaf47fb9

## Expected result

Construct doesn't crash.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r364b

## System details

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r364/projectResources.js, line 1939, col 257
Message: Uncaught Error: Undopoint not present in buffer
Stack: Error: Undopoint not present in buffer at window.Ac.Nf (https://editor.construct.net/r364/projectResources.js:1939:263) at d.ZN (https://editor.construct.net/r364/projectResources.js:1812:363) at window.I0b.td (https://editor.construct.net/r364/components/editors/textEditor/textEditor.js:11:160) at Array. (https://editor.construct.net/r364/components/editors/textEditor/textEditor.js:10:35) at Sf.g.qb.Ova.dispatchEvent (https://editor.construct.net/r364/main.js:1257:42) at Sf.g.qb.Ova.Nf (https://editor.construct.net/r364/main.js:1440:159) at Sf.g.qb.Ova.Nf (https://editor.construct.net/r364/main.js:1446:95) at Sf.g.qb.Ova.Nf (https://editor.construct.net/r364/main.js:1464:332) at Sf.g.qb.Ova.vw (https://editor.construct.net/r364/main.js:1459:497) at Array. (https://editor.construct.net/r364/main.js:1471:41)
Construct version: r364
URL: https://editor.construct.net/r364/
Date: Sun Oct 29 2023 01:57:52 GMT+0300 (Восточная Европа, летнее время)
Uptime: 19.3 s

Platform information
Product: Construct 3 r364 (beta)
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
