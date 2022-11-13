# gruvbuddy.nvim

Gruvbox-esque colors using [tjdevries/colorbuddy.vim](https://github.com/tjdevries/colorbuddy.vim)

![screen](./media/screenshot.png)

This plugin is also an example of how easy it is to customize and make new colorschemes based on `colorbuddy`.

Check out `lua/gruvbuddy.lua`

## Installation

### packer
```lua
use { 'tjdevries/gruvbuddy.nvim', requires = 'tjdevries/colorbuddy.vim'}
```

### vim-plug 
```vim
Plug 'tjdevries/colorbuddy.vim'
Plug 'tjdevries/gruvbuddy.nvim'
```


### Usage
somewhere in your init.vim
```vim
colorscheme gruvbuddy
```

or if you have a lua configuration
```lua
vim.cmd [[ colorscheme gruvbuddy ]]
```
