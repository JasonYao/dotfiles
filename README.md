# Lazy Dotfiles Configuration | Why do work when you can be lazy
By [Jason Yao](https://github.com/JasonYao/)

This repo contains my own personal implementation of the
configuration files required to use the [pydotfiles]() library
for dotfile creation and management, in order to unify my
own personal experience across all `macOS` and `*nix` systems.

For a less opinionated basic example, please see
the [pydotfiles-configuration-basic]() repo.

## Features
- Sets sane starting defaults

- Downloads a bunch of useful command-line tools (GNU tools, wget, bash v4+, vim, node, etc.)

- [macOS only] Downloads a bunch of useful applications:
  - [Firefox](https://www.mozilla.org/en-US/firefox/)
  - [smcFanControl](https://www.eidac.de/)
  - [JetBrains Toolbox](https://www.jetbrains.com/toolbox/)
  - [vlc](https://www.videolan.org/vlc/index.html)
  - and everything else that I end up using on a day-to-day basis

- Secures and locks down the system via proper firewalling

- Sets up proper dev environments (Python, Java, Ruby, Golang)

- Sets up proper git environment with a better [diff](https://github.com/so-fancy/diff-so-fancy)

- [macOS only] Adds iTerm 2 [shell integrations](https://www.iterm2.com/documentation-shell-integration.html)

## Supported Platforms
- macOS 10.12.x+ (Sierra+)
- Ubuntu 16.04 LTS

# Installation
### [RECOMMENDED] Opinionated Bootstrap
The following one-liner will bootstrap the system to an opinionated
setup, in particular setting up [pyenv](https://github.com/pyenv/pyenv)
for you if you don't have it yet, and setting up a new laptop-wide global
python environment for day-to-day use.

**`Basically, if there's a completely new computer, run this:`**

```sh
curl -s https://raw.githubusercontent.com/JasonYao/pydotfiles/master/start-opinionated | bash -s {CONFIGURATION_REPO_GIT_LINK}
# e.g.
curl -s https://raw.githubusercontent.com/JasonYao/pydotfiles/master/start-opinionated | bash -s git@github.com:JasonYao/dotfiles.git
```

### Non-Opinionated Bootstrap
The following one-liner won't assume the python environment that you're
installing this to, and just install itself with `pip`.

**`Basically, if your computer already has the required python version/environments, run this:`**

```sh
curl -s https://raw.githubusercontent.com/JasonYao/pydotfiles/master/start-base | bash -s {CONFIGURATION_REPO_GIT_LINK}
# e.g.
curl -s https://raw.githubusercontent.com/JasonYao/pydotfiles/master/start-base | bash -s git@github.com:JasonYao/dotfiles.git
```

## Usage
- To toggle show/hiding of iTerm 2:
<kbd>⌘</kbd> + <kbd>↓</kbd>

- To update + upgrade the dotfiles:
```sh
pydotfiles upgrade
```

- To uninstall the dotfiles:
```sh
pydotfiles uninstall
```

## License
This repo is licensed under the terms of the
GNU GPL v3, a copy of which may be found [here](LICENSE).
