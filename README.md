#

## テスト方法

### 1.GitHub の招待を受ける

GitHub のリポジトリのページに行き、Setting から Collaborators へと移動する。

Add people のボタンから招待を送ってもらう。

### 2.リポジトリをローカル環境に複製

ターミナルで　 git clone [リポジトリパス]

### 3.外部ファイルのインストール

ターミナルで　 npm install

### 4..env ファイルの修正

以下の 4 箇所を修正

APP_NAME=ToDo アプリ

DB_DATABASE=laravel_todo_app

DB_PASSWORD=root

DB_SOCKET=/Applications/MAMP/tmp/mysql/mysql.sock

### 5.データベースの作成

phpMyAdmin で laravel_todo_app という名前のデータベースを作成

### 6.マイグレーション

ターミナルで　 php artisan migrate:fresh
