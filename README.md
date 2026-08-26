# 部分翻訳学習アプリ Webサイト

GitHub Pages向けの静的サイトです。JavaScript、分析SDK、問い合わせフォーム、外部フォントは使用していません。

公開URL: <https://learningbrowser.com/>

GitHub Pagesのカスタムドメインはルートの`CNAME`で固定します。TLS証明書の発行中は従来のGitHub Pages URLからも到達できます。

## アプリ公開前Blocker

- 2026年8月27日施行の法務文書とアプリのprod configを同じ版へ同期済み
- Store申告内容を最終signed artifactと照合する
- アプリの審査提出・一般公開は別途明示承認後に行う

## ローカル確認

リポジトリ直下で次を実行し、表示されたURLをブラウザで開きます。

```sh
python3 -m http.server 8080 --directory website
```
