# Prog2kakushin
## プログラム１について  
- 概要
  - 広島県内の市町村(入力)で前年度からの変化が最も大きい年を調べる
- 作成理由
  - グラフ化してもいまいち変化量がわかりづらい場合に使えると思ったから
- 入力と出力
  - 調べる市町村名を入力する
  - 年(西暦)と変化量(人)が出力される
- 工夫
  - 変化量を調べるときに処理が簡単にできるようdiffモジュールを使いました
## プログラム２について  
- 概要
  - 入力された関数とその導関数を計算してグラフ化する
- 作成理由
  - 微分が簡単にできて、グラフ化によって分析しやすくなるから
- 入力と出力
  - 変数がxの関数を入力, 記述はコードを書く時と同じように
  - 入力した関数とその導関数が表示され, グラフに出力される
- 工夫
  - numpyで数式を入力して利用する方法がよくわからなかったのでsympyを使用した
## プログラム３について
- 概要
  - 動物の画像が表示されているパネルを選ぶゲーム
  - 上から順に, 画像の体裁を整える, 合成された画像を作成する, 回答を入力するプログラム
- 入力と出力
  - 正解だと思う番号をカンマ区切りで入力する
  - 完答の場合「正解」が, 不十分なら「不正解」が出力される
- 工夫
  - サイズの違う画像が組み合わせられるよう大きさを均一に（100＊100に）整えるプログラムを作っておいた
  - その際すでに整えた画像は除外するよう[！]を利用した
  - 回答の入力が一度にできるようstpilを利用した
