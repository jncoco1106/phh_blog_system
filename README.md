# 初期化手順
1. GitHub で Fork する
1. `$ git clone クローンする URL ` とする
1. `$ cd クローンしたディレクトリ名`
1. `$ npm init` として初期化する
1. `$ mysql.server start` として MySQL サーバーを立ち上げる
1. `$ mysql -uroot -p < schema.sql` として データベースを初期化する 
1. `$ node index.js`
1. Web ブラウザから `http://localhost:8000` にアクセスして動作を確認する

# 既知のバグ（これを実装していく）
+ タグの追加が出来ない
+ 記事の投稿が出来ない
+ 記事の変更が出来ない
+ 記事の削除が出来ない
+ ページング（ページ送り）が正しく動作していない
+ プロフィールの変更が出来ない
+ 血液型の選択が出来ない

# 課題
+ デザインを変更する
+ 機能を追加する（画像のアップロード、カレンダーなど）
+ セキュリティを強化する（ログイン機能など）
+ ユーザー登録機能を作って複数ユーザーに対応する
