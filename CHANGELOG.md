
## v4.0.0-beta.0 (2023-08-09)

#### :boom: Breaking Change
* `ember-truth-helpers`, `test-app`
  * [#147](https://github.com/jmurphyau/ember-truth-helpers/pull/147) Convert to v2 addon ([@ctjhoa](https://github.com/ctjhoa))

#### :rocket: Enhancement
* `ember-truth-helpers`, `modern-test-app`, `test-app`
  * [#176](https://github.com/jmurphyau/ember-truth-helpers/pull/176) Glint Support ([@gossi](https://github.com/gossi))

#### :memo: Documentation
* [#184](https://github.com/jmurphyau/ember-truth-helpers/pull/184) Remove "short-circuit" disclaimer from readme ([@Techn1x](https://github.com/Techn1x))
* [#179](https://github.com/jmurphyau/ember-truth-helpers/pull/179) Update readme ([@SergeAstapov](https://github.com/SergeAstapov))

#### :house: Internal
* `ember-truth-helpers`, `modern-test-app`, `test-app`
  * [#182](https://github.com/jmurphyau/ember-truth-helpers/pull/182) Sync with embroider-addon blueprint ([@SergeAstapov](https://github.com/SergeAstapov))
  * [#177](https://github.com/jmurphyau/ember-truth-helpers/pull/177) switch from yarn to pnpm ([@SergeAstapov](https://github.com/SergeAstapov))
* Other
  * [#180](https://github.com/jmurphyau/ember-truth-helpers/pull/180) Add new workflow to provide release branches ([@SergeAstapov](https://github.com/SergeAstapov))
* `test-app`
  * [#178](https://github.com/jmurphyau/ember-truth-helpers/pull/178) ember-cli-update v3.28.5...v4.12.1 ([@SergeAstapov](https://github.com/SergeAstapov))

#### Committers: 4
- Brad Overton ([@Techn1x](https://github.com/Techn1x))
- Camille TJHOA ([@ctjhoa](https://github.com/ctjhoa))
- Sergey Astapov ([@SergeAstapov](https://github.com/SergeAstapov))
- Thomas Gossmann ([@gossi](https://github.com/gossi))


## v3.1.1 (2022-07-14)

#### :bug: Bug Fix
* [#155](https://github.com/jmurphyau/ember-truth-helpers/pull/155) fix for issues that occured during v3.1.0 ([@jmurphyau](https://github.com/jmurphyau))

#### Committers: 1
- James Murphy ([@jmurphyau](https://github.com/jmurphyau))


## v3.1.0 (2022-07-14)

#### :rocket: Enhancement
* [#134](https://github.com/jmurphyau/ember-truth-helpers/pull/134) Export eq and not-eq directly from /addon ([@nlfurniss](https://github.com/nlfurniss))

#### Committers: 1
- Nathaniel Furniss ([@nlfurniss](https://github.com/nlfurniss))


## v3.0.0 (2020-10-09)

#### :boom: Breaking Change
* [#120](https://github.com/jmurphyau/ember-truth-helpers/pull/120) Drop support for Node < 10; Upgrade ember-cli-babel to v7. ([@nlfurniss](https://github.com/nlfurniss))
* [#89](https://github.com/jmurphyau/ember-truth-helpers/pull/89) Update to ember-cli@3.5 blueprint ([@loganrosen](https://github.com/loganrosen))
* [#91](https://github.com/jmurphyau/ember-truth-helpers/pull/91) Drop Node 4 support ([@rondale-sc](https://github.com/rondale-sc))

#### :rocket: Enhancement
* [#89](https://github.com/jmurphyau/ember-truth-helpers/pull/89) Update to ember-cli@3.5 blueprint ([@loganrosen](https://github.com/loganrosen))

#### :bug: Bug Fix
* [#110](https://github.com/jmurphyau/ember-truth-helpers/pull/110) fix: proper named export ([@lifeart](https://github.com/lifeart))

#### :memo: Documentation
* [#105](https://github.com/jmurphyau/ember-truth-helpers/pull/105) Fix link to isEqual docs from @ember/utils pkg ([@gabrielgrant](https://github.com/gabrielgrant))
* [#94](https://github.com/jmurphyau/ember-truth-helpers/pull/94) Add note about short circuiting ([@danwenzel](https://github.com/danwenzel))

#### :house: Internal
* [#90](https://github.com/jmurphyau/ember-truth-helpers/pull/90) Use template strings intstead of string literals with htmbars-inline-precompile ([@rondale-sc](https://github.com/rondale-sc))

#### Committers: 6
- Alex Kanunnikov ([@lifeart](https://github.com/lifeart))
- Dan Wenzel ([@danwenzel](https://github.com/danwenzel))
- Gabriel Grant ([@gabrielgrant](https://github.com/gabrielgrant))
- Jonathan ([@rondale-sc](https://github.com/rondale-sc))
- Logan Rosen ([@loganrosen](https://github.com/loganrosen))
- Nathaniel Furniss ([@nlfurniss](https://github.com/nlfurniss))


### v2.1.0 (2018-08-20)
- Add `is-empty` helper

### v2.0.0 (2017-10-15)
- Drop support for Node < 4
- Drop support for Ember 1.13
