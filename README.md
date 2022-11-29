# robosys2022
このリポジトリはロボットシステム学の練習リポジトリです.    

# plusコマンド 
![test](https://github.com/kula0416/robosys2022/actions/workflows/test.yml/badge.svg)  
標準入力から読み込んだ数字を足す(詳細は使い方で...).

## 使い方
```
$ git clone https://github.com/kula0416/robosys2022
```
を実行する.  
```
$ seq <数字> | ./plus
```
によって指定した数字を足す.
### 使用例
```
$ seq 5 | ./plus  #1から5までの数字を足す.
15
```

## 必要なソフトウェア
* Python
  * テスト済み: 3.7~3.10

## テスト環境
* Ubuntu

© 2022 Yuto Okura　　

# 権利関係
* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます.   
 © 2022 Yuto Okura
