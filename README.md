# 指纹浏览器（Fingerprint Browser）

基于 C++ Chromium 开发的指纹浏览器相关技术

## 功能特点：

- **指纹识别防护：** 指纹浏览器通过多种技术手段防护指纹识别，包括对用户特征的屏蔽和混淆，从而减少网站对用户身份的识别准确率。
- **相关产品：**  几乎具有ads,vmlogin 指纹部分的所有功能。个人使用推荐使用ads,vmlogin等。他们的成熟度更高，使用量不大更划算。。我不做卖客户端。
- **相关功能：** 一个新窗口就是一个新的指纹浏览器。管理指纹配置文件即可管理UA,硬件指纹,网络代理,密码填充管理，cookie管理等。
- **代理中转**  支持vmess,vless,socks,http,trojan等多种协议服务器。可配置N台中转机->到落地机。实现本地–>中转机–>落地机。
- **支持多内核版本** 可以提供支持多个chromium内核版本。当前已更新到2023年10月117最新内核
- **实际应用场景** 网页数据获取、tiktok,Facebook 矩阵养号、海外问卷调研。 用户反馈tiktok 注册账号，跨机器登录成功率在85以上。相关的项目已稳定接近3年
- **开发周期短**  拥有完整的js接入方式，可快速接入到自身的应用到场景中。 含：创建指纹浏览器进程，指纹写入生效，加密指纹,代理转发。 无任何自定义网络和后门。
- **多平台**  windows, mac ,Linux 均可开发。

## 支持的指纹和功能
- **指纹：** 时区、WebRtc、地理位置、语言、分辨率、字体、Canvas、Webgl、AudioContext
媒体设备、语音列表、CPU、内存、Do not Track、端口扫描保护

- **其他功能：** 各种类型代理转发 、 网站账号密码填充 、用户数据同步、增加JS自定义函数响应（控制进程，关机，读写数据等等）
- **浏览器开关：**禁止网站播放声音 、禁止图片加载  、禁止浏览器弹出谷歌翻译 、禁止保存密码弹窗 等等



## 联系方式：
- **服务** 可定制浏览器内核版本、接口、服务、指纹功能、代理等。
- **注意** 只提供相关技术和解决方案。 不卖个人客户端，不卖个人客户端，不卖个人客户端。重要的事情说三遍。
- 微信：812376073  
- 设置界面没有展示全部的功能,这里仅仅是个人对作用的展示。实际商业场景下指纹配置功能跟ads 95%类似
- 擅长chromium 源码编译，electron 源码更改编译(例如: 内置node https 证书)。可以指定任意版本

![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/clinet2.png)
![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/client4.png)
![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/client3.png)

## 部分作品展示：
![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/al.png)
![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/xp.png)