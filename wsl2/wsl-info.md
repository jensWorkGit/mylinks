# installation
sudo apt-get install zsh
sudo apt-get install git
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

## themes
### Change to
ZSH_THEME="robbyrussell"

# To this
ZSH_THEME="agnoster"

# zsh with conemu (windows)
https://blog.joaograssi.com/windows-subsystem-for-linux-with-oh-my-zsh-conemu/

sed -i '0,/blue/{s/blue/39d/}' ~/.oh-my-zsh/themes/agnoster.zsh-theme

https://pascalnaber.wordpress.com/2019/10/05/have-a-great-looking-terminal-and-a-more-effective-shell-with-oh-my-zsh-on-wsl-2-using-windows/

## auto suggestions in zsh
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

## fonts
git clone https://github.com/powerline/fonts.git