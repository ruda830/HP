# これはgitの練習用ファイルです。
push,fetch,pullの練習。リポジトリ名変更の練習。ファイル削除の練習をしています。

git global設定で username emailをgithub上のモノと同じに  
→設定後、git repository settingでもgithub上のユーザーアカウントに変更されていた。  
これでローカルでのコミットも同アカウントで認識される。  

(2020/1/3)
branchの練習
local上でbranch_first_localを作製。これ上でhello.txtを新たに追加。
→プッシュしたところ、リモート上でbranch_first_localが作製され、更新された。
→slnx.sqliteのせいでmerge出来ないと言われたので、branch_first_localをベースにbranch_second_localを作り、branch_first_local上でREADMEを書き付け加えた。その後プッシュ(この時点でなぜかslnx.sqliteの変更も一緒に保存された)。  
→github上でプルリクエスト(branch_first_localをmainへ)をしてみる。→try mergeとコメント。→実際にリポジトリ管理者としてmergeした。  
→ここまでをmainのREADMEに書き記した。





(2020/1/3)
branch_second_localにチェックアウトして、この文章を書き足した。
現状　main:branch_first_localをmergeしてREADMEに書き足した最新状態。
現状　branch_second_localはbranch_first_localからbranchしてそのまま、リモート上にこのbranchは作られてない。
  
