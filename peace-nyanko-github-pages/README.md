# PEACE NYANKO CLUB｜LINEミニアプリ モック

GitHub Pagesへそのまま公開できる静的サイトです。ビルド作業や追加ライブラリは不要です。

## フォルダ構成

```text
peace-nyanko-github-pages/
├─ index.html
├─ .nojekyll
├─ README.md
└─ assets/
   ├─ products.jpg
   └─ impact.jpg
```

## GitHubへ手動で載せる手順

1. GitHubで新しいリポジトリを作成します。
2. リポジトリの `Add file` → `Upload files` を開きます。
3. このフォルダを開き、`index.html`、`.nojekyll`、`README.md`、`assets` フォルダをアップロードします。
   - 親フォルダごとではなく、上記4項目がリポジトリ直下に来るようにしてください。
4. `Commit changes` を押します。
5. リポジトリの `Settings` → `Pages` を開きます。
6. `Build and deployment` の `Source` を `Deploy from a branch` にします。
7. Branchを `main`、フォルダを `/(root)` にして `Save` を押します。

数分後、次の形式で公開されます。

```text
https://GitHubユーザー名.github.io/リポジトリ名/
```

公開URLが決まったら、そのURLを使って本番用QRコードを作成してください。

## データ連携について

現状は画面と操作感を確認するためのフロントエンドモックです。Shopify、LINE Login、LIFF、顧客DBとはまだ接続していません。
