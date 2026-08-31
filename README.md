# 部分翻訳学習アプリ Webサイト

GitHub Pages向けの静的サイトです。JavaScript、分析SDK、問い合わせフォーム、外部フォントは使用していません。

公開URL: <https://learningbrowser.com/>

GitHub Pagesのカスタムドメインはルートの`CNAME`で固定します。TLS証明書の発行中は従来のGitHub Pages URLからも到達できます。

## 公開状況

- Android版 `1.0.0` はGoogle Playで公開中
- iOS版は準備中
- 2026年8月27日施行の法務文書Version 1.0とアプリのprod configは同期済み
- 有料機能の販売条件と事業者情報は`/commerce/`の「特定商取引法に基づく表示」で明示

このディレクトリを公開サイト専用のGitHub Pagesリポジトリのルートへ同期し、pushして公開します。アプリ本体リポジトリの`website/`を変更しただけでは公開URLは更新されません。

## ローカル確認

リポジトリ直下で次を実行し、表示されたURLをブラウザで開きます。

```sh
python3 -m http.server 8080 --directory website
```
