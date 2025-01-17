---
Name: permission
Stage: 3
Package: "@solid-primitives/permission"
Primitives: createPermission
Category: Browser APIs
---

# @solid-primitives/permission

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg?style=for-the-badge)](https://lerna.js.org/)
[![size](https://img.shields.io/bundlephobia/minzip/@solid-primitives/permission?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/permission)
[![size](https://img.shields.io/npm/v/@solid-primitives/permission?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/permission)

Creates a primitive to query user permissions.

## How to use it

```ts
const state: "unknown" | PermissionState = createPermission(descriptor: PermissionDescription | PermissionName);
```

## Demo

TODO

## Changelog

<details>
<summary><b>Expand Changelog</b></summary>

0.0.100

Initial release adapted from https://github.com/microcipcip/vue-use-kit/blob/master/src/functions/useFetch/useFetch.ts.

1.0.1

Minor clean-up and added CJS support.

</details>
