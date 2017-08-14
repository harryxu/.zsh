```
brew install zsh zsh-completions
chsh -s /usr/local/bin/zsh

cd ~
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
npm install --global pure-prompt
git clone https://github.com/harryxu/.zsh.git
rm .zshrc
ln -s ~/.zsh/zshrc ~/.zshrc
```

REF:

http://zsh.sourceforge.net/

http://ohmyz.sh/

https://github.com/zsh-users/zsh-completions/

https://github.com/sindresorhus/pure/

