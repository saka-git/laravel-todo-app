#

## テスト方法

### 1.GitHub の招待を受ける

GitHub のリポジトリのページに行き、Setting から Collaborators へと移動する。

Add people のボタンから招待を送ってもらう。

### 2.リポジトリをローカル環境に複製

git clone [リポジトリパス]

### 3.外部ファイルのインストール

### 4..env ファイルの修正

### 5.データベースの作成

### 6.マイグレーション

#### .env ファイル

APP_NAME=ToDo アプリ
APP_ENV=local
APP_KEY=base64:rThxim3hRY38SgUExITQGlwZx/kkhFvalp18+voavBA=
APP_DEBUG=true
APP_URL=http://localhost

LOG_CHANNEL=stack
LOG_DEPRECATIONS_CHANNEL=null
LOG_LEVEL=debug

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_todo_app
DB_USERNAME=root
DB_PASSWORD=root
DB_SOCKET=/Applications/MAMP/tmp/mysql/mysql.sock

BROADCAST_DRIVER=log
CACHE_DRIVER=file
FILESYSTEM_DISK=local
QUEUE_CONNECTION=sync
SESSION_DRIVER=file
SESSION_LIFETIME=120

MEMCACHED_HOST=127.0.0.1

REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_MAILER=smtp
MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USERNAME=sakamoto.tatsuya1997a@gmail.com
MAIL_PASSWORD=zslwxymvpnfmkbpz
MAIL_ENCRYPTION=tls
MAIL_FROM_ADDRESS=sakamoto.tatsuya1997a@gmail.com

MAIL_FROM_NAME="${APP_NAME}"

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_DEFAULT_REGION=us-east-1
AWS_BUCKET=
AWS_USE_PATH_STYLE_ENDPOINT=false

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=
PUSHER_HOST=
PUSHER_PORT=443
PUSHER_SCHEME=https
PUSHER_APP_CLUSTER=mt1

VITE_PUSHER_APP_KEY="${PUSHER_APP_KEY}"
VITE_PUSHER_HOST="${PUSHER_HOST}"
VITE_PUSHER_PORT="${PUSHER_PORT}"
VITE_PUSHER_SCHEME="${PUSHER_SCHEME}"
VITE_PUSHER_APP_CLUSTER="${PUSHER_APP_CLUSTER}"
