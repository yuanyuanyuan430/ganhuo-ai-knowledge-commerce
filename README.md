# ganhuo-ai-knowledge-commerce

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111111)
![Knowledge Commerce](https://img.shields.io/badge/Knowledge-Commerce-2563eb)
![WeChat](https://img.shields.io/badge/WeChat-Official%20Account-16a34a)
![Language](https://img.shields.io/badge/Language-中文-red)

把 AI 写作、公众号、飞书知识库和知识星球，做成一条可复制的知识付费流水线。

`ganhuo-ai-knowledge-commerce` 是一个面向内容创作者、知识博主、咨询顾问、训练营操盘手和小团队的 Codex Skill。它把知识付费里最容易乱掉的几件事拆成 SOP：选题、来源、知识库、风格、草稿、审核、公众号、知识星球、私域跟进和数据复盘。

输入一个细分品类和你已有的资料，它会输出一套可验收的流水线设计：产品定位、来源卡、知识库结构、公众号模板、知识星球周交付、自动化分工和 30/60/90 天执行表。

它的目标很直接：

- 提高选题命中率。
- 提高内容生产效率。
- 提高读者信任。
- 提高从免费内容到付费产品的转化概率。
- 降低来源混乱、夸大承诺、平台投诉和退款风险。

## 它解决什么问题

很多知识付费项目不是死在“不会写”，而是死在流程散：

```text
资料到处放，来源说不清；
AI 写得快，但文章没有个人经验；
公众号能发，但转化路径断；
星球开了，但不知道每天交付什么；
数据看了，但不知道下周改什么。
```

这个 Skill 把它们整理成一个 agent 能重复执行的流程。每次使用时，它会帮你输出一份 `Knowledge Commerce Pipeline Brief`，让一个细分品类从想法变成能跑的内容-信任-付费闭环。

## 它会帮你设计什么

| 模块 | 它会输出什么 | 价值 |
| --- | --- | --- |
| 产品定位 | 品类、目标用户、交付结果、价格梯度 | 让用户知道为什么要付费 |
| 来源系统 | 来源卡、授权状态、公开资料、实测记录 | 让内容更稳、更可信 |
| 知识库 | 主题簇、FAQ、案例、模板、反对意见 | 让 AI 有底子可检索 |
| 风格蒸馏 | 语气、节奏、例子、CTA、禁用表达 | 让内容更像一个人，而不是机器 |
| 内容工厂 | 选题、提纲、草稿、表格、审核清单 | 提高公众号输出效率 |
| 星球交付 | 周节奏、作业、答疑、精华、复盘 | 提高会员留存 |
| 自动化 | 飞书、n8n、RAG、公众号草稿 | 提高复用率 |
| 数据复盘 | 阅读、完读、加私域、付费、退款 | 知道下周该改哪里 |

## 默认转化路径

第一版先跑简单链路，不要一开始就做复杂矩阵：

```text
公众号文章 -> 朋友圈/企微跟进 -> 低价模板包或迷你课 -> 知识星球/训练营 -> 咨询或年度陪跑
```

| 位置 | 主要任务 | 输出 |
| --- | --- | --- |
| 公众号 | 建立信任，验证选题 | 高完读文章、CTA、来源链接 |
| 朋友圈/企微 | 承接互动，回答异议 | 私聊话术、用户问题、成交记录 |
| 低价产品 | 降低首次付费门槛 | 模板包、清单、迷你课 |
| 知识星球 | 持续交付和答疑 | 周主题、作业、精华、复盘 |
| 咨询/陪跑 | 高客单深度交付 | 诊断、方案、阶段验收 |

## 典型使用场景

更多可复制 prompt 在 [PROMPTS.md](PROMPTS.md)。

做一个 AI 工具知识星球：

```text
用 ganhuo-ai-knowledge-commerce 帮我设计一个 AI 工具/编程/效率工具方向的公众号 + 知识星球流水线。
要求包含来源卡、知识库结构、公众号模板、星球周交付和 30 天执行表。
```

把已有资料变成内容系统：

```text
我有一批公开文档、工具测试记录和自己的案例。
用 ganhuo-ai-knowledge-commerce 帮我整理成可复用知识库，并设计 10 篇公众号选题和星球交付节奏。
```

搭一个自动化 SOP：

```text
用 ganhuo-ai-knowledge-commerce 设计 n8n + 飞书多维表格 + Dify + 公众号草稿的自动化流程。
重点是字段、人工审核点、失败处理和复盘指标。
```

优化销售表达：

```text
用 ganhuo-ai-knowledge-commerce 帮我把“保证赚钱”这类表达改成更可信的增长表达，同时保留转化力。
```

## 它会输出什么

```markdown
## Knowledge Commerce Pipeline Brief

### Product Positioning
品类、用户、痛点、交付结果、价格梯度、信任资产。

### Source Map
公开资料、自有经验、授权资料、工具实测、用户案例分别怎么用。

### Knowledge Base Structure
主题簇、FAQ、模板、案例、术语、反对意见。

### Publishing Workflow
选题 -> 来源卡 -> 提纲 -> 草稿 -> 审核 -> 公众号草稿 -> 星球主题 -> 私域跟进。

### Content Template
标题、前 150 字、核心表格、个人经验、CTA。

### Knowledge Planet Rhythm
周一到周日每天交付什么，AI 帮什么，人做什么。

### Automation Map
飞书、n8n、Dify/RAG、公众号接口、知识星球人工动作怎么分工。

### 30/60/90-Day Rollout
从第一批种子用户，到创始会员，再到稳定周更和复盘。
```

## 迷你样例

```markdown
## Knowledge Commerce Pipeline Brief

### Product Positioning
| Field | Decision |
| --- | --- |
| Niche | AI 工具/编程/效率工具 |
| Target user | 想用 AI 提高工作效率，但不会筛工具和搭流程的普通职场人 |
| Paid deliverable | 每周 3 个可复制工作流 + 工具实测记录 + 答疑 |
| Entry product | 19-49 元 AI 工具清单或提示词包 |
| Core product | 68-199 元/年的知识星球 |

### Source Map
| Source type | Use | Risk control |
| --- | --- | --- |
| 官方文档 | 工具能力、价格、限制 | 记录发布日期和链接 |
| 自己实测 | 截图、失败案例、对比表 | 保留测试日期和环境 |
| 用户问题 | 选题和 FAQ | 去标识化，获得授权 |

### Weekly Rhythm
| Day | Member value | Human gate |
| --- | --- | --- |
| 周一 | 本周工具清单 | 确认工具可用性 |
| 周三 | 一个可复制工作流 | 加入真实截图 |
| 周五 | 成员问题答疑 | 审核敏感承诺 |
| 周日 | 数据复盘和下周预告 | 决定继续/停止的实验 |
```

## 推荐最小工具栈

第一版不用上复杂系统：

| 环节 | 推荐工具 |
| --- | --- |
| 总台账 | 飞书多维表格 |
| 正文与模板 | 飞书文档或 Markdown |
| 知识库/RAG | Dify 或 AnythingLLM |
| 自动化编排 | n8n |
| 公众号 | 自动建草稿，人工确认发布 |
| 知识星球 | AI 生成主题和答疑草稿，人工发布和运营 |

复杂以后再加 LangGraph、CrewAI、Postgres 或自定义脚本。

## 安装

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/yuanyuanyuan430/ganhuo-ai-knowledge-commerce.git ~/.codex/skills/ganhuo-ai-knowledge-commerce
```

重启 Codex 后即可使用：

```text
请用 ganhuo-ai-knowledge-commerce 帮我设计一个 AI 辅助知识付费流水线。
```

## 文件结构

```text
.
├── SKILL.md
├── README.md
├── llms.txt
├── llms-full.txt
├── manifest.json
├── agents/
│   └── openai.yaml
└── references/
    ├── checklist.md
    ├── platform-map.md
    ├── prompt-pack.md
    └── source-policy.md
```

## 核心理念

知识付费不是“把资料换个说法再卖”。真正能长期跑的，是把公开信息、自有经验、工具实测、用户问题和持续交付，组织成一套用户愿意跟着执行的系统。

AI 的价值是提高每一步的效率和质量：更快找题，更快成稿，更快复盘，更快发现用户真正愿意付费的问题。

把流程跑稳，比把话说满更值钱。
