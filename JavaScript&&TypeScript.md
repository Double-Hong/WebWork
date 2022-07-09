# JavaScript
JavaScript 是 Web 的编程语言。所有现代的 HTML 页面都可以使用 JavaScript。  
JavaScript是一种轻量级的编程语言、脚本语言，是可插入HTML页面的编程代码。在插入HTML页面后，可以由现代的所有浏览器执行。  
JavaScript可以提取HTML中的内容，改变HTML的内容，直接写入HTML输出流、对事件进行反应、改变图像等等。  
* 用法  
要在HTML中插入JavaScript，那JavaScript的代码必须位于`<script></script>`中，在其中，你可能会使用一些你写的函数或者console之类的东西。Web网页会在刚进入页面时执行相应的功能。  
JavaScript就有点像C语言一样，都是先定义一些变量，然后对变量赋值，再使用自己所写的函数对变量进行操作。  
* JavaScript 变量  
与代数一样，JavaScript 变量可用于存放值（比如 x=5）和表达式（比如 z=x+y）。
变量可以使用短名称（比如 x 和 y），也可以使用描述性更好的名称（比如 age, sum, totalvolume）。  
1.变量必须以字母开头  
2.变量也能以 $ 和 _ 符号开头（但是并不推荐）  
3.变量名称对大小写敏感（y 和 Y 是不同的变量）  
* JavaScript 数据类型  
基本类型:   
  字符串（String）、数字(Number)、布尔(Boolean)、空（Null）、未定义（Undefined）、Symbol。  
对象类型:  
  对象(Object)、数组(Array)、函数(Function)，还有两个特殊的对象：正则（RegExp）和日期（Date）  
  JavaScript有动态类型，即相同的变量可以用作不同的类型  
  * JavaScript 字符串  
  字符串是存储字符的变量。  
  字符串可以是引号中的任意文本。  
  `var myname="JavaScript";`  
  * JavaScript 数字  
  JavaScript 只有一种数字类型。数字可以带小数点，也可以不带。 
  `var x1=34.00;var x2=34;`   
  极大或极小的数字可以通过科学（指数）计数法来书写：
  `var y=123e5;var z=123e-5;`
  * JavaScript 布尔  
  布尔（逻辑）只能有两个值：true 或 false。布尔常用在条件测试中。
  `var x=true;var y=false;`  
  * JavaScript 数组  
  创建名为food的数组:`var food=["apple","chicken","beef"]`。  
* 操作符  
  * 一元操作符 `++ --`  
  * 布尔操作符 `&& || !`  
  * 算术操作符 `+ - * / %`  
  * 关系操作符 `<> <=>= == === != !==`  
  * 条件（问号）操作符 `? :`  
  * 赋值操作符 `= += -+ *= /= %=`  
  # TypeScript    
  TypeScript是JavaScript类型的超集,它可以编译成纯JavaScript。  
  TypeScript 程序由以下几个部分组成：模块、函数、变量、语句和表达式、注释。  
  使用以下 TypeScript 程序来输出 "Hello World" ：`const hello : string = "Hello World!";console.log(hello)`  
    * 空白和换行  
    TypeScript 会忽略程序中出现的空格、制表符和换行符。  
    空格、制表符通常用来缩进代码，使代码易于阅读和理解。  
    * TypeScript 区分大小写  
    TypeScript 区分大写和小写字符  
    * 分号是可选的  
    每行指令都是一段语句，可以使用分号或不使用， 分号在 TypeScript 中是可选的。  
    * TypeScript 注释  
    单行注释 `//`后面的内容都是注释内容。  
    多行注释`/* */`这可以多行注释。
    * TypeScript 与面向对象  
    TypeScript 是一种面向对象的编程语言。  
    也就是说TypeScript可以在js中声明类和对象，用js进行调用。  
    