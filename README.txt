やることリストPWA
=================

同梱ファイル
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

使い方（iPhone）
1. ファイル一式を同じフォルダのままWebサーバーに置きます。
   例: GitHub Pages / Netlify / Cloudflare Pages
2. SafariでURLを開きます。
3. 共有ボタン →「ホーム画面に追加」を押します。
4. 以後はアプリのように起動できます。

ローカル確認（PC）
- VS Code の Live Server
- Python: python -m http.server 8000
  その後 http://localhost:8000 を開く

仕様メモ
- データは端末内(localStorage)に保存されます。
- 1日最大10件まで追加できます。
- その日のタスクを全達成すると、ゲーム時間30分が1回だけ追加されます。
- 累計追加時間と履歴は設定画面から確認できます。
