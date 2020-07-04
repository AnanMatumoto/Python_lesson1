# Python_lesson1
 パイソン練習１

## ■実行環境
	Google colaboratory

## ■課題
*【じゃんけんゲームを作る】*

1.相手と自分の手を表示させる
 ``` 
   0:グー
   1:チョキ
   2:パー 
	自分の手は入力で受け取れるようにする
	相手の手はランダムで決める
```

2.勝敗を表示する
```
  勝ち、負け、あいこを表示する
  表示が出来たらif elif elseの数を最小限にしてみる
```    

3.①②を関数化する

 ```
 【仕様について】
  ・get_message()
  	引数  ：なし
	戻り値：なし
	内容  ：スタートメッセージを表示する
		
 ・get_hand()
	引数  ：なし
	戻り値：入力された値	
	内容  ：入力を促すメッセージの表示と入力
			
 ・get_you_hand()
	引数：なし
	戻り値：相手の手の値 
	内容：相手の手をランダムで取得 

 ・view_result() 
	引数：hand_diff
	戻り値：なし 
	内容：hand_diffを判断して勝ち or 負け or あいこを表示する
```
