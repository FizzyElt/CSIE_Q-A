## JavaScript 相關問題
* * * 

#### 何謂 this ?
this 關鍵字等於當前執行上下文的 ThisBinding 的值<br>
this 會被自動定義於每個函數作用域當中<br>
判斷 this 的值取決於函數如何被呼叫。
* [ecma規格書11.1.1](https://www.ecma-international.org/ecma-262/5.1/#sec-11.1.1)
* [淺談 JavaScript 頭號難題 this：絕對不完整，但保證好懂](https://blog.techbridge.cc/2019/02/23/javascript-this/)
* [你不知道的JavaScript（上卷）74頁](https://github.com/woai3c/recommended-books/blob/master/%E5%89%8D%E7%AB%AF/%E4%BD%A0%E4%B8%8D%E7%9F%A5%E9%81%93%E7%9A%84JavaScript%EF%BC%88%E4%B8%8A%E5%8D%B7%EF%BC%89.pdf)
* * *
#### var、let、const 的區別是什麼 ?
var為 JS 基本的宣告變數的方式，其作用範圍則為全域性 (global) (亦即包納於全域物件之內)。<br>
let、const 是ES6新增宣告變數的語法，只作用在當前區塊的變數(大括號內)。<br>
var 宣告會有 hoisting 現象，let、const則無，<br>
const 在宣告過後無法再對變數重新賦值及重複宣告。
* [MDN let](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Reference/Statements/let)
* [MDN const](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Reference/Statements/const)
* [MDN var](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Reference/Statements/var)
* [Var, Let, and Const – What's the Difference?](https://www.freecodecamp.org/news/var-let-and-const-whats-the-difference/)