# Git Boot Camp

## コマンド

[status]
  showUntrackedFiles = all

これを記載すると、 `git status` でUntrackedなフォルダ以下のファイルも表示されるようになる

## SourceTree

### git commit --amend

対象の一つ前のコミットを右クリックより、 `<コミット番号>の子を対話ベースでリベース` を実行

### git reset --hard

1. 戻したいコミットを右クリックより、 `このコミットまで<ブランチ名>を元に戻す` を実行
1. モードを「Hard」にしOK

### git pull --rebase

1. プル実行
1. プルのメニューより、 `マージではなくリベースする` にチェックを入れOK

### git merge --squash
