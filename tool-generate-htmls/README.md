# tool-generate-htmls

docs内を全てHTMLに変換するツールです。

## セットアップ方法

コマンドラインで次の命令を実行して、必要なモジュールをダウンロードします。

```
npm install
```

TypeScriptのコンパイルで、上記コマンドを実行して「typings/」フォルダが生成されない場合は、下記コマンドを入力してください。
```
npm run postinstall 
```

## 使い方

### HTMLを生成する
コマンドラインで次の命令を実行して、「finish!!!」と表示されるまで待ちます。

```
node index
```

### TypeScriptのコンパイル
1. TypeScriptを編集してTypeScriptのコンパイルのみ行いたい場合は下記を実行します。

```
npm run compile-ts
```

2. TypeScriptのコンパイルとHTMLの生成の両方を実行する場合は下記を実行します。

```
npm run build
```

