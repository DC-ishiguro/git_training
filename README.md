# gitの操作
- add  
    * ファイルを挙げる(ステージング)
- commit -m(コメント)
    * コミットし、ローカルリポジトリに移す。  
    * 取り消したい場合は、commit -amend -mでコメントを書き換えられる。
- git (branch名)  
    * branchを作成
    * 名前を変えたい場合は、git branch -m (branch名)  
    * branchを消す場合は、git branch -d (branch名)
- checkout (branch名)
    * branchを変えたい場合
    * git switchでいいのでは？
- git switch (branch名)
    * ブランチを変える。
    * 新しいブランチを作成して変える場合、git switch -c (branch名)
    * ブランチを上書きして変える場合、git switch -C (branch名)
- git diff  
    * 差分を見たい場合
- git mv (変更前のファイル名) (変更後のファイル名)  
    * ファイル名を変えたい場合
    a