# Mastogetter is 何

Mastogetterとは、分散SNSオープンソースサーバ「Mastodon」の投稿を任意の順番で表示する、togetter的なまとめサイトをパーマリンクを作成することで擬似的に作成するサービスです。

Mastodon API v1 に対応しているすべてのインスタンスの公開トゥートに対して利用できます。

本サービスはデータベース等を使用しておらず、静的サイトとして設置・公開できます。ただし、まとめサイトのパーマリンクにアクセスするたびに対象インスタンスに複数のリクエストを投げるので、参照先のサーバ負荷が上がる欠点があります。

## 使い方

1. https://hidao80.github.io/mastogetter/ にアクセスします。
2. 「インスタンス名」テキストボックスにインスタンスのURLをhttp,https付きで入力します。
3. 「トゥートID or URL」テキストボックスに追記したいトゥートのIDの数字またはトゥートのURLを入力します。
4. 「ID or URLからプレビュー」ボタンを押し、フォーム下のプレビュー欄にトゥートを一度表示させます。
5. 「トゥートを追加」ボタンを押し、プレビュー欄のトゥートを画面右半分の編集リストの一番下にコピーします。
6. 必要な数だけ3.～5.を繰り返します。
7. 編集リスト上の「コピー」ボタンを押し、パーマリンクをコピーします。
8. まとめページへのパーマリンクを任意のWebページに配置します。

- 「インポートするまとめリンク」テキストボックスにパーマリンクを入力し「まとめを読み込む」ボタンを押すと、パーマリンクで表示されるトゥートまとめを編集リストに読み込むことが出来ます。
- 画面右半分の編集リストに表示されているトゥートをダブルクリックすると編集リストからトゥートを取り除くことができます。削除した項目は元には戻せません。
- 編集リストのトゥートをドラッグ＆ドロップすることで順番を変えることができます。

## バージョン毎のトップページURL

### バージョン1

https://hidao80.github.io/mastogetter/

### バージョン2

トゥートIDを符号化して、パーマリンクを短くできます。バージョン1と互換性がありません。

https://hidao80.github.io/mastogetter/v2/

## ライセンス

MIT です。ライセンスが許す範囲での複製・頒布が可能です。詳しくは[ライセンスファイル](LICENSE)をご確認下さい。
