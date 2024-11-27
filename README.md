# dotfiles

My dotfiles managed by chezmoi.

## Installation

[Install homebrew](https://brew.sh) if not provided by your distribution already.

[Install nix](https://github.com/DeterminateSystems/nix-installer),
then use it to clone and apply the configuration:

```sh
nix run nixpkgs#chezmoi -- init https://github.com/jdmarble/dotfiles.git
nix run nixpkgs#chezmoi -- apply
```
