# Changelog

## [5.0.0](https://github.com/MichaelDeBoey/eslint-plugin-markdown/compare/v4.0.1...v5.0.0) (2024-04-02)


### ⚠ BREAKING CHANGES

* drop eslint < 8 & Node.js < 18 ([#238](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/238))
* Switch to flat config ([#232](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/232))
* drop node v8 and v10 ([#203](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/203))

### Features

* add `meta` property ([#233](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/233)) ([eedda96](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/eedda967069a665b800fcf95b985424e50c77df6))
* drop eslint &lt; 8 & Node.js < 18 ([#238](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/238)) ([f14f6a5](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/f14f6a58ffe65cee8c31beb6d8ff8bcc1ae81383))
* drop node v8 and v10 ([#203](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/203)) ([071fa66](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/071fa661875e4bd88a91dcd39eee9276bf3f2b0a))
* Switch to flat config ([#232](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/232)) ([7a27eef](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/7a27eef394dbc06f24b16d926946d60accb2d4c7))


### Bug Fixes

* `message.line` could be `undefined` ([#191](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/191)) ([3a40160](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/3a401606cb2ac4dae6b95720799ed1c611af32d0))
* `overrides` general docs and Atom linter-eslint tips (fixes [#109](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/109)) ([#111](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/111)) ([2a8482e](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/2a8482e8e39da2ab4a1d8aeb7459f26a8377905d))
* Add unicode-bom to unsatisfiable rules (refs [#75](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/75)) ([#84](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/84)) ([e34acc6](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/e34acc60c2867889ba4d16a2deecc2cbd03e351b))
* Allowing eslint-plugin-prettier to work (fixes [#101](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/101)) ([#107](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/107)) ([a2f4492](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/a2f44927bda799a699bea3fbee0bfb8f6dd8ce14))
* Apply base indent to multiple line breaks (fixes [#127](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/127)) ([#128](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/128)) ([5640ea6](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/5640ea65730abab5c9c97d77b5708f3499ec62f3))
* check upper bounds of message line numbers for code blocks ([#247](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/247)) ([00adccb](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/00adccb49ed74e6b6ce43bc221a93d7c6782a83c))
* Don't require message end locations (fixes [#112](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/112)) ([#154](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/154)) ([0311640](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/03116401ae7be0c86b5a48d22aacd94df387a5df))
* Emit correct endLine numbers ([#88](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/88)) ([dff8e9c](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/dff8e9c7f334af8a68a6c8a3671ffc01c3bdafbb))
* Exclude eol-last from output (fixes [#48](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/48)) ([abab043](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/abab043f054e0b7f838615875b579c81d6aa288b))
* Ignore anything after space in code fence's language (fixes [#98](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/98)) ([#99](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/99)) ([a5d0cce](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/a5d0ccec6f14f4808a535c0f06273d1e9892be15))
* Ignore words in info string after syntax (fixes [#166](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/166)) ([#167](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/167)) ([23ac2b9](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/23ac2b95b1c2666baf422c24f5b73607d315a700))
* Indent multiline fixes (fixes [#120](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/120)) ([#124](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/124)) ([fb0b5a3](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/fb0b5a3fc36ad362556cafc49929f49e3b4bc6b0))
* More reliable comment attachment (fixes [#76](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/76)) ([#177](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/177)) ([79be776](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/79be776331cf2bb4db2f265ee6cf7260e90e3d5e))
* npm prepare script on Windows (refs [#166](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/166)) ([#168](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/168)) ([1dd7089](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/1dd70890b92827a5fbd3a86a62c3f2bc30389340))
* overrides pattern for virtual filenames in recommended config ([#169](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/169)) ([f6a3fad](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/f6a3fada43aaeb613aaf9168dfd06a53b9db0ab4))
* Support autofix at the very start of blocks (fixes [#117](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/117)) ([#119](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/119)) ([dc90961](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/dc909618aa8f39e84279f5bdeb4a888d56d919b1))
* Support globals (fixes [#79](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/79)) ([#81](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/81)) ([7c19f8b](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/7c19f8bdd5db610ea4c65208f5a37fea684a8d7b))
* use blocksCache instead of single blocks instance (fixes [#181](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/181)) ([#183](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/183)) ([d23d5f7](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/d23d5f739943d136669aac945ef25528f31cd7db))


### Documentation

* Add --ext flag to usage instructions ([9ec8738](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/9ec87382dc1b2ecbe432c823d0b65bedb227b97b))
* Add JSX to supported syntax list ([bf362d9](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/bf362d986da73e7c1be93a3312828791de4c671d))
* Add license info to source header comments (refs [#31](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/31)) ([6e11976](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/6e11976d6df5c2b5317bc38118237fb5530eebc6))
* Add React example ([#152](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/152)) ([f2d4923](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/f2d4923d3b974a201077574fd6e6e7535152db96))
* Add screenshot to readme ([f029492](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/f029492ad9a3eed767ec7143f7e0a6b4ea67e259))
* Add TypeScript example ([#155](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/155)) ([bf7648f](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/bf7648f0ebdb5ac967059ee83708b46f389aa4a9))
* Add unicode-bom to list of unsatisfiable rules ([#91](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/91)) ([6cfd1f0](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/6cfd1f09baa77955fdbb67d512aacac96f174179))
* Dogfood plugin by linting readme ([#145](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/145)) ([b221391](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/b2213919e3973ebb3788295143c17e14f5fc3f3b))
* Explain use of --ext option in ESLint v7 ([#146](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/146)) ([7423610](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/74236108b5c996b5f73046c2112270c7458cbae9))
* Fix broken contributing guide link ([87727b9](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/87727b92e8f984f218427bdedba3fa8008760b7b))
* Fix broken link to contributing guide ([a21eac1](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/a21eac19d57eee94f3ff28f7362ceee6aac70dd8))
* fix expected errors in react example ([#237](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/237)) ([a758163](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/a758163a05c8ff79fa6a67d907f6a6ae07f55b90))
* improve jsdoc, better for typings ([#182](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/182)) ([1280ac1](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/1280ac1f4998e8ab2030742fe510cc02d200aea2))
* Reference recommended config disabled rules ([#159](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/159)) ([7f26cb9](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/7f26cb9a9d1b3c169f532200d12aee80d41bb3e7))
* Remove Gitter chat link ([e6620e3](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/e6620e37fdc3a2640d088e4ea165442ef0f52907))
* Remove prerelease README notes ([#173](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/173)) ([53dc0e5](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/53dc0e56a86144a8b93b3e220116252058fa3144))
* Revamp documentation for v2 ([#149](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/149)) ([51e48c6](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/51e48c68535964b1fe0f5c949d721baca4e6a1d6))
* Suggest disabling strict in .md files (fixes [#94](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/94)) ([#95](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/95)) ([83f00d0](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/83f00d0c1510f1feb26ca11ba9a37a6c8f9532ba))
* Syntax highlight Markdown ([#116](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/116)) ([2de2490](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/2de2490f6d9dd5073bd9662d7ec6d61ceb13a811))
* update badges ([#202](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/202)) ([87c2b53](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/87c2b536fd80b15e134766d92b90048ae45cbe1f))
* Update license copyright ([af22a03](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/af22a03e8f3c07a12bbb8738b9b286d72477f127))
* Updating CLA link ([#93](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/93)) ([5582fce](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/5582fce79e48e8177b92b7806c0aad63bb1eb9c1))


### Build Related

* Add files list to package.json (fixes [#42](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/42)) ([158b87b](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/158b87b5890c36d28b4242b655413051af0829c2))
* Add Node v6 and v7 to Travis CI ([#56](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/56)) ([0f5593f](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/0f5593f039b5d593de9dd4b4ec8e87ddf54a478c))
* Add Node.js v5 to Travis build (fixes [#28](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/28)) ([230519f](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/230519f7098ff7c618e1a7e43fc9e31946a14bf5))
* Add Travis CI (fixes [#15](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/15)) ([52c5116](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/52c511655737e0560571f2509c523a12493ff935))
* changelog update for 1.0.0 ([902d0f7](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/902d0f77daeef3c7de31193bb83af7653a9ae11b))
* changelog update for 1.0.0-beta.5 ([91b3fa9](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/91b3fa91b51fc94b3989346e9258d4d05b294f14))
* changelog update for 1.0.0-beta.6 ([07d179f](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/07d179f649c8100abf249fe6ca18624e72370281))
* changelog update for 1.0.0-beta.7 ([19f5b5a](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/19f5b5aec5f0fe2e2396bf92a6b035b5800dffd6))
* changelog update for 1.0.0-beta.8 ([8952ac6](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/8952ac6435406d4c011b07bacf74cd3280a09d2f))
* changelog update for 1.0.0-rc.0 ([8bc7c0c](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/8bc7c0c46f377a8238c897fdde310c4e09599aaa))
* changelog update for 1.0.0-rc.1 ([3920041](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/3920041e8814157deeade26eab09c34c99d2e5e8))
* changelog update for 1.0.1 ([7b6f11b](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/7b6f11b088fbd55e0b0597ed0512cb482b65cafc))
* changelog update for 1.0.2 ([caf733a](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/caf733a6bea3eb73314f68cb76026c48c73b07f8))
* changelog update for 2.0.0 ([e2f13a9](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/e2f13a90a949c6a6d17d5472bd4ae70d1c26e9f6))
* changelog update for 2.0.0-alpha.0 ([c0ba401](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/c0ba401315323890ce072507a83ab9b3207aeff7))
* changelog update for 2.0.0-rc.0 ([922a00e](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/922a00e286f548f2810ebe5fb534418ae9ba83a3))
* changelog update for 2.0.0-rc.1 ([e05d6eb](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/e05d6ebdbcd87d0ac57ff037fcfe82cd2b0cca37))
* changelog update for 2.0.0-rc.2 ([15d7aa6](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/15d7aa6cd830f769078b6eb6cf89ef3e6e04548f))
* changelog update for 2.0.1 ([e301eea](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/e301eeac5fb14ea703efb5f73f837c04b18ba68e))
* changelog update for 2.1.0 ([63322a5](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/63322a57c880028313c863dc6e3da2e776c86cdb))
* changelog update for 2.2.0 ([5083d83](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/5083d83cbdf6e44087d7b7bda585f7e63258a1a8))
* changelog update for 2.2.1 ([75e1c03](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/75e1c038b58e23a0ca39e714942ea858d1b6fbb1))
* changelog update for 3.0.0 ([5b184f9](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/5b184f93992c6474bccd2f831a25a67ac68c68e3))
* Dogfood plugin without npm link ([#65](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/65)) ([48122eb](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/48122ebce3f18a15633e83ec7d5d60997b163507))
* Explicitly specify package.json files ([#67](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/67)) ([c5e9d67](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/c5e9d67a3d9e4b833683716e8304afdbb98f8b87))
* Install eslint-release ([#66](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/66)) ([7bd0f6e](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/7bd0f6e1208151b0d86d2d3960d55059ae1f305e))
* Install example test dependencies in Jenkins ([#160](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/160)) ([d94c22f](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/d94c22fa908c5ea93f5ca083438af3b108f440c2))
* Remove Travis ([#140](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/140)) ([f584cc6](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/f584cc6f08f0eeac0e657ae45cbf561764fab696))
* Test against Node v10 ([#96](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/96)) ([3b4ff95](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/3b4ff9573d7af4f89b4099d07c7f5972374c6a88))
* Update Travis config (fixes [#20](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/20)) ([49d6bb1](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/49d6bb1b102003931a6427d4911228d6d318c4f1))
* Upgrade to eslint-release@0.11.1 ([#92](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/92)) ([24070e6](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/24070e6eac02c00428235068088d4285aa28ed01))
* Use eslint-release ([#63](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/63)) ([29f2f05](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/29f2f05d38b25bb3822895afb1954b2ff6855b69))


### Chores

* Add .npmrc to disable creating package-lock.json ([#90](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/90)) ([a1544c2](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/a1544c2faf9c2dcd0d27175e3e593f55976e496b))
* add `.vscode` to `.gitignore` ([#236](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/236)) ([cbb8e3a](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/cbb8e3afc665d314570a9b087c7cef2e97d45860))
* Add jQuery Foundation license ([09bac84](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/09bac847d14ce6d63543bc0cbabb9724283db4b6))
* Add Node 12 to Travis ([#122](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/122)) ([b5bf014](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/b5bf01465252a5d5ae3e1849b99b7d37bcd5a030))
* add node v18 ([#205](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/205)) ([558ae3c](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/558ae3ca2b2b35f7a389aa37389d322dc3d3630c))
* add Node v19 ([#212](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/212)) ([81ff967](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/81ff967a325608e44b7bb467f8359ab620528dac))
* Add npm version and build status badges ([#139](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/139)) ([6f02ef5](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/6f02ef53abc08b5e35b56361f2bd7cbc7ea8e993))
* Add test ensuring config comments do not fall through ([#70](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/70)) ([132ea5b](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/132ea5b9ece41ded6a87e2e3115fce1be8801f83)), closes [#69](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/69)
* Add test for code fences without blank lines ([#72](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/72)) ([249904f](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/249904f01c9f2ce788f1988787575a515e058bbe)), closes [#69](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/69)
* add tests for ESLint 8 ([#195](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/195)) ([2fd5b89](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/2fd5b89a589a5b25677983c0228bd2a27e60ba00))
* add triage action ([#213](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/213)) ([ef7dcdc](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/ef7dcdccfb94ac7e657a6c66998ce8831f3e58fd))
* add yarn.lock and package-lock.json into .gitignore ([#184](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/184)) ([a09a645](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/a09a6452c1031b029efb17fe606cc5f56cfa0d23))
* Automatically install example dependencies ([#164](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/164)) ([d30c50f](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/d30c50f46237af2fdef0a8a21fb547ed8e6c4d80))
* bump setup-node and checkout actions to v4 in release workflow ([#239](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/239)) ([3fd99ad](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/3fd99ad0a3787f2ce28b5eb74f5fc197974b0ede))
* Check for package.json in examples ([#200](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/200)) ([8db0978](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/8db097895222a8b0ac0e85b68728829dc508701f))
* generate provenance statements when release ([#222](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/222)) ([30ae649](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/30ae6492e48328672c10da3a7a5bead850b03b52))
* ignore pnpm-lock.yaml ([#193](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/193)) ([ecae4fe](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/ecae4fe7ee53afeefbb8a2627b6bde38a4e5d297))
* Increase code coverage ([#64](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/64)) ([cc7deea](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/cc7deea2aa707bb137b427778e7cd6da34f1e7f6))
* release 3.0.1 ([#220](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/220)) ([e589949](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/e5899493efe0d802a7bc00073a4948a149ae2830))
* release 4.0.0 ([#224](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/224)) ([3e55f7c](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/3e55f7cce502b239ab0011f8ca84f2af0e2f7664))
* release 4.0.1 ([#242](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/242)) ([bb5c3d4](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/bb5c3d4d9b0283bbb44fd75d1c04a3ec7e789fe1))
* Remove call to lint absent `Makefile.js` ([#129](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/129)) ([d52988f](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/d52988f5efcacb16862c79c1857e9b912cf3ffb0))
* remove unused `@eslint/eslintrc` in test examples ([#234](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/234)) ([4e2e160](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/4e2e160e267b5bce91d2ec2795d6b0f13c7ea62c))
* Replace global comment integration test with unit test (refs [#81](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/81)) ([#85](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/85)) ([47ad3f9](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/47ad3f9d1a5e96945b0544b254b2f7793bf91d1f))
* run CI in Node 14.x ([#158](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/158)) ([fc4d7aa](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/fc4d7aa0612a3fdeeb26fbaf261e94547393ab48))
* run tests in Node.js 21 ([#225](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/225)) ([4d9f36f](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/4d9f36f5c5fd1b5d3b1957913118cd76a92750f2))
* run tests on Node.js v20 ([#215](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/215)) ([f5ce090](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/f5ce090010659cd55e38348083585ab116d9b19a))
* set up release-please ([#219](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/219)) ([311c626](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/311c626ac9f9ec05aa8bc6915e995f0a0c408891))
* standardize npm script names ([#223](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/223)) ([6bdff60](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/6bdff605b1d2793f9b20ec9cbadb5c55dbcb783a))
* Switch to main for primary branch (fixes [#161](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/161)) ([#165](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/165)) ([8f729d3](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/8f729d3f286820da8099aaf2708d54aa9edcc000))
* test all supported ESLint versions ([#196](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/196)) ([3667566](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/36675663b83bf02bcde5b7bd8895f7fd4d0b7451))
* test with `ESLint` instead of `CLIEngine` when available ([#198](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/198)) ([b695396](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/b69539679a2bd4f9dc1b0b52bae68fba85749187))
* Un-disable strict and eol-last in repository ([#71](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/71)) ([3abc569](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/3abc5694bc2403fbb5d618cff163e29e34ca99f6))
* update `devDependencies` ([#197](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/197)) ([8f590fc](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/8f590fc3bc61df4e72a06da3e6bf3264df9eea54))
* update changelog with note that v4.0.0 was not published to npm ([#241](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/241)) ([e80139d](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/e80139da3f8be9179469a015e8345b460537e958))
* Update ESLint config and plugins ([#143](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/143)) ([7eeafb8](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/7eeafb83e446f76bc4581381cd68dacc484b2249))
* update github actions ([#207](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/207)) ([f186730](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/f186730bd7420e251da6469f07f3d873d9259abd))
* Update source headers (fixes [#51](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/51)) ([f97e0c0](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/f97e0c01beb7cc6dad21d828ea80e4fbe55317af))
* Upgrade to eslint-config-eslint@5.0.1 ([#110](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/110)) ([fdacf0c](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/fdacf0c29e4c9267816df0918f1b372fbd8eef32))
* use `actions/setup-node@v2` in CI ([#192](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/192)) ([ffdb245](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/ffdb24573dff0728342e21c44013fa78882352d9))
* Use ES2018 object spread syntax ([#141](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/141)) ([9aa1fdc](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/9aa1fdca62733543d2c26a755ad14dbc02926f27))
* Use GitHub Actions ([#123](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/123)) ([07c9017](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/07c9017551d3a3382126882cf08bc162afcab734))
* use latest `typescript-eslint` in examples ([#235](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/235)) ([313959b](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/313959bcaf1613a60fc60a42c52b78146934eae2))
* use node `v16` ([#199](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/199)) ([e1ddcc5](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/e1ddcc5a274bbb4902b8ac8029928a3b2aff5a51))
* Work around npm behavior changes to fix CI on main ([#206](https://github.com/MichaelDeBoey/eslint-plugin-markdown/issues/206)) ([6570c82](https://github.com/MichaelDeBoey/eslint-plugin-markdown/commit/6570c829155a2ca802195c1efd3623e62ca18f4e))

## [4.0.1](https://github.com/eslint/eslint-plugin-markdown/compare/v4.0.0...v4.0.1) (2024-03-06)


### Chores

* update changelog with note that v4.0.0 was not published to npm ([#241](https://github.com/eslint/eslint-plugin-markdown/issues/241)) ([e80139d](https://github.com/eslint/eslint-plugin-markdown/commit/e80139da3f8be9179469a015e8345b460537e958))

## [4.0.0](https://github.com/eslint/eslint-plugin-markdown/compare/v3.0.1...v4.0.0) (2024-03-01)

⚠️ This release was not published to npm due to technical problems.

### ⚠ BREAKING CHANGES

* drop eslint < 8 & Node.js < 18 ([#238](https://github.com/eslint/eslint-plugin-markdown/issues/238))
* Switch to flat config ([#232](https://github.com/eslint/eslint-plugin-markdown/issues/232))

### Features

* add `meta` property ([#233](https://github.com/eslint/eslint-plugin-markdown/issues/233)) ([eedda96](https://github.com/eslint/eslint-plugin-markdown/commit/eedda967069a665b800fcf95b985424e50c77df6))
* drop eslint &lt; 8 & Node.js < 18 ([#238](https://github.com/eslint/eslint-plugin-markdown/issues/238)) ([f14f6a5](https://github.com/eslint/eslint-plugin-markdown/commit/f14f6a58ffe65cee8c31beb6d8ff8bcc1ae81383))
* Switch to flat config ([#232](https://github.com/eslint/eslint-plugin-markdown/issues/232)) ([7a27eef](https://github.com/eslint/eslint-plugin-markdown/commit/7a27eef394dbc06f24b16d926946d60accb2d4c7))


### Documentation

* fix expected errors in react example ([#237](https://github.com/eslint/eslint-plugin-markdown/issues/237)) ([a758163](https://github.com/eslint/eslint-plugin-markdown/commit/a758163a05c8ff79fa6a67d907f6a6ae07f55b90))


### Chores

* add `.vscode` to `.gitignore` ([#236](https://github.com/eslint/eslint-plugin-markdown/issues/236)) ([cbb8e3a](https://github.com/eslint/eslint-plugin-markdown/commit/cbb8e3afc665d314570a9b087c7cef2e97d45860))
* bump setup-node and checkout actions to v4 in release workflow ([#239](https://github.com/eslint/eslint-plugin-markdown/issues/239)) ([3fd99ad](https://github.com/eslint/eslint-plugin-markdown/commit/3fd99ad0a3787f2ce28b5eb74f5fc197974b0ede))
* remove unused `@eslint/eslintrc` in test examples ([#234](https://github.com/eslint/eslint-plugin-markdown/issues/234)) ([4e2e160](https://github.com/eslint/eslint-plugin-markdown/commit/4e2e160e267b5bce91d2ec2795d6b0f13c7ea62c))
* run tests in Node.js 21 ([#225](https://github.com/eslint/eslint-plugin-markdown/issues/225)) ([4d9f36f](https://github.com/eslint/eslint-plugin-markdown/commit/4d9f36f5c5fd1b5d3b1957913118cd76a92750f2))
* standardize npm script names ([#223](https://github.com/eslint/eslint-plugin-markdown/issues/223)) ([6bdff60](https://github.com/eslint/eslint-plugin-markdown/commit/6bdff605b1d2793f9b20ec9cbadb5c55dbcb783a))
* use latest `typescript-eslint` in examples ([#235](https://github.com/eslint/eslint-plugin-markdown/issues/235)) ([313959b](https://github.com/eslint/eslint-plugin-markdown/commit/313959bcaf1613a60fc60a42c52b78146934eae2))

## [3.0.1](https://github.com/eslint/eslint-plugin-markdown/compare/v3.0.0...v3.0.1) (2023-07-15)


### Chores

* add Node v19 ([#212](https://github.com/eslint/eslint-plugin-markdown/issues/212)) ([81ff967](https://github.com/eslint/eslint-plugin-markdown/commit/81ff967a325608e44b7bb467f8359ab620528dac))
* add triage action ([#213](https://github.com/eslint/eslint-plugin-markdown/issues/213)) ([ef7dcdc](https://github.com/eslint/eslint-plugin-markdown/commit/ef7dcdccfb94ac7e657a6c66998ce8831f3e58fd))
* generate provenance statements when release ([#222](https://github.com/eslint/eslint-plugin-markdown/issues/222)) ([30ae649](https://github.com/eslint/eslint-plugin-markdown/commit/30ae6492e48328672c10da3a7a5bead850b03b52))
* run tests on Node.js v20 ([#215](https://github.com/eslint/eslint-plugin-markdown/issues/215)) ([f5ce090](https://github.com/eslint/eslint-plugin-markdown/commit/f5ce090010659cd55e38348083585ab116d9b19a))
* set up release-please ([#219](https://github.com/eslint/eslint-plugin-markdown/issues/219)) ([311c626](https://github.com/eslint/eslint-plugin-markdown/commit/311c626ac9f9ec05aa8bc6915e995f0a0c408891))

v3.0.0 - July 16, 2022

* [`558ae3c`](https://github.com/eslint/eslint-plugin-markdown/commit/558ae3ca2b2b35f7a389aa37389d322dc3d3630c) chore: add node v18 (#205) (Amaresh  S M)
* [`071fa66`](https://github.com/eslint/eslint-plugin-markdown/commit/071fa661875e4bd88a91dcd39eee9276bf3f2b0a) feat!: drop node v8 and v10 (#203) (Amaresh  S M)
* [`f186730`](https://github.com/eslint/eslint-plugin-markdown/commit/f186730bd7420e251da6469f07f3d873d9259abd) ci: update github actions (#207) (Deepshika S)
* [`6570c82`](https://github.com/eslint/eslint-plugin-markdown/commit/6570c829155a2ca802195c1efd3623e62ca18f4e) ci: Work around npm behavior changes to fix CI on main (#206) (Brandon Mills)
* [`87c2b53`](https://github.com/eslint/eslint-plugin-markdown/commit/87c2b536fd80b15e134766d92b90048ae45cbe1f) docs: update badges (#202) (Milos Djermanovic)
* [`2fd5b89`](https://github.com/eslint/eslint-plugin-markdown/commit/2fd5b89a589a5b25677983c0228bd2a27e60ba00) chore: add tests for ESLint 8 (#195) (Michaël De Boey)
* [`8db0978`](https://github.com/eslint/eslint-plugin-markdown/commit/8db097895222a8b0ac0e85b68728829dc508701f) chore: Check for package.json in examples (#200) (Brandon Mills)
* [`b695396`](https://github.com/eslint/eslint-plugin-markdown/commit/b69539679a2bd4f9dc1b0b52bae68fba85749187) test: test with `ESLint` instead of `CLIEngine` when available (#198) (Michaël De Boey)
* [`e1ddcc5`](https://github.com/eslint/eslint-plugin-markdown/commit/e1ddcc5a274bbb4902b8ac8029928a3b2aff5a51) ci: use node `v16` (#199) (Nitin Kumar)
* [`8f590fc`](https://github.com/eslint/eslint-plugin-markdown/commit/8f590fc3bc61df4e72a06da3e6bf3264df9eea54) chore: update `devDependencies` (#197) (Michaël De Boey)
* [`3667566`](https://github.com/eslint/eslint-plugin-markdown/commit/36675663b83bf02bcde5b7bd8895f7fd4d0b7451) chore: test all supported ESLint versions (#196) (Michaël De Boey)
* [`ecae4fe`](https://github.com/eslint/eslint-plugin-markdown/commit/ecae4fe7ee53afeefbb8a2627b6bde38a4e5d297) Chore: ignore pnpm-lock.yaml (#193) (Nitin Kumar)
* [`ffdb245`](https://github.com/eslint/eslint-plugin-markdown/commit/ffdb24573dff0728342e21c44013fa78882352d9) Chore: use `actions/setup-node@v2` in CI (#192) (Nitin Kumar)

v2.2.1 - September 11, 2021

* [`3a40160`](https://github.com/eslint/eslint-plugin-markdown/commit/3a401606cb2ac4dae6b95720799ed1c611af32d0) Fix: `message.line` could be `undefined` (#191) (JounQin)

v2.2.0 - May 26, 2021

* [`32203f6`](https://github.com/eslint/eslint-plugin-markdown/commit/32203f6ec86ec5e220d18099863d94408f334665) Update: Replace Markdown parser (fixes #125, fixes #186) (#188) (Brandon Mills)

v2.1.0 - April 25, 2021

* [`f1e153b`](https://github.com/eslint/eslint-plugin-markdown/commit/f1e153b8b634af7121e87b505c3c882536f4e3a5) Update: Upgrade remark-parse to v7 (fixes #77, fixes #78) (#175) (Brandon Mills)

v2.0.1 - April 5, 2021

* [`d23d5f7`](https://github.com/eslint/eslint-plugin-markdown/commit/d23d5f739943d136669aac945ef25528f31cd7db) Fix: use blocksCache instead of single blocks instance (fixes #181) (#183) (JounQin)
* [`a09a645`](https://github.com/eslint/eslint-plugin-markdown/commit/a09a6452c1031b029efb17fe606cc5f56cfa0d23) Chore: add yarn.lock and package-lock.json into .gitignore (#184) (JounQin)
* [`1280ac1`](https://github.com/eslint/eslint-plugin-markdown/commit/1280ac1f4998e8ab2030742fe510cc02d200aea2) Docs: improve jsdoc, better for typings (#182) (JounQin)
* [`79be776`](https://github.com/eslint/eslint-plugin-markdown/commit/79be776331cf2bb4db2f265ee6cf7260e90e3d5e) Fix: More reliable comment attachment (fixes #76) (#177) (Brandon Mills)

v2.0.0 - February 14, 2021

* [`53dc0e5`](https://github.com/eslint/eslint-plugin-markdown/commit/53dc0e56a86144a8b93b3e220116252058fa3144) Docs: Remove prerelease README notes (#173) (Brandon Mills)
* [`140adf4`](https://github.com/eslint/eslint-plugin-markdown/commit/140adf42a9e103c5fdce5338b737fa0a7c47d38c) 2.0.0-rc.2 (ESLint Jenkins)
* [`15d7aa6`](https://github.com/eslint/eslint-plugin-markdown/commit/15d7aa6cd830f769078b6eb6cf89ef3e6e04548f) Build: changelog update for 2.0.0-rc.2 (ESLint Jenkins)
* [`f6a3fad`](https://github.com/eslint/eslint-plugin-markdown/commit/f6a3fada43aaeb613aaf9168dfd06a53b9db0ab4) Fix: overrides pattern for virtual filenames in recommended config (#169) (Milos Djermanovic)
* [`390d508`](https://github.com/eslint/eslint-plugin-markdown/commit/390d508607aa6a5b1668633799d8e6b34a853d26) 2.0.0-rc.1 (ESLint Jenkins)
* [`e05d6eb`](https://github.com/eslint/eslint-plugin-markdown/commit/e05d6ebdbcd87d0ac57ff037fcfe82cd2b0cca37) Build: changelog update for 2.0.0-rc.1 (ESLint Jenkins)
* [`1dd7089`](https://github.com/eslint/eslint-plugin-markdown/commit/1dd70890b92827a5fbd3a86a62c3f2bc30389340) Fix: npm prepare script on Windows (refs #166) (#168) (Brandon Mills)
* [`23ac2b9`](https://github.com/eslint/eslint-plugin-markdown/commit/23ac2b95b1c2666baf422c24f5b73607d315a700) Fix: Ignore words in info string after syntax (fixes #166) (#167) (Brandon Mills)
* [`8f729d3`](https://github.com/eslint/eslint-plugin-markdown/commit/8f729d3f286820da8099aaf2708d54aa9edcc000) Chore: Switch to main for primary branch (fixes #161) (#165) (Brandon Mills)
* [`d30c50f`](https://github.com/eslint/eslint-plugin-markdown/commit/d30c50f46237af2fdef0a8a21fb547ed8e6c4d80) Chore: Automatically install example dependencies (#164) (Brandon Mills)
* [`2749b4d`](https://github.com/eslint/eslint-plugin-markdown/commit/2749b4deb8a8f8015721ecb5eb49bec8de2042c4) 2.0.0-rc.0 (ESLint Jenkins)
* [`922a00e`](https://github.com/eslint/eslint-plugin-markdown/commit/922a00e286f548f2810ebe5fb534418ae9ba83a3) Build: changelog update for 2.0.0-rc.0 (ESLint Jenkins)
* [`d94c22f`](https://github.com/eslint/eslint-plugin-markdown/commit/d94c22fa908c5ea93f5ca083438af3b108f440c2) Build: Install example test dependencies in Jenkins (#160) (Brandon Mills)
* [`7f26cb9`](https://github.com/eslint/eslint-plugin-markdown/commit/7f26cb9a9d1b3c169f532200d12aee80d41bb3e7) Docs: Reference recommended config disabled rules (#159) (Brandon Mills)
* [`bf7648f`](https://github.com/eslint/eslint-plugin-markdown/commit/bf7648f0ebdb5ac967059ee83708b46f389aa4a9) Docs: Add TypeScript example (#155) (Brandon Mills)
* [`d80be9e`](https://github.com/eslint/eslint-plugin-markdown/commit/d80be9e0b668c0bf3b2176f0f82b5852d4559b59) New: Add rules to recommended config (#157) (Nikolay Stoynov)
* [`fc4d7aa`](https://github.com/eslint/eslint-plugin-markdown/commit/fc4d7aa0612a3fdeeb26fbaf261e94547393ab48) Chore: run CI in Node 14.x (#158) (Kai Cataldo)
* [`f2d4923`](https://github.com/eslint/eslint-plugin-markdown/commit/f2d4923d3b974a201077574fd6e6e7535152db96) Docs: Add React example (#152) (Brandon Mills)
* [`eb66833`](https://github.com/eslint/eslint-plugin-markdown/commit/eb6683351f72735f52dad5018d4fa0c1b3f0f2a1) New: Add recommended config (fixes #151) (#153) (Brandon Mills)
* [`0311640`](https://github.com/eslint/eslint-plugin-markdown/commit/03116401ae7be0c86b5a48d22aacd94df387a5df) Fix: Don't require message end locations (fixes #112) (#154) (Brandon Mills)
* [`2bc9352`](https://github.com/eslint/eslint-plugin-markdown/commit/2bc93523e006b482a4c57a251c221e7b8711b66b) 2.0.0-alpha.0 (ESLint Jenkins)
* [`c0ba401`](https://github.com/eslint/eslint-plugin-markdown/commit/c0ba401315323890ce072507a83ab9b3207aeff7) Build: changelog update for 2.0.0-alpha.0 (ESLint Jenkins)
* [`51e48c6`](https://github.com/eslint/eslint-plugin-markdown/commit/51e48c68535964b1fe0f5c949d721baca4e6a1d6) Docs: Revamp documentation for v2 (#149) (Brandon Mills)
* [`b221391`](https://github.com/eslint/eslint-plugin-markdown/commit/b2213919e3973ebb3788295143c17e14f5fc3f3b) Docs: Dogfood plugin by linting readme (#145) (Brandon Mills)
* [`7423610`](https://github.com/eslint/eslint-plugin-markdown/commit/74236108b5c996b5f73046c2112270c7458cbae9) Docs: Explain use of --ext option in ESLint v7 (#146) (Brandon Mills)
* [`0d4dbe8`](https://github.com/eslint/eslint-plugin-markdown/commit/0d4dbe8a50852516e14f656007c60e9e7a180b0a) Breaking: Implement new processor API (fixes #138) (#144) (Brandon Mills)
* [`7eeafb8`](https://github.com/eslint/eslint-plugin-markdown/commit/7eeafb83e446f76bc4581381cd68dacc484b2249) Chore: Update ESLint config and plugins (#143) (Brandon Mills)
* [`f483343`](https://github.com/eslint/eslint-plugin-markdown/commit/f4833438fa2c06941f05e994eb1084321ce4cfb3) Breaking: Require ESLint v6 (#142) (Brandon Mills)
* [`9aa1fdc`](https://github.com/eslint/eslint-plugin-markdown/commit/9aa1fdca62733543d2c26a755ad14dbc02926f27) Chore: Use ES2018 object spread syntax (#141) (Brandon Mills)
* [`f584cc6`](https://github.com/eslint/eslint-plugin-markdown/commit/f584cc6f08f0eeac0e657ae45cbf561764fab696) Build: Remove Travis (#140) (Brandon Mills)
* [`35f9a11`](https://github.com/eslint/eslint-plugin-markdown/commit/35f9a11b407078774eef37295ba7ddb95c56f419) Breaking: Drop support for Node.js v6 (refs #138) (#137) (Brandon Mills)
* [`6f02ef5`](https://github.com/eslint/eslint-plugin-markdown/commit/6f02ef53abc08b5e35b56361f2bd7cbc7ea8e993) Chore: Add npm version and build status badges (#139) (Brandon Mills)

v2.0.0-rc.2 - January 30, 2021

* [`f6a3fad`](https://github.com/eslint/eslint-plugin-markdown/commit/f6a3fada43aaeb613aaf9168dfd06a53b9db0ab4) Fix: overrides pattern for virtual filenames in recommended config (#169) (Milos Djermanovic)

v2.0.0-rc.1 - December 20, 2020

* [`1dd7089`](https://github.com/eslint/eslint-plugin-markdown/commit/1dd70890b92827a5fbd3a86a62c3f2bc30389340) Fix: npm prepare script on Windows (refs #166) (#168) (Brandon Mills)
* [`23ac2b9`](https://github.com/eslint/eslint-plugin-markdown/commit/23ac2b95b1c2666baf422c24f5b73607d315a700) Fix: Ignore words in info string after syntax (fixes #166) (#167) (Brandon Mills)
* [`8f729d3`](https://github.com/eslint/eslint-plugin-markdown/commit/8f729d3f286820da8099aaf2708d54aa9edcc000) Chore: Switch to main for primary branch (fixes #161) (#165) (Brandon Mills)
* [`d30c50f`](https://github.com/eslint/eslint-plugin-markdown/commit/d30c50f46237af2fdef0a8a21fb547ed8e6c4d80) Chore: Automatically install example dependencies (#164) (Brandon Mills)

v2.0.0-rc.0 - August 19, 2020

* [`d94c22f`](https://github.com/eslint/eslint-plugin-markdown/commit/d94c22fa908c5ea93f5ca083438af3b108f440c2) Build: Install example test dependencies in Jenkins (#160) (Brandon Mills)
* [`7f26cb9`](https://github.com/eslint/eslint-plugin-markdown/commit/7f26cb9a9d1b3c169f532200d12aee80d41bb3e7) Docs: Reference recommended config disabled rules (#159) (Brandon Mills)
* [`bf7648f`](https://github.com/eslint/eslint-plugin-markdown/commit/bf7648f0ebdb5ac967059ee83708b46f389aa4a9) Docs: Add TypeScript example (#155) (Brandon Mills)
* [`d80be9e`](https://github.com/eslint/eslint-plugin-markdown/commit/d80be9e0b668c0bf3b2176f0f82b5852d4559b59) New: Add rules to recommended config (#157) (Nikolay Stoynov)
* [`fc4d7aa`](https://github.com/eslint/eslint-plugin-markdown/commit/fc4d7aa0612a3fdeeb26fbaf261e94547393ab48) Chore: run CI in Node 14.x (#158) (Kai Cataldo)
* [`f2d4923`](https://github.com/eslint/eslint-plugin-markdown/commit/f2d4923d3b974a201077574fd6e6e7535152db96) Docs: Add React example (#152) (Brandon Mills)
* [`eb66833`](https://github.com/eslint/eslint-plugin-markdown/commit/eb6683351f72735f52dad5018d4fa0c1b3f0f2a1) New: Add recommended config (fixes #151) (#153) (Brandon Mills)
* [`0311640`](https://github.com/eslint/eslint-plugin-markdown/commit/03116401ae7be0c86b5a48d22aacd94df387a5df) Fix: Don't require message end locations (fixes #112) (#154) (Brandon Mills)

v2.0.0-alpha.0 - April 12, 2020

* [`51e48c6`](https://github.com/eslint/eslint-plugin-markdown/commit/51e48c68535964b1fe0f5c949d721baca4e6a1d6) Docs: Revamp documentation for v2 (#149) (Brandon Mills)
* [`b221391`](https://github.com/eslint/eslint-plugin-markdown/commit/b2213919e3973ebb3788295143c17e14f5fc3f3b) Docs: Dogfood plugin by linting readme (#145) (Brandon Mills)
* [`7423610`](https://github.com/eslint/eslint-plugin-markdown/commit/74236108b5c996b5f73046c2112270c7458cbae9) Docs: Explain use of --ext option in ESLint v7 (#146) (Brandon Mills)
* [`0d4dbe8`](https://github.com/eslint/eslint-plugin-markdown/commit/0d4dbe8a50852516e14f656007c60e9e7a180b0a) Breaking: Implement new processor API (fixes #138) (#144) (Brandon Mills)
* [`7eeafb8`](https://github.com/eslint/eslint-plugin-markdown/commit/7eeafb83e446f76bc4581381cd68dacc484b2249) Chore: Update ESLint config and plugins (#143) (Brandon Mills)
* [`f483343`](https://github.com/eslint/eslint-plugin-markdown/commit/f4833438fa2c06941f05e994eb1084321ce4cfb3) Breaking: Require ESLint v6 (#142) (Brandon Mills)
* [`9aa1fdc`](https://github.com/eslint/eslint-plugin-markdown/commit/9aa1fdca62733543d2c26a755ad14dbc02926f27) Chore: Use ES2018 object spread syntax (#141) (Brandon Mills)
* [`f584cc6`](https://github.com/eslint/eslint-plugin-markdown/commit/f584cc6f08f0eeac0e657ae45cbf561764fab696) Build: Remove Travis (#140) (Brandon Mills)
* [`35f9a11`](https://github.com/eslint/eslint-plugin-markdown/commit/35f9a11b407078774eef37295ba7ddb95c56f419) Breaking: Drop support for Node.js v6 (refs #138) (#137) (Brandon Mills)
* [`6f02ef5`](https://github.com/eslint/eslint-plugin-markdown/commit/6f02ef53abc08b5e35b56361f2bd7cbc7ea8e993) Chore: Add npm version and build status badges (#139) (Brandon Mills)

v1.0.2 - February 24, 2020

* [`52e0984`](https://github.com/eslint/eslint-plugin-markdown/commit/52e098483fdf958a8dce96ab66c52b4337d522fe) Upgrade: Update devDeps and change istanbul -> nyc (#130) (Brett Zamir)
* [`d52988f`](https://github.com/eslint/eslint-plugin-markdown/commit/d52988f5efcacb16862c79c1857e9b912cf3ffb0) Chore: Remove call to lint absent `Makefile.js` (#129) (Brett Zamir)
* [`5640ea6`](https://github.com/eslint/eslint-plugin-markdown/commit/5640ea65730abab5c9c97d77b5708f3499ec62f3) Fix: Apply base indent to multiple line breaks (fixes #127) (#128) (Brett Zamir)

v1.0.1 - October 21, 2019

* [`fb0b5a3`](https://github.com/eslint/eslint-plugin-markdown/commit/fb0b5a3fc36ad362556cafc49929f49e3b4bc6b0) Fix: Indent multiline fixes (fixes #120) (#124) (Brandon Mills)
* [`07c9017`](https://github.com/eslint/eslint-plugin-markdown/commit/07c9017551d3a3382126882cf08bc162afcab734) Chore: Use GitHub Actions (#123) (Brandon Mills)
* [`b5bf014`](https://github.com/eslint/eslint-plugin-markdown/commit/b5bf01465252a5d5ae3e1849b99b7d37bcd5a030) Chore: Add Node 12 to Travis (#122) (Brandon Mills)
* [`dc90961`](https://github.com/eslint/eslint-plugin-markdown/commit/dc909618aa8f39e84279f5bdeb4a888d56d919b1) Fix: Support autofix at the very start of blocks (fixes #117) (#119) (Simon Lydell)
* [`2de2490`](https://github.com/eslint/eslint-plugin-markdown/commit/2de2490f6d9dd5073bd9662d7ec6d61ceb13a811) Docs: Syntax highlight Markdown (#116) (Brett Zamir)
* [`fdacf0c`](https://github.com/eslint/eslint-plugin-markdown/commit/fdacf0c29e4c9267816df0918f1b372fbd8eef32) Chore: Upgrade to eslint-config-eslint@5.0.1 (#110) (Brandon Mills)

v1.0.0 - January 2, 2019

* [`2a8482e`](https://github.com/eslint/eslint-plugin-markdown/commit/2a8482e8e39da2ab4a1d8aeb7459f26a8377905d) Fix: `overrides` general docs and Atom linter-eslint tips (fixes #109) (#111) (Brett Zamir)

v1.0.0-rc.1 - November 5, 2018

* a2f4492 Fix: Allowing eslint-plugin-prettier to work (fixes #101) (#107) (simlu)

v1.0.0-rc.0 - October 27, 2018

* 8fe9a0e New: Enable autofix with --fix (fixes #58) (#97) (Bohdan Khodakivskyi)
* a5d0cce Fix: Ignore anything after space in code fence's language (fixes #98) (#99) (Francisco Ryan Tolmasky I)
* 6fd340d Upgrade: eslint-release@1.0.0 (#100) (Teddy Katz)
* dff8e9c Fix: Emit correct endLine numbers (#88) (Paul Murray)
* 83f00d0 Docs: Suggest disabling strict in .md files (fixes #94) (#95) (Brandon Mills)
* 3b4ff95 Build: Test against Node v10 (#96) (Brandon Mills)
* 6777977 Breaking: required node version 6+ (#89) (薛定谔的猫)
* 5582fce Docs: Updating CLA link (#93) (Pablo Nevares)
* 24070e6 Build: Upgrade to eslint-release@0.11.1 (#92) (Brandon Mills)
* 6cfd1f0 Docs: Add unicode-bom to list of unsatisfiable rules (#91) (Brandon Mills)

v1.0.0-beta.8 - April 8, 2018

* a1544c2 Chore: Add .npmrc to disable creating package-lock.json (#90) (Brandon Mills)
* 47ad3f9 Chore: Replace global comment integration test with unit test (refs #81) (#85) (Brandon Mills)
* e34acc6 Fix: Add unicode-bom to unsatisfiable rules (refs #75) (#84) (Brandon Mills)
* 7c19f8b Fix: Support globals (fixes #79) (#81) (Anders D. Johnson)

v1.0.0-beta.7 - July 2, 2017

* f8ba18a New: Custom eslint-skip HTML comment skips blocks (fixes #69) (#73) (Brandon Mills)
* 249904f Chore: Add test for code fences without blank lines (#72) (Brandon Mills)
* 3abc569 Chore: Un-disable strict and eol-last in repository (#71) (Brandon Mills)
* 132ea5b Chore: Add test ensuring config comments do not fall through (#70) (Brandon Mills)

v1.0.0-beta.6 - April 29, 2017

* c5e9d67 Build: Explicitly specify package.json files (#67) (Brandon Mills)

v1.0.0-beta.5 - April 29, 2017

* 7bd0f6e Build: Install eslint-release (#66) (Brandon Mills)
* 48122eb Build: Dogfood plugin without npm link (#65) (Brandon Mills)
* cc7deea Chore: Increase code coverage (#64) (Brandon Mills)
* 29f2f05 Build: Use eslint-release (#63) (Brandon Mills)
* d2f2962 Upgrade: remark (#62) (Titus)
