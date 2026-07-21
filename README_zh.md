<p align="center">
  <img src="https://github.com/molvqingtai/WebChat/blob/master/public/logo.png" width="200px"/>
</p>

[English](./README.md) | 简体中文

# WebChat

[![持续集成](https://github.com/molvqingtai/WebChat/actions/workflows/ci.yml/badge.svg)](https://github.com/molvqingtai/WebChat/actions) [![GitHub 许可证](https://img.shields.io/github/license/molvqingtai/WebChat)](https://github.com/molvqingtai/WebChat/blob/master/LICENSE) [![Chrome 网上应用店版本](https://img.shields.io/chrome-web-store/v/cpaedhbidlpnbdfegakhiamfpndhjpgf)](https://chromewebstore.google.com/detail/webchat/cpaedhbidlpnbdfegakhiamfpndhjpgf) [![GitHub 发布](https://img.shields.io/github/v/release/molvqingtai/WebChat)](https://github.com/molvqingtai/WebChat/releases) [![询问 DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/molvqingtai/WebChat)

> 在任何网站上与任何人聊天

这是一个匿名聊天浏览器扩展，去中心化且无服务器，利用 WebRTC 进行端到端加密通信。它优先考虑隐私，所有数据都存储在本地。

其目的是为任何网站添加聊天室功能，让你再也不感到孤单。

### 安装

**从插件商店安装**

- [Chrome](https://chromewebstore.google.com/detail/webchat/cpaedhbidlpnbdfegakhiamfpndhjpgf)
- [Edge](https://microsoftedge.microsoft.com/addons/detail/mmfdplbomjjlgdffecapcpgjmhfhmiob)
- [Firefox](https://addons.mozilla.org/firefox/addon/webchat/)

**手动安装**

1. 前往 GitHub 仓库（[发布页面](https://github.com/molvqingtai/WebChat/releases)）
2. 点击“Assets”按钮，选择“web-chat-\*.zip”
3. 将 ZIP 文件解压到你电脑上的一个文件夹
4. 在浏览器中打开扩展管理页面（通常是 chrome://extensions/）
   - 启用“开发者模式”
   - 点击“加载已解压的扩展程序”，选择你刚解压的文件夹

### 使用方法

安装扩展后，你会在任何网站的右下角看到一个幽灵图标。点击它，你就能和同一网站上的其他人愉快地聊天了！

### 视频

https://github.com/user-attachments/assets/e7ac9b8e-1b6c-43fb-8469-7a0a2c09d450

### 社区

加入我们的 Discord 社区，讨论 WebChat 并与其他用户联系：

[Discord](https://discord.com/channels/1398133810398367805/1398137562043908248)

### 站在巨人的肩膀上

除了去中心化聊天的好主意之外，它还利用了一些了不起的技术。

- **[remesh](https://github.com/remesh-js/remesh)**：一个 JavaScript 框架，实现了 DDD 原则，真正分离了 UI 和逻辑，由于独立于 UI，因此可以轻松实现 UI 部分，例如用 Vue 重写。

- **[shadcn/ui](https://ui.shadcn.com/)**：一个漂亮的 UI 库，也是无安装概念的先驱，在自定义样式方面提供了无与伦比的便利。

- **[wxt](https://wxt.dev/)**：这是我用过构建浏览器扩展最好的框架，没有之一。

- ~~**[trystero](https://github.com/dmotz/trystero)**~~：实现去中心化通信的核心依赖，可连接到 IPFS、torrent、Nostr 等去中心化网络。
- **[Artico](https://github.com/matallui/artico)**：一套灵活的库，帮助你创建自己的基于 WebRTC 的解决方案。

- **[ugly-avatar](https://github.com/txstc55/ugly-avatar)**：用它来创建令人惊艳的随机头像。

### 赞助商

WebChat 是一个开源项目，其持续发展完全依靠这些出色支持者的支持才得以实现。

[![由 DartNode 提供支持](https://dartnode.com/branding/DN-Open-Source-sm.png)](https://dartnode.com "由 DartNode 提供支持 - 面向开源的免费 VPS")

### 许可证

本项目基于 MIT 许可证开源 - 详情请参阅 [LICENSE](./LICENSE) 文件。
