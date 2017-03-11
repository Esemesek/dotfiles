# Welcome to my vim and tmux configuration
### How to install?
* Install [Vundle]
```bash
$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
* Clone this repository and copy configuration files into your home folder
```bash
$ git clone https://github.com/Esemesek/config.git
$ cp config/.gitconfig config/.tmux.conf config/.vimrc~.
```
* Install vim plugins
```bash
$ vim +PluginInstall
```

* Cleanup cloned repository
```bash
$ sudo rm -rf config/
```
### Font
Additionally, I use [Fantasque font] in my terminal for nicer feel.
[Fantasque font]: https://github.com/belluzj/fantasque-sans
[Vundle]: https://github.com/VundleVim/Vundle.vim
