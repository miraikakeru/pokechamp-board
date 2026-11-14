# ポケチャン上位構築ボード

ポケモンチャンピオンズのランクマ・大会の上位構築を、シングル／ダブルで並べて見るサイトです。

- 公開URL: https://miraikakeru.github.io/pokechamp-board/
- `pokechamp/data.json` は毎週土曜の朝1時に自動で更新されます。
- お気に入りは閲覧しているブラウザ内に保存されます。

## サイト構成

- `/`（ルートの `index.html`）… メインメニュー「安間の好きなものまとめサイト」
- `/pokechamp/` … ポケチャン上位構築ボード（https://miraikakeru.github.io/pokechamp-board/pokechamp/）
- `/goods/` … グッズ情報まとめボード（ポケモン・マーベル・原神／ゼンレスゾーンゼロ／崩壊：スターレイルのグッズとコラボ。データは `goods/data.json`、毎週土曜4時に自動更新）
- `/ai/` … AI情報ボード（Claude の基本・アップデート・使い方、ChatGPT・Gemini などほかの生成AIのニュース、各社の現行モデル一覧。データは `ai/data.json`、毎週土曜1時に自動更新）
- `/events/` … おでかけイベントボード（小平から電車・車でおおむね90分以内のお祭り・花火、グルメフェス、音楽フェス、家族向けイベント。データは `events/data.json`、毎週土曜3時に自動更新）
- ボードのデータは `pokechamp/data.json`。毎週土曜1時の自動更新はこの `pokechamp/data.json` を書き換えます。
- favicon・アイコン・`manifest.webmanifest` はルートに置き、ボードから `../` で参照しています。
