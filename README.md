## Only for MAC

### install iterm2
```
https://iterm2.com/downloads.html
```

### install homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
https://brew.sh/
```

### install oh-my-zsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
https://github.com/ohmyzsh/ohmyzsh
```

### install powerline9k
```
brew tap sambadevi/powerlevel9k
brew install powerlevel9k
sudo   echo "source /usr/local/opt/powerlevel9k/powerlevel9k.zsh-theme" >> ~/.zshrc
git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k
vim ~/.zshrc,  change theme to ZSH_THEME="powerlevel9k/powerlevel9k"
```

### install powerline fonts
```
git clone https://github.com/powerline/fonts.git --depth=1
cd fonts
./install.sh
cd ..; rm -rf fonts

iterm preferances => profiles => Text => Font (Source code pro for powerlevel9k)
iterm preferances => profiles => Text => color presets (Solarized Dark)
```

### material design
```
https://github.com/MartinSeeler/iterm2-material-design
download
iTerm2 > Preferences > Profiles > Colors Tab
Click Color Presets...
Click Import...
Select the material-design-colors.itermcolors file
```
