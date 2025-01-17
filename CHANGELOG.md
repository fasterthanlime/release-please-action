# Changelog

## [2.13.0](https://www.github.com/google-github-actions/release-please-action/compare/v2.12.3...v2.13.0) (2020-12-29)


### Features

* **release-please:** fallback tag check is looser ([#169](https://www.github.com/google-github-actions/release-please-action/issues/169)) ([46292e5](https://www.github.com/google-github-actions/release-please-action/commit/46292e55636f49995766fb1bb9ef1b0aaaf21aa7))

### [2.12.3](https://www.github.com/google-github-actions/release-please-action/compare/v2.12.2...v2.12.3) (2020-12-18)


### Bug Fixes

* **release-please:** stop dynamically loading releasers ([#165](https://www.github.com/google-github-actions/release-please-action/issues/165)) ([4de8d4a](https://www.github.com/google-github-actions/release-please-action/commit/4de8d4ac44ed9d0a8d20386d68169b86b30d798a))

### [2.12.2](https://www.github.com/google-github-actions/release-please-action/compare/v2.12.1...v2.12.2) (2020-12-10)


### Bug Fixes

* **go:** pass release-type ([#160](https://www.github.com/google-github-actions/release-please-action/issues/160)) ([5c5271c](https://www.github.com/google-github-actions/release-please-action/commit/5c5271ce75fb1e7955fddc806b9260163206aa27))

### [2.12.1](https://www.github.com/google-github-actions/release-please-action/compare/v2.12.0...v2.12.1) (2020-12-10)


### Bug Fixes

* **release-please:** map go to alternate tag separator ([#157](https://www.github.com/google-github-actions/release-please-action/issues/157)) ([bdc110f](https://www.github.com/google-github-actions/release-please-action/commit/bdc110f19e7d011ed957f41b21f69b3005d151c1))

## [2.12.0](https://www.github.com/google-github-actions/release-please-action/compare/v2.11.5...v2.12.0) (2020-12-10)


### Features

* allow changelogPath to be specified ([#153](https://www.github.com/google-github-actions/release-please-action/issues/153)) ([10d7619](https://www.github.com/google-github-actions/release-please-action/commit/10d761994342597b3e1d24464a41d28d5d97abe3))

### [2.11.5](https://www.github.com/google-github-actions/release-please-action/compare/v2.11.4...v2.11.5) (2020-12-08)


### Bug Fixes

* **go:** non-gapic/apiary libraries now bump patch ([#150](https://www.github.com/google-github-actions/release-please-action/issues/150)) ([00fefb4](https://www.github.com/google-github-actions/release-please-action/commit/00fefb4ff917a53cb65ed27c14c0586ef9055b37))

### [2.11.4](https://www.github.com/google-github-actions/release-please-action/compare/v2.11.3...v2.11.4) (2020-12-07)


### Bug Fixes

* **go:** first commit sha was not being stored ([b555656](https://www.github.com/google-github-actions/release-please-action/commit/b5556569e8852edb74aadc6aff8bd9315d600689))

### [2.11.3](https://www.github.com/google-github-actions/release-please-action/compare/v2.11.2...v2.11.3) (2020-12-07)


### Bug Fixes

* **go:** filter additional PRs from gapic repo ([#145](https://www.github.com/google-github-actions/release-please-action/issues/145)) ([b02ff3b](https://www.github.com/google-github-actions/release-please-action/commit/b02ff3b568326db3e85a5249ae37e33c39dd4563))

### [2.11.2](https://www.github.com/google-github-actions/release-please-action/compare/v2.11.1...v2.11.2) (2020-12-07)


### Bug Fixes

* **go:** pass monorepoTags when opening PR ([#142](https://www.github.com/google-github-actions/release-please-action/issues/142)) ([3428252](https://www.github.com/google-github-actions/release-please-action/commit/34282521f08daa0962fba0a8d98936286a0b2896))

### [2.11.1](https://www.github.com/google-github-actions/release-please-action/compare/v2.11.0...v2.11.1) (2020-12-07)


### Bug Fixes

* **release-please:** fixed branch detection logic for ruby ([#139](https://www.github.com/google-github-actions/release-please-action/issues/139)) ([cd052f4](https://www.github.com/google-github-actions/release-please-action/commit/cd052f41cb6dce082f59e9edad966004813dcdc5))

## [2.11.0](https://www.github.com/google-github-actions/release-please-action/compare/v2.10.1...v2.11.0) (2020-12-07)


### Features

* **release-please:** upgrade to relese-please with go support ([#133](https://www.github.com/google-github-actions/release-please-action/issues/133)) ([5703b0f](https://www.github.com/google-github-actions/release-please-action/commit/5703b0fdec00d70d4be84f7d1a98b3e5adb738ec))


### Bug Fixes

* do not set PR output, if no PR opened ([#129](https://www.github.com/google-github-actions/release-please-action/issues/129)) ([b0faf1d](https://www.github.com/google-github-actions/release-please-action/commit/b0faf1dd7d65697a12321df74e57458262513d70))

### [2.10.1](https://www.github.com/google-github-actions/release-please-action/compare/v2.10.0...v2.10.1) (2020-12-03)


### Bug Fixes

* fix readme typo ([#125](https://www.github.com/google-github-actions/release-please-action/issues/125)) ([d5b0c35](https://www.github.com/google-github-actions/release-please-action/commit/d5b0c3523e4cae31bc0a75685616e21df3197a90))
* **release-please:** fix for merge commits ([#126](https://www.github.com/google-github-actions/release-please-action/issues/126)) ([35f9456](https://www.github.com/google-github-actions/release-please-action/commit/35f94566f5857aafe9fdaad7b2e7df122aac5a92))

## [2.10.0](https://www.github.com/google-github-actions/release-please-action/compare/v2.9.3...v2.10.0) (2020-12-01)


### Features

* **deps:** latest version of release-please ([#122](https://www.github.com/google-github-actions/release-please-action/issues/122)) ([5469575](https://www.github.com/google-github-actions/release-please-action/commit/54695753296b6274758664da88a333e49528635a))

### [2.9.3](https://www.github.com/google-github-actions/release-please-action/compare/v2.9.2...v2.9.3) (2020-11-25)


### Bug Fixes

* **release-please:** don't add labels from fork ([13bffc3](https://www.github.com/google-github-actions/release-please-action/commit/13bffc3e974a8edf5d4830257a17d40e9cb9a32f))

### [2.9.2](https://www.github.com/google-github-actions/release-please-action/compare/v2.9.1...v2.9.2) (2020-11-25)


### Bug Fixes

* parse false value for clean ([fc5b3e5](https://www.github.com/google-github-actions/release-please-action/commit/fc5b3e5c11baace865aed65127f107a4d8b392da))

### [2.9.1](https://www.github.com/google-github-actions/release-please-action/compare/v2.9.0...v2.9.1) (2020-11-25)


### Bug Fixes

* **build:** attempt to ignore errors ([15d0718](https://www.github.com/google-github-actions/release-please-action/commit/15d0718b84b06b34d9125a5d7e97b38888480f99))

## [2.9.0](https://www.github.com/google-github-actions/release-please-action/compare/v2.8.2...v2.9.0) (2020-11-25)


### Features

* pass monorepoTags and packageName when creating GitHub release ([#112](https://www.github.com/google-github-actions/release-please-action/issues/112)) ([69af5fc](https://www.github.com/google-github-actions/release-please-action/commit/69af5fc7d9bb0977586102a0e1488abab7fdaace))


### Bug Fixes

* **build:** add message to tag ([b467439](https://www.github.com/google-github-actions/release-please-action/commit/b46743913ea2c717e2a144864cd026c3f2df4029))

### [2.8.2](https://www.github.com/google-github-actions/release-please-action/compare/v2.8.1...v2.8.2) (2020-11-25)


### Bug Fixes

* **build:** configure git checkout step ([ff5dfe1](https://www.github.com/google-github-actions/release-please-action/commit/ff5dfe1653289b33b5fb3e5de72e0b3733ff390d))
* **build:** run latest dist ([799e6de](https://www.github.com/google-github-actions/release-please-action/commit/799e6de570879ef6ad3d7067295b3e0c2c837e04))

### [2.8.1](https://www.github.com/google-github-actions/release-please-action/compare/v2.8.0...v2.8.1) (2020-11-25)


### Bug Fixes

* **build:** working on version of build that tags major/minor release line ([d4814fe](https://www.github.com/google-github-actions/release-please-action/commit/d4814feca529141f25d8c871b3c2d093b38c14c8))

## [2.8.0](https://www.github.com/google-github-actions/release-please-action/compare/v2.7.0...v2.8.0) (2020-11-25)


### Features

* add additional outputs ([#106](https://www.github.com/google-github-actions/release-please-action/issues/106)) ([c0f7d24](https://www.github.com/google-github-actions/release-please-action/commit/c0f7d24cd04488b7e14836d90143850b97aefadd))

## [2.7.0](https://www.github.com/google-github-actions/release-please-action/compare/v2.6.0...v2.7.0) (2020-11-19)


### Features

* **deps:** upgrade to release-please 6.9.0 ([#100](https://www.github.com/google-github-actions/release-please-action/issues/100)) ([40aba5e](https://www.github.com/google-github-actions/release-please-action/commit/40aba5e11684d69de9f36e60e19de0c5aa28750b))

## [2.6.0](https://www.github.com/google-github-actions/release-please-action/compare/v2.5.7...v2.6.0) (2020-11-08)


### Features

* **deps:** upgrade to release-please 6.7.0 ([#95](https://www.github.com/google-github-actions/release-please-action/issues/95)) ([6461ef3](https://www.github.com/google-github-actions/release-please-action/commit/6461ef332678b2989b09860f8d6b0652cd7a8432))

### [2.5.7](https://www.github.com/google-github-actions/release-please-action/compare/v2.5.6...v2.5.7) (2020-10-29)


### Bug Fixes

* **ruby:** properly support ruby release process ([#92](https://www.github.com/google-github-actions/release-please-action/issues/92)) ([6c289af](https://www.github.com/google-github-actions/release-please-action/commit/6c289af7b611b6019c67c2285397d905380962ac))

### [2.5.6](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.5.5...v2.5.6) (2020-10-15)


### Bug Fixes

* **release-please:** fallback to tag ([#89](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/89)) ([c6f1cd6](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/c6f1cd680fabd9729dc13f6bde59ed5160acb9a3))

### [2.5.5](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.5.4...v2.5.5) (2020-10-10)


### Bug Fixes

* **docs:** document functional version of release-please ([0ab3b32](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/0ab3b3257c9f07aa7e7f2ef5b843556b277b53f5))

### [2.5.4](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.5.3...v2.5.4) (2020-10-10)


### Bug Fixes

* **release-please:** last release had undefined ordering behavior ([a4b349d](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/a4b349d8a8462722f0d1c246581650a4788b76ee))

### [2.5.3](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.5.2...v2.5.3) (2020-10-09)


### Bug Fixes

* **docs:** indicate correct version ([#84](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/84)) ([b632af4](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/b632af41016a545a6e7ee6ecd9b9325538c88e28))

### [2.5.2](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.5.1...v2.5.2) (2020-10-09)


### Bug Fixes

* **release-please:** sort commits ([#82](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/82)) ([846f33a](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/846f33aee4836826ed78a893aa7c1bbd46da6bd4))

### [2.5.1](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.5.0...v2.5.1) (2020-10-08)


### Bug Fixes

* **build:** use new release strategy ([646de90](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/646de90a87173de7b76c7d83807348c2b05b3e43))

## [2.5.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.4.2...v2.5.0) (2020-10-08)


### Features

* **deps:** release-please with support for alternate release branches ([#79](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/79)) ([dfe6b62](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/dfe6b622584ce774821ae93012eda87a2ad9d8a5))


### Bug Fixes

* **build:** revert build to non-debug form ([e6f39a1](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/e6f39a1ff2137720a77acef0b92a813658920fa4))

### [2.4.2](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.4.1...v2.4.2) (2020-10-01)


### Bug Fixes

* **deps:** bump @actions/core from 1.2.4 to 1.2.6 ([#76](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/76)) ([fa86b83](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/fa86b83b5666ef0319c5508ded6b43af2cdf317b))

### [2.4.1](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.4.0...v2.4.1) (2020-09-17)


### Bug Fixes

* **build:** document working version of release-please ([60ae28e](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/60ae28e4b20929fc93a249186726c13098fd6019))

## [2.4.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.3.0...v2.4.0) (2020-09-17)


### Features

* allow github-release/release-pr to be run separately ([#70](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/70)) ([37d423f](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/37d423feba66be7be541aa122419aee5b50fdf98))


### Bug Fixes

* default changelog sections to undefined ([31e1a25](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/31e1a25ccf4f8df92fdb4066e3650a6167e5fe25))
* **build:** release from fork ([f2bda04](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/f2bda04bb55ac6fdaf5e3673a78323966a3768b5))

## [2.3.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.2.0...v2.3.0) (2020-09-17)


### Features

* **release-please:** now supports large files; introduces fork option ([#67](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/67)) ([e7d31db](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/e7d31db9262f11895e7938b84f049e2d6a31be4f))

## [2.2.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.1.1...v2.2.0) (2020-09-10)


### Features

*  Add a changelog section type ([#64](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/64)) ([2ca6d30](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/2ca6d30396e3b6b10ca9623ecbc3174b476ec8a2))


### Bug Fixes

* **release-please:** release please with code-suggester bug fixes ([#66](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/66)) ([6b79987](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/6b79987e9000e7617d81e9645c8394f27b396a8d))

### [2.1.1](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.1.0...v2.1.1) (2020-09-06)


### Bug Fixes

* do not try to fork ([#62](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/62)) ([139a5ef](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/139a5efd7c7e8161ddaa5d5f0f3a80be2e2af96a))

## [2.1.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v2.0.0...v2.1.0) (2020-09-05)


### Features

* **build:** document and update to 2.x ([#59](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/59)) ([512c940](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/512c940c3aa1d2569b540b05472636550d772946))


### Bug Fixes

* hot fix for permission issues in code suggester ([#61](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/61)) ([1b9bcd5](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/1b9bcd506ca8e69c807f51b7be7433c2b2b6bc96))

## [2.0.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.6.3...v2.0.0) (2020-09-04)


### ⚠ BREAKING CHANGES

* moves to code-suggester for PR management (#57)

### Features

* moves to code-suggester for PR management ([#57](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/57)) ([1875a0a](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/1875a0accd4910cdeed87ee0d05c376f71b9d155))

### [1.6.3](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.6.2...v1.6.3) (2020-08-02)


### Bug Fixes

* path was sometimes empty string ([37d7741](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/37d774119e97ee91ab924fc3e30902a38a64c6bb))

### [1.6.2](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.6.1...v1.6.2) (2020-08-02)


### Bug Fixes

* falsy path should be passed as undefined ([#54](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/54)) ([21233d3](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/21233d3c9f239105feab8f1df3e5fb013c1bd7f8))

### [1.6.1](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.6.0...v1.6.1) (2020-07-28)


### Bug Fixes

* add missing  path and  monorepo-tags options ([#52](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/52)) ([41fbc62](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/41fbc62bb12a4b0ff33a3ae5f401acc3d1bf3b7f))

## [1.6.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.5.0...v1.6.0) (2020-07-27)


### Features

* adds support for releases from alternate paths ([#50](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/50)) ([6fc9b14](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/6fc9b14e82521ecefd65c6b7f6b4f32561ce35f6))


### Bug Fixes

* run tests on release PRs ([#47](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/47)) ([b4c1bd2](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/b4c1bd25c7ff2d17dcdd9a91d018dc7058c654a8))

## [1.5.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.4.0...v1.5.0) (2020-07-23)


### Features

* **release-please:** auth gets; stop skipping all ci/cd ([#45](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/45)) ([367f112](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/367f112c21cbef9eef1ec197173f276b42b2fcbf))

## [1.4.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.3.2...v1.4.0) (2020-07-23)


### Features

* output tag name and upload url ([#43](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/43)) ([90469b0](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/90469b02b471d8f7cba6c353b4c1ec1bab5bcde4))

### [1.3.2](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.3.1...v1.3.2) (2020-06-17)


### Bug Fixes

* **build:** switch to GITHUB_TOKEN ([#38](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/38)) ([188d363](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/188d36320b0644bc436b701963d78be6386fe2c3))

### [1.3.1](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.3.0...v1.3.1) (2020-06-17)


### Bug Fixes

* **build:** update to match new default branch ([#36](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/36)) ([1188197](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/1188197913717dd90bc1d79e1139269f427411e9))

## [1.3.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.2.2...v1.3.0) (2020-06-17)


### Features

* **release-please:** configurable default branch; package-lock.json now updated ([#34](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/34)) ([a4607bd](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/a4607bde22b13d1ff7f153625f6e9c84ddf20a41))


### Bug Fixes

* **docs:** update docs to GoogleCloudPlatform ([#31](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/31)) ([4f72a02](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/4f72a02b61bc06a7607189ce5eea318ac382d242))

### [1.2.2](https://www.github.com/bcoe/release-please-action/compare/v1.2.1...v1.2.2) (2020-06-11)


### Bug Fixes

* **deps:** depend on release-please ^5.2.1 to support merge commits  ([#28](https://www.github.com/bcoe/release-please-action/issues/28)) ([5c2e7c4](https://www.github.com/bcoe/release-please-action/commit/5c2e7c41fc2a838bdd1c4319f18385e4784b020f))

### [1.2.1](https://www.github.com/bcoe/release-please-action/compare/v1.2.0...v1.2.1) (2020-05-21)


### Bug Fixes

* use the static build helper ([6872559](https://www.github.com/bcoe/release-please-action/commit/687255987d0e25878a9d56fd69de09c232bbcea3))

## [1.2.0](https://www.github.com/bcoe/release-please-action/compare/v1.1.0...v1.2.0) (2020-05-21)


### Features

* output whether or not a release was created ([#24](https://www.github.com/bcoe/release-please-action/issues/24)) ([b80ca61](https://www.github.com/bcoe/release-please-action/commit/b80ca61e2612c87bad38d85451c7f696a040bdc8))

## [1.1.0](https://www.github.com/bcoe/release-please-action/compare/v1.0.1...v1.1.0) (2020-05-20)


### Features

* Add `bump-minor-pre-major` option ([#9](https://www.github.com/bcoe/release-please-action/issues/9)) ([788c495](https://www.github.com/bcoe/release-please-action/commit/788c495e2607702ce5ab41e9e246161d07fe8854))

### [1.0.1](https://www.github.com/bcoe/release-please-action/compare/v1.0.0...v1.0.1) (2020-05-09)


### Bug Fixes

* pass token to create release ([3ad91fa](https://www.github.com/bcoe/release-please-action/commit/3ad91fa6cb8cf2c05464672da14cbea65555e5a2))

## 1.0.0 (2020-05-09)


### ⚠ BREAKING CHANGES

* initial implementation of logic for running release please

### Features

* handle creating releases ([#3](https://www.github.com/bcoe/release-please-action/issues/3)) ([e72afe0](https://www.github.com/bcoe/release-please-action/commit/e72afe059a2eae50d319b3a4cee2a31479886fe8))
* initial implementation of logic for running release please ([196390b](https://www.github.com/bcoe/release-please-action/commit/196390b8667a14c2ab16f53ba086c11afee28327))
