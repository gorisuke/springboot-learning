# 🌱 Spring Boot 学習プロジェクト

このリポジトリは、**Spring Boot** を使った Web API 開発を通じて学習を進めるためのハンズオンプロジェクトです。  
Docker を利用した開発環境構築、**JWT 認証付き REST API**、**CRUD 機能**、**JUnit を使ったテスト**まで網羅します。

---

## 🚀 主な機能

- ✅ Docker を使った開発環境構築
- ✅ PostgreSQL コンテナとの連携
- ✅ JWT を使ったユーザー認証（ログイン・登録）
- ✅ 認証付きのアイテム CRUD 操作
- ✅ リクエストバリデーションとエラーハンドリング
- ✅ JUnit と MockMvc を使ったユニット・統合テスト
- ✅ Swagger / OpenAPI による API ドキュメント自動生成

---

## 🗂️ 使用技術スタック

| レイヤー | 技術 |
|---------|------|
| バックエンド | Spring Boot (Java) |
| データベース | PostgreSQL |
| ORM | Spring Data JPA (Hibernate) |
| 認証 | Spring Security + JWT |
| テスト | JUnit, MockMvc |
| コンテナ | Docker, Docker Compose |

---

## 🛠️ 開発環境の起動方法

```bash
# リポジトリをクローン
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME

# Docker Compose で起動
docker-compose up --build
```

起動後、以下の URL で API にアクセスできます：  
📍 `http://localhost:8080`

---

## 📚 学習目標

- Spring Boot を用いた REST API 開発に慣れる
- Spring Security + JWT による認証の仕組みを理解する
- Docker を用いたローカル開発環境を構築する
- Java におけるユニット・統合テストの書き方を学ぶ

---

## ✅ 学習進捗チェックリスト

- [ ] Week 1：環境構築と基本REST APIの作成
- [ ] Week 2：JWT認証とユーザー管理機能の実装
- [ ] Week 3：アイテムCRUD処理とバリデーション
- [ ] Week 4：テスト実装と仕上げ

---

## 📄 ライセンス

このプロジェクトは MIT ライセンスのもとで公開されています。

---

## ✨ 作者より

このリポジトリは、自身のスキルアップと実践的なポートフォリオ作成を目的とした学習プロジェクトです。  
ぜひフォークして活用してください！改善提案やフィードバックも歓迎します。
