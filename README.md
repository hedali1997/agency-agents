# 🎭 The Agency: AI 专家团队，随时改变您的工作流程

> **一个完整的 AI 代理机构，触手可及** - 从前端魔法师到 Reddit 社区忍者，从创意注入者到现实检验者。每个 agent 都是具有个性、流程和成熟交付成果的专业专家。

[![GitHub stars](https://img.shields.io/github/stars/msitarzewski/agency-agents?style=social)](https://github.com/msitarzewski/agency-agents)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)
[![Sponsor](https://img.shields.io/badge/Sponsor-%E2%9D%A4-pink?logo=github)](https://github.com/sponsors/msitarzewski)

---

## 🚀 这是什么？

诞生于 Reddit 讨论和数月的迭代，**The Agency** 是一个精心打造的 AI agent 个性集合。每个 agent 都具备：

- **🎯 专业化**：在各自领域拥有深厚专业知识（不是通用的提示词模板）
- **🧠 个性驱动**：独特的声音、沟通风格和方法论
- **📋 交付导向**：真实的代码、流程和可衡量的成果
- **✅ 生产就绪**：经过实战考验的工作流程和成功指标

**可以这样理解**：组建你的梦幻团队，只不过他们是永不睡觉、从不抱怨、始终交付的 AI 专家。

---

## ⚡ 快速开始

### 选项 1：与 Claude Code 一起使用（推荐）

```
# 复制 agents 到你的 Claude Code 目录
cp -r agency-agents/* ~/.claude/agents/

# 现在可以在 Claude Code 会话中激活任何 agent：
# "Hey Claude, activate Frontend Developer mode and help me build a React component"
```

### 选项 2：作为参考使用

每个 agent 文件包含：
- 身份和个性特征
- 核心使命和工作流程
- 带有代码示例的技术交付物
- 成功指标和沟通风格

浏览下面的 agents，复制并改编你需要的！

### 选项 3：与其他工具一起使用（Cursor、Aider、Windsurf、Gemini CLI、OpenCode）

```
# 步骤 1 -- 为所有支持的工具生成交互文件
./scripts/convert.sh

# 步骤 2 -- 交互式安装（自动检测已安装的工具）
./scripts/install.sh

# 或直接针对特定工具
./scripts/install.sh --tool cursor
./scripts/install.sh --tool copilot
./scripts/install.sh --tool aider
./scripts/install.sh --tool windsurf
```

查看下方的 [🔌 多工具集成](#-多工具集成) 部分了解详情。

---

## 🎨 The Agency 团队名单

### 💻 工程部门

构建未来，一次提交一个。

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 🎨 [前端开发者](engineering/engineering-frontend-developer.md) | React/Vue/Angular, UI 实现，性能优化 | 现代 Web 应用、像素级完美 UI、Core Web Vitals 优化 |
| 🏗️ [后端架构师](engineering/engineering-backend-architect.md) | API 设计、数据库架构、可扩展性 | 服务端系统、微服务、云基础设施 |
| 📱 [移动应用开发者](engineering/engineering-mobile-app-builder.md) | iOS/Android, React Native, Flutter | 原生和跨平台移动应用 |
| 🤖 [AI 工程师](engineering/engineering-ai-engineer.md) | ML 模型、部署、AI 集成 | 机器学习功能、数据管道、AI 驱动的应用 |
| 🚀 [DevOps 自动化专家](engineering/engineering-devops-automator.md) | CI/CD、基础设施自动化、云运维 | 管道开发、部署自动化、监控 |
| ⚡ [快速原型开发者](engineering/engineering-rapid-prototyper.md) | 快速 POC 开发、MVP | 快速概念验证、黑客马拉松项目、快速迭代 |
| 💎 [高级开发者](engineering/engineering-senior-developer.md) | Laravel/Livewire、高级模式 | 复杂实现、架构决策 |
| 🔒 [安全工程师](engineering/engineering-security-engineer.md) | 威胁建模、安全代码审查、安全架构 | 应用安全、漏洞评估、安全 CI/CD |
| ⚡ [自主优化架构师](engineering/engineering-autonomous-optimization-architect.md) | LLM 路由、成本优化、影子测试 | 需要智能 API 选择和成本防护的自主系统 |
| 🔩 [嵌入式固件工程师](engineering/engineering-embedded-firmware-engineer.md) | 裸机、RTOS、ESP32/STM32/Nordic 固件 | 生产级嵌入式系统和 IoT 设备 |
| 🚨 [事件响应指挥官](engineering/engineering-incident-response-commander.md) | 事件管理、事后分析、on-call | 管理生产事件和构建事件响应能力 |
| ⛓️ [Solidity 智能合约工程师](engineering/engineering-solidity-smart-contract-engineer.md) | EVM 合约、gas 优化、DeFi | 安全、gas 优化的智能合约和 DeFi 协议 |
| 📚 [技术文档工程师](engineering/engineering-technical-writer.md) | 开发者文档、API 参考、教程 | 清晰准确的技术文档 |
| 🎯 [威胁检测工程师](engineering/engineering-threat-detection-engineer.md) | SIEM 规则、威胁狩猎、ATT&CK 映射 | 构建检测层和威胁狩猎 |
| 💬 [微信小程序开发者](engineering/engineering-wechat-mini-program-developer.md) | 微信生态、小程序、支付集成 | 为微信生态构建高性能应用 |
| 👁️ [代码审查员](engineering/engineering-code-reviewer.md) | 建设性代码审查、安全性、可维护性 | PR 审查、代码质量门禁、通过审查指导 |
| 🗄️ [数据库优化师](engineering/engineering-database-optimizer.md) | 模式设计、查询优化、索引策略 | PostgreSQL/MySQL 调优、慢查询调试、迁移规划 |
| 🌿 [Git 工作流大师](engineering/engineering-git-workflow-master.md) | 分支策略、约定式提交、高级 Git | Git 工作流设计、历史清理、CI 友好的分支管理 |
| 🏛️ [软件架构师](engineering/engineering-software-architect.md) | 系统设计、DDD、架构模式、权衡分析 | 架构决策、领域建模、系统演进策略 |
| 🛡️ [SRE](engineering/engineering-sre.md) | SLO、错误预算、可观测性、混沌工程 | 生产可靠性、减少琐事、容量规划 |
| 🧬 [AI 数据修复工程师](engineering/engineering-ai-data-remediation-engineer.md) | 自愈管道、气隙 SLM、语义聚类 | 零数据损失大规模修复损坏数据 |
| 🔧 [数据工程师](engineering/engineering-data-engineer.md) | 数据管道、湖仓架构、ETL/ELT | 构建可靠的数据基础设施和数据仓库 |
| 🔗 [飞书集成开发者](engineering/engineering-feishu-integration-developer.md) | 飞书/Lark 开放平台、机器人、工作流 | 为飞书生态构建集成 |

### 🎨 设计部门

让产品更美观、更易用、更愉悦。

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 🎯 [UI 设计师](design/design-ui-designer.md) | 视觉设计、组件库、设计系统 | 界面创建、品牌一致性、组件设计 |
| 🔍 [UX 研究员](design/design-ux-researcher.md) | 用户测试、行为分析、研究 | 理解用户、可用性测试、设计洞察 |
| 🏛️ [UX 架构师](design/design-ux-architect.md) | 技术架构、CSS 系统、实现 | 开发者友好的基础、实现指导 |
| 🎭 [品牌守护者](design/design-brand-guardian.md) | 品牌识别、一致性、定位 | 品牌策略、识别开发、指南 |
| 📖 [视觉叙事者](design/design-visual-storyteller.md) | 视觉叙事、多媒体内容 | 引人入胜的视觉故事、品牌故事讲述 |
| ✨ [创意注入者](design/design-whimsy-injector.md) | 个性、愉悦感、趣味互动 | 增添乐趣、微交互、彩蛋、品牌个性 |
| 📷 [图像提示词工程师](design/design-image-prompt-engineer.md) | AI 图像生成提示词、摄影 | Midjourney、DALL-E、Stable Diffusion 摄影提示词 |
| 🌈 [包容性视觉专家](design/design-inclusive-visuals-specialist.md) | 代表性、偏见缓解、真实意象 | 生成文化准确的 AI 图像和视频 |

### 💰 付费媒体部门

将广告支出转化为可衡量的业务成果。

| Agent | 专业领域 | 使用场景 |
| --- | --- | --- |
| 💰 [PPC 活动策略师](paid-media/paid-media-ppc-strategist.md) | Google/Microsoft/Amazon Ads、账户架构、出价 | 账户构建、预算分配、扩展、性能诊断 |
| 🔍 [搜索查询分析师](paid-media/paid-media-search-query-analyst.md) | 搜索词分析、否定关键词、意图映射 | 查询审计、消除浪费支出、关键词发现 |
| 📋 [付费媒体审计师](paid-media/paid-media-auditor.md) | 200+ 点账户审计、竞争分析 | 账户接管、季度审查、竞争提案 |
| 📡 [跟踪与测量专家](paid-media/paid-media-tracking-specialist.md) | GTM、GA4、转化跟踪、CAPI | 新实施、跟踪审计、平台迁移 |
| ✍️ [广告创意策略师](paid-media/paid-media-creative-strategist.md) | RSA 文案、Meta 创意、Performance Max 素材 | 创意发布、测试计划、广告疲劳刷新 |
| 📺 [程序化与展示购买专家](paid-media/paid-media-programmatic-buyer.md) | GDN、DSP、合作伙伴媒体、ABM 展示 | 展示计划、合作伙伴外展、ABM 计划 |
| 📱 [付费社交策略师](paid-media/paid-media-paid-social-strategist.md) | Meta、LinkedIn、TikTok、跨平台社交 | 社交广告计划、平台选择、受众策略 |

### 💼 销售部门

通过技巧而非 CRM 繁琐工作将管道转化为收入。

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 🎯 [外展策略师](sales/sales-outbound-strategist.md) | 基于信号的潜在开发、多渠道序列、ICP 定位 | 通过研究驱动的外展建立管道，而非数量 |
| 🔍 [发现教练](sales/sales-discovery-coach.md) | SPIN、Gap Selling、Sandler —— 问题设计和通话结构 | 准备发现电话、筛选机会、指导销售代表 |
| ♟️ [交易策略师](sales/sales-deal-strategist.md) | MEDDPICC 筛选、竞争定位、赢单计划 | 评分交易、暴露管道风险、建立赢单策略 |
| 🛠️ [销售工程师](sales/sales-engineer.md) | 技术演示、POC 范围界定、竞争战斗卡 | 售前技术赢单、演示准备、竞争定位 |
| 🏹 [提案策略师](sales/sales-proposal-strategist.md) | RFP 响应、赢单主题、叙事结构 | 撰写有说服力的提案，而不仅仅是合规 |
| 📊 [管道分析师](sales/sales-pipeline-analyst.md) | 预测、管道健康度、交易速度、营收运营 | 管道审查、预测准确性、营收运营 |
| 🗺️ [客户策略师](sales/sales-account-strategist.md) | 切入与扩展、QBR、利益相关者映射 | 售后扩展、客户计划、NRR 增长 |
| 🏋️ [销售教练](sales/sales-coach.md) | 代表发展、电话指导、管道审查引导 | 通过结构化指导让每个代表和每笔交易更好 |

### 📢 营销部门

一次一个真实的互动来发展你的受众。

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 🚀 [增长黑客](marketing/marketing-growth-hacker.md) | 快速用户获取、病毒循环、实验 | 爆发式增长、用户获取、转化优化 |
| 📝 [内容创作者](marketing/marketing-content-creator.md) | 多平台内容、编辑日历 | 内容策略、文案撰写、品牌故事讲述 |
| 🐦 [Twitter 互动专家](marketing/marketing-twitter-engager.md) | 实时互动、思想领导力 | Twitter 策略、LinkedIn 活动、专业社交 |
| 📱 [TikTok 策略师](marketing/marketing-tiktok-strategist.md) | 病毒内容、算法优化 | TikTok 增长、病毒内容、Z 世代/千禧一代受众 |
| 📸 [Instagram 策划师](marketing/marketing-instagram-curator.md) | 视觉故事讲述、社区建设 | Instagram 策略、美学发展、视觉内容 |
| 🤝 [Reddit 社区建设者](marketing/marketing-reddit-community-builder.md) | 真实互动、价值驱动内容 | Reddit 策略、社区信任、真实营销 |
| 📱 [应用商店优化师](marketing/marketing-app-store-optimizer.md) | ASO、转化优化、可发现性 | 应用营销、商店优化、应用增长 |
| 🌐 [社交媒体策略师](marketing/marketing-social-media-strategist.md) | 跨平台策略、活动 | 整体社交策略、多平台活动 |
| 📕 [小红书专家](marketing/marketing-xiaohongshu-specialist.md) | 生活方式内容、趋势驱动策略 | 小红书增长、美学叙事、Z 世代受众 |
| 💬 [微信公众号运营者](marketing/marketing-wechat-official-account.md) | 订阅者互动、内容营销 | 公众号策略、社区建设、转化优化 |
| 🧠 [知乎策略师](marketing/marketing-zhihu-strategist.md) | 思想领导力、知识驱动的互动 | 知乎权威建设、问答策略、潜在客户开发 |
| 🇨🇳 [百度 SEO 专家](marketing/marketing-baidu-seo-specialist.md) | 百度优化、中国 SEO、ICP 备案 | 在百度排名并触达中国搜索市场 |
| 🎬 [B 站内容策略师](marketing/marketing-bilibili-content-strategist.md) | B 站算法、弹幕文化、UP 主成长 | 通过社区优先内容在 B 站建立受众 |
| 🠠 [轮播增长引擎](marketing/marketing-carousel-growth-engine.md) | TikTok/Instagram 轮播、自主发布 | 生成并发布病毒式轮播内容 |
| 💼 [LinkedIn 内容创作者](marketing/marketing-linkedin-content-creator.md) | 个人品牌、思想领导力、专业内容 | LinkedIn 增长、专业受众建设、B2B 内容 |
| 🛒 [中国电商运营官](marketing/marketing-china-ecommerce-operator.md) | 淘宝、天猫、拼多多、直播电商 | 在中国运营多平台电商 |
| 🎥 [快手策略师](marketing/marketing-kuaishou-strategist.md) | 快手、老铁社区、草根增长 | 在下沉市场建立真实受众 |
| 🔍 [SEO 专家](marketing/marketing-seo-specialist.md) | 技术 SEO、内容策略、外链建设 | 推动可持续的有机搜索增长 |
| 📘 [书籍合著者](marketing/marketing-book-co-author.md) | 思想领导力书籍、代笔、出版 | 为创始人和专家进行战略书籍合作 |
| 🌏 [跨境电商专家](marketing/marketing-cross-border-ecommerce.md) | Amazon、Shopee、Lazada、跨境履约 | 全渠道跨境电商策略 |
| 🎵 [抖音策略师](marketing/marketing-douyin-strategist.md) | 抖音平台、短视频营销、算法 | 在中国领先的短视频平台上发展受众 |
| 🎙️ [直播电商教练](marketing/marketing-livestream-commerce-coach.md) | 主播培训、直播间优化、转化 | 构建高绩效的直播电商运营 |
| 🎧 [播客策略师](marketing/marketing-podcast-strategist.md) | 播客内容策略、平台优化 | 中国播客市场策略和运营 |
| 🔒 [私域运营官](marketing/marketing-private-domain-operator.md) | 企业微信、私域流量、社区运营 | 构建企业微信私域生态 |
| 🎬 [短视频剪辑教练](marketing/marketing-short-video-editing-coach.md) | 后期制作、剪辑工作流、平台规范 | 实战短视频剪辑培训和优化 |
| 🔥 [微博策略师](marketing/marketing-weibo-strategist.md) | 新浪微博、热门话题、粉丝互动 | 全方位微博运营和增长 |
| 🔮 [AI 引用策略师](marketing/marketing-ai-citation-strategist.md) | AEO/GEO、AI 推荐可见性、引用审计 | 提升品牌在 ChatGPT、Claude、Gemini、Perplexity 的可见性 |

### 📊 产品部门

在正确的时间构建正确的东西。

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 🎯 [冲刺优先级排序师](product/product-sprint-prioritizer.md) | 敏捷规划、功能优先级 | 冲刺规划、资源分配、待办事项管理 |
| 🔍 [趋势研究员](product/product-trend-researcher.md) | 市场情报、竞争分析 | 市场研究、机会评估、趋势识别 |
| 💬 [反馈综合师](product/product-feedback-synthesizer.md) | 用户反馈分析、洞察提取 | 反馈分析、用户洞察、产品优先级 |
| 🧠 [行为助推引擎](product/product-behavioral-nudge-engine.md) | 行为心理学、助推设计、参与度 | 通过行为科学最大化用户动机 |
| 🧭 [产品经理](product/product-manager.md) | 全生命周期产品所有权 | 发现、PRD、路线图规划、GTM、成果衡量 |

### 🎬 项目管理部门

让列车准时运行（并在预算内）。

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 🎬 [工作室制片人](project-management/project-management-studio-producer.md) | 高层协调、组合管理 | 多项目监督、战略对齐、资源分配 |
| 🐑 [项目牧羊人](project-management/project-management-project-shepherd.md) | 跨职能协调、时间线管理 | 端到端项目协调、利益相关者管理 |
| ⚙️ [工作室运营官](project-management/project-management-studio-operations.md) | 日常效率、流程优化 | 卓越运营、团队支持、生产力 |
| 🧪 [实验跟踪员](project-management/project-management-experiment-tracker.md) | A/B 测试、假设验证 | 实验管理、数据驱动决策、测试 |
| 👔 [高级项目经理](project-management/project-manager-senior.md) | 现实的范围界定、任务转换 | 将规范转换为任务、范围管理 |
| 📋 [Jira 工作流管理员](project-management/project-management-jira-workflow-steward.md) | Git 工作流、分支策略、可追溯性 | 执行 Jira 关联的 Git 纪律和交付 |

### 🧪 测试部门

破坏东西，这样用户就不必了。

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 📸 [证据收集员](testing/testing-evidence-collector.md) | 基于截图的 QA、视觉证明 | UI 测试、视觉验证、bug 文档 |
| 🔍 [现实检验员](testing/testing-reality-checker.md) | 基于证据的认证、质量门禁 | 生产就绪、质量批准、发布认证 |
| 📊 [测试结果分析师](testing/testing-test-results-analyzer.md) | 测试评估、指标分析 | 测试输出分析、质量洞察、覆盖率报告 |
| ⚡ [性能基准测试员](testing/testing-performance-benchmarker.md) | 性能测试、优化 | 速度测试、负载测试、性能调优 |
| 🔌 [API 测试员](testing/testing-api-tester.md) | API 验证、集成测试 | API 测试、端点验证、集成 QA |
| 🛠️ [工具评估员](testing/testing-tool-evaluator.md) | 技术评估、工具选择 | 评估工具、软件推荐、技术决策 |
| 🔄 [工作流优化师](testing/testing-workflow-optimizer.md) | 流程分析、工作流改进 | 流程优化、效率提升、自动化机会 |
| ♿ [无障碍审计员](testing/testing-accessibility-auditor.md) | WCAG 审计、辅助技术测试 | 无障碍合规、屏幕阅读器测试、包容性设计验证 |

### 🛟 支持部门

运营的支柱。

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 💬 [支持响应员](support/support-support-responder.md) | 客户服务、问题解决 | 客户支持、用户体验、支持运营 |
| 📊 [分析报告师](support/support-analytics-reporter.md) | 数据分析、仪表板、洞察 | 商业智能、KPI 跟踪、数据可视化 |
| 💰 [财务跟踪员](support/support-finance-tracker.md) | 财务规划、预算管理 | 财务分析、现金流、业务绩效 |
| 🏗️ [基础设施维护员](support/support-infrastructure-maintainer.md) | 系统可靠性、性能优化 | 基础设施管理、系统运营、监控 |
| ⚖️ [法律合规检查员](support/support-legal-compliance-checker.md) | 合规、法规、法律审查 | 法律合规、监管要求、风险管理 |
| 📑 [高管摘要生成器](support/support-executive-summary-generator.md) | C 层级沟通、战略摘要 | 高管报告、战略沟通、决策支持 |

### 🥽 空间计算部门

构建沉浸式未来。

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 🏗️ [XR 界面架构师](spatial-computing/xr-interface-architect.md) | 空间交互设计、沉浸式 UX | AR/VR/XR 界面设计、空间计算 UX |
| 💻 [macOS 空间/Metal 工程师](spatial-computing/macos-spatial-metal-engineer.md) | Swift、Metal、高性能 3D | macOS 空间计算、Vision Pro 原生应用 |
| 🌐 [XR 沉浸式开发者](spatial-computing/xr-immersive-developer.md) | WebXR、基于浏览器的 AR/VR | 基于浏览器的沉浸式体验、WebXR 应用 |
| 🎮 [XR 驾驶舱交互专家](spatial-computing/xr-cockpit-interaction-specialist.md) | 基于驾驶舱的控制、沉浸式系统 | 驾驶舱控制系统、沉浸式控制界面 |
| 🍎 [visionOS 空间工程师](spatial-computing/visionos-spatial-engineer.md) | Apple Vision Pro 开发 | Vision Pro 应用、空间计算体验 |
| 🔌 [终端集成专家](spatial-computing/terminal-integration-specialist.md) | 终端集成、命令行工具 | CLI 工具、终端工作流、开发者工具 |

### 🎯 专业部门

不适合归类的独特专家。

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 🎭 [Agents 编排师](specialized/agents-orchestrator.md) | 多 agent 协调、工作流管理 | 需要多个 agent 协调的复杂项目 |
| 🔍 [LSP/索引工程师](specialized/lsp-index-engineer.md) | 语言服务器协议、代码智能 | 代码智能系统、LSP 实现、语义索引 |
| 📥 [销售数据提取 Agent](specialized/sales-data-extraction-agent.md) | Excel 监控、销售指标提取 | 销售数据摄取、MTD/YTD/年度指标 |
| 📈 [数据整合 Agent](specialized/data-consolidation-agent.md) | 销售数据聚合、仪表板报告 | 区域总结、代表绩效、管道快照 |
| 📬 [报告分发 Agent](specialized/report-distribution-agent.md) | 自动报告交付 | 基于区域的报告分发、定时发送 |
| 🔐 [Agentic 身份与信任架构师](specialized/agentic-identity-trust.md) | Agent 身份、认证、信任验证 | 多 agent 身份系统、agent 授权、审计追踪 |
| 🔗 [身份图谱操作员](specialized/identity-graph-operator.md) | 多 agent 系统的共享身份解析 | 实体去重、合并提案、跨 agent 身份一致性 |
| 💸 [应付账款 Agent](specialized/accounts-payable-agent.md) | 支付处理、供应商管理、审计 | 跨加密货币、法币、稳定币的自主支付执行 |
| 🛡️ [区块链安全审计师](specialized/blockchain-security-auditor.md) | 智能合约审计、漏洞利用分析 | 在部署前发现合约中的漏洞 |
| 📋 [合规审计师](specialized/compliance-auditor.md) | SOC 2、ISO 27001、HIPAA、PCI-DSS | 指导组织完成合规认证 |
| 🌍 [文化情报策略师](specialized/specialized-cultural-intelligence-strategist.md) | 全球 UX、代表性、文化包容性 | 确保软件在不同文化中产生共鸣 |
| 🗣️ [开发者布道师](specialized/specialized-developer-advocate.md) | 社区建设、DX、开发者内容 | 连接产品和开发者社区 |
| 🔬 [模型 QA 专家](specialized/specialized-model-qa.md) | ML 审计、特征分析、可解释性 | 机器学习模型的端到端 QA |
| 🗃️ [ZK 管家](specialized/zk-steward.md) | 知识管理、Zettelkasten、笔记 | 构建互联的、经过验证的知识库 |
| 🔌 [MCP 构建师](specialized/specialized-mcp-builder.md) | 模型上下文协议服务器、AI agent 工具 | 构建扩展 AI agent 能力的 MCP 服务器 |
| 📄 [文档生成器](specialized/specialized-document-generator.md) | 从代码生成 PDF、PPTX、DOCX、XLSX | 专业文档创建、报告、数据可视化 |
| ⚙️ [自动化治理架构师](specialized/automation-governance-architect.md) | 自动化治理、n8n、工作流审计 | 大规模评估和治理业务自动化 |
| 📚 [企业培训设计师](specialized/corporate-training-designer.md) | 企业培训、课程开发 | 设计培训系统和学习项目 |
| 🏛️ [政府数字售前顾问](specialized/government-digital-presales-consultant.md) | 中国 ToG 售前、数字化转型 | 政府数字化转型提案和投标 |
| ⚕️ [医疗营销合规官](specialized/healthcare-marketing-compliance.md) | 中国医疗广告合规 | 医疗营销监管合规 |
| 🎯 [招聘专家](specialized/recruitment-specialist.md) | 人才获取、招聘运营 | 招聘策略、寻源和招聘流程 |
| 🎓 [留学顾问](specialized/study-abroad-advisor.md) | 国际教育、申请规划 | 美、英、加、澳留学规划 |
| 🔗 [供应链策略师](specialized/supply-chain-strategist.md) | 供应链管理、采购策略 | 供应链优化和采购规划 |
| 🗺️ [工作流架构师](specialized/specialized-workflow-architect.md) | 工作流发现、映射和规范 | 在编写代码之前映射系统中的每条路径 |
| ☁️ [Salesforce 架构师](specialized/specialized-salesforce-architect.md) | 多云 Salesforce 设计、限制器、集成 | 企业 Salesforce 架构、org 策略、部署管道 |
| 🇫🇷 [法国咨询市场导航员](specialized/specialized-french-consulting-market.md) | ESN/SI 生态、薪资托管、费率定位 | 法国 IT 市场的自由职业咨询 |
| 🇰🇷 [韩国商业导航员](specialized/specialized-korean-business-navigator.md) | 韩国商业文化、禀议流程、关系机制 | 外国专业人士驾驭韩国商业关系 |

### 🎮 游戏开发部门

在每个主要引擎上构建世界、系统和体验。

#### 跨引擎 Agents（引擎无关）

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 🎯 [游戏设计师](game-development/game-designer.md) | 系统设计、GDD 撰写、经济平衡、玩法循环 | 设计游戏机制、进度系统、撰写设计文档 |
| 🗺️ [关卡设计师](game-development/level-designer.md) | 布局理论、节奏、遭遇设计、环境叙事 | 构建关卡、设计遭遇流程、空间叙事 |
| 🎨 [技术美术](game-development/technical-artist.md) | 着色器、VFX、LOD 流程、美术到引擎优化 | 桥接美术和工程、着色器创作、性能安全的资产管道 |
| 🔊 [游戏音频工程师](game-development/game-audio-engineer.md) | FMOD/Wwise、自适应音乐、空间音频、音频预算 | 交互式音频系统、动态音乐、音频性能 |
| 📖 [叙事设计师](game-development/narrative-designer.md) | 故事系统、分支对话、传说架构 | 编写分支叙事、实现对话系统、世界观设定 |

#### Unity

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 🏗️ [Unity 架构师](game-development/unity/unity-architect.md) | ScriptableObjects、数据驱动模块化、DOTS/ECS | 大型 Unity 项目、数据驱动系统设计、ECS 性能工作 |
| ✨ [Unity Shader Graph 艺术家](game-development/unity/unity-shader-graph-artist.md) | Shader Graph、HLSL、URP/HDRP、渲染器特性 | 自定义 Unity 材质、VFX 着色器、后处理通道 |
| 🌐 [Unity 多人游戏工程师](game-development/unity/unity-multiplayer-engineer.md) | Netcode for GameObjects、Unity Relay/Lobby、服务器权限、预测 | 在线 Unity 游戏、客户端预测、Unity Gaming Services 集成 |
| 🛠️ [Unity 编辑器工具开发者](game-development/unity/unity-editor-tool-developer.md) | EditorWindows、AssetPostprocessors、PropertyDrawers、构建验证 | 自定义 Unity 编辑器工具、管道自动化、内容验证 |

#### Unreal Engine

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| ⚙️ [Unreal 系统工程师](game-development/unreal-engine/unreal-systems-engineer.md) | C++/Blueprint 混合、GAS、Nanite 约束、内存管理 | 复杂 Unreal 游戏玩法系统、Gameplay Ability System、引擎级 C++ |
| 🎨 [Unreal 技术美术](game-development/unreal-engine/unreal-technical-artist.md) | Material Editor、Niagara、PCG、Substrate | Unreal 材质、Niagara VFX、程序化内容生成 |
| 🌐 [Unreal 多人游戏架构师](game-development/unreal-engine/unreal-multiplayer-architect.md) | Actor 复制、GameMode/GameState 层次结构、专用服务器 | Unreal 在线游戏、复制图、服务器权威 Unreal |
| 🗺️ [Unreal 世界构建师](game-development/unreal-engine/unreal-world-builder.md) | World Partition、地形、HLOD、LWC | 大型开放世界 Unreal 关卡、流式系统、大规模地形 |

#### Godot

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 📜 [Godot 游戏玩法脚本师](game-development/godot/godot-gameplay-scripter.md) | GDScript 2.0、信号、组合、静态类型 | Godot 游戏玩法系统、场景组合、性能敏感的 GDScript |
| 🌐 [Godot 多人游戏工程师](game-development/godot/godot-multiplayer-engineer.md) | MultiplayerAPI、ENet/WebRTC、RPC、权限模型 | 在线 Godot 游戏、场景复制、服务器权威 Godot |
| ✨ [Godot 着色器开发者](game-development/godot/godot-shader-developer.md) | Godot 着色语言、VisualShader、RenderingDevice | 自定义 Godot 材质、2D/3D 效果、后处理、计算着色器 |

#### Blender

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 🧩 [Blender 插件工程师](game-development/blender/blender-addon-engineer.md) | Blender Python (`bpy`)、自定义操作符/面板、资产验证器、导出器、管道自动化 | 构建 Blender 插件、资产准备工具、导出工作流和 DCC 管道自动化 |

#### Roblox Studio

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| ⚙️ [Roblox 系统脚本师](game-development/roblox-studio/roblox-systems-scripter.md) | Luau、RemoteEvents/Functions、DataStore、服务器权威模块架构 | 构建安全的 Roblox 游戏系统、客户端 - 服务器通信、数据持久化 |
| 🎯 [Roblox 体验设计师](game-development/roblox-studio/roblox-experience-designer.md) | 参与循环、变现、D1/D7 留存、入职流程 | 设计 Roblox 游戏循环、Game Passes、每日奖励、玩家留存 |
| 👗 [Roblox 虚拟形象创作者](game-development/roblox-studio/roblox-avatar-creator.md) | UGC 管道、配件绑定、Creator Marketplace 提交 | Roblox UGC 物品、HumanoidDescription 定制、体验内虚拟形象商店 |

### 📚 学术部门

为世界构建、故事讲述和叙事设计带来学术严谨性。

| Agent | 专业领域 | 使用场景 |
|-------|-----------|-------------|
| 🌍 [人类学家](academic/academic-anthropologist.md) | 文化系统、亲属关系、仪式、信仰系统 | 设计具有内在逻辑的文化连贯社会 |
| 🌐 [地理学家](academic/academic-geographer.md) | 自然/人文地理、气候、制图学 | 构建具有真实地形和定居点的地理连贯世界 |
| 📚 [历史学家](academic/academic-historian.md) | 历史分析、时期划分、物质文化 | 验证历史连贯性、用真实的时代细节丰富背景 |
| 📜 [叙事学家](academic/academic-narratologist.md) | 叙事理论、故事结构、角色弧线 | 用成熟的理论框架分析和改进故事结构 |
| 🧠 [心理学家](academic/academic-psychologist.md) | 人格理论、动机、认知模式 | 构建基于研究的心理可信角色 |

---

## 🎯 现实世界使用案例

### 场景 1：构建初创公司 MVP

**你的团队**：
1. 🎨 **前端开发者** - 构建 React 应用
2. 🏗️ **后端架构师** - 设计 API 和数据库
3. 🚀 **增长黑客** - 规划用户获取
4. ⚡ **快速原型开发者** - 快速迭代周期
5. 🔍 **现实检验员** - 确保发布前的质量

**结果**：在每个阶段都拥有专业化专业知识，更快发布。

---

### 场景 2：营销活动发布

**你的团队**：
1. 📝 **内容创作者** - 开发活动内容
2. 🐦 **Twitter 互动专家** - Twitter 策略和执行
3. 📸 **Instagram 策划师** - 视觉内容和故事
4. 🤝 **Reddit 社区建设者** - 真实的社区互动
5. 📊 **分析报告师** - 跟踪和优化性能

**结果**：多平台协调活动，具有平台特定的专业知识。

---

### 场景 3：企业功能开发

**你的团队**：
1. 👔 **高级项目经理** - 范围和任务规划
2. 💎 **高级开发者** - 复杂实现
3. 🎨 **UI 设计师** - 设计系统和组件
4. 🧪 **实验跟踪员** - A/B 测试规划
5. 📸 **证据收集员** - 质量验证
6. 🔍 **现实检验员** - 生产就绪

**结果**：具有质量门禁和文档的企业级交付。

---

### 场景 4：付费媒体账户接管

**你的团队**：

1. 📋 **付费媒体审计师** - 全面的账户评估
2. 📡 **跟踪与测量专家** - 验证转化跟踪准确性
3. 💰 **PPC 活动策略师** - 重新设计账户架构
4. 🔍 **搜索查询分析师** - 清除搜索词的浪费支出
5. ✍️ **广告创意策略师** - 刷新所有广告文案和扩展
6. 📊 **分析报告师**（支持部门） - 构建报告仪表板

**结果**：系统化的账户接管，在前 30 天内完成跟踪验证、消除浪费、结构优化和创意刷新。

---

### 场景 5：完整代理机构产品发现

**你的团队**：所有 8 个部门并行工作在一个单一任务上。

查看 **[Nexus 空间发现练习](examples/nexus-spatial-discovery.md)** —— 一个完整的示例，其中 8 个 agents（产品趋势研究员、后端架构师、品牌守护者、增长黑客、支持响应员、UX 研究员、项目牧羊人和 XR 界面架构师）同时部署以评估软件机会并产生统一的产品计划，涵盖市场验证、技术架构、品牌策略、上市策略、支持系统、UX 研究、项目执行和空间 UI 设计。

**结果**：在单次会话中生成全面的跨职能产品蓝图。[更多示例](examples/)。

---

## 🤝 贡献

我们欢迎贡献！以下是如何提供帮助：

### 添加新的 Agent

1. Fork 仓库
2. 在相应类别中创建新的 agent 文件
3. 遵循 agent 模板结构：
   - 包含名称、描述、颜色的 Frontmatter
   - 身份和记忆部分
   - 核心使命
   - 关键规则（特定领域的）
   - 带有示例的技术交付物
   - 工作流程
   - 成功指标
4. 提交你的 agent 的 PR

### 改进现有的 Agents

- 添加真实世界的示例
- 增强代码示例
- 更新成功指标
- 改进工作流程

### 分享你的成功故事

你是否成功使用过这些 agents？在 [Discussions](https://github.com/msitarzewski/agency-agents/discussions) 中分享你的故事！

---

## 📖 Agent 设计理念

每个 agent 的设计都包含：

1. **🎭 强烈的个性**：不是通用模板 —— 真实的角色和声音
2. **📋 清晰的交付物**：具体的产出，而不是模糊的指导
3. **✅ 成功指标**：可衡量的结果和质量标准
4. **🔄 成熟的工作流程**：行之有效的逐步流程
5. **💡 学习记忆**：模式识别和持续改进

---

## 🎁 这是什么特别之处？

### 与通用 AI 提示词不同：
- ❌ 通用的"扮演开发者"提示词
- ✅ 具有个性和流程的深度专业化

### 与提示词库不同：
- ❌ 一次性提示词集合
- ✅ 具有工作流和交付物的综合 agent 系统

### 与 AI 工具不同：
- ❌ 无法定制的黑盒工具
- ✅ 透明、可 fork、可适应的 agent 个性

---

## 🎨 Agent 个性亮点

> "我不仅仅是测试你的代码 —— 我默认会发现 3-5 个问题，并要求所有事情都有视觉证明。"
>
> -- **证据收集员**（测试部门）

> "你不是在 Reddit 上做营销 —— 你正在成为一个有价值的社区成员，碰巧代表一个品牌。"
>
> -- **Reddit 社区建设者**（营销部门）

> "每个有趣的元素都必须服务于功能或情感目的。设计增强而非分散注意力的愉悦感。"
>
> -- **创意注入者**（设计部门）

> "让我添加一个庆祝动画，将任务完成焦虑降低 40%"
>
> -- **创意注入者**（在 UX 审查期间）

---

## 📊 统计数据

- 🎭 **144 个专业 Agents**，分布在 12 个部门
- 📝 **10,000+ 行** 个性、流程和代码示例
- ⏱️ **数月的迭代**，来自真实世界的使用
- 🌟 **在生产环境中经过实战检验**
- 💬 **Reddit 上 12 小时内收到 50+ 请求**

---

## 🔌 多工具集成

The Agency 原生适用于 Claude Code，并提供转换和安装脚本，因此你可以在每个主要的 agent 编码工具中使用相同的 agents。

### 支持的工具

- **[Claude Code](https://claude.ai/code)** —— 原生 `.md` agents，无需转换 → `~/.claude/agents/`
- **[GitHub Copilot](https://github.com/copilot)** —— 原生 `.md` agents，无需转换 → `~/.github/agents/` + `~/.copilot/agents/`
- **[Antigravity](https://github.com/google-gemini/antigravity)** —— 每个 agent 一个 `SKILL.md` → `~/.gemini/antigravity/skills/`
- **[Gemini CLI](https://github.com/google-gemini/gemini-cli)** —— 扩展 + `SKILL.md` 文件 → `~/.gemini/extensions/agency-agents/`
- **[OpenCode](https://opencode.ai)** —— `.md` agent 文件 → `.opencode/agents/`
- **[Cursor](https://cursor.sh)** —— `.mdc` 规则文件 → `.cursor/rules/`
- **[Aider](https://aider.chat)** —— 单个 `CONVENTIONS.md` → `./CONVENTIONS.md`
- **[Windsurf](https://codeium.com/windsurf)** —— 单个 `.windsurfrules` → `./.windsurfrules`
- **[OpenClaw](https://github.com/openclaw/openclaw)** —— 每个 agent 一个 `SOUL.md` + `AGENTS.md` + `IDENTITY.md`
- **[Qwen Code](https://github.com/QwenLM/qwen-code)** —— `.md` SubAgent 文件 → `~/.qwen/agents/`

---

### ⚡ 快速安装

**步骤 1 -- 生成交互文件：**
```bash
./scripts/convert.sh
# 更快（并行，输出顺序可能不同）：./scripts/convert.sh --parallel
```

**步骤 2 -- 安装（交互式，自动检测你的工具）：**
```bash
./scripts/install.sh
# 更快（并行，输出顺序可能不同）：./scripts/install.sh --no-interactive --parallel
```

安装程序会扫描系统中已安装的工具，显示复选框 UI，让你精确选择要安装的内容：

```
  +------------------------------------------------+
  |   The Agency -- Tool Installer                 |
  +------------------------------------------------+

  System scan: [*] = detected on this machine

  [x]  1)  [*]  Claude Code     (claude.ai/code)
  [x]  2)  [*]  Copilot         (~/.github + ~/.copilot)
  [x]  3)  [*]  Antigravity     (~/.gemini/antigravity)
  [ ]  4)  [ ]  Gemini CLI      (gemini extension)
  [ ]  5)  [ ]  OpenCode        (opencode.ai)
  [ ]  6)  [ ]  OpenClaw        (~/.openclaw)
  [x]  7)  [*]  Cursor          (.cursor/rules)
  [ ]  8)  [ ]  Aider           (CONVENTIONS.md)
  [ ]  9)  [ ]  Windsurf        (.windsurfrules)
  [ ] 10)  [ ]  Qwen Code       (~/.qwen/agents/)

  [1-10] toggle   [a] all   [n] none   [d] detected
  [Enter] install   [q] quit
```

**或直接安装特定工具：**
```bash
./scripts/install.sh --tool cursor
./scripts/install.sh --tool opencode
./scripts/install.sh --tool openclaw
./scripts/install.sh --tool antigravity
```

**非交互式（CI/脚本）：**
```bash
./scripts/install.sh --no-interactive --tool all
```

**更快的运行（并行）** —— 在多核机器上，使用 `--parallel` 以便并行处理每个工具。跨工具的输出顺序是不确定的。适用于交互和非交互式安装：例如 `./scripts/install.sh --interactive --parallel`（选择工具，然后并行安装）或 `./scripts/install.sh --no-interactive --parallel`。作业数量默认为 `nproc`（Linux）、`sysctl -n hw.ncpu`（macOS）或 4；可通过 `--jobs N` 覆盖。

```bash
./scripts/convert.sh --parallel                    # 并行转换所有工具
./scripts/convert.sh --parallel --jobs 8           # 限制并行作业数
./scripts/install.sh --no-interactive --parallel   # 并行安装所有检测到的工具
./scripts/install.sh --interactive --parallel      # 选择工具，然后并行安装
./scripts/install.sh --no-interactive --parallel --jobs 4
```

---

### 特定工具说明

<details>
<summary><strong>Claude Code</strong></summary>

Agents 直接从仓库复制到 `~/.claude/agents/` —— 无需转换。

```bash
./scripts/install.sh --tool claude-code
```

然后在 Claude Code 中激活：
```
Use the Frontend Developer agent to review this component.
```

详见 [integrations/claude-code/README.md](integrations/claude-code/README.md)。
</details>

<details>
<summary><strong>GitHub Copilot</strong></summary>

Agents 直接从仓库复制到 `~/.github/agents/` 和 `~/.copilot/agents/` —— 无需转换。

```bash
./scripts/install.sh --tool copilot
```

然后在 GitHub Copilot 中激活：
```
Use the Frontend Developer agent to review this component.
```

详见 [integrations/github-copilot/README.md](integrations/github-copilot/README.md)。
</details>

<details>
<summary><strong>Antigravity (Gemini)</strong></summary>

每个 agent 成为 `~/.gemini/antigravity/skills/agency-<slug>/` 中的一个技能。

```bash
./scripts/install.sh --tool antigravity
```

在 Gemini with Antigravity 中激活：
```
@agency-frontend-developer review this React component
```

详见 [integrations/antigravity/README.md](integrations/antigravity/README.md)。
</details>

<details>
<summary><strong>Gemini CLI</strong></summary>

作为 Gemini CLI 扩展安装，每个 agent 一个技能加上清单文件。
在全新克隆时，运行安装程序之前先生成 Gemini 扩展文件。

```bash
./scripts/convert.sh --tool gemini-cli
./scripts/install.sh --tool gemini-cli
```

详见 [integrations/gemini-cli/README.md](integrations/gemini-cli/README.md)。
</details>

<details>
<summary><strong>OpenCode</strong></summary>

Agents 放置在项目根目录的 `.opencode/agents/` 中（项目范围）。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool opencode
```

或全局安装：
```bash
mkdir -p ~/.config/opencode/agents
cp integrations/opencode/agents/*.md ~/.config/opencode/agents/
```

在 OpenCode 中激活：
```
@backend-architect design this API.
```

详见 [integrations/opencode/README.md](integrations/opencode/README.md)。
</details>

<details>
<summary><strong>Cursor</strong></summary>

每个 agent 成为项目 `.cursor/rules/` 中的 `.mdc` 规则文件。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool cursor
```

当 Cursor 检测到项目中的规则时会自动应用。显式引用：
```
Use the @security-engineer rules to review this code.
```

详见 [integrations/cursor/README.md](integrations/cursor/README.md)。
</details>

<details>
<summary><strong>Aider</strong></summary>

所有 agents 被编译到单个 `CONVENTIONS.md` 文件中，Aider 会自动读取。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool aider
```

然后在 Aider 会话中引用 agents：
```
Use the Frontend Developer agent to refactor this component.
```

详见 [integrations/aider/README.md](integrations/aider/README.md)。
</details>

<details>
<summary><strong>Windsurf</strong></summary>

所有 agents 被编译到项目根目录的 `.windsurfrules` 中。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool windsurf
```

在 Windsurf 的 Cascade 中引用 agents：
```
Use the Reality Checker agent to verify this is production ready.
```

详见 [integrations/windsurf/README.md](integrations/windsurf/README.md)。
</details>

<details>
<summary><strong>OpenClaw</strong></summary>

每个 agent 成为 `~/.openclaw/agency-agents/` 中包含 `SOUL.md`、`AGENTS.md` 和 `IDENTITY.md` 的工作区。

```bash
./scripts/install.sh --tool openclaw
```

Agents 在 OpenClaw 会话中通过 `agentId` 注册和可用。

详见 [integrations/openclaw/README.md](integrations/openclaw/README.md)。

</details>

<details>
<summary><strong>Qwen Code</strong></summary>

SubAgents 安装到项目根目录的 `.qwen/agents/` 中（项目范围）。

```bash
# 转换并安装（从项目根目录运行）
cd /your/project
./scripts/convert.sh --tool qwen
./scripts/install.sh --tool qwen
```

**在 Qwen Code 中使用：**
- 按名称引用：`Use the frontend-developer agent to review this component`
- 或让 Qwen 根据任务上下文自动委派
- 在交互模式下通过 `/agents` 命令管理

> 📚 [Qwen SubAgents 文档](https://qwenlm.github.io/qwen-code-docs/en/users/features/sub-agents/)

</details>

---

### 更改后重新生成

当你添加新 agents 或编辑现有 agents 时，重新生成所有集成交互文件：

```bash
./scripts/convert.sh                    # 重新生成所有（串行）
./scripts/convert.sh --parallel         # 并行重新生成所有（更快）
./scripts/convert.sh --tool cursor      # 仅重新生成一个工具
```

---

## 🗺️ 路线图

- [ ] 交互式 agent 选择器 Web 工具
- [x] 多 agent 工作流示例 —— 见 [examples/](examples/)
- [x] 多工具集成脚本（Claude Code、GitHub Copilot、Antigravity、Gemini CLI、OpenCode、OpenClaw、Cursor、Aider、Windsurf、Qwen Code）
- [ ] Agent 设计视频教程
- [ ] 社区 agent 市场
- [ ] Agent"性格测试"用于项目匹配
- [ ] "本周 Agent"展示系列

---

## 🌐 社区翻译和本地化

社区维护的翻译和区域改编。这些都是独立维护的 —— 查看每个仓库以了解覆盖范围和版本兼容性。

| 语言 | 维护者 | 链接 | 备注 |
|----------|-----------|------|-------|
| 🇨🇳 简体中文 (zh-CN) | [@jnMetaCode](https://github.com/jnMetaCode) | [agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh) | 100 个翻译 agents + 9 个中国市场原创 |
| 🇨🇳 简体中文 (zh-CN) | [@dsclca12](https://github.com/dsclca12) | [agent-teams](https://github.com/dsclca12/agent-teams) | 独立翻译，包含 B 站、微信、小红书本地化 |

想要添加翻译？开个 issue 我们会在这里链接。

---

## 🔗 相关资源

- [awesome-openclaw-agents](https://github.com/mergisi/awesome-openclaw-agents) —— 社区维护的 OpenClaw agent 集合（源自此仓库）

---

## 📜 许可证

MIT 许可证 - 免费用于商业或个人用途。感谢注明出处，但不强制要求。

---

## 🙏 致谢

始于 Reddit 上关于 AI agent 专业化的讨论，现已发展成为非凡的成果 —— **12 个部门 147 个 agents**，得到来自世界各地贡献者社区的支持。此仓库中的每个 agent 都因为有人足够关心它、编写它、测试它并分享它而存在。

献给所有开启 PR、提交 issue、发起 Discussion，或只是尝试 agent 并告诉我们什么有效的人 —— 谢谢你们。你们是 The Agency 不断进步的原因。

---

## 💬 社区

- **GitHub Discussions**: [分享你的成功故事](https://github.com/msitarzewski/agency-agents/discussions)
- **Issues**: [报告 bug 或请求功能](https://github.com/msitarzewski/agency-agents/issues)
- **Reddit**: 加入 r/ClaudeAI 的讨论
- **Twitter/X**: 使用 #TheAgency 分享

---

## 🚀 开始使用

1. **浏览** 上方的 agents 并找到适合你的专家
2. **复制** agents 到 `~/.claude/agents/` 用于 Claude Code 集成
3. **激活** agents，在你的 Claude 对话中引用它们
4. **定制** agent 个性与工作流以适应你的特定需求
5. **分享** 你的成果并回馈社区

---

<div align="center">

**🎭 The Agency: 你的 AI 梦幻团队已就绪 🎭**

[⭐ Star 此仓库](https://github.com/msitarzewski/agency-agents) • [🍴 Fork 此仓库](https://github.com/msitarzewski/agency-agents/fork) • [🐛 报告 issue](https://github.com/msitarzewski/agency-agents/issues) • [❤️ 赞助](https://github.com/sponsors/msitarzewski)

由社区制作，为社区服务 ❤️

</div>
