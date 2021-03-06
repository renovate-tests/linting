# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

<a name="2.0.1"></a>
## [2.0.1](https://github.com/researchgate/linting/compare/v2.0.0...v2.0.1) (2018-02-04)




**Note:** Version bump only for package @researchgate/eslint-config-rg-react

<a name="2.0.0"></a>
# [2.0.0](https://github.com/researchgate/linting/compare/v1.0.1...v2.0.0) (2017-12-13)


### Bug Fixes

* **deps:** Add missing peer dependency on eslint ([f2b43d2](https://github.com/researchgate/linting/commit/f2b43d2))
* **lint:** correctly set sourceType in all configs ([ecb126e](https://github.com/researchgate/linting/commit/ecb126e))
* **package:** Ensure latest versions of plugins are required. ([ca5cc3f](https://github.com/researchgate/linting/commit/ca5cc3f))
* **prettier:** Fix conflicting rules check and remove 2 conflicting react rules ([484678c](https://github.com/researchgate/linting/commit/484678c))


### Features

* **jsx:** Require booleans to always be specified ([a6d7a76](https://github.com/researchgate/linting/commit/a6d7a76))
* **react:** Make prop-types rule an error ([4be64d6](https://github.com/researchgate/linting/commit/4be64d6))
* **rules:** Add 3 new react rules: display-name, no-string-refs, require-render-return ([f88c2f6](https://github.com/researchgate/linting/commit/f88c2f6))


### BREAKING CHANGES

* **jsx:** Requires boolean flags in jsx to always specify true explicitely
* **rules:** The 3 new react rules might trigger new linting errors
* **react:** The prop-types rule is now an error. Downgrade to warning in project if necessary.
* **package:** Requires newer versions of peer dependencies.




<a name="1.0.1"></a>
## [1.0.1](https://github.com/researchgate/linting/compare/v1.0.0...v1.0.1) (2017-09-23)


### Bug Fixes

* **prettier:** Require eslint-plugin-prettier >= 2.3.0 for config support ([89150d0](https://github.com/researchgate/linting/commit/89150d0))




<a name="1.0.0"></a>
# [1.0.0](https://github.com/researchgate/linting/compare/v0.3.0...v1.0.0) (2017-09-23)


### Bug Fixes

* **dependencies:** Add correct peerDependencies ([ef1d4ce](https://github.com/researchgate/linting/commit/ef1d4ce))


### BREAKING CHANGES

* **dependencies:** Need to install peerDependencies




<a name="0.3.0"></a>
# [0.3.0](https://github.com/researchgate/linting/compare/v0.2.0...v0.3.0) (2017-09-02)


### Bug Fixes

* **prettier:** Fix eslint configs to not conflict with prettier ([eacbef1](https://github.com/researchgate/linting/commit/eacbef1))




<a name="0.2.0"></a>
# [0.2.0](https://github.com/researchgate/linting/compare/v0.1.1...v0.2.0) (2017-09-02)


### Features

* **eslint-react:** Add commonjs, and shared-node-browser environments ([64654cb](https://github.com/researchgate/linting/commit/64654cb))
* **eslint-react:** Add import/no-nodejs-modules rule ([ab3b2b1](https://github.com/researchgate/linting/commit/ab3b2b1))




<a name="0.1.1"></a>
## [0.1.1](https://github.com/researchgate/linting/compare/v0.1.0...v0.1.1) (2017-09-01)




**Note:** Version bump only for package @researchgate/eslint-config-rg-react

<a name="0.1.0"></a>
# 0.1.0 (2017-09-01)


### Features

* **monorepo:** Initial commit ([7c56318](https://github.com/researchgate/linting/commit/7c56318))
