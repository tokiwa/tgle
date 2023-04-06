# TGLE

## 概要

TGLEは Tools for Group Learning Envoronmentの略で文字通りグループ学習の環境を支援するツールです。
次のモジュールから構成されており、教員と学習者が投稿したキーワード間の類似度を計算し、そのデータを用いてグループ分けをする機能を提供します。
- Front-End: PHP + Vue
- Back-End: PHP + Laravel
- mkgroup: Python + Flask
- similarity(w2v): Python + Flask

TGLEはLTI 1.3ツールとして開発されており、Moodle等のLMSをPlatformとしてその機能を拡張します。

![TGLEシステム構成図](TGLE.jpg)


## GitHub構成

それぞれのモジュールは。次に示すように別々のリポジトリで管理され、git submoduleにて関連付けられています。
- TGLE TOP: tgle
- Front-End: tgle-be
- Back-End: tgle-fe
- mkgroup: tgle-mkgroup
- similarit(w2v)): tgle-similarity


## 利用

次の活用を想定しています。

1. LMSと連携したグループ形成ツール
1. REST APIを学習するための教材
1. 製品化する前のプロトタイピング

## 謝辞

本研究はJSPS 科研費 18K11581 の助成を受けたものです．

![科研費](KAKENHIlogo_S.jpg)