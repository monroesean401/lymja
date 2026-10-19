# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 数字阅读服务的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_08vip%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/YZB
- 公园休闲体验的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_08vip%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/800=gnr
- 社区读书角建设从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_08vip%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/yns=008
- 青少年科技社团的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_08vip%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/Lme=SYw
- 节约用水实践的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_08vip%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/192
- 社区读书角建设的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_08vip%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/uob
- 本地历史资料的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_08vip%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/Vg0
- 智能手机助老的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_08vip%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/596=vjg
- 家庭环保行动的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_08vip%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/rrj=051
- 周末休闲规划的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_08vip%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/hD2=W0u
- 公共文化活动的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_08vip%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/377
- 社区停车服务的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_08vip%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/ayz
- 远程协作工具的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_08vip%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/T9c
- 城市绿色交通的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_08vip%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/421=hfb
- 零废弃生活尝试的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_08vip%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/udm=139
- 网络信息辨识的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_08vip%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/ZJN=3iR
- 电子商务服务的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_08vip%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/297
- 校园安全教育的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_08vip%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/xcf
- 城市展览体验的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_08vip%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/1aj
- 社区修缮行动的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_08vip%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/244=xak
- 电动汽车充电的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_08vip%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/etc=509
- 租房信息服务的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_08vip%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/QRo=ejb
- 社区消防演练的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_08%E5%BE%AE%E8%81%8A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/197
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_08%E5%BE%AE%E8%81%8A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/fmv
- 城市慢行系统的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_08%E5%BE%AE%E8%81%8A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/av4
- 生活技能分享的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_08%E5%BE%AE%E8%81%8A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/697=bhu
- 公共服务指南的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_08%E5%BE%AE%E8%81%8A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/ovc=105
- 家庭阅读计划的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_08%E5%BE%AE%E8%81%8A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%9B%86?/fAI=ctA
- 文化讲座服务的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_08%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/151
- 居家适老化改造的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_08%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/bxy
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_08%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/qg2
- 家庭饮食安排的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_08%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/578=vdj
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_08%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/mcm=727
- 老年运动活动的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_08%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/xaU=uPU
- 社区科普课堂的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/182
- 绿色校园实践的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/cgu
- 智慧停车服务的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/tur
- 城市地名文化的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/741=fop
- 城市公共自行车的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/abt=998
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/jet=Dur
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/411
- 街区小店体验的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/aar
- 健康饮食教育的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/Ucc
- 居家防滑改造的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/138=krj
- 家庭安全提示的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/ihe=047
- 乡村文化活动的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/cGd=K42
- 本地消费场景中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/909
- 小区电梯维护的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/ryc
- 城市公共标识的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/tFr
- 数字创意课程的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/588=aln
- 老年人文化生活的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/ruo=662
- 城乡公共服务的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/6mK=Z4x
- 生成式工具使用的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/588
- 居家防滑改造的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/lki
- 乡村阅读空间的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/IB1
- 数字生活课堂的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/134=tpr
- 社区垃圾回收的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/enb=374
- 青年志愿活动的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/AFE=Ncg
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_08%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/951
- 城市基础设施的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_08%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/kyg
- 在线学习体验的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_08%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/MMl
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_08%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/452=qjb
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_08%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/fih=511
- 公共文化活动的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_08%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/sEW=5dz
- 家庭运动计划的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/413
- 公交站点体验的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/qya
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/FsB
- 个人信息保护的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/880=mow
- 软件开发学习的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/gdy=725
- 社区活动策划的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/UTK=GVQ
- 乡村生态观察的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E7%BD%91_360%E5%9B%BD%E5%86%85?/540
- 家庭养老规划的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E7%BD%91_360%E5%9B%BD%E5%86%85?/axw
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E7%BD%91_360%E5%9B%BD%E5%86%85?/eGR
- 应急物资管理的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E7%BD%91_360%E5%9B%BD%E5%86%85?/911=lbs
- 农业科普体验的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E7%BD%91_360%E5%9B%BD%E5%86%85?/gwi=922
- 老年人日常照护的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E7%BD%91_360%E5%9B%BD%E5%86%85?/4pv=mjw
- 青少年职业启蒙的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/034
- 文化讲座服务的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/jnc
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/8oI
- 垃圾分类指导的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/037=qfg
- 远程协作工具的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/wnd=128
- 社区教育资源的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/cfi=9Ke
- 家庭急救准备的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/913
- 社区养老服务的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/pbt
- 图书馆数字服务的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/bib
- 急救知识普及的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/945=evf
- 本地旅行体验的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/ncs=615
- 农产品消费体验的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_08%E5%BE%AE%E8%81%8A-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/GfS=gEb
- 医院导诊服务的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_08%E5%BE%AE%E8%81%8A-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/886
- 城市空气科普的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_08%E5%BE%AE%E8%81%8A-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/ahz
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_08%E5%BE%AE%E8%81%8A-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/FVR
- 家庭陪伴活动的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_08%E5%BE%AE%E8%81%8A-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/182=yqw
- 城市共享单车的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_08%E5%BE%AE%E8%81%8A-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/gkx=611
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_08%E5%BE%AE%E8%81%8A-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/g1t=GIz
- 城市博物馆活动的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_08%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/096
- 数字学习资源的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_08%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/lrv
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_08%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/ltR
- 周末休闲规划的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_08%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/631=qch
- 公共服务指南的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_08%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/ngj=078
- 城市游园体验的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_08%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/Fwv=zOG
- 职业技能学习的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_08%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/074
- 公共服务咨询的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_08%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/nyb
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_08%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/a4w
- 乡村公共阅读的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_08%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/653=dxh
- 城市公共空间的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_08%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/upq=749
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_08%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/EZD=ar1
- 社区故事采集的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/658
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/fti
- 基层健康服务的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/kLp
- 社区应急准备的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/269=hqu
- 社区活动空间中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/kvv=957
- 机器学习入门的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_08%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/6BN=iDm
- 社区协商议事的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_08%E5%BE%AE%E8%81%8A-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/764
- 校园节能行动的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_08%E5%BE%AE%E8%81%8A-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/dkb
- 数字艺术创作的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_08%E5%BE%AE%E8%81%8A-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/UFs
- 家庭饮食安排的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_08%E5%BE%AE%E8%81%8A-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/981=kte
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_08%E5%BE%AE%E8%81%8A-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/omu=226
- 社会体育指导的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_08%E5%BE%AE%E8%81%8A-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/Wl6=XJu
- 城市生活记录的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_08%E5%BE%AE%E8%81%8A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E7%BE%8E%E5%A6%86?/426
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_08%E5%BE%AE%E8%81%8A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E7%BE%8E%E5%A6%86?/lyh
- 社区体育组织的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_08%E5%BE%AE%E8%81%8A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E7%BE%8E%E5%A6%86?/BKT
- 城市绿道建设中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_08%E5%BE%AE%E8%81%8A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E7%BE%8E%E5%A6%86?/002=glm
- 个人数据管理的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_08%E5%BE%AE%E8%81%8A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E7%BE%8E%E5%A6%86?/tfm=514
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_08%E5%BE%AE%E8%81%8A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E7%BE%8E%E5%A6%86?/62G=5BA
- 乡村教育资源中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_08%E5%BE%AE%E8%81%8A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/105
- 青年就业服务的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_08%E5%BE%AE%E8%81%8A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/tqh
- 社区商业活力的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_08%E5%BE%AE%E8%81%8A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/89D
- 公共服务评价的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_08%E5%BE%AE%E8%81%8A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/777=nnv
- 公共卫生设施的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_08%E5%BE%AE%E8%81%8A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/pih=006
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_08%E5%BE%AE%E8%81%8A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/AuL=cZe
- 城市生活服务的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_08%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/319
- 居家防滑改造的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_08%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/keh
- 市民热线服务的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_08%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/OAa
- 食品安全科普的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_08%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/979=myv
- 城市人文观察的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_08%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/awb=185
- 城市慢跑路线的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_08%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/nrI=XBF
- 气象科普传播的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_08%E5%BE%AE%E8%81%8A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%BE%8E%E9%A3%9F?/935
- 公共空间安全中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_08%E5%BE%AE%E8%81%8A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%BE%8E%E9%A3%9F?/fky
- 街区更新实践的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_08%E5%BE%AE%E8%81%8A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%BE%8E%E9%A3%9F?/wwJ
- 新能源出行的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_08%E5%BE%AE%E8%81%8A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%BE%8E%E9%A3%9F?/905=tzy
- 社区手工活动的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_08%E5%BE%AE%E8%81%8A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%BE%8E%E9%A3%9F?/kva=911
- 城乡公共服务的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_08%E5%BE%AE%E8%81%8A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%BE%8E%E9%A3%9F?/ChV=jYq
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_08%E5%BE%AE%E8%81%8A-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%8E%A2%E5%BA%97?/568
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_08%E5%BE%AE%E8%81%8A-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%8E%A2%E5%BA%97?/qfc
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_08%E5%BE%AE%E8%81%8A-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%8E%A2%E5%BA%97?/7gu
- 社区活动策划的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_08%E5%BE%AE%E8%81%8A-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%8E%A2%E5%BA%97?/353=nku
- 青少年户外教育的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_08%E5%BE%AE%E8%81%8A-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%8E%A2%E5%BA%97?/hfi=066
- 家庭消费规划的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_08%E5%BE%AE%E8%81%8A-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%8E%A2%E5%BA%97?/fVN=fLJ
- 急救知识普及的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/529
- 家庭教育交流的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/wpf
- 城市展览体验的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/J9O
- 城市运动公园的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/974=jhc
- 城市水环境观察的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/zxt=213
- 公共图书馆服务的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/rnj=Uon
- 街区更新实践的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_100%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/912
- 就业技能培训中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_100%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/wmt
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_100%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/Kql
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_100%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/282=sql
- 街区道路维护的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_100%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/qpe=624
- 节能家电使用的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_100%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/rLc=sjE
- 家庭节能设备的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/614
- 青少年户外教育的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/kuw
- 社区手工活动的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/wdl
- 乡村生态旅游的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/609=lpw
- 城市水环境观察的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/cxi=097
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/CvT=qbC
- 农村环境治理的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/306
- 城市文明出行的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/ujs
- 户外活动组织的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/Z94
- 开放式学习空间的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/746=prx
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/kzv=329
- 药品使用科普的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/RQX=lao
- 志愿服务平台的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/758
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/esu
- 公共服务数字化的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/kCf
- 社区绿色空间的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/371=ism
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/won=441
- 城市公共空间的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/08o=HvM
- 数字生活课堂的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/957
- 环境监测科普的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/toi
- 健康信息获取的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/AN0
- 儿童户外活动的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/725=gwi
- 应急物资管理的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/uht=395
- 本地消费场景的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/q2Z=ljd
- 非遗体验活动的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%B1%BD%E8%BD%A6?/394
- 数字便民地图从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%B1%BD%E8%BD%A6?/gmx
- 家庭网络使用的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%B1%BD%E8%BD%A6?/G1E
- 社区休闲设施的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%B1%BD%E8%BD%A6?/199=fij
- 社区体育组织的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%B1%BD%E8%BD%A6?/sdf=888
- 科学睡眠习惯的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%B1%BD%E8%BD%A6?/kfB=sUY
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/784
- 城市游园体验的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/ieq
- 城市公共自行车的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/FpB
- 机器人科普活动的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/436=itm
- 数字课堂应用的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/thh=946
- 公共文化活动中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/xpj=JyP
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/644
- 公共卫生宣传的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/jed
- 安全出行教育的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/kvo
- 图书馆亲子空间的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/173=jga
- 老旧小区改造的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/zpk=335
- 应急物资管理的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/06W=INI
- 图书馆活动策划的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/099
- 节能家电使用的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/vce
- 口袋公园建设中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/KHu
- 社区便民服务的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/324=csg
- 家庭照护支持的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ahl=993
- 家庭安全提示的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/vPW=XRU
- 物业服务沟通的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/446
- 公共设施维护的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/ojh
- 城市文明出行的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/OgN
- 公共服务沟通的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/844=pck
- 城市应急广播的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/sxc=171
- 本地历史资料的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/HVV=QIy
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/823
- 家庭网络使用的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/cac
- 本地消费场景的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/jW2
- 传统手工艺体验的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/383=gaq
- 社区活动报名的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/anr=322
- 城市文明实践的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/2lM=ygJ
- 社区科普课堂的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_100%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/745
- 数字档案服务的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_100%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/tsa
- 家庭节能设备的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_100%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/Psn
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_100%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/333=zva
- 家庭用电安全的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_100%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/cqk=926
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_100%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/Ee4=RBf
- 机器学习入门的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/940
- 校园阅读活动的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/nam
- 绿色生活实践的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/8T1
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/239=ooj
- 居家防滑改造的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/bsx=132
- 城市适老服务的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/H4H=zGy
- 老年智能设备的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/559
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/xot
- 小微企业服务的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/jf4
- 市民热线服务的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/012=idb
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/czr=387
- 城市夜间生活的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/5Mq=TF8
- 社区快递服务的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/844
- 开放数据应用的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/rsh
- 社区活动空间的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/PIw
- 社区菜市场服务的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/712=jkr
- 城市基础设施有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/hpx=983
- 城市骑行环境的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/42n=mJO
- 城市休闲步道中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/055
- 通勤路线规划的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/tvj
- 社区运动空间的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/sBs
- 乡村文化活动的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/172=bqm
- 个人时间管理的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/pjm=845
- 生活垃圾回收的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/ZCU=2rJ

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
