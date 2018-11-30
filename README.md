sourcetreeで以下のコマンドの使い方

[git commit --amend]
    コミットタブを開き、コミットコメント右上の「コミットオプションを指定」から「最新のコミットを修正」

[git reset --hard]
    対象のコミットを右クリック(ctrl + Lclick)する。
    このコミットまで、[branch]を戻す。　その後、オプションで[hard]を指定する

[git pull --rebase]
    上部メニューから、[プル]を選択し、「マージではなく、リベースする」のオプションにチェックを入れる

[git reset --mixed]
    対象のコミットを右クリック(ctrl + Lclick)する。
    このコミットまで、[branch]を戻す。　その後、オプションで[mixed]を指定する

[git reset --soft]
    対象のコミットを右クリック(ctrl + Lclick)する。
    このコミットまで、[branch]を戻す。　その後、オプションで[soft]を指定する

[git merge --no-ff]
    上部メニューから、[マージ]を選択し、「"fast-forward"可能でも新たなコミットを作成する」オプションにチェックを入れる

[git rebase --i]
    起点となるコミットを右クリック(ctrl + Lclick)する。
    「〜〜の子を対話式でリベース」