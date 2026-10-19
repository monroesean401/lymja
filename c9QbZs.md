# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 城市夜间照明的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E7%B3%BB%E5%88%97_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/EzX
- 儿童运动体验的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E7%B3%BB%E5%88%97_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/688=fbx
- 儿童运动体验的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E7%B3%BB%E5%88%97_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/hpl=525
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E7%B3%BB%E5%88%97_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/Bk1=NXL
- 社区活动策划的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%88%E6%9D%83%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%912023_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/924
- 节假日出行安排的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%88%E6%9D%83%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%912023_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/yay
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%88%E6%9D%83%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%912023_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/YBh
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%88%E6%9D%83%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%912023_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/640=kfc
- 公共服务沟通的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%88%E6%9D%83%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%912023_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/ymc=095
- 数字素养提升的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%88%E6%9D%83%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%912023_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/RUw=O9A
- 数字地图应用的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E5%A4%A7%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/689
- 社区公共议事中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E5%A4%A7%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/yib
- 公共空间导览的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E5%A4%A7%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/0O7
- 社区生活指南的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E5%A4%A7%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/008=oit
- 乡村生活观察的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E5%A4%A7%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/edu=019
- 街区更新实践的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E5%A4%A7%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/79a=ilg
- 青年职业探索的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/655
- 社区协商议事的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/lwy
- 社区设施共享的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/lOx
- 光伏知识科普的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/881=xgx
- 地方旅游导览的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/hwz=175
- 社区垃圾回收的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/JBL=W57
- 街区绿化养护的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/357
- 城市社区治理的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/vht
- 城市步行友好的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/5rI
- 社区应急准备的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/529=lqz
- 个人数据管理的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/wiz=682
- 药品使用科普的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/3hn=n7w
- 公共服务数字化的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/364
- 公共交通接驳的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/pmc
- 公共服务预约的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/ukf
- 科技馆参观体验的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/630=iuk
- 社区环保活动的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/yao=199
- 小区电梯维护的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/6oK=hjU
- 公共设施使用的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/436
- 城市夜间照明的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/zha
- 街区更新实践的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/dGk
- 家庭照护支持的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/084=dyo
- 乡村生态观察的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/nho=618
- 城市公共艺术的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/Gqh=ZHr
- 乡村生活观察的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/070
- 乡村公共阅读的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/egb
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/Xt6
- 家庭养老规划的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/198=fqv
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/jet=884
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/g4l=REq
- 消防知识宣传的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/284
- 线上办事服务的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/gxa
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/h4m
- 社区安全巡查的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/081=qiw
- 城市人文观察的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/tkx=415
- 社区垃圾回收的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/KB7=SMM
- 灵活就业交流的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E7%9A%84%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/583
- 乡村公共服务的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E7%9A%84%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/kte
- 绿色办公实践的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E7%9A%84%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/7kS
- 家庭节能设备的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E7%9A%84%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/808=vov
- 休闲运动入门的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E7%9A%84%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/wkp=302
- 数据分析入门中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E7%9A%84%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/ImE=zFY
- 公交站点体验的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/646
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/ggf
- 节日文化体验中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/Wa1
- 电动汽车充电的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/155=izu
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/xgi=467
- 在线教育体验的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/aEr=Bvd
- 老年人日常照护的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/154
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/lzw
- 劳动教育实践的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/6jH
- 社区科普课堂的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/757=stv
- 邻里互助活动的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/rys=041
- 劳动教育实践的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/aEe=Yqy
- 科学观察活动的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/449
- 家庭食品保存的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/chz
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/PHt
- 数字支付体验的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/187=rwf
- 社区阅读服务的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/bat=510
- 街道综合服务的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/cxq=Iqx
- 社区便民集市的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%8F%B0%E5%AD%90_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/929
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%8F%B0%E5%AD%90_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/ojx
- 软件开发学习的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%8F%B0%E5%AD%90_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/aRM
- 地方文化传播的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%8F%B0%E5%AD%90_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/614=utz
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%8F%B0%E5%AD%90_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/lti=451
- 城市共享单车的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%8F%B0%E5%AD%90_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/NLW=cRF
- 公共空间安全的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%85%AC%E7%9B%8A?/860
- 城市基础设施中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%85%AC%E7%9B%8A?/eji
- 数字艺术创作的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%85%AC%E7%9B%8A?/VTo
- 社区便民服务的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%85%AC%E7%9B%8A?/994=xhz
- 数字学习资源的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%85%AC%E7%9B%8A?/yim=074
- 远程协作工具的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%85%AC%E7%9B%8A?/rvT=nEO
- 乡村生活观察的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/482
- 老年友好服务有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/ihp
- 音乐欣赏活动的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/Bpw
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/154=lbx
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/pen=703
- 乡村产业科普的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/8fH=sRR
- 社区公共议事的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E5%91%A2_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/726
- 本地旅行体验的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E5%91%A2_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/iza
- 非遗体验活动的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E5%91%A2_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/0w6
- 智能手机助老的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E5%91%A2_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/867=nge
- 智慧停车服务的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E5%91%A2_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/nev=128
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E5%91%A2_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/jN5=a8y
- 灵活就业交流的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%80%E5%85%B1%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%95%8A_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/651
- 社区便民服务的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%80%E5%85%B1%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%95%8A_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/lgg
- 乡村公共服务的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%80%E5%85%B1%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%95%8A_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/tI2
- 文明养宠科普的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%80%E5%85%B1%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%95%8A_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/858=ikw
- 城乡公共服务的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%80%E5%85%B1%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%95%8A_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/vtk=680
- 邻里共享空间的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%80%E5%85%B1%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%95%8A_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/mAF=bck
- 社区公共餐饮的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/158
- 社区托育服务的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/dcg
- 在线教育体验的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/C8y
- 社区教育资源的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/233=tcb
- 日常摄影记录的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/lpn=917
- 城市共享单车的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/JqF=5ci
- 社区公共餐饮的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/288
- 科学观察活动的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/xhh
- 志愿服务平台的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/aeq
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/554=mlq
- 绿色出行服务的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/ctk=394
- 地方民俗记录的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/epH=8D0
- 软件开发学习的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E9%AB%98%E7%BA%A7%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%9C%BA%E5%88%B6_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/671
- 社区共享书架的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E9%AB%98%E7%BA%A7%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%9C%BA%E5%88%B6_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/hpf
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E9%AB%98%E7%BA%A7%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%9C%BA%E5%88%B6_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/wOn
- 社区便民集市的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E9%AB%98%E7%BA%A7%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%9C%BA%E5%88%B6_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/710=hqd
- 社区教育资源的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E9%AB%98%E7%BA%A7%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%9C%BA%E5%88%B6_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/mzx=606
- 绿色办公实践的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E9%AB%98%E7%BA%A7%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%9C%BA%E5%88%B6_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/vxr=0v8
- 在线教育体验的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%B8%B8%E6%88%8F%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84%E5%95%8A_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/187
- 社区体育组织的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%B8%B8%E6%88%8F%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84%E5%95%8A_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/obr
- 生活垃圾回收的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%B8%B8%E6%88%8F%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84%E5%95%8A_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/bh2
- 家庭安全提示的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%B8%B8%E6%88%8F%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84%E5%95%8A_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/102=uga
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%B8%B8%E6%88%8F%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84%E5%95%8A_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/cmc=331
- 社区活动空间的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%B8%B8%E6%88%8F%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84%E5%95%8A_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/jht=HW8
- 城市生活记录的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/323
- 社区协商议事的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/vvz
- 乡村公共文化的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/W9o
- 健康饮水科普的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/631=kuy
- 社区养老服务的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/tvy=296
- 家庭收纳实践的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/Zx5=jfb
- 城市便民驿站的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/418
- 科学教育活动的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/kzi
- 城市博物馆服务的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/MN4
- 市民意见收集的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/288=qzp
- 绿色校园实践中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/gtw=294
- 社区便利生活的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/bRo=Uuf
- 科学健身方法的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/179
- 社区菜市场服务的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/ozj
- 校园阅读活动的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/Wvq
- 本地旅行体验的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/209=kxx
- 公共空间导览的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/rzf=062
- 数字生活课堂的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/XFy=Ifc
- 图书馆数字服务的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/781
- 社区垃圾回收的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/nnr
- 社区家政服务的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/UWN
- 亲子科普活动的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/815=dzl
- 公共空间休憩的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/mni=118
- 社区公共餐饮的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/UtF=A69
- 社区垃圾回收的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/546
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/csy
- 绿色校园实践的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/lC9
- 租房信息服务的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/330=fkz
- 社区便民服务的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/axf=394
- 家庭网络使用的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/OO5=UuN
- 公共健身器材的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/056
- 安全出行教育的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/aqc
- 科学教育活动从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/sZQ
- 数字资源检索的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/840=fvi
- 数字设备回收的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/wwr=030
- 公共服务咨询的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/YmY=wFR
- 网络信息辨识的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/050
- 公共场所导视的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/muw
- 通勤路线规划的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/Eu7
- 数字资源检索的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/633=vbm
- 机器人科普活动的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/rqw=063
- 老年数字阅读的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/atA=BN4
- 农产品消费体验的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/566
- 儿童友好街区的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/twx
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/YNg
- 青少年编程学习的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/720=xsx
- 社区垃圾分类的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/lpz=479
- 智慧停车服务的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/Eb1=D2h
- 机器学习入门的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/329
- 信息无障碍体验的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/yhp
- 远程协作工具的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/lcs
- 城市绿色交通的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/972=rzc
- 城市文化路线中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/awk=699
- 社区学习活动的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/FHg=LDu
- 无障碍出行的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/736
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/thj
- 食品配送体验的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/s78
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/015=yzo
- 青年志愿活动的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/mmd=095
- 绿色办公实践的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/WqE=ZwS
- 传统手工艺体验的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/122
- 数字生活课堂的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/jpd
- 软件开发学习的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/cfj
- 公共场馆服务的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/168=svu
- 物业服务沟通的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/wls=390
- 家庭急救准备的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/Dbm=KZ9
- 乡村生态旅游的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/684
- 城市绿道建设的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/gvj
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/41z
- 新能源知识普及的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/720=bgl
- 公共空间照明的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/edn=025
- 数字创作工具的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/yD1=EG8
- 城市适老服务的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/875
- 创业经验分享的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/dwk
- 绿色校园实践的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/4OD
- 街区更新实践的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/013=qmb
- 社区快递服务的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/tlh=770
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/VuB=efx
- 数字课堂应用的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/658
- 城市夜间照明的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/llh
- 公园休闲体验的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/37t
- 社区快递服务的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/696=wya
- 非遗课堂体验的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/uhv=836
- 乡村文化活动的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/zPZ=BPP
- 社区便利生活的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/248
- 劳动教育实践的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/rhz
- 家庭食品保存的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/oUL
- 农产品消费体验的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/041=hvd
- 消防知识宣传的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/ftn=851
- 社区垃圾分类的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/WRr=bqo
- 全民阅读推广的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C?/746
- 数字便民地图的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C?/swa
- 社区活动策划的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C?/ot6
- 城市绿色交通的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C?/581=oal
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C?/lty=555
- 城市骑行环境的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C?/0NS=t8L
- 农产品消费体验的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/746
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/vpd
- 科学观察活动的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/AGT
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/469=ieg
- 家庭健康科普的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/dmn=671
- 健康饮食教育的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/Fhk=BYb
- 健康步道使用的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/475
- 社区菜市场服务从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/uho
- 数字支付体验的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/F0H
- 地方戏曲体验的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/957=dqf
- 家庭理财科普的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/fde=622
- 数字创意课程的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/ZNf=02E
- 城市住房服务的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/830
- 城市公共座椅的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/mah
- 城市社区治理的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/QVg
- 青少年科普实践的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/317=gfd
- 电动汽车充电的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/ydh=374
- 科普展览体验的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/FVT=Qg7
- 街区道路维护的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/215
- 社区设施共享的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/kyv
- 公共设施维护的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/6RI
- 家庭阅读计划的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/747=rnf
- 家庭急救准备的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/hvp=905
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/2pu=pIr

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
