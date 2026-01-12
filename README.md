# django-backend-project
### プロジェクト概要

本プロジェクトは、
ユーザーに適した店舗情報を推薦するアプリケーションの
バックエンドを担当したチーム開発プロジェクトです。
私はサーバーサイドの設計・実装を中心に担当しました。

### 開発背景

広告や過剰な情報が多い環境の中で、
ユーザーにとって本当に適した店舗を提案できる
アプリケーションの必要性を感じ、本プロジェクトを企画しました。

### 開発体制

開発人数：6名

担当領域

Web / App：他メンバー

Server：担当（バックエンド）

Database：他メンバー

Algorithm / AI：他メンバー

Data Scraping / Cleaning：他メンバー

### 担当内容

Djangoを用いたREST APIサーバーの設計・構築

アルゴリズムおよびAI処理を想定したAPI連携設計

MySQLとの連携およびデータ管理処理の実装

APIの入出力仕様を明確に定義し、
フロントエンド・アルゴリズム担当と連携

### システム構成

Backend：Django

Database：MySQL

Application Server：Gunicorn

Web Server：Nginx

API：REST API

### 工夫した点・学んだこと

Webサーバー・WAS・WSGIの役割を意識し、
実運用を想定したサーバー構成を設計

APIの入出力仕様を明確に定義することで、
並行開発でもスムーズに統合できる構成を実現

サーバーを外部からリクエスト可能な形で構築し、
バックエンドの全体像への理解を深めました

### 使用技術

Python

Django

REST API

MySQL

Gunicorn

Nginx
