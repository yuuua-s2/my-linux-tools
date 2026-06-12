# my-linux-tools
Linuxの授業で作成した
## showpath
⾃作コマンド集です。
PATH
の中⾝を 
1
⾏ずつ 表⽰します

alias pco='echo $PATH | tr ":" "/n" | cat -n'
