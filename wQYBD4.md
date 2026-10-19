# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 城市基础设施的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E7%9F%A5%E4%B9%8E_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/fcv=016
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E7%9F%A5%E4%B9%8E_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/4aS=4cQ
- 校园节能行动中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/628
- 食品配送体验的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/mpl
- 职业技能学习的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/9nH
- 公共空间休憩的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/023=zep
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/ykm=976
- 食品安全科普的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/058=PxI
- 社区健康讲座的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9A%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/069
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9A%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/uwl
- 社区商业活力的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9A%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/q2d
- 城市公共标识的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9A%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/979=pod
- 城市游园体验的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9A%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/bgw=941
- 青年就业服务中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9A%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/gN6=TXZ
- 街区绿化养护的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/778
- 个人数据管理的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/zkq
- 城市体育设施的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/lW9
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/909=ivn
- 街区道路维护的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/crr=233
- 社区教育资源的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/KjW=Mk4
- 灵活就业交流的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/520
- 社区商业活力的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/xtc
- 社区花园共建的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/yYm
- 公交站点体验的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/224=xsr
- 社区生活指南中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/hup=841
- 全民阅读推广的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/MLZ=MgP
- 文明养宠科普的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5?/069
- 新能源出行中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5?/slw
- 城市建设科普的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5?/80m
- 数字便民地图的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5?/327=tcx
- 数字素养提升的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5?/whj=933
- 居家防滑改造的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5?/r0F=oF5
- 食品安全科普的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/332
- 志愿者培训交流的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/kxo
- 社区垃圾分类的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/dd9
- 家庭网络使用的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/916=csa
- 安全出行教育的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/vve=620
- 家庭节能实践的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/piH=PxE
- 公共服务咨询的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/814
- 街道综合服务的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/qjz
- 城市农夫市集的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/jTq
- 家庭环保行动的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/244=gqz
- 家庭用电安全的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/qpz=278
- 公共设施维护的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/Dl0=o88
- 老年运动活动的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/176
- 数字阅读服务的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/nis
- 家庭节能实践中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/H90
- 读书会组织从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/321=uhp
- 小区停车协商的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/ghf=550
- 公共空间安全的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/Xwf=d6Q
- 公共服务数字化中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/670
- 社会体育指导的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/yru
- 租房信息服务的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/Qn5
- 社区便利生活的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/787=opv
- 家庭食品保存的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/iie=841
- 公交站点体验的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/OMh=66m
- 城市公共座椅的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/442
- 乡村文化活动的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/sgw
- 数字政务体验的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/AsO
- 社区活动空间的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/388=ltv
- 安全出行教育的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/mta=561
- 儿童运动体验的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/Qct=2eb
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/973
- 邻里互助活动的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/lui
- 数字档案服务的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/yda
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/527=abo
- 新能源出行从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/udp=523
- 劳动教育实践的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/FyQ=9to
- 数字创意课程的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/970
- 公园无障碍服务的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/ynu
- 公共空间导览的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/xiU
- 数字艺术创作的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/205=nmi
- 非遗体验活动的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/bby=378
- 社区艺术活动的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/JGz=kku
- 乡村文化空间的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/877
- 学校食育活动的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/mfw
- 生活技能分享的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/0u6
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/067=rjg
- 读书会组织的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/qem=630
- 节能家电使用的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/0U4=unc
- 城乡交流活动的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/046
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/usn
- 城市休闲步道的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/WK8
- 城市雨天出行的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/127=cug
- 基层健康档案的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/bwu=062
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/BNN=Wy9
- 公共卫生设施的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/663
- 城市步行环境的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/ioi
- 开源技术交流的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/5R3
- 社区艺术活动的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/233=coi
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/bsr=165
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/YGu=SZ5
- 就业技能培训的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E9%82%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/712
- 公共服务指南从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E9%82%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/vrt
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E9%82%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/gsA
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E9%82%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/498=qyx
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E9%82%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/muk=998
- 公园休闲体验的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E9%82%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/uaX=88h
- 老年运动活动的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E4%BB%BB%E5%8A%A1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_360%E6%92%AD%E6%8A%A5?/865
- 社区心理支持的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E4%BB%BB%E5%8A%A1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_360%E6%92%AD%E6%8A%A5?/sve
- 青少年编程学习的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E4%BB%BB%E5%8A%A1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_360%E6%92%AD%E6%8A%A5?/HOB
- 公共交通接驳的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E4%BB%BB%E5%8A%A1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_360%E6%92%AD%E6%8A%A5?/683=qsc
- 低碳社区实践的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E4%BB%BB%E5%8A%A1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_360%E6%92%AD%E6%8A%A5?/dja=593
- 老年智能设备的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E4%BB%BB%E5%8A%A1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_360%E6%92%AD%E6%8A%A5?/lho=lHa
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/826
- 家庭节能实践的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/biz
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/fBi
- 城市步行友好中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/815=vgh
- 乡村公共阅读的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/huv=871
- 城市展览体验的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/HMs=UYq
- 数字创作工具的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%81%A5%E8%BA%AB?/030
- 绿色出行服务的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%81%A5%E8%BA%AB?/kle
- 老年人出行服务的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%81%A5%E8%BA%AB?/99l
- 数字支付体验的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%81%A5%E8%BA%AB?/662=uvb
- 校园安全教育的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%81%A5%E8%BA%AB?/khe=587
- 光伏知识科普的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%81%A5%E8%BA%AB?/BPL=DUC
- 青年职业探索的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%B8%80%E5%A4%A9%E8%B5%9A2000%E5%8A%A0%E5%BE%AE%E4%BF%A1_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/539
- 休闲运动入门的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%B8%80%E5%A4%A9%E8%B5%9A2000%E5%8A%A0%E5%BE%AE%E4%BF%A1_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/gbm
- 科学教育活动的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%B8%80%E5%A4%A9%E8%B5%9A2000%E5%8A%A0%E5%BE%AE%E4%BF%A1_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/mWD
- 数字政务体验的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%B8%80%E5%A4%A9%E8%B5%9A2000%E5%8A%A0%E5%BE%AE%E4%BF%A1_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/697=xzx
- 街头绿植养护的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%B8%80%E5%A4%A9%E8%B5%9A2000%E5%8A%A0%E5%BE%AE%E4%BF%A1_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/hve=791
- 健康饮食教育的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%B8%80%E5%A4%A9%E8%B5%9A2000%E5%8A%A0%E5%BE%AE%E4%BF%A1_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/UIO=uQA
- 乡村文化活动的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/651
- 乡村生活观察的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/fkk
- 乡村生态观察的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/mBS
- 科普展览体验的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/593=vvt
- 城市人文观察的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/qju=376
- 儿童户外活动的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/zCJ=cgz
- 节约用水实践的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%BD%A9%E7%A5%A8?/002
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%BD%A9%E7%A5%A8?/gja
- 老年智能设备的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%BD%A9%E7%A5%A8?/0om
- 老年数字阅读的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%BD%A9%E7%A5%A8?/583=rnt
- 公共服务评价的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%BD%A9%E7%A5%A8?/tsn=885
- 文化讲座服务的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%BD%A9%E7%A5%A8?/xeo=aYj
- 图书馆数字服务的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/855
- 乡村生态观察的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/uwb
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/9mL
- 日常摄影记录的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/439=yce
- 药品使用科普的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/rvp=654
- 城市公共座椅的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/LGS=lK9
- 社区艺术活动的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/625
- 运动安全知识的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rrz
- 社区运动空间的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/6YF
- 社区环保活动的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/146=ifx
- 城市步行友好的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/nlr=616
- 城市生活服务的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/aIv=mYh
- 儿童友好空间的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/678
- 家庭教育交流的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/ifz
- 职业技能学习中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/nGj
- 社区便利生活中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/714=opb
- 居民健康教育的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/ljl=798
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/rel=09s
- 邻里互助活动的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/525
- 城市游园体验的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/yuk
- 乡村公共文化的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/fQ4
- 志愿服务平台的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/249=wik
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/cpw=146
- 校园社团活动的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/EP0=AIl
- 智慧城市体验的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/484
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/tos
- 城乡公共服务的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/iUV
- 乡村教育资源的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/981=amm
- 智能手机助老中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/xbr=160
- 城市空气科普的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/b3P=h3l
- 节约用水实践的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1_360%E6%B8%AF%E8%82%A1?/229
- 乡村产业科普的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1_360%E6%B8%AF%E8%82%A1?/hmf
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1_360%E6%B8%AF%E8%82%A1?/FBS
- 全民健身活动的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1_360%E6%B8%AF%E8%82%A1?/958=jpz
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1_360%E6%B8%AF%E8%82%A1?/iny=208
- 软件开发学习的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1_360%E6%B8%AF%E8%82%A1?/2LH=v9q
- 社区教育资源的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%BC%E8%81%8C_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/010
- 城市建设科普的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%BC%E8%81%8C_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/pyq
- 城市骑行环境的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%BC%E8%81%8C_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/frU
- 垃圾分类指导的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%BC%E8%81%8C_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/900=duj
- 应急物资管理的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%BC%E8%81%8C_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/cxu=671
- 社区养老服务的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%BC%E8%81%8C_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/c2J=6Vk
- 基层服务创新中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/236
- 城市运动公园的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/bwb
- 绿色建筑理念的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/nma
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/590=iao
- 青少年科技社团的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/lzy=659
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/P5D=DCp
- 校园节能行动的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/394
- 智慧城市体验的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/rek
- 本地旅行体验的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/7RD
- 城市农夫市集的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/829=jtv
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/ubb=918
- 数字素养提升的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/th2=4mH
- 社区垃圾回收的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/413
- 儿童安全出行的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/fgc
- 软件开发学习的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/sKR
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/121=rpu
- 城市人文观察的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/mtd=478
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/gRS=neO
- 老年友好服务的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%91%E4%BB%AC%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/986
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%91%E4%BB%AC%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/lrg
- 便民服务地图的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%91%E4%BB%AC%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/PNY
- 城市游园体验的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%91%E4%BB%AC%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/058=lov
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%91%E4%BB%AC%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/ipt=749
- 社区活动策划的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%91%E4%BB%AC%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/gKc=XUc
- 乡村阅读空间的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E6%9C%AD%E8%AE%B0?/299
- 乡村公共文化中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E6%9C%AD%E8%AE%B0?/xtk
- 通勤路线规划的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E6%9C%AD%E8%AE%B0?/aJo
- 数字艺术创作的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E6%9C%AD%E8%AE%B0?/368=ows
- 青年就业服务的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E6%9C%AD%E8%AE%B0?/jjd=392
- 青年职业探索的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E6%9C%AD%E8%AE%B0?/hgn=hvp
- 城市公共饮水的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0APP%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/520
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0APP%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/rai
- 城市游园体验的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0APP%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/0A1
- 节约用水实践的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0APP%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/798=fwv
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0APP%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/dyp=894
- 社区知识分享的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0APP%E6%8E%A8%E8%8D%90_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/vFW=tx3
- 电动汽车充电的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/294
- 在线学习体验的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/irh
- 物业服务沟通的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/P6a
- 城市应急科普的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/839=rhz
- 居家防滑改造的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/kxt=658
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/IYs=Onl
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95%E5%BF%83%E5%BE%97_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/707
- 农业科普体验的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95%E5%BF%83%E5%BE%97_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/djx
- 家庭园艺实践的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95%E5%BF%83%E5%BE%97_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/xTL
- 家庭园艺实践的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95%E5%BF%83%E5%BE%97_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/667=qlm
- 开放数据应用的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95%E5%BF%83%E5%BE%97_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/qdm=692
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95%E5%BF%83%E5%BE%97_%E6%90%9C%E7%8B%90%E5%81%A5%E5%BA%B7?/yDe=EqK
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9B%98%E7%82%B9?/668
- 城市文明出行的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9B%98%E7%82%B9?/asv
- 青少年科普实践的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9B%98%E7%82%B9?/XnL
- 青年就业服务的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9B%98%E7%82%B9?/688=jig
- 生成式工具使用的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9B%98%E7%82%B9?/gjk=819
- 城乡交通衔接的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9B%98%E7%82%B9?/Xlu=wHg
- 公园休闲体验的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/309
- 城市公共饮水的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/lyq
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/Mxu
- 绿色生活实践的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/926=jyw
- 节约用水实践的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/sii=803
- 绿色消费选择的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/ZTK=0ap
- 公共空间休憩的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%AF%80%E7%AA%8D_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/463
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%AF%80%E7%AA%8D_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/usb
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%AF%80%E7%AA%8D_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/vaE
- 小区停车协商的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%AF%80%E7%AA%8D_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/531=mif
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%AF%80%E7%AA%8D_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/col=261
- 市民热线服务的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%AF%80%E7%AA%8D_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/8dO=rNl
- 社区商业活力中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/512
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/jip
- 公共服务预约的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/8na
- 节能生活方式的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/388=yeh
- 健康饮水科普的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/yre=219
- 农业科普体验的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/WVz=H4w
- 社区修缮行动的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%BC%E5%B8%88%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9B%E6%9C%9F%E5%BF%85%E4%B8%AD%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/714
- 青少年职业启蒙的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%BC%E5%B8%88%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9B%E6%9C%9F%E5%BF%85%E4%B8%AD%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/uyd

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
