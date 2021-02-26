# タスク管理アプリ課題

以下の内容でplansテーブルを作成する DDL(CREATE TABLE)を記述して下さい。
|カラム|データ型|Not Null|オプション|デフォルト値|備考|
|:--|:--|:--:|:--:|:--:|:--:|
|id|INT|◯|PRIMARY KEY , AUTO INCREMENT||プランの id|
|title|VARCHAR(255)|◯|||学習内容|
|due_date|DATE|◯|||学習内容の期限|
|status|VARCHAR(10)|||notyet|notyet:未完了 or done: 完了|
|created_at|DATETIME|◯|DEFAULT CURRENT_TIMESTAMP||記事の作成日時|
|updated_at|DATETIME|◯|DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP||記事の編集日時|

## index.php
## config.php
## delete.php
## done.php
## edit.php
## functions.php