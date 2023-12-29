# ⚙️machine.nvim

**machine.nvim** is a plugin mananger for neovim

## Requirements
- Neovim >= 9.0
- Git latest version

## Installation
Add the code to your **$HOME/.config/init.lua**  
```lua  
-- default download directory 
local M_path = vim.fn.stdpath("data") .. "/machine.nvim"  

--- add the above dir to neovim runtimepath
vim.opt.rtp:prepend(M_path)

-- require machine lua module
require("machine")

```

## author
luolawlan@outlook.com

## license
MIT