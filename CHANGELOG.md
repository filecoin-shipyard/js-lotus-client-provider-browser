## 1.0.0 (2021-08-20)

### Trivial Changes

* implement semantic-release auto-releasing, and dependabot ([87bdf2e](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/87bdf2e226abd72f1fec57e36bc56d72e8f0b593))
* **docs:** update readme, prep changelog for semantic-release ([03131e2](https://github.com/filecoin-shipyard/js-lotus-client-provider-browser/commit/03131e2533d2ed4d0b2f6dcc0ab8112c9ca2a069))

### 0.0.14

* Renamed .import() to .importFile() - SES (Secure ECMAScript) doesn't
  like the method named 'import', presumably because it's the same as
  the JavaScript keyword.
