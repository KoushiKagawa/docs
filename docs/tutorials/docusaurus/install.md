---
sidebar_position: 6
---

# docusaurus インストール

## docusaurusとは
- ドキュメントサイトに特化した静的サイトジェネレータ  
- マークダウンファイルからサイト生成  
- Facebook傘下のチームが開発している

## やったことまとめ

### 環境構築
下記記事を参考にしたらすぐに対応できました。  
- https://zenn.dev/ningensei848/articles/docusaurus_intro
- https://zatta.link/web/docusaurus-how-to.html

### configファイルの修正
docusaurus.config.jsの修正。


### デプロイ
今回はnetlifyにデプロイすることにした。  
https://docusaurus.io/docs/deployment#deploying-to-netlify
https://developer.redis.com/create/netlify/deploy-docusaurus-to-netlify/

#### netlifyにデプロイ
netlifyにてサイトを作成し、GitHubのリポジトリ選択で自動でデプロイできた！楽！

#### configの修正
docusaurus.config.js の`const config `を修正する。  
`title`や`url`を修正する
