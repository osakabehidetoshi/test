https://github.com/osakabehidetoshi/test
https://github.com/osakabehidetoshi/test.git

#gitの初期設定

$ git config --global user.name "ユーザ名"
$ git config --global user.email メールアドレス

#editerの設定
$　git config --global core.editor "vim -f"


#…or create a new repository on the command line

#gitの初期化
　#作業フォルダ作成
    $ mkdir gittest
    $ cd gittest
  #git initialize
    $ git init
    $git add README.md
1）ローカルリポジトリを作成する
    $ git init

    $git status  #状態確認。随時作成

2）ローカルリポジトリにファイルの変更点を追加（インデックスに追加）
    $ git add .  # $ git add <filename>

3）ローカルリポジトリにインデックスに追加したファイルを登録
    $git commit -m "first commit"

4)コミットログの確認
    $git log

#GitHubにプッシュ
 (1)GitHubアカウント作成
 (2)通信は暗号化しましょう。SSHkeyの設定
 (3)レポジトリの作成
 (4)GitHubへのpush

4)インデックス（ファイルの変更点などのリスト？）をGitHubに作成．
   $ git remote add origin https://github.com/<username>/first_app.git

5)コミットされたデータをGitHubに送信（プッシュ）します．
   $ git push -u origin master
     or 
   $ git push origin master


〇プッシュしたデータを変更・更新してみる
0) fileを編集する。

1）変更をインデックスに追加
　　$ git add test.txt

2）ファイルを登録（コミット）
　　$ git commit -m "変更してみたよ"

3）データの送信
　　$ git push origin master



