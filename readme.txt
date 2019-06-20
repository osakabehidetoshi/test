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

 1)$ git init   #ローカルリポジトリを作成する
 2)$git add .  #  #ローカルリポジトリにファイルの変更点を追加（インデックスに追加）
 2)$ git add <filename>

 3) $git status  #状態確認。随時作成

 4)$git commit -m "first commit" #ローカルリポジトリにインデックスに追加したファイルを登録
 5)$git log #コミットログの確認

#GitHubにプッシュ
 (1)GitHubアカウント作成
 (2)通信は暗号化しましょう。SSHkeyの設定
 (3)レポジトリの作成
 (4)GitHubへのpush

4)インデックス（ファイルの変更点などのリスト？）をGitHubに作成．
   $ git remote add origin https://github.com/<username>/first_app.git

5) $ git push -u origin master #コミットされたデータをGitHubに送信（プッシュ）
     or 
   $ git push origin master    #コミットされたデータをGitHubに送信（プッシュ）


〇プッシュしたデータを変更・更新してみる
  0) fileを編集する。
  1）$ git add test.txt  #変更をインデックスに追加
  2）$ git commit -m "変更してみたよ" #ファイルを登録（コミット）
  3）$ git push origin master #データの送信


〇その他参考コマンド
　$git status    #コミット待ちファイルの表示
  $git checkout  #check out
  $git push      #リモートレポジトリコミット