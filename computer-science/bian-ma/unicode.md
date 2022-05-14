# Unicode

{% hint style="info" %}
**Unicode**，聯盟官方中文名稱為**統一碼**，是電腦科學領域的業界標準。它整理、編碼了世界上大部分的[文字系統](https://zh.wikipedia.org/wiki/%E6%96%87%E5%AD%97%E7%B3%BB%E7%B5%B1)，使得電腦可以用更為簡單的方式來呈現和處理文字。

Unicode伴隨著[通用字元集](https://zh.wikipedia.org/wiki/%E9%80%9A%E7%94%A8%E5%AD%97%E7%AC%A6%E9%9B%86)的標準而發展，同時也以書本的形式對外發表。<mark style="background-color:yellow;">**Unicode至今仍在不斷增修**</mark>，每個新版本都加入更多新的字元。目前最新的版本為2021年9月公布的14.0.0，已經收錄超過14萬個字元（第十萬個字元在2005年獲採納）。Unicode除了視覺上的字形、編碼方法、標準的[字元編碼](https://zh.wikipedia.org/wiki/%E5%AD%97%E7%AC%A6%E7%BC%96%E7%A0%81)資料外，還包含了字元特性（如大小寫字母）、書寫方向、拆分標準等特性的資料庫。

—[https://zh.wikipedia.org/wiki/Unicode](https://zh.wikipedia.org/wiki/Unicode)
{% endhint %}

計算機起源於美國，他們對英語字符與二進制位之間的關係做了統一規定，並制定了一套字符編碼規則，這套編碼規則被稱爲 ASCII 編碼，一共定義了 128 個字符的編碼規則，這些字符組成的集合就叫做 ASCII 字符集，隨着計算機的普及，在不同的地區和國家又出現了很多字符編碼，比如: 大陸的 GB2312、港臺的 BIG5, 日本的 Shift JIS 等等

由於字符編碼不同，計算機在不同國家之間的交流變得很困難，經常會出現亂碼的問題，比如：對於同一個二進制數據，不同的編碼會解析出不同的字符

當互聯網迅猛發展，地域限制打破之後，人們迫切的希望有一種統一的規則, 對所有國家和地區的字符進行編碼，於是 Unicode 就出現了．

### UTF-8

{% hint style="info" %}
**UTF-8**（**8-bit Unicode Transformation Format**）是一種針對[Unicode](https://zh.wikipedia.org/wiki/Unicode)的可變長度[字元編碼](https://zh.wikipedia.org/wiki/%E5%AD%97%E5%85%83%E7%B7%A8%E7%A2%BC)，也是一種[字首碼](https://zh.wikipedia.org/wiki/%E5%89%8D%E7%BC%80%E7%A0%81)。它可以用一至四個位元組對Unicode字元集中的所有有效編碼點進行編碼，屬於Unicode標準的一部分。由於較小值的編碼點一般使用頻率較高，直接使用Unicode編碼效率低下，大量浪費記憶體空間。UTF-8就是為了解決向下相容ASCII碼而設計，Unicode中前128個字元，使用與ASCII碼相同的二進位值的單個[位元組](https://zh.wikipedia.org/wiki/%E5%AD%97%E8%8A%82)進行編碼，而且字面與ASCII碼的字面一一對應，這使得原來處理ASCII字元的軟體無須或只須做少部份修改，即可繼續使用。因此，它逐漸成為<mark style="background-color:green;">**電子郵件、網頁**</mark>及其他儲存或傳送文字優先採用的編碼方式。

—[https://zh.wikipedia.org/wiki/UTF-8](https://zh.wikipedia.org/wiki/UTF-8)
{% endhint %}

### 不同

* Unicode、UTF-8、UTF-16，終於懂了
* [https://www.readfog.com/a/1638084002220969984](https://www.readfog.com/a/1638084002220969984)
