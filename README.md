# robosys_2020_kadai02

### 概要
4つのノードを動かし，2倍3倍4倍した結果を出力する.

### 動作環境
- Rasberry Pi Model 3B+
- Ubuntu18.04
- Ros Noetic

### 実行手順
```
1.ディレクトリに入る
$cd ~/catkin_ws/src
2.リポジトリをクローンする
$git clone https://github.com/yukikimuramura/mypkg.git
3.一つ前のリポジトリに戻る
$cd ..
4.コンパイルする
$catkin_make
5.rosを起動する
$roscore
6.ディレクトリに入る
$cd ~/catkin_ws/src/mypkg/scripts/
7.実行できるようにそれぞれのプログラムのパーミッションを設定する
$chmod +x count.py       
$chmod +x twice.py     
$chmod +x three.py       
$chmod +x four.py
8.count.pyを実行する
$roscore mypkg count.py
9.twice.py,three.py,four.pyを実行する際それぞれ別の端末で実行する
$rosrun mypkg twice.py
$rosrun mypkg three.py
$rosrun mypkg four.py
```
### Demo
こちらが実際に動かした動画のURLです.
https://youtu.be/5Rv4Tgka2Rg
