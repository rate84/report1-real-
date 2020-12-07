# report1-real-
2020年ロボットシステム学の課題1になります．
17C1704 先進工学部未来ロボティクス学科　4年　寺井遼平

概要としてはLEDの点灯・消灯・点滅を行う．というものである．

事前準備は以下の通り．

必要な物
Raspberry Pi3 Model B ×1
LANケーブル ×1
Wifiルータ ×1
microSD ×1
USB電源ケーブル(TypeA-MicroB) ×1
LED ×1
220Ωの抵抗 ×1
ジャンプワイヤー ×2

ubuntuのセットアップ方法は以下を参考にした．
https://ryuichiueda.github.io/robosys2020/lesson1_introduction.html

LEDを点灯させるためのデバイスを作成する．点灯と消灯を行うデバイスは以下を参考にする．
https://ryuichiueda.github.io/robosys2020/lesson7_device_driver.html

コマンド操作の手順は以下の通り．
echo 1 > /dev/myled0(LEDが点灯)
echo 2 > /dev/myled0(LEDが点滅)
echo 0 > /dev/myled0(LEDが消灯)

面白いものは作成できませんでした．提出遅れて申し訳ありません．
