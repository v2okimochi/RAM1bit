# Tmuxの神

- キーバインド `Ctrl B`の後にコマンドを打つ
- `~/.tmux.conf`での設定

        # マウスで操作可能にする＆ドラッグでコピーできるようにする
        set-option -g mouse on
        setw -g mode-keys vi
        bind-key -T copy-mode-vi MouseDragEnd1Pane send-keys -X copy-pipe-and-cancel "reattach-to-user-namespace pbcopy"

- ペイン操作

    横に分割

    `"`

    縦に分割

    `%`

- ウィンドウ操作

    ウィンドウを新規作成

    `c`

    ウィンドウ一覧を表示（移動もできる）

    `w`

    ウィンドウ名を変更

    `,`

    ウィンドウ移動（番号や名前を先頭部分一致）

    `'`