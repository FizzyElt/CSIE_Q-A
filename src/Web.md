## Web相關問題
----------
#### CORS 是什麼 ?
跨來源資源共用(Cross-Origin Resource Sharing)，是一種使用額外 HTTP 標頭令目前瀏覽網站的使用者代理取得存取其他來源（網域）伺服器特定資源權限的機制。<br>
基於安全性考量，程式碼所發出的跨來源 HTTP 請求會受到限制。例如，XMLHttpRequest 及 Fetch 都遵守同源政策（same-origin policy）。這代表網路應用程式所使用的 API 除非使用 CORS 標頭，否則只能請求與應用程式相同網域的 HTTP 資源。<br>
所以可跨域存取的有
```html
<img />
<video />
<audio />
<iframe />
<link rel="stylesheet" href /> 
<script src="" />
```
- [和 CORS 跟 cookie 打交道](https://medium.com/d-d-mag/%E5%92%8C-cors-%E8%B7%9F-cookie-%E6%89%93%E4%BA%A4%E9%81%93-dd420ccc7399)
- [MDN CORS](https://developer.mozilla.org/zh-TW/docs/Web/HTTP/CORS)
----------
#### 何謂 AJAX (Asynchronous JavaScript and XML) ?
AJAX 應用可以僅向伺服器傳送並取回必要的資料，並且由JavaScript 來處理伺服器的回應，使伺服器與瀏覽起之間交換的資料大幅減少，減輕伺服器負擔。<br>
也因為有 AJAX 我們可以在不重新換頁的情況下獲取資料並且將資料替換到畫面上，資料的格式不限於 XML，現今已 JSON 較為常見。
- [wiki AJAX](https://zh.wikipedia.org/zh-tw/AJAX)
- [MDN AJAX](https://developer.mozilla.org/zh-TW/docs/Web/Guide/AJAX)
----------
#### 什麼是 REST/RESTful (Representational State Transfer) ?
RESTful是一種軟體架構風格，並不是一個標準及規範，通常應用在http 中，利用 http 的 method 來定義要對資源做的動作，URI作為資源的名稱，以及資源呈現的方式作為形容詞。

| Nouns        | Verbs | Content Types |
| ------------ | ----- | ------------- |
| HTTP methods | URI   | XML, JSON...  |

- [RESTful API 設計準則與實務經驗](https://www.webguide.nat.gov.tw/News_Content.aspx?n=531&s=2918)
- [Learn REST: A RESTful Tutorial](https://www.restapitutorial.com/) 
- [Restful API Design 心得分享 by TritonHo](https://github.com/TritonHo/slides/blob/master/Taipei%202016-04%20talk/RESTful%20API%20Design-tw-2.1.pdf) 
----------
#### 什麼是 DOM (Document Object Model) ?
DOM 是用來表示和與任何HTML 或 XML 文件互動的 API。<br>
DOM 是一個載入於 browser 中的文件模組，它的表示方式像樹的節點一樣, 每個節點代表著文件的一部分(如：element、 文字或留言)。
- [MDN DOM](https://developer.mozilla.org/zh-TW/docs/Web/API/Document_Object_Model)
----------
  #### 什麼是 Cookie ?
  Cookie 是一個網站通過瀏覽器訪問在訪客電腦裡留下的一小段訊息，最大可存放 4KB (4096 Bytes)。
- [wiki Cookie](https://zh.wikipedia.org/zh-tw/Cookie)
- [MDN Cookie](https://developer.mozilla.org/zh-TW/docs/Glossary/Cookie)
- [MDN Document.cookie](https://developer.mozilla.org/zh-CN/docs/Web/API/Document/cookie)
- [RFC 6265 page27](https://tools.ietf.org/html/rfc6265#page-27)
----------
