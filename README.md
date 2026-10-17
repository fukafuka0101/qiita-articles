# qiita-articles

Qiita 投稿用の公開リポジトリです。

原稿はプライベートリポジトリ `articles` で管理しており、`private: false` に設定して push すると GitHub Actions により自動でこのリポジトリに同期されます。

このリポジトリには Qiita CLI の GitHub Actions が設定されており、同期後に自動で Qiita に公開されます。

## セットアップ（初回のみ）

Qiita への自動公開には GitHub Secrets に `QIITA_TOKEN` の登録が必要です。

## 直接編集について

このリポジトリを直接編集した場合、次回の自動同期で上書きされる可能性があります。編集は `articles` リポジトリで行ってください。
