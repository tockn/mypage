---
title: "Twitro" # Title of your project
date: 2020-01-03T03:53:45+09:00
weight: 0 # Order in which to show this project on the home page
resources:
    - src: twitro.png
      params:
          weight: 0 # Optional weighting for a specific image in this project folder
    - src: userpage.png
      params:
          weight: 1 # Optional weighting for a specific image in this project folder
---

### Twitterのユーザーをレビューできるサービス

https://twitro.com

初めてリリースしたWebサービス。

初期はRuby on Railsで開発しましたが、UX改善のためにフロントをVue.jsで、バックエンドをGoで一新。技術的にも様々な学びがありました。

Frontend: Vue.js

Backend: Go

Infrastructure: Conoha VPS

Database: MySQL

自分が作ったサービスを全く知らない人に使ってもらえる、そして何かしらの価値を提供できる、という初めての体験は衝撃的でした。MySQLでSELECT usersするたびにユーザー数が増えていくあの感覚は、なかなか忘れられません。

今は使われておらず放置していますが、なんだかもったいなくて消してません。（それでもかかるサーバー代...）
