---
title: RIMAPI 日本語解説
---

# RIMAPI — RimWorld 用 REST API（日本語解説）

このページは、オリジナルのドキュメント（https://ilyachichkov.github.io/RIMAPI/）を要約・翻訳した日本語の解説です。原著者 Ilya Chichkov に敬意を表します。

## 概要

RIMAPI は RimWorld に REST API サーバーを追加するモッドで、ゲームのデータに外部からアクセスしたり、ゲーム内の操作を自動化したりできます。コロニーの状態監視、ポーン操作、資源管理などを外部ツールやスクリプトから行えます。

## 主な特徴

- RESTful API: 標準的な HTTP エンドポイントでゲームデータを取得・操作できます。
- リアルタイムイベント: Server-Sent Events (SSE) によるライブ更新を受け取れます。
- 拡張可能な設計: 他のモッドが独自のエンドポイントを追加できます。
- 非ブロッキング設計: メインスレッド上で安全に動作し、リクエストは適切にキューイングされます。
- 自動ドキュメント: API は自己記述的で、複数フォーマットのドキュメントが利用可能です。

## 使い始め（Quick Start まとめ）

詳しい手順はオリジナルのクイックスタートを参照してください: https://ilyachichkov.github.io/RIMAPI/quick_start.html

簡単な流れ:

1. RIMAPI モッドを RimWorld に導入する。
2. ゲームを起動し、RIMAPI が提供する HTTP エンドポイント（デフォルトのポートやベースパスはドキュメント参照）にアクセスする。
3. API ドキュメントを確認して、必要なエンドポイントを呼び出す。

## 主要ドキュメント（原文）

- API リファレンス: https://ilyachichkov.github.io/RIMAPI/api.html
- 開発者ガイド（拡張・エンドポイント作成）: https://ilyachichkov.github.io/RIMAPI/developer_guide/creating_extensions.html
- アーキテクチャ: https://ilyachichkov.github.io/RIMAPI/contributors_guide/architecture.html

## 翻訳ポリシーと帰属

このサイトはオリジナルの英語ドキュメントを要約・翻訳したもので、原文の著作権は原著作者に帰属します。重要な仕様や正確な使用方法は必ず原文を参照してください。

---

## このリポジトリの公開方法

このリポジトリを GitHub に push し、GitHub Pages を `docs/` フォルダから公開することで簡単に表示できます。詳しい手順はリポジトリルートの `README.md` を参照してください。
