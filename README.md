# ベストセラー製造機

長倉顕太さん向けのサンプルゲーム（HTML1枚・約5分）。

原稿3本を、タイトル・見せ方・売り方だけで部数を伸ばす編集シミュレーター。
選択に応じて長倉さん（ドット絵・表情5段階）が講評します。

- 実体は `index.html` のみ。外部依存なし
- 効果音は Web Audio で合成（音声ファイルなし）
- LP への導線 URL は `index.html` 内の `CONF.LP_URL` 1か所のみ

※ 限定公開（noindex）。検索結果には出しません。

## 流れ図

`shots/flow.png` … タイトルからLP案内までの全9画面。`shots/*.png` は各画面の単体。
再生成は `node scratchpad/shots.js && node scratchpad/strip.js`（Playwright／実Chrome使用）。
