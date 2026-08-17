Stash Tiles

![Stash Network Diagnostic Tiles](./copy_DBB6470D-277A-44D3-9CDD-8EDCC0AC8DFC.GIF)
适用于 Stash iOS 的网络诊断 Tile 配置。

🔍 检测内容

* 🌐 国际出口 * 🟢 网络控制中心* 🧠 DNS* 🛡️ WebRTC 检测* 🔐 TLS / HTTPS* 📊 网络质量 * ⚡ QUIC / HTTP3 * 💚 节点健康 * 🌍 第三方服务 

🔗 手动检测网址；

DNS 泄漏：
[DNS Leak Test](https://www.dnsleaktest.com/)

WebRTC 泄漏：
[BrowserLeaks WebRTC Test](https://browserleaks.com/webrtc)

📄ZIKA STASH CONFIG
[Default.yaml Raw](https://raw.githubusercontent.com/lihx0481-create/-Stash-config/main/Default.yaml)



## 🛡️ stash去广告复写
[🇨🇳 国内软件去广告](./Stash/去广告/)

⚠️ 面板真实性说明

本配置尽量只显示实际请求获得的数据。

DNS 查询成功 ≠ DNS 无泄漏
WebRTC 服务可访问 ≠ WebRTC 无泄漏

因此 DNS 和 WebRTC Tile 均保留 「手动检测 →」，用于进行真正的泄漏检测。

无法可靠检测的项目不会伪造 ✓。

本项目用于 Stash 网络状态、连通性及泄漏检测辅助。

检测结果受当前网络、节点、DNS 和目标服务器影响，仅代表检测时的实际状态。