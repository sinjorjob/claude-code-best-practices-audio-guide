# Claude Code ベストプラクティス 音声ガイド

**公開 URL**: <!-- TODO: GitHub Pages にデプロイしたら差し替え -->  `https://<user>.github.io/<repo>/`

Anthropic 公式トーク **[Claude Code best practices](https://www.youtube.com/watch?v=gv0WHhKelSE)**（Cal Rueb 氏, 約 25 分）を日本語で再構成し、**再生ボタンを押すと字幕付きで自動スクロールしながら読み上げてくれる Web アプリ**にしたものです。

ナレーションに加え、非エンジニア向けに解説を挟むキャラクター「Piyofeed」のコメントも差し込まれます。

## Opus 4.7 でどこまで作れるか試してみた

本プロジェクトは **Claude Opus 4.7（1M context）** と Claude Code だけでゼロから作りました。

- 元動画の字幕から日本語リライト
- 雑誌風 HTML / CSS デザイン
- Fish Audio による 152 ブロックの TTS パイプライン
- カラオケ風字幕 + 同期スクロール + かわいいアバター

Opus 4.7 で軽く試作してみた、というプロジェクトです。
