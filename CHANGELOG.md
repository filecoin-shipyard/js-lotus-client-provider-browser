## [1.1.0](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/compare/v1.0.5...v1.1.0) (2022-02-14)


### Features

* add support for other content types for http requests ([#14](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/issues/14)) ([d7ee42b](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/d7ee42b1c01b44cab24e76b5dd72d2f6054bce91))

### [1.0.5](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/compare/v1.0.4...v1.0.5) (2022-01-24)


### Bug Fixes

* **ci:** release with Node.js 16, simplify Actions ([f466bda](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/f466bda8c6c2ce040c14e2645f1487a8e77feb70))


### Trivial Changes

* **deps-dev:** bump dual-publish from 2.0.2 to 3.0.0 ([788be64](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/788be6496d584bc07c7ecf53167427de28d00687))
* **no-release:** bump actions/setup-node from 2.4.1 to 2.5.0 ([#11](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/issues/11)) ([fe38a10](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/fe38a10c1004bd448afbdfda7dbb5dc793582e82))
* **no-release:** bump actions/setup-node from 2.5.0 to 2.5.1 ([#12](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/issues/12)) ([89aaeb9](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/89aaeb94bfea3b87577ff8a521c0c5b4171907b8))

### [1.0.4](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/compare/v1.0.3...v1.0.4) (2021-11-04)


### Trivial Changes

* **deps:** bump actions/checkout from 2.3.5 to 2.4.0 ([8a2f291](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/8a2f291c1f74c4ca0ebd681390ecc50c17c2f010))

### [1.0.3](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/compare/v1.0.2...v1.0.3) (2021-10-18)


### Trivial Changes

* **deps:** bump actions/checkout from 2.3.4 to 2.3.5 ([2172c6c](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/2172c6c1f0ab91dd08649183e1a4d7717779a3cc))

### [1.0.2](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/compare/v1.0.1...v1.0.2) (2021-09-28)


### Trivial Changes

* **deps-dev:** bump dual-publish from 1.0.9 to 2.0.0 ([b18cb5f](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/b18cb5f64b2a914d4d16d25eb723dc6367e739b6))
* **deps:** bump actions/setup-node from 2.4.0 to 2.4.1 ([af8b823](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/af8b8239a68210fa7a21d5a0196da6de0ffc2353))

### [1.0.1](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/compare/v1.0.0...v1.0.1) (2021-08-20)


### Bug Fixes

* semantic-release versioning and CHANGELOG commit ([2883800](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/2883800042c1a9420b61cec65c164987347da9eb))

## 1.0.0 (2021-08-20)

### Trivial Changes

* implement semantic-release auto-releasing, and dependabot ([87bdf2e](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/87bdf2e226abd72f1fec57e36bc56d72e8f0b593))
* **docs:** update readme, prep changelog for semantic-release ([03131e2](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/03131e2533d2ed4d0b2f6dcc0ab8112c9ca2a069))

### 0.0.14

* Renamed .import() to .importFile() - SES (Secure ECMAScript) doesn't
  like the method named 'import', presumably because it's the same as
  the JavaScript keyword.
