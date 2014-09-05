mocha-greps
===========

mochaのgrepオプションを使い分ける



## やり方

`npm test`だと`package.json`の`scripts.test`だけを実行する。
これは`npm run test`と同じ。

mochaにoptionをそれぞれ与えたいので`npm run [command]`で実行する。

---

- hogeのテスト
  - `npm run test_hoge`で実行。`scripts.test_hoge`-->'mocha --grep hoge'。
- fooのテスト
  - `npm run test_foo`で実行。`scripts.test_foo`-->'mocha --grep foo'。
- 全部のテスト
  - `npm test`で実行。

