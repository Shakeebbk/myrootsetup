# FFS
> Clone repo
> source shakeeb_bashrc
> source shakeeb_vimrc

# Terminal Setup
https://blog.ropnop.com/configuring-a-pretty-and-usable-terminal-emulator-for-wsl/

# VIM

## Install ultimate rc
[Vimrc Link](https://github.com/amix/vimrc)

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
# TMUX
https://gist.github.com/MohamedAlaa/2961058
# Resize panes
### VIM
```
Ctrl+W +/-: increase/decrease height (ex. 20<C-w>+)
Ctrl+W >/<: increase/decrease width (ex. 30<C-w><)
Ctrl+W _: set height (ex. 50<C-w>_)
Ctrl+W |: set width (ex. 50<C-w>|)
Ctrl+W =: equalize width and height of all windows
```
### tmux
```
cntrl+a + arrows
```
