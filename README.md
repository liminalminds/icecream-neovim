# Icecream for [Neovim](https://github.com/neovim/neovim)

![Screenshot](screenshot.png)

## Credits

This colorscheme is based on the awesome [rosepine](https://github.com/rose-pine) colorscheme for [neovim](https://github.com/rose-pine/neovim).

## Install

### [Lazy](https://github.com/folke/lazy.nvim)

```lua
require('lazy').setup({
  {
    'liminalminds/icecream-neovim',
    name = 'icecream',
    lazy = false,
    priority = 1000,
  }
})
```

### [Packer](https://github.com/wbthomason/packer.nvim)

```lua
require('packer').startup(function(use)
  use({ 'liminalminds/icecream-neovim', as = 'icecream' })
end)
```

