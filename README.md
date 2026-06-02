---
license: mit
tags:
  - competitor-research
  - competitive-analysis
  - growth-flywheel
  - market-research
  - startup-growth
  - social-media-analysis
  - twitter-analysis
  - content-strategy
  - product-launch
  - go-to-market
  - SaaS-growth
  - indie-hacker
  - growth-hacking
  - KOL-marketing
  - SEO
language:
  - en
  - zh
pretty_name: "Competitor Research & Growth Flywheel Playbook"
---

# Competitor Research & Growth Flywheel Playbook — Full SOP

> Complete SOP for systematic competitor research: website evolution analysis, social media channel teardown, growth flywheel scoring, X/Twitter propagation chain mapping, and KOL identification. Battle-tested across 150+ AI startups. Includes Lovable full case study (Nov 2024 launch: 229K impressions, 4.3M video views, 10K+ Discord community).


## 二、官网拆解方法论

### 2.1 拆解版本阶段

研究每个竞品需覆盖以下**三个关键版本节点**：

1. **第一版本的官网** — 产品刚上线时的最小可行版本
2. **第一阶段Beta Test的官网** — 封闭测试期，面向种子用户的版本
3. **第一阶段正式Launch的官网** — 公开上市时的完整版本

### 2.2 拆解框架

每个版本需记录以下维度：

| 维度 | 具体记录内容 |
|-|-|
| 一句话介绍 | 当版本的核心Value Proposition，首页Banner文案 |
| 官网长度 | 总共多少屏，落地页结构（几栏布局） |
| 用户案例 | 列出了哪些行业/场景的用例，数量变化 |
| 框架结构 | Banner/落地页结构/Pricing模块/CTA按钮的位置和文案 |
| SEO动作 | 何时开始布局SEO，首页标题/描述的变化 |
| 社区渠道 | 何时加入Discord/Reddit链接，各渠道启动节点 |
| 集成生态 | 展示了哪些第三方集成 |

### 2.3 操作步骤与记录模板

**步骤一：访问Wayback Machine**

- 打开 [web.archive.org](https://web.archive.org/)，输入竞品官网域名
- 在时间轴上找到三个关键节点（V1 / Beta / Launch）
- 截图并记录每个节点的内容

**步骤二：对比表格记录**

| 阶段 | 时间节点 | 一句话介绍 | 核心Value Prop | 官网长度 | 主要板块 | 启动的渠道 | 关键Feature |
|-|-|-|-|-|-|-|-|
| V1 | YYYY-MM | ... | ... | X屏 | ... | ... | ... |
| Beta | YYYY-MM | ... | ... | X屏 | ... | ... | ... |
| Launch | YYYY-MM | ... | ... | X屏 | ... | ... | ... |

**步骤三：提炼演进规律**

- Value Prop的措辞变化（从技术语言到商业语言的迁移路径）
- 产品定位的升级路径
- 功能展示的优先级调整


## 四、竞品传播飞轮分析法

### 4.1 核心增长飞轮结构

```
        创作(Activation)
           ↓
分享(Referral) ←→ 发现(Acquisition)
           ↑           ↓
      互动(Retention) ← 产品优化(Product Iteration)
           ↑
        变现(Revenue)
```

### 4.2 飞轮六阶段详细分析模板

| 飞轮阶段 | 核心问题 | 分析维度 | 必答子问题 |
|-|-|-|-|
| **一、创作** | 如何驱动用户完成"Aha Moment"？ | 入职门槛、AI能力深度、工作流整合 | 用户第一个有价值的产出需要多长时间？ |
| **二、分享** | 产品内是否有病毒式传播机制？ | Remix/分享功能、平台机制、分享激励 | 用户分享动机是"炫耀成果"还是"利他推荐"？ |
| **三、发现** | 潜在用户如何被吸引？ | UGC内容质量、SEO、推荐算法 | 新用户是被内容还是被广告拉来的？ |
| **四、互动** | 如何构建社区归属感？ | Discord/社区运营、活动机制、UGC放大 | 社区是否有自生长的UGC内容？ |
| **五、变现** | 免费到付费的转化路径？ | 定价模型、积分/Credit机制、升级触发点 | 用户在什么场景下最自然地付费？ |
| **六、产品优化** | 数据和反馈如何驱动迭代？ | 用户反馈闭环、迭代节奏 | 产品更新频率和用户反馈的关系？ |

### 4.3 增长飞轮强弱判断标准

| 指标 | 强飞轮表现 | 弱飞轮表现 |
|-|-|-|
| 用户留存 | Discord DAU高，UGC持续产出 | 缺乏社区运营，用户流失快 |
| 口碑传播 | 有明确的用户故事传播路径 | 无系统化的用户案例放大机制 |
| 付费转化 | 自然触发点清晰，价值阶梯合理 | 转化路径模糊 |
| 增长持续性 | 产品与社区形成闭环 | 增长依赖外部投放 |


## 六、X/Twitter传播深度分析方法

### 6.1 搜索语法模板

```
# 搜索竞品官方账号内容（排除转发）
from:[竞品官方Handle] since:YYYY-MM-DD until:YYYY-MM-DD -filter:retweets lang:en

# 搜索竞品相关讨论（排除官方和回复）
[竞品关键词] since:YYYY-MM-DD until:YYYY-MM-DD -filter:retweets -filter:replies

# 搜索非官方提及（用于发现UGC）
"[产品名]" OR "[产品域名]" -from:[官方Handle] since:YYYY-MM-DD until:YYYY-MM-DD -filter:retweets -filter:replies lang:en
```

### 6.2 数据统计维度

| 指标 | 计算方式 | 意义 |
|-|-|-|
| 总参与人数 | 去重独立用户数 | 传播广度 |
| 总曝光量 | 所有帖子曝光之和 | 传播总量 |
| 总互动量 | Likes + Reposts + Quotes + Comments | 传播深度 |
| 二次扩散新增 | 第二轮传播中新出现的用户数 | 破圈效率 |
| 传播层级漏斗 | 各级别人数/曝光量对比 | 传播效率分析 |

### 6.3 单帖爆款分析模板

#### A. 基础信息核查

| 核查项 | 记录内容 |
|-|-|
| 发布者账号 | Handle、身份（创始人/KOL/普通用户）、粉丝量级 |
| 发布时间 | 精确到小时，与官方发布日的时间差 |
| 帖子内容摘要 | 文案核心信息 + 视觉素材类型 |
| 六维数据 | Views / Likes / Reposts / Quotes / Comments / Bookmarks |

#### B. 内容核心拆解

| 拆解维度 | 具体分析 |
|-|-|
| **内容切入点（Hook）** | 从哪个角度讲故事？痛点/对比/数据/愿景？ |
| **传播点（Nugget）** | 什么信息让用户忍不住转发？ |
| **情绪触发点（Feeling）** | 惊叹/好奇/认同/愤怒/FOMO？ |
| **视觉素材作用** | 降低了什么理解成本？ |

#### C. 传播链路还原

| 分析维度 | 具体问题 |
|-|-|
| 上游来源 | 发布者的信息从哪来？ |
| 下游带动 | 哪些高粉账号参与？形成什么讨论？ |
| 引爆特征 | 是否存在机构化权威中心？ |


## 八、执行建议

### 8.1 竞品分级

| 优先级 | 竞品类型 | 调研深度 | 时间投入 |
|-|-|-|-|
| **P0** | 直接竞品（同品类、同目标用户） | 全维度深度拆解 | 每个2-3天 |
| **P1** | 间接竞品（同场景、不同品类） | 重点渠道策略拆解 | 每个1-2天 |
| **P2** | 参考标杆（不同品类但增长模式相似） | 飞轮+传播策略分析 | 每个1天 |

### 8.2 调研节奏建议

| 阶段 | 目标 | 时间建议 |
|-|-|-|
| 第一轮建档 | 建立竞品档案，覆盖所有P0和P1竞品 | 2周内完成 |
| 持续跟踪 | 更新动态、监控传播节点 | 每周1次快速扫描 |
| 深度复盘 | 每季度一次深度分析 | 每季度 |

