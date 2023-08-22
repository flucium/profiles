**ZSHをインストールする**
```bash
apt update && apt upgrade

chsh #シェルをzshに変更する．zshのパスを指定する．

# rebootしておく．
```

<br>

**ZSHのプロンプトを設定する**
```bash
vi ~/.zshrc
```

`prompt adam1`をコメントアウトして，`PROMPT=""`を追加する．
```
#prompt adam1
PROMPT="%K{blue}%n@%M%k %K{cyan}%c%k %# "
```

<br>

シェルをリスタートする．
```bash
exec $SHELL -l
reset
```

