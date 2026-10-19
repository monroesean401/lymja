# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 城市可持续生活的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/204
- 绿色出行服务的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/mys
- 个人时间管理的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/NxK
- 课后服务体验的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/981=uvf
- 城市绿色交通的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/yid=916
- 青少年科技社团的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/cPX=Fnm
- 远程协作工具的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%95%85%E6%B8%B8?/126
- 社区活动空间的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%95%85%E6%B8%B8?/iwi
- 儿童阅读角的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%95%85%E6%B8%B8?/6Al
- 青少年户外教育的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%95%85%E6%B8%B8?/903=tdk
- 音乐欣赏活动的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%95%85%E6%B8%B8?/wbl=163
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%95%85%E6%B8%B8?/7Na=ihi
- 创业经验分享的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/164
- 社区信息发布的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/ccw
- 新能源出行的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/tTa
- 城市公共座椅的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/092=mhq
- 公共交通信息服务的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/skb=206
- 城市地名文化的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/keJ=y24
- 公共卫生宣传的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/093
- 数字生活课堂的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/prz
- 街道综合服务的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/g6c
- 地方旅游导览的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/784=dvl
- 休闲运动入门的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/xws=552
- 城市适老服务的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/llt=PE3
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/343
- 社区信息发布的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/gec
- 新能源出行的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/2SN
- 智慧停车服务的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/505=goa
- 儿童运动体验的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/cbu=384
- 非遗体验活动的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/hSR=WlE
- 社区志愿服务中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/195
- 社区绿色空间的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/ccj
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/bCI
- 儿童运动体验的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/311=ydq
- 科普展览体验的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/tow=069
- 公交无障碍服务的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/eC5=WOl
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/703
- 个人信息保护中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/lcb
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/pTO
- 气象科普传播有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/037=wmu
- 社区便民服务的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/pqv=432
- 科学健身方法的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/1yf=9qg
- 人工智能科普的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/401
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/xuw
- 志愿服务平台的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/PUd
- 科学教育活动的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/549=mxm
- 无障碍出行的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/gbi=539
- 社区阅读服务的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/Whi=U9d
- 社区手工活动的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E6%99%9A%E6%8A%A5?/971
- 社区家政服务的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E6%99%9A%E6%8A%A5?/ukc
- 社区家校合作的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E6%99%9A%E6%8A%A5?/OfZ
- 周末休闲规划的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E6%99%9A%E6%8A%A5?/277=jku
- 城市文化路线的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E6%99%9A%E6%8A%A5?/psv=948
- 社区文化节活动的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E6%99%9A%E6%8A%A5?/d7I=Ulb
- 社区公共餐饮的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/159
- 智慧城市体验的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/gsk
- 食品安全科普的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/HFn
- 城市人文观察的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/435=ryg
- 乡村文化活动的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/rck=824
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/cce=XTs
- 社区学习活动的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/634
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/qxo
- 儿童安全出行的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/bLR
- 社区应急准备的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/300=gxp
- 家庭养老规划的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/kvy=655
- 社区志愿服务的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/oW5=8JV
- 就业技能培训的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/257
- 学校食育活动的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/pix
- 城市基础设施的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/C6j
- 城市公共艺术的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/091=ebk
- 便民维修服务的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/igp=988
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/cfQ=ohK
- 老年学习活动的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%8C%96?/422
- 网络信息辨识的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%8C%96?/alf
- 生活技能分享的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%8C%96?/xiB
- 老年学习活动的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%8C%96?/336=vhx
- 数字便民地图的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%8C%96?/swm=369
- 社区活动空间的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%8C%96?/Xgw=3Ib
- 社区便利生活的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/568
- 网络安全教育的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/quh
- 非遗体验活动的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/1Eh
- 居家适老化改造的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/321=dyk
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/ysq=807
- 科技馆参观体验的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/Dq8=XIB
- 绿色快递包装的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/488
- 社区故事采集的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/pyl
- 城市公共标识的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/fi7
- 亲子科普活动的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/281=ysp
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/szo=111
- 乡村公共文化的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/kmX=kpw
- 绿色校园实践的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/189
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/ujc
- 节日文化体验的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/epu
- 城市文化路线的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/827=uoq
- 城市人文观察的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/jhh=480
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/X4H=m59
- 公园无障碍服务的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/975
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/muc
- 公共卫生宣传的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/RUH
- 社区养老服务的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/477=hux
- 乡村文化活动的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/xyx=988
- 通勤路线规划的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/ZRr=PAX
- 社区信息发布的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/457
- 社区信息发布的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/xqu
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/LAI
- 读书会组织的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/397=ehx
- 家庭教育交流的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/udv=927
- 智能家居应用的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/QJZ=Y6t
- 城市应急科普的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/180
- 乡村产业科普的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/rju
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/Pw7
- 无障碍出行的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/150=klb
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/pky=661
- 社区家校合作的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/aE9=dFD
- 城市公共厕所的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/978
- 城市慢行系统的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/laz
- 开放数据应用的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/TCc
- 社区停车服务的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/199=ggh
- 城市共享单车的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/nyq=709
- 城市适老服务的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/Uit=EXf
- 社会体育指导的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/705
- 运动安全知识的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/xkl
- 家庭健康管理的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/3Go
- 亲子科普活动中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/836=jpe
- 城市运动公园的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/szs=664
- 非遗体验活动的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/f27=93r
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/160
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/uqg
- 老年学习活动的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/kqv
- 社区体育组织的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/087=tis
- 城市公共标识的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/shg=627
- 街头绿植养护的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/N4l=QVF
- 青少年科普实践的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9F%8E%E4%BA%8B?/241
- 基层健康档案的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9F%8E%E4%BA%8B?/jpp
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9F%8E%E4%BA%8B?/3CL
- 开放式学习空间的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9F%8E%E4%BA%8B?/560=fnf
- 社区手工活动的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9F%8E%E4%BA%8B?/dek=375
- 生活技能分享的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9F%8E%E4%BA%8B?/doq=tbH
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%92%AD%E6%8A%A5?/697
- 绿色校园实践的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%92%AD%E6%8A%A5?/rho
- 节日文化体验的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%92%AD%E6%8A%A5?/0Ad
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%92%AD%E6%8A%A5?/113=ley
- 数字课堂应用的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%92%AD%E6%8A%A5?/nlx=381
- 数字创意课程的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%92%AD%E6%8A%A5?/Q9n=e0O
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/693
- 市民热线服务的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/gbp
- 城市水环境观察的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/uh5
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/776=jjm
- 城市建设科普的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/zsl=711
- 社区共享书架的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/Cr1=7FC
- 社区宣传栏更新的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/233
- 老年人日常照护的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/dmb
- 街区更新实践的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/j76
- 社区手工活动的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/986=sml
- 社区快递服务的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/aep=326
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/nCg=Nmt
- 安全出行教育的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/070
- 文化讲座服务的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/lqy
- 居家防滑改造的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/94j
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/691=jix
- 家庭环保行动的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/yob=580
- 社区共享书架的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/zSw=UPE
- 城市共享单车的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/183
- 医院导诊服务的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/lbb
- 课后服务体验的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/wQ3
- 社区生活指南的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/428=jyv
- 节约用水实践的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/uzo=821
- 环境监测科普的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/PhB=3cl
- 青少年户外教育的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/772
- 社区宠物管理的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/jnc
- 城市可持续生活的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/Rnh
- 节约用水实践的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/294=bjh
- 人工智能科普的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/xhu=668
- 城市博物馆活动的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/29x=kXj
- 便民服务地图的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/179
- 数据分析入门的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/dtv
- 城市生活记录的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/B9P
- 运动安全知识的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/340=xfa
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/cga=841
- 公共图书馆服务的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/vva=1Fw
- 绿色消费选择的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%9B%86?/776
- 乡村文化空间的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%9B%86?/fbo
- 乡村电商实践的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%9B%86?/4oN
- 新能源出行中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%9B%86?/078=lvb
- 家庭运动计划的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%9B%86?/pvx=679
- 农产品消费体验的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%9B%86?/OEs=M9f
- 居民健康教育的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/460
- 图书馆数字服务的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/xtg
- 老年学习活动的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/p6W
- 图书馆数字服务的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/296=oxh
- 传统手工艺体验的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/iyf=686
- 社区教育资源的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/Mxv=rjv
- 老年数字阅读的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/170
- 职业技能学习的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/avt
- 开放数据应用的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/qZ1
- 科学观察活动的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/976=xkz
- 电动汽车充电中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/egv=998
- 家庭环保习惯的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/NSr=Nx1
- 消防知识宣传的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/022
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/fes
- 生活垃圾减量的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/ZtV
- 应急物资管理的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/425=lwf
- 数字课堂应用的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/umb=675
- 社区阅读服务的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/j5Z=WGQ
- 公共服务沟通的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/042
- 健康步道使用的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/bbu
- 家庭健康科普的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/s4z
- 社区应急准备的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/115=bxz
- 社区停车服务的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/lpd=361
- 社区阅读服务的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/FpO=Ukn
- 社区体育组织的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/624
- 就业技能培训的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/nyt
- 人工智能科普的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/rfb
- 骑行路线规划的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/052=bfq
- 城市文明实践的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/nzb=620
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/U2q=GF2
- 公共文化活动的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/885
- 公园休闲体验的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/aca
- 社区养老服务的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/cme
- 城市基础设施的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/309=oam
- 社区活动策划的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/mqh=653
- 家庭环保行动的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/Fpv=Apy
- 本地消费场景的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/851
- 数字艺术创作的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/adu
- 全民健身活动的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/jmD
- 无障碍信息设计的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/956=has
- 公共服务咨询的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/gdj=847
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/rS2=OEO
- 老年人文化生活的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/845
- 环境监测科普的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/krr
- 城乡公共服务的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/g2l
- 跨代沟通活动的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/279=saf
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/ymu=867
- 街道综合服务的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/jCB=awg
- 公共设施维护的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/046
- 社区知识分享的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/yta
- 公交无障碍服务中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/Hlp
- 基层服务创新的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/824=vsg
- 家庭科学教育的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/gks=757
- 家庭用电安全的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/fdq=RzC
- 软件开发学习的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/591
- 街道综合服务的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/tbq
- 青少年编程学习的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/nwz
- 社区便利生活的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/468=dvu
- 社区应急准备的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/ggs=987
- 社区教育资源的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/808=G7H
- 城市运动公园的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/191
- 无障碍出行的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/frk
- 城市生活记录的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/UJO
- 社区托育服务的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/807=rve

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
