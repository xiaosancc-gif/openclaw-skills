# OpenClaw Skills & 项目安装包

> 生成时间：2026-03-23
> 来源机器：C:\Users\Administrator\.openclaw
> 用途：快速在另一台 OpenClaw 上重建相同环境

---

## 快速安装（一键）

在新的 OpenClaw 上运行以下命令安装全部 Skills：

```bash
# 方式1：clawhub 批量安装（推荐）
npx clawhub install-all

# 方式2：agent-reach GitHub 项目
npx agent-reach install <repo-url>

# 方式3：手动逐个安装 skills/ 目录
```

---

## 📦 Skills 清单（共 91 个）

### 核心系统（必装）

| 名称 | 描述 | 安装源 |
|------|------|--------|
| skill-watcher | 技能更新检查和自动同步 | clawhub |
| self-improving-agent | 自我改进，捕获错误和纠正 | clawhub |
| agent-reach | GitHub 项目批量安装执行器 | clawhub |
| find-skills | 技能发现和安装助手 | clawhub |
| myclaw-backup | MyClaw 备份恢复 | clawhub |
| memU | 记忆管理 | clawhub |

### 浏览器自动化

| 名称 | 描述 | 安装源 |
|------|------|--------|
| agent-browser | Playwright 浏览器自动化（Accessibility tree） | clawhub |
| actionbook | 网页自动化（JS 渲染页面/X/Twitter/1688） | clawhub |
| bb-browser | Chrome CDP 9222 连接控制 | clawhub |
| browserwing | 浏览器扩展 | clawhub |

### 飞书集成

| 名称 | 描述 | 安装源 |
|------|------|--------|
| feishu-doc | 飞书云文档读写 | @larksuite/openclaw-lark |
| feishu-bitable | 飞书多维表格 | @larksuite/openclaw-lark |
| feishu-calendar | 飞书日历管理 | @larksuite/openclaw-lark |
| feishu-task | 飞书任务管理 | @larksuite/openclaw-lark |
| feishu-wiki | 飞书知识库 | @larksuite/openclaw-lark |
| feishu-drive | 飞书云盘 | @larksuite/openclaw-lark |
| feishu-webhook | 飞书 Webhook | clawhub |

### 搜索 & 数据采集

| 名称 | 描述 | 安装源 |
|------|------|--------|
| tavily-search | AI 优化搜索（Tavily API） | clawhub |
| brave-web-search | Brave 网页搜索 | clawhub |
| baidu-search | 百度 AI 搜索 | clawhub |
| baidu-scholar-search-skill | 百度学术搜索 | clawhub |
| baidu-baike-data | 百度百科查询 | clawhub |
| searxng-search | SearXNG 元搜索 | clawhub |
| x-reader | X/Twitter 内容读取 | clawhub |
| x-bookmark-manager | X 书签管理器 | clawhub |
| x-research | X/Twitter 研究工具 | clawhub |
| opentwitter-mcp | Twitter MCP | clawhub |
| redbook | 小红书 CLI（搜索/分析/自动化） | clawhub |
| xiaohongshu-skills-v2 | 小红书技能 | clawhub |
| XiaohongshuSkills | 小红书技能（旧版） | clawhub |
| wechat_articles_spider | 微信文章爬虫 | clawhub |

### 营销 & 增长

| 名称 | 描述 | 安装源 |
|------|------|--------|
| ad-creative | 广告创意生成（Google/Meta/LinkedIn） | clawhub |
| copywriting | 营销文案（首页/落地页/产品页） | clawhub |
| content-strategy | 内容策略规划 | clawhub |
| seo-audit | SEO 审计 | clawhub |
| programmatic-seo | 程序化 SEO（模板批量生成） | clawhub |
| ai-seo | AI 搜索优化（AI Overviews/GEO） | clawhub |
| schema-markup | 结构化数据（JSON-LD） | clawhub |
| paid-ads | 付费广告（Google/Meta/LinkedIn） | clawhub |
| cold-email | B2B 冷邮件 | clawhub |
| email-sequence | 邮件序列/培育流程 | clawhub |
| launch-strategy | 产品发布策略（Product Hunt） | clawhub |
| marketing-ideas | 营销创意灵感 | clawhub |
| page-cro | 页面转化率优化 | clawhub |
| signup-flow-cro | 注册流程优化 | clawhub |
| popup-cro | 弹窗优化 | clawhub |
| form-cro | 表单优化（非注册类） | clawhub |
| onboarding-cro | 新用户引导优化 | clawhub |
| churn-prevention | 流失预防/挽留 | clawhub |
| pricing-strategy | 定价策略 | clawhub |
| paywall-upgrade-cro | 付费墙优化 | clawhub |
| lead-magnets | 线索磁铁（电子书/模板） | clawhub |
| free-tool-strategy | 免费工具策略 | clawhub |
| competitor-alternatives | 竞品对比页 | clawhub |
| sales-enablement | 销售赋能（PPT/单页/话术） | clawhub |
| revops | 收入运营/CRM | clawhub |
| referral-program | 推荐计划 | clawhub |
| analytics-tracking | 分析追踪（GA4/UTM） | clawhub |
| ab-test-setup | A/B 测试设计 | clawhub |
| social-content | 社交内容创作 | clawhub |
| copy-editing | 文案编辑润色 | clawhub |

### 设计 & 图片/视频

| 名称 | 描述 | 安装源 |
|------|------|--------|
| canvas-design | 海报/视觉设计（PNG/PDF） | clawhub |
| nano-banana-pro-prompts-recommend-skill | 智谱图片提示词（10,901+） | clawhub |
| seedance-prompt | 即梦 Seedance 2.0 视频提示词 | clawhub |
| yaoqiansu-digital-human | 摇钱树数字人 | clawhub |
| auto-cut-video-a-roll | 自动剪辑 | clawhub |
| naiba-keling-picture-3.0omni | 可灵图片 3.0 Omni | clawhub |
| lanshu-waytovideo | 蓝獬视频助手 | clawhub |

### AI & 效率工具

| 名称 | 描述 | 安装源 |
|------|------|--------|
| gog | Google Workspace CLI（Gmail/Calendar/Drive） | clawhub |
| himalaya | 邮件管理（IMAP/SMTP） | clawhub |
| opencli | OpenCLI 工具 | clawhub |
| openclaw-china | OpenClaw 中文优化 | clawhub |
| openclaw-master-skills | 339+ OpenClaw 技能集合 | clawhub |
| awesome-openclaw-usecases | OpenClaw 案例集合 | clawhub |
| modelbox | 模型管理 | clawhub |
| felo-skills | Felo AI 技能 | clawhub |
| capability-evolver | AI Agent 自进化引擎 | clawhub |
| proactive-agent-1-2-4 | 主动式 Agent 架构 | clawhub |
| session-resume | 会话恢复 | clawhub |
| claudesidian | Claude + Obsidian 集成 | clawhub |
| everything-claude-code | Claude Code 工具 | clawhub |

### 电商 & B2B

| 名称 | 描述 | 安装源 |
|------|------|--------|
| AiToEarn | AI 内容营销平台 | clawhub |
| agency-agents | AI Agent 代理框架 | clawhub |
| midscene-skills | 字节跳动 Midscene 自动化测试 | clawhub |
| antfarm | 开源 AI Agent 框架 | clawhub |
| Perplexica | AI 搜索引擎（Docker） | GitHub |
| redbook | 小红书 CLI | clawhub |
| raphael-publish | Raphael 发布工具 | clawhub |

### 学术 & 数据

| 名称 | 描述 | 安装源 |
|------|------|--------|
| Scrapling | 智能网页爬虫（pip） | pip install scrapling |
| OpenMAIC | 上海 AI 中心工具 | clawhub |
| opennews-mcp | 新闻 MCP | clawhub |

### 其他工具

| 名称 | 描述 | 安装源 |
|------|------|--------|
| twitter-cli | Twitter/X CLI | clawhub |
| SwiftUI-Agent-Skill | SwiftUI 开发技能 | clawhub |
| pinchtab | 浏览器标签页管理 | clawhub |
| OrbitOS | OrbitOS 工具 | clawhub |
| Ripple | Ripple AI | clawhub |
| mem9 | 云端记忆插件 | npm install @mem9/mem9 |
| skill-vetter | 安全审查 | clawhub |
| skilless | Skilless 元工具 | clawhub |
| skilless.ai-brainstorming | AI 头脑风暴 | clawhub |
| skilless.ai-research | AI 研究 | clawhub |
| skilless.ai-writing | AI 写作 | clawhub |

---

## 🛠️ 已安装 GitHub 项目

通过 agent-reach 批量安装（12 个）：

```bash
# Twitter CLI
npx agent-reach install postiz/twitter-cli

# Midscene 自动化测试
npx agent-reach install midscene/midscene-skills

# Agency Agents
npx agent-reach install agency-agents/agency-agents

# Nano Banana Pro 提示词（10901+）
npx agent-reach install nano-banana-pro-prompts-recommend-skill

# Scrapling 爬虫
pip install scrapling

# Redbook 小红书
npx agent-reach install redbook

# SwiftUI Agent
npx agent-reach install SwiftUI-Agent-Skill

# Pinchtab
npx agent-reach install pinchtab

# 可灵图片 3.0
npx agent-reach install naiba-keling-picture-3.0omni

# Perplexica AI 搜索
npx agent-reach install Perplexica/Vane

# AiToEarn
npx agent-reach install AiToEarn

# Agent Reach 本身
npm install -g agent-reach
```

---

## 🔌 必装插件

```bash
# 飞书插件
openclaw plugins install @larksuite/openclaw-lark

# Mem9 云记忆
openclaw plugins install @mem9/mem9

# 配置 API key（mem9）
# 在 openclaw.json 中写入：
# plugins.entries.mem9.config.apiKey = "601d46dd-0931-4b86-9545-7942a348ba99"
```

---

## 📋 安装优先级

### 第一梯队（日常必需）
- skill-watcher、self-improving-agent、find-skills、agent-reach
- feishu-doc、feishu-bitable、feishu-calendar
- tavily-search、x-reader、actionbook

### 第二梯队（营销/内容）
- seedance-prompt、nano-banana-pro-prompts
- copywriting、ad-creative、seo-audit
- redbook、xiaohongshu-skills-v2

### 第三梯队（进阶工具）
- agent-browser、bb-browser
- Perplexica（Docker）
- myclaw-backup、mem9

---

## 📝 本地 Skills 路径
`C:\Users\Administrator\.openclaw\workspace\skills\`

## 📝 本地记忆文件
`C:\Users\Administrator\.openclaw\workspace\memory\`

## 📝 记忆云（mem9）
API Key: `601d46dd-0931-4b86-9545-7942a348ba99`
