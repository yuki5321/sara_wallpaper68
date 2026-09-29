# SARA's ふわふわ星空さんぽ（Flappy Angel） 🪽✨

スマートフォン向けの縦画面Webミニゲーム「SARA's ふわふわ星空さんぽ」のリポジトリです。
HTML5 Canvas と Web Audio API による単一ファイル構成で、パステルパープルと星空の世界観を楽しめます。

---

## 🌟 プレイURL
👉 **[今すぐあそぶ（GitHub Pages）](https://yuki5321.github.io/sara-flappy-angel/)**

---

## 🎀 世界観・デザイン
- **テーマ**: SARAのパステルパープル・星空・雲の上の世界
- **主人公**: 羽の生えた白うさぎ（Angel Bunny）
  - タップで羽ばたきながらふわっとジャンプ
  - 背中や足元からパステルハートや星屑パーティクルが舞い散る演出
- **障害物**: 紫〜アイスブルーの淡い発光を放つ「半透明のクリスタルタワー」
  - 柱の先端には回転しながらキラキラ輝く星
- **サウンド演出 (Web Audio API)**:
  - タップ時：「ぴょん♪」
  - クリスタル通過時：「チリン♪（星のチャイム音）」
  - 衝突時：「ぽよん（星屑になって消える）」
  - BGM：ドリーミーなコードアルペジオ（ON/OFF切替可能）
- **結果画面＆称号**:
  - グラスモーフィズム（すりガラス）カード
  - スコアに応じたガーリーな称号（Sleepy Bunny / Baby Angel / Sparkle Chaser / Crystal Princess / Miracle Starlight）
  - 「今日のハッピーを占う（星占い）」機能
  - LINE / X(Twitter) シェア機能

---

## 🛠️ 技術スタック
- HTML5 / CSS3 (CSS Grid, Flexbox, Animations, Glassmorphism)
- JavaScript (HTML5 Canvas 2D API, Web Audio API)
- 外部アセット（画像・音声ファイル）依存ゼロ
- スマホ縦画面（9:16比率）＆ Retina (高DPI) 対応
