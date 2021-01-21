ロボットシステム学課題２
- リポジトリの概要
 
 タイピング練習ゲーム
 
  ランダムに出力される小英字を正確に打ち込んでいくシンプルなゲーム
  
  scripts内のコードでは4字×5回になっているがどちらも可変可能になっており、難易度の調整が簡単に行うことができる。
  
  また、大英字を追加することもできる。
- 動作環境

RaspberryPi4

Ubuntu20.04LTS

ROS  noetic
- 使用したもの

RaspberryPi4
- デモ動画のリンク

https://youtu.be/JlyYiThhs88
- インストール方法

ターミナル

cd ~/catkin_ws/src/

git clone https://github.com/ShinnosukeTamai/roshw.git

- 使用方法

ターミナル

chmod +x rand_a.py

roscore &

rosrun roshw rand_a.py
- ライセンス

BSD-3-clause License
