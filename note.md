# note.md

- queryと`mutation`は同時にできない？
- リテラルのgraphqlに対して補完やフォーマットは効かない？
- MongoDB接続失敗の解決
  - <https://stackoverflow.com/questions/55499175/how-to-fix-error-querysrv-erefused-when-connecting-to-mongodb-atlas>
- graphqlでは文字列リテラルは"のみ
- localhost:3000はあえてアクセスできない場所を指定しているっぽい
- Playgroundからdebugするときどうやる？
- ctrl+cするとアプリが残ることがある
  - `lsof -i tcp:4000` , `kill -9 pid` で解決
- currentuserが動作しない
  - node-fetchがインストールされていない？→変わらない
  - 