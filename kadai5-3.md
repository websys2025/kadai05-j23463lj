## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能  
  https://zipcloud.ibsnet.co.jp/api/search
* リクエストとレスポンスのフォーマット
  request: zipcodeを指定する必要  
  responsor:   {"message": null, "results": [{"zipcode": "1000001", "prefcode": "13",
  "address1": "東京都", "address2": "千代田区", "address3": "千代田", "kana1": "ﾄｳｷｮｳﾄ",
  "kana2": "ﾁﾖﾀﾞｸ", "kana3": "ﾁﾖﾀﾞ"}], "status": 200 }
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL  
  https://official-joke-api.appspot.com/random_joke
* エンドポイントと機能  
  jokeをもらう
* リクエストとレスポンスのフォーマット
  URLそのまま  
  {"id": 1, "type": "general", "setup": "Why did the scarecrow win an award?",
  "punchline": "Because he was outstanding in his field!"}
### Q3-3. 感想
* 今回の課題で苦労したこと
  課題２のAPIを調べること
* 演習を通して理解できたこと
  fetchの使い方が分かった
* Web APIの利便性や課題など
