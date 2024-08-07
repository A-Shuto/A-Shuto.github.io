---
layout: page
title: "git memo"
permalink: /git-memo
---
# gitの概要
# gitとは
　gitとは分散管理型のバージョン管理システムである．
・変更履歴が残る
・変更した箇所に戻ることができる
・他人と共同編集できる
という特徴がある．  

# 用語解説
＜レポジトリ＞  
　gitが管理するプロジェクトのフォルダをレポジトリと呼ぶ．個々の編集者が自身の環境下で用いるレポジトリを「ローカルレポジトリ」，それらがアップロードされる共有の管理場所を「リモートレポジトリ」と呼ぶ．  
  
＜コミット＞  
　ファイルに対する変更を保存して，gitに登録することをコミットと呼ぶ．記録としての役割があり，原則コミットの作業は取り消すことはできない．基本的にローカルレポジトリで行う作業である．  

＜プッシュ・プル＞  
　ローカルレポジトリでコミットされた内容をリモートレポジトリへ反映させる作業をプッシュと呼び，リモートレポジトリにある内容をローカルレポジトリに反映させることをプルと呼ぶ．  
  
＜ブランチ＞  
　git上で作業を分けるために用いられるディレクトリのような分類をブランチと呼ぶ．開発用のブランチでファイル編集を行い，メインブランチに変更を反映させるような作業をgithubフローと呼ぶ．

[トップページ](\docs\)  
[ソフトウェア工学で学んだことまとめ](\software)  
[gitの使い方](\git-cheat)  