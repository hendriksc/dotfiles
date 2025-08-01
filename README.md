# 🏠 Dotfiles

![Build Status](https://github.com/hendriksc/dotfiles/actions/workflows/ci.yml/badge.svg)
[![SLOC](https://sloc.xyz/github/hendriksc/dotfiles?lower=true&badge-bg-color=32CD32)](#)
[![XDG Compliancy](https://img.shields.io/badge/%E2%9C%94%20Compliancy-XDG%20Base%20Directory%20Standard-limegreen)](#)


My local dotfiles, managed with [dotbot](https://github.com/anishathalye/dotbot). I follow the XDG Base Directory Specification for a clean, minimal `$HOME` and install my used packages using `homebrew/linuxbrew` under `$HOME/.local/share`.

## Usage

```bash
# clone and link dotfiles
git clone https://github.com/hendriksc/dotfiles ~/.dotfiles && cd ~/.dotfiles && ./install
```

## Private Submodule

This repo includes a private submodule at `.private/` for machine-specific and secret data.

If you don't have access to it and want to try my other dotfiles, you can safely ignore any Git warnings - the public dotfiles work fine without it.
