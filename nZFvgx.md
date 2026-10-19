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

- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E9%80%9A%E7%94%A8%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/921
- 在线教育体验的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E9%80%9A%E7%94%A8%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/zho
- 社区宠物管理的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E9%80%9A%E7%94%A8%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/0bT
- 老年人文化生活中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E9%80%9A%E7%94%A8%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/452=fcp
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E9%80%9A%E7%94%A8%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/nqh=472
- 医院导诊服务的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E9%80%9A%E7%94%A8%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/1Yh=wc4
- 绿色消费选择的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%83%AD%E6%A6%9C?/344
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%83%AD%E6%A6%9C?/apl
- 公共服务咨询的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%83%AD%E6%A6%9C?/IR9
- 光伏知识科普的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%83%AD%E6%A6%9C?/284=pcr
- 小区停车协商的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%83%AD%E6%A6%9C?/plp=254
- 城市体育设施的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%83%AD%E6%A6%9C?/ACO=t59
- 家庭消费规划的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/389
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/exw
- 公共文化活动的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/XDI
- 社区停车服务的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/267=ayp
- 农业科普体验的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/mbq=163
- 传统节日科普的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/vXx=WZ4
- 无障碍出行的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/969
- 文化讲座服务的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/ele
- 志愿者培训交流的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/6n8
- 儿童阅读角的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/541=ujn
- 农产品消费体验的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/gta=692
- 图书借阅体验的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/ikA=EYO
- 街道综合服务的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9APP%E6%80%8E%E4%B9%88%E7%94%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/915
- 乡村生态旅游的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9APP%E6%80%8E%E4%B9%88%E7%94%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/zic
- 电子商务服务的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9APP%E6%80%8E%E4%B9%88%E7%94%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/o9W
- 绿色生活实践的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9APP%E6%80%8E%E4%B9%88%E7%94%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/236=cub
- 公共设施维护的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9APP%E6%80%8E%E4%B9%88%E7%94%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/uku=894
- 公益活动组织的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9APP%E6%80%8E%E4%B9%88%E7%94%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/dBd=9TM
- 城市公共空间的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/951
- 公共服务数字化的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/mpd
- 日常摄影记录的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/qdV
- 老年人日常照护的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/614=otp
- 邻里互助活动的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/lbv=189
- 社区艺术活动的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/DYX=6bf
- 绿色快递包装中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/703
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/xmj
- 运动安全知识的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/lRr
- 公共卫生设施的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/791=fck
- 数字公共文化的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/mzh=020
- 终身学习资源的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/Z4w=PI1
- 老年智能设备的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E8%80%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/936
- 城市基础设施的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E8%80%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/ybc
- 休闲运动入门的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E8%80%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/9QQ
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E8%80%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/434=wsx
- 节气饮食文化的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E8%80%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/lup=325
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E8%80%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/3CC=2Cm
- 老年友好服务的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/086
- 公共健身器材的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/iad
- 公共交通接驳的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/RPe
- 应急物资管理的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/649=gjy
- 社区应急准备的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/cxp=305
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/144=pRm
- 社区家政服务的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/898
- 公共空间安全的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/ffm
- 农业科普体验的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/EWJ
- 远程协作工具的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/032=xqz
- 学校体育活动的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/cfw=089
- 传统节日科普的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/vrm=87Z
- 应急物资管理的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/988
- 居家适老化改造的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/mjm
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/xwt
- 城市步行环境的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/244=lxw
- 社区宠物管理的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/ive=930
- 志愿者培训交流的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/ljp=aQC
- 城市噪声观察的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_m%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/916
- 公共文化活动的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_m%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/dmk
- 网络安全教育的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_m%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/uPT
- 乡村公共阅读的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_m%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/786=aty
- 城市住房服务的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_m%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ysj=340
- 社区老年食堂的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_m%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/u4R=58n
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/696
- 城市展览体验的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/pjk
- 社区安全巡查的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/l4T
- 城市绿色交通的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/528=lsa
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/dsp=487
- 周末休闲规划的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/vqp=qqz
- 公共空间导览的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A9500-top_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/195
- 药品使用科普的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A9500-top_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/yig
- 社区防暑服务的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A9500-top_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/F9w
- 城市生活记录的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A9500-top_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/013=xhe
- 城市公共厕所的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A9500-top_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/ufo=008
- 城市游园体验的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A9500-top_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/z3L=o19
- 城市公共艺术的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/109
- 创业经验分享的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/nri
- 家庭消费规划的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/ysr
- 城市步行环境中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/167=baw
- 公共卫生宣传的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/qyl=495
- 街区更新实践的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/NZ3=Fiq
- 居家适老化改造的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/634
- 城市夜间生活的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/jln
- 邻里共享空间的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/cJY
- 城市水环境观察的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/575=uyt
- 电子商务服务的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/hvr=067
- 通勤路线规划的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/QdG=LFO
- 公交站点体验的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/069
- 城市夜间照明中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/lxu
- 城市公共自行车的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/aSs
- 数字课堂应用的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/081=qfq
- 生活垃圾回收的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/hzg=777
- 青年职业探索的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/ePe=nmm
- 人工智能科普的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/112
- 公共设施维护的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/ibr
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/TGq
- 儿童安全出行的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/205=xsm
- 校园阅读活动的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/erl=624
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/D9k=7nj
- 公共场所导视的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/988
- 社区艺术活动的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/zks
- 乡村文化活动的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/Idq
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/088=coi
- 校园节能行动的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/kbz=902
- 家庭防灾准备的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%A3%B9%E5%8F%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/OX9=62Q
- 数字档案服务的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%B0%8A%E5%BD%A9%E7%BD%91%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/395
- 社区故事采集的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%B0%8A%E5%BD%A9%E7%BD%91%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/xqf
- 电子商务服务的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%B0%8A%E5%BD%A9%E7%BD%91%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/TZS
- 绿色快递包装的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%B0%8A%E5%BD%A9%E7%BD%91%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/170=btw
- 社区学习活动的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%B0%8A%E5%BD%A9%E7%BD%91%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/iam=921
- 邻里互助活动的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%B0%8A%E5%BD%A9%E7%BD%91%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/Cum=al0
- 城市微更新实践的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_360%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9E%E5%BD%A9%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%9C%9B?/689
- 文明养宠科普的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_360%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9E%E5%BD%A9%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%9C%9B?/byq
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_360%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9E%E5%BD%A9%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%9C%9B?/A5R
- 绿色生活实践的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_360%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9E%E5%BD%A9%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%9C%9B?/193=vdj
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_360%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9E%E5%BD%A9%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%9C%9B?/whg=265
- 城市文化路线的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_360%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9E%E5%BD%A9%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%9C%9B?/3T4=fef
- 科学运动指导的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_360%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/865
- 家庭运动计划的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_360%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/flm
- 城乡交流活动的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_360%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/RaD
- 农村环境治理的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_360%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/464=vsh
- 健康步道使用的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_360%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/tzi=051
- 食品配送体验的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_360%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/Xcx=0BE
- 职业技能学习的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_360%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/621
- 农产品品牌传播的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_360%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/uuw
- 城市休闲步道的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_360%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/mcb
- 公共服务指南的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_360%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/490=xve
- 街头绿植养护的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_360%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/glo=304
- 公共空间休憩的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_360%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Bax=X0g
- 城市水环境观察中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%9117500_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/074
- 城市应急科普的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%9117500_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/umt
- 通勤路线规划的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%9117500_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/pqA
- 社区休闲设施的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%9117500_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/100=lvj
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%9117500_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/skk=094
- 公共服务预约的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%9117500_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/D7F=4Ym
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AE%BA%E5%9D%9B_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/168
- 就业技能培训的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AE%BA%E5%9D%9B_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/fbh
- 城市博物馆服务的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AE%BA%E5%9D%9B_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/wTM
- 社会体育指导的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AE%BA%E5%9D%9B_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/163=nqj
- 跨代沟通活动的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AE%BA%E5%9D%9B_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/hch=654
- 公共交通接驳的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AE%BA%E5%9D%9B_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/PrJ=F48
- 校园安全教育的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B9%90%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93D_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/837
- 城市共享单车的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B9%90%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93D_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/vdc
- 城市生活记录的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B9%90%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93D_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/EAn
- 乡村生态观察的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B9%90%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93D_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/381=xuc
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B9%90%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93D_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/grb=135
- 租房信息服务的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B9%90%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93D_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/hbR=r4E
- 绿色快递包装的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/875
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/nwo
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/Dsl
- 邻里共享空间的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/825=aul
- 家庭饮食安排的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/urh=551
- 城市生活服务的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/vgc=sHF
- 图书馆数字服务的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%B7%A5%E5%85%B7%E5%9B%BE%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/188
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%B7%A5%E5%85%B7%E5%9B%BE%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/xve
- 城市建设科普的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%B7%A5%E5%85%B7%E5%9B%BE%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/lFB
- 公共交通接驳的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%B7%A5%E5%85%B7%E5%9B%BE%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/453=isn
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%B7%A5%E5%85%B7%E5%9B%BE%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/bee=899
- 生活垃圾回收的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%B7%A5%E5%85%B7%E5%9B%BE%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/Izm=1nq
- 城市基础设施的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AF%95%E6%9C%BA%E5%8F%B7_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/760
- 文化讲座服务的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AF%95%E6%9C%BA%E5%8F%B7_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ejl
- 公园休闲体验从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AF%95%E6%9C%BA%E5%8F%B7_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zd9
- 城市步行环境的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AF%95%E6%9C%BA%E5%8F%B7_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/122=mxk
- 志愿者培训交流的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AF%95%E6%9C%BA%E5%8F%B7_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zrk=345
- 读书会组织的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AF%95%E6%9C%BA%E5%8F%B7_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kXw=ZnI
- 消防知识宣传的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9%E7%BD%9117500%E5%8E%9F%E5%88%9B%E4%B8%93%E4%B8%9A_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/723
- 软件开发学习的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9%E7%BD%9117500%E5%8E%9F%E5%88%9B%E4%B8%93%E4%B8%9A_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/qbl
- 家庭健康管理中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9%E7%BD%9117500%E5%8E%9F%E5%88%9B%E4%B8%93%E4%B8%9A_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/EiS
- 城市骑行环境的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9%E7%BD%9117500%E5%8E%9F%E5%88%9B%E4%B8%93%E4%B8%9A_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/853=ygm
- 个人数据管理的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9%E7%BD%9117500%E5%8E%9F%E5%88%9B%E4%B8%93%E4%B8%9A_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/ybu=009
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9%E7%BD%9117500%E5%8E%9F%E5%88%9B%E4%B8%93%E4%B8%9A_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/VR2=BTz
- 青少年心理健康的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/764
- 数字公共文化的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/ynx
- 农业科普体验的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/mjo
- 公共设施维护的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/282=xeg
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/uip=344
- 社区阅读服务的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/3Xx=8xg
- 基层服务创新的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/755
- 青年志愿活动的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/spt
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/Nb1
- 食品配送体验的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/088=rzo
- 城市步行环境的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/ned=262
- 城市公共标识的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/cXt=inC
- 在线学习体验的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/832
- 地方旅游导览的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/bvy
- 家庭用电安全的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/HIR
- 软件开发学习的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/015=yiw
- 便民信息查询的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/cja=789
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/QJt=mcL
- 城市可持续生活的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%B9%B6%E8%B4%AD?/240
- 家庭志愿活动的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%B9%B6%E8%B4%AD?/lgj
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%B9%B6%E8%B4%AD?/lM2
- 社区便利生活的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%B9%B6%E8%B4%AD?/862=dpl
- 绿色出行服务的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%B9%B6%E8%B4%AD?/qhf=690
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%B9%B6%E8%B4%AD?/MWT=JaR
- 数字素养提升的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/988
- 老年友好服务的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/hjo
- 城市公共饮水的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/JDE
- 个人时间管理中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/169=xlb
- 城市空气科普的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/qck=771
- 家庭照护支持的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/4m7=mA4
- 市民热线服务的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8APP_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/920
- 生活垃圾回收的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8APP_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/yjy
- 户外活动组织的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8APP_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/0h1
- 社区菜市场服务的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8APP_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/732=ewv
- 公园休闲体验的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8APP_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/rnn=738
- 家庭收纳实践的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8APP_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/BXv=Gl5
- 光伏知识科普的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%8B%E8%BD%BD%E4%B9%90%E5%BD%A9%E7%BD%91app_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/707
- 城市适老服务的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%8B%E8%BD%BD%E4%B9%90%E5%BD%A9%E7%BD%91app_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/ioi
- 社区体育组织的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%8B%E8%BD%BD%E4%B9%90%E5%BD%A9%E7%BD%91app_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/zPm
- 儿童安全出行的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%8B%E8%BD%BD%E4%B9%90%E5%BD%A9%E7%BD%91app_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/389=bqy
- 社区阅读服务的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%8B%E8%BD%BD%E4%B9%90%E5%BD%A9%E7%BD%91app_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/hof=888
- 数字地图应用的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%8B%E8%BD%BD%E4%B9%90%E5%BD%A9%E7%BD%91app_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/xzg=1P0
- 地方旅游导览的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8365%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/633
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8365%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/rbb
- 节日文化体验的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8365%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/mUc
- 青少年科技社团的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8365%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/399=ovl
- 社区健康讲座的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8365%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/zzd=460
- 社区活动策划的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8365%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/lUS=BX6
- 市民意见收集的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8365%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%93%94%E5%93%A9%E6%B8%AF%E8%82%A1?/653
- 社区家政服务的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8365%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%93%94%E5%93%A9%E6%B8%AF%E8%82%A1?/qvw
- 青少年科技社团的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8365%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%93%94%E5%93%A9%E6%B8%AF%E8%82%A1?/3EP
- 城市展览体验的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8365%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%93%94%E5%93%A9%E6%B8%AF%E8%82%A1?/143=poy
- 城乡交流活动的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8365%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%93%94%E5%93%A9%E6%B8%AF%E8%82%A1?/jfc=409
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8365%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%93%94%E5%93%A9%E6%B8%AF%E8%82%A1?/SLN=EJH
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E6%89%98?/358
- 社区阅读服务的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E6%89%98?/bwi
- 社区共享书架的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E6%89%98?/aCb
- 数字生活课堂的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E6%89%98?/483=paa
- 节日文化体验的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E6%89%98?/vli=649
- 线上办事服务的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E6%89%98?/c7D=1Vt
- 城市公共座椅的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/556
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/cwz
- 街道综合服务的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/hW8
- 社区养老服务的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/804=npd
- 课后服务体验的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/idt=132
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/2mG=ZvW
- 乡村产业科普的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E5%93%94%E5%93%A9%E5%86%9B%E4%BA%8B?/699
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E5%93%94%E5%93%A9%E5%86%9B%E4%BA%8B?/des
- 终身学习资源的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E5%93%94%E5%93%A9%E5%86%9B%E4%BA%8B?/Ems
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E5%93%94%E5%93%A9%E5%86%9B%E4%BA%8B?/683=vau

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
