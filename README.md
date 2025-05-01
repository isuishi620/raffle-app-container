# 春祭り 抽選アプリ🎉
シンプルな番号抽選アプリです。最大番号を入力すると、１～Nの中から重複なくランダムに番号を抽選します。抽選状況はlocalStorageへ自動保存されるため、ページをリロードしても続きから再開できます。

## デモ
[https://isuishi620.github.io/raffle-app-container/](https://isuishi620.github.io/raffle-app-container/)

## クイックスタート
※VS CodeのDev Containersでの開発を想定しています。初めにReopen in Containerを実行してください。
```
cd raffle-app
npm install # 依存関係を取得
npm run dev # 開発サーバー : http://localhost:5173
```

## ビルド&公開
```
npm run build
npm run deploy   # gh‑pages ブランチへ push して GitHub Pages へ公開
```

## 技術スタック
- React
- Vite
- Tailwind CSS
