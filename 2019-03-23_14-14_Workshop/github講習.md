---
tags:
  - Workshop
  - Git/Github
---

# Git/Github講習会
***
## Gitとは
* バージョン管理ツール
* 機能とメリット
  * ファイルのバージョンを逐一記録。
  * ファイルの変更内容を記録
  * チームワークを円滑に進められる。

### Git initコマンド
* Gitを有効化するコマンド
  > git init

### 変更を保存するまでの３ステップ
1. git status
    * 前回保存時からの変更を教えてくれる。
    * Untracked files: 
1. git add <file name>
    * Gitにどのバージョンを管理して欲しいのかを伝える必要がある。
1. git commit --message <message>
    * 履歴を保存　⇒　コミット
4. git push origin <ブランチ名>
    * github使用時。

### Branch
* Master branch : 本流
* Branch : コピーファイル

### GitとGithub
* Git : バージョンコントロールツール
* Github : バージョンコントロールWebサービス

* Githubに挙げる
  * git push でgithub上のリモートリポジトリへ上がる。
  * git push origin <branch名>


Q. Origin意味
Q. リモートリポジトリとローカルリポジトリでそれぞれマスターがいる？
Q. conflict⇒発生条件
