# 指纹浏览器（Fingerprint Browser）

基于 C++ Chromium 开发的指纹浏览器工具

## 功能特点：

- **指纹识别防护：** 指纹浏览器通过多种技术手段防护指纹识别，包括对用户特征的屏蔽和混淆，从而减少网站对用户身份的识别准确率。
- **竞品：** ads,vmlogin等。
- **相关功能：** 随机UA,硬件指纹,网络代理,密码填充管理，cookie管理等。
- **代理中转**  支持vmess,vless,socks,http,trojan等多种协议服务器。可配置N台中转机->到落地机。实现本地–>中转机–>落地机。
- **支持多内核版本** 可以提供支持多个chromium内核版本。当前已更新到2023年10月117最新内核。但当前演示包只有一个版本2022年9月107内核。
- **功能可以定制** 可以定制浏览器内核版本和接口服务等。
- **实际应用场景** 网页数据获取、tiktok,Facebook 矩阵养号、海外问卷调研。 用户反馈tiktok 注册账号，跨机器登录成功率在80% 以上。项目已稳定接近3年
- **开发周期短**  平均2周内即可接入到自己的应用到场景中。服务含：创建指纹浏览器进程，指纹写入生效，加密指纹,代理转发。 无任何自定义网络和后门。
- **多平台**  支持windows, mac 版本


## 支持的指纹和功能
- **指纹：** 时区、WebRtc、地理位置、语言、分辨率、字体、Canvas、Webgl、AudioContext
媒体设备、语音列表、CPU、内存、Do not Track、端口扫描保护

- **其他功能：** 各种类型代理转发 、 网站账号密码填充 、用户数据同步、用户数据解密(用户目录下的密码,cookie)
- **浏览器开关：**禁止网站播放声音 、禁止图片加载 、禁止视频加载 、禁止浏览器弹出谷歌翻译 、禁止保存密码弹窗




## 联系方式：

- 微信：812376073
- 设置界面没有展示全部的功能,这里仅仅是个人对作用的展示。实际商业场景下指纹配置功能跟ads 95%类似


感谢您的关注和支持，让我们一起为用户创造一个更加隐私安全的网络浏览环境！

![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/client1.png)
![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/clinet2.png)
![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/client4.png)
![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/client3.png)