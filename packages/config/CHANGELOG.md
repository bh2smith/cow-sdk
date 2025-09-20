# Changelog

## [1.0.0](https://github.com/bh2smith/cow-sdk/compare/sdk-config-v0.1.0...sdk-config-v1.0.0) (2025-09-20)


### ⚠ BREAKING CHANGES

* release cow-sdk v7

### ✨ Features

* add monorepo package network images ([#429](https://github.com/bh2smith/cow-sdk/issues/429)) ([56ef05b](https://github.com/bh2smith/cow-sdk/commit/56ef05b84a25955cbe6d1f8f74df0ff0fa2bdfff))
* allow changing backoff and limiter per request ([#208](https://github.com/bh2smith/cow-sdk/issues/208)) ([ebea5ca](https://github.com/bh2smith/cow-sdk/commit/ebea5ca0858aeb89ae3e5d5407c8903c3ca5178d))
* create config package ([212c4a7](https://github.com/bh2smith/cow-sdk/commit/212c4a74eae46ff6150138300334e0565f581ad1))
* **lib-agnostic:** migrate latest Bridging changes ([#426](https://github.com/bh2smith/cow-sdk/issues/426)) ([2359d9b](https://github.com/bh2smith/cow-sdk/commit/2359d9b903e80ae5bab0cdb92d8cf52ae250da36))
* **lib-agnostic:** migrate latest SDK changes ([#427](https://github.com/bh2smith/cow-sdk/issues/427)) ([323bab6](https://github.com/bh2smith/cow-sdk/commit/323bab61eb5adeb4a58bc15e25ffb29d2e1afcbf))
* **monorepo-config:** adjust all package.json and scripts ([23dc2a5](https://github.com/bh2smith/cow-sdk/commit/23dc2a5db02ce3734b55e1151c8579f9a42a4bc5))
* refactor config ([f7fcf73](https://github.com/bh2smith/cow-sdk/commit/f7fcf73a7fde59b47a5aa2432fddea8e1648fd94))
* release cow-sdk v7 ([6cd3e57](https://github.com/bh2smith/cow-sdk/commit/6cd3e573687b1ffdbc0fdcb8cdbb414d88546e38))
* **sdk-agnostic-lib:** create cow trading package ([#368](https://github.com/bh2smith/cow-sdk/issues/368)) ([0a4534a](https://github.com/bh2smith/cow-sdk/commit/0a4534aababce4f5d8bab991cd6ae9f51842d719))
* **sdk-agnostic-lib:** Create weiroll package ([#371](https://github.com/bh2smith/cow-sdk/issues/371)) ([8f6a2e1](https://github.com/bh2smith/cow-sdk/commit/8f6a2e16e5e7a43a5afc43cf5faab174be916b2e))
* test release of packages ([#485](https://github.com/bh2smith/cow-sdk/issues/485)) ([74109d8](https://github.com/bh2smith/cow-sdk/commit/74109d893417c14c1ee476be8040704183e800c6))


### 🐛 Bug Fixes

* **config:** make native token address lower in url ([#499](https://github.com/bh2smith/cow-sdk/issues/499)) ([96e0dc6](https://github.com/bh2smith/cow-sdk/commit/96e0dc6fd837f9b67025d6e05959ad9b773c0ed4))
* fix gnosis native token url ([#501](https://github.com/bh2smith/cow-sdk/issues/501)) ([4d5176e](https://github.com/bh2smith/cow-sdk/commit/4d5176e85594f45d96a5d9d7aa7285cbf3cfebf2))
* migrate lens eth-flow contract address ([#468](https://github.com/bh2smith/cow-sdk/issues/468)) ([91c87b2](https://github.com/bh2smith/cow-sdk/commit/91c87b2e31c1b80ef1703d986f4c49811897f3a0))


### ♻️ Refactoring

* move cow-error and wallets.ts and remove duplicate types ([4a7e5d6](https://github.com/bh2smith/cow-sdk/commit/4a7e5d6d035ccebf05cce437f0409220f39b643a))


### 📚 Documentation

* update README to focus on main use cases ([#493](https://github.com/bh2smith/cow-sdk/issues/493)) ([a05cb1b](https://github.com/bh2smith/cow-sdk/commit/a05cb1ba11b5f9895d7cfe6262cf74c4089fd73c))


### 🔧 Miscellaneous

* migrate latest changes from main 26-08-2025 ([#445](https://github.com/bh2smith/cow-sdk/issues/445)) ([698937c](https://github.com/bh2smith/cow-sdk/commit/698937c0feff3a254873371bc1ef791917e6294e))
* release main ([#453](https://github.com/bh2smith/cow-sdk/issues/453)) ([36080c1](https://github.com/bh2smith/cow-sdk/commit/36080c1955f5f161bebce7867af110f6938e5c95))
* release main ([#467](https://github.com/bh2smith/cow-sdk/issues/467)) ([ed2977a](https://github.com/bh2smith/cow-sdk/commit/ed2977a82bb2f4b43de900840848e33532d001f0))
* release main ([#486](https://github.com/bh2smith/cow-sdk/issues/486)) ([cf53df2](https://github.com/bh2smith/cow-sdk/commit/cf53df2d0f5e96a544165547958ecc959c1948d7))
* release main ([#500](https://github.com/bh2smith/cow-sdk/issues/500)) ([76c5185](https://github.com/bh2smith/cow-sdk/commit/76c5185d4b827d185af11bef9435fbed87484b0b))
* release main ([#502](https://github.com/bh2smith/cow-sdk/issues/502)) ([c452d8e](https://github.com/bh2smith/cow-sdk/commit/c452d8e53bc0dcd79052b1877d2c48a32777093e))
* release main ([#503](https://github.com/bh2smith/cow-sdk/issues/503)) ([532d8eb](https://github.com/bh2smith/cow-sdk/commit/532d8eb2a0a0f9ec5775e566fe2507f1ccc4f961))
* release main ([#515](https://github.com/bh2smith/cow-sdk/issues/515)) ([912e315](https://github.com/bh2smith/cow-sdk/commit/912e31551440ebfa61d7d2f5c846d61162559448))
* **sdk-agnostic-lib:** merge multiple PRs to avoid conflicts and speed up base branch sync ([#354](https://github.com/bh2smith/cow-sdk/issues/354)) ([55d3068](https://github.com/bh2smith/cow-sdk/commit/55d3068c52217dd2618d8c180ab4fed8c9334c72))
* update sdk-config tsconfig ([8666af4](https://github.com/bh2smith/cow-sdk/commit/8666af48c60cd1d6e945f8412b192029299f7c90))

## [0.1.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-config-v0.3.3-beta.0...sdk-config-v0.1.0) (2025-09-17)


### ⚠ BREAKING CHANGES

* release cow-sdk v7

### ✨ Features

* release cow-sdk v7 ([6cd3e57](https://github.com/cowprotocol/cow-sdk/commit/6cd3e573687b1ffdbc0fdcb8cdbb414d88546e38))

## [0.3.3-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-config-v0.3.2-beta.0...sdk-config-v0.3.3-beta.0) (2025-09-16)


### 📚 Documentation

* update README to focus on main use cases ([#493](https://github.com/cowprotocol/cow-sdk/issues/493)) ([a05cb1b](https://github.com/cowprotocol/cow-sdk/commit/a05cb1ba11b5f9895d7cfe6262cf74c4089fd73c))

## [0.3.2-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-config-v0.3.1-beta.0...sdk-config-v0.3.2-beta.0) (2025-09-15)


### 🐛 Bug Fixes

* fix gnosis native token url ([#501](https://github.com/cowprotocol/cow-sdk/issues/501)) ([4d5176e](https://github.com/cowprotocol/cow-sdk/commit/4d5176e85594f45d96a5d9d7aa7285cbf3cfebf2))

## [0.3.1-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-config-v0.3.0-beta.0...sdk-config-v0.3.1-beta.0) (2025-09-15)


### 🐛 Bug Fixes

* **config:** make native token address lower in url ([#499](https://github.com/cowprotocol/cow-sdk/issues/499)) ([96e0dc6](https://github.com/cowprotocol/cow-sdk/commit/96e0dc6fd837f9b67025d6e05959ad9b773c0ed4))

## [0.3.0-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-config-v0.2.1-beta.0...sdk-config-v0.3.0-beta.0) (2025-09-11)


### ✨ Features

* test release of packages ([#485](https://github.com/cowprotocol/cow-sdk/issues/485)) ([74109d8](https://github.com/cowprotocol/cow-sdk/commit/74109d893417c14c1ee476be8040704183e800c6))

## [0.2.1-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-config-v0.2.0-beta.0...sdk-config-v0.2.1-beta.0) (2025-09-01)


### 🐛 Bug Fixes

* migrate lens eth-flow contract address ([#468](https://github.com/cowprotocol/cow-sdk/issues/468)) ([91c87b2](https://github.com/cowprotocol/cow-sdk/commit/91c87b2e31c1b80ef1703d986f4c49811897f3a0))

## [0.2.0-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-config-v0.1.0-beta.0...sdk-config-v0.2.0-beta.0) (2025-08-28)


### ✨ Features

* add monorepo package network images ([#429](https://github.com/cowprotocol/cow-sdk/issues/429)) ([56ef05b](https://github.com/cowprotocol/cow-sdk/commit/56ef05b84a25955cbe6d1f8f74df0ff0fa2bdfff))
* allow changing backoff and limiter per request ([#208](https://github.com/cowprotocol/cow-sdk/issues/208)) ([ebea5ca](https://github.com/cowprotocol/cow-sdk/commit/ebea5ca0858aeb89ae3e5d5407c8903c3ca5178d))
* create config package ([212c4a7](https://github.com/cowprotocol/cow-sdk/commit/212c4a74eae46ff6150138300334e0565f581ad1))
* **lib-agnostic:** migrate latest Bridging changes ([#426](https://github.com/cowprotocol/cow-sdk/issues/426)) ([2359d9b](https://github.com/cowprotocol/cow-sdk/commit/2359d9b903e80ae5bab0cdb92d8cf52ae250da36))
* **lib-agnostic:** migrate latest SDK changes ([#427](https://github.com/cowprotocol/cow-sdk/issues/427)) ([323bab6](https://github.com/cowprotocol/cow-sdk/commit/323bab61eb5adeb4a58bc15e25ffb29d2e1afcbf))
* **monorepo-config:** adjust all package.json and scripts ([23dc2a5](https://github.com/cowprotocol/cow-sdk/commit/23dc2a5db02ce3734b55e1151c8579f9a42a4bc5))
* refactor config ([f7fcf73](https://github.com/cowprotocol/cow-sdk/commit/f7fcf73a7fde59b47a5aa2432fddea8e1648fd94))
* **sdk-agnostic-lib:** create cow trading package ([#368](https://github.com/cowprotocol/cow-sdk/issues/368)) ([0a4534a](https://github.com/cowprotocol/cow-sdk/commit/0a4534aababce4f5d8bab991cd6ae9f51842d719))
* **sdk-agnostic-lib:** Create weiroll package ([#371](https://github.com/cowprotocol/cow-sdk/issues/371)) ([8f6a2e1](https://github.com/cowprotocol/cow-sdk/commit/8f6a2e16e5e7a43a5afc43cf5faab174be916b2e))


### ♻️ Refactoring

* move cow-error and wallets.ts and remove duplicate types ([4a7e5d6](https://github.com/cowprotocol/cow-sdk/commit/4a7e5d6d035ccebf05cce437f0409220f39b643a))


### 🔧 Miscellaneous

* migrate latest changes from main 26-08-2025 ([#445](https://github.com/cowprotocol/cow-sdk/issues/445)) ([698937c](https://github.com/cowprotocol/cow-sdk/commit/698937c0feff3a254873371bc1ef791917e6294e))
* **sdk-agnostic-lib:** merge multiple PRs to avoid conflicts and speed up base branch sync ([#354](https://github.com/cowprotocol/cow-sdk/issues/354)) ([55d3068](https://github.com/cowprotocol/cow-sdk/commit/55d3068c52217dd2618d8c180ab4fed8c9334c72))
* update sdk-config tsconfig ([8666af4](https://github.com/cowprotocol/cow-sdk/commit/8666af48c60cd1d6e945f8412b192029299f7c90))
