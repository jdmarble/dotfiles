# dotfiles

My dotfiles managed by chezmoi.

## Installation

### macOS

* Sign in to the App Store.
* [Install homebrew](https://brew.sh).

### Common

[Install nix](https://github.com/DeterminateSystems/nix-installer),
then use it to clone and apply the configuration:

```sh
nix run nixpkgs#chezmoi -- init https://github.com/jdmarble/dotfiles.git
nix run nixpkgs#chezmoi -- apply
```
