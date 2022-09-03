# Setup

## (1) install nvim

Take appimage or `.deb` from here:

https://github.com/neovim/neovim/releases/nightly


## (2) install Astro config

```sh
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
nvim +PackerSync
```

## (2a) server installs

`:TSInstall python`
`:LspInstall pyright`

etc.

## (3) clone user customization

Clone with the specified dir name `user`.

```sh
cd ~/.config/nvim/lua
git clone https://www.github.com/windrim/nvim user
```

Then `:PackerSync`.
