# Introduction

- requests.Session を継承したので宣言するだけで使えるようになりました
- `import uribo`していろんなことに使ってください
- 作りかけです
- schedule 使わないなら time と threading はコメントアウトして OK
- import keys は消していいです

## 作りかけの部分

- schedule を True にすると 15 分でログアウトになるやつを自動で延長するようにしたかった
- 監視 bot とか作るなら必要そう
- うりぼーネットのトップページで `extendSession()`を発火すれば伸びるっぽいことはわかった
- でもそのために Qt 入れて dryscrape なり selenium なり動かすのはめんどくさかった
- `_extend()` の所にその処理かけば多分いける気がする。誰か頑張ってください
- あとログインでエラー出た時の処理とかも面倒なのであまりしてない
