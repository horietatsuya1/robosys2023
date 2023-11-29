# plusコマンド

![test](https://github.com/horietatsuya1/robosys2023/actions/workflows/test.yml/badge.svg)

標準入力から読み込んだ数字を足す。

## ダウンロード方法
```
  git clone https://github.com/horietatsuya1/robosys2023

```

## 簡単な使い方
```

 $ seq 10 > nums
 $ cat nums
  1 2 3 4 5 6 7 8 9 10

```
```
 $ seq 10 | ./plus
  55.0

```

## ライセンス

* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
  * このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
      * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
  * © 2023 Tatsuya Horie

## 必要なソフトウェア

* Python
  * テスト済みバージョン: 3.7~3.10

## テスト環境

* Ubuntu
