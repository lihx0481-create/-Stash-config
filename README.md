Stash Network Diagnostic Tiles

![Stash Network Diagnostic Tiles](./copy_DBB6470D-277A-44D3-9CDD-8EDCC0AC8DFC.GIF)
适用于 Stash iOS 的网络诊断 Tile 配置。

🔍 检测内容

* 🌐 国际出口 — 真实获取出口 IP、地区、网络组织及 RTT
* 🟢 网络控制中心 — 显示 Stash 版本、Build 等运行信息
* 🧠 DNS 检测 — 真实 Cloudflare DoH 查询，并提供手动 DNS 泄漏检测
* 🛡️ WebRTC 检测 — 自动检测服务状态，并提供手动 WebRTC 泄漏检测
* 🔐 TLS / HTTPS — 真实 HTTPS/TLS 连接、TLS 版本、HTTP 协议、状态及 RTT
* 📊 网络质量 — 真实 HTTPS RTT 与 Cloudflare POP
* ⚡ QUIC / HTTP3 — 不伪造检测结果，无法可靠验证时明确提示
* 💚 节点健康 — 真实 HTTP 连通性与响应延迟
* 🌍 第三方服务 — YouTube、TikTok、X、Instagram、Google、Netflix 真实访问检测

🔗 手动检测

DNS 泄漏：
[DNS Leak Test](https://www.dnsleaktest.com/)

WebRTC 泄漏：
[BrowserLeaks WebRTC Test](https://browserleaks.com/webrtc)

📄 配置

[Default.yaml Raw](https://raw.githubusercontent.com/lihx0481-create/-Stash-config/main/Default.yaml)

⚠️ 真实性说明

本配置尽量只显示实际请求获得的数据。

DNS 查询成功 ≠ DNS 无泄漏
WebRTC 服务可访问 ≠ WebRTC 无泄漏

因此 DNS 和 WebRTC Tile 均保留 「手动检测 →」，用于进行真正的泄漏检测。

无法可靠检测的项目不会伪造 ✓。

本项目用于 Stash 网络状态、连通性及泄漏检测辅助。

检测结果受当前网络、节点、DNS 和目标服务器影响，仅代表检测时的实际状态。
