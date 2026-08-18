🛡️ ZIKA STASH 配置中心

Zika 自维护的 Stash 配置、复写、规则集与网络检测工具集合。

⸻

📡 ZIKA STASH 配置文件

📄 Default.yaml Raw

⸻

🛡️ Stash 去广告复写

🇨🇳 国内软件去广告

🌍 国际媒体去广告

⸻

⚠️ 面板真实性说明

本项目尽量只显示实际请求、实际检测以及实际存在的数据。

DNS 查询成功 ≠ DNS 无泄漏
WebRTC 服务可访问 ≠ WebRTC 无泄漏

因此 DNS 和 WebRTC 检测项目均保留「手动检测」方式，用于进行真正的泄漏检测。

无法可靠检测的项目不会伪造结果。

本项目用于 Stash 网络状态、连通性及泄漏检测辅助。

检测结果受当前网络、节点、DNS 和目标服务器影响，仅代表检测时的实际状态。

⸻

🔍 网络检测

DNS 泄漏

🧪 DNS Leak Test

WebRTC 泄漏

🧪 BrowserLeaks WebRTC Test

⸻

📁 项目结构

-Stash-config/
│
├── README.md
├── Default.yaml
│
└── Stash/
    │
    ├── 去广告/
    │   ├── Qishui-No-Ads-Zika-2026.stoverride
    │   └── WeChat-Zika-2026.stoverride
    │
    └── 国际媒体去广告/
        ├── Instagram-Zika-2026.stoverride
        └── Bilibili-Zika-2026.stoverride

⸻

🧩 Zika 自维护原则

* 自己维护
* 自己测试
* 不直接套用第三方完整配置
* 不伪造检测结果
* 不隐藏未知问题
* 规则尽量针对实际请求编写
* 保持 Stash 配置结构清晰

⸻

📌 更新记录

2026

持续更新：

* Stash 配置
* 去广告复写
* 国内软件
* 国际媒体
* DNS / WebRTC 检测
* 网络连通性
* 图标与资源

⸻

👤 Zika

Zika Stash Config

持续维护中........