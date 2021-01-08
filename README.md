ロボットシステム学 課題2
---

## 課題内容 
  
 課題: 第10回で作成したROSのパッケージをベースに、オリジナリティーある改造をして、GitHubに置く。
  
---

## 概要

　四倍にした数字を出力する。
 
---

## 動作環境

・Ubuntu 20.04
・Raspberry Pi 4 ModelB

---

## インストール方法

`$cd ~/catkin_ws/src/`
`&git clone`
`cd ..`
`catkin_make`

---

## 実行手順

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
