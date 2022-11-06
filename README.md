# Contextual Folding Organizer (CFO)

The main idea of this plugin is to provide the user foldmethods for different

## Installation

- Using vim default plugin manager.

```bash
mkdir -p ~/.vim/pack/RobinCamarasa/start
cd ~/.vim/pack/RobinCamarasa/start
git https://github.com/RobinCamarasa/cfo.vim.git
vim -u NONE -c "helptags cfo.vim/doc" -c q
```

- Using [vim-plug](https://github.com/junegunn/vim-plug) this plugin can be installed as follow:

```vimscript
Plug "RobinCamarasa/cfo.vim"
```

## Documentation

To check the documentation, launch the following command within vim: `:help cfo`
The main idea of this plugin is to provide the user |foldmethod| for different

## Folding Overview

|Filetype|method|
|---|---|
|sh|marker|
|vim|marker|
|python|indent|

## Author

- [RobinCamarasa](https://github.com/RobinCamarasa)
