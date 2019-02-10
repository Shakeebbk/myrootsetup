# FFS
> Clone repo
> source shakeeb_bashrc
> source shakeeb_vimrc

# Terminal Setup
https://blog.ropnop.com/configuring-a-pretty-and-usable-terminal-emulator-for-wsl/

# VIM

## Install ultimate rc
[Vimrc Link](https://github.com/amix/vimrc)

## Change color scheme
```
~/.vim_runtime/vimrcs/basic.vim
colorschem solarized
```
## Change NerdTree scheme
```
~/.vim_runtime/vimrcs/plugins_config.vim
NerdTree window - left
```
### VIM Commands
https://stackoverflow.com/questions/11784408/vim-multiline-editing-like-in-sublimetext

# Multiline edit
Cntrl+v all line, I<chars>, esc

# nerd tree
,nn -> open
,nf -> reveal file

# cntrl p - search file
: cd <path>
,j

# open recently opened file
,f

# find and replace in file
visual select, cntrl+r
# find and replace in project
cntrl+v select ,r
list finds - ,cc or ,co
next and prev finding - ,n & ,p
# grep using Ack from visual selection
sudo apt install ack -y
simpler: cntrl+v select, gv
,g cntrl+r "
