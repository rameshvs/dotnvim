.nvim
---
This is my neovim configuration. To use this, you'll need to clone it into `~/.config/nvim` and then install plugins:

    mkdir -p $HOME/.config/nvim
    git clone http://github.com/rameshvs/dotnvim $HOME/.config/nvim
    nvim +PlugInstall +qa

I've tested this on Mac OS X 10.13.5 and a few flavors of linux. I can't make
any guarantees, but I do try to make sure it works across all platforms
that I use.

I've documented most of the settings in `init.vim`, and vim's excellent `:help`
explains things even better.

Plugins
---
I organize my neovim plugins using `vim-plug`. To install, you need to either
open neovim and run `:PlugInstall`, or use the command above. Plugins (and
their configuration) are at the top of `init.vim`.
