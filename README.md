# 刘具辅 / Jules Liu

全栈工程师 · 独立完成从产品定义到部署上线的全流程
Full-stack engineer — I take products from definition to deployment on my own.

正在找新机会 — 如果你需要一个能独立交付完整产品的人，聊聊：[liujufu019@gmail.com](mailto:liujufu019@gmail.com)

---

## 正在维护

### [Quota Panel](https://github.com/Jules-0409/quota-panel)

macOS / Windows 桌面常驻小组件，实时监控 AI 订阅额度：Factory (Droid) 的 5h / 7d / 30d 令牌窗口、
Devin 的日 / 周配额、Cursor 的 Auto / API 池与 Grok Bot 周额度。

- **Tauri v2 + Rust**：三路数据源并发拉取，本地凭据内存中解密（AES-256-GCM），凭据库只读打开
- **不伪装客户端身份**：如实上报自己的 User-Agent，实测各接口在伪造与如实声明之间返回相同数据
- **原生透明毛玻璃窗口** + 菜单栏托盘 + 灵动岛式胶囊 / 卡片收起展开，空闲内存实测约 150 MB
- Apache-2.0 开源

`Rust` `Tauri v2` `tokio` `reqwest` `AES-256-GCM` `SQLite（只读）` `WKWebView / WebView2`

## 代表作品

**ShopGenie（商店精灵）** — 面向中小电商的 AI 内容运营系统（源码私有，可面谈演示）

不是又一个「帮你写文案」的工具：把生成、质检、A/B 实验、效果追踪、诊断迭代连成数据驱动的闭环，
覆盖小红书、抖音、Amazon、客服话术四类场景，每条内容必须通过确定性结构校验才能出稿。

`Python` `FastAPI` `Next.js` `React` `TypeScript` `SSE` `SQLite`

## 我怎么工作

- **先测量再说话**：写进 README 的数字来自实测（进程 RSS、接口对照实验），不搬营销话术
- **独立交付**：产品定义、接口调研、实现、测试、打包上线，一个人走完全链
- **与 AI agent 协作**：多 agent 并行开发是日常，产品取舍与代码评审由人负责

## 技术栈

| 层 | 常用 |
| :-- | :-- |
| 桌面 | Rust · Tauri v2 · WKWebView / WebView2 · 托盘与原生透明窗口 |
| 后端 | Python · FastAPI · SQLite · SSE 流式 · LLM 集成（OpenAI 兼容） |
| 前端 | Next.js · React · TypeScript · 纯 CSS（无 UI 框架） |
| 工程 | pytest / vitest · 多 agent 协作 · 人工代码评审 |

---

*Full-stack engineer, building complete products from concept to deployment. Open to new opportunities.*
