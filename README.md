# LINEbot版後悔しています
登録者千人間近！　　
ありがとう😃　　
## 最近研究が忙しく管理全部譲りたいのでやりたい方いたら至急メールくれや  
ソース欲しい人も至急メールくれや　　
アーキテクチャを大雑把にいうと  
発言を受け取る→DBに入れる→毎日それらを学習→どんどん賢くなってく  
スタックは鯖:heroku、DB:ポスグレ、LINE拡張:messsagingAPI
言語はほぼPython(3系)

# syamu_bot
syamu_gameと会話しよう

## 使い方（CUI版）

```
$ cd engine
$ python bot.py
```

quitで終了します

## 現在の機能
・受け取った単語に対してword2vecによるsyamuの世界観からの文章生成


・syamuを複数体用意してそれぞれに対話させる（強化学習では無いです）


・botの知識は語録から生成、ユーザーから受け取ったことがを知らなかった場合それを学習する


・ブラウザによるGUIでの会話（jqueryによるAjaxを用いています）


・極性辞書を用いたこちらからの発言、問いかけに対してsyamuの心境を数値で表し感情を備える  
