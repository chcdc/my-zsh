## My zsh

#### Install package zsh
Like Ubuntu/Debian/Mint
```bash
apt-get update && apt-get install git vim-nox zsh zsh-syntax-highlighting
```

Like RHEL/CentOS
```bash
yum install zsh git
```

Like Suse
```bash
zypper in zsh git
```

#### Install framework oh-my-zsh
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

#### Install Fonts Hack
```bash
git clone https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/Hack.zip
unzip Hack.zip ~/.fonts/
```

#### Install Theme powerlevel10k
```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>! ~/.zshrc
```

#### Copy the repo
```bash
git clone https://github.com/chcdc/zsh.git --depth=1
mv .zshrc ~/
source ~/.zshrc
```

More links
[Wiki](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)
[Plugins](https://github.com/unixorn/awesome-zsh-plugins#plugins)

