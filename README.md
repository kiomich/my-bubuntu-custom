# my-bubuntu-custom

![изображение](https://github.com/user-attachments/assets/0dda273e-1996-42a2-92c2-5ff4a56cb461)

# install Zsh

sudo apt install zsh -y

#and add Zsh default shell

chsh -s $(which zsh)

# install Oh My Zsh

## With curl:

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

## With wget:

sh -c "$(wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh

# install Powerlevel10k(beautiful theme for Zsh)

git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

# open

nano ~/.zshrc

replacement ZSH_THEME="robbyrussell" in ZSH_THEME="powerlevel10k/powerlevel10k"

# download in https://extensions.gnome.org/

Снимок экрана от 2025-05-28 23-00-54.png
