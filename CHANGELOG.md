# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

## 0.10.2
* Add error message on wrong export format.

## 0.10.1
* Fix `.npmignore` support (by Ali Gasymov).

## 0.10
* Add `package.bin` support.

## 0.9
* Add `package.files` support (by Ali Gasymov).

## 0.8.7
* Remove `clean-publish` hack.

## 0.8.6
* Clean `eslintIgnore` from `package.json`.

## 0.8.5
* Remove extra files for React Native.

## 0.8.4
* Allow to React Native without `resolverMainFields` (by @farwayer).
* Fix `index.native.js` support.

## 0.8.3
* Fix React Native `package.json` warnings.

## 0.8.2
* Fix `package.browser` entry.

## 0.8.1
* Clean `package.json` from unnecessary exports.

## 0.8
* Ignore files with ESM export if they have no `index.js` name.

## 0.7
* React Native replacements must have `index.native.js` name.
* Add `index.cjs.js` files as temporary solution for React Native.

## 0.6.1
* Fix auto-generated `package.browser.js` syntax.

## 0.6
* Rename `--without-publish` to `--check`.
* Fix support of `index.browser.js` in subfolders.
* Generate ESM-only files for React Native.

## 0.5.2
* Fix `*.svg`, `*.png`, and `*.css` imports support.

## 0.5.1
* Fix `*.test.js` and `*.spec.js` files support.

## 0.5
* Add default export support.
* Add multiline import support.
* Add renamed import support.
* Remove temporary dir on error.

## 0.4.1
* Use `dual-publish-tmp/` on `--without-publish`.

## 0.4
* Add named exports support.
* Add Conditional Exports support.

## 0.3
* Add `index.browser.js` files support.

## 0.2
* Use `index.js` for ESM.
* Add `.npmignore` support.

## 0.1
* Initial release.
