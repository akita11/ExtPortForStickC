# ExtPortForStickC

<img src="https://github.com/akita11/ExtPortForStickC/blob/main/ExtPortForStickC1.jpg" width="240px">

<img src="https://github.com/akita11/ExtPortForStickC/blob/main/ExtPortForStickC2.jpg" width="240px">

<img src="https://github.com/akita11/ExtPortForStickC/blob/main/ExtPortForStickC3.jpg" width="240px">

[M5StickCPlus](https://www.switch-science.com/products/6470)や[M5StickCPlus2](https://www.switch-science.com/products/9350)の上部コネクタに接続し、最大2つのGroveポートを増設することができます。

M5StickCPlusの上部コネクタに出ているI/Oポートは数が少ないため、配線を切り替えて使用できるようになっています。


## ピン配置

2つのGroveポートがあり、それぞれのピン配置は以下のとおりです。

- PortB（黒）: G25/G26/V/G
- PortC（青）: G26/[G0 or G25]/V/G

PortCの2番ピンは、コネクタ横のショートピンによって、G0またはG25を切り替えることができます。（中央-"G0"側をショート=G0、中央-"G25"側をショート=G25）

※M5StickCPlus/2の仕様として、G25はG36と内部で接続されています。このピンはアナログ入力として使用できるG36を使うこともできますが、その場合はG25を入力ピンとして設定して使用してください。


## Author

Junichi Akita (@akita11) / akita@ifdl.jp

