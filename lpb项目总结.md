# 简历素材：lpb 及相关项目

> 生成日期：2026-08-06

---

## 工作内容

**落地页低代码平台（Landing Page Builder）** — 核心开发者

- 负责拖拽式落地页编辑器的全栈开发，覆盖编辑器（Vue 3 + Pinia + Element Plus）、运行时 SDK（TypeScript，IIFE 内联）、Mock 服务（NestJS + Redis）三大模块
- 设计并实现 6 层反作弊防御体系：客户端 Bot 检测、行为轨迹追踪、pageToken 一次性令牌、请求签名防重放、服务端滑动窗口限流、爬虫白名单 + iframe 检测
- 制定组件 JSON-Schema 协议，统一编辑器与 SDK 的数据交互标准
- 搭建 Monorepo（pnpm workspace）工程架构，含体积门禁 CLI 工具，管控 SDK 产物体积
- 新增 **AI 编排器**：Vue Flow 节点图编排（条件/触发/埋点/分支/互动节点）+ DAG 校验（环检测/孤立节点）+ client-runtime 运行时解释器（信号传播驱动页面交互）+ AI 自然语言生成节点图（独立入口），`EditorComponent` schema 零改动、无编排页面完全向后兼容

**广告协议引擎（Ad Protocol Engine）** — 独立开发

- 从零自研 IAB 广告协议引擎，覆盖 MRAID 3.0 / VAST 4.0 协议解析
- 采用三层架构：TypeScript 协议调度层 + Rust/WASM 高性能解析核心 + Map 驱动协议分发
- 产出多格式产物（CJS/ESM/IIFE/DTS），覆盖 Node/浏览器/内联全场景

**自动化自测工具（Ad Automation）** — 独立开发

- 开发红队自测工具，Playwright CDP 直连真机 Chrome（ADB forward），模拟真实用户操作
- 实现反检测注入（绕过 navigator.webdriver）、随机延时 + 坐标偏移模拟真人行为
- 以黑盒攻击方视角验证自建反作弊体系的防护强度

**AI 辅助开发体系** — 独立搭建

- 设计并落地三层 AI 资产生命周期体系：23 份编码规范 + 15 份踩坑记忆 + 17 个专项技能 + 3 个流程 Agent
- 开发 `sync-ai-assets.mjs` 一源多发脚本，编译期将标签矩阵展开为精确的文件匹配规则，同步到 VS Code / Qoder / Codex / DSH / Kiro / Cursor 等 6 个编辑器
- 建立 Spec 驱动开发工作流（Spec-Kit Lite），10 个活跃 spec，覆盖需求 → 设计 → 任务 → 归档全流程

---

## 拥有技能

| 类别 | 技能 |
|------|------|
| **前端** | Vue 3（Composition API + `<script setup>`）、TypeScript 严格模式、Pinia、Element Plus、SCSS、Vite、Vue Flow 节点图编排 |
| **后端** | NestJS、Express、Node.js、Redis、ClickHouse（架构设计） |
| **系统编程** | Rust（WASM 编译、CLI 工具、Fuzzer）、Go（了解） |
| **测试** | Vitest、Playwright（CDP 直连真机）、Rust cargo-fuzz |
| **工程化** | Monorepo（pnpm workspace）、tsup 构建、Docker（docker-compose 编排）、体积门禁、CI/CD |
| **广告协议** | IAB MRAID 3.0、VAST 4.0、OpenRTB 竞价逻辑 |
| **反作弊** | Bot 检测、指纹识别、令牌机制、签名防重放、限流策略 |
| **AI 工具链** | VS Code Copilot 体系搭建、MCP 协议（Chrome/蓝湖/GitKraken）、Spec-Kit Lite 工作流 |

---

## 工作业绩

- **落地页平台**：完成编辑器 + SDK + Mock-Server 全栈开发，支撑广告投放业务；6 层反作弊体系已上线，有效防御 Puppeteer/Playwright 脚本刷量
- **AI 编排器**：lpb 落地页交互编排层（节点图 + DAG 校验 + 运行时解释器 + AI 生成），`EditorComponent` schema 零改动、向后兼容，32 个编排单测
- **协议引擎**：独立完成 98 个单元测试 + 27 个合规测试；Rust/WASM 解析性能达 7.6µs/次；支持五端 Bridge 架构
- **自测工具**：Playwright CDP 真机测试框架，以攻击方视角验证防护体系，发现并修复多个反作弊盲区
- **AI 体系**：23 份编码规范 + 15 份踩坑记忆 + 17 个技能 + 3 个 Agent，通过编译期标签矩阵自动匹配项目，注入精准度提升 40%
- **Spec 驱动**：10 个活跃 spec，覆盖 AI 辅助布局、引擎核心抽象、BFF 中间件等关键模块
- **VS Code 插件**：Agnes AI - Copilot Chat Provider 已上线 Marketplace，将自定义模型接入 Copilot Chat
