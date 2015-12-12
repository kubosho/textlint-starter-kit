# textlint Starter Kit

[textlint](https://github.com/textlint/textlint)のスターターキットです。
このリポジトリーに含んでいるのは、textlint本体とそのプラグインのみです。

## インストール

別途[Node.js](https://nodejs.org/en/)のインストールが必要です。
Node.jsは特にこだわりがなければStable版をインストールします。
Node.jsをインストールしている方は、次に挙げるどちらかのインストール方法でtextlintを使えるようにします。

1. <a href="#zipファイルをダウンロードしてインストール">zipファイルをダウンロードしてインストール</a>（Gitに慣れていない方）
2. <a href="#git-cloneでインストール">`git clone`でインストール</a>（Gitを使いこなせる方）

### zipファイルをダウンロードしてインストール

Gitに慣れていない方向けのインストール方法です。

[Releases](https://github.com/kubosho/textlint-starter-kit/releases)から最新版をダウンロードしてください。
その後zipを展開します。展開したらそのディレクトリー配下にあるファイルやディレクトリーを適当なところにコピー&ペーストします。

### `git clone`でインストール

Gitを使いこなせる方向けのインストール方法です。

ターミナルや任意のGitを扱えるソフトウェアなどで次のコマンドを実行してください。

```shell
git clone https://github.com/kubosho/textlint-starter-kit.git
cd textlint-starter-kit
npm install
```

### Atom上でtextlintを使えるようにする

テキストエディターとして[Atom](https://atom.io/)を使う場合は、拡張パッケージのインストールをすることで、ターミナルなどの操作なくtextlintを使うことができます。
インストールする拡張パッケージは次の2つです。

- [linter](https://atom.io/packages/linter)
- [linter-textlint](https://atom.io/packages/linter-textlint)

これらをインストールすれば、Atom上からtextlintが使えるようになり、とても便利です。
拡張パッケージのインストールについては、次のリンクを参考にしてください。

- [Atomでパッケージをインストールする方法とメニューの日本語化 – nocorica](http://blog.nocorica.jp/2015/03/atom-package-install/)
- [#11 パッケージを導入してみよう | Atom入門 - プログラミングならドットインストール](http://dotinstall.com/lessons/basic_atom/30510)

## 使い方

いずれの説明も、前提はtextlint-starter-kitをインストールしたディレクトリー上に`src`ディレクトリーがあることです。

- Atomと前述のAtom拡張パッケージをインストールした方は、`src`ディレクトリーにテキストやマークダウンファイルを追加することで、文章の自動校正がおこなえます。
- Atomを使っていないかたは、ターミナルなどで次のコマンドを実行します。このコマンドで`src`ディレクトリー以下にある文書へ対し、textlintが実行されます。

```shell
npm start
```

## 貢献する方法

1. フォークします
1. 任意の名前でブランチを作ります：`git checkout -b my-new-feature`
1. 変更した点をコミットします：`git commit -am 'Add some feature'`
1. ブランチをリモートへプッシュします：`git push origin my-new-feature`
1. Pull Requestしましょう :D

## ライセンス

MIT License
