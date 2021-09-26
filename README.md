### Hackintosh EFI

### Tool setup

#### Command Line Tool

##### Install iTerm2

##### Install zsh

##### Install ohmyzsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

##### Install powerlevel10k theme
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

##### Install custom fonts

##### Copy powerlevel10k configuration to .zshrc

![iTerm Preview](/images/iterm-preview-2.png)

#### Xcode
##### Theme and Key binding
Go to ~/Library/Developer/Xcode/UserData/FontAndColorThemes then copy those 2 files .idekeybindings and .xccolortheme
