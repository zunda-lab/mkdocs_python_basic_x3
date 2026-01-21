# sortメソッド

文字列が格納されているリストをABC順に並び替えるには、リストのsortメソッドを利用します。

```
並び替え対象のリスト.sort()
```

sortメソッドは、並び替え対象のリストの後ろに「ピリオド・sort・丸カッコ・丸カッコ閉じ」と書きます。

プログラム例を紹介しましょう。

```
fruits_list␣=␣['orange',␣'apple',␣'peach',␣'banana',␣'cherry']
fruits_list.sort()
print(fruits_list)
```

```
 ['apple', 'banana', 'cherry', orange', 'peach' ]
```

並び替え対象のリストには、果物の名前「orange・apple・peach・banana・cherry」が５つの要素として格納され、リストを変数 fruits_list に代入しています。

そして、変数 fruits_list のsortメソッドです。

sortメソッドには戻り値はありません。並び替え対象のリストそのものを並び替えてしまいます。

最後にprint関数でfruits_list 変数をディスプレイに表示します。

果物の名前がアルファベット順に「apple・banana・cherry・orange・peach」と表示されています。print関数でリスト型の変数を表示しているので、最初に角カッコ、最後に角カッコ閉じ、文字列の間にはカンマが表示されています。

以上「英単語をABC順に並べる方法を学ぼう」でした。