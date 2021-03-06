# excel-price-card

## 概要

Excelで価格POPを作成します

## バーコードまわり

以下サイトのバーコードとJANコードVBAマクロを利用させていただいています。

[JANCODE-nicotan](http://nicotan.at-ninja.jp/blog/newWindow/conversion_Excel_JANCODE-nicotan.html)

## 前提条件：

- バーコードフォントをインストール
- マクロを有効化してね

## 使い方：

1. 商品台帳シートに情報入力
2. 印刷シートのJANコード欄に入力
商品台帳を参照しているので、商品情報が転記されます。  
同時に、POPシートに商品情報が転記されます（バーコード付き！）  
バーコードがおかしいなと思ったら、再計算を実行してください。
3. あとは印刷するのみ！  
印刷対象のページは印刷時に設定してください。

## プライスカード（POP）のカスタマイズ

POPシートは印刷シートを参照しているだけなので、式を埋め込んであげればいいわけです。しかし、枚数が大量のため式を埋め込むのも一苦労だと思います。

そこで、式を埋め込むマクロを作成しました。POP設定のページにて式を埋め込むマクロを動作させることができます。各パラメータの説明をよく読んでご利用ください。