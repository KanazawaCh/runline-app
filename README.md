# runline-app

RUNLINE ― 走った記録を、伸びとして見る。

ランニング記録（日付・距離・時間・平均心拍数など）を手入力またはCSVインポートで管理し、統計・目標進捗（GOAL LANE）・ペース/距離チャート・記録一覧を表示するアプリです。データはブラウザのlocalStorageにのみ保存され、外部には送信されません。

## 構成

- `index.html` — アプリ本体（HTML / CSS / JS 一式）
- `vendor/` — D3.js・PapaParseのローカル同梱版（CDN非依存）

## 実行方法

ビルド不要の静的HTMLアプリです。適当な静的サーバーで配信してブラウザで開いてください。

```bash
python3 -m http.server 8420
# http://localhost:8420/index.html を開く
```
