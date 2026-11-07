# zenn-content

wabiplantメディア（正本: https://portfolio.wabiplant.workers.dev/media/ ）の記事を
Zenn へ横展開するためのコンテンツリポジトリです。

## 構成

- `articles/` — Zenn 記事（Markdown + frontmatter）。`fanout/distribute.py` が
  正本サイトの記事から自動生成してコミットします。
- `books/` — Zenn 本（将来用）。

## Zenn との連携

Zenn のダッシュボードで「GitHub連携」からこのリポジトリを選択すると、
`articles/` 以下の Markdown が Zenn の記事として取り込まれます。
連携手順の詳細は `../ENABLE.md` を参照してください。

frontmatter の `published` は当面 `false`（下書き）で運用します。
