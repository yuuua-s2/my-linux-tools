# my-linux-tools
Linuxの授業で作成した⾃作コマンド集です。
## showpath
PATHの中⾝を1⾏ずつ表⽰します

alias pco='echo $PATH | tr ":" "/n" | cat -n'

実はここでもOK

検索するコマンド
find . -type d -name ".git"
