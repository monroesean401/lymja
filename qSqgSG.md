# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:25**

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

- 城市步行环境的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/QuV
- 城市夜间照明的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/540=fan
- 老年人出行服务的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/zfr=643
- 数字公共文化的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/91e=GRT
- 城市展览体验的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/676
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/nnm
- 小微企业服务的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/3pl
- 骑行路线规划的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/048=pcn
- 在线学习体验的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/imp=076
- 城乡公共服务的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/GQG=X8l
- 图书馆活动策划的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%85%9A%E5%BB%BA?/959
- 安全出行教育的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%85%9A%E5%BB%BA?/qqv
- 街区道路维护的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%85%9A%E5%BB%BA?/aPx
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%85%9A%E5%BB%BA?/114=yag
- 城市公共艺术的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%85%9A%E5%BB%BA?/tyr=515
- 小区电梯维护的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E5%85%9A%E5%BB%BA?/6cq=TOv
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/072
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/gmu
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/RaS
- 城市步行友好的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/380=sak
- 青少年心理健康的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/jug=004
- 街道综合服务的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/2VA=9kQ
- 城市生活记录的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/396
- 城市噪声观察的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/bqu
- 电动汽车充电的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/aKz
- 儿童运动体验的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/490=meb
- 线上办事服务的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/wbx=270
- 社区托育服务的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/gaT=hQH
- 乡村教育资源的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/863
- 零废弃生活尝试的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/psu
- 旧物循环利用的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/V2P
- 节能家电使用的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/755=eke
- 家庭安全提示的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/elx=656
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/8GU=7Tk
- 城市夜间生活的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/673
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/que
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/NJ8
- 乡村文化活动的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/863=oil
- 公共空间安全的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/cbl=841
- 绿色出行服务的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/cnL=Ac2
- 基层服务创新的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/488
- 青年志愿活动的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/scl
- 新能源知识普及的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/eOH
- 亲子科普活动的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/706=rfe
- 科学观察活动的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/osy=961
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/YBG=WOT
- 社区知识分享的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E7%BB%BC%E8%89%BA?/160
- 图书借阅体验的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E7%BB%BC%E8%89%BA?/pdv
- 社区生活指南的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E7%BB%BC%E8%89%BA?/OGn
- 口袋公园建设的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E7%BB%BC%E8%89%BA?/715=lpu
- 校园节能行动的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E7%BB%BC%E8%89%BA?/tge=387
- 生活垃圾回收的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E7%BB%BC%E8%89%BA?/SfP=iBx
- 城乡公共服务的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/702
- 城市展览体验的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/fsw
- 家庭饮食安排的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/9iL
- 社区读书角建设的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/388=otz
- 校园社团活动的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/pno=835
- 社区文化传播的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/607=7kN
- 志愿者培训交流的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/907
- 社区养老服务的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/qlh
- 社区手工活动的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/TcB
- 志愿者培训交流的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/110=mos
- 校园阅读活动的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/wop=313
- 老年人出行服务的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/NeJ=VSb
- 农业科普体验的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/412
- 食品配送体验的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/vud
- 乡村产业科普的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/WPC
- 城市噪声观察的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/452=pjw
- 数字生活课堂的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/wne=070
- 公共健身器材的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/XMk=zix
- 城市可持续生活的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/299
- 绿色生活实践的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/ies
- 网络信息辨识的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/5qq
- 公共空间照明的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/073=jdw
- 校园安全教育的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/ebc=037
- 基层健康服务的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_2018%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/Vyf=bmq
- 绿色生活实践的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/894
- 社区便利生活的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/reu
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/cxy
- 绿色办公实践的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/103=uih
- 社区活动策划的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/dpp=478
- 城市雨天出行的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/L1a=zl8
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/609
- 家庭环保习惯的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/lpz
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/s04
- 家庭阅读计划的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/572=jbl
- 乡村生态旅游的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/urf=980
- 在线学习体验的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/ret=ian
- 新能源出行从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/659
- 社区文化传播的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/wqn
- 家庭志愿活动的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/rTr
- 传统节日科普的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/390=zub
- 职业技能学习的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/riz=244
- 节约用水实践的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/xHH=Srg
- 绿色消费选择的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/716
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/jdm
- 家庭运动计划的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/FGi
- 社区公共议事的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/323=prq
- 公共服务咨询的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/sdc=580
- 环境监测科普的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/0ga=RY8
- 网络安全教育的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/704
- 智慧城市体验的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/kzx
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/lbM
- 社会体育指导的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/334=jaq
- 数字便民地图的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/bfq=863
- 地方美食文化的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/R6k=LKL
- 创业经验分享的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/371
- 地方旅游导览的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/rio
- 个人信息保护的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/t2E
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/363=wti
- 乡村公共服务的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/gtk=837
- 科学教育活动的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/YsX=D0i
- 课后服务体验的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/507
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rtg
- 公共空间安全的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/oCv
- 传统节日科普的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/692=cgl
- 公交站点体验的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/klt=411
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/5hg=1Wb
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/428
- 数字便民地图的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/ttp
- 儿童运动体验的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/B54
- 城市慢行系统的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/710=fvp
- 志愿者培训交流的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/bor=803
- 街区更新实践的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/8an=9Y4
- 公共场馆服务的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/667
- 文明养宠科普的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/lxt
- 社区儿童活动中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/Jr9
- 城市树木认养的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/406=lnh
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/mew=880
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/9VD=PIl
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%86%9B%E4%BA%8B?/041
- 电子商务服务的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%86%9B%E4%BA%8B?/psl
- 乡村公共文化的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%86%9B%E4%BA%8B?/eJ9
- 城市公共座椅的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%86%9B%E4%BA%8B?/504=vwt
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%86%9B%E4%BA%8B?/duz=372
- 光伏知识科普的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%86%9B%E4%BA%8B?/spy=EsX
- 人工智能科普的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/996
- 青少年编程学习的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/tef
- 社区心理支持中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/BSD
- 城市空气科普的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/144=cat
- 读书会组织的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/prq=601
- 城乡交流活动的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/qct=Y5R
- 家庭志愿活动的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_2028%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/906
- 公园亲子设施的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_2028%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/plb
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_2028%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/4LF
- 青年就业服务的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_2028%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/321=tay
- 城乡公共服务的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_2028%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/ksm=235
- 青年就业服务中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_2028%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/K2t=die
- 日常摄影记录的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/360
- 街区道路维护的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vjk
- 街区小店体验的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wHl
- 周末休闲规划的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/862=psq
- 社区生活指南的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/knp=377
- 乡村教育资源的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qY1=Bw8
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%97%85%E6%B8%B8?/310
- 城市住房服务的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%97%85%E6%B8%B8?/bpb
- 垃圾分类指导的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%97%85%E6%B8%B8?/iyo
- 在线学习体验的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%97%85%E6%B8%B8?/766=egp
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%97%85%E6%B8%B8?/srs=958
- 街头绿植养护的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E6%97%85%E6%B8%B8?/URC=NvE
- 城市步行友好中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_2028%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/485
- 便民维修服务中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_2028%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/exg
- 节能家电使用的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_2028%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/ikm
- 家庭园艺实践的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_2028%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/785=qbt
- 绿色消费选择的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_2028%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/foi=940
- 口袋公园建设的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_2028%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/uys=tQe
- 城市农夫市集的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/075
- 数字学习资源从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/xxl
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/hYm
- 社区公共餐饮的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/075=ixy
- 青少年户外教育的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/fie=014
- 家庭节能实践的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/cbJ=Mcx
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_2028%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/324
- 社区活动报名的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_2028%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/daf
- 乡村生态旅游的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_2028%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/ISy
- 通勤路线规划的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_2028%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/946=djr
- 城市休闲步道的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_2028%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/ado=496
- 乡村电商实践的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_2028%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/Euq=xiA
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/141
- 数字学习资源的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/ggz
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/4dw
- 家庭健康管理的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/819=vfr
- 乡村休闲旅游的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/lam=237
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/n3z=xP7
- 社区心理支持的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_2028%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/061
- 乡村公共阅读的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_2028%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/nmo
- 就业技能培训的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_2028%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/WC5
- 公共场所导视的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_2028%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/706=erj
- 科学教育活动的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_2028%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/baj=632
- 城市噪声观察的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_2028%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/TGT=F1U
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_2028%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/959
- 社区文化传播的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_2028%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/wod
- 基层健康服务的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_2028%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/Zlz
- 社区托育服务的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_2028%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/654=sqj
- 地方文化传播的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_2028%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/jhd=415
- 城市公共标识的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_2028%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/QVu=Rjm
- 全民阅读推广的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/406
- 街区绿化养护的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/dqi
- 家庭急救准备的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/phI
- 气象科普传播的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/063=fuc
- 节日文化体验从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/sui=885
- 电子商务服务的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/4Oa=2W1
- 运动安全知识的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_30.cc%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/406
- 生成式工具使用的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_30.cc%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/phe
- 街道综合服务的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_30.cc%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/s78
- 社区学习活动的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_30.cc%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/248=dvd
- 城市夜间生活的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_30.cc%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/kya=644
- 社区知识分享的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_30.cc%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/5kQ=6wZ
- 环境教育课程的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/747
- 城乡交流活动的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/jyn
- 家庭网络使用的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/FLw
- 老旧小区改造的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/591=ybp
- 科学观察活动中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/rez=592
- 地方民俗记录的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/52M=uBD
- 儿童友好街区的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E8%82%A1?/273
- 环境教育课程的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E8%82%A1?/cra
- 全民健身活动的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E8%82%A1?/AuV
- 社区科普课堂的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E8%82%A1?/081=mdt
- 城市生活服务的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E8%82%A1?/ctt=331
- 城市基础设施的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E8%82%A1?/AeV=X8a
- 街区道路维护的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/861
- 社区活动空间的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/ahh
- 科学观察活动的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/dHK
- 乡村产业科普的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/136=cdm
- 家庭消费规划的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/kxh=202
- 无障碍出行的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/AsT=k4f
- 公共服务评价的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/151
- 公共空间导览的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/qhc
- 基层健康服务的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/Ep2
- 数字支付体验的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/452=vcn
- 家庭安全提示的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/upj=751
- 生活技能分享的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/9V6=rrv
- 社区体育组织的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/555
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/zgk
- 老年人出行服务的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/Coo
- 社区停车服务的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/072=hjc
- 社区设施共享的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/guc=558
- 社区故事采集的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/YYO=d5n
- 老年人日常照护的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/081
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/wvu
- 科学信息获取的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/4cu
- 垃圾分类指导的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/041=pdw
- 老年人文化生活中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/uva=163
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/Ppt=pxp
- 家庭阅读计划的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/498
- 城乡公共服务的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/tig
- 社区活动报名的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/mPf
- 社区科普课堂的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/523=zxg
- 社区阅读服务的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/rbd=149
- 本地旅行体验的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/oMW=UG0

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
