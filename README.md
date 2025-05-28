# my-bubuntu-custom

![изображение](https://github.com/user-attachments/assets/0dda273e-1996-42a2-92c2-5ff4a56cb461)

# install Zsh

sudo apt install zsh -y

## and add Zsh default shell

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
![изображение](https://github.com/kiomich/my-bubuntu-custom/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202025-05-28%2023-00-54.png)
