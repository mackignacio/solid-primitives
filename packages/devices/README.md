---
Name: devices
Stage: 3
Package: "@solid-primitives/devices"
Primitives: createDevices, createMicrophones, createSpeakers, createCameras
Category: Display & Media
---

# @solid-primitives/devices

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg?style=for-the-badge)](https://lerna.js.org/)
[![size](https://img.shields.io/bundlephobia/minzip/@solid-primitives/devices?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/devices)
[![size](https://img.shields.io/npm/v/@solid-primitives/devices?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/devices)

Creates a primitive to get a list of media devices (microphones, speakers, cameras). There are filtered primitives for convenience reasons.

## How to use it

```ts
const devices = createDevices();

const microphones = createMicrophones();
const speakers = createSpeakers();
const cameras = createCameras();
```

The filtered primitives are build so that they only triggered if the devices of their own kind changed.

## Demo

TODO

## Changelog

<details>
<summary><b>Expand Changelog</b></summary>

0.0.100

Initial release loosely adapted from https://github.com/microcipcip/vue-use-kit/blob/master/src/functions/useMediaDevices/useMediaDevices.ts.

1.0.1

Released official version, CJS and updated to Stage 3

</details>
