---
title: "自作アプリの技術要件をまとめる！！！！"
draft: false
date: 2024-04-10
description: "学習用の自作アプリの技術要件を書きなぐります"
categories:
  - Others
tags:
  - Others
---
業務以外にもアプリを作ることで、技術についての学習や検証を行いたい！！！！！

## 作るアプリ
社内で使われているアプリ「[ふぁしりたいまー](https://timer.masakurapa.com/)」を自分なりに作ってみる

{{< img
  src="facilitimer.png"
  alt="facilitimer"
  caption="ふぁしりたいまー" >}}

## 使いたいフロントエンド技術
ベースとして社内でつかっているものを使用

**JavaScriptライブラリ・フレームワーク**
- ライブラリ：React + TypeScript
- フレームワーク：[Vite](https://vitejs.dev/guide/)のものを使用）

**CSS-in-JS**
- styled-component

**LinterFomatter**
- ESLint
- Prettier

**Global State**
- Redux Toolkit

**Form**
- Formik

**Testing・a11y検証**
- Storybook
- Jest
- Testing Library
- axe-core

## まとめてみた感想
社内で使っている技術についてしっかり学習したいという気持ちなため、あまりおもしろい構成にならなかった😕

まずはサクッと基本的なものを作って、DnDとか無駄な魔改造しまくりたい


## P.S.
ブログ構築したばかりで、いろいろカスタムしきれてない

特に日付のところでgoのエラーメッセージがでてしまっているのが気になる  
技術者のブログとしてどうなの？って感じなので、早く直したい
