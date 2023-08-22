**vim(vi)をインストールする**
```bash
apt install vim
```
<br>

**カーソルキー,バックスペースを使えるようにする**
```bash
vi ~/.vimrc

echo -e "set nocompatible\nset backspace=indent,eol,start > ~/.vimrc
```
