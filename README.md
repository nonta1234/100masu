# マス計算

小学生向けのシンプルなマス計算アプリです。  
5×5・7×7・10×10、たし算・ひき算・かけ算に対応しています。

PWA対応のため、iPadやスマートフォンではホーム画面に追加してアプリのように利用できます。

## 主な機能

- 5×5 / 7×7 / 10×10
- たし算 / ひき算 / かけ算
- 専用テンキー
- タイマー / 一時停止
- カウントダウン
- 誤答の自動消去
- 進捗表示
- 名前登録
- 自己ベスト
- 条件別ランキング TOP 5
- プレイ履歴
- 縦画面 / 横画面対応
- オフライン利用対応

記録は各端末の `localStorage` に保存されます。直近履歴は50件、自己ベストは別に保持します。

## GitHub Pagesで使う

1. **Settings → Pages**
2. Source を `Deploy from a branch`
3. `main` / `/(root)` を選択
4. 公開URLをSafariやChromeで開く

iPadではSafariの共有メニューから「ホーム画面に追加」すると、PWAとして利用できます。

## Files

```text
index.html
manifest.webmanifest
sw.js
icon-192.png
icon-512.png
apple-touch-icon.png
README.md
```
