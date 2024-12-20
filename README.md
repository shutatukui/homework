# homework [![test](https://github.com/shutatukui/homework/actions/workflows/test.yml/badge.svg)](https://github.com/shutatukui/homework/actions/workflows/test.yml)
# 作ったプログラムの内容
世界標準時間(UTC)、日本(東京)、アメリカ(ニューヨーク)の現在時刻、東京証券取引所の開閉場時間、ニューヨーク証券取引所の開閉場時間の5つを表示する


# 導入方法
- クローンしたい場所で下のコマンドを実行する


  ```git clone https://github.com/shutatukui/robosys2024.git```


# pytzライブラリ
  - 各国のタイムゾーンを把握、扱うためのライブラリ


# 使用方法
- このインストール方法は ``` pip ``` を利用して ``` pytz ``` をインストールします
 
 
　　``` pip ```はPythonのパッケージ管理システムです

 
  　　最初に、ホームで下記を実行してください


 　　 sudoのパスワードを聞かれた場合、パスワードを入力すれば次に進めます


    
 　　　　　　　　　

　　 ``` sudo apt install python3-pip ```


   　　　　　　　


- 次に、「新たにパッケージが追加されます。追加しますか？」という感じに英語で「Do you want to continue? [Y/n]」聞かれます


  この場合　「Y」　を入力して進めます


  そして下記を実行してください


  　　　


　　``` pip3 install pytz ```


　  　　
 

　　これで``` pytz ```がインストールできます


# 使用例
``` echo "Asia/Tokyo" | ./sys ```


**実行結果**

``` 
: 2024-11-29 15:21:47
: 2024-11-30 00:21:47
: 2024-11-29 10:21:47


: 09:00:00 - 15:00:00 (JST)
: 09:30:00 - 16:00:00:
```


# 必要なソフトウェア
  - python 3.7 3.8 3.9 3.10

    
# テスト環境　
  - python 3.7 3.8 3.9 3.10
  - ubuntu 22.04.5


# 参考にした文献
  - [[5分でマスター] 初心者はまずREADMEを書け [テンプレート付き]](https://qiita.com/Canard_engineer_c_cpp/items/81ce4e53881138dbf37f)


  - [pytzを使ってpythonでタイムゾーンを扱う"正しい"方法](https://qiita.com/non_cal/items/2927fbdfa1d1f355b89d)


# ライセンス関係


  - ```pytz```ライブラリのライセンス　MIT license


    - 著作権者　Stuart Bishop


    - リリース日: 2024年9月11日


  - このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可される


     © 2024 Shuta Tsukui
