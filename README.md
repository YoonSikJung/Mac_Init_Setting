## Install homebrew
You can find how to intall in website.
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
And below command is to set the environment for homebrew.
This is for zsh setting.
```bash
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/yoon/.zprofile
```
 
## Install packages using brew
This is my packages
```bash
brew install node vim tig
```
After install, you can check what package is installed.
```bash
yoon@yoonui-MacBookPro ~ % brew list
==> Formulae
brotli		c-ares		ca-certificates	icu4c		libnghttp2	libuv		node		openssl@1.1
```

## oh-my-zsh
How to install
```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
### plugin
zsh-autosuggestions
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
how to apply it
```bash
vi ~/.zshrc
 pligins=( 
 	git
    	autojump
    	zsh-autosuggestion
    	zsh-syntax-highlighting
 )
```
zsh-syntax-highlighting
```bash
brew install zsh-syntax-highlighting
```
how to apply
```bash
source /opt/homebrew/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```
Or insert it to .zshrc


