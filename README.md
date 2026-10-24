# naishin-navi-data

内申点計算アプリ「内申ナビ」のルールデータです。GitHub Pages で公開し、アプリが起動時に読み込みます。

- 公開URL: https://kanatok1177-svg.github.io/naishin-navi-data/rules.json
- 元データ: アプリ本体のリポジトリ(非公開)の `data/rules.json`。全国47都道府県の計算ルール一覧と照らし合わせるテストを通したものを置いています。

## 更新のしかた

1. アプリ本体のリポジトリで `data/rules.json` を直し、テストを通す。
2. その `data/rules.json` を、このリポジトリの `rules.json` にそのままコピーする。

形の正しくないファイルを置いた場合、アプリはそのファイルを使わず、端末に保存した前回分か、アプリに同梱した分を使います。
