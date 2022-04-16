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

## Install node
we can use brew to install node
```bash
brew install node
```
After install, you can check what package is installed.
```bash
yoon@yoonui-MacBookPro ~ % brew list
==> Formulae
brotli		c-ares		ca-certificates	icu4c		libnghttp2	libuv		node		openssl@1.1
```

## oh-my-zsh
```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
