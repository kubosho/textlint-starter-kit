# textlint Starter Kit

[textlint](https://github.com/textlint/textlint)のスターターキットです。
このリポジトリーに含んでいるのは、textlint本体とそのプラグインのみです。

## インストール

別途[Node.js](https://nodejs.org/en/)のインストールが必要です。

### zipファイルをダウンロードしてインストール

[Releases](https://github.com/kubosho/textlint-starter-kit/releases)から最新版をダウンロードしてください。
その後、適当なディレクトリでzipを展開します。

### `git clone`でインストール

ターミナルなどで次のコマンドを実行してください。

```shell
git clone https://github.com/kubosho/textlint-starter-kit.git
cd textlint-starter-kit
npm install
```

また、あわせて[Atom](https://atom.io/)というエディターや、その拡張機能である[linter](https://atom.io/packages/linter)と[linter-textlint](https://atom.io/packages/linter-textlint)をインストールするのがいいでしょう。
これらをインストールすれば、Atom上からtextlintが使えるようになり、とても便利です。

## 使い方

Atomを使っているかたは、[linter](https://atom.io/packages/linter)と[linter-textlint](https://atom.io/packages/linter-textlint)さえインストールしておけば、`src`ディレクトリーにテキストやマークダウンファイルを追加することで、textlintによる自動校正がされます。

Atomを使っていないかたは、ターミナルなどで次のコマンドを実行します。このコマンドで`src`ディレクトリー以下にある文書へ対し、textlintが実行されます。

```shell
npm start
```

### ファイルの追加方法

`src`ディレクトリー以下に、テキスト形式やMarkdown形式のファイルを追加します。
追加した後は、`npm start`で`src`ディレクトリー以下にある文書へ対し、textlintが実行されます。

## 貢献する方法

1. フォークします
1. 任意の名前でブランチを作ります：`git checkout -b my-new-feature`
1. 変更した点をコミットします：`git commit -am 'Add some feature'`
1. ブランチをリモートへプッシュします：`git push origin my-new-feature`
1. Pull Requestしましょう :D

## ライセンス

MIT License
