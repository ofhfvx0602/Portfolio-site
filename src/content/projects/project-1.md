---
title: "電子書籍販売サイト"
description: "電子書籍を販売することができるサイトを制作しました。"
image:
  url: "/電子書籍サイト.jpg"
  alt: "book commerce wallpaper"
worksImage1:
  url: ""
  alt: ""
worksImage2:
  url: ""
  alt: ""
platform: Web
stack: Next.js, Vercel Postgres, NextAuth.js, Prisma, API Route, Stripe
website: https://book-commerce-app-nine-tan.vercel.app/
github: https://github.com/ofhfvx0602
---

電子書籍を販売することができるサイトを制作しました。<br>
Next.js/Vercel Postgres/NextAuth.js/Prisma/API
Route/Stripe を駆使して 1 つのフレームワークで Web アプリ開発を行いました。
MicroCMS で執筆した電子記事を販売することができます。
NextAuth を使った OAuth 認証の実装を行いました。
<br>
<br>
■ 具体的に行ったこと<br>
・MicroCMS と WebHook を使った記事作成の実装を行いました。<br>
・Vercel Postgres を使った DB 管理を行いました。<br>
・GithubProvider を利用して OAuth 認証を実装しました。<br>
・PrismaORM を使ってデータ操作ができます。<br>
・getServerSession を使ってサーバーサイドでセッション取得しています。<br>
・microcms-sdk を使ってクライアント側で MicroCMS 専用の API を作成しました。<br>
・Next API Route で API を実装しました。<br>
・商品購入時の際にモーダルが出現します。<br>
・NextAuth でログイン/ログアウトが実装を行いました。<br>
・Stripe を使ってチェックアウト決済機能を実装しました。<br>
・決済が完了したら購入完了ページへ遷移できます。<br>
・購入時に DB に保存履歴を残すことができます。<br>
・購入履歴のデータを利用して複数回購入を防ぐ実装をしました。<br>
・商品購入履歴 API を実装しました。<br>
・Typescript ベースで Nextjs 開発ができます。<br>
・ユーザープロフィールページを作成しています。<br>
・ログイン中のユーザーの購入履歴を取得できます。<br>
・購入した記事一覧取得 API を構築しています。<br>
・Suspense を利用してローディングを実装しています。<br>
・Vercel を使ってデプロイしました。<br>
・最新記事データを反映させるために SSR を実装しました。<br>
・デプロイ後のパフォーマンス測定も行っています。<br>
・ISR に変更した際に SSR とパフォーマンスの差があるのかも分かります。<br>
・CSR と SSR と ISR をどのように使い分けるのかを理解しています。<br>
・リファクタリングできる箇所がないか？最後に確認しました。<br>
<br>
