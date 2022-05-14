# URL

### URL 編碼

\
\
[https://www.796t.com/post/MTU0dDY=.html](https://www.796t.com/post/MTU0dDY=.html)\
查詢字串是URL的一部分，其中包含可以傳遞給Web應用程式的資料。該資料需要進行編碼，並且使用url.QueryEscape進行編碼。它執行通常也稱為URL encoding的操作。\
fmt.Println( webpage + "?image=" + url.QueryEscape(image))\
你真的瞭解URLEncode嗎？\
\
[https://iter01.com/587250.html](https://iter01.com/587250.html)\
中文不在ASCII字元中，因此中文出現在URL地址中時，需要進行編碼；同時可書寫的ASCII字元中，存在一些不安全字元也需要轉碼，如空格（空格容易被忽略，也容易意想不到的原因引入）。\
\
URL 編碼\
[https://openhome.cc/Gossip/Encoding/URLEncoding.html](https://openhome.cc/Gossip/Encoding/URLEncoding.html)\
在 URI 的規範中定義了一些保留字元（Reserved character），必須在 % 字元之後以十六進位數值表示方式\
其實是現在的瀏覽器很聰明，會自動將上述的 URI 編碼顯示為中文。貼到純文字檔案中，就會看到 URI 編碼的結果

```
https://translate.google.com.tw/?hl=zh-TW
urlencode
https%3A%2F%2Ftranslate.google.com.tw%2F%3Fhl%3Dzh-TW
```
