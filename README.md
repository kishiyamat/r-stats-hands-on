[![Binder](https://binder.cs.rcos.nii.ac.jp/badge_logo.svg)](https://binder.cs.rcos.nii.ac.jp/v2/gh/kishiyamat/r-stats-hands-on/HEAD)

# 受講者ガイド

目標

- 仮説検証に使う統計のX,Y,Zを理解する
- 手法と、Rに慣れる
- 統計手法を考慮して実験の設計ができる

## 環境構築

このページは、授業・セミナー等でNIIのオンライン分析システムを利用する学生・受講者の方向けの情報を
まとめています。
(基本的に[nii-rcos-ap/受講者ガイド](https://meatwiki.nii.ac.jp/confluence/pages/viewpage.action?pageId=67614937)
をコピーしたものですが、ところどころ変更を加えています。)

RStudio の分析環境をブラウザ上で利用します。
自分のパソコンに分析環境をインストールする必要がありません。
分析環境には、講師が作成したプログラム、データファイル、依存パッケージ等が含まれています。
パッケージを追加でインストールしたりする必要がありません。

本システムを利用するには、ご自身の所属機関（大学等）のアカウントか、
OpenIdP のアカウントが必要です。講師の指示に従って適切なアカウントをご利用ください。
(東大から支給されているアカウントでログインを要求されます。)

講師から伝えられた URL をブラウザで開きます。
ここでは https://binder.cs.rcos.nii.ac.jp/v2/gh/kishiyamat/r-stats-hands-on/main
を使います。

上記のURLをクリックし、NIIのウェブページに移動してください。
その後、所属機関の選択で、ご自身の所属機関または OpenIdP を選び、[選択] ボタンをクリックします。
ご自身の所属機関または OpenIdP のアカウントで認証します。
自分用の分析環境が新たに作られます。
Files の右側にある New → RStudio をクリックします。RStudio が新しいタブで開きます。

## 進め方

このチュートリアルでは
[Rで学ぶ統計学入門 - 株式会社東京化学同人](http://www.tkd-pbl.com/book/b279683.html)
の内容を進めます。本文の内容を新しくスライドに起こす、ということはしません。
学習の助けになるデータを追加する程度です。第一章の内容は `ch01.Rmd` に
載せており、続く章も同様です。
基本的には議論をしたり、手を動かしたりしながら
進めていく形式を想定しています。

部分的に行間を読まなくてはならなかったり、
タイポと思われる部分がありますので、
それらを補う形ですすめます。

# r-stats-hands-on

- [Rで学ぶ統計学入門 - 株式会社東京化学同人](http://www.tkd-pbl.com/book/b279683.html) を利用して統計のチュートリアル
- [オンライン分析システム（実証実験）](https://meatwiki.nii.ac.jp/confluence/pages/viewpage.action?pageId=48137275)
- [Zero-to-Binder](https://the-turing-way.netlify.app/communication/binder/zero-to-binder.html)
    - Helps you create a Binder project from scratch.
