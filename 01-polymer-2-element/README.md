# \<polymer-2-element\>


## bower_components　のインストール

```
bouwer init
```

## Build

ビルドはコマンドプロンプトで以下を実行

```
polymer build
```
buildフォルダ配下にIE11で実行可能なソースが作成されます。
運用環境にはbuild配下のソースを配置します。


## 単体テストの実行

コマンドプロンプトで以下を実行
```
polymer test
```

単体テストが動作しない場合には以下のコマンドを入力してテスターをインストール
```
npm install -g web-component-tester
```

