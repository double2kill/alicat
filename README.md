alicat html
===

这是一个用于生成RS232串口的代码，用于控制流量计A和流量计B的页面，根据当量比和一个流量计流量决定另一个流量计的流量，并且生成对应RS232代码。供学习交流

使用方法
---

在浏览器中打开index.html，选择气体类型和总量程，在某个流量计中输入流量值，同时输入当量比（A/B），即可得到代码，复制并粘贴在超级终端中就可以控制两个流量计按照一定当量比给混合室充气。

tools
---
* [bootstrap](http://getbootstrap.com/2.3.2/)
* [angular](https://github.com/angular/angular)
* [clipboard.js](https://github.com/zenorocha/clipboard.js)
* [font-awesome](http://www.bootcss.com/p/font-awesome/)
* [jquery](http://jquery.com/)