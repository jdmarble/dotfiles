# dotfiles

My dotfiles managed by chezmoi.

## Installation

[Install nix](https://github.com/DeterminateSystems/nix-installer),
then use it to clone and apply the configuration:

```sh
nix run nixpkgs#chezmoi -- init https://github.com/jdmarble/dotfiles.git
nix run nixpkgs#chezmoi -- apply
```
