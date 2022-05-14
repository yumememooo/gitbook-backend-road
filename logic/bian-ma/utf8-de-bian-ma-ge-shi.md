# UTF-8 的編碼格式

{% hint style="info" %}
**UTF-8**（**8-bit Unicode Transformation Format**）是一種針對[Unicode](https://zh.wikipedia.org/wiki/Unicode)的可變長度[字元編碼](https://zh.wikipedia.org/wiki/%E5%AD%97%E5%85%83%E7%B7%A8%E7%A2%BC)，也是一種[字首碼](https://zh.wikipedia.org/wiki/%E5%89%8D%E7%BC%80%E7%A0%81)。它可以用一至四個位元組對Unicode字元集中的所有有效編碼點進行編碼，屬於Unicode標準的一部分。由於較小值的編碼點一般使用頻率較高，直接使用Unicode編碼效率低下，大量浪費記憶體空間。UTF-8就是為了解決向下相容ASCII碼而設計，Unicode中前128個字元，使用與ASCII碼相同的二進位值的單個[位元組](https://zh.wikipedia.org/wiki/%E5%AD%97%E8%8A%82)進行編碼，而且字面與ASCII碼的字面一一對應，這使得原來處理ASCII字元的軟體無須或只須做少部份修改，即可繼續使用。因此，它逐漸成為電子郵件、網頁及其他儲存或傳送文字優先採用的編碼方式。
{% endhint %}
