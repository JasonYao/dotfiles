# Changelog | Dotfiles

# [1.5.0](https://github.com/JasonYao/dotfiles/compare/v1.4.2...v1.5.0) (2022-10-20)


### Bug Fixes

* **shell:** resets the shell back to the normal bash since it errors out otherwise ([e71ad20](https://github.com/JasonYao/dotfiles/commit/e71ad203528180974aabfa1a56106aadb7f20045))


### Features

* **powerline:** adds in a new default powerline that responds to directory location ([6137ca6](https://github.com/JasonYao/dotfiles/commit/6137ca61fee5b42f7f9a794491d56a68c24fd365)), closes [#63](https://github.com/JasonYao/dotfiles/issues/63)

## [1.4.2](https://github.com/JasonYao/dotfiles/compare/v1.4.1...v1.4.2) (2022-10-18)


### Bug Fixes

* **vim:** makes vim colorscheme less of an eyesore ([d14b751](https://github.com/JasonYao/dotfiles/commit/d14b751c005ea39a9339f7157002c73af8ca8e75)), closes [#61](https://github.com/JasonYao/dotfiles/issues/61)

## [1.4.1](https://github.com/JasonYao/dotfiles/compare/v1.4.0...v1.4.1) (2022-10-18)


### Bug Fixes

* **default-settings:** fixes default settings so that its idempotent ([774b563](https://github.com/JasonYao/dotfiles/commit/774b56320188fa3049bd810cc2d13a3266b8223a))
* **default-settings:** fixes the dock folder add idempotency issue and re-added in read checks ([7da904b](https://github.com/JasonYao/dotfiles/commit/7da904bf4f252d68a310a723f8b8e35ee5c109fa)), closes [#59](https://github.com/JasonYao/dotfiles/issues/59)

# [1.4.0](https://github.com/JasonYao/dotfiles/compare/v1.3.0...v1.4.0) (2022-10-18)


### Features

* **homebrew:** disables analytics from homebrew package manager ([a5b2fe0](https://github.com/JasonYao/dotfiles/commit/a5b2fe0d4e5ac2b9ab42f9f5dd9f9de3ab200839)), closes [#33](https://github.com/JasonYao/dotfiles/issues/33)

# [1.3.0](https://github.com/JasonYao/dotfiles/compare/v1.2.0...v1.3.0) (2022-10-18)


### Features

* **readline:** updates shell auto completion options to not ring bell when ambiguous ([f126ec5](https://github.com/JasonYao/dotfiles/commit/f126ec5fd2cc0f7e077e25b0783379eba9bf1a7c)), closes [#15](https://github.com/JasonYao/dotfiles/issues/15)

# [1.2.0](https://github.com/JasonYao/dotfiles/compare/v1.1.2...v1.2.0) (2022-10-17)


### Features

* **shell:** sets default shell for macos personal to be bash instead of zsh ([18a73d5](https://github.com/JasonYao/dotfiles/commit/18a73d531c5801b8dd3eb9a31d9696facf2fa930))

## [1.1.2](https://github.com/JasonYao/dotfiles/compare/v1.1.1...v1.1.2) (2022-10-17)


### Bug Fixes

* **dns:** disables default DNS setting for now to avoid script error ([0d84116](https://github.com/JasonYao/dotfiles/commit/0d84116859adf53d3bf3477117ef442825192629))

## [1.1.1](https://github.com/JasonYao/dotfiles/compare/v1.1.0...v1.1.1) (2022-10-17)


### Bug Fixes

* **macos:** fixes global macos disabling of smart quotes ([03c5345](https://github.com/JasonYao/dotfiles/commit/03c5345d91043339657ee634e9be7a43f275f88f))

# [1.1.0](https://github.com/JasonYao/dotfiles/compare/v1.0.0...v1.1.0) (2022-10-17)


### Features

* **default-settings:** disables smart quotes and smart dashes for MacOS ([e0be461](https://github.com/JasonYao/dotfiles/commit/e0be4614152f6bbf94d5ed85c437097ae5426603)), closes [#46](https://github.com/JasonYao/dotfiles/issues/46)

# 1.0.0 (2022-10-17)


### Bug Fixes

* **pydotfiles:** Updates our dotfiles to be compatible with version 3.0 release ([2c318bf](https://github.com/JasonYao/dotfiles/commit/2c318bf83219d58f72f6abacfb43452eb9f2964a)), closes [#23](https://github.com/JasonYao/dotfiles/issues/23)
* **schema:** Updates dotfiles to utilize the alpha schema for pydotfiles ([fbf62ce](https://github.com/JasonYao/dotfiles/commit/fbf62ce4dfbe218b25cdeb4adf0aa8a06381b7ea)), closes [#10](https://github.com/JasonYao/dotfiles/issues/10)


### Continuous Integration

* **semver:** added in auto semver and automated releases ([8471a64](https://github.com/JasonYao/dotfiles/commit/8471a64a979907336a613612a925323ac9800836)), closes [#54](https://github.com/JasonYao/dotfiles/issues/54)


### Features

* **general:** General updates to dotfiles ([d40bf2f](https://github.com/JasonYao/dotfiles/commit/d40bf2f9de5ecc5eaffd3d9abeb57c9e98707d53))
* **git:** Adds in git track/untrack aliases and branch sorting override ([40ed5c0](https://github.com/JasonYao/dotfiles/commit/40ed5c0495131e897598ae965cc874a80e0d1369)), closes [#4](https://github.com/JasonYao/dotfiles/issues/4)
* **homebrew:** Adds in the jq library by default ([09aa0c7](https://github.com/JasonYao/dotfiles/commit/09aa0c715d15ccb41f62cc452ba37a4b64b0f7ad)), closes [#9](https://github.com/JasonYao/dotfiles/issues/9)


### Performance Improvements

* **dns:** Updates default DNS to point to Cloudflare's 1.1.1.1 DNS ([3d23768](https://github.com/JasonYao/dotfiles/commit/3d237687d65d4ce606fd530e1af5a25c8bd7c4ef)), closes [#3](https://github.com/JasonYao/dotfiles/issues/3)


### BREAKING CHANGES

* **semver:** Current approaches using the old script will no longer work
