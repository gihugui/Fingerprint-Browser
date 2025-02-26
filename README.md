# 指纹浏览器（Fingerprint Browser）

基于 C++ Chromium 内核开发的指纹浏览器相关技术

## 功能特点：

- **指纹识别防护**：通过多种技术手段防护指纹识别，包括对用户特征的屏蔽和混淆，减少网站对用户身份的识别准确率。
- **功能丰富**：
  - 一个新窗口即为一个全新的指纹浏览器。
  - 管理指纹配置文件即可管理UA、硬件指纹、网络代理、密码填充管理、cookie管理等。
- **代理中转**：支持vmess、vless、socks、http、trojan等多种协议服务器。可配置多台中转机至落地机，实现本地到中转机再到落地机的连接。
- **多内核版本支持**：支持多个Chromium内核版本（100-130版本）。
- **实际应用场景**：适用于网页数据获取、TikTok/Facebook矩阵养号、海外问卷调研等场景。用户反馈在TikTok、谷歌广告业务方面成功率超过85%，特别是安卓版成功率最高。相关项目已稳定运行接近3年。
- **多平台支持**：支持Windows、macOS、Linux、Android等多个平台。


### 支持的指纹和功能

- User Agent
- 语言
- 时区
- 地理位置
- 分辨率
- 字体指纹
- WebRTC
- WebGL 图像
- WebGL Info
- Canvas
- AudioContext
- Speech Voices
- Do Not Track
- Client Rects
- 媒体设备
- 设备名称
- 硬件并发数
- 设备内存
- SSL指纹设置
- 端口扫描保护
- 硬件加速模式
- 电池状态
- 网络类型

#### 其他功能

- 默认打开指定网站
- 启动自带指定插件
- 禁止网站播放声音
- 禁止浏览器弹出谷歌翻译
- 禁止保存密码弹窗
- 禁止获取地理位置
- referrer目标来源替换
- 图标替换
- 进程名称替换
- 各种类型代理转发
- 网站账号密码填充
- 用户数据同步
- 增加JS自定义函数响应（控制进程、关机、读写数据等）


## 使用说明

为了让更多开发者能够受益并参与到Chromium内核的改进与开发中，我决定将指纹浏览器客户端免费提供给所有用户使用。您可以自由下载。

通过网盘分享的文件: https://pan.baidu.com/s/1wx_vDuLQyhEBLoIXbCcyXA 提取码: rnhb

如果您在使用过程中遇到问题或需要技术支持，欢迎随时联系我。同时对于更深入的技术咨询和定制化开发服务，您可以选择付费咨询。


## 联系方式：
- **注意** 可提供相关技术服务咨询。 上面指纹相关功能的技术100-500￥/单个
- 微信：812376073 
- 擅长chromium 源码编译，electron 源码更改编译(例如: 内置node https 证书)。可以指定任意版本

![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/clinet2.png)
![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/client4.png)
![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/client3.png)
![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/android.png)

## 部分作品展示：
![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/al.png)
![指纹浏览器客户端](https://github.com/gihugui/Fingerprint-Browser/raw/main/img/xp.png)