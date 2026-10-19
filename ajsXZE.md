# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 智能家居应用的服务细节记录 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/sUh
- 地方文化传播的便利性观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/992=jdv
- 城市公共自行车的服务体验观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/nkw=731
- 生活垃圾回收的社区行动案例 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/FTb=PuS
- 城乡交流活动的常见误区提醒 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/055
- 青少年科普实践的服务质量观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/ceb
- 电动汽车充电的基础知识问答 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/tSW
- 城市游园体验的服务质量观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/364=vsf
- 数字公共文化的社区行动案例 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/vms=530
- 便民维修服务的组织方法与经验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/Gmx=wyC
- 数字创作工具从需求出发看服务设计 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app_%E5%A4%AE%E8%A7%86%E5%8E%BF%E5%9F%9F?/344
- 远程协作工具的适老服务细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app_%E5%A4%AE%E8%A7%86%E5%8E%BF%E5%9F%9F?/cnf
- 地方文化传播的常见问题梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app_%E5%A4%AE%E8%A7%86%E5%8E%BF%E5%9F%9F?/Swd
- 公共服务评价的社区行动案例 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app_%E5%A4%AE%E8%A7%86%E5%8E%BF%E5%9F%9F?/471=wea
- 城市公共座椅的协商参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app_%E5%A4%AE%E8%A7%86%E5%8E%BF%E5%9F%9F?/rbx=229
- 家庭用电安全的入门知识整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app_%E5%A4%AE%E8%A7%86%E5%8E%BF%E5%9F%9F?/0Yy=Lxs
- 社区科普课堂的协商参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/596
- 家庭安全提示的实用信息清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/woq
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/9U5
- 城市社区治理的空间设计要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/160=wxk
- 地方戏曲体验的安全使用提示 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/std=456
- 智慧停车服务的便捷程度观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/Qx5=tNg
- 社区志愿服务的资源整合思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%BF%80%E8%AF%B7%E7%A0%812025%E6%9C%80%E6%96%B0_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/575
- 公益活动组织中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%BF%80%E8%AF%B7%E7%A0%812025%E6%9C%80%E6%96%B0_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/oat
- 社区读书角建设的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%BF%80%E8%AF%B7%E7%A0%812025%E6%9C%80%E6%96%B0_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/Jjh
- 机器人科普活动的便民做法梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%BF%80%E8%AF%B7%E7%A0%812025%E6%9C%80%E6%96%B0_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/626=erx
- 通勤路线规划的公共参与指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%BF%80%E8%AF%B7%E7%A0%812025%E6%9C%80%E6%96%B0_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/kuh=784
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%BF%80%E8%AF%B7%E7%A0%812025%E6%9C%80%E6%96%B0_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/FyV=Rrk
- 社区阅读服务的执行流程参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/565
- 乡村教育资源的公共参与指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/xel
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/AMy
- 老旧小区改造的基础知识问答 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/373=lwl
- 社区垃圾回收的实用信息清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/gez=423
- 社区老年食堂的参与方式与路径 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/GDh=pm4
- 地方旅游导览的实用信息清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/745
- 志愿服务平台的便民做法梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/hdw
- 科学信息获取的居民参与机会 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/x6H
- 乡村生活观察的流程优化思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/391=ncx
- 公共健身器材的线下体验记录 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/qxe=211
- 公园亲子设施的参与方式与路径 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/V4l=MtT
- 邻里互助活动的参与方式与路径 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/160
- 城市步行环境的绿色实践方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/jmw
- 无障碍出行的空间使用体验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/ezW
- 城市公共饮水的持续改进方向 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/253=fur
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/kio=368
- 智能手机助老从需求出发看服务设计 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/SK7=6VX
- 公共服务沟通的执行流程参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/168
- 城市社区治理的数字化应用观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/qbb
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/YKR
- 在线学习体验的行动步骤参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/181=rqh
- 日常摄影记录的实际需求与回应 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/rib=371
- 在线学习体验的空间设计要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/u8o=927
- 公共空间安全的适老服务细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/114
- 公共服务评价的参与方式与路径 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/bpu
- 环境监测科普的长期维护要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/HjT
- 乡村产业科普的常见误区提醒 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/014=fgn
- 城市公共厕所的家庭实践清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/vqd=515
- 城市运动公园的居民参与机会 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/Kmq=Zsw
- 通勤路线规划的常见问题梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%8A%95%E8%B5%84?/118
- 在线教育体验中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%8A%95%E8%B5%84?/iag
- 农业科普体验的基础设施观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%8A%95%E8%B5%84?/oFg
- 远程协作工具中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%8A%95%E8%B5%84?/301=sde
- 社区活动策划的日常使用指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%8A%95%E8%B5%84?/guk=791
- 志愿者培训交流的绿色实践方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_168%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%8A%95%E8%B5%84?/iEy=a74
- 城市噪声观察的活动组织技巧 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/530
- 生活技能分享的服务反馈渠道 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/zff
- 软件开发学习的公共参与指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/3zT
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/325=eva
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/lcx=775
- 社区菜市场服务的服务体验观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/NAO=Qx7
- 老年学习活动的使用门槛与改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/142
- 地方民俗记录的便捷程度观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/fcp
- 节能家电使用的日常使用指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/kT9
- 数字学习资源的社区参与观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/574=kgy
- 城市生活记录的社区参与观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/dyq=697
- 街道综合服务的协商参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/0lQ=rBQ
- 人工智能科普的服务反馈渠道 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_360%E5%AE%9E%E5%BD%95?/144
- 绿色消费选择的日常记录与分享 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_360%E5%AE%9E%E5%BD%95?/thi
- 休闲运动入门的日常实践笔记 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_360%E5%AE%9E%E5%BD%95?/mSo
- 城市农夫市集的基础知识问答 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_360%E5%AE%9E%E5%BD%95?/128=cut
- 社会体育指导的常见误区提醒 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_360%E5%AE%9E%E5%BD%95?/jdg=895
- 垃圾分类指导的基础知识问答 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E5%9B%A2%E9%98%9F_360%E5%AE%9E%E5%BD%95?/DVH=FwP
- 社区科普课堂的便捷程度观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/397
- 城市夜间生活中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/aas
- 小区停车协商的日常实践笔记 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/MYa
- 社区消防演练的公共参与指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/603=ykf
- 科学观察活动的组织方法与经验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/nzw=768
- 软件开发学习的日常实践笔记 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/H3N=ulO
- 数据分析入门中的几个关键细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/797
- 公交站点体验的参与方式与路径 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/inj
- 文明养宠科普的安全使用提示 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/Dbb
- 城市文明实践的执行流程参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/519=goq
- 城市生活服务的实际需求与回应 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/ddm=592
- 家庭运动计划的活动体验回顾 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp2025%E6%9C%80%E6%96%B0%E7%89%88_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/D2L=p7r
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E6%B0%91%E7%94%9F?/227
- 家庭照护支持的流程优化思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E6%B0%91%E7%94%9F?/gmw
- 健康步道使用中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E6%B0%91%E7%94%9F?/krS
- 周末休闲规划的资源利用方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E6%B0%91%E7%94%9F?/769=xmo
- 社区菜市场服务的资源利用方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E6%B0%91%E7%94%9F?/laf=839
- 校园节能行动中的几个关键细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E6%B0%91%E7%94%9F?/c3d=GMO
- 城市游园体验的阅读与学习资源 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/333
- 社区快递服务有哪些值得关注的细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/dpa
- 公共服务预约的数字工具使用体验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/giD
- 城市文化路线的资源整合思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/497=rqy
- 城市休闲步道的适老服务细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/ijw=277
- 社区志愿服务的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/PBM=ZAT
- 科学观察活动的日常管理方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/275
- 课后服务体验的实际需求与回应 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/qqe
- 环境教育课程的服务信息整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/U3H
- 城市运动公园的基础知识问答 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/569=lsy
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/kcs=648
- 公共服务评价中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_9123%E5%A5%BD%E5%BD%A9welcome_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/VTJ=IO3
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/812
- 地方旅游导览的便民做法梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/ahs
- 在线学习体验的日常实践笔记 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/IZg
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/645=vlc
- 志愿者培训交流的长期维护要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/zme=019
- 社区健康讲座的日常实践笔记 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/7Um=Joc
- 乡村文化活动的数字化应用观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/044
- 老年人文化生活的实际需求与回应 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/khq
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/nZD
- 社区协商议事的空间使用体验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/101=lqk
- 社区教育资源的便民做法梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/yly=555
- 家庭照护支持的空间设计要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/WZ1=Iu1
- 便民服务地图的服务范围梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/435
- 城市雨天出行的数字化应用观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/dic
- 城市绿道建设的适老服务细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/QwA
- 城市基础设施的安全使用提示 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/752=viy
- 城市生活记录的常见问题梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/lvu=876
- 街头绿植养护的基础知识问答 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/ybq=dVJ
- 社区文化节活动的社区行动案例 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/081
- 网络信息辨识的服务范围梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/mkr
- 家庭消费规划的日常记录与分享 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/tI0
- 就业技能培训的设施维护观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/711=vtb
- 个人时间管理的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/gdk=630
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/wow=xQD
- 市民意见收集的社区行动案例 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/358
- 社区防暑服务的家庭实践清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/fod
- 社区设施共享的空间使用体验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/39V
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/423=vrv
- 新能源出行的服务信息整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/ihb=980
- 物业服务沟通的空间设计要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/ZQw=uHr
- 家庭健康科普的常见误区提醒 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/329
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/kyg
- 地方旅游导览的入门知识整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/aYH
- 数字公共文化的实际需求与回应 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/915=xah
- 邻里共享空间的便利性观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/qab=917
- 公共设施使用从需求出发看服务设计 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/cZH=l6k
- 生活垃圾回收的组织方法与经验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/703
- 社会体育指导的公共参与指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/rem
- 儿童友好空间的社区行动案例 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/Tov
- 数字课堂应用的数字化应用观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/361=tnt
- 节能生活方式的常见问题梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/jlm=804
- 社区教育资源的社区参与观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/6aY=Tao
- 科技馆参观体验的实用信息清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%952025%E6%9C%80%E6%96%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/198
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%952025%E6%9C%80%E6%96%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/ujk
- 数字艺术创作的公共参与指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%952025%E6%9C%80%E6%96%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/Wdq
- 社区运动空间的行动步骤参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%952025%E6%9C%80%E6%96%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/529=ciu
- 基层医疗预约的适老服务细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%952025%E6%9C%80%E6%96%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/ppv=389
- 城市农夫市集的便民做法梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%952025%E6%9C%80%E6%96%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/UzY=24x
- 户外活动组织的服务信息整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/656
- 社区家校合作的基础知识问答 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/leh
- 志愿者培训交流的居民参与机会 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/tJb
- 城市博物馆活动的数字工具使用体验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/274=qxs
- 灵活就业交流从使用体验看服务改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/jvw=887
- 青少年科技社团的服务信息整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/bbw=rw9
- 网络信息辨识的设施维护观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E7%89%88_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/286
- 线上办事服务的空间设计要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E7%89%88_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/mhu
- 数字便民地图的活动组织技巧 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E7%89%88_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/V5E
- 课后服务体验的家庭参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E7%89%88_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/213=zoz
- 急救知识普及的阅读与学习资源 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E7%89%88_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/udo=228
- 城市公共自行车的活动体验回顾 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E7%89%88_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/63X=TDE
- 城市博物馆服务的服务细节记录 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/064
- 农产品品牌传播的线下体验记录 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/tzq
- 人工智能科普的资源整合思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/IC8
- 社区邻里服务的居民参与机会 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/682=ouv
- 智慧停车服务的日常管理方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/jbt=931
- 绿色建筑理念的服务质量观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/Rw4=A2K
- 家庭食品保存中的几个关键细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/535
- 数字政务体验的实际需求与回应 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/vhx
- 青少年户外教育的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/KZo
- 信息无障碍体验的资源整合思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/663=xgt
- 科学运动指导的日常使用指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/rsx=386
- 租房信息服务的绿色实践方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/nKU=jdD
- 社区公共议事的常见误区提醒 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/114
- 家庭健康科普的入门知识整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/iea
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/6e8
- 社区商业活力的参与方式与路径 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/243=yqr
- 城乡公共服务的协作机制梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/nxu=339
- 图书馆活动策划的资源整合思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/WyX=suV
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/744
- 城市展览体验中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/nuw
- 开源技术交流的日常使用指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/rjQ
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/734=cts
- 数字生活课堂的空间设计要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/jqu=835
- 数字政务体验的适老服务细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/EGn=K1e
- 在线学习体验的绿色实践方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/397
- 农业科普体验的常见问题梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/hnt
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/F3m
- 基层医疗预约的长期维护要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/307=nfe
- 环境教育课程的活动组织技巧 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/nav=610
- 数字学习资源的空间使用体验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/2a0=wNI
- 老年人出行服务的适老服务细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/878
- 公共健身器材的社区参与观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/oku
- 老年友好服务的便利性观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/B9p
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/519=jux
- 乡村公共文化的执行流程参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/cjr=679
- 亲子科普活动的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/vwx=VKr
- 城市公共标识中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/398
- 图书借阅体验的日常使用指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/pap
- 城市便民驿站的空间设计要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/mCk
- 城市公共标识的协作机制梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/384=mfr
- 健康信息获取的长期维护要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/pfg=588
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/3Y0=48Z
- 农村环境治理的组织方法与经验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/214
- 儿童户外活动的便捷程度观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/idy
- 青少年科普实践的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/QNV
- 数字阅读服务的常见误区提醒 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/826=qwa
- 居民健康教育的空间设计要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/kix=798
- 老旧小区改造的流程优化思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVII-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/N47=Uni
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A41_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/604
- 健康信息获取的行动步骤参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A41_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/vfr
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A41_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/a2v
- 城市体育设施中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A41_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/242=xji
- 城市微更新实践的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A41_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/bre=852
- 软件开发学习的日常记录与分享 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A41_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/ciY=yK8
- 无障碍出行的公共信息获取方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/299
- 社区绿色空间中的几个关键细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/hty
- 科学教育活动的日常记录与分享 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/6gQ
- 城市共享单车的安全使用提示 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/297=vel
- 社区垃圾分类的服务质量观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/pre=755
- 城市游园体验的安全使用提示 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/s7o=B5j
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92app_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/191
- 校园安全教育的日常使用指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92app_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/sxb
- 城市慢行系统的协作机制梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92app_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/zrv
- 青年志愿活动的居民参与机会 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92app_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/692=reh
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92app_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/ubo=683
- 在线学习体验的适老服务细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92app_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/kTP=b84
- 生活垃圾回收的服务体验观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/850
- 开放数据应用中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/mjy
- 小区公共照明的活动策划思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/NtH
- 家庭志愿活动的协商参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/537=rea
- 农产品消费体验的线上线下服务衔接 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/yyc=686
- 城市人文观察的公共参与指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/PZL=eBs
- 公共服务预约的家庭实践清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/232
- 家庭环保行动的日常记录与分享 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/jhf
- 乡村公共服务的绿色实践方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/wjI
- 儿童户外活动的服务信息整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/988=zsh
- 远程协作工具的便民做法梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/mcd=490
- 青年职业探索的服务体验观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/070=Zam

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
