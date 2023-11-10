# Changelog

## [1.4.0](https://github.com/hostinger/ansible-collection-fireactions/compare/v1.3.0...v1.4.0) (2023-11-10)


### Features

* **client:** Add default containerd config ([0f0239b](https://github.com/hostinger/ansible-collection-fireactions/commit/0f0239b4c9e9079d4d126c64276c0bf44e1dcf24))
* **client:** Update version to v1.2.0 ([55caf99](https://github.com/hostinger/ansible-collection-fireactions/commit/55caf99e84cafb819d3a5e60f7cc4c228031ec21))

## [1.3.0](https://github.com/hostinger/ansible-collection-fireactions/compare/v1.2.0...v1.3.0) (2023-11-09)


### Features

* **ci:** Publish to Ansible Galaxy on release ([5d56a00](https://github.com/hostinger/ansible-collection-fireactions/commit/5d56a002d626ae0c936ded4c9513161c8df45a04))

## [1.2.0](https://github.com/hostinger/ansible-collection-fireactions/compare/v1.1.0...v1.2.0) (2023-11-09)


### Features

* Move out core roles to hostinger.core collection ([fb87471](https://github.com/hostinger/ansible-collection-fireactions/commit/fb874715241af6beb912431cba6e0930fbfd5ee3))

## [1.1.0](https://github.com/hostinger/ansible-collection-fireactions/compare/v1.0.1...v1.1.0) (2023-11-08)


### Features

* **roles/client:** Ability to disable dependencies install ([a5a3561](https://github.com/hostinger/ansible-collection-fireactions/commit/a5a3561a1242c1e5142ceb4007f45e37a45cce61))
* **roles/client:** Allow setting service state ([c8fc0ef](https://github.com/hostinger/ansible-collection-fireactions/commit/c8fc0ef5041fb41d7dbe04dca49c9799b6a39e3d))
* **roles/client:** Set sysctl setting net.ipv4.ip_forward=1 ([2805cb4](https://github.com/hostinger/ansible-collection-fireactions/commit/2805cb46726e999f9c919618a355f999cd8a3e20))
* **roles/containerd:** Allow setting service state ([627a69e](https://github.com/hostinger/ansible-collection-fireactions/commit/627a69e24caa119c12eaf6b666cd64145b2c173f))
* **roles/firecracker:** Remove option to configure symlink ([57d0e72](https://github.com/hostinger/ansible-collection-fireactions/commit/57d0e7258d0ab39490ebb9de5f24753ca9fcb7dd))
* **roles:** Add sysctl role ([2805cb4](https://github.com/hostinger/ansible-collection-fireactions/commit/2805cb46726e999f9c919618a355f999cd8a3e20))

## [1.0.1](https://github.com/hostinger/ansible-collection-fireactions/compare/v1.0.0...v1.0.1) (2023-11-01)


### Bug Fixes

* **roles/client:** Correctly merge default config ([98b83d9](https://github.com/hostinger/ansible-collection-fireactions/commit/98b83d9a56983c6e291d3520d3b1c435d8d6ca6f))

## [1.0.0](https://github.com/hostinger/ansible-collection-fireactions/compare/v0.3.0...v1.0.0) (2023-11-01)


### ⚠ BREAKING CHANGES

* **roles/client:** Add support for v1.0.3

### Features

* **roles/client:** Add support for v1.0.3 ([dd79db0](https://github.com/hostinger/ansible-collection-fireactions/commit/dd79db0b87314de36a4d77a41ea822d6f54b0e7b))
* **roles/cni_plugins:** Include all plugins in cni_plugins_binaries ([a791119](https://github.com/hostinger/ansible-collection-fireactions/commit/a7911194b4eb7ebb231f69bbdb8576a11594f5a9))
* **roles:** Add cni role ([aee5914](https://github.com/hostinger/ansible-collection-fireactions/commit/aee591405edf2d3e8a7cc07375642fa1627914b8))

## [0.3.0](https://github.com/hostinger/ansible-collection-fireactions/compare/v0.2.0...v0.3.0) (2023-11-01)


### Features

* **ci:** Test roles on Ubuntu (22.04,20.04) and Debian (10,11,12) distros ([4d562d4](https://github.com/hostinger/ansible-collection-fireactions/commit/4d562d4bbd5ea66e5151caa097e6af590661a5d6))
* **roles:** Add cni_plugins role ([f35d4e3](https://github.com/hostinger/ansible-collection-fireactions/commit/f35d4e3a53cac1e7e292b6ff943d53bc84da8c31))

## [0.2.0](https://github.com/hostinger/ansible-collection-fireactions/compare/v0.1.1...v0.2.0) (2023-10-31)


### Features

* **roles:** Add containerd role ([71ee711](https://github.com/hostinger/ansible-collection-fireactions/commit/71ee7118f51875074ff790a99c460d3d16ce7ee4))


### Bug Fixes

* **roles/client:** Remove fireactions_os variable, support only linux ([8f922a6](https://github.com/hostinger/ansible-collection-fireactions/commit/8f922a60b5496697f603ab939563d2bb67f303dd))

## [0.1.1](https://github.com/hostinger/ansible-collection-fireactions/compare/v0.1.0...v0.1.1) (2023-10-31)


### Bug Fixes

* **ci:** Test release-please ([f1349a3](https://github.com/hostinger/ansible-collection-fireactions/commit/f1349a32923454ed371ea7087ce146ca58f21fe4))

## 0.1.0 (2023-10-31)


### Features

* Initial commit ([4e004f5](https://github.com/hostinger/ansible-collection-fireactions/commit/4e004f53420ca16be74b3f707610721467f97ef1))
* Preflight checks for OS and architecture ([11011e3](https://github.com/hostinger/ansible-collection-fireactions/commit/11011e3fa23f2e71ff79ae41fe89d61891e64a52))
* Restructure to Ansible collection ([#1](https://github.com/hostinger/ansible-collection-fireactions/issues/1)) ([15d698b](https://github.com/hostinger/ansible-collection-fireactions/commit/15d698b1ec3c74bc40375ee1ecc6847e29cf4c12))
