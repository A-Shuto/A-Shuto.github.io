gitの流れ  
git pull でリモートレポジトリの変更をローカルレポジトリに反映させる．  
ローカルレポジトリでファイルを編集  
git add でステージングエリアにファイルを登録  
git commit でステージングエリアに登録されたファイルの変更をgitで管理する  
git push でコミットされたファイルの変更をリモートレポジトリに登録  
git pull-request で共同制作者(ほかのブランチ)に対してgit pullを行うよう要求できる  

以下，簡単なコマンド一覧  
gitのオーナーの初期設定  
    git config –global  
    git config –global user.name yourname  
    git config –global user.email yourname@example.com  

gitの初期化・設定開始  
    git init  
ワークツリーのステータスを表示  
    git status  
設定周りの確認・変更  
    git config   
ログを表示-- onelineでコミットメッセージの1行のみの一覧表示  
    git log  
ファイルの差分を表示  
    git diff  

コミットの修正  
    git commit --amend --no-edit  
削除されたファイルを復旧や過去コミットの復元など（元に戻す変更がstaging area/index内にある場合）  
    git checkout  
コミットのリセット  
    git reset  
「コミットの変更を打ち消す」コミット  
    git revert  
ファイルとindex情報の削除  
    git rm  

レポジトリをコピー  
    git clone  
リモートレポジトリの同期  	
    git pull  
変更をアップロードする  
    git push  
プルリクエスト：変更依頼  
    git request-pull  
リモートレポジトリの設定  
    git remote  

ブランチの作成  
    git branch  
ブランチの切り替え  
    git checkout  
ブランチの統合  
    git merge  
レポジトリをコピー  
    git clone  
変更をアップロードする  
    git push  
