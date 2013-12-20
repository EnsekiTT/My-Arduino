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

マイコン [ATMEGA 328-PU](http://akizukidenshi.com/catalog/g/gI-03142/)

抵抗 [1kΩ 1/6w](http://akizukidenshi.com/catalog/g/gR-16102/) x2, [1MΩ 1/6w](http://akizukidenshi.com/catalog/g/gR-16105/) x1

コンデンサ [22pF セラミック](http://akizukidenshi.com/catalog/g/gP-04060/) x2, [0.1μF セラミック](http://akizukidenshi.com/catalog/g/gP-00090/) x1

[水晶発振子 16MHz](http://akizukidenshi.com/catalog/g/gP-00545/) x1

[LED 5mm](http://akizukidenshi.com/catalog/g/gI-04781/) x1

ピンヘッダ [2x3](http://akizukidenshi.com/catalog/g/gC-00082/) x1, [1x8](http://akizukidenshi.com/catalog/g/gC-00167/) x4

電源周り GND(0Vのこと), VCC(5Vのこと)


---
#EAGLEに部品を配置する
---
