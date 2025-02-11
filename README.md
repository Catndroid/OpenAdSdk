# OpenAdSdk
<hr>

### OpenAdSdk是什么？
这是基于基于裕语言v3(iApp,iYu,v3)制作的轻量化广告服务，为我们提供广告推送的需求。简单配置即可使用，大大缩小的我们的上线时间。内置AdVideoFive，可以快速为用户展示5秒种的广告，为您和您的雇主有好的体验

### 它的应用范围
## 1.静态处理
我们可以使用静态处理的方法进行广告传输，比如在/OpenAdSdk/file/assets/res/demo/有静态的index.html网页配置信息，仅简单修改，就可快速上线展示静态处理的内容。
(警告:可能涉及跨境传输)
## 2.动态处理
我们可以使用动态处理的方法进行广告传输，比如在远程服务器上，上传广告页面，在/OpenAdSdk/file/assets/res/demo/有静态的index.html网页配置信息，修改页面展示到远程服务器，仅简单修改，就可快速上线展示动态处理的内容。
(警告:可能涉及跨境传输)
## 3.可于后端交互
基于上两点实现
## 4.简化网络架构
广告页 --> 请求握手 --> 请求展示广告内容 --> 广告图片 `--> (广告内容被点击) --> 打开浏览器应雇主的URL。
简化了许多，不仅减少了用户的流量，且减小了篡改的可能(XSS跨站攻击)。(这并不代表完全安全)
### 安全性和开源协议
## 1.除关键进程，无任何活动。
## 2.我们严格遵守GPL
GPL具有传染性，不允许修改后和衍生的代码作为闭源的商业软件发布和销售。例如，Linux 操作系统就是采用 GPL 协议。使用该协议的软件，其所有修改的源代码也必须开源。

This Redme.md by Cat in 2月11日,2025年
