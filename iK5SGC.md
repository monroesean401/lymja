# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

---

## 🔥 今日头条

**1️⃣ Meta 发布首个前沿模型系列 Muse Wonder，全球前沿竞赛进一步多极化。** 10月12日，Meta 超级智能实验室（Meta Superintelligence Labs，AI 负责人 Alexandr Wang）正式发布 Muse Wonder 与 Muse Wonder Full 两款模型（开发代号"Watermelon"），称其在个人与专业智能体（Agentic）任务、记忆与编程场景达到业界前沿水平。Meta 公布的基准显示其性能与 Anthropic 的 Claude Fable 5.1、OpenAI 的 GPT-6 Astra 相当；在 Artificial Analysis 智能指数 v4.3 中，Wonder Full 得分 56（标准版 52），仅次于 Claude Opus 5.5（58 分）、高于 OpenAI 与 Google 的最强模型（各 53 分）；中文媒体转述称其编程智能体表现与 Claude 并列第一。定价 $4/$20 每百万 token（输入/输出），与 Opus 5.5 同价位；已通过 Meta Model API 与 Muse Code 提供（Full 版限高级订阅，新增 Active Memory / Active Focus 能力）。发布当日 Meta 股价上涨约 3.4%–4.1%（约报 $748）。[来源：TechCrunch/WIRED/NYT/The Verge/新浪科技]

**2️⃣ 微软发布第三代自研 AI 芯片 Maia 300：从"最大押注"到百万颗级部署。** 10月12日于 OCP 全球峰会（圣何塞）亮相：288GB HBM4 显存、18TB/s 带宽；微软称其每兆瓦可产出比"领先 GPU 系统"多 40% 的 token，机架级吞吐为 Maia 200 的 7 倍。微软计划 2027 年起以"多吉瓦级"规模部署超 100 万颗 Maia 300，使其成为自家 AI 服务的主要推理硬件；公司预计今年资本开支超 1,750 亿美元。纳德拉称其为"对自研芯片的最大一笔押注"；当日微软股价涨约 2.4%，英伟达、AMD 承压。[来源：GeekWire/CNBC/Reuters/HPCwire]

---

## ☝ Headlines

- **Meta·Muse Wonder**：Meta 首个前沿模型发布，对标 Claude Opus 5.5/Fable 5.1 与 GPT-6 Astra，$4/$20 定价、发布日股价涨约 3-4%
- **微软·Maia 300**：第三代自研 AI 芯片亮相，2027 年部署超百万颗、能效 +40%/MW
- **亚马逊·Decart**：洽谈约 70 亿美元收购 AI 芯片软件公司 Decart（Anthropic 尽调后退出、亚马逊接手）
- **英国 AI 安全**：白宫解除 17 天冻结，UK AISI 恢复 OpenAI/Anthropic/DeepMind 预发布模型访问；同日英国公布 AI 风险防御包
- **DeepMind·AlphaProof Nexus**：解出 9 个 Erdős 开放数学问题（2 个悬置 56 年）+ 44 个数列猜想，并通过同行评审
- **中国 AI**：大模型周调用量 86.74 万亿 Token（环比 +50.96%）连续 24 周全球第一、前五全为中国模型；美国头部两家厂商则占近九成收入

---

## 📊 分类详报

### 🧠 模型与技术

- **Meta Muse Wonder 更多细节**：该系列由 Meta 超级智能实验室开发（2025 年 6 月招入 Scale AI 创始人 Alexandr Wang 后启动 AI 重构，历时约 14 个月），定位"面向个人与专业智能体任务的前沿模型"，较前代 Muse Spark 明显升级（Artificial Analysis 智能指数 48 → 52/56）。WIRED 评价其"让 Meta 重回 AI 前沿"。社区侧：开发者对比指出 Wonder 定价与 Opus 5.5 完全持平，但在 Meta 自家 14 项基准中有 9 项落后（dev.to 分析）；Full 版目前仅限 Meta 高级 AI 编码订阅用户。[来源：TechCrunch/WIRED/NYT/Artificial Analysis/dev.to]

- **Claude Opus 5.5 Max 首次登顶 Arena 智能体榜**：Anthropic 新模型首次入榜即夺得智能体榜第一，工具幻觉率仅 0.37%；综合榜由 Google gemini-4-argon-high 居首；国产模型 kimi-k3-max 稳居综合榜前 20，qwen3.8-max 等多款保持中上游。[来源：Arena AI 周榜（网易/搜狐转载）]

- **OpenRouter 周度调用数据（10月5日-11日）**：全球总调用量 172 万亿 Token（环比 +3.61%）；中国大模型 86.74 万亿（+50.96%），连续 24 周超过美国（18.97 万亿，+17.1%），约为其 4.6 倍；全球前五全为中国模型——DeepSeek V4.1 Flash（41 万亿、+60%）、智谱 GLM 5.3 Flash（12.2 万亿）、小米 MiMo-V2.6-Flash（11.5 万亿）、阶跃星辰 Step 5 Preview（8.84 万亿）、腾讯 Hy4 preview（8.28 万亿）；Claude Opus 5.5 居第八（5.02 万亿）。[来源：每日经济新闻/OpenRouter 测算]

### 📋 政策与监管

- **英国恢复前沿模型预发布访问权（10月12日）**：白宫逆转此前"企业须先获美国批准才能向英方共享模型"的政策，为期 17 天的冻结解除。英国 AI 部长 Kanishka Narayan 确认：UK AISI 将继续对 OpenAI、Anthropic、Google DeepMind 的最强模型进行发布前安全评估（正评估 Gemini 4 Argon 等系统）；其称目标是让英国"成为全球最难被 AI 攻击的国家之一"。[来源：Quartz/Bloomberg/Firstpost/TheNextWeb]

- **英国公布 AI 风险防御包（10月12日）**：追加系列国家级防御措施——延长"用前沿 AI 审计政府代码"试点（既有两轮试点已发现 1,000+ 潜在漏洞；其中已公布一轮以约 £13,000 的 token 成本发现 407 处弱点）；政府表示或立法保护关键基础设施免受 AI 网络威胁，并着手准备"自主系统脱离人类控制"类事件的应急机制（有专家呼吁"终止开关"）。[来源：Unite.AI/TheNextWeb/bankinfosecurity/resiliencemedia]

- **美国 CAISI 拟"并入"白宫**：路透报道，特朗普政府计划将商务部 AI 标准与创新中心（CAISI）的三名高级官员转入白宫编制、直接向白宫汇报（重组仍在敲定中）；CAISI 此前负责与 OpenAI、Google、微软等开展自愿性模型评估。[来源：Reuters/US News/cryptobriefing]

- **Brad Smith："牛奶受到的监管都比 AI 多"**：微软副董事长兼总裁 Brad Smith 呼吁建立全球统一的 AI 安全规则，包括独立评估机构与面向开发者的"紧急刹车"机制——并称当前 AI 的安全要求比一盒牛奶还少。[来源：Reuters/Fox Business]

- **比尔·盖茨警告（10月11-12日）**：在 CNN 采访中称 AI 是"人类发明过的最危险的技术"，最紧迫威胁是"未来一年内 AI 驱动的网络攻击"；强调不能让企业"自我监管"，并提到社会需讨论如何对 AI 与机器人的使用征税。[来源：CNN/Yahoo Finance]

- **中国：《关于发展新质生产力的意见》持续发酵**：中共中央、国务院 10 月 9 日印发该文件，明确"全面实施'人工智能+'行动"、加快推进 AI 手机/电脑等新一代智能终端应用，并建立技术监测、风险预警与应急响应体系、确保 AI"安全、可靠、可控"；本周进入配套落实期（如工信部"AI 应用服务商培育专项行动"）。[来源：国家发改委/财新/VOA]

- **布鲁金斯学会：AI 智能体（Agent）的全球治理**：发文探讨 AI 智能体跨境运行带来的治理缺口（责任归属、跨国部署合规）。[来源：Brookings]

### 💰 产业与商业

- **亚马逊洽购 Decart（约 70 亿美元）**：WSJ 首发（10月11日晚）——Decart 开发让 AI 模型跨不同芯片高效运行的软件，并研发"世界模型"（模拟 3D 环境）；公司 2023 年成立，今年 5 月估值近 40 亿美元（若按 70 亿成交，较该估值高出约 75%）。此前 Anthropic 8 月曾洽谈约 60 亿美元收购、9 月尽调后放弃；亚马逊为其战略客户并给予 Trainium 芯片早期访问。交易若落地将强化 AWS 自研芯片生态、进一步对冲英伟达依赖。[来源：WSJ/Bloomberg/Calcalist/Quartz]

- **微软 Maia 300 详细规格与部署计划**：288GB HBM4、18TB/s 带宽；每兆瓦 token 数 +40% vs 领先 GPU 系统、机架吞吐 7× vs Maia 200；2027 年"多吉瓦"部署、逾 100 万颗；年内资本开支预期超 1,750 亿美元。市场解读：微软推理算力从"英伟达为主"转向"自研为主"的转折点。[来源：The Verge/Notebookcheck/The Tech Portal/Reuters]

- **英伟达联合 AMD、Google、Meta 发布"开放数据中心规范 v0.7"**：在 OCP 全球峰会上联合发布统一 AI 工厂设施蓝图（覆盖电力架构、冷却、物理布局）；Google、Meta、微软、英伟达另发布"OCP 电网韧性规范"（应对公用事业扰动、快速恢复）；英伟达同时通过 MGX 1.2 开放 Vera Rubin NVL72 机架设计（支持 250kW 级机架），并宣布 ConnectX-10 / BlueField 支持 Google Falcon 传输协议（开放互联再进一步）。[来源：NVIDIA博客/StorageReview/Yahoo Finance]

- **Salesforce 收购以色列 AI 分析公司 Loops（约 3,000 万美元）**：并入 Tableau，主打"agentic analytics"（解释业务指标变动并给出行动建议）；预计 11 月初交割；消息后 CRM 涨约 3%。[来源：CTech/Globes/Proactive Investors]

- **中美 AI 商业化分化（分析）**：Menlo Ventures 数据显示，2025 年 OpenAI + Anthropic 合计占企业 LLM API 支出 67%；其 5 月报告显示两家在追踪的 34 家头部 AI 初创中占 89% 收入；Ramp 数据称首次采购 AI 的企业中 Anthropic 占逾 73% 支出。对照中国侧"调用量份额领先、收入份额有限"的结构——模型能力差距正快速转化为商业收入差距。[来源：新浪科技（投资者内参）]

### 🚀 应用与产品

- **Apple "Welcome Home" 发布会（今日 10月13日，9:00 ET 纽约）**：预计推出智能家居中枢（HomePad 类新品）、新一代 Apple TV 4K、HomePod mini 等；以"新闻稿 + 媒体体验"形式发布，AI 家庭中枢为核心看点。[来源：The Verge/9to5Mac/MacRumors]

- **阶跃星辰 STEPX Neo 智能体手机（今日上海发布）**：阶跃终端"Ready Builder One"发布会推出首款"大模型原生智能体手机"；同日，千问新一代 AI 眼镜现货发售；阶跃星辰将于 10月15日 正式开源 Step 5 Preview（该模型已上线腾讯 WorkBuddy）。[来源：智东西/华尔街见闻/东方财富/IT之家]

- **富士胶片 Synapse Pathology v3.0**（10月12日）：数字病理平台扩展 AI 能力。[来源：BioSpace]

### 🔬 研究前沿

- **DeepMind "AlphaProof Nexus" 解出 9 个 Erdős 开放问题（10月12日集中报道）**：从 353 个未解 Erdős 问题中解出 9 个（其中 2 个自 1970 年起悬置 56 年），另证明 44 个 OEIS 数列猜想；解法先行在线公开、成果通过同行评审——AI 数学推理从"竞赛题"走向真实开放问题的标志性一步。[来源：the-decoder/Reddit/The Daily Star]

- **TikTok CEO 周受资（Shou Zi Chew）：AI 将在 3 年内带来"重大科学突破"**（CNBC，10月12日）——认为 AI 对科学的推动（药物研发、材料等）将在三年内集中兑现。[来源：CNBC]

---

## ⚡ 明日关注

- **10月14日：Anthropic 上市前投资者日（Investor Day）**——已向机构投资者发出邀请（Bloomberg）；正式 IPO 营销或于 11月9日当周启动、目标感恩节前挂牌。市场关注其 ARR 指引与算力承诺兑现节奏（22V Research 视其为"市场内部结构与 AI 前景的重要节点"）。
- **10月15日：台积电 Q3 财报**（14:00 台北时间）——营收预计 NT$1.49 万亿（约 $467 亿、同比 +51%，创纪录）、净利润预计同比 +65%；AI 需求风向标；同周还有 ASML 财报。
- **10月15日：阶跃星辰正式开源 Step 5 Preview**（600B 稀疏 MoE，面向 Agentic 任务）。
- **10月13-16日：TechCrunch Disrupt 2026（旧金山）与 OCP 全球峰会持续**——更多 AI 基础设施/芯片发布与创业公司动向。
- **持续跟踪**：① 英伟达-Reflection AI 谈判进展；② Anthropic IPO 流程（投资者日 → 路演）；③ 英国 AI 立法动向（关键基础设施保护）。

---

## ⚡ 其他新闻

- 科学运动指导的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/705
- 老年人文化生活的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/mdl
- 社区安全巡查的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/DET
- 社区手工活动的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/208=zym
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/jqi=313
- 城市绿色交通的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/TXF=hKa
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/585
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/sep
- 周末休闲规划的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/d1w
- 乡村休闲旅游的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/541=qzx
- 绿色出行服务的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/vqm=870
- 社区协商议事中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/AsV=pr6
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/909
- 社区邻里服务的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/hqy
- 青年就业服务的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/ECu
- 在线教育体验的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/907=wpn
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/xoq=540
- 城市生活服务的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/Zsd=pYr
- 社区快递服务的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/744
- 图书借阅体验的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/ifb
- 街区道路维护中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/1n5
- 社区活动空间的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/942=sez
- 节气饮食文化的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/eqa=561
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/7WN=RnE
- 社区知识分享的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/977
- 基层医疗预约的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/syj
- 社区安全巡查的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/8MH
- 社区生活指南的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/719=gch
- 健康步道使用的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/qqu=165
- 机器人科普活动的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/OUh=ZH8
- 社区活动策划的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/449
- 青年职业探索的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/wdj
- 城市共享单车的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/W7f
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/974=ile
- 休闲运动入门的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/dih=928
- 公园无障碍服务的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/IOx=g5t
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E9%9B%85%E8%99%8E%E5%9C%88%E5%AD%90?/315
- 电动汽车充电的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E9%9B%85%E8%99%8E%E5%9C%88%E5%AD%90?/mko
- 家庭节能实践的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E9%9B%85%E8%99%8E%E5%9C%88%E5%AD%90?/iN6
- 节假日出行安排中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E9%9B%85%E8%99%8E%E5%9C%88%E5%AD%90?/254=lkn
- 周末休闲规划的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E9%9B%85%E8%99%8E%E5%9C%88%E5%AD%90?/oyg=805
- 公共交通信息服务的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E9%9B%85%E8%99%8E%E5%9C%88%E5%AD%90?/STZ=Fb1
- 志愿服务平台的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/430
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/cwn
- 公交站点体验的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/sKE
- 社区设施共享的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/359=hwh
- 周末休闲规划的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/nxo=457
- 食品安全科普的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/Esn=sGG
- 城市骑行环境的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/705
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/dwi
- 生活技能分享的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/n5w
- 劳动教育实践有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/057=kvp
- 线上阅读资源的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/ttn=323
- 邻里互助活动的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/ewf=FN0
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/417
- 城市体育设施的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/ljj
- 地方民俗记录的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/mLk
- 线上办事服务的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/466=iia
- 青年志愿活动的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/aov=348
- 急救知识普及的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/mUb=rqX
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/737
- 社区互助网络的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/kgo
- 居家适老化改造的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/ziX
- 街区道路维护中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/340=lix
- 邻里共享空间的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/xzv=031
- 创业经验分享的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/dIY=qvg
- 亲子阅读活动的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/518
- 城市文化路线的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/fac
- 志愿者培训交流的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/NdK
- 文明养宠科普的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/267=kwi
- 公共场所导视的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/kwj=752
- 绿色出行服务的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/MZs=o8n
- 人工智能科普的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/228
- 青少年户外教育从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/ssv
- 农业科普体验的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/vMd
- 公园亲子设施的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/113=lxj
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/nts=491
- 乡村生活观察的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/COV=U3s
- 科学健身方法的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/244
- 公交站点体验的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/onz
- 城市共享单车的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/tzQ
- 科学观察活动的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/480=ixw
- 数字艺术创作的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/ivi=127
- 节能家电使用的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/fEj=q1U
- 在线学习体验的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/638
- 家庭急救准备的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/rdk
- 青少年编程学习的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/l9Q
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/882=mfh
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/mce=125
- 骑行路线规划的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/jVb=xXb
- 社区法律科普的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/363
- 绿色快递包装的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/ind
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/I24
- 节气饮食文化从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/995=wte
- 儿童安全出行的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/zqi=298
- 社区读书角建设的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/78M=rx6
- 社区活动报名的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/123
- 绿色建筑理念的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/rdh
- 基层健康服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/5Ee
- 健康信息获取的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/493=glf
- 地方美食文化的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/onr=243
- 绿色校园实践的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/bBC=gJW
- 老年人文化生活的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/275
- 公共场馆服务的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/zil
- 绿色办公实践中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/zCd
- 数字档案服务的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/277=rks
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/vpv=839
- 公共设施使用的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/jqI=TuT
- 文明养宠科普的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/417
- 户外活动组织的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/dqo
- 健康饮食教育的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/HHc
- 青年就业服务的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/948=cjd
- 无障碍出行的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/tel=777
- 社区宠物管理的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/kuy=7cv
- 家庭照护支持的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/143
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/oqi
- 校园阅读活动的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/I3U
- 小区停车协商的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/161=yox
- 数字素养提升的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/wpx=301
- 环境监测科普从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/6AU=oBb
- 城市基础设施的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/345
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/kfd
- 绿色消费选择的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/hgV
- 儿童友好街区的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/554=jmp
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/mao=907
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/wxs=0Rd
- 乡村文化空间的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/160
- 城市博物馆活动的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pyi
- 社区邻里服务的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Xx9
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/463=obq
- 乡村文化活动的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/qnz=783
- 数字公共文化的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/TDS=pee
- 社区学习活动的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/983
- 节能生活方式的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/qib
- 市民意见收集的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/cCQ
- 个人信息保护的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/095=ppz
- 青少年职业启蒙的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/sfz=539
- 城市住房服务的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/SI5=eoD
- 便民服务地图的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/578
- 社区邻里服务的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/dun
- 社区科普课堂的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/e2B
- 城市生活记录的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/141=sus
- 城市绿色交通的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/bld=397
- 公共服务评价中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/3ng=xXN
- 社会体育指导的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/120
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/hnb
- 节假日出行安排的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/onY
- 亲子阅读活动的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/059=njo
- 智慧城市体验的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/mjy=403
- 家庭节能实践的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/xOK=vDs
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/845
- 城市共享单车的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/zul
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/ygh
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/826=lmj
- 旧物循环利用中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/eyy=198
- 公共空间休憩的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/tCX=p0c
- 公共设施维护的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/599
- 乡村文化活动的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/ire
- 家庭健康管理的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/pFl
- 节假日出行安排的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/813=bvt
- 生活服务数字化的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/jec=486
- 老旧小区改造的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/PQ2=Dpl
- 无障碍信息设计的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/237
- 社区菜市场服务从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/hre
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/pEd
- 劳动教育实践的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/257=gwv
- 社区停车服务的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/gnp=546
- 城市文明实践的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/egV=9kb
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/649
- 消防知识宣传的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/aqs
- 公共文化活动的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/4oF
- 智能手机助老的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/081=hbo
- 公共服务评价的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/pph=921
- 街区小店体验的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/6Dm=vb8
- 数字资源检索的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/473
- 新能源出行的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/cvs
- 城乡公共服务的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/ONF
- 数字艺术创作的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/038=ekf
- 社区知识分享的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/zfw=829
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/3cZ=89i
- 社会体育指导的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/503
- 农产品品牌传播的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/lhx
- 社区托育服务的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/MTc
- 消防知识宣传的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/963=elo
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/mgp=066
- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/tCK=oK9
- 社区邻里服务的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/413
- 居民健康教育的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/dbw
- 绿色出行服务的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/Rfn
- 公园休闲体验的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/125=cbc
- 家庭运动计划的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/iby=113
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/2CZ=D8W
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/678
- 青少年职业启蒙的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/muo
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/nb8
- 城市公共饮水的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/000=hdj
- 旧物循环利用的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/oxb=010
- 社区文化节活动的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/2Ad=tDv
- 数字阅读服务的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/246
- 科技馆参观体验的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/ejn
- 城市微更新实践的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/V8W
- 社区故事采集的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/560=vod
- 地方美食文化的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/jww=290
- 城市共享单车的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/3RS=3i0
- 乡村教育资源的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%9B%B4%E6%92%AD?/281
- 家庭消费规划的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%9B%B4%E6%92%AD?/wih
- 城市应急科普的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%9B%B4%E6%92%AD?/hDN
- 城市公共厕所的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%9B%B4%E6%92%AD?/518=imn
- 传统手工艺体验的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%9B%B4%E6%92%AD?/rgu=049
- 小区公共照明的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%9B%B4%E6%92%AD?/0SW=6e9
- 乡村产业科普的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%90%86%E8%B4%A2?/851
- 公共服务预约的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%90%86%E8%B4%A2?/lug
- 环境监测科普的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%90%86%E8%B4%A2?/1OA
- 科普展览体验的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%90%86%E8%B4%A2?/668=efs
- 公共服务咨询的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%90%86%E8%B4%A2?/pkc=186
- 安全出行教育的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%90%86%E8%B4%A2?/HGh=Rjm
- 校园阅读活动的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/468
- 个人信息保护的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/vqc
- 日常摄影记录的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/E9i
- 环境监测科普的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/961=rhe
- 科技馆参观体验的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/lir=716
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/Ook=0nU
- 社区文化传播的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/585
- 科学教育活动的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/tgq
- 软件开发学习的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/y1D
- 开放数据应用的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/964=ivl
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/qju=867
- 家庭园艺实践的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/Lcg=z4O
- 软件开发学习的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/264
- 光伏知识科普的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/fml
- 急救知识普及的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/JPL
- 绿色快递包装的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/881=yjs
- 社区文化传播中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/pog=198
- 数字学习资源的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/6mP=XF8
- 公共卫生设施的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/483
- 图书借阅体验的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/mmx
- 公共服务评价中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/dLs
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/721=akc
- 便民维修服务的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/rxc=873
- 图书借阅体验的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/mcN=x0R
- 老年人出行服务的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/280
- 社区庭院绿化的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/djj
- 社区休闲设施的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/iq0
- 开放式学习空间的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/747=udx
- 健康饮水科普的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/xqn=423
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/Pyi=aIE
- 垃圾分类指导的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/400
- 社区宠物管理的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/kzy
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/d0X
- 城市慢跑路线的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/836=asx

---

## 📈 关键数据（10月11-13日）

| 指标 | 数值 | 变化/说明 |
|------|------|------|
| 全球大模型周调用量（10/5-11） | 172 万亿 Token | 环比 +3.61%（OpenRouter 测算） |
| 中国大模型周调用量 | 86.74 万亿 Token | 环比 +50.96%；连续 24 周全球第一 |
| 美国大模型周调用量 | 18.97 万亿 Token | 环比 +17.1% |
| Meta Muse Wonder 定价 | $4 / $20（每百万 Token 入/出） | 与 Claude Opus 5.5 同价位 |
| Meta / 微软股价（10/12） | Meta 约 $748（+3.4%–4.1%）；MSFT +2.4% | 模型与自研芯片发布驱动 |
| 微软 Maia 300 | 288GB HBM4；18TB/s；+40% tokens/MW | 2027 年部署超 100 万颗；资本开支预期 >$1750 亿（今年） |
| 亚马逊洽购 Decart | 约 $70 亿 | 较 5 月估值（近 $40 亿）高约 75% |
| AlphaProof Nexus 成果 | 9 个 Erdős 问题 + 44 个数列猜想 | 其中 2 题悬置 56 年；已通过同行评审 |
| 英国网络防御试点 | 累计发现 1,000+ 潜在漏洞 | 单轮试点：407 处弱点/£13,000 token 成本 |

---

*本简报由 Hermes Agent 自动生成*  
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  @PHWT7等*  
*仅供参考，不构成投资建议*
