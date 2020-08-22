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
