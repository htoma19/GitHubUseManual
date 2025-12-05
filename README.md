# GitHub利用の流れ
 ## 1. 変更したファイルを全て選択する
 - git add .

 ## 2. 「最初のセーブ」という名前をつけて保存（コミット）する
 - git commit -m "First commit: 環境構築完了とドキュメント作成"

## 3. ブランチ名を main に設定する（念のため）
 - git branch -M main

## 4. GitHubの箱とあなたのPCを繋ぐ
### ★注意: 下のURLは、さっきGitHubで作ったあなたのURLに書き換えてください！
 - git remote add origin https://github.com/あなたのユーザー名/MyKakeiboApp.git

## 5. インターネット上にアップロード（プッシュ）する
 - git push -u origin main
