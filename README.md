# GRB256

`grb256` is a Vim color scheme by Gary Bernhardt, based on `ir_black`, "the last Vim color scheme you'll ever need", by Todd Werth.

The file exists in [garybernhardt/dotfiles/.vim/colors/grb256.vim](https://github.com/garybernhardt/dotfiles/blob/main/.vim/colors/grb256.vim); this is a standalone version suitable to be packaged.

There are several other versions of the same thing, such as:
* [quanganhdo/grb256](https://github.com/quanganhdo/grb256),
* [zanloy/vim-colors-grb256](https://github.com/zanloy/vim-colors-grb256).

The main difference is this preserves the original Git history (as well as possible) from Gary's original implementation.

## Usage

Install in `pack/*/opt/grb256` and add
```vim
packadd grb256
colorscheme grb256
```
or
```lua
vim.cmd.packadd("grb256")
vim.cmd.colorscheme("grb256")
```
to your configuration file.
