# RIMAPI_JP — 日本語ドキュメント（GitHub Pages 用）

このリポジトリは、https://ilyachichkov.github.io/RIMAPI/ の内容を日本語で要約・解説したドキュメントを GitHub Pages で公開するためのものです。

## ローカルで確認

docs フォルダにある `index.md` は静的サイトとして GitHub Pages から配信できます。ローカルで簡単に確認するには、Markdown プレビューや簡易 HTTP サーバーを使います。

## GitHub へ公開する手順（推奨: `docs/` を使う）

1. リポジトリを GitHub に作成（新規リポジトリ名例: `RIMAPI_JP`）
2. リモートを追加して push:

```powershell
git init
git add .
git commit -m "Add Japanese docs for RIMAPI"
git branch -M main
git remote add origin https://github.com/<あなたのユーザ名>/RIMAPI_JP.git
git push -u origin main
```

3. GitHub 上のリポジトリ設定 -> Pages 設定で、
   - ソース: `Branch: main` / フォルダ: `/docs` を選択
   - 保存して有効化すると数分で公開されます。

4. または `gh` CLI を使用して設定することもできます。

## 注意と帰属

この翻訳はオリジナルのドキュメントを要約したものです。正確な API の仕様や利用法は必ず原文（https://ilyachichkov.github.io/RIMAPI/）を参照してください。原著作権は Ilya Chichkov に帰属します。

---

何か追加したい翻訳や、ページのスタイル調整・画像追加などあれば教えてください。公開まで私が手伝います。
# RIMAPI_JP
RIMAPI日本語解説Wiki
