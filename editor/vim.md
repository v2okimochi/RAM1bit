# Vimの神

insert modeからvim modeになる： `Escape`または `Ctrl + [`

- オプション（ `:`）

    行番号を表示

    `:set number`

    ペインを横に切る

    `:split`

    ペインを縦に切る

    `:vsplit`

- vim modeでの操作

    ## insert mode

    カーソル位置からinsert mode: `i`

    カーソル位置の1文字後からinsert mode: `a`

    カーソル位置から改行してinsert mode: `o`

    カーソル位置の上に改行してinsert mode: `Shift + o`

    ## 切り取り・貼り付け

    1文字切り取り： `x`

    カーソル行を切り取り： `d d`

    カーソル行から3行を切り取り： `3 d d` 

    ## 範囲選択モード（同じコマンドでモードを抜ける）

    1文字単位で選択モード： `v`

    行単位で選択モード： `Shift + v`

- [オブジェクト操作](https://qiita.com/kasei-san/items/143af11bb2559cf0e540)（c, d, y）

    [`コマンド + 回数指定 + オブジェクトの種類の指定`]に従う。

    カーソル上の単語を消して入力を始める（変更）： `c w`

    直前の操作を実行（insert modeに入ってから出るまでの操作）： `.`