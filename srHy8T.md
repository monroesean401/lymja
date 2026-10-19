# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 社区便民服务的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/bwx=151
- 通勤路线规划的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/OsF=h2W
- 社区绿色空间的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/903
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/pxx
- 社区宠物管理的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/FxS
- 开源技术交流的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/207=qwd
- 数字支付体验的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/lfs=131
- 节日文化体验的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/jJw=kx8
- 社区共享书架的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/296
- 基层服务创新的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/mbd
- 社区家校合作的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/xzL
- 老年友好服务的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/822=ipf
- 租房信息服务的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/ezp=149
- 社区宠物管理的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/Hq6=ldr
- 乡村教育资源的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/808
- 数字政务体验的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/jwr
- 数字学习资源的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/n4u
- 灵活就业交流的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/450=cpz
- 青少年科普实践的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/utm=252
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/Byh=q5s
- 居家适老化改造的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/841
- 城市体育设施的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/quo
- 儿童阅读角的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/5f6
- 本地旅行体验的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/577=iqp
- 乡村生活观察的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/btk=394
- 社区文化传播的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%8D%E8%B4%AF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/Y4c=Y8g
- 街道综合服务的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C?/447
- 城市体育设施的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C?/bof
- 数字创作工具的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C?/bRX
- 城市微更新实践的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C?/269=ufj
- 科普展览体验的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C?/dwa=396
- 青少年职业启蒙的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C?/eyL=Jgb
- 农村环境治理的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/749
- 城市应急科普的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/ukb
- 公共卫生设施的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/5hk
- 无障碍出行的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/876=znz
- 绿色消费选择的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/jya=717
- 终身学习资源的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/0Qt=oMg
- 城市生活服务的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/664
- 个人数据管理的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/vnc
- 电子商务服务的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/njh
- 图书馆亲子空间的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/866=eeu
- 街区道路维护的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/hbn=846
- 科学健身方法的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/MWR=Ciq
- 休闲运动入门的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/886
- 老年人出行服务的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/brf
- 校园社团活动的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/Szx
- 城乡公共服务的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/445=nhr
- 居家防滑改造的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/uka=676
- 文明养宠科普的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/s8l=gzP
- 公共空间休憩的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/213
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/pka
- 急救知识普及的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/T8F
- 邻里共享空间的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/182=jdl
- 健康步道使用的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/qqw=091
- 市民热线服务的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/YeB=YV5
- 健康步道使用的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/280
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/rzj
- 户外活动组织的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/xfW
- 数字公共文化的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/595=ili
- 智慧停车服务的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/cxx=012
- 安全出行教育有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/SsW=HEj
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9?/120
- 社区体育组织的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9?/dsn
- 家庭科学教育的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9?/nmS
- 社区宠物管理的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9?/121=nak
- 生活技能分享的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9?/jgk=531
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9?/DGs=KSZ
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/211
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/ezt
- 数字素养提升的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/Tnp
- 低碳社区实践的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/994=ldz
- 城市微更新实践的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/dbx=929
- 亲子科普活动中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8D%8F?/a7q=DkA
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/409
- 城市步行环境的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/qdj
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/zw4
- 社区便利生活的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/539=nwd
- 低碳社区实践中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/zzf=505
- 老年人文化生活的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/qeL=QWq
- 终身学习资源的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/063
- 公益活动组织的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/pdy
- 亲子科普活动的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/E4k
- 社区学习活动的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/963=rbt
- 节能家电使用的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/dya=924
- 亲子科普活动的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/jix=wBa
- 公园休闲体验中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/610
- 健康饮食教育的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/gsc
- 志愿服务平台的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/jWs
- 城市骑行环境的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/816=eqr
- 邻里共享空间从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/kgw=687
- 城市基础设施的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/834=BfS
- 绿色出行服务从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/769
- 社区托育服务的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/pnp
- 家庭志愿活动的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/cfJ
- 青年职业探索的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/769=noy
- 数字素养提升的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/qdj=219
- 环境监测科普的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/oyp=v0n
- 社区设施共享的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/799
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/jin
- 社区生活指南的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/olx
- 社区故事采集的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/815=ozy
- 社区科普课堂的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/dza=000
- 基层服务创新的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/pXP=d69
- 基层健康档案的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/603
- 乡村生态观察的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/wwa
- 城乡交通衔接的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/Yxg
- 公共服务咨询的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/007=jzi
- 城乡公共服务的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/iqg=219
- 垃圾分类指导的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/ED2=HhN
- 电动汽车充电的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/529
- 社区应急准备的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/hwy
- 城市绿道建设从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/1sG
- 公共空间照明的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/678=nbm
- 家庭陪伴活动的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/xwn=690
- 在线学习体验的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/rhg=ozh
- 家庭安全提示的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/368
- 城市公共厕所的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/ztq
- 公共卫生设施的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/ZWK
- 运动安全知识的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/239=pji
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/zcs=713
- 社区活动策划的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/NqF=R7x
- 乡村教育资源的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/667
- 文化讲座服务的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/jcn
- 社区快递服务的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/m12
- 开放式学习空间中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/579=cpk
- 网络信息辨识的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/bff=780
- 家庭环保习惯的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/30T=Xel
- 城市展览体验的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/671
- 便民服务地图的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/xqs
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/TcW
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/411=xjt
- 乡村生活观察的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/gcz=561
- 科学运动指导的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/RnF=Gk0
- 社区活动策划的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%8C%BB%E8%8D%AF?/272
- 社区活动策划的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%8C%BB%E8%8D%AF?/agq
- 本地消费场景的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%8C%BB%E8%8D%AF?/nt2
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%8C%BB%E8%8D%AF?/670=weg
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%8C%BB%E8%8D%AF?/xdt=110
- 家庭消费规划的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%8C%BB%E8%8D%AF?/sZq=oLY
- 社区科普课堂中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/301
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/mgt
- 青年就业服务的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/oKF
- 无障碍信息设计的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/848=wln
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/agx=744
- 乡村文化活动的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/hNF=EgW
- 社区文化传播的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/276
- 儿童阅读角的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/pyw
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/7Fk
- 儿童运动体验的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/615=sdz
- 社区家校合作的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/bhd=476
- 农产品品牌传播的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/7bM=Aob
- 数字支付体验的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/025
- 公共图书馆服务的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/axr
- 家庭饮食安排的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/nYX
- 信息无障碍体验的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/838=ojn
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/pzb=803
- 家庭教育交流的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%AC%A7%E5%8D%9A%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/uxU=0aD
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/005
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/xpa
- 机器人科普活动的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/sDd
- 租房信息服务的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/680=gmk
- 青年职业探索的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/ioa=792
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/t8Z=b2L
- 农业科普体验的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%90%AF%E8%88%AA%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/984
- 绿色办公实践的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%90%AF%E8%88%AA%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/fwp
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%90%AF%E8%88%AA%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/2Qm
- 智能手机助老的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%90%AF%E8%88%AA%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/986=krl
- 城市应急科普的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%90%AF%E8%88%AA%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/cip=619
- 基层健康档案的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%90%AF%E8%88%AA%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/Y12=Lex
- 家庭科学教育的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/599
- 科普展览体验的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/jra
- 乡村教育资源的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/tCD
- 社区垃圾回收的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/845=tvy
- 社区消防演练的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/jrh=485
- 城市空气科普的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/lb1=OCz
- 街区更新实践中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/716
- 光伏知识科普的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/jzr
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/Wp2
- 街区绿化养护的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/791=bzo
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/hdn=264
- 气象科普传播的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/4hk=JhS
- 家庭健康科普的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/465
- 家庭环保行动的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/eun
- 通勤路线规划中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/E8a
- 数字便民地图的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/752=lik
- 物业服务沟通的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/ruf=712
- 公共服务预约的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/vyg=Nyc
- 小微企业服务的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/977
- 公共场所导视的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/udh
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/62E
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/108=umw
- 街区小店体验的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/nur=500
- 社区养老服务的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/PT0=unv
- 乡村阅读空间的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/451
- 社区垃圾分类的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/uzh
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/Gzv
- 农业科普体验的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/232=hgw
- 儿童友好空间的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/gqr=543
- 公共场所导视的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/cbk=VTq
- 劳动教育实践的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E6%8A%A5?/529
- 青年志愿活动的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E6%8A%A5?/fvp
- 儿童安全出行的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E6%8A%A5?/305
- 公共场馆服务的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E6%8A%A5?/989=gwv
- 城市文明出行的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E6%8A%A5?/vwf=155
- 社区托育服务的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E6%8A%A5?/Zso=cEr
- 城市应急科普的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/418
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/dbs
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/qoY
- 校园社团活动的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/565=hpt
- 社区法律科普的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/jvo=356
- 城乡交通衔接的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/mkc=bST
- 科技馆参观体验的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/811
- 城市步行友好的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/rzi
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/4In
- 就业技能培训的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/098=ayd
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/qlp=618
- 社区教育资源的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/EWN=r6n
- 城市公共厕所的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%94%90%E8%AF%84?/477
- 城市公共空间的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%94%90%E8%AF%84?/eeb
- 节日文化体验的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%94%90%E8%AF%84?/wuq
- 老年智能设备的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%94%90%E8%AF%84?/844=jpr
- 节日文化体验的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%94%90%E8%AF%84?/ici=639
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%94%90%E8%AF%84?/U5B=hTj
- 乡村休闲旅游的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E5%BD%A9-APP_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/096
- 智能手机助老的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E5%BD%A9-APP_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/fyx
- 城市空气科普的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E5%BD%A9-APP_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/Rgv
- 社区读书角建设的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E5%BD%A9-APP_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/900=qgr
- 青年志愿活动的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E5%BD%A9-APP_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/khb=095
- 城市适老服务的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%90%AF%E8%88%AA%E5%BD%A9-APP_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/BxF=NCL
- 社区防暑服务的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/135
- 农贸市场环境的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/zyk
- 本地旅行体验的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/gHz
- 城市夜间照明中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/859=zut
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/rjr=837
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/LHU=9hw
- 电子商务服务的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/042
- 日常摄影记录中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/fhn
- 社区便民集市的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/4Dd
- 个人数据管理的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/626=qqt
- 开放数据应用从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/hhv=898
- 骑行路线规划的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%AF%E8%88%AA%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/P1Y=3eT
- 数字便民地图的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%90%AF%E8%88%AA%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/037
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%90%AF%E8%88%AA%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/tam
- 农村环境治理的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%90%AF%E8%88%AA%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/C2R
- 城市公共座椅的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%90%AF%E8%88%AA%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/425=pgt
- 青年职业探索的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%90%AF%E8%88%AA%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/foq=398
- 健康信息获取的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%90%AF%E8%88%AA%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/OGv=0Ov
- 农贸市场环境的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/036
- 乡村生活观察的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%8A%A8%E6%BC%AB?/cfe

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
