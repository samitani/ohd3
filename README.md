# スイカ割れんじゃー at Open Hack Day Japan 3 

## スイカ割れんじゃーとは
* ５人のプレイヤーが協力して１体のロボットを操作し、すいか割りをします。
* 操作はWEBブラウザから行います。いつでも、どこでもすいか割りが楽しめます。
* 各プレイヤーはそれぞれ１方向しか操作できません。
* ロボットの頭につけられたWEBカメラの映像を見ながら操作します。

## 仕組み
* GR-001 http://www.hpirobot.jp/gr-001/product/index.html
* VSidoConn4Edison https://github.com/Asratec/VSidoConn4Edison

## 苦労したところ
* 結局WiFiの感度が悪いとEdisonが高負荷になる。
* バッテリーが10分ぐらいしか持たない。デバッグ時間が限られる。
* コマンドが捨てられることがある。リトライ機構の実装。

## お礼
* 夜おそくまで、相談にのってくださったアスラテックのみなさま
* Open Hack Day Japan の事務局の方々
* ありがとうございました
