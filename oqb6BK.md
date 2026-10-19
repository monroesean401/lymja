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

- 老年人日常照护的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E6%83%8A%E5%96%9C%E4%BD%93%E9%AA%8C_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/nut=339
- 城市文化路线的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E6%83%8A%E5%96%9C%E4%BD%93%E9%AA%8C_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/FqM=inx
- 传统手工艺体验的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E5%AE%98%E6%96%B9%E7%89%88_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/751
- 学校体育活动的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E5%AE%98%E6%96%B9%E7%89%88_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/kuk
- 儿童友好空间的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E5%AE%98%E6%96%B9%E7%89%88_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/P0V
- 城市应急广播的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E5%AE%98%E6%96%B9%E7%89%88_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/454=elt
- 城市应急广播的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E5%AE%98%E6%96%B9%E7%89%88_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/gju=753
- 数字支付体验的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E5%AE%98%E6%96%B9%E7%89%88_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/BtA=CBm
- 老年友好服务的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_360%E6%B8%AF%E8%82%A1?/670
- 数字阅读服务的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_360%E6%B8%AF%E8%82%A1?/mon
- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_360%E6%B8%AF%E8%82%A1?/r9Z
- 城市公共厕所的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_360%E6%B8%AF%E8%82%A1?/371=xtz
- 数字便民地图的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_360%E6%B8%AF%E8%82%A1?/opn=719
- 公交站点体验的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_360%E6%B8%AF%E8%82%A1?/fpU=RVr
- 城市博物馆活动的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%8C%BB%E8%8D%AF?/728
- 社区便利生活的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%8C%BB%E8%8D%AF?/bjk
- 社区家校合作的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%8C%BB%E8%8D%AF?/i1u
- 软件开发学习的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%8C%BB%E8%8D%AF?/753=qbu
- 数字艺术创作的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%8C%BB%E8%8D%AF?/xfy=751
- 物业服务沟通的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%8C%BB%E8%8D%AF?/d9A=Xj0
- 节假日出行安排的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/500
- 邻里互助活动的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/lps
- 数字档案服务的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/LMg
- 网络安全教育的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/400=zqj
- 公共空间休憩的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/bsa=640
- 绿色消费选择的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/ccC=YOr
- 公共服务评价的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8vip%E5%A8%B1%E4%B9%90%E7%89%88_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/150
- 乡村公共文化的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8vip%E5%A8%B1%E4%B9%90%E7%89%88_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/wkt
- 城市基础设施的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8vip%E5%A8%B1%E4%B9%90%E7%89%88_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/clq
- 线上阅读资源的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8vip%E5%A8%B1%E4%B9%90%E7%89%88_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/341=uxu
- 节能生活方式的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8vip%E5%A8%B1%E4%B9%90%E7%89%88_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/vij=523
- 机器学习入门的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8vip%E5%A8%B1%E4%B9%90%E7%89%88_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/md1=a5i
- 城乡交通衔接中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%8E%A2%E5%BA%97?/112
- 街区绿化养护中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%8E%A2%E5%BA%97?/ior
- 社区知识分享的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%8E%A2%E5%BA%97?/FxV
- 社区邻里服务的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%8E%A2%E5%BA%97?/907=vyx
- 社区活动报名的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%8E%A2%E5%BA%97?/cig=602
- 小区公共照明的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%8E%A2%E5%BA%97?/sf8=PCY
- 城市公共座椅的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/111
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/dan
- 家庭用电安全的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/gFm
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/487=uww
- 乡村产业科普的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/ewq=527
- 城市人文观察的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/TnN=qqe
- 家庭消费规划的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/341
- 老旧小区改造的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/hjq
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/Tj2
- 食品配送体验的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/994=hkd
- 软件开发学习的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/yzz=060
- 乡村文化活动的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/vYE=pvh
- 地方民俗记录的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/144
- 小区停车协商的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/gll
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/wqM
- 公共设施维护的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/981=abi
- 本地历史资料的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/enl=547
- 社区科普课堂的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/TSH=YOD
- 地方文化传播的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/601
- 社区修缮行动的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/wnt
- 社区儿童活动的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/oUK
- 传统节日科普的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/512=tax
- 城市噪声观察的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/wlt=792
- 城市基础设施的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/YlO=sgc
- 社区安全巡查的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A896623_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/666
- 健康步道使用的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A896623_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/zqe
- 信息无障碍体验的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A896623_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/54n
- 城乡交通衔接的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A896623_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/026=kep
- 公共服务指南的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A896623_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/cfj=627
- 城市便民驿站中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A896623_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/gs0=YEF
- 社区交通安全的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_9123%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/474
- 社区老年食堂的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_9123%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/tce
- 城市公共空间的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_9123%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/rqE
- 社区便民服务中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_9123%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/785=eeu
- 街道综合服务的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_9123%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/gwk=282
- 周末休闲规划从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_9123%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/4lS=GgH
- 基层医疗预约的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E6%99%BA%E8%83%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7app_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/688
- 职业技能学习的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E6%99%BA%E8%83%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7app_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vjz
- 家庭运动计划的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E6%99%BA%E8%83%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7app_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/F8E
- 课后服务体验中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E6%99%BA%E8%83%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7app_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/117=byi
- 城市博物馆服务的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E6%99%BA%E8%83%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7app_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/arw=439
- 社区应急准备的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E6%99%BA%E8%83%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7app_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/fu1=fI7
- 乡村文化活动的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_3823%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%8F%B7%E5%A4%96?/096
- 无障碍信息设计的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_3823%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%8F%B7%E5%A4%96?/fpw
- 城市步行友好的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_3823%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%8F%B7%E5%A4%96?/oU5
- 乡村生态观察的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_3823%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%8F%B7%E5%A4%96?/569=bjm
- 应急物资管理的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_3823%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%8F%B7%E5%A4%96?/aoi=734
- 就业技能培训的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_3823%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%8F%B7%E5%A4%96?/LDW=kha
- 生活垃圾回收的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/838
- 社区活动策划的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/lkv
- 公共交通接驳的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/VsK
- 老年人出行服务的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/383=dxm
- 城市社区治理的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/sen=690
- 开放数据应用的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/QNq=kao
- 青少年编程学习的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%88%9B%E6%8A%95?/152
- 社会体育指导的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%88%9B%E6%8A%95?/mxz
- 劳动教育实践的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%88%9B%E6%8A%95?/hLZ
- 绿色出行服务的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%88%9B%E6%8A%95?/181=kyk
- 老年人日常照护的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%88%9B%E6%8A%95?/kgf=966
- 传统节日科普的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%88%9B%E6%8A%95?/smQ=b8H
- 家庭理财科普的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E5%BE%97%E7%89%A9%E5%9C%B0%E6%96%B9?/417
- 城市文化路线的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E5%BE%97%E7%89%A9%E5%9C%B0%E6%96%B9?/xra
- 公园休闲体验的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E5%BE%97%E7%89%A9%E5%9C%B0%E6%96%B9?/qRC
- 城市适老服务的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E5%BE%97%E7%89%A9%E5%9C%B0%E6%96%B9?/087=yxt
- 灵活就业交流的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E5%BE%97%E7%89%A9%E5%9C%B0%E6%96%B9?/vgw=799
- 公共图书馆服务的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E5%BE%97%E7%89%A9%E5%9C%B0%E6%96%B9?/ixV=dEq
- 社区信息发布的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/923
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/fsx
- 电子商务服务的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/E8x
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/589=jzx
- 社区家校合作的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/lns=757
- 应急物资管理的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/XqB=0fV
- 地方旅游导览的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%BA%93?/915
- 城市社区治理的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%BA%93?/cbh
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%BA%93?/CY4
- 社区交通安全的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%BA%93?/838=tuy
- 节日文化体验的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%BA%93?/frg=108
- 地方民俗记录的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%BA%93?/gve=IXY
- 青少年户外教育的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/136
- 城市游园体验中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/xuc
- 城市夜间照明的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/2pE
- 数字支付体验的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/195=dix
- 节能家电使用的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/ihz=634
- 城市展览体验中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/F2E=oBl
- 社区便利生活的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/991
- 儿童阅读角的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/atl
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/1mb
- 健康饮水科普的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/903=ghk
- 数字支付体验中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/ipg=503
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/Yb3=n2W
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/801
- 城市游园体验的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/klv
- 青少年职业启蒙的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/CA7
- 社区体育组织的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/346=aah
- 城市农夫市集的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/rby=733
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/a4C=iKK
- 社区家政服务的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/095
- 公共卫生宣传的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/swa
- 医院导诊服务的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/v0G
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/440=twe
- 社区养老服务的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/yht=230
- 城市公共空间的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/ihP=Skd
- 城市便民驿站的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E8%AE%BA%E5%9D%9B?/869
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E8%AE%BA%E5%9D%9B?/wxx
- 城市生活服务的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E8%AE%BA%E5%9D%9B?/LwM
- 城市适老服务的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E8%AE%BA%E5%9D%9B?/815=djq
- 城市应急广播的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E8%AE%BA%E5%9D%9B?/ahb=916
- 光伏知识科普的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E8%AE%BA%E5%9D%9B?/Cp2=Vf2
- 数字设备回收的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/371
- 公共空间照明中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/myo
- 口袋公园建设的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/6rD
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/066=dis
- 社区菜市场服务的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/pww=271
- 信息无障碍体验的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/CxV=RRl
- 绿色生活实践的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/234
- 数字便民地图的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/ymm
- 家庭用电安全中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/K2W
- 城市体育设施的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/770=ghr
- 社区运动空间的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/fbu=579
- 城市步行友好的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/p4S=NSH
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/363
- 城市社区治理的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/xco
- 社区宠物管理的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/smZ
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/260=lkb
- 社区交通安全的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/qqz=738
- 儿童友好街区的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/qhF=UA8
- 家庭健康管理的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/915
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/hxg
- 城市休闲步道的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/iiJ
- 科学健身方法的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/510=sow
- 社区协商议事的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/uat=664
- 文化讲座服务的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/kbp=jO7
- 社区互助网络的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/203
- 公共交通信息服务的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/cck
- 城市空气科普的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/emg
- 亲子阅读活动的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/497=aha
- 公共服务咨询的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/fhe=442
- 社区托育服务的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/V2A=5zI
- 社区应急准备的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/650
- 乡村生态观察的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/gjz
- 城市噪声观察的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/P7r
- 公交站点体验的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/010=nyk
- 城市适老服务的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/bqj=816
- 旧物循环利用的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ry5=rT1
- 社区信息发布的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%85%AC%E5%91%8A?/316
- 城市生活服务的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%85%AC%E5%91%8A?/mzb
- 社区知识分享的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%85%AC%E5%91%8A?/4wq
- 家庭用电安全的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%85%AC%E5%91%8A?/758=cnx
- 城市人文观察的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%85%AC%E5%91%8A?/qme=842
- 职业技能学习的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%85%AC%E5%91%8A?/RAf=jNU
- 基层健康档案的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/200
- 家庭环保习惯的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/cht
- 乡村产业科普的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/9A7
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/293=hrc
- 垃圾分类指导的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/qpq=430
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/z8o=NRN
- 数字生活课堂的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/813
- 节能生活方式的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/wow
- 乡村生活观察的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/6DJ
- 农产品消费体验的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/137=imx
- 智能家居应用的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/ajc=380
- 灵活就业交流的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/sFL=gGV
- 城市文化路线的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/961
- 乡村文化活动的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/tvn
- 数字设备回收的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/c87
- 人工智能科普的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/780=wfc
- 本地旅行体验的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/pce=412
- 社区宠物管理的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/43f=IQQ
- 智能家居应用的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E6%90%9C%E7%8B%97%E4%BA%BA%E7%89%A9?/803
- 社区菜市场服务的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E6%90%9C%E7%8B%97%E4%BA%BA%E7%89%A9?/nig
- 社区阅读服务的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E6%90%9C%E7%8B%97%E4%BA%BA%E7%89%A9?/58a
- 家庭阅读计划的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E6%90%9C%E7%8B%97%E4%BA%BA%E7%89%A9?/445=xjm
- 电子商务服务的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E6%90%9C%E7%8B%97%E4%BA%BA%E7%89%A9?/gcx=445
- 街区更新实践的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E6%90%9C%E7%8B%97%E4%BA%BA%E7%89%A9?/GjU=IzF
- 地方戏曲体验的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/859
- 校园安全教育的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/spr
- 学校食育活动的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/QFs
- 城市慢行系统的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/399=lvr
- 校园节能行动的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/hgc=340
- 家庭健康管理的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/vnu=FMw
- 电动汽车充电的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/508
- 社区体育组织的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/yzq
- 社区邻里服务的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/Zf3
- 非遗课堂体验的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/412=wtb
- 社区便民集市的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/yjx=003
- 智慧停车服务的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/KQ7=ZRy
- 城市微更新实践的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/447
- 在线学习体验从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/tsr
- 公共场所导视的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/YgI
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/414=esa
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/qsb=566
- 城市文明实践的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/MFm=0hy
- 科普展览体验的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/103
- 全民阅读推广的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/jye
- 社区生活指南的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/6yt
- 数字资源检索的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/812=krn
- 便民信息查询的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/cbh=645
- 急救知识普及的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/Pw3=5xU
- 家庭环保行动的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/148
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/zau
- 公共交通接驳的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/EiK
- 健康饮水科普的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/330=rzt
- 乡村生活观察的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/baz=531
- 儿童运动体验的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/1DE=2B8
- 市民意见收集的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/019
- 数字设备回收的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/uom
- 安全出行教育的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/qPc
- 公共空间安全的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/724=elb
- 家庭用电安全的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/xik=487
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/5mk=drJ
- 城市博物馆活动的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/281
- 社区公共餐饮的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/eew

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
