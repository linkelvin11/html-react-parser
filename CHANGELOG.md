# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.9.1](https://github.com/remarkablemark/html-react-parser/compare/v0.9.0...v0.9.1) (2019-07-09)


### Build System

* replace `webpack` with `rollup` in order to optimize bundle ([a04ef27](https://github.com/remarkablemark/html-react-parser/commit/a04ef27))
* **index:** fix rollup error of mixing named and default exports ([230de70](https://github.com/remarkablemark/html-react-parser/commit/230de70))



## [0.9.0](https://github.com/remarkablemark/html-react-parser/compare/v0.8.1...v0.9.0) (2019-07-09)


### Bug Fixes

* **attributes-to-props:** handle attr named after Object properties ([3f857bb](https://github.com/remarkablemark/html-react-parser/commit/3f857bb))


### Build System

* **package:** update `react-property` to 1.0.1 ([26ebef9](https://github.com/remarkablemark/html-react-parser/commit/26ebef9))


### Features

* **attributes-to-props:** check for overloaded boolean values ([1151cfb](https://github.com/remarkablemark/html-react-parser/commit/1151cfb))
* **attributes-to-props:** replace `react-dom` with `react-property` ([d6274b9](https://github.com/remarkablemark/html-react-parser/commit/d6274b9)), closes [#107](https://github.com/remarkablemark/html-react-parser/issues/107)


### Tests

* **attributes-to-props:** improve test names ([17fbdfd](https://github.com/remarkablemark/html-react-parser/commit/17fbdfd))



### [0.8.1](https://github.com/remarkablemark/html-react-parser/compare/v0.8.0...v0.8.1) (2019-07-03)


### Tests

* **html-to-react:** update variable name to fix test ([73237dd](https://github.com/remarkablemark/html-react-parser/commit/73237dd))



## [0.8.0](https://github.com/remarkablemark/html-react-parser/compare/v0.7.1...v0.8.0) (2019-06-24)


### Bug Fixes

* **attributes-to-props:** fix lint error `no-prototype-builtins` ([fa66dfc](https://github.com/remarkablemark/html-react-parser/commit/fa66dfc))


### Build System

* **package:** refactor webpack config and generate sourcemap ([5dd4f07](https://github.com/remarkablemark/html-react-parser/commit/5dd4f07))
* **package:** rename npm script `cover` to `test:cover` ([7d806c8](https://github.com/remarkablemark/html-react-parser/commit/7d806c8))
* **package:** update `html-dom-parser@0.2.2` and devDependencies ([b39ac53](https://github.com/remarkablemark/html-react-parser/commit/b39ac53))
* **package:** update dependencies and devDependencies ([8765ea9](https://github.com/remarkablemark/html-react-parser/commit/8765ea9))
* **package:** update dependency `style-to-object` to 0.2.3 ([c2cc2ec](https://github.com/remarkablemark/html-react-parser/commit/c2cc2ec)), closes [remarkablemark/style-to-object#5](https://github.com/remarkablemark/html-react-parser/issues/5)


### Features

* **dom-to-react:** skip and do not parse <script> content ([1fb5ee2](https://github.com/remarkablemark/html-react-parser/commit/1fb5ee2))


### Tests

* **html-to-react:** add test that verifies `domToReact` is exported ([320c364](https://github.com/remarkablemark/html-react-parser/commit/320c364))
* verify invalid style for `attributesToProps` throws an error ([b97f2e1](https://github.com/remarkablemark/html-react-parser/commit/b97f2e1))



<a name="0.7.1"></a>
## [0.7.1](https://github.com/remarkablemark/html-react-parser/compare/v0.7.0...v0.7.1) (2019-05-27)



<a name="0.7.0"></a>
## [0.7.0](https://github.com/remarkablemark/html-react-parser/compare/v0.6.4...v0.7.0) (2019-04-05)


### Bug Fixes

* **coveralls:** moved dtslint tests to lint folder ([306fceb](https://github.com/remarkablemark/html-react-parser/commit/306fceb))
* **types:** html-dom-parser > html-react-parser ([438b9af](https://github.com/remarkablemark/html-react-parser/commit/438b9af))


### Features

* **types:** add lib/dom-to-react declaration ([27ed8b6](https://github.com/remarkablemark/html-react-parser/commit/27ed8b6))



<a name="0.6.4"></a>
## [0.6.4](https://github.com/remarkablemark/html-react-parser/compare/v0.6.3...v0.6.4) (2019-03-29)


### Bug Fixes

* **dom-to-react:** allow custom keys for replacement ([abf20a2](https://github.com/remarkablemark/html-react-parser/commit/abf20a2))
* **dom-to-react:** fix typos in the test ([4eec53e](https://github.com/remarkablemark/html-react-parser/commit/4eec53e))



<a name="0.6.3"></a>
## [0.6.3](https://github.com/remarkablemark/html-react-parser/compare/v0.6.2...v0.6.3) (2019-03-19)


### Bug Fixes

* **typescript:** test.tsx after dtslint run ([38e6bba](https://github.com/remarkablemark/html-react-parser/commit/38e6bba))



<a name="0.6.2"></a>
## [0.6.2](https://github.com/remarkablemark/html-react-parser/compare/v0.6.1...v0.6.2) (2019-03-07)



<a name="0.6.1"></a>
## [0.6.1](https://github.com/remarkablemark/html-react-parser/compare/v0.6.0...v0.6.1) (2019-01-03)


### Bug Fixes

* **utilities:** allow numbers in custom style names ([5a6600f](https://github.com/remarkablemark/html-react-parser/commit/5a6600f))



<a name="0.6.0"></a>
## [0.6.0](https://github.com/remarkablemark/html-react-parser/compare/v0.5.0...v0.6.0) (2018-12-17)


### Features

* **utilities:** add support for custom styles beginning with "--*" ([2c0a9dc](https://github.com/remarkablemark/html-react-parser/commit/2c0a9dc))



<a name="0.5.0"></a>
## [0.5.0](https://github.com/remarkablemark/html-react-parser/compare/v0.4.7...v0.5.0) (2018-12-16)


### Bug Fixes

* **attributes-to-props:** undo default function parameter ([1017b25](https://github.com/remarkablemark/html-react-parser/commit/1017b25))


### Features

* support custom elements in React 16 ([7b2c5a8](https://github.com/remarkablemark/html-react-parser/commit/7b2c5a8))



<a name="0.4.7"></a>
## [0.4.7](https://github.com/remarkablemark/html-react-parser/compare/v0.4.6...v0.4.7) (2018-09-14)



<a name="0.4.6"></a>
## [0.4.6](https://github.com/remarkablemark/html-react-parser/compare/v0.4.5...v0.4.6) (2018-05-13)


### Bug Fixes

* accidentally left a console ([953e564](https://github.com/remarkablemark/html-react-parser/commit/953e564))
* added test case for viewBox ([261ffb7](https://github.com/remarkablemark/html-react-parser/commit/261ffb7))
* moving svg mock to correct place ([6ffb148](https://github.com/remarkablemark/html-react-parser/commit/6ffb148))
* svg attributes now correctly handled ([94643e1](https://github.com/remarkablemark/html-react-parser/commit/94643e1))



<a name="0.4.5"></a>
## [0.4.5](https://github.com/remarkablemark/html-react-parser/compare/v0.4.4...v0.4.5) (2018-05-09)


### Bug Fixes

* **package:** upgrade style-to-object@0.2.1 ([d065c60](https://github.com/remarkablemark/html-react-parser/commit/d065c60))



<a name="0.4.4"></a>
## [0.4.4](https://github.com/remarkablemark/html-react-parser/compare/v0.4.3...v0.4.4) (2018-05-07)


### Bug Fixes

* **package:** upgrade react-dom-core@0.0.3 ([b4a1c6e](https://github.com/remarkablemark/html-react-parser/commit/b4a1c6e))



<a name="0.4.3"></a>
## [0.4.3](https://github.com/remarkablemark/html-react-parser/compare/v0.4.2...v0.4.3) (2018-03-27)


### Bug Fixes

* **parser:** fix boolean attributes parsing ([e478a44](https://github.com/remarkablemark/html-react-parser/commit/e478a44))
* **parser:** fix case when style is empty string ([fa2a8b4](https://github.com/remarkablemark/html-react-parser/commit/fa2a8b4))



<a name="0.4.2"></a>
## [0.4.2](https://github.com/remarkablemark/html-react-parser/compare/v0.4.1...v0.4.2) (2018-02-20)


### Bug Fixes

* **package:** upgrade html-dom-parser@0.1.3 and devDependencies ([1c236ed](https://github.com/remarkablemark/html-react-parser/commit/1c236ed))
* **release:** do not lint standard-version commit message ([2d35a1f](https://github.com/remarkablemark/html-react-parser/commit/2d35a1f))



<a name="0.4.1"></a>
## [0.4.1](https://github.com/remarkablemark/html-react-parser/compare/v0.4.0...v0.4.1) (2017-11-28)


### Bug Fixes

* **attributes-to-props.js:** Remove unappropriate console logging and remove double quote from tests ([10ff149](https://github.com/remarkablemark/html-react-parser/commit/10ff149))
* **attributes-to-props.js:** Use AST to transform style attributes into an style object ([68cd565](https://github.com/remarkablemark/html-react-parser/commit/68cd565))
* **utilities.js:** Format string to lowercase before converting to camel case and assert the string is a string ([4522666](https://github.com/remarkablemark/html-react-parser/commit/4522666))



## [0.4.0](https://github.com/remarkablemark/html-react-parser/compare/v0.3.6...v0.4.0) - 2017-10-01
### Added
- [react-dom-core](https://github.com/remarkablemark/react-dom-core) to dependencies (closes #43)
  - `react-dom` 16 no longer exposes `lib`, which includes the DOM property configs
  - Upgrade devDependencies of `react` and `react-dom` to 16
  - Update README and examples

## [0.3.6](https://github.com/remarkablemark/html-react-parser/compare/v0.3.5...v0.3.6) - 2017-09-30
### Changed
- Dependencies
  - html-dom-parser@0.1.2
    - Fixes IE9 client parser bug
  - Set react and react-dom versions to `^15.4`
    - Version 16 no longer exposes `HTMLDOMPropertyConfig` and `SVGDOMPropertyConfig`

## [0.3.5](https://github.com/remarkablemark/html-react-parser/compare/v0.3.4...v0.3.5) - 2017-06-26
### Changed
- Dependencies
  - html-dom-parser@0.1.1
    - Fixes IE client parser bug
  - eslint@4.1.1
  - webpack@3.0.0
- Update webpack to enable scope hoisting

## [0.3.4](https://github.com/remarkablemark/html-react-parser/compare/v0.3.3...v0.3.4) - 2017-06-17
### Changed
- Dependencies:
  - html-dom-parser@0.1.0
  - coveralls@2.13.1
  - eslint@4.0.0
  - mocha@3.4.2
  - webpack@2.6.1

### Removed
- Dependencies:
  - jsdomify

## [0.3.3](https://github.com/remarkablemark/html-react-parser/compare/v0.3.2...v0.3.3) - 2017-01-27
### Added
- Created CHANGELOG with details on each version release (#37)

### Changed
- Update examples to load parser from relative `dist/` directory (#36)

### Removed
- Removed unnecessary field "browser" in `package.json` (#36)

## [0.3.2](https://github.com/remarkablemark/html-react-parser/compare/v0.3.1...v0.3.2) - 2017-01-26
### Fixed
- Decode HTML entities by default on node (#34)

## [0.3.1](https://github.com/remarkablemark/html-react-parser/compare/v0.3.0...v0.3.1) - 2017-01-10
### Changed
- Updated README by fixing CDN installation instructions and adding JSFiddle

## [0.3.0](https://github.com/remarkablemark/html-react-parser/compare/v0.2.0...v0.3.0) - 2016-11-18
### Changed
- Upgrade `react` and `react-dom` to >15.4

## [0.2.0](https://github.com/remarkablemark/html-react-parser/compare/v0.1.1...v0.2.0) - 2016-11-18
### Added
- Create npm script `clean` that removes `dist/` directory

### Fixed
- Silence webpack warning by keeping react <15.4 in this version

## [0.1.1](https://github.com/remarkablemark/html-react-parser/compare/v0.1.0...v0.1.1) - 2016-11-17
### Fixed
- `HTMLDOMPropertyConfig.js` and `SVGDOMPropertyConfig.js` have been moved from `react/lib/` to `react-dom/lib/` in v15.4

## [0.1.0](https://github.com/remarkablemark/html-react-parser/compare/v0.0.7...v0.1.0) - 2016-10-14
### Changed
- Replace HTML to DOM converter with [html-dom-parser](https://github.com/remarkablemark/html-dom-parser) (#28)
  - Save `html-dom-parser`
  - Remove `domhandler` and `htmlparser2`
- Update tests and README

## [0.0.7](https://github.com/remarkablemark/html-react-parser/compare/v0.0.6...v0.0.7) - 2016-09-27
### Added
- Examples of using the parser with script tag and RequireJS (#26)

### Changed
- Update build (#25)
- Update README description, instructions, and examples (#27)

## [0.0.6](https://github.com/remarkablemark/html-react-parser/compare/v0.0.5...v0.0.6) - 2016-09-27
### Added
- README example with advanced usage of `replace` option from @poacher2k (#17)
- Contributors section to README (#21)

### Changed
- Use webpack to build UMD bundle (#22)

### Fixed
- Regex bug on client parser (#24)

## [0.0.5](https://github.com/remarkablemark/html-react-parser/compare/v0.0.4...v0.0.5) - 2016-08-30
### Changed
- Remove `key` parameter from `replace` and use `React.cloneElement` (#18)

### Fixed
- Parsing of `<script>` and `<style>` tags (#20)

## [0.0.4](https://github.com/remarkablemark/html-react-parser/compare/v0.0.3...v0.0.4) - 2016-08-29
### Added
- Send coverage report generated by [istanbul](http://gotwarlost.github.io/istanbul/) to [coveralls](https://coveralls.io) (#12)
- Display badges in README (#13, #15)
- Update parser's `replace` option with additional 2nd parameter `key` (#16)

### Fixed
- Void elements (e.g., `<img />`) should not have children (#16)
- Set default `key` parameter for sibling elements due to [keys warning](https://fb.me/react-warning-keys) (#16)

## [0.0.3](https://github.com/remarkablemark/html-react-parser/compare/v0.0.2...v0.0.3) - 2016-08-24
### Added
- Make package [UMD](https://github.com/ForbesLindesay/umd/blob/master/template.js) compatible (#9)
- Throw an error if first argument is not a string (#10)

### Changed
- Differentiate between node and browser environments for parser (#5)

### Fixed
- HTML to DOM conversion on the client (#10)

## [0.0.2](https://github.com/remarkablemark/html-react-parser/compare/v0.0.1...v0.0.2) - 2016-08-23
### Added
- [ESLint](http://eslint.org) as the linter (#2)
- [Travis CI](https://travis-ci.org) (#4)

### Fixed
- `package.json` **peerDependencies** for `react` and `react-dom`

## [0.0.1](https://github.com/remarkablemark/html-react-parser/tree/v0.0.1) - 2016-08-23
### Added
- HTML to React parser which consists of:
  - HTML string to DOM object converter
  - DOM object to React nodes converter
- Tests
- README
