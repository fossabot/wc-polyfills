## Web Components polyfills

[![Renovate enabled](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)](https://renovatebot.com/)

For browsers with ES2015+ support:
A repackaging of the polyfills from https://github.com/webcomponents
- `customElements`
- `ShadowDOM`

For browsers with ES5 support:
- `Array.from`, `Object.assign`, `customEvent`, `defaultPrevented` from https://github.com/webcomponents/webcomponents-platform/webcomponents-platform.js
- `Promise` from https://github.com/zloirock/core-js
- `URL` and `URLSearchParams` from https://github.com/ungap/url-search-params
- `customElements` as above but ES5 version
- `ShadowDOM` as above but ES5 version

### How to
- Clone the repo
- run `npm install`
- run `node build.js` or `npm run build`
