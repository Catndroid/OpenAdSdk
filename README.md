# OpenAdSdk
## 这篇短文将您快速入门OpenAdSdk，帮助您快速了解和如何使用。

## OpenAdSdk是什么？
这是基于裕语言v3(iApp,iYu,v3)制作的轻量化广告的Android服务，为用户提供广告推送的需求。简单配置即可使用，大大缩小了上线时间。内置AdVideoFive，可以快速为用户展示5秒种的广告，为您和您的雇主有好的体验。

## 它的应用范围
### 1.静态处理
我们可以使用静态处理的方法进行广告传输，比如在/OpenAdSdk/file/assets/res/demo/有静态的index.html网页配置信息，仅简单修改，就可快速上线展示静态处理的内容。
(警告:可能涉及跨境传输)
### 2.动态处理
我们可以使用动态处理的方法进行广告传输，比如在远程服务器上，上传广告页面，在/OpenAdSdk/file/assets/res/demo/有静态的index.html网页配置信息，修改页面展示到远程服务器，仅简单修改，就可快速上线展示动态处理的内容。
(警告:可能涉及跨境传输)
### 3.可于后端交互
基于上两点实现
### 4.简化网络架构
广告页 --> 请求握手 --> 请求展示广告内容 --> 广告图片 `--> (广告内容被点击) --> 打开浏览器应雇主的URL。
简化了许多，不仅减少了用户的流量，且减小了篡改的可能(XSS跨站攻击)。(这并不代表完全安全)
## 安全性和开源协议
### 1.除关键广告进程，我们不会进行网络传输。
### 2.我们严格遵守Apache Licence 2.0
Apache Licence 2.0：和 BSD 类似，鼓励代码共享和最终原作者的著作权，允许源代码修改和再发布（作为开源或商业软件）。需要给代码的用户一份 Apache Licence；如果修改了代码，要在被修改的文件中说明；在衍生的代码中（修改和有源代码衍生的代码中）需要带有原来代码中的协议、商标、专利声明和其他原来作者规定需要包含的说明；如果再发布的产品中包含一个 Notice 文件，则在 Notice 文件中需要带有 Apache Licence，且可以在 Notice 中增加自己的许可，但不可以对 Apache Licence 构成更改。


<a href="https://www.1145117.xyz">欢迎到访我的个人网站: https://www.1145117.xyz</a><br>
<a href="https://t.me/minopenadsdk">官方中文TG: https://t.me/minopenadsdk</a><br>
<a href="https://t.me/mjnopenadsdk">Official English Telegram: https://t.me/mjnopenadsdk</a><br>

This Redme.md by Cat in 2月11日,2025年
