# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 基层健康服务从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/vjy=654
- 家庭急救准备的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/ih2=7CT
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/478
- 社区志愿服务的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/jxm
- 乡村文化空间的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/kDR
- 乡村生态观察的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/470=xjh
- 街区绿化养护的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/xrk=395
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/r6B=mpl
- 小区公共照明的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/187
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/gxs
- 开放式学习空间的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/RBl
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/054=prn
- 社区活动策划的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/asc=448
- 周末休闲规划中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/thB=e16
- 乡村文化活动的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/497
- 社区菜市场服务从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/mik
- 家庭防灾准备的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/IEd
- 乡村生态观察的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/242=djz
- 公共空间安全的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/rxa=536
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/vnn=nLy
- 传统手工艺体验的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/484
- 便民服务窗口的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/hdb
- 数字设备回收的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/UH9
- 开放数据应用的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/260=svv
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/zsz=254
- 家庭用电安全的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/Fhr=Djg
- 绿色校园实践的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E6%95%99%E8%82%B2?/928
- 城市共享单车的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E6%95%99%E8%82%B2?/kss
- 街区小店体验的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E6%95%99%E8%82%B2?/JaG
- 家庭健康管理的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E6%95%99%E8%82%B2?/593=nlk
- 非遗课堂体验的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E6%95%99%E8%82%B2?/ntx=548
- 垃圾分类指导的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E6%95%99%E8%82%B2?/bPu=Pf4
- 租房信息服务的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/045
- 智慧停车服务的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/wwf
- 城市适老服务的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/ysV
- 社区垃圾回收的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/134=smz
- 社区公共议事的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/axi=477
- 个人数据管理的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/iWr=VnW
- 社区知识分享的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/101
- 社区手工活动的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/app
- 街区小店体验的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/3eN
- 数字公共文化的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/526=wsb
- 城乡交流活动的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/fat=073
- 老年人日常照护的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/FIu=1TP
- 公共服务预约的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/754
- 食品安全科普的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/nll
- 街头绿植养护的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/Br8
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/240=rpk
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/huu=006
- 信息无障碍体验的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%9B%98%E7%82%B9?/Njz=aKt
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/302
- 公共卫生宣传的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/qxk
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/MYp
- 城市适老服务的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/810=qam
- 科学教育活动的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/iqi=868
- 校园社团活动的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/lsx=7sC
- 城市可持续生活的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/995
- 社区商业活力的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/fjk
- 社区阅读服务的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/mxP
- 绿色生活实践的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/846=ckm
- 老年学习活动的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/lme=339
- 本地消费场景的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/hI5=zxN
- 全民健身活动的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/746
- 无障碍信息设计的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/wph
- 通勤路线规划的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/NuQ
- 老旧小区改造的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/281=msa
- 读书会组织的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/qbn=699
- 智能家居应用的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/aSW=AVi
- 社区应急准备的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/016
- 校园安全教育的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/hlk
- 家庭消费规划的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/QKB
- 街头绿植养护的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/862=rxn
- 学校体育活动的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/rrb=703
- 旧物循环利用的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/shS=zKY
- 个人时间管理的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/916
- 休闲运动入门的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/eak
- 周末休闲规划的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/QxO
- 开放数据应用的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/324=yhb
- 城市噪声观察的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/msb=398
- 软件开发学习的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/Ihd=CAW
- 食品配送体验的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/511
- 城乡公共服务的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/puy
- 家庭志愿活动的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/YeI
- 社区快递服务的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/667=ues
- 老年智能设备的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/yjk=655
- 机器学习入门的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/c5F=zTT
- 志愿服务平台的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/357
- 公共空间安全的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/ylp
- 校园社团活动的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/JYe
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/113=xmj
- 儿童运动体验的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/ppm=968
- 城市绿色交通的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/VCW=ZVM
- 数字学习资源的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/285
- 老年数字阅读的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/yau
- 物业服务沟通的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/qII
- 社区活动空间的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/603=nnu
- 社区法律科普的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/zts=706
- 文明养宠科普的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/1s1=GfG
- 社区活动空间的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%80%9F%E8%A7%88?/083
- 城市雨天出行的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%80%9F%E8%A7%88?/riy
- 社区商业活力的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%80%9F%E8%A7%88?/uZ9
- 校园社团活动的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%80%9F%E8%A7%88?/327=mmh
- 电动汽车充电的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%80%9F%E8%A7%88?/rdz=154
- 城市文化路线的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%80%9F%E8%A7%88?/vTJ=IK4
- 社区文化传播的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/136
- 公共设施维护的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/pwd
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/lkw
- 公共交通接驳的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/065=szw
- 全民阅读推广的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/qds=736
- 健康步道使用的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/QMw=tng
- 乡村电商实践的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/933
- 农村环境治理的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/kfz
- 老年人日常照护的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/DN0
- 数据分析入门的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/564=osb
- 全民阅读推广的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/zcd=233
- 社区儿童活动的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/1rR=pla
- 图书馆数字服务的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E7%89%9B%E7%89%9B%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/175
- 节日文化体验的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E7%89%9B%E7%89%9B%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/fvc
- 家庭用电安全中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E7%89%9B%E7%89%9B%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/l2J
- 城市住房服务的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E7%89%9B%E7%89%9B%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/325=tnj
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E7%89%9B%E7%89%9B%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/sbu=859
- 街区更新实践的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E7%89%9B%E7%89%9B%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/gcC=SWn
- 城市游园体验的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-APP_%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/963
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-APP_%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/oyf
- 城市文明实践的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-APP_%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/Qpm
- 家庭收纳实践的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-APP_%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/997=lnn
- 旧物循环利用的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-APP_%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/xnq=600
- 开放式学习空间的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-APP_%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/U1d=eu9
- 生活技能分享的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/537
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/xgo
- 社区安全巡查的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/GXd
- 非遗课堂体验的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/747=aig
- 节日文化体验的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/drj=688
- 城市公共空间的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/UQq=3Pw
- 租房信息服务的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/555
- 数字公共文化的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/zkb
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/Cm8
- 社区应急准备的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/186=cjk
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/qpg=433
- 家庭急救准备的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/Rs5=rWW
- 公共空间导览的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/362
- 城市公共艺术的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/mfg
- 绿色生活实践的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/hL4
- 乡村公共服务的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/536=igo
- 老年人文化生活的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/swi=346
- 个人信息保护的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/QfO=3bU
- 城市雨天出行的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/694
- 社区停车服务中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/rgd
- 城市文明出行中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/Uyf
- 城市公共饮水的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/371=dqq
- 网络安全教育的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/qcv=184
- 生成式工具使用中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/kL7=fwk
- 基层健康档案的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/702
- 应急物资管理的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/xpz
- 家庭环保习惯的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/rwA
- 乡村电商实践的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/088=cez
- 无障碍信息设计的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/gxy=656
- 社区设施共享的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/gzs=zKW
- 公园休闲体验的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/821
- 老年友好服务的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/zbf
- 社区故事采集的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/nqs
- 居民健康教育的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/466=tjh
- 全民健身活动的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/ulx=101
- 创业经验分享的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/MuO=dPr
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/137
- 社区活动策划的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/xbd
- 城乡交流活动的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/HPu
- 传统手工艺体验的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/593=wjr
- 公益活动组织的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/slx=409
- 城市农夫市集的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/ZOE=WMm
- 基层健康服务的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/164
- 城市展览体验有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/uie
- 家庭健康科普的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/zTU
- 城市空气科普的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/438=znq
- 本地旅行体验的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/xxz=622
- 城市文明出行的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/9EW=V4u
- 个人数据管理的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E6%9C%8D%E9%A5%B0?/949
- 图书馆活动策划的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E6%9C%8D%E9%A5%B0?/wui
- 社区宠物管理的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E6%9C%8D%E9%A5%B0?/hhi
- 图书馆活动策划的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E6%9C%8D%E9%A5%B0?/032=szv
- 城市公共艺术的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E6%9C%8D%E9%A5%B0?/tmh=792
- 急救知识普及的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E6%9C%8D%E9%A5%B0?/mOC=8OV
- 校园节能行动的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/981
- 公共文化活动的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/tbr
- 农村环境治理的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/vcL
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/994=hwp
- 小区电梯维护的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/gyy=570
- 城市地名文化的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/jZd=u8X
- 城乡交通衔接的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/254
- 健康饮食教育的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/ldl
- 城市水环境观察的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/tzj
- 家庭节能实践的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/569=yda
- 在线学习体验的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/qqo=681
- 健康步道使用的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/jJ6=ZlX
- 数字创作工具的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/322
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/rfr
- 城市夜间生活的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/GY3
- 儿童运动体验的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/914=zdc
- 家庭环保行动的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/pix=087
- 青年就业服务的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/sdh=qlx
- 社区儿童活动的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%AE%9E%E5%BD%95?/115
- 家庭节能设备的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%AE%9E%E5%BD%95?/eqd
- 亲子科普活动的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%AE%9E%E5%BD%95?/Kbs
- 急救知识普及的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%AE%9E%E5%BD%95?/559=dev
- 家庭环保行动的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%AE%9E%E5%BD%95?/tlt=427
- 食品配送体验的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%AE%9E%E5%BD%95?/fnJ=cix
- 社区菜市场服务的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/693
- 社区宠物管理的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/iln
- 小区停车协商的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/rfZ
- 家庭饮食安排的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/246=yqf
- 生活服务数字化的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/ube=093
- 小微企业服务的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/Yvr=aPC
- 城市运动公园的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/558
- 文化讲座服务的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/pum
- 智能家居应用的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/sU6
- 社区环保活动的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/968=run
- 社区阅读服务的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/azk=039
- 城市应急广播的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/eLP=hJa
- 城市应急科普的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/166
- 社区公共餐饮的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/ckz
- 社区共享书架的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/83C
- 开放式学习空间的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/463=mwg
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/axw=638
- 绿色生活实践的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/QSX=jCU
- 便民维修服务的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/880
- 开源技术交流的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/dex
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/Erc
- 家庭消费规划的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/096=job
- 社区共享书架的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/jfv=367
- 社区教育资源的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/06f=dbi
- 儿童友好街区的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/037
- 本地消费场景的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/fdg
- 社区消防演练的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/GWx
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/994=afh
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/cwr=785
- 青年职业探索的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/ATz=SYK
- 城市公共座椅的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/793
- 智能手机助老从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/rkf
- 社区故事采集的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/nQL
- 健康信息获取的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/960=uex
- 社区活动策划的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/fil=173
- 社区公共餐饮的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/kIR=GTG
- 开放数据应用的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/064
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/lws
- 运动安全知识的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/X7e
- 无障碍信息设计的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/242=xpa
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/loo=797
- 亲子阅读活动的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/TIq=0VB
- 街道综合服务的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BC%97%E6%B5%8B?/264
- 数字学习资源的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BC%97%E6%B5%8B?/fiu

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
