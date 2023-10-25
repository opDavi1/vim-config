
# My neovim config.

This config is mainly just for me whenever I need to install neovim on a new computer.  
It's probably pretty bad compared to yours or anyone else's but hey it's here if you need it for some reason.

# Requirements

> For mason to install language servers

- You need a C compiler installed and in your PATH environment variable. I use minGW to get clang, but cc, gcc, cl, and zig are also available to use. If you're on Linux you likely already have a C compiler installed.
- Node.js is required for NPM if you want the Javascript language server.
<br>
<br>

> For the Java language server (jdtls):

- You need to have Java installed (duh)

# Installation

First install packer.nvim (Installation as of August 2023, check [wbthomason/packer.nvim](wbthomason/packer.nvim) for current installation)

> Windows (Powershell):
 
```cmd
git clone https://github.com/wbthomason/packer.nvim "$env:LOCALAPPDATA\nvim-data\site\pack\packer\start\packer.nvim"
```

> Unix/Linux:

```bash
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
~/.local/share/nvim/site/pack/packer/start/packer.nvim
```
<br>
<br>

After you install packer, you can clone this repo and put the files in your neovim config folder.

> Windows:

```file
C:\Users\<USER>\AppData\Local\nvim
```

> Unix/Linux:
 ```file
~/.config/nvim/
```
<br>
<br>

Then you can run ```:PackerSync``` once neovim is open.  
After all of the plugins are done installing / updating, restart neovim.
Run ```:PackerSync``` and restart one more time and pray to god that none of the packages had any updates that break this config and you should be good to go!


