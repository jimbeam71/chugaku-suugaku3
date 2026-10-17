# 中学数学 レベル3（文字式・式の計算・一次方程式）

公開URL: https://chugaku-suugaku3.senta1111.workers.dev/

- 配信するのは `public/index.html` の1枚だけ（KaTeXの式表示も中に入っている）。
- 内容: 文字式のきまり / 式の計算 / 一次方程式。全16ステップ・105問。
- 問題を直す・足すとき: `tools/gen3.js` を直す。
  1. `cd tools`
  2. `node gen3.js`（`src/data.js` を作る）
  3. `node check.js`（ALL OK が出ること）
  4. `node build.js --repo`（`tools/public/index.html` を作る）→ `public/index.html` に置きかえる
