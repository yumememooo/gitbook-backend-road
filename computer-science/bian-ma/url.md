# URL

### URL 編碼

{% hint style="info" %}
百分號編碼（英語：Percent-encoding），又稱：URL編碼（URL encoding）是特定上下文的統一資源定位符 （URL）的編碼機制，實際上也適用於統一資源標誌符（URI）的編碼。
{% endhint %}

{% hint style="info" %}
統一資源定位符（英語：Uniform Resource Locator，縮寫：URL，或稱統一資源定位器、定位位址、URL位址\[1]）俗稱網頁位址，簡稱網址，是網際網路上標準的資源的位址（Address），如同在網路上的門牌。

統一資源定位符的完整格式如下：

&#x20;\[協定類型]://\[存取資源需要的憑證資訊]@\[伺服器位址]:\[埠號]/\[資源層級UNIX檔案路徑]\[檔名]?\[查詢]#\[片段ID]
{% endhint %}

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
