# gruvbuddy.nvim

This colorscheme used to look kind of like gruvbox, but now it looks like what you
can see on my stream :)

Check out `colors/gruvbuddy.lua`

## Installation

```lua
-- Lazy setup
return {
  {
    'tjdevries/gruvbuddy.nvim',
    dependencies = {
       { 'tjdevries/colorbuddy.vim', branch = 'dev' },
    },
    config = function()
      vim.cmd.colorscheme("gruvbuddy")
    end,
  }
}
```
