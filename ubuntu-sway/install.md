# Ubuntu Sway Install

## Prerequisites

# კლავიატურა

- კლავიატურის კონფიგურირება ხდება ~/.config/sway/config.d/00-keyboard.conf

# upgrade
 თავისთავად გვინდა აპგრეიდი

# nvim
 vim და nvim არის ძველი, ამიტომ უნდა განვაახლოთ რეპოზიტორებიც
sudo add-apt-repository ppa:neovim-ppa/unstable
sudo apt update
sudo apt install neovim

# yarn
sudo apt install curl
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update
sudo apt install yarn

# nodejs
sudo apt install nodejs
sudo apt install npm

# rust
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

# git
sudo apt install git

 sudo apt install -y git ninja-build gettext libtool libtool-bin autoconf automake cmake g++ pkg-config unzip xclip xsel


# .oh-my-zsh/custom
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions



# nvchad
