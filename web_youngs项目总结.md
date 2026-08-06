# 简历素材：web_youngs（广告平台前端系统）

> 生成日期：2026-08-06

---

## 项目概述

DSP/SSP 广告平台前端全栈系统，覆盖程序化广告投放、报表分析、媒体管理、受众定向、数据看板等核心业务，40+ 业务页面，支撑日均百万级广告请求。

技术栈：Vue 3 + TypeScript + Pinia + Element Plus + ECharts + Vite + NestJS + Rust/WASM + AWS S3

---

## 工作内容

**广告业务模块开发**

- 负责 DSP（需求方平台）全链路开发：广告投放管理、活动配置、报表分析、媒体管理、受众定向、ADX 对接
- 负责 SSP（供给方平台）模块：媒体管理、广告网络配置、收益报表、对账系统
- 负责平台管理模块：多租户权限、用户管理、数据看板、操作控制台

**Rust/WASM 高性能数据处理**

- 集成 Rust 编译为 WASM，实现 CSV/Excel 百万级数据前端解析
- 性能对比：纯 JS 方案 30s+ → WASM 方案 < 2s

**AI 能力集成**

- 搭建 AI Agent 后端服务（NestJS + OpenAI 兼容 API），为平台提供智能数据分析
- 配置 Chrome DevTools MCP，实现 AI 驱动的浏览器自动化调试与页面验证

**Chrome 扩展开发**

- 开发 AppsFlyer 一键登录扩展（Manifest V3），自动填写 2FA 验证码
- 简化多账号操作流程，提升运营效率

**工程化建设**

- 配置多环境构建（serve-dev/serve-test/build-test/build）
- 集成 Husky + lint-staged + commitlint 代码规范管控
- 配置 nginx 反向代理，支持多子应用独立部署
- Vitest 单元测试覆盖核心业务逻辑

---

## 拥有技能

| 类别 | 技能 |
|------|------|
| **前端框架** | Vue 3、TypeScript、Pinia、Element Plus、Vite |
| **数据可视化** | ECharts 6.x、复杂报表与看板 |
| **后端** | NestJS、OpenAI API、Node.js |
| **系统编程** | Rust → WASM（CSV/Excel 高性能解析） |
| **浏览器扩展** | Chrome Extension Manifest V3 |
| **云服务** | AWS S3（文件上传与预签名 URL） |
| **工程化** | 多环境构建、Docker（docker-compose 部署）、Husky、Nginx 反向代理、Vitest |
| **广告领域** | DSP 投放管理、SSP 媒体变现、报表分析、ADX 对接 |

---

## 工作业绩

- 独立负责 40+ 业务页面全栈开发，覆盖 DSP/SSP 全链路
- Rust/WASM 数据处理性能提升 15 倍（30s → 2s）
- Chrome 扩展简化 AppsFlyer 多账号管理，日均节省运营 30 分钟
- AI Agent 集成实现自然语言驱动的数据查询与分析
- 多环境 + nginx 方案支撑开发/测试/生产三套环境独立部署
