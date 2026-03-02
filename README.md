# hello-fast-world

Claude Code の Fast モード（Opus 4.6）で生成した、インタラクティブなパーティクルギャラクシー。

**プロンプトから完成まで約15秒。**

## Demo

👉 **[Live Demo](https://hello-fast-world.techtalkjp.workers.dev)**

https://github.com/coji/hello-fast-world/releases/download/v0.0.0/demo.mp4

## What is this?

Claude Code の Fast モードがどれくらい速いかを試すために作ったもの。単一の `index.html` でキャンバスベースのパーティクルアニメーションが動く。

- マウスを動かすとパーティクルが反応
- クリックで爆発エフェクト
- Cloudflare Workers の Static Assets としてデプロイ

## Stack

- HTML / CSS / Canvas API（単一ファイル）
- Cloudflare Workers（Static Assets）
- Claude Code Fast mode（コード生成）
