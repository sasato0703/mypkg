ロボットシステム学 課題2
---

## 課題内容 
  
 課題: 第10回で作成したROSのパッケージをベースに、オリジナリティーある改造をして、GitHubに置く。
  
---

## 概要

　4倍にした数字を出力する。
 
---

## 動作環境

・Ubuntu 20.04  
・Raspberry Pi 4 ModelB  

---

## インストール方法

`$cd ~/catkin_ws/src/`  
`&git clone https://github.com/sasato0703/mypkg.git`  
`$cd ..`  
`$catkin_make`  

---

## 実行手順

ディレクトリに移動する。  
`$cd ~/catkin_ws/src/mypkg/scripts/`  

パーミッションの設定
`$chmod +x count.py`
`$chmod +x fukitu.py`

4つのターミナルに以下のコマンド順番に入力する。  

ターミナル1  
`$roscore`   
ターミナル2  
`$rosrun mypkg count.py`  
ターミナル3  
`$rosrun mypkg fukitu.py`  
ターミナル4  
`$rostopic echo /fukitu`

---

## 動画

　プログラムを実行した様子：https://youtu.be/-sKA5XiUXMU
 
---
