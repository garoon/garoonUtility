garoon-soap-connector
==============
#Overview
garoon-soap-connectorはサイボウズ ガルーンのSOAP APIにアクセスするJavaScript ライブラリです。  
SOAP APIのリクエストやレスポンスをjson形式で取り扱うことができます。

##Desctiption
* Garoon on cybozu.com に対応します。
* SOAP APIの扱えるバージョンであればオンプレ版ガルーンでも動作しますがテストはしていません。
* 下記アプリケーションに対応しています
  * ベース(Base)
  * スケジュール(Schedule)
* SOAP APIリファレンス
  * [Garoon(ガルーン) API](https://cybozudev.zendesk.com/hc/ja/articles/202228424) 
* APIアクセスの度に、ログイン名およびパスワードをプレーンテキストでサーバーに送信しています。セキュリティを確保するためには、SSLをご利用ください。

##Requirement
* 以下の JavaScript ライブラリに依存しています。
  * [jQuery](http://jquery.com/) v3.1.1

##Usage
* [リファレンス](https://github.com/north-river/garoon-soap-connector/wiki)

##VS.
[cybozu-connect](https://github.com/hatashinya/cybozu-connect)との相違点は以下です。
 * kintoneやガルーンカスタマイズ時に利用する想定で、各関数をカスタマイズJSから参照しやすい形に変更しています。（内部的な変更であり利用の仕方自体に変わりはありません。）

##License
MIT License

##Copyright
Copyright(c) Cybozu, Inc.
