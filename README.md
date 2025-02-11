# OpenAdSdk

## 这篇短文将帮助您快速了解 OpenAdSdk 并掌握其使用方法。

## OpenAdSdk 是什么？
这是基于裕语言 v3（iApp，iYu，v3）制作的轻量化广告 Android 服务，能够为用户提供广告推送功能。通过简单配置即可使用，从而大大缩短上线时间。它内置了 AdVideoFive，可以快速为用户展示 5 秒的广告，为您和您的雇主带来良好的体验。

## 它的应用范围
### 1. 静态处理
我们可以使用静态处理方法进行广告传输。例如，在 `/OpenAdSdk/file/assets/res/demo/` 中有静态的 `index.html` 网页配置信息，仅需简单修改，即可快速上线展示静态内容。
（**警告**：可能涉及跨境传输）

### 2. 动态处理
我们也可以使用动态处理方法进行广告传输。例如，将广告页面上传到远程服务器，修改 `/OpenAdSdk/file/assets/res/demo/` 中的 `index.html` 网页配置信息，使其展示来自远程服务器的内容，仅需简单修改，即可快速上线展示动态内容。
（**警告**：可能涉及跨境传输）

### 3. 后端交互
基于上述两点实现。

### 4. 简化网络架构
广告页 → 请求握手 → 请求展示广告内容 → 广告图片 →（广告内容被点击）→ 打开浏览器访问雇主的 URL。
这种方式简化了许多环节，不仅减少了用户的流量，还降低了篡改的可能性（例如 XSS 跨站攻击）。不过，这并不意味着完全安全。

## 安全性和开源协议
### 1. 除关键广告进程外，我们不会进行网络传输。
### 2. 我们严格遵守 Apache License 2.0
Apache License 2.0：与 BSD 类似，该协议鼓励代码共享并尊重原作者的著作权。它允许对源代码进行修改和再发布（无论是作为开源软件还是商业软件）。具体要求包括：
- 向代码使用者提供一份 Apache License。
- 如果修改了代码，需在被修改的文件中说明。
- 在衍生代码中（包括修改后的代码和基于源代码衍生的代码）需保留原代码中的协议、商标、专利声明以及其他原作者要求包含的说明。
- 如果再发布的产品中包含一个 NOTICE 文件，则需在 NOTICE 文件中包含 Apache License，并且可以在 NOTICE 中增加自己的许可，但不得对 Apache License 进行更改。

欢迎访问我的个人网站：[https://www.1145117.xyz](https://www.1145117.xyz)  
官方中文 TG：[https://t.me/minopenadsdk](https://t.me/minopenadsdk)  
官方英文 Telegram：[https://t.me/mjnopenadsdk](https://t.me/mjnopenadsdk)  

本 README.md 由 Cat 编写，于 2025 年 2 月 11 日。

<a href="./REDMEENGLISH.md">OpenAdSdk English Page</a>