# ポケチャン上位構築ボード

ポケモンチャンピオンズのランクマ・大会の上位構築を、シングル／ダブルで並べて見るサイトです。

- 公開URL: https://miraikakeru.github.io/pokechamp-board/
- `pokechamp/data.json` は毎朝自動で更新されます。
- お気に入りは閲覧しているブラウザ内に保存されます。

## サイト構成

- `/`（ルートの `index.html`）… メインメニュー「安間の好きなものまとめサイト」
- `/pokechamp/` … ポケチャン上位構築ボード（https://miraikakeru.github.io/pokechamp-board/pokechamp/）
- ボードのデータは `pokechamp/data.json`。毎朝の自動更新はこの `pokechamp/data.json` を書き換えます。
- favicon・アイコン・`manifest.webmanifest` はルートに置き、ボードから `../` で参照しています。
