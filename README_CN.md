# Google 授权应用管理器

[English](README.md)

---

提取并备份 Google 授权应用，提供快捷链接设置备用登录方式。

## 功能

- 从 Google 权限页面提取已授权应用
- 收录 200+ 服务的登录、设置、安全页面链接
- 中英双语界面
- 导出备份为 JSON 或文本
- 支持手动添加遗漏的应用

## 为什么需要

如果 Google 账号丢了，那些只用"通过 Google 登录"的服务可能就登不进去了。

这个工具帮你：
1. 看到所有关联 Google 账号的服务
2. 直接跳转到各服务的安全设置
3. 给每个服务设置邮箱+密码登录

## 使用方法

1. 打开 [myaccount.google.com/connections](https://myaccount.google.com/connections)
2. 按 `Ctrl+A` 全选，`Ctrl+C` 复制
3. 粘贴到文本框，点"解析"
4. 点链接跳转到各服务的设置页

## 收录的服务（200+）

| 分类 | 示例 |
|------|------|
| 效率工具 | Notion, Trello, Slack, Asana, Monday, Miro |
| 设计工具 | Figma, Canva, Adobe, Sketch, Framer |
| 开发工具 | GitHub, GitLab, Vercel, Docker, AWS, Firebase |
| 社交通讯 | Discord, Twitter/X, LinkedIn, Reddit, Facebook |
| 娱乐游戏 | Spotify, Netflix, Steam, PlayStation, Nintendo |
| 购物服务 | Amazon, eBay, Airbnb, Uber, Booking |
| 云存储 | Dropbox, OneDrive, iCloud, MEGA |
| 学习平台 | Coursera, Udemy, Duolingo, Codecademy |
| 金融服务 | PayPal, Coinbase, Binance, Robinhood |
| AI 工具 | ChatGPT, Claude, Midjourney, Perplexity |

## 隐私

- 数据保存在浏览器本地
- 不会发送到任何服务器
- 开源项目

## 许可证

MIT

## 贡献

发现遗漏的服务？欢迎 PR 添加到 `database.js`。
