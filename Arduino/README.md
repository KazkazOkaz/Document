# Arduino


----------------------------
## 1.0　Arduinoとは
----------------------------

+ Arduinoのよみ:アルドゥイーノ / アルデュイーノ / アルディーノ
+ ハードウェアの「Arduinoボード」、およびソフトウェアの「Arduino IDE」から構成される
    + [Arduinoボード](#22-ボードとモジュール) : AVR/ARMマイコン、入出力ポートを備えた基板 (#2.2　ボードとモジュール)
    + [Arduino IDE](#21-Arduino総合開発環境-(Arduino-IDE)): PC上で作動させる一種のソフトウェアであり、C言語風の「Arduino言語」によってプログラムを制作・コンパイル・デバッグ等し、それをArduinoボードに転送　等々するための「統合開発環境」
+ その他：「Arduino」という名称は広義には、それらの開発・改良を行う一連のプロジェクトや、その結果生まれた会社、またその多くの開発者らによるコミュニティまでも指すことがある。
(以上　[ウィキペディア](https://ja.wikipedia.org/wiki/Arduino)　を参考に記載)
+ [SHIELDS](#23-SHIELDS) : Arduinoを拡張するための基板

[Arduino Home Page](https://www.arduino.cc/)

<!--
![image](https://store-cdn.arduino.cc/usa/catalog/product/cache/1/image/520x330/604a3538c15e081937dbfbd20aa60aad/a/0/a000066_featured_5.jpg)
-->

![image](https://store-cdn.arduino.cc/usa/catalog/product/cache/1/image/500x375/f8876a31b63532bbba4e781c30024a0a/a/0/a000066_iso_5.jpg)

<h5 style="text-align: center;">
Arduino Uno Rev3
</h5>



![image](https://store-cdn.arduino.cc/usa/catalog/product/cache/1/image/500x375/f8876a31b63532bbba4e781c30024a0a/a/b/abx00035_iso_1.jpg)
<h5 style="text-align: center;">
Arduino Nano 33 BLE Sense with headers
</h5>

<!--
![image](https://store-cdn.arduino.cc/usa/catalog/product/cache/1/image/520x330/604a3538c15e081937dbfbd20aa60aad/a/0/a000024_featured.jpg)
-->

![image](https://store-cdn.arduino.cc/usa/catalog/product/cache/1/image/500x375/f8876a31b63532bbba4e781c30024a0a/a/0/a000024_iso_4.jpg)
<h5 style="text-align: center;">Arduino Ethernet Shield 2
</h5>

<br>
<br>



--------------------------
## 2.0　開発環境
--------------------------

### 2.1　Arduino総合開発環境 (Arduino IDE)

- Arduinoの開発環境:[Download the Arduino IDE](https://www.arduino.cc/en/Main/Software)

- [Arduino 日本語リファレンス:[武蔵野電波](http://www.musashinodenpa.com/arduino/ref/)

### 2.2　ボードとモジュール

- [ボードとモジュール一覧](https://store.arduino.cc/usa/arduino/boards-modules)


<h5 style="text-align: center;">
主なエディッションのスペック*
</h5>

|  | Arduino UNO<br>R3| Arduino<br>101 | Arduino<br>Due | Ardiuno<br>Micro | Ardiuno<br>Nano | Arduino<br>Nano Every | Ardiuno<br>Yun |
|:----------: |:-------------:|:----------: |:----------: |:------------: |:-----------: |:-----------------: |:----------:|
|プロセッサ<br>（動作周波数) |ATmega328P<br>(16MHz) |Intel Curie<br>(32MHz) |AT91SAM3X8E<br>(84MHz) | ATmega32u4<br>(16MHz) |ATmega168/32<br>(16Mhz)|ATmega4809<br>(20MHz)  |ATmega32u4<br>(16MHz)|
| メインメモリ | 2KB | 80KB | 96KB | 2.5KB | 1KB/2KB | 6KB | 2.5KB |
| フラッシュメモリ| 32KB | 384KB | 512KB | 32KB | 16KB/32KB | 48KB | 32KB |
| デジタルIO | 14 | 14 | 54 | 20 | 14 | 14 | 20 |
| PWM出力 | 6 | 4 | 12 | 7 | 6 | 5 | 7 |
| アナログ入力 | 6 | 6 | 12 | 12 | 8 | 8 | 12
| アナログ出力(DAC) | - | - | 2 | - | - | - | - |
| 端子の定格電流 | 各端子40mA | 20mA | 端子合計130mA | 各端子40mA |各端子40mA |各端子20mA |各端子40mA |
| 動作電圧 | 5V | 3.3V | 3.3V | 5V | 5V | 5V | 5V |
| 電源入力電圧 | 7~12V | 7~12V | 7~12V | 7~12V | 7~12V | 7~12V | 7~12V |
| 出力電圧 | 5V, 3.3V | 5V, 3.3V | 5V, 3.3V | 5V, 3.3V | 5V, 3.3V | 5V, 3.3V | 5V, 3.3V |
|プログラム書き込み端子 | USB(Type-B),ICSP | USB(Type-B),ICSP | USB(Type-B),ICSP | USB(Type-B),ICSP | USB(Type-B),ICSP | USB(Type-B),ICSP | USB(Type-B),ICSP | 
| その他インタフェース | UART<br>I2C<br>SPI | UART<br>I2C<br>SPI | UART<br>I2C<br>SPI<br>CAN<br>USB | UART<br>I2C<br>SPI | UART<br>I2C<br>SPI | UART<br>I2C<br>SPI | UART<br>I2C<br>SPI<br>IEEE 802.11b/g/n<br>Ethernet<br>USB |
{ サイズ(mm) | 74.9x<br>53.3 | 68.6x<br>53,3 | 101.6x<br>53.3 | 48.2x<br>17.8 | 43.2x<br>17.8 | 45x<br>18 | 74.9x<br>53.3|


<br>

<h5 style="text-align: center;">
Arduino Nano 33シリーズ
</h5>


|    | Arduino Nano 33 IoT | Arduino Nano 33 BLE |  Arduino Nano 33 BLE<br>Sence |
|:--:|:--:|:--:|:--:|
| プロセッサ<br>(動作周波数)| ARM Cortex-MO+<br>(48MHz) | ARM Cortex-M4F<br>(64MHz) | ARM Cortex-M4F<br>(64MHz) |
| メインメモリ | 32KB | 256K |  256KB |
| フラッシュメモリ | 256KB | 1MB | 1MB |
| 通信モジュール | NINA W102 | NINA B306 | NINA B306 |
| 無線LAN | IEEE 802.11 b/g/n | - | - |
| Bluetooth | Bluetooth 4.2 |  Bluetooth 5.0 |Bluetooth 5.0|
|デジタルI/O | 14 | 14 | 14 |
| PWM出力 | 11 | 14 | 14 |
| アナログ入力 | 8 | 8 | 8 |
| アナログ出力(DAC) | 1 | - | - |
| 端子の定格電流 | 各端子7mA | 各端子15mA | 各端子15mA |
| 完成センサー | - | LSM9DS1(加速度、地磁気、ジャイロ)|LSM9DS1(加速度、地磁気、ジャイロ)|
| 気象センサー | - | - | HTS221(温湿度)<br>LPS22HB(気圧) |
| 光センサー | - | - | APDS9960<br>(カラー、ジェスチャー、近接) |
| マイク | - | - | MP34DT05 |
| 動作電圧 | 3.3V | 3.3V | 3.3V |
| 電源入力電圧 | ~21V | ~21V | ~21V |
| 出力電圧 | 3.3V | 3.3V | 3.3V |
| プログラム書込端子 | USB(micro-B) | USB(micro-B) | USB(micro-B) |
| その他インタフェース | UART, I2C, SPI |  UART, I2C, SPI | UART, I2C, SPI |
| サイズ | 45x18mm | 45x18mm | 45x18mm |

(出典：これ1冊でできる！Arduinoではじめる電子工作 超入門 改訂第4版 福田和宏著)
*出典と[Arduinoホームページ](https://store.arduino.cc/usa/)の数値に齟齬あり
[参考URL：Arduinoシリーズ15種類の違い](http://ideahack.me/article/134)

### 2.3　SHIELDS

[SHIELD一覧](https://store.arduino.cc/usa/arduino/shields)




