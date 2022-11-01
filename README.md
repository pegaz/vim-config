# vim-config

1. Clone the repository and move its content to `~/vim`:
```
$ git clone https://github.com/pegaz/vim-config.git
$ mv vim-config/ .vim/
```

2. Install vim-plug:
```
$ curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

3. Create a symlink to `.vimrc`:
```
$ ln -s ~/.vim/.vimrc ~/.vimrc
```

4. Open `vim` and install plugins:
```
:PlugInstall
```

Ref: https://www.freecodecamp.org/news/vimrc-configuration-guide-customize-your-vim-editor/
