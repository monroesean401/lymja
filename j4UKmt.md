# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 科学观察活动的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/dEu
- 社区学习活动的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/460=xra
- 物业服务沟通的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/jvp=940
- 亲子科普活动的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/Pan=TWo
- 城市公共标识的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/032
- 信息无障碍体验的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/stv
- 数字课堂应用的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/4xR
- 垃圾分类指导中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/454=fer
- 在线教育体验的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/sky=068
- 家庭运动计划的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/DgC=Oin
- 应急物资管理的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/075
- 个人数据管理的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/oho
- 家庭阅读计划的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/Wyz
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/162=try
- 图书馆数字服务有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/lmm=355
- 老年人文化生活的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/RH9=vIg
- 老年学习活动的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/967
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/rho
- 全民健身活动从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/Khw
- 社区休闲设施的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/791=xpv
- 社区交通安全的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/wgh=936
- 公交站点体验的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/wTf=hxj
- 旧物循环利用中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9F_%E8%8A%92%E6%9E%9C%E4%BA%B2%E5%AD%90?/171
- 居民健康教育的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9F_%E8%8A%92%E6%9E%9C%E4%BA%B2%E5%AD%90?/isr
- 家庭网络使用的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9F_%E8%8A%92%E6%9E%9C%E4%BA%B2%E5%AD%90?/V2p
- 新能源知识普及的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9F_%E8%8A%92%E6%9E%9C%E4%BA%B2%E5%AD%90?/818=cxe
- 农业科普体验的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9F_%E8%8A%92%E6%9E%9C%E4%BA%B2%E5%AD%90?/qdq=976
- 消防知识宣传的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9F_%E8%8A%92%E6%9E%9C%E4%BA%B2%E5%AD%90?/sUZ=6Xq
- 数字档案服务的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%A8%B39%E7%A0%81_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/091
- 数字创意课程的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%A8%B39%E7%A0%81_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/nqd
- 学校体育活动的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%A8%B39%E7%A0%81_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/V95
- 科学教育活动的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%A8%B39%E7%A0%81_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/101=stj
- 在线学习体验的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%A8%B39%E7%A0%81_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/fnt=756
- 乡村教育资源有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%A8%B39%E7%A0%81_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/GdS=UJn
- 小区公共照明的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/776
- 乡村文化活动的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/djd
- 农业科普体验的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/d8P
- 电子商务服务的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/688=sqy
- 城市骑行环境的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/zsd=470
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/bDu=ur6
- 城市宠物友好空间的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/944
- 校园节能行动的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/hfn
- 家庭饮食安排的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/YT1
- 城市公共饮水的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/049=zgh
- 家庭运动计划的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/kkh=423
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/Wag=zUk
- 乡村文化活动的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC341819%E6%BC%8F%E6%B4%9E_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/211
- 老年人日常照护的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC341819%E6%BC%8F%E6%B4%9E_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/xpv
- 信息无障碍体验的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC341819%E6%BC%8F%E6%B4%9E_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/s2n
- 城市可持续生活的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC341819%E6%BC%8F%E6%B4%9E_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/902=jsa
- 传统节日科普的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC341819%E6%BC%8F%E6%B4%9E_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/ppz=253
- 家庭饮食安排的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC341819%E6%BC%8F%E6%B4%9E_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/aP9=nhu
- 社区科普课堂的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/057
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/kwa
- 农贸市场环境的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/xBJ
- 地方民俗记录中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/795=enc
- 家庭环保行动的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/ycb=753
- 绿色生活实践的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/AkU=aq4
- 社区体育组织的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/018
- 绿色办公实践的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/lgj
- 社区交通安全的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/sRJ
- 开源技术交流的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/083=rks
- 社区垃圾回收的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/mqj=038
- 乡村生活观察的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/tDc=AEO
- 校园阅读活动的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC341819%E7%9A%84%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/455
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC341819%E7%9A%84%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/ebb
- 城市基础设施的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC341819%E7%9A%84%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/XWF
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC341819%E7%9A%84%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/948=lzz
- 劳动教育实践的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC341819%E7%9A%84%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/skd=636
- 城市雨天出行的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC341819%E7%9A%84%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/1oP=hR3
- 社区公共议事的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%92%8C%E5%A5%97%E5%88%A9%E6%96%B9%E6%A1%88_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/333
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%92%8C%E5%A5%97%E5%88%A9%E6%96%B9%E6%A1%88_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/sot
- 社区家校合作的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%92%8C%E5%A5%97%E5%88%A9%E6%96%B9%E6%A1%88_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/GOt
- 旧物循环利用的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%92%8C%E5%A5%97%E5%88%A9%E6%96%B9%E6%A1%88_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/199=ybb
- 街区更新实践的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%92%8C%E5%A5%97%E5%88%A9%E6%96%B9%E6%A1%88_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/xtl=396
- 城市步行环境的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%92%8C%E5%A5%97%E5%88%A9%E6%96%B9%E6%A1%88_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/aMk=oiF
- 老年人日常照护的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%85%A8%E5%8C%85%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/265
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%85%A8%E5%8C%85%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/agj
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%85%A8%E5%8C%85%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/bh4
- 数字生活课堂的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%85%A8%E5%8C%85%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/191=vnd
- 城市公共艺术的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%85%A8%E5%8C%85%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/stc=904
- 城乡公共服务的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%85%A8%E5%8C%85%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/rqz=TvZ
- 无障碍出行的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C2.2%E5%AF%B9%E5%88%B71.79_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/850
- 文化场馆预约的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C2.2%E5%AF%B9%E5%88%B71.79_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/opj
- 青少年科普实践的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C2.2%E5%AF%B9%E5%88%B71.79_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/GJT
- 数字档案服务的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C2.2%E5%AF%B9%E5%88%B71.79_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/212=bbi
- 家庭饮食安排的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C2.2%E5%AF%B9%E5%88%B71.79_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/oek=462
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C2.2%E5%AF%B9%E5%88%B71.79_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/Jul=15X
- 数字创意课程的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E4%B8%8E%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8%E5%9B%BE_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/424
- 数字艺术创作的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E4%B8%8E%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8%E5%9B%BE_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/idb
- 老旧小区改造的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E4%B8%8E%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8%E5%9B%BE_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/NxR
- 公共交通信息服务的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E4%B8%8E%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8%E5%9B%BE_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/341=aef
- 绿色校园实践的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E4%B8%8E%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8%E5%9B%BE_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/uts=107
- 生活技能分享的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E4%B8%8E%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8%E5%9B%BE_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/22t=KSC
- 城市公共座椅的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_pk10%E7%8E%A9%E6%B3%95%E7%BB%9D%E6%8B%9B_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/763
- 城市空气科普的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_pk10%E7%8E%A9%E6%B3%95%E7%BB%9D%E6%8B%9B_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/igf
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_pk10%E7%8E%A9%E6%B3%95%E7%BB%9D%E6%8B%9B_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/dpg
- 城市文明实践的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_pk10%E7%8E%A9%E6%B3%95%E7%BB%9D%E6%8B%9B_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/301=fmp
- 数字资源检索的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_pk10%E7%8E%A9%E6%B3%95%E7%BB%9D%E6%8B%9B_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/cll=634
- 城乡公共服务中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_pk10%E7%8E%A9%E6%B3%95%E7%BB%9D%E6%8B%9B_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/l1F=ELr
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/947
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/jjg
- 公共服务评价的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/cW6
- 数字艺术创作的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/338=rxc
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/ahy=607
- 亲子阅读活动的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/iOd=VVB
- 家庭网络使用的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%86%A0%E4%BA%9A11%E6%BC%8F%E6%B4%9E%E8%AF%A6%E7%BB%86%E8%A7%A3%E6%9E%90_36%E6%B0%AA?/105
- 科普展览体验的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%86%A0%E4%BA%9A11%E6%BC%8F%E6%B4%9E%E8%AF%A6%E7%BB%86%E8%A7%A3%E6%9E%90_36%E6%B0%AA?/szk
- 家庭园艺实践的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%86%A0%E4%BA%9A11%E6%BC%8F%E6%B4%9E%E8%AF%A6%E7%BB%86%E8%A7%A3%E6%9E%90_36%E6%B0%AA?/t9e
- 健康饮食教育有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%86%A0%E4%BA%9A11%E6%BC%8F%E6%B4%9E%E8%AF%A6%E7%BB%86%E8%A7%A3%E6%9E%90_36%E6%B0%AA?/395=sgs
- 数字学习资源的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%86%A0%E4%BA%9A11%E6%BC%8F%E6%B4%9E%E8%AF%A6%E7%BB%86%E8%A7%A3%E6%9E%90_36%E6%B0%AA?/awv=891
- 数字设备回收的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%86%A0%E4%BA%9A11%E6%BC%8F%E6%B4%9E%E8%AF%A6%E7%BB%86%E8%A7%A3%E6%9E%90_36%E6%B0%AA?/3p9=B0A
- 社区体育组织的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%83%E7%A0%81%E4%B8%80%E6%9C%9F%E5%B9%B3%E5%88%B7%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/637
- 公共空间照明的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%83%E7%A0%81%E4%B8%80%E6%9C%9F%E5%B9%B3%E5%88%B7%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/muq
- 课后服务体验的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%83%E7%A0%81%E4%B8%80%E6%9C%9F%E5%B9%B3%E5%88%B7%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/RZs
- 老年人出行服务的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%83%E7%A0%81%E4%B8%80%E6%9C%9F%E5%B9%B3%E5%88%B7%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/339=dvr
- 校园社团活动的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%83%E7%A0%81%E4%B8%80%E6%9C%9F%E5%B9%B3%E5%88%B7%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/ljl=347
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%83%E7%A0%81%E4%B8%80%E6%9C%9F%E5%B9%B3%E5%88%B7%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/a3s=A0J
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%86%A0%E4%BA%9A%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/315
- 公园休闲体验的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%86%A0%E4%BA%9A%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/cgg
- 青少年心理健康的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%86%A0%E4%BA%9A%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/L4C
- 数字素养提升的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%86%A0%E4%BA%9A%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/597=inz
- 城市夜间照明的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%86%A0%E4%BA%9A%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/tlc=488
- 数据分析入门中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%86%A0%E4%BA%9A%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/VhU=nQm
- 乡村公共阅读的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/318
- 家庭阅读计划的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/vtj
- 儿童阅读角的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/ZE7
- 远程协作工具的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/639=qeg
- 食品安全科普的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/ybf=673
- 社区花园共建的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/ZMD=Xd6
- 城市公共厕所中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E8%AE%A1%E7%AE%97%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC_36%E6%B0%AA%E9%80%9F%E8%A7%88?/621
- 本地消费场景的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E8%AE%A1%E7%AE%97%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC_36%E6%B0%AA%E9%80%9F%E8%A7%88?/bgj
- 城市游园体验的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E8%AE%A1%E7%AE%97%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC_36%E6%B0%AA%E9%80%9F%E8%A7%88?/QQq
- 智能手机助老的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E8%AE%A1%E7%AE%97%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC_36%E6%B0%AA%E9%80%9F%E8%A7%88?/092=mic
- 城市博物馆服务的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E8%AE%A1%E7%AE%97%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC_36%E6%B0%AA%E9%80%9F%E8%A7%88?/yps=884
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E8%AE%A1%E7%AE%97%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC_36%E6%B0%AA%E9%80%9F%E8%A7%88?/lN8=8ic
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%91%84%E5%BD%B1?/827
- 个人数据管理的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%91%84%E5%BD%B1?/dyu
- 公交无障碍服务的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%91%84%E5%BD%B1?/GSE
- 城市雨天出行的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%91%84%E5%BD%B1?/123=lsy
- 社区家政服务的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%91%84%E5%BD%B1?/bxa=797
- 公交无障碍服务的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%91%84%E5%BD%B1?/f4d=JNp
- 骑行路线规划的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%B0%8F%E5%A5%97%E5%88%A9_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/711
- 社区家政服务的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%B0%8F%E5%A5%97%E5%88%A9_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/vkk
- 街区道路维护的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%B0%8F%E5%A5%97%E5%88%A9_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/pc3
- 社区儿童活动的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%B0%8F%E5%A5%97%E5%88%A9_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/966=tqe
- 社区生活指南的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%B0%8F%E5%A5%97%E5%88%A9_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/cgw=573
- 乡村教育资源的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%B0%8F%E5%A5%97%E5%88%A9_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/Vb7=TtE
- 社区邻里服务的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/379
- 公共空间照明的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/lly
- 开源技术交流的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/sDZ
- 社区商业活力的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/965=vjb
- 家庭用电安全的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/ruq=118
- 机器人科普活动有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/v3u=PHC
- 公共空间导览的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A9pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/319
- 家庭阅读计划的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A9pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/nbd
- 农贸市场环境的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A9pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/xpE
- 劳动教育实践的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A9pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/814=ovs
- 社区交通安全的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A9pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/bms=282
- 农村环境治理的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A9pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/aEE=nIw
- 家庭饮食安排的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/018
- 公共空间休憩的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/tmo
- 社区公共议事的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/ZCa
- 公共文化活动的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/802=ufk
- 青年志愿活动的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/zvz=349
- 网络安全教育的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/yP3=Xnr
- 青年志愿活动的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E5%AF%B9%E5%88%B7%E6%80%8E%E4%B9%88%E6%8A%95%E6%B3%A8_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/223
- 公共服务咨询的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E5%AF%B9%E5%88%B7%E6%80%8E%E4%B9%88%E6%8A%95%E6%B3%A8_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/bhb
- 社区防暑服务的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E5%AF%B9%E5%88%B7%E6%80%8E%E4%B9%88%E6%8A%95%E6%B3%A8_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/qaH
- 公园无障碍服务的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E5%AF%B9%E5%88%B7%E6%80%8E%E4%B9%88%E6%8A%95%E6%B3%A8_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/006=orw
- 社区托育服务的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E5%AF%B9%E5%88%B7%E6%80%8E%E4%B9%88%E6%8A%95%E6%B3%A8_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/wac=207
- 青年就业服务的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E5%AF%B9%E5%88%B7%E6%80%8E%E4%B9%88%E6%8A%95%E6%B3%A8_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/C1I=jBf
- 乡村文化空间的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%A4%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%B9%E6%89%93%E5%A5%97%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/484
- 科学健身方法的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%A4%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%B9%E6%89%93%E5%A5%97%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/yav
- 公共场所导视的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%A4%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%B9%E6%89%93%E5%A5%97%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/HQv
- 城市文明出行的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%A4%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%B9%E6%89%93%E5%A5%97%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/319=oug
- 科学健身方法的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%A4%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%B9%E6%89%93%E5%A5%97%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/rpg=284
- 地方旅游导览的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%A4%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%B9%E6%89%93%E5%A5%97%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/LCw=v2U
- 绿色校园实践的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%99%8E%E6%80%8E%E4%B9%88%E4%B8%8B%E8%B5%A2%E6%A6%82%E7%8E%87%E5%A4%A7_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/843
- 家庭环保行动的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%99%8E%E6%80%8E%E4%B9%88%E4%B8%8B%E8%B5%A2%E6%A6%82%E7%8E%87%E5%A4%A7_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/qej
- 电子商务服务的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%99%8E%E6%80%8E%E4%B9%88%E4%B8%8B%E8%B5%A2%E6%A6%82%E7%8E%87%E5%A4%A7_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/al9
- 生活技能分享的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%99%8E%E6%80%8E%E4%B9%88%E4%B8%8B%E8%B5%A2%E6%A6%82%E7%8E%87%E5%A4%A7_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/241=hoz
- 公共空间照明的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%99%8E%E6%80%8E%E4%B9%88%E4%B8%8B%E8%B5%A2%E6%A6%82%E7%8E%87%E5%A4%A7_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/yvd=400
- 乡村文化空间的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%99%8E%E6%80%8E%E4%B9%88%E4%B8%8B%E8%B5%A2%E6%A6%82%E7%8E%87%E5%A4%A7_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/AqV=EVi
- 数字资源检索的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E6%B3%95_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/694
- 口袋公园建设中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E6%B3%95_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/lez
- 线上办事服务中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E6%B3%95_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/5nF
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E6%B3%95_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/972=nhh
- 城市文化路线的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E6%B3%95_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/hbi=561
- 城市文化路线的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E6%B3%95_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/Xkc=5VG
- 图书借阅体验的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%8E%A9_360%E5%91%A8%E6%8A%A5?/152
- 老年数字阅读的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%8E%A9_360%E5%91%A8%E6%8A%A5?/ybw
- 智能手机助老的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%8E%A9_360%E5%91%A8%E6%8A%A5?/YbE
- 公交站点体验的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%8E%A9_360%E5%91%A8%E6%8A%A5?/072=qel
- 社区家校合作的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%8E%A9_360%E5%91%A8%E6%8A%A5?/tcz=607
- 青少年科普实践的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%8E%A9_360%E5%91%A8%E6%8A%A5?/hLI=pya
- 校园节能行动的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%8A%80%E5%B7%A7_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/076
- 周末休闲规划的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%8A%80%E5%B7%A7_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/osd
- 乡村生态观察中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%8A%80%E5%B7%A7_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wfR
- 电子商务服务的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%8A%80%E5%B7%A7_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/311=fxo
- 农贸市场环境的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%8A%80%E5%B7%A7_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/sfl=710
- 社区交通安全的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%8A%80%E5%B7%A7_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Clx=6Qk
- 健康饮食教育的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E4%BB%A5%E4%B8%8A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8D%9A%E5%AE%A2?/568
- 数字公共文化的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E4%BB%A5%E4%B8%8A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8D%9A%E5%AE%A2?/liw
- 地方民俗记录的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E4%BB%A5%E4%B8%8A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8D%9A%E5%AE%A2?/5P5
- 城市社区治理的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E4%BB%A5%E4%B8%8A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8D%9A%E5%AE%A2?/115=cst
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E4%BB%A5%E4%B8%8A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8D%9A%E5%AE%A2?/ojn=148
- 公共空间安全的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E4%BB%A5%E4%B8%8A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8D%9A%E5%AE%A2?/W2G=bdF
- 数字生活课堂的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/384
- 城市夜间照明的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/ema
- 开放数据应用的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/tNf
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/644=tvo
- 小区停车协商的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/laa=123
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/VJ4=J73
- 农业科普体验的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/882
- 老年数字阅读的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/hlo
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/zrz
- 城市便民驿站的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/150=mog
- 儿童阅读角的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/jda=640
- 城市文明出行的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/Smh=qFu
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/194
- 城市空气科普的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/tie
- 校园阅读活动的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/w2h
- 社区体育组织的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/147=itg
- 社区故事采集的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/lyh=304
- 生成式工具使用的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/NGX=TFD
- 机器人科普活动的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B__%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/270
- 社区修缮行动的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B__%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/lcn
- 线上阅读资源的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B__%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/hnU
- 在线学习体验的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B__%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/542=zpi
- 社区绿色空间的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B__%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/dcx=525
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B__%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/Vl8=z6E
- 运动安全知识的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%89%E5%87%A0%E7%A7%8D%E7%BB%84%E5%90%88_%E7%BD%91%E6%98%93%E6%AF%8D%E5%A9%B4?/646
- 城市微更新实践的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%89%E5%87%A0%E7%A7%8D%E7%BB%84%E5%90%88_%E7%BD%91%E6%98%93%E6%AF%8D%E5%A9%B4?/wfb
- 环境监测科普从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%89%E5%87%A0%E7%A7%8D%E7%BB%84%E5%90%88_%E7%BD%91%E6%98%93%E6%AF%8D%E5%A9%B4?/577
- 社区快递服务中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%89%E5%87%A0%E7%A7%8D%E7%BB%84%E5%90%88_%E7%BD%91%E6%98%93%E6%AF%8D%E5%A9%B4?/750=lim
- 数字支付体验的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%89%E5%87%A0%E7%A7%8D%E7%BB%84%E5%90%88_%E7%BD%91%E6%98%93%E6%AF%8D%E5%A9%B4?/lmq=072
- 城市树木认养的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%89%E5%87%A0%E7%A7%8D%E7%BB%84%E5%90%88_%E7%BD%91%E6%98%93%E6%AF%8D%E5%A9%B4?/zKI=jsT
- 城乡公共服务的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%9C%BA%E7%90%86_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/809
- 物业服务沟通的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%9C%BA%E7%90%86_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/lyj
- 城市文明实践的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%9C%BA%E7%90%86_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/NQo
- 城乡交流活动的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%9C%BA%E7%90%86_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/049=prs
- 城市应急科普的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%9C%BA%E7%90%86_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/ngc=603
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%9C%BA%E7%90%86_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/2ir=7tE
- 家庭健康管理的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%97%B6%E9%97%B4%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/902
- 城市农夫市集的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%97%B6%E9%97%B4%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/obl
- 城市公共自行车的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%97%B6%E9%97%B4%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/2vw
- 食品配送体验的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%97%B6%E9%97%B4%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/005=qvr
- 便民信息查询中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%97%B6%E9%97%B4%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/pkq=495
- 家庭网络使用的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%97%B6%E9%97%B4%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/DJR=EhA

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
