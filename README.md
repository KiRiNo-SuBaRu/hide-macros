# hide-macros

秀丸エディタ専用マクロ関連の開発・試作・整備を行うための作業用プロジェクト領域です。

このリポジトリでは、秀丸エディタ上で動作する各種マクロの作成、改良、検証、ドキュメント整備を行います。  
個々のマクロはサブディレクトリごとに管理し、必要に応じて個別の README や補足資料を配置します。

## 目的

- 秀丸エディタ用マクロの開発
- マクロごとの仕様整理
- README や利用手順の整備
- 動作確認用の補助ファイル管理

## ディレクトリ構成

```text
hide-macros/
├─ README.md
├─ LICENSE
└─ auto-surround_with_brackets_or_block-comment-delimiters/
   ├─ README.md
   ├─ auto-surround_with_brackets_or_block-comment-delimiters.mac
   └─ docs/
```

## 収録内容

- `auto-surround_with_brackets_or_block-comment-delimiters/`
  - 範囲選択した文字列や複数行を、対括弧・コメント区切り記号・環境変数形式で囲む秀丸マクロ

## 利用方法

各マクロの使い方、登録方法、動作条件は、それぞれのサブディレクトリ内にある `README.md` を参照してください。

## 対象

- 秀丸エディタを利用しているユーザー
- 秀丸エディタ用マクロを自作・改造したいユーザー
- マクロの実装例や運用例を参照したいユーザー

## 作者

霧野昴 (Subaru Kirino)

## ライセンス

本リポジトリは MIT License のもとで公開します。  
詳細は `LICENSE` ファイルを参照してください。