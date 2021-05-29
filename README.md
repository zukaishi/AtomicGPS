# AtomicGPS

## 参考
https://eng-blog.iij.ad.jp/archives/7375

## 目的
小学1年生の子供がどこかへ遊びに行ってしまって行方不明（大げさ）になることが増えてきた。

周りのお母さん達も同じことを言っている。

だったら自作して、周辺に配れないか。


## こんな感じのものをポッケに忍ばせたりしたい
<img width="364" alt="スクリーンショット 2021-05-24 6 30 56" src="https://user-images.githubusercontent.com/22611735/119277270-a1f17800-bc59-11eb-88bc-30c50b9505b4.png">

## 購入先
https://www.switch-science.com/catalog/6474/

私の購入したときは、送料込みで ¥3,060　でした。

## MQTT
MQTTとは ”Message Queue Telemetry Transport” の略で、パブリッシュ/サブスクライブ型の非常にシンプルで軽量なメッセージングプロトコルです。制約のあるデバイスや、低帯域幅、高レーテンシー、または信頼性の低いネットワーク向けに設計されています。
その設計原理は、ネットワーク帯域幅とデバイスリソースを最小限に抑えつつ、メッセージ配信の一定の信頼性を確保する、というものです。
これらの原理は、M2M (Machine-to-Machine) や IoT (Internet of Things) といったデバイス同士が接続される世界においても、また帯域幅とバッテリー消費が鍵となるモバイルアプリケーションにとっても理想的なプロトコルであると言えます。

## MQTT vs HTTP 性能比較
- スループットが93倍UP
- 送信時のバッテリー使用量が91.5%減
- 受信時のバッテリー使用量が99.4%減
- 接続保持電力が50%減
- ネットワークオーバーヘッドが87.5%減

## MQTTブローカ
https://www.shiftr.io/

![スクリーンショット 2021-05-26 6 08](https://user-images.githubusercontent.com/22611735/119569391-a64c9b00-bde9-11eb-9c4c-ebc861a55337.png)

<img width="441" alt="スクリーンショット 2021-05-26 6 13 34" src="https://user-images.githubusercontent.com/22611735/119569404-a9e02200-bde9-11eb-9bb8-0fda56c3431d.png">

<img width="422" alt="スクリーンショット 2021-05-26 6 13 43" src="https://user-images.githubusercontent.com/22611735/119569419-ac427c00-bde9-11eb-95de-e3953f624dbe.png">

<img width="1125" alt="スクリーンショット 2021-05-26 6 14 28" src="https://user-images.githubusercontent.com/22611735/119569439-b3698a00-bde9-11eb-9d07-3fdc42673cfd.png">


## EasyLoader
https://docs.m5stack.com/en/atom/atomicgps
![スクリーンショット 2021-05-27 6 33 16](https://user-images.githubusercontent.com/22611735/119734374-df524180-beb5-11eb-9da6-d720507026ae.png)


## Arduino IDEのインストール
https://www.arduino.cc/en/software

<img width="501" alt="スクリーンショット 2021-05-27 6 17 31" src="https://user-images.githubusercontent.com/22611735/119732528-415d7780-beb3-11eb-969e-73e7417e891d.png">

## ソースコードの入手
$ git clone https://github.com/iij/adventcalendar2020-atomicgps
