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
#### Install vim plugins
```
cd ~/.vim_runtime
git clone git://github.com/tpope/vim-rails.git my_plugins/vim-rails
```

### tmux
```
cntrl+a + arrows
```
#### Powerline for tmux
https://github.com/erikw/tmux-powerline
```
cd ~
git clone git@github.com:Shakeebbk/tmux-powerline.git

cd /tmp
wget https://github.com/powerline/powerline/raw/develop/font/PowerlineSymbols.otf
wget https://github.com/powerline/powerline/raw/develop/font/10-powerline-symbols.conf
mkdir ~/.local/share/fonts
mv PowerlineSymbols.otf ~/.local/share/fonts
fc-cache -vf ~/.local/share/fonts/
ls ~/.config/fontconfig/conf.d/
mkdir ~/.config/fontconfig/conf.d/
mkdir ~/.config/fontconfig/conf.d/ -p
mv 10-powerline-symbols.conf ~/.config/fontconfig/conf.d/
```

### ZSH - oh my zsh + powerline
https://gist.github.com/renshuki/3cf3de6e7f00fa7e744a
https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions#step-1-install-powerlevel9k
https://powerline.readthedocs.io/en/latest/installation/linux.html#fonts-installation

