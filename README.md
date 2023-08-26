## 環境構築方法
仕様と環境
- Dockerを使用します。
- DBはpostgres 12を使用します。

## 手順

1. リポジトリのクローン
```
git clone git@github.com:tsmog52/rails-docker.git
```

2. コンテナの立ち上げ(再構築)
```
docker-compose up --build
```

3. 動作確認
ブラウザ上で`localhost:3000`に接続しアプリケーションが表示されればOK

次回からはのコンテナの立ち上げは以下のコマンドのみで実行
```
docker-compose up
```

