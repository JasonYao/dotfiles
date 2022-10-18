# Lazy dotfiles configuration

## tl;dr
Run these commands based on the OS and desired profile:

```sh
##
# For the curl command:
# -L signifies to follow redirects (required to download from github
# -o dictates what the output file will be called
##

# MacOS personal
mkdir -p ~/.dotfiles && curl -L -o ~/.dotfiles/dotfiles.zip https://github.com/JasonYao/dotfiles/releases/download/v1.3.0/dotfiles-macos-personal.zip && cd ~/.dotfiles && unzip dotfiles.zip && bash install.sh

# MacOS work
mkdir -p ~/.dotfiles && curl -L -o ~/.dotfiles/dotfiles.zip https://github.com/JasonYao/dotfiles/releases/download/v1.3.0/dotfiles-macos-work.zip && cd ~/.dotfiles && unzip dotfiles.zip && bash install.sh

# Linux personal
mkdir -p ~/.dotfiles && curl -L -o ~/.dotfiles/dotfiles.zip https://github.com/JasonYao/dotfiles/releases/download/v1.3.0/dotfiles-linux-personal.zip && cd ~/.dotfiles && unzip dotfiles.zip && bash install.sh

# Linux work
mkdir -p ~/.dotfiles && curl -L -o ~/.dotfiles/dotfiles.zip https://github.com/JasonYao/dotfiles/releases/download/v1.3.0/dotfiles-linux-work.zip && cd ~/.dotfiles && unzip dotfiles.zip && bash install.sh
```

## Overview
This repo contains my own personal set of [dotfiles](https://dotfiles.github.io/),
in order to unify my own customized experience across all
`macOS` and `*nix` systems.

This dotfiles leverages [pydotfiles](https://github.com/JasonYao/pydotfiles/)
which enables me to keep large portions of the dotfiles as JSON/YAML configuration
files, instead of bash or python scripts.

For a less opinionated basic repo of a configuration-based set of
dotfiles that is meant to be easily forked and customized, please
see the [pydotfiles-basic](https://github.com/JasonYao/pydotfiles-basic/) repo.

## Features
- Automatically sets my background image
- Automatically manages my configuration files via symlinks
- Automatically installs a lot of utilities that I commonly use
  (e.g. GNU tools, wget, bash v4+, vim, node, etc.)
- Automatically sets sane defaults for my OS, e.g.:
  - Turns on the firewall, and enables stealth-mode receiving
  - Turns on a super-high key-repeat rate
  - Turns on showing the battery percentage
  - Sets the computer to never sleep unless explicitly told to
  - Disables Apple's "natural" scrolling (god that thing is so annoying)
  - Removes all the clutter from my dock, and adds in just the applications
    that I want on the dock
  - Enables [dark mode](https://support.apple.com/en-us/HT208976) (hurray!)
  - Sets the default DNS to [Cloudflare's DNS](https://1.3.0.1/)
  - Removes ISP-level bloatware in the form of browser hijacking via
    [search domains](https://www.theregister.com/2007/11/08/verizon_highjacks_web_browsers_on_fios/) (seriously, how is this even a thing?)
- Automatically installs a bunch of useful applications like:
  - [Firefox](https://www.mozilla.org/en-US/firefox/)
  - [smcFanControl](https://www.eidac.de/)
  - [JetBrains Toolbox](https://www.jetbrains.com/toolbox/)
  - [vlc](https://www.videolan.org/vlc/index.html)
  - and everything else that I end up using on a day-to-day basis
- Sets up proper dev environment runtimes via environment managers
  like [jenv](https://www.jenv.be/) for Java, and [pyenv](https://github.com/pyenv/pyenv) for Python
- Sets up proper git environment with a much prettier [diff](https://github.com/so-fancy/diff-so-fancy)
- Adds iTerm 2 [shell integrations](https://www.iterm2.com/documentation-shell-integration.html)
- Enables you to hide/show iTerm as an overlay via a keystroke!
  (see the [usage](#Usage)) section below
- And many more!

## Supported Platforms
- macOS 10.12.x+ (Sierra+)
- Ubuntu 16.04 LTS

## Usage
- To toggle showing/hiding of iTerm 2:
<kbd>⌘</kbd> + <kbd>↓</kbd>

## License
This repo is licensed under the terms of the
GNU GPL v3, a copy of which may be found [here](LICENSE).
