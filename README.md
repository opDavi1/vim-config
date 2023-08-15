
# My neovim config.

This config is mainly just for me whenever I need to install neovim on a new computer.  
It's probably pretty bad compared to yours or anyone else`s but hey it's here if you need it for some reason.


# Installation

To set up this neovim config, first install packer.nvim (Installation as of August 2023, check [wbthomason/packer.nvim](wbthomason/packer.nvim) for current installation)

> Windows:
 
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
After all of the plugins are done installing / updating just restart neovim for the changes to take effect.  


