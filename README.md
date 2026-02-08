# Prompt Engineering Explorer

2025年の高度なプロンプトエンジニアリング概念をインタラクティブに探索できるWebアプリ。

## 概要

6つの高度なプロンプトエンジニアリング概念をカード形式で表示し、タップで詳細を確認できます。

- エージェンティック・パターン
- メタプロンプティング
- 構造化出力設計
- RAG + Knowledge Graph
- プロンプトチェーニング
- LLM-as-Judge 評価

## デプロイ

単一の `index.html` ファイルです。Cloudflare Pages にそのままデプロイできます。

### Cloudflare Pages（GitHub連携）

1. このリポジトリをGitHubにpush
2. [Cloudflare Dashboard](https://dash.cloudflare.com) → Workers & Pages → Create → Pages
3. 「Connect to Git」でこのリポジトリを選択
4. ビルド設定はすべて空欄のままでOK（静的ファイルのみ）
5. デプロイ！

## 技術スタック

- バニラ JavaScript（フレームワーク不要）
- Google Fonts（Noto Sans JP / JetBrains Mono）
- 外部ライブラリ依存なし
