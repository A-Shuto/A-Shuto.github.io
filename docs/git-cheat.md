---
layout: page
title: "git cheat"
permalink: /git-cheat
---
# gitの使い方
# 1.ホストの設定
　以下のようにしてホストを設定する．メールアドレスなどは「a@b.c」などのよう実在しないものでも構わない
  git config –global  
  git config –global user.name yourname  
  git config –global user.email yourname@example.com

# 2.gitの設定
　以下のようにgitを初期化，設定開始する  
　$git init  

　以下はそれぞれ，ワークツリーのステータス表示，設定の確認，ログの表示ができる  
　$git status  
　$git config  
　$git log

　また，以下のコマンドでブランチを作成し，作業を分担できる  
　$git branch

# 3.ファイルの変更
　ファイルの内容を変更した後，以下のコマンドでファイルの変更をステージングする  
　$git add

　ステージングされた変更は以下のコマンドでコミットできる  
　$git commit

# 4.変更を反映
　以下のコマンドで変更をアップロード(プッシュ)する  
　$git push

　以下のコマンドでリモートレポジトリと同期させる(プッシュ)  
　$git pull
