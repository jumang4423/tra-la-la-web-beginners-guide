# 演習課題03

### 提出期限

2020/2/11 \(木曜日\)

## 課題内容

* pythonインタプリタモード\(対話モード\)を使って、円の面積を計測してください

半径を予め、radiusという変数にradius = 5のように定義し、最終的にその変数を使って円の面積を算出します。

円の面積の計算方法は `面積 = 半径 x 半径 x 3.14`



## 前提知識

pythonを勉強する前に、対話形式のpythonを触ってみましょう。

対話形式のpythonはpythonと話しながら計算をしたりプログラムを実行したりできます。

電卓や、軽くコードを書いてすぐ結果を見たいときに使うことがあります。

### 起動方法

terminalを起動して、

`$ python`

と打ち込みます（頭の$とは、この文章がコマンドであるということを示しています。よって$は実際にterminalに打ち込む必要はありません！`python`だけでいいです）

そうすると、

`>` 

こういったインジケータが出てくると思います。

ここに実際に命令を与えるとpythonが認識してすぐに結果を返してくれます。

では実際に計算してみましょう

`1 + 1` 

ここでエンターキーを押すと、2という結果が返されます。

こういった感じで、対話形式で計算をしてくれます。

色々計算してみます。

 `5 * 5` 

 `10 / 5` 

このようにもちろん掛け算やわり算の算出もできます。

### 変数を使ってみる

以下のコマンドをpythonで実行してみてください。

```text
$ name = "太郎"
$ "私の名前は" + name + "です"
```

このように、情報を一旦保存して、後で使ったりできます。

```text
$ name = "太郎"
```

ここで実際、変数が使われており、情報を保存できる箱をnameと名付け、そこに"太郎"という文字を格納しています。

そして、最後にその文字通しを足し合わせることができます。便利ですね。

### 正方形の面積を求める

```text
$ side = 5
$ side * side
```

これで１辺５cmの正方形の面積を求めることができました。



もっと対話モードについて知りたい場合は以下のリンクを参考にしてください。

[https://websites-manual.com/python-start/](https://websites-manual.com/python-start/)
