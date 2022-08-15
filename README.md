[![Binder](https://binder.cs.rcos.nii.ac.jp/badge_logo.svg)](https://binder.cs.rcos.nii.ac.jp/v2/gh/kishiyamat/r-stats-hands-on/HEAD)

# 『Rで学ぶ統計学入門』勉強会(受講者ガイド)

## 概要

-   『Rで学ぶ統計学入門』を教科書として統計学の基本(t検定まで)と
    初歩的、応用（8章までと補足）を進める。

-   ゴールは統計の全体像を掴んで、とりあえず与えられたデータに対して
    適切な手法を選択、実行できるようになること

-   **統計学の厳密な部分には立ち入らない**

    -   こういうケースで何をすればいいのか、の説明のみ
    -   より細かく知りたい場合は教科書の該当部分を参照

## 全体のアウトライン

Day0

-   R/RStudio

Day1

-   t検定
-   補足: t検定と線形モデル
-   ANOVA

Day2

-   GLM
-   ランダム構造
-   モデル選択


## 進め方

以下の「ノート」と「Day1」、「Day2」はリンクが付いているので、クリックすると遷移します。

1. Day0環境構築なので各自[ノート](https://github.com/kishiyamat/r-stats-hands-on/blob/main/notes/day0.md)を参考にしながら事前準備
1. [Day1](https://drive.google.com/file/d/13e8Q5TsYXYbDSVtw1h2MZJJ66tRu-MSc/view?usp=sharing)と[Day2]()は動画を見て学習

## 補足

-   チュートリアルが終わり、環境を手元に作りたい方は[RStudioのドキュメント](https://www.rstudio.com/products/rstudio/download/)を参照すると良いと思います
-   動画を見ても不明な点がある際は[東大RAの質問受付フォーム]()にご記入して回答を得てください。その際「動画のここまではわかったが...」のような形で参照していただけるとお答えしやすいかと思います。
-   Day2のBackward Eliminationでランダム効果を削る順番が実際のデータと異なっていますが、分析したデータが異なるためです。最新版では順序が修正されています。

# 参照

- [Rで学ぶ統計学入門 - 株式会社東京化学同人](http://www.tkd-pbl.com/book/b279683.html) を利用して統計のチュートリアル
- [オンライン分析システム（実証実験）](https://meatwiki.nii.ac.jp/confluence/pages/viewpage.action?pageId=48137275)
- [Zero-to-Binder](https://the-turing-way.netlify.app/communication/binder/zero-to-binder.html)
    - Helps you create a Binder project from scratch.
