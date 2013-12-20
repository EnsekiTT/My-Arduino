# My-Arduino
## arduino
This document is made by [gitfab](http://gitfab.org)
---
#EAGLEをインストールする

[EagleのHP](http://www.cadsoftusa.com/download-eagle/?language=en)

自分のOSに合わせてEagleをインストール。

英語に負けず起動する。
---
#EAGLEでプロジェクトをつくる

ツールバーから

File -&gt; New -&gt; Project

を選択して新しいプロジェクトを作る。名前は適当に…

次に作ったプロジェクトを右クリックして

Edit -&gt; New -&gt; Schematic

をクリックすると新しい回路図を作る画面が表示される。
---
#部品をリストアップする
Arduinoを構成するために必要な最小限の部品たち

* **マイコン [ATMEGA 328P-PU](http://akizukidenshi.com/catalog/g/gI-03142/) :[EAGLEスケッチ](http://www.faludi.com/2008/10/07/arduino-avr-library-for-eagle-layout-editor/)**
    * add -> Arduino−AVR -> ATMEGA 168-PU

    * ※EAGLEには最初からArduino用のマイコンが入っていないためATMEGA168-PUのライブラリで代用する。

    * ※※ダウンロードしたライブラリは/Applications/EAGLE-x.x.x/lbr/以下に置く。


* **抵抗 [1kΩ 1/6w](http://akizukidenshi.com/catalog/g/gR-16102/) x2, [1MΩ 1/6w](http://akizukidenshi.com/catalog/g/gR-16105/) x1**
    * add -> rcl -> R-EU_ -> R-EU_0204/5

* **コンデンサ [22pF セラミック](http://akizukidenshi.com/catalog/g/gP-04060/) x2, [0.1μF セラミック](http://akizukidenshi.com/catalog/g/gP-00090/) x1**
    * add -> rcl -> C-EU -> C-EU025-025X050

* **[水晶発振子 16MHz](http://akizukidenshi.com/catalog/g/gP-00545/) x1**
    * add -> crystal -> CRYSTAL -> CRYSTALHC49S

* **[LED 5mm](http://akizukidenshi.com/catalog/g/gI-04781/) x1**
    * add -> led -> LED -> LED5MM

* **ピンヘッダ [2x3](http://akizukidenshi.com/catalog/g/gC-00082/) x1, [1x8](http://akizukidenshi.com/catalog/g/gC-00167/) x4**
    * add -> con-lstb -> MA03-2
    * add -> con-lstb -> MA08-1

* **電源周り GND(0Vのこと), VCC(5Vのこと)**
    * add -> supply1 -> GND
    * add -> supply1 -> +5V
---
#EAGLEに部品を配置する

[EAGLEの基本的な使い方](http://www.picfun.com/Eagleframe.html)

を見ながら

![スクリーンショット 2013-12-18 20.25.55.png](https://raw.github.com/EnsekiTT/My-Arduino/master/gitfab/resources/スクリーンショット-2013-12-18-20.25.55.png)

のように配線する。

---
