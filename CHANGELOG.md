# Changelog

## 1.0.0 (2021-02-16)


### Features

* Added DialContext to Client and proxy package ([#483](https://www.github.com/renovate-bot/cloudsql-proxy/issues/483)) ([c84aa50](https://www.github.com/renovate-bot/cloudsql-proxy/commit/c84aa5079668e07e3d2dc8f254d30e1103a6ead3))
* **containers:** Add "-alpine" and "-buster" based images.  ([#415](https://www.github.com/renovate-bot/cloudsql-proxy/issues/415)) ([ebcf294](https://www.github.com/renovate-bot/cloudsql-proxy/commit/ebcf294b9ee028340695868fb6f4cc4bbe09d849))
* **containers:** Add fuse to alpine and buster images ([#459](https://www.github.com/renovate-bot/cloudsql-proxy/issues/459)) ([0f28fcd](https://www.github.com/renovate-bot/cloudsql-proxy/commit/0f28fcd008a5bb863ec2ca1402c31ae81d7dae5d))
* use regionalized instance ids to prevent global conflicts with sqladmin v1 ([#504](https://www.github.com/renovate-bot/cloudsql-proxy/issues/504)) ([6c45513](https://www.github.com/renovate-bot/cloudsql-proxy/commit/6c455136a24b841dbfc015a1f8ed7505f9e77dec))


### Bug Fixes

* Add socket suffix for Postgres instances when running in `-fuse` mode ([#426](https://www.github.com/renovate-bot/cloudsql-proxy/issues/426)) ([20ffaec](https://www.github.com/renovate-bot/cloudsql-proxy/commit/20ffaec2f0f00a2516206a0453bd0d1c6e62770c))
* **containers:** Allow non-root users to mount fuse filesystems for alpine and buster images ([#540](https://www.github.com/renovate-bot/cloudsql-proxy/issues/540)) ([5b653f5](https://www.github.com/renovate-bot/cloudsql-proxy/commit/5b653f5df6d9c4c226e3c4f6036d5e7d4c43c699))
* **container:** Specify nonroot user by uid to work with runAsNonRoot ([#402](https://www.github.com/renovate-bot/cloudsql-proxy/issues/402)) ([c5c0be1](https://www.github.com/renovate-bot/cloudsql-proxy/commit/c5c0be1b60bfc1c3fa862039619908a328066e5e))
* **docs:** Update helm chart URL ([#411](https://www.github.com/renovate-bot/cloudsql-proxy/issues/411)) ([60bab64](https://www.github.com/renovate-bot/cloudsql-proxy/commit/60bab6481d784761d0b8c36a0ee8b6d53db250f9))
* Ensure necessary fields are 64-bit aligned ([#550](https://www.github.com/renovate-bot/cloudsql-proxy/issues/550)) ([4575c8f](https://www.github.com/renovate-bot/cloudsql-proxy/commit/4575c8f8cb496ac3069208e446c47fb6c6acb868))
* **examples/k8s:** Make secret keys consistent ([#405](https://www.github.com/renovate-bot/cloudsql-proxy/issues/405)) ([54573d5](https://www.github.com/renovate-bot/cloudsql-proxy/commit/54573d521428a322f8049b117854987830fa082a))
* **examples:** Remove sidecar from no-proxy example. ([#410](https://www.github.com/renovate-bot/cloudsql-proxy/issues/410)) ([5f761d7](https://www.github.com/renovate-bot/cloudsql-proxy/commit/5f761d7ef539bfe4fb65c6856d439496cddbfcc7))
* improve logging for file descriptor limits ([#609](https://www.github.com/renovate-bot/cloudsql-proxy/issues/609)) ([b42b681](https://www.github.com/renovate-bot/cloudsql-proxy/commit/b42b68134543fbee7da4fbb9a8d667fd9153bec2)), closes [#413](https://www.github.com/renovate-bot/cloudsql-proxy/issues/413)
* only allow fuse mode to unmount if an error occurs first ([#537](https://www.github.com/renovate-bot/cloudsql-proxy/issues/537)) ([6caef36](https://www.github.com/renovate-bot/cloudsql-proxy/commit/6caef36968d23b931c824450e418e29ac6277191))
* Prevent the binary from getting checked in when using go build ([#376](https://www.github.com/renovate-bot/cloudsql-proxy/issues/376)) ([886d9fc](https://www.github.com/renovate-bot/cloudsql-proxy/commit/886d9fc2a60744cc484a194a185260450765935e))
* refreshCfg no longer caches error over valid cert ([#521](https://www.github.com/renovate-bot/cloudsql-proxy/issues/521)) ([4a6b3d8](https://www.github.com/renovate-bot/cloudsql-proxy/commit/4a6b3d8c895e2634afd8cee2341db668f20b9a33))
* Remove incorrect api base url from the host flag. ([#354](https://www.github.com/renovate-bot/cloudsql-proxy/issues/354)) ([887a30e](https://www.github.com/renovate-bot/cloudsql-proxy/commit/887a30e53f599db6cec6a781fd99960d76cc0ae0))

### [1.19.1](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/compare/v1.19.0...v1.19.1) (2020-12-02)


### Bug Fixes

* Ensure necessary fields are 64-bit aligned ([#550](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/issues/550)) ([4575c8f](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/commit/4575c8f8cb496ac3069208e446c47fb6c6acb868))

## [1.19.0](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/compare/v1.18.0...v1.19.0) (2020-11-18)


### Features

* Added DialContext to Client and proxy package ([#483](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/issues/483)) ([c84aa50](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/commit/c84aa5079668e07e3d2dc8f254d30e1103a6ead3))
* use regionalized instance ids to prevent global conflicts with sqladmin v1 ([#504](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/issues/504)) ([6c45513](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/commit/6c455136a24b841dbfc015a1f8ed7505f9e77dec))


### Bug Fixes

* **containers:** Allow non-root users to mount fuse filesystems for alpine and buster images ([#540](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/issues/540)) ([5b653f5](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/commit/5b653f5df6d9c4c226e3c4f6036d5e7d4c43c699))
* only allow fuse mode to unmount if an error occurs first ([#537](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/issues/537)) ([6caef36](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/commit/6caef36968d23b931c824450e418e29ac6277191))
* refreshCfg no longer caches error over valid cert ([#521](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/issues/521)) ([4a6b3d8](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/commit/4a6b3d8c895e2634afd8cee2341db668f20b9a33))

## [1.18.0](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/compare/v1.17.0...v1.18.0) (2020-09-08)


### Features

* **containers:** Add "-alpine" and "-buster" based images.  ([#415](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/issues/415)) ([ebcf294](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/commit/ebcf294b9ee028340695868fb6f4cc4bbe09d849))
* **containers:** Add fuse to alpine and buster images ([#459](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/issues/459)) ([0f28fcd](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/commit/0f28fcd008a5bb863ec2ca1402c31ae81d7dae5d))


### Bug Fixes
* Print out any errors during SIGTERM-caused shutdown ([#389](https://github.com/GoogleCloudPlatform/cloudsql-proxy/pull/389))
* Optimize `-term-timeout` wait ([#391](https://github.com/GoogleCloudPlatform/cloudsql-proxy/pull/391))
* Add socket suffix for Postgres instances when running in `-fuse` mode ([#426](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/issues/426)) ([20ffaec](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/commit/20ffaec2f0f00a2516206a0453bd0d1c6e62770c))
* **containers:** Specify nonroot user by uid to work with runAsNonRoot ([#402](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/issues/402)) ([c5c0be1](https://www.github.com/GoogleCloudPlatform/cloudsql-proxy/commit/c5c0be1b60bfc1c3fa862039619908a328066e5e))
* Releases are now tagged using `vMAJOR.MINOR.PATCH` for correct compatibility with go-modules. Please note that this will effect container image tags (which were previously only `vMAJOR.MINOR`), since these tags correspond directly to the release on GitHub.
