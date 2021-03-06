# 開発環境構築手順
1. プロジェクトのルートディレクトリで以下を実施する
    ```
    $ npm install
    ```
2. strongloopをインストール
    ```
    $ npm install -g strongloop
    ```
3. MongoDBをHome Brewからインストールする
    ```
    $ brew install mongodb
    ```
4. MongoDBをサービスへ登録し、PC起動時に起動するようにする
    ```
    $ brew services start mongodb
    ```

# サーバのスタート
1. プロジェクトのルートディレクトリで以下を実行する
    ```
    $ npm start
    ```
2. 以下のURLからAPIのリファレンスページに移動する
    ```
    http://localhost:3000/explorer
    ```

# テストの実行方法
以下のコマンドをプロジェクトのルートディレクトリで実行する
```
$ node_modules/mocha/bin/mocha --reporter spec test
```

# 依存モジュールのバージョン情報
* node:10.16.0
* npm:6.9.0
* MongoDB:4.0.3

The project is generated by [LoopBack](http://loopback.io).