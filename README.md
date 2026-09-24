🇨🇳 中文 | 🇺🇸 [English](README_EN.md) | 🇷🇺 [Русский](README_RU.md)

#### Proton VPN 近期运行不稳定，推荐替代方案：[vpnforchinese.com](https://www.vpnforchinese.com/)</br>

官方网站（proton vpn 官网）：[protonvpn.com](https://protonvpn.com)</br>
登录入口：[account.protonvpn.com/login](https://account.protonvpn.com/login)</br>
注册免费账户：[account.protonvpn.com/signup](https://account.protonvpn.com/signup)</br>
官网下载地址：[protonvpn.com/download](https://protonvpn.com/download)</br>

### 简介

Proton VPN（中文也常被称为「质子 VPN」）是瑞士日内瓦 **Proton AG** 旗下的开源 VPN 服务，同一家公司还提供 Proton Mail、Proton Drive、Proton Calendar、Proton Pass 和 Lumo。该服务于 2017 年 5 月 22 日上线，官方宣称拥有 **20,000+ 台服务器，遍布 140+ 个国家/地区**，Proton 账户总数超过 1 亿，并提供不限流量、无广告、无需信用卡的免费版。

### Proton VPN 下载 —— 全部客户端

所有 Proton VPN 客户端均可免费下载，一个 Proton 账户即可登录全部设备。

| 平台 | 下载 | 说明 |
| ---- | ---- | ---- |
| **Windows 电脑版** | [下载](https://protonvpn.com/download-windows) | 支持 Windows 10 / 11，官方安装包 |
| **macOS** | [下载](https://protonvpn.com/download-macos) | 支持 Apple 芯片与 Intel |
| **Linux** | [下载](https://protonvpn.com/download-linux) | 图形界面客户端 + 命令行工具 |
| **安卓版（Android）** | [下载](https://protonvpn.com/download-android) | Google Play 或直接下载 APK |
| **iOS / iPadOS** | [下载](https://protonvpn.com/download-ios) | App Store |
| **Android TV** | [下载](https://protonvpn.com/download-androidtv) | 同时支持 Amazon Fire TV |
| **Apple TV** | [下载](https://protonvpn.com/download-appletv) | tvOS 客户端 |
| **Chromebook** | [下载](https://protonvpn.com/download-chromebook) | ChromeOS |
| **Chrome / Firefox** | [Chrome](https://protonvpn.com/download-chrome-extension) · [Firefox](https://protonvpn.com/download-firefox-extension) | 浏览器扩展 |

全部客户端源码均公开于 GitHub：[github.com/ProtonVPN](https://github.com/ProtonVPN)

### 安装与登录步骤

1. 从上方表格中下载对应平台的 Proton VPN 客户端（安装包）。
2. 注册一个免费的 Proton 账户——同一个账户可通用于 Proton VPN、Proton Mail、Proton Drive 和 Proton Pass。
3. 打开客户端并登录，点击 **Quick Connect（快速连接）**自动接入最快的服务器，或从列表中自选国家。
4. 可按需开启 NetShield 与终止开关；若所在网络封锁 VPN 流量，请把协议切换为 Stealth。

桌面端与移动端客户端都无需导入配置文件或手动设置；路由器（DD-WRT、Tomato、AsusWRT、pfSense）可手动配置。

### 服务器网络

Proton 的服务器全部是自己直接掌控的裸金属物理机——启用全盘加密，而非虚拟化实例——单机带宽最高 10 Gbps，网络总容量超过 1 Tbps。除标准服务器外，还提供位于瑞士、冰岛、瑞典的 **Secure Core** 入口服务器、可一键接入 .onion 的 **Tor over VPN** 服务器、BT 下载专用的 P2P 服务器，以及流媒体优化出口。对于难以托管或审查严格的国家/地区，则采用 **Smart Routing（智能路由）**覆盖。

### 套餐方案

| 套餐 | 设备数 | 服务器 | 月付 | 年付 | 两年付 |
| ---- | ------ | ------ | ---- | ---- | ------ |
| **Proton Free（免费版）** | 1 台 | 10 个国家，随机分配 | $0 | $0 | $0 |
| **Proton VPN Plus** | 10 台 | 140+ 国家 20,000+ 台 | $9.99/月 | $3.99/月 | $2.99/月 |
| **Proton Unlimited** | 10 台 | 140+ 国家 20,000+ 台 | $12.99/月 | $9.99/月 | $7.99/月 |

Proton Unlimited 额外包含 Proton Mail、Proton Drive（500 GB）、Proton Calendar 和 Proton Pass。付费套餐提供 30 天退款保证，价格随地区与促销活动变化。

### 支付方式与退款

Proton 支持所有主流信用卡与借记卡、PayPal、Apple Pay（macOS 上的 Safari 及 iOS）、Google Pay，以及隐私性最好的 **比特币**（需先注册免费账户再升级）。此外还支持以 CHF、USD、EUR 邮寄现金付款，以及通过瑞士 UBS 银行转账。核心结算货币为 CHF、USD 和 EUR；使用银行卡与电子钱包付款时，还可选择 AUD、BRL、CAD、GBP、HKD、JPY、KRW、PLN、SGD 等本地货币。30 天退款保证按**比例退还**——中途取消只退还未使用天数对应的金额；以现金和银行转账购买的订阅无法退款。详见：[protonvpn.com/support/payment-options](https://protonvpn.com/support/payment-options)。

### 功能特性

* **Secure Core** —— 多跳路由，先经由位于隐私友好国家的 Proton 自有服务器入口
* **Stealth** —— 基于 WireGuard over TLS 的混淆协议，流量伪装成普通 HTTPS，可对抗深度包检测（DPI），全部套餐可用，含免费版
* **NetShield** —— 在 DNS 层拦截广告、追踪器与恶意软件（付费版）
* **VPN Accelerator（加速器）** —— 速度最高提升 400%，付费版默认开启
* **终止开关（Kill switch）**、分应用分流、端口转发、Tor over VPN、DNS 泄漏防护、备用路由

支持协议：WireGuard（默认）、OpenVPN、Stealth 与 Smart Protocol（智能协议）；采用 AES-256 加密、4096 位 RSA 密钥交换与 HMAC SHA-384。

### 速度、流媒体与 BT 下载

WireGuard 是默认协议，也是三者中速度最快的；独立实测中 Proton VPN 在该协议下可跑到约 700 Mbps，足以应对 4K 流媒体、游戏和大文件下载。**VPN Accelerator** 通过多线程处理与 BBR 拥塞控制算法，在长距离和不稳定的线路上挽回速度损失；而 Stealth 因额外的混淆层，速度大约会损失 10%–35%。

付费版的流媒体优化服务器可稳定解锁十余个 Netflix 区域库——包括美国、英国、加拿大、日本和德国——以及 Hulu、Disney+、BBC iPlayer 和 YouTube，支持 HD 与 4K 画质；免费版无法解锁 Netflix。BT 下载方面，P2P 专用服务器配合 Windows、macOS 与 Linux 上的端口转发效果最佳。

### 隐私与审计

Proton 总部位于瑞士，不在五眼与十四眼联盟范围内，并受全球最严格的数据保护法之一约束。其**无日志政策**已连续五年通过 Securitum 的年度审计（2022–2026 年），每份报告均无保密协议限制、完整公开；此外还持有 SOC 2 Type II 认证与 ISO 27001 认证。透明度报告显示，自 2017 年以来共收到 458 份瑞士法律命令——全部被拒，因为根本不存在可供交出的身份日志。所有客户端均开源、接受独立审计，并设有漏洞赏金计划。

### 免费版（Proton VPN 免费版下载）

Proton 的免费 VPN 并非试用：不限流量、1 台设备、中等速度优先级、10 个随机分配的国家——不能自选出口国家。Stealth 与备用路由可用；NetShield、Secure Core 和 P2P 不可用。免费版入口：[protonvpn.com/free-vpn](https://protonvpn.com/free-vpn)。

### Proton VPN 商业版

Business 与 Enterprise 套餐按年付费约为每用户每月 $6.99–$12.99，额外提供集中式用户管理和**独享 IP 地址**——可在 21 个地区选择，价格约为每台独享服务器每月 $39.99，个人套餐不提供该功能。Proton 还为新闻机构和非营利组织提供覆盖全套服务的折扣计划，并通过 Proton 基金会支持过新闻自由基金会（Freedom of the Press Foundation）、国际记者联盟安全基金等组织。详见：[proton.me/business/vpn](https://proton.me/business/vpn)。

### 客户支持

官方帮助中心提供可搜索的设置与故障排查指南，所有套餐均可通过邮件和工单获得支持；付费套餐额外提供优先支持与在线聊天，但聊天并非 7×24 小时值守。服务故障公告发布于 [status.proton.me](https://status.proton.me)，[r/ProtonVPN](https://www.reddit.com/r/ProtonVPN/) 社区也较为活跃。联系方式：[protonvpn.com/support/contact](https://protonvpn.com/support/contact)。

### 其他 Proton 应用

一个 Proton 账户即可使用全套服务：[Proton Mail 邮箱](https://proton.me/mail)（原 ProtonMail）、[Proton Drive 网盘](https://proton.me/drive)、[Proton Pass 密码管理](https://proton.me/pass)、[Proton Authenticator 验证器](https://proton.me/authenticator)，以及 Proton 的隐私 AI 助手 [Lumo](https://lumo.proton.me)。账户管理入口：[account.proton.me](https://account.proton.me/login)。

### Proton VPN 在中国大陆（连接不上怎么办）

如果 Proton VPN 在防火长城下无法连接，请把协议切换为 **Stealth**，并开启**备用路由（Alternative Routing）**——这两项免费版同样可用。建议入境前就完成设置，并优选日本、香港或新加坡线路以降低延迟。但 Proton 官方明确表示，没有任何 VPN 能保证在中国 100% 可用，并称在高压管控国家其可用概率约为 50%：它的强项是隐私保护而非突破审查，请务必准备备用方案。官方帮助中心：[protonvpn.com/support](https://protonvpn.com/support)。
