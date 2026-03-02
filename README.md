# hello-fast-world

Claude Code の Fast モード（Opus 4.6）で生成した、インタラクティブなパーティクルギャラクシー。

**プロンプトから完成まで約15秒。**

## Demo

👉 **[Live Demo](https://hello-fast-world.techtalkjp.workers.dev)**



https://github.com/user-attachments/assets/587bc746-e85a-46f1-8448-3885c9b7b356



## What is this?

Claude Code の Fast モードがどれくらい速いかを試すために作ったもの。単一の `index.html` でキャンバスベースのパーティクルアニメーションが動く。

- マウスを動かすとパーティクルが反応
- クリックで爆発エフェクト
- Cloudflare Workers の Static Assets としてデプロイ

## Stack

- HTML / CSS / Canvas API（単一ファイル）
- Cloudflare Workers（Static Assets）
- Claude Code Fast mode（コード生成）
