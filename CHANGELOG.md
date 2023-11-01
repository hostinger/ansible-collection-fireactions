# Changelog

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
