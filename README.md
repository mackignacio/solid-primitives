<p align="center">
  <img width="75px" src="https://raw.githubusercontent.com/solidjs/solid-site/dev/src/assets/logo.png" alt="Solid logo">
</p>

# Solid Primitives

A project that strives to develop high-quality, community contributed Solid primitives. All utilities are well tested and continuously maintained. Every contribution to the repository is checked for quality and maintained by the highest degree of excellence. The ultimate goal is to extend Solid's primary and secondary primitives with a set of tertiary primitives.

While Solid Primitives is not a SolidJS Core Team maintained project is managed by members of the SolidJS core and ecosystem members. This separation allows the core library to iterate independently while allowing Solid Primitives to remain in-sync with future plans.

## Philosophy

The goal of Solid Primitives is to wrap client and server side functionality to provide a fully reactive API layer. Ultimately the more rooted our tertiary primitives are, the more they act as foundation within Solid's base ecosystem. With well built and re-used foundations, the smaller (aggregate tree-shaking benefits), more concise (readability) and stable (consistent and managed testing + maintenance) applications can be overall.

## Primitives

<!-- ⛔️ AUTO-GENERATED-CONTENT:START (GENERATE_PRIMITIVES_TABLE)
- Do not remove or modify this section. -->
|Name|Stage|Primitives|Size|NPM|
|----|----|----|----|----|
|<br />*Utilities*<br /><br />|
|[analytics](https://github.com/davedbase/solid-primitives/tree/main/packages/analytics)|0|createAnalytics|||
|[countdown](https://github.com/davedbase/solid-primitives/tree/main/packages/countdown)|3|createCountdown|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/countdown?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/countdown)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/countdown?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/countdown)|
|[debounce](https://github.com/davedbase/solid-primitives/tree/main/packages/debounce)|3|createDebounce|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/debounce?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/debounce)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/debounce?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/debounce)|
|[i18n](https://github.com/davedbase/solid-primitives/tree/main/packages/i18n)|3|createI18nContext<br />useI18n|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/i18n?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/i18n)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/i18n?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/i18n)|
|[share](https://github.com/davedbase/solid-primitives/tree/main/packages/share)|2|createSocialShare|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/share?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/share)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/share?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/share)|
|[throttle](https://github.com/davedbase/solid-primitives/tree/main/packages/throttle)|3|createThrottle|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/throttle?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/throttle)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/throttle?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/throttle)|
|[date-difference](https://github.com/davedbase/solid-primitives/tree/main/packages/date-difference)|2|createDateNow<br />createDateDifference|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/date-difference?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/date-difference)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/date-difference?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/date-difference)|
|<br />*Display & Media*<br /><br />|
|[audio](https://github.com/davedbase/solid-primitives/tree/main/packages/audio)|3|createAudio<br />createAudioPlayer<br />createAudioManager|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/audio?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/audio)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/audio?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/audio)|
|[devices](https://github.com/davedbase/solid-primitives/tree/main/packages/devices)|3|createDevices<br />createMicrophones<br />createSpeakers<br />createCameras|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/devices?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/devices)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/devices?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/devices)|
|[intersection-observer](https://github.com/davedbase/solid-primitives/tree/main/packages/intersection-observer)|3|createIntersectionObserver<br />createViewportObserver<br />createVisibilityObserver|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/intersection-observer?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/intersection-observer)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/intersection-observer?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/intersection-observer)|
|[media](https://github.com/davedbase/solid-primitives/tree/main/packages/media)|2|createMediaQuery|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/media?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/media)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/media?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/media)|
|[raf](https://github.com/davedbase/solid-primitives/tree/main/packages/raf)|2|createRAF|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/raf?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/raf)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/raf?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/raf)|
|[resize-observer](https://github.com/davedbase/solid-primitives/tree/main/packages/resize-observer)|3|createResizeObserver|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/resize-observer?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/resize-observer)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/resize-observer?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/resize-observer)|
|[scroll](https://github.com/davedbase/solid-primitives/tree/main/packages/scroll)|3|createScrollObserver|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/scroll?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/scroll)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/scroll?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/scroll)|
|[stream](https://github.com/davedbase/solid-primitives/tree/main/packages/stream)|3|createStream<br />createAmplitudeStream|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/stream?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/stream)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/stream?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/stream)|
|[tween](https://github.com/davedbase/solid-primitives/tree/main/packages/tween)|3|createTween|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/tween?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/tween)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/tween?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/tween)|
|<br />*Browser APIs*<br /><br />|
|[clipboard](https://github.com/davedbase/solid-primitives/tree/main/packages/clipboard)|3|createClipboard<br />copyToClipboard|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/clipboard?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/clipboard)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/clipboard?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/clipboard)|
|[event-listener](https://github.com/davedbase/solid-primitives/tree/main/packages/event-listener)|3|createEventListener|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/event-listener?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/event-listener)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/event-listener?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/event-listener)|
|[fullscreen](https://github.com/davedbase/solid-primitives/tree/main/packages/fullscreen)|3|createFullscreen|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/fullscreen?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/fullscreen)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/fullscreen?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/fullscreen)|
|[geolocation](https://github.com/davedbase/solid-primitives/tree/main/packages/geolocation)|3|createGeolocation<br />createGeolocationWatcher|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/geolocation?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/geolocation)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/geolocation?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/geolocation)|
|[permission](https://github.com/davedbase/solid-primitives/tree/main/packages/permission)|3|createPermission|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/permission?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/permission)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/permission?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/permission)|
|[storage](https://github.com/davedbase/solid-primitives/tree/main/packages/storage)|3|createStorage<br />createCookieStorage<br />createAsyncStorage<br />createStorageSignal<br />createLocalStorage<br />createSessionStorage|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/storage?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/storage)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/storage?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/storage)|
|[worker](https://github.com/davedbase/solid-primitives/tree/main/packages/worker)|0|createWorker|||
|[mutation-observer](https://github.com/davedbase/solid-primitives/tree/main/packages/mutation-observer)|2|createMutationObserver<br />mutationObserver|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/mutation-observer?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/mutation-observer)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/mutation-observer?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/mutation-observer)|
|<br />*Network*<br /><br />|
|[fetch](https://github.com/davedbase/solid-primitives/tree/main/packages/fetch)|3|createFetch|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/fetch?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/fetch)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/fetch?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/fetch)|
|[graphql](https://github.com/davedbase/solid-primitives/tree/main/packages/graphql)|3|createGraphQLClient|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/graphql?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/graphql)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/graphql?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/graphql)|
|[websocket](https://github.com/davedbase/solid-primitives/tree/main/packages/websocket)|0|createWebsocket|||
|<br />*Misc*<br /><br />|
|[props](https://github.com/davedbase/solid-primitives/tree/main/packages/props)|3|createProps|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/props?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/props)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/props?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/props)|
|[script-loader](https://github.com/davedbase/solid-primitives/tree/main/packages/script-loader)|3|createScriptLoader|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/script-loader?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/script-loader)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/script-loader?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/script-loader)|
|[timer](https://github.com/davedbase/solid-primitives/tree/main/packages/timer)|3|createTimer|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/timer?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/timer)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/timer?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/timer)|
|<br />*Reactivity*<br /><br />|
|[composites](https://github.com/davedbase/solid-primitives/tree/main/packages/composites)|2|createCompositeEffect<br />createCompositeComputed<br />createCompositeMemo<br />createCompositeRenderEffect<br />createModifier|[![SIZE](https://img.shields.io/bundlephobia/minzip/@solid-primitives/composites?style=for-the-badge)](https://bundlephobia.com/package/@solid-primitives/composites)|[![VERSION](https://img.shields.io/npm/v/@solid-primitives/composites?style=for-the-badge)](https://www.npmjs.com/package/@solid-primitives/composites)|

<!-- ⛔️ AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. -->

## Contribution Process

Solid Primitives strives to provide idiomatic Solid principles but also allow room for innovation and experimentation. In a growing community many opinions and patterns merge together to produce a de facto standard. Managing opinions and expectations can be difficult. As a result, in November 2021 Solid Primitives implemented a ratification/approval tracking process roughly modelled on [TC39 Proposal Stage Process](https://tc39.es/process-document/). The following summarizes these stages briefly:

| Stage | Description                 |
| ----- | --------------------------- |
| X     | Deprecated or rejected      |
| 0     | Initial submission          |
| 1     | Demonstrations and examples |
| 2     | General use (experimental)  |
| 3     | Pre-shipping (final effort) |
| 4     | Accepted/shipped            |

Any primitive Stage 0-1 should be used with caution and with the understanding the the design or implementation may change. Beyond Stage 2 we make an effort to mitigate changes. If a primitive reaches Stage 2 it's likely to remain an official package with additional approvements until fully accepted and shipped.

## Design Maxims

Other frameworks have large and extremely well established ecosystems. Notably React which has a vast array of component and hooks. The amount of choice within the ecosystem is great but often these tools are built as one-offs resulting in often un-tested logic or are designed with narrow needs. Over time the less concise these building blocks are the more they tend to repeat themselves. Our goal with Primitives is to bring the community together to contribute, evolve and utilize a powerful centralize primitive foundation.

All our primitives are meant to be consistent and sustain a level of quality. We guarentee that each is created with the utmost care. Our primitivates are:

1. Documented and follow a consistent style guide
2. Be well tested
3. Small, concise and practical as possible
4. A single primitive for a single purpose
5. As few, if none, dependencies as possible
6. SSR safe entries provided
7. Wrap base level Browser APIs
8. Should be progressively improved for future features
9. Be focused on composition vs. isolation of logic
10. Community voice and needs guide roadmap and planning
11. Strong TypeScript support
12. Export support for ESM & CJS
13. Solid performance!

## Compound vs. Isolated Primitives

Each primitive is designed with composition in mind. To align with the goal of being small and concise a major rule to designing our primitives is deciding if the interface for primitives should be: composable or segmented. For this reason every API is intricately studied and considered to be composed (stacked with features) or composed into smaller units.

Designing our primitives in this manner allows for better tree shaking and very layering complexity as needed. Only ship what you have to by picking from existing primitives as your foundational building blocks.

## Lerna CLI Helpers

This package comes with a number of support utilities built with Lerna Scripts.

- `yarn ls updateReadme` - This will update the list of primitives by inspecting individual packages.
- `yarn ls createPrimitive name` - A helper to setup a primitive template package.

## Planned Primitives

### Display & Media

- createDragAndDrop
- createPageVisibilityObserver

### Device

- createBattery
- createAccelerometer
- createGyroscope

### Browser

- createURL
- createHistory
- createLocale
- createUpload (https://github.com/Marvinified/use-file-upload)

### Network

- createNotification
- createPush
- createConnectionObserver

### Inputs

- createGesture (in progress)
- createCompositionObserver (CompositionEvent observer)
- createKeyboard (in progress)
- createForm
- createInput
- createTouch
- createMouse

### Utilities

- createWorker (in progress)
- createQueue
- createDateDifference
- createEffectWhen
