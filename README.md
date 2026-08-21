# 王伟 - 高级前端工程师/全栈架构师

---

> **联系方式**: 17600206327 | **邮箱**: 736354882@qq.com | **GitHub**: [github.com/ERVeepp](https://github.com/ERVeepp)
> **工作经验**: 10年 | **期望职位**: 高级前端工程师/技术专家/架构师
> **专业领域**: 程序化广告平台、前端架构设计、AI工具应用、性能优化

---

## 📂 文件说明

| 文件 | 用途 |
|------|------|
| `个人优势.md` | 六大核心优势总结（GitHub Copilot / DeepSeek V4 Pro 基于 docs 知识库生成） |
| `项目经历.md` | 9 个项目，按时间倒序，分项目描述 + 项目业绩 |
| `lpb项目总结.md` | 落地页平台 + 协议引擎 + 自测工具 + AI 体系详细展开 |
| `web_youngs项目总结.md` | 广告平台前端系统详细展开 |
| `resume-new.md` | 正式简历 |

## 个人优势

- **全栈纵深**：Vue 3 前端 + NestJS/Go 后端 + Rust/WASM 底层三层贯通，独立完成 40+ 业务页面、协议引擎、后端服务
- **广告技术全链路**：DSP/SSP/ADX 全链路 + 自研 IAB MRAID 3.0/VAST 4.0 协议引擎 + 归因反欺诈（AppsFlyer 四层防御 + 红蓝对抗系统）
- **AI Agent 全栈**：多 Agent 协作平台 + **文档/代码/多模态三 RAG**（Qdrant 向量检索 + tree-sitter 代码索引 + CLIP 图文检索）+ SSE 流式 + Function Calling，agent-core 核心库 + VS Code 插件（已上架）
- **多模态 AI 生成**：基于 Pixelle-Video 跑通 AI 全自动短视频端到端流水线（LLM 文案 + 文生图/视频 + TTS + 合成）
- **AI 工程化**：三层 AI 资产生命周期 + 编译期标签矩阵一源多发 6 编辑器 + Spec 驱动 + AI 评测体系（评测四层全落地：前三层前置门禁 + LLM-as-Judge 抽检）
- **开源贡献**：npm 开源组件 dragsection（获 9 个下游依赖）+ GitHub 开源项目（github.com/ERVeepp）
- **行业标准**：IAB 全套认证，MRAID 3.0 + VAST 4.2 + OpenRTB 2.6 + GDPR 合规

---

## 技术栈

| 类别 | 技能 |
|------|------|
| 前端框架 | Vue 3.5+、React 19、TypeScript 5.9、JavaScript ES6+ |
| 构建工具 | Vite 7.2、Webpack 5、Rollup、ESBuild |
| 包管理 | pnpm 10.25+、npm、yarn 4、mise工具链管理 |
| UI组件库 | Element-Plus、Ant-Design、自研组件库 |
| 状态管理 | Pinia、Vuex、Redux、Context API |
| CSS预处理 | Sass、Less、Stylus、PostCSS、TailwindCSS |
| 测试框架 | Vitest、Jest、@testing-library、Cypress |
| 后端开发 | Node.js 23、Nest.js、Egg.js、Express、Koa |
| 数据库 | MySQL、MongoDB、Redis、PostgreSQL |
| 系统编程 | Rust、WebAssembly、C++基础 |
| 移动广告 | MRAID 3.0、VAST 4.2、OpenRTB 2.6、GDPR合规 |
| 移动调试 | ADB、Chrome DevTools、移动端性能优化 |
| 系统运维 | Nginx、Docker、PM2、Linux服务器管理 |
| 云服务 | AWS SDK、华为云、阿里云、CDN配置 |
| AI框架 | LangChain、LangGraph、agent-core（自研）、Function Calling、SSE 流式 |
| 向量数据库 | Qdrant、Embedding（OpenAI/BGE/nomic） |
| AI工具链 | Kiro、ChatGPT、Copilot、Ollama、OpenClaw、通义灵码、MCP |
| 开发工具 | VSCode、WebStorm、Chrome DevTools MCP、Playwright、Electron |

---

## 工作经历

### 2024.01 - 至今 | Youngs广告管理平台 & AI工具链

**技术架构**: 微前端 + 组件化设计 + Rust WASM

- Youngs广告管理平台（SSP核心系统）：参考Facebook技术架构
- 技术栈：Vue 3.5 + Vite 7.2 + TypeScript 5.9 + Rust WASM
- 核心亮点：
  - Rust WASM数据处理性能提升1000%，支持千万级数据无卡顿
  - 构建速度比Webpack快10倍，开发效率提升60%
  - 首屏加载时间优化至1.2秒，用户体验显著改善
- 业务价值：提升广告位管理效率80%，支持日均千万级广告请求
- Youngs的H5模块的开发

**AI工具链搭建**
- 本地AI部署：Ollama + OpenClaw + Qwen/Gemini多模型配置
- 多模型切换（本地Ollama / MiniMax / Google Gemini）
- AI Agent浏览器自动化（OpenClaw Browser）
- Chrome DevTools MCP协议集成
- 团队贡献：编写完整部署文档，推动团队AI工具采用率达100%

### 2023.01 - 2024.01 | 整合ADX, DSP, SSP到统一平台Youngs

- SPA架构 + 状态管理 + WebSocket实时通信
- DSP需求方平台：广告投放管理、实时数据监控、创意批量管理
- 业务成果：投放ROI提升25%，创意上线效率提升3倍
- Youngs广告管理平台核心开发

### 2022.01 - 2023.01 | ADX广告交易平台

- MRAID 3.0 + VAST 4.2 + OpenRTB 2.6行业标准实现
- 完整实现expand、resize、close、playVideo等核心API
- Linear/NonLinear/Companion广告格式
- BidRequest/BidResponse实时竞价协议
- GDPR、CCPA用户同意管理(CMP)
- 获得IAB全套标准认证，广告收益提升30%

### 2021.05 - 2022.01 | DPA动态产品广告系统

- DPA系统开发
- DPA模板开发
- 浏览器自动化 & RPA系统：
  - 自研Chrome插件：一键登录第三方平台 + 自动2FA验证码填写
  - Web Crypto API原生实现TOTP（SHA1/Base32/30s），零依赖
  - Playwright无头浏览器批量执行任务，支持登录态管理和截图审计
  - bot_tasks任务调度系统：前端提交 → 后端入库 → 爬虫轮询执行 → 状态回写
- 架构设计：前端/后端/爬虫三方解耦，通过统一API交互
- 业务价值：将人工操作从5分钟/次降至全自动，日均处理200+任务

### 2021.01 - 2021.05 | BI数据分析平台

- BI平台开发
- 数据可视化与报表系统

### 2020.01 - 2021.01 | 游戏广告

- 游戏广告平台开发
- 广告投放管理系统

### 2019.01 - 2020.01 | hdt广告

- 广告平台开发
- SDK模板开发

### 2016.11 - 2019.01 | CloudMobi

- cloudmobi SSP管理后台开发
- jsTag SDK开发
- SDK模板开发：包含Mraid、Vast、VAPID、playable等广告形式和协议

---

## 技术成果

| 优化项目 | 优化前 | 优化后 | 提升幅度 |
|----------|--------|--------|----------|
| 首屏加载时间 | 8秒 | 2.5秒 | 69% |
| 数据处理性能 | 30秒 | 2秒 | 93% |
| 内存使用峰值 | 2GB | 200MB | 90% |
| 构建速度 | 10分钟 | 2分钟 | 80% |
| 测试覆盖率 | 60% | 90%+ | 50% |

- 年度节省服务器成本50万+
- 团队开发效率提升40%
- 广告平台收益提升30%
- bug率降低80%

---

## 核心优势

### 广告行业专业技能
- 程序化广告：深度理解SSP/DSP/RTB生态，熟悉广告交易流程
- 行业标准：IAB全套认证，MRAID 3.0 + VAST 4.2 + OpenRTB 2.6
- 隐私合规：GDPR、CCPA等隐私法规的技术实现和合规方案
- 实时竞价：Header Bidding、Server-to-Server集成经验

### 技术专长
- 前端架构：微前端设计、组件库建设、运行时配置热更新
- 全栈开发：Node.js后端、数据库设计、任务调度系统、服务器运维
- 系统编程：Rust WASM高性能计算、Web Crypto API、零拷贝优化
- 浏览器自动化：Chrome插件开发、Playwright RPA、TOTP 2FA自动化
- AI应用：多 Agent 平台（RAG 知识增强 + 向量检索）、LangChain/LangGraph、多模型热切换、MCP、本地大模型部署（Ollama）、AI 评测体系
- 性能优化：全局定时器架构、虚拟滚动、按需加载、内存优化

---

## 个人项目（详细见 `项目经历.md`）

| 项目 | 方向 | 亮点 |
|------|------|------|
| matrix-ai-agent | AI Agent 平台 | 多 Agent 协作 + RAG 知识增强（Qdrant）+ SSE 流式 + token 成本追踪 |
| landing-page-builder | 低代码平台 | 拖拽编辑器 + 运行时 SDK + 6 层反作弊体系 |
| ad-protocol-engine | 广告协议引擎 | 自研 MRAID 3.0/VAST 4.0，Rust/WASM 解析 7.6µs/次 |
| ad-automation | 反作弊红蓝对抗 | CDP 真机 + 蓝方双归因模拟 + 5 种攻击方案 |
| deepseek-harness-desktop | Electron 桌面 | Cordis 插件化 + 内置 Node 运行时 + 进程托管 |
| agnes-ai-for-copilot | VS Code 插件 | 自定义模型接入 Copilot Chat，已上架 Marketplace |
| dragsection | npm 开源组件 | Vue 3 拖拽区间选择，获 9 个下游依赖 |

---

## 教育背景 & 持续学习

- 谷歌开发者大会：线下参加全球顶级技术会议
- 年度完成《JavaScript设计模式》等3本技术书籍
- 持续关注Rust、AI、WebAssembly等前沿领域
- 定期进行内部技术分享和最佳实践推广

---

> "技术的价值在于解决问题，AI的价值在于放大人的能力。在AI时代，最重要的是培养与AI协作的思维方式，以及对技术发展趋势的敏锐洞察。"

---

**期望薪资**: 30k-40k | **工作地点**: 北京 | **到岗时间**: 随时