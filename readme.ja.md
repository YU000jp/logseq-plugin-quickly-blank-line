# Logseq プラグイン: New Line Shortcut 🦢

1. ショートカットキーを使って、新しい行を簡単に挿入するためのプラグインです。
   > Logseqでは、ブロック参照(行の引用)や埋め込みに入力カーソルを置いていると、改行がしにくい問題が生じます。ショートカットコマンドによって、次の行をすばやく作成します。
> [!NOTE]
このプラグインはLogseq db版で動作します。

<div align="right">

[English](https://github.com/YU000jp/logseq-plugin-blank-line) | [日本語](https://github.com/YU000jp/logseq-plugin-blank-line/blob/main/readme.ja.md) [![最新リリースバージョン](https://img.shields.io/github/v/release/YU000jp/logseq-plugin-blank-line)](https://github.com/YU000jp/logseq-plugin-blank-line/releases) [![ライセンス](https://img.shields.io/github/license/YU000jp/logseq-plugin-blank-line?color=blue)](https://github.com/YU000jp/logseq-plugin-blank-line/LICENSE) [![ダウンロード](https://img.shields.io/github/downloads/YU000jp/logseq-plugin-blank-line/total.svg)](https://github.com/YU000jp/logseq-plugin-blank-line/releases)
  公開日: 2023/08/07 <a href="https://www.buymeacoffee.com/yu000japan"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a pizza&emoji=🍕&slug=yu000japan&button_colour=FFDD00&font_colour=000000&font_family=Poppins&outline_colour=000000&coffee_colour=ffffff" /></a>
</div>

## 概要

### ショートカットコマンド一覧

- 編集中の行から、ショートカットキーでコマンドを実行します。
  1. 前に一行挿入する
    - `Shift` `Alt` `Enter` 同時押し
  1. 次の行を挿入する
      - `Alt` `Enter` 同時押し
  1. 前に複数の行を挿入する
      - `Ctrl` (もしくは`Cmd`) `Pg-Up` 同時押し
  1. 次に複数の行を挿入する
      - `Ctrl` (もしくは`Cmd`) `Pg-Down` 同時押し

- ページ名のメニュー(右クリック)から、次のいずれかを選択します。
  > プラグイン設定で、挿入する行数を指定してください。
  1. (メニュー項目) `🦢 ページの先頭に、複数の行を挿入する ⏫`
     > ページの先頭に、指定した数の行を追加します
  1. (メニュー項目) `🦢 ページの最後尾に、複数の行を挿入する ⏬`
     > ページの最後に、指定した数の行を追加します

- 1つまたは複数の行を選択して、ショートカットキーでコマンドを実行します。
  > 複数の行を選択するには、編集中のブロックで`Esc`キーを押し、ブロック選択状態に切り替えて、`Ctrl`とクリック、もしくは`Shift ↑ ↓`でブロックを選択してください。
  1. 選択したブロックをクリアにする
     > Logseq標準の削除コマンドではブロックごと削除されますが、そうではなく内容のみをクリアします。

---

## はじめに

Logseq マーケットプレイスからインストール

   - 右上のツールバーで [`---`] をクリックして [`プラグイン`] を開きます。`マーケットプレイス` を選択し、検索フィールドに `Blank` と入力し、検索結果から選択してインストールします。

  ![画像](https://github.com/YU000jp/logseq-plugin-blank-line/assets/111847207/668cace9-8da2-4b90-91f7-4353f073c911)

### プラグイン設定

- 空行の挿入数（前）: 選択
  - `1`-`20`
- 空行の挿入数（次）: 選択
  - `1`-`20`
- ページメニューからの空行の挿入数: 選択
  - `1`-`30`

---

## ショーケース / 質問 / アイデア / ヘルプ

> [ディスカッション](https://github.com/YU000jp/logseq-plugin-blank-line/discussions) タブにアクセスして、質問やこれらの種類の情報を見つけて質問してください。

## クレジット

- アイコン > [icooon-mono.com](https://icooon-mono.com/14658-%e3%82%b9%e3%83%af%e3%83%b3%e3%83%9c%e3%83%bc%e3%83%88%e3%81%ae%e7%84%a1%e6%96%99%e3%82%a4%e3%83%a9%e3%82%b9%e3%83%883/)
- 製作者 > [@YU000jp](https://github.com/YU000jp)
- Logseq プラグイン > [@freder/ extra-editing-commands](https://github.com/freder/logseq-plugin-extra-editing-commands)
