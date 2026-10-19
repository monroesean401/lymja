# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 数字设备回收的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E4%BF%A1%E8%B4%B7?/cyk=134
- 社区心理支持的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E4%BF%A1%E8%B4%B7?/y08=kgV
- 节假日出行安排的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E5%A8%B1%E4%B9%90%E5%9C%BA_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/525
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E5%A8%B1%E4%B9%90%E5%9C%BA_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/uje
- 个人信息保护的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E5%A8%B1%E4%B9%90%E5%9C%BA_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/qw8
- 社区便民服务中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E5%A8%B1%E4%B9%90%E5%9C%BA_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/445=ucn
- 生成式工具使用的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E5%A8%B1%E4%B9%90%E5%9C%BA_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/phx=775
- 志愿者培训交流的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E5%A8%B1%E4%B9%90%E5%9C%BA_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/mxR=5ul
- 街区更新实践的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/378
- 食品配送体验的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/prc
- 家庭健康科普的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/tvQ
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/667=ynd
- 乡村生活观察的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/cyk=403
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/bLK=Iqo
- 食品安全科普的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_30cc%E5%A8%B1%E4%B9%90%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/612
- 老年人文化生活的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_30cc%E5%A8%B1%E4%B9%90%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/pzb
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_30cc%E5%A8%B1%E4%B9%90%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/Cnd
- 农业科普体验的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_30cc%E5%A8%B1%E4%B9%90%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/443=wvr
- 在线教育体验的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_30cc%E5%A8%B1%E4%B9%90%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/ydr=349
- 城市休闲步道的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_30cc%E5%A8%B1%E4%B9%90%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/mk1=LPg
- 农村环境治理的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%90%89%E5%BD%A9%E7%BD%91%E6%B3%A8%E5%86%8C...welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E9%9F%B3%E4%B9%90?/758
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%90%89%E5%BD%A9%E7%BD%91%E6%B3%A8%E5%86%8C...welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E9%9F%B3%E4%B9%90?/ptp
- 公共空间照明的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%90%89%E5%BD%A9%E7%BD%91%E6%B3%A8%E5%86%8C...welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E9%9F%B3%E4%B9%90?/M4E
- 节气饮食文化的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%90%89%E5%BD%A9%E7%BD%91%E6%B3%A8%E5%86%8C...welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E9%9F%B3%E4%B9%90?/605=nwl
- 非遗课堂体验的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%90%89%E5%BD%A9%E7%BD%91%E6%B3%A8%E5%86%8C...welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E9%9F%B3%E4%B9%90?/wxo=737
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%90%89%E5%BD%A9%E7%BD%91%E6%B3%A8%E5%86%8C...welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E9%9F%B3%E4%B9%90?/QWy=oa2
- 社区共享书架的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/517
- 市民意见收集的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/mxu
- 农村环境治理的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/s5J
- 社区健康讲座的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/029=ffg
- 城市文明出行的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/elo=393
- 社区文化节活动的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/soT=bSK
- 健康饮水科普的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/519
- 乡村教育资源有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/ulh
- 城乡公共服务的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/fmY
- 劳动教育实践的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/295=mfe
- 社区绿色空间的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/hub=648
- 智慧城市体验的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/RB1=lJ6
- 科学睡眠习惯从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/017
- 老年数字阅读中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/ymx
- 老年人日常照护的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/WPU
- 校园安全教育的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/770=uxr
- 乡村教育资源的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/gsk=034
- 节能家电使用的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/lFH=Sfq
- 街道综合服务的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/557
- 社区活动策划的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/qxq
- 城市展览体验的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/1QJ
- 社区读书角建设的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/889=pkb
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/bpm=934
- 社区信息发布的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/RTr=X1F
- 城市公共自行车的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%90%89%E7%A5%A5%E5%BD%A9app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/299
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%90%89%E7%A5%A5%E5%BD%A9app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/znx
- 科技馆参观体验中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%90%89%E7%A5%A5%E5%BD%A9app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/nTc
- 公共服务数字化的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%90%89%E7%A5%A5%E5%BD%A9app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/189=jsf
- 家庭网络使用的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%90%89%E7%A5%A5%E5%BD%A9app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/afk=826
- 本地消费场景的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%90%89%E7%A5%A5%E5%BD%A9app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/INQ=qZe
- 线上办事服务的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%BD%91%E9%A1%B5%E7%89%88_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/634
- 非遗课堂体验的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%BD%91%E9%A1%B5%E7%89%88_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/kgn
- 城市生活服务的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%BD%91%E9%A1%B5%E7%89%88_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/qfw
- 青少年科技社团的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%BD%91%E9%A1%B5%E7%89%88_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/458=rxl
- 乡村文化空间的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%BD%91%E9%A1%B5%E7%89%88_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/qyb=005
- 公园休闲体验的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%BD%91%E9%A1%B5%E7%89%88_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/nl5=pED
- 乡村公共阅读的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/776
- 社区邻里服务的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/vjp
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/ElG
- 绿色办公实践的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/730=dow
- 乡村公共文化中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/xwh=186
- 社区防暑服务的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/XzK=MOX
- 公共空间休憩的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A905005%E5%AE%98%E6%96%B9%E7%89%88_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/128
- 老年人日常照护的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A905005%E5%AE%98%E6%96%B9%E7%89%88_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/xns
- 青少年心理健康的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A905005%E5%AE%98%E6%96%B9%E7%89%88_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/iFn
- 乡村产业科普的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A905005%E5%AE%98%E6%96%B9%E7%89%88_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/814=hnf
- 个人信息保护的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A905005%E5%AE%98%E6%96%B9%E7%89%88_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/ykz=807
- 城市人文观察的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A905005%E5%AE%98%E6%96%B9%E7%89%88_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/vZS=TsM
- 公园亲子设施的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_welcome%E5%90%89%E7%A5%A5%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/563
- 青年志愿活动的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_welcome%E5%90%89%E7%A5%A5%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/csx
- 公共服务数字化的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_welcome%E5%90%89%E7%A5%A5%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/RG7
- 城市公共标识的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_welcome%E5%90%89%E7%A5%A5%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/100=vhm
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_welcome%E5%90%89%E7%A5%A5%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/fkq=957
- 社区便民集市的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_welcome%E5%90%89%E7%A5%A5%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/dZD=07i
- 在线学习体验的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E6%8B%9B%E5%95%86_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/463
- 个人信息保护的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E6%8B%9B%E5%95%86_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/wkz
- 远程协作工具的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E6%8B%9B%E5%95%86_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/wmY
- 学校食育活动的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E6%8B%9B%E5%95%86_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/336=pfa
- 本地历史资料的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E6%8B%9B%E5%95%86_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/acx=250
- 社区交通安全的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E6%8B%9B%E5%95%86_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/DRB=qgT
- 公共服务沟通的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E7%A5%A5%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E6%8F%90%E7%8E%B0_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/013
- 老年数字阅读的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E7%A5%A5%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E6%8F%90%E7%8E%B0_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/neb
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E7%A5%A5%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E6%8F%90%E7%8E%B0_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/jHA
- 公共交通接驳的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E7%A5%A5%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E6%8F%90%E7%8E%B0_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/430=rkq
- 社区快递服务的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E7%A5%A5%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E6%8F%90%E7%8E%B0_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/mki=967
- 数字创意课程的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E7%A5%A5%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E6%8F%90%E7%8E%B0_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/l3O=qLI
- 城市步行友好的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%90%89%E7%A5%A5%E8%B4%AD%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/404
- 图书馆活动策划的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%90%89%E7%A5%A5%E8%B4%AD%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/nqx
- 基层医疗预约的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%90%89%E7%A5%A5%E8%B4%AD%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/GcG
- 地方民俗记录的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%90%89%E7%A5%A5%E8%B4%AD%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/605=jla
- 健康信息获取的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%90%89%E7%A5%A5%E8%B4%AD%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/blp=181
- 城市生活服务的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%90%89%E7%A5%A5%E8%B4%AD%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/vBI=av5
- 药品使用科普的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/654
- 城市公共空间的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/ezl
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/6IZ
- 公共服务咨询的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/398=gke
- 节假日出行安排的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/ouh=437
- 公共文化活动的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/6gw=ZLq
- 城市步行友好的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_4G%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/497
- 本地历史资料的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_4G%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/vcw
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_4G%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/1S0
- 公共卫生设施的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_4G%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/782=bce
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_4G%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/bbf=401
- 节日文化体验的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_4G%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/jBv=F4h
- 社区慢性病防控的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/394
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/mgx
- 社区消防演练的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/rQf
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/345=nmn
- 地方文化传播的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/vpz=388
- 公共空间安全的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/f3B=1KQ
- 社会体育指导的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%90%89%E7%A5%A5%E8%B4%AD%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/800
- 城市文明出行的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%90%89%E7%A5%A5%E8%B4%AD%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/cdv
- 人工智能科普的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%90%89%E7%A5%A5%E8%B4%AD%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/p1x
- 智能家居应用的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%90%89%E7%A5%A5%E8%B4%AD%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/031=ykm
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%90%89%E7%A5%A5%E8%B4%AD%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/gqt=593
- 新能源知识普及的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%90%89%E7%A5%A5%E8%B4%AD%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/YDE=MJT
- 个人时间管理的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/329
- 机器人科普活动的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dqt
- 居民健康教育的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/e9P
- 街区绿化养护的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/759=mkl
- 社区庭院绿化的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kwg=140
- 社区手工活动的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/owE=dvo
- 开源技术交流的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%87%91%E5%BD%A9%E6%B1%87%E6%B4%BB%E5%8A%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8?/203
- 节能生活方式的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%87%91%E5%BD%A9%E6%B1%87%E6%B4%BB%E5%8A%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8?/sss
- 邻里互助活动的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%87%91%E5%BD%A9%E6%B1%87%E6%B4%BB%E5%8A%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8?/sbd
- 新能源出行的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%87%91%E5%BD%A9%E6%B1%87%E6%B4%BB%E5%8A%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8?/768=avr
- 便民服务窗口的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%87%91%E5%BD%A9%E6%B1%87%E6%B4%BB%E5%8A%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8?/hai=775
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%87%91%E5%BD%A9%E6%B1%87%E6%B4%BB%E5%8A%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8?/OMX=3zx
- 新能源知识普及中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E6%B1%87%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/349
- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E6%B1%87%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/tkp
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E6%B1%87%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/uyF
- 城市基础设施的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E6%B1%87%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/561=hdt
- 消防知识宣传的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E6%B1%87%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/rps=620
- 公交无障碍服务的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E6%B1%87%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/vS2=4c8
- 灵活就业交流从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/680
- 街道综合服务的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/kjd
- 公共设施维护的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/VvX
- 机器人科普活动的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/685=aai
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/mkp=332
- 社区学习活动的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/dPG=Jgv
- 图书馆亲子空间的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E9%87%91%E6%B1%87%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/366
- 社区家校合作的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E9%87%91%E6%B1%87%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/iuw
- 乡村文化空间的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E9%87%91%E6%B1%87%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/ErH
- 社区家校合作的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E9%87%91%E6%B1%87%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/658=uza
- 社区家校合作的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E9%87%91%E6%B1%87%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/xtb=226
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E9%87%91%E6%B1%87%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/USK=8OY
- 家庭健康管理的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%87%91%E5%BD%A94.0_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/111
- 旧物循环利用的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%87%91%E5%BD%A94.0_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/fiv
- 城市共享单车的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%87%91%E5%BD%A94.0_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/ykl
- 在线教育体验的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%87%91%E5%BD%A94.0_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/193=oda
- 本地消费场景的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%87%91%E5%BD%A94.0_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/rmq=875
- 家庭健康科普的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%87%91%E5%BD%A94.0_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/Q0d=Ezz
- 乡村生活观察的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_657cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/088
- 城乡交流活动的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_657cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/buo
- 城市绿道建设的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_657cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/5pp
- 休闲运动入门的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_657cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/686=qjd
- 家庭节能实践的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_657cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/udn=945
- 公共场所导视的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_657cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/VRl=ZZz
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%87%91%E6%B1%87%E5%BD%A9%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/569
- 老年友好服务的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%87%91%E6%B1%87%E5%BD%A9%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/iis
- 在线学习体验的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%87%91%E6%B1%87%E5%BD%A9%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/sV4
- 城市公共标识的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%87%91%E6%B1%87%E5%BD%A9%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/456=zgv
- 社区共享书架的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%87%91%E6%B1%87%E5%BD%A9%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/vhs=215
- 职业技能学习的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%87%91%E6%B1%87%E5%BD%A9%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E9%9F%B3%E4%B9%90?/ywZ=cWY
- 城市基础设施的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/911
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/wsk
- 智慧城市体验的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/ta8
- 本地旅行体验的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/913=uhi
- 节能生活方式的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/lhr=109
- 文化讲座服务的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/iFm=eCK
- 家庭节能设备的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%BE%8E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/317
- 青年就业服务的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%BE%8E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/ubu
- 乡村电商实践的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%BE%8E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/WOK
- 城市可持续生活的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%BE%8E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/837=drw
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%BE%8E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/juu=885
- 小区停车协商的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%BE%8E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/Tt2=5G7
- 学校食育活动的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E9%87%91%E6%B1%87%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/740
- 口袋公园建设中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E9%87%91%E6%B1%87%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/qkw
- 街头绿植养护的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E9%87%91%E6%B1%87%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/Kpm
- 数字创作工具的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E9%87%91%E6%B1%87%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/120=kko
- 周末休闲规划中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E9%87%91%E6%B1%87%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/thc=929
- 生活服务数字化的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E9%87%91%E6%B1%87%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/SdD=EXn
- 社区宠物管理的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E9%87%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/589
- 休闲运动入门的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E9%87%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/nsc
- 乡村文化活动的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E9%87%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/8xR
- 乡村教育资源的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E9%87%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/425=lnz
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E9%87%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/fxq=715
- 公共卫生宣传的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E9%87%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/xSl=3AQ
- 街头绿植养护的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/254
- 公共空间休憩的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/csg
- 绿色出行服务的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/BOA
- 家庭科学教育的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/759=oey
- 地方文化传播的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/zpe=498
- 社区体育组织的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/ejy=Hvf
- 药品使用科普的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%95%99%E8%82%B2?/340
- 消防知识宣传的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%95%99%E8%82%B2?/hlu
- 青少年科技社团的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%95%99%E8%82%B2?/Nr0
- 乡村公共文化的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%95%99%E8%82%B2?/157=svc
- 乡村文化空间的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%95%99%E8%82%B2?/nxm=063
- 城市文明实践的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%95%99%E8%82%B2?/RtZ=FEf
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E2%80%94%E5%AF%B9%E2%80%94%E5%8C%85%E8%B5%94_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/796
- 农产品消费体验的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E2%80%94%E5%AF%B9%E2%80%94%E5%8C%85%E8%B5%94_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/puo
- 校园社团活动的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E2%80%94%E5%AF%B9%E2%80%94%E5%8C%85%E8%B5%94_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/oZb
- 便民服务窗口的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E2%80%94%E5%AF%B9%E2%80%94%E5%8C%85%E8%B5%94_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/927=dfo
- 街道综合服务的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E2%80%94%E5%AF%B9%E2%80%94%E5%8C%85%E8%B5%94_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/tfh=513
- 街区道路维护的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E2%80%94%E5%AF%B9%E2%80%94%E5%8C%85%E8%B5%94_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/hlv=3eK
- 图书馆数字服务的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87welcome%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5%E7%82%B9%E5%87%BB%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/761
- 新能源知识普及的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87welcome%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5%E7%82%B9%E5%87%BB%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/glp
- 社区邻里服务的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87welcome%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5%E7%82%B9%E5%87%BB%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/JfJ
- 家庭安全提示的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87welcome%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5%E7%82%B9%E5%87%BB%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/519=gno
- 公共服务评价的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87welcome%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5%E7%82%B9%E5%87%BB%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/nlo=428
- 智能家居应用的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87welcome%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5%E7%82%B9%E5%87%BB%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/Qn1=okS
- 基层健康档案的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E6%A0%87%E5%87%86%E7%89%88%E9%87%91%E5%BD%A9%E6%B1%87%E6%A0%87%E5%87%86%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/688
- 公共服务数字化的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E6%A0%87%E5%87%86%E7%89%88%E9%87%91%E5%BD%A9%E6%B1%87%E6%A0%87%E5%87%86%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/fyj
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E6%A0%87%E5%87%86%E7%89%88%E9%87%91%E5%BD%A9%E6%B1%87%E6%A0%87%E5%87%86%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/3kZ
- 城市住房服务的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E6%A0%87%E5%87%86%E7%89%88%E9%87%91%E5%BD%A9%E6%B1%87%E6%A0%87%E5%87%86%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/628=aly
- 城市体育设施的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E6%A0%87%E5%87%86%E7%89%88%E9%87%91%E5%BD%A9%E6%B1%87%E6%A0%87%E5%87%86%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/bry=365
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E6%A0%87%E5%87%86%E7%89%88%E9%87%91%E5%BD%A9%E6%B1%87%E6%A0%87%E5%87%86%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/4Mx=X0Y
- 生活垃圾减量的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E9%87%91%E5%BD%A9%E6%B1%87-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%BD%B1%E8%A7%86?/173
- 社区便利生活的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E9%87%91%E5%BD%A9%E6%B1%87-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%BD%B1%E8%A7%86?/ceu
- 老年学习活动的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E9%87%91%E5%BD%A9%E6%B1%87-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%BD%B1%E8%A7%86?/5oN
- 公共卫生宣传的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E9%87%91%E5%BD%A9%E6%B1%87-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%BD%B1%E8%A7%86?/466=uca
- 社区便利生活的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E9%87%91%E5%BD%A9%E6%B1%87-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%BD%B1%E8%A7%86?/tnd=335
- 乡村阅读活动的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E9%87%91%E5%BD%A9%E6%B1%87-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%BD%B1%E8%A7%86?/g6A=RRB
- 数字学习资源的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%87%91%E5%BD%A9%E6%B1%87-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/374
- 城市噪声观察的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%87%91%E5%BD%A9%E6%B1%87-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/rja
- 儿童安全出行的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%87%91%E5%BD%A9%E6%B1%87-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/ej1
- 食品配送体验的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%87%91%E5%BD%A9%E6%B1%87-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/007=uoz
- 社区故事采集的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%87%91%E5%BD%A9%E6%B1%87-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/qmq=820
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%87%91%E5%BD%A9%E6%B1%87-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/JC2=GAP
- 城市应急广播的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%29_%E8%84%89%E8%84%89%E4%BA%BA%E5%A4%A7?/729
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%29_%E8%84%89%E8%84%89%E4%BA%BA%E5%A4%A7?/tlq
- 家庭养老规划的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%29_%E8%84%89%E8%84%89%E4%BA%BA%E5%A4%A7?/5LR
- 公园休闲体验的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%29_%E8%84%89%E8%84%89%E4%BA%BA%E5%A4%A7?/603=xyi
- 社区花园共建的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%29_%E8%84%89%E8%84%89%E4%BA%BA%E5%A4%A7?/bmh=814
- 社区协商议事的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%29_%E8%84%89%E8%84%89%E4%BA%BA%E5%A4%A7?/62C=S3z
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E7%BD%91%E7%AB%99%E6%9C%80%E5%A5%BD_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/216
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E7%BD%91%E7%AB%99%E6%9C%80%E5%A5%BD_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/gzn
- 小区公共照明的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E7%BD%91%E7%AB%99%E6%9C%80%E5%A5%BD_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/rPC
- 老年运动活动的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E7%BD%91%E7%AB%99%E6%9C%80%E5%A5%BD_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/371=hhn
- 城市游园体验的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E7%BD%91%E7%AB%99%E6%9C%80%E5%A5%BD_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/pmq=287
- 社区设施共享的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E7%BD%91%E7%AB%99%E6%9C%80%E5%A5%BD_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/mrs=J11
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/953
- 健康信息获取的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%87%91%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/rjo

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
