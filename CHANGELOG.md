# Changelog | Dotfiles

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