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

- 本地旅行体验的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_2828%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/598
- 城市生活服务的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_2828%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/cjb
- 社区公共议事的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_2828%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/8t8
- 乡村阅读空间的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_2828%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/632=una
- 气象科普传播的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_2828%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/yoo=432
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_2828%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/C9y=Mod
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_2828%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/915
- 社区快递服务的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_2828%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/pwr
- 家庭用电安全的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_2828%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/NZ8
- 青年志愿活动的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_2828%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/531=yta
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_2828%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/zgo=640
- 城市人文观察的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_2828%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/baC=5jf
- 城市运动公园的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_2828%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/512
- 绿色校园实践的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_2828%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/unm
- 机器人科普活动的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_2828%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/UPv
- 绿色出行服务的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_2828%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/030=cln
- 开放式学习空间的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_2828%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/eap=703
- 公共空间照明的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_2828%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/yQu=fy8
- 个人数据管理的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/613
- 城市步行环境的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/lxu
- 电子商务服务的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/W9I
- 城市水环境观察的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/528=ikt
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/hwm=913
- 环境教育课程的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_2028%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/r9W=nSt
- 绿色建筑理念的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/231
- 城市博物馆活动的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/qos
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/yo9
- 机器人科普活动的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/203=crf
- 农业科普体验的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/pjy=768
- 城市应急广播的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/iQZ=xNm
- 社区活动策划的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_30cc%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/789
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_30cc%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/qzw
- 健康步道使用的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_30cc%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/58S
- 远程协作工具的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_30cc%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/730=wta
- 公共设施使用的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_30cc%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/deo=288
- 低碳社区实践的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_30cc%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/hQd=Orj
- 儿童安全出行的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_30cc%E5%A8%B1%E4%B9%90%E6%9C%80%E6%96%B0%E7%89%88%E6%9B%B4%E6%96%B0%E4%BA%86%E4%BB%80%E4%B9%88%E6%96%B0%E5%8A%9F%E8%83%BD_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/597
- 街道综合服务的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_30cc%E5%A8%B1%E4%B9%90%E6%9C%80%E6%96%B0%E7%89%88%E6%9B%B4%E6%96%B0%E4%BA%86%E4%BB%80%E4%B9%88%E6%96%B0%E5%8A%9F%E8%83%BD_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/nql
- 社区便民服务的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_30cc%E5%A8%B1%E4%B9%90%E6%9C%80%E6%96%B0%E7%89%88%E6%9B%B4%E6%96%B0%E4%BA%86%E4%BB%80%E4%B9%88%E6%96%B0%E5%8A%9F%E8%83%BD_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/2Vz
- 社区共享书架的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_30cc%E5%A8%B1%E4%B9%90%E6%9C%80%E6%96%B0%E7%89%88%E6%9B%B4%E6%96%B0%E4%BA%86%E4%BB%80%E4%B9%88%E6%96%B0%E5%8A%9F%E8%83%BD_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/249=ymz
- 社区快递服务的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_30cc%E5%A8%B1%E4%B9%90%E6%9C%80%E6%96%B0%E7%89%88%E6%9B%B4%E6%96%B0%E4%BA%86%E4%BB%80%E4%B9%88%E6%96%B0%E5%8A%9F%E8%83%BD_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/lmo=764
- 居家适老化改造的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_30cc%E5%A8%B1%E4%B9%90%E6%9C%80%E6%96%B0%E7%89%88%E6%9B%B4%E6%96%B0%E4%BA%86%E4%BB%80%E4%B9%88%E6%96%B0%E5%8A%9F%E8%83%BD_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/9vC=8mP
- 食品安全科普的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_30cc%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/790
- 电动汽车充电的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_30cc%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/mho
- 休闲运动入门的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_30cc%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/l8F
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_30cc%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/277=wih
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_30cc%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/nxd=501
- 机器人科普活动的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_30cc%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/LDe=maj
- 文明养宠科普的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30cc%E5%A8%B1%E4%B9%90APP%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/977
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30cc%E5%A8%B1%E4%B9%90APP%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/xmt
- 气象科普传播的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30cc%E5%A8%B1%E4%B9%90APP%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/7zJ
- 公共空间照明的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30cc%E5%A8%B1%E4%B9%90APP%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/605=utz
- 数字创意课程的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30cc%E5%A8%B1%E4%B9%90APP%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/hvh=807
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30cc%E5%A8%B1%E4%B9%90APP%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/BBY=XeE
- 社区文化传播的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_30%E5%A8%B1%E4%B9%90Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/434
- 在线学习体验的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_30%E5%A8%B1%E4%B9%90Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/tvq
- 亲子科普活动中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_30%E5%A8%B1%E4%B9%90Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/q1R
- 社区快递服务中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_30%E5%A8%B1%E4%B9%90Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/723=zlc
- 社区休闲设施的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_30%E5%A8%B1%E4%B9%90Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/qjx=594
- 绿色生活实践的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_30%E5%A8%B1%E4%B9%90Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/Xc9=Xha
- 社区快递服务的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_cc%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/784
- 数字艺术创作的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_cc%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/hbd
- 家庭收纳实践的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_cc%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/zpO
- 社区协商议事的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_cc%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/214=oua
- 老年友好服务的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_cc%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/pot=188
- 城市地名文化的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_cc%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/OBQ=X34
- 机器学习入门的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E7%95%8C%E9%9D%A2%E6%96%87%E5%8C%96?/977
- 文明养宠科普的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E7%95%8C%E9%9D%A2%E6%96%87%E5%8C%96?/mwe
- 运动安全知识中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E7%95%8C%E9%9D%A2%E6%96%87%E5%8C%96?/fbo
- 社区停车服务的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E7%95%8C%E9%9D%A2%E6%96%87%E5%8C%96?/733=bod
- 城市应急科普的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E7%95%8C%E9%9D%A2%E6%96%87%E5%8C%96?/grp=140
- 机器学习入门的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E7%95%8C%E9%9D%A2%E6%96%87%E5%8C%96?/dOM=n8o
- 公共空间安全中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/779
- 公共交通信息服务的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/uot
- 城市适老服务的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/ZQi
- 公园休闲体验的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/259=yxu
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/cvg=297
- 家庭健康管理的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/Q7a=hLG
- 公交无障碍服务的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/808
- 家庭教育交流中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/cbu
- 全民阅读推广的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/DaR
- 社区环保活动的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/556=mrj
- 公共卫生设施的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/mto=074
- 个人信息保护的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/yxz=Yaj
- 社区应急准备的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90%E8%83%BD%E6%8F%90%E5%88%B0%E6%AC%BE%E5%90%97_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/802
- 城市住房服务的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90%E8%83%BD%E6%8F%90%E5%88%B0%E6%AC%BE%E5%90%97_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/afh
- 非遗体验活动的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90%E8%83%BD%E6%8F%90%E5%88%B0%E6%AC%BE%E5%90%97_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/o1u
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90%E8%83%BD%E6%8F%90%E5%88%B0%E6%AC%BE%E5%90%97_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/496=mne
- 农贸市场环境的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90%E8%83%BD%E6%8F%90%E5%88%B0%E6%AC%BE%E5%90%97_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/lnj=543
- 骑行路线规划的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90%E8%83%BD%E6%8F%90%E5%88%B0%E6%AC%BE%E5%90%97_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/qL1=Cu2
- 老年学习活动的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_30%E5%A8%B1%E4%B9%90%E4%BF%A1%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E6%94%B6%E8%97%8F?/282
- 科普展览体验的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_30%E5%A8%B1%E4%B9%90%E4%BF%A1%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E6%94%B6%E8%97%8F?/eid
- 儿童友好空间的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_30%E5%A8%B1%E4%B9%90%E4%BF%A1%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E6%94%B6%E8%97%8F?/bjZ
- 社区老年食堂的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_30%E5%A8%B1%E4%B9%90%E4%BF%A1%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E6%94%B6%E8%97%8F?/433=zur
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_30%E5%A8%B1%E4%B9%90%E4%BF%A1%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E6%94%B6%E8%97%8F?/zoo=053
- 科学观察活动的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_30%E5%A8%B1%E4%B9%90%E4%BF%A1%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E6%94%B6%E8%97%8F?/6L7=lyf
- 城市公共空间的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E6%9C%80%E6%96%B0%E7%89%88_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/383
- 城市农夫市集的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E6%9C%80%E6%96%B0%E7%89%88_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/afs
- 就业技能培训的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E6%9C%80%E6%96%B0%E7%89%88_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/ZOa
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E6%9C%80%E6%96%B0%E7%89%88_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/280=bzt
- 个人时间管理的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E6%9C%80%E6%96%B0%E7%89%88_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/yyx=844
- 乡村电商实践从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E6%9C%80%E6%96%B0%E7%89%88_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/aTC=Mpx
- 劳动教育实践的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_3378%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/519
- 家庭网络使用的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_3378%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/msi
- 智能手机助老的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_3378%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/Bvc
- 城乡公共服务的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_3378%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/829=qvr
- 科学观察活动的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_3378%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/qun=349
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_3378%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/SKR=MQR
- 健康饮水科普的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_7733%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BD%93%E8%82%B2?/808
- 家庭健康科普的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_7733%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BD%93%E8%82%B2?/mbh
- 社区知识分享的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_7733%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BD%93%E8%82%B2?/G8C
- 地方民俗记录的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_7733%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BD%93%E8%82%B2?/006=fqe
- 城市夜间生活的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_7733%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BD%93%E8%82%B2?/smh=041
- 终身学习资源的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_7733%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BD%93%E8%82%B2?/yPB=MJ5
- 城市步行环境的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_7731%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/251
- 城乡公共服务的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_7731%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/oly
- 老年友好服务的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_7731%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/ugI
- 课后服务体验的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_7731%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/734=maw
- 街区小店体验的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_7731%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/dbn=114
- 校园社团活动的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_7731%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/uuk=Vx5
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_733%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/170
- 全民阅读推广的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_733%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/osd
- 社区知识分享的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_733%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/SyQ
- 乡村公共服务的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_733%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/807=cau
- 图书馆亲子空间的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_733%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/ink=888
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_733%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/ZG7=8us
- 食品安全科普的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/597
- 节假日出行安排的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lei
- 街头绿植养护的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/g9r
- 城市骑行环境的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/546=kdg
- 智慧城市体验的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wzl=553
- 地方文化传播的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_3378%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/SBU=t2E
- 社区读书角建设的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_3625%E5%85%A8%E6%B0%91%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/376
- 公共图书馆服务的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_3625%E5%85%A8%E6%B0%91%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/egf
- 城市绿道建设的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_3625%E5%85%A8%E6%B0%91%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/9gt
- 城市运动公园的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_3625%E5%85%A8%E6%B0%91%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/995=ukw
- 公共空间休憩的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_3625%E5%85%A8%E6%B0%91%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/nlk=099
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_3625%E5%85%A8%E6%B0%91%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/UAo=2Js
- 网络信息辨识的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/563
- 节气饮食文化有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/mqc
- 社区知识分享的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/CrY
- 城市公共标识的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/900=jcp
- 乡村生态观察的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/dpe=375
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/U6C=x4J
- 社区协商议事的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%9B%86?/009
- 社区活动报名的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%9B%86?/bno
- 科学观察活动的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%9B%86?/syc
- 社区便民集市的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%9B%86?/481=lrb
- 租房信息服务的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%9B%86?/orb=197
- 开放数据应用的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%9B%86?/VhE=ugQ
- 儿童友好空间的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/645
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/phl
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/g7E
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/461=rga
- 城市公共厕所的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/unr=776
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/B5S=IhL
- 智慧城市体验的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/543
- 学校食育活动中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/lpd
- 数字创意课程的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/0Xy
- 街区更新实践的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/350=ofj
- 城市微更新实践的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/bid=112
- 数字阅读服务的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/kKx=x7l
- 全民健身活动有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_6295VIP%E5%85%A8%E6%B0%91%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/071
- 儿童安全出行的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_6295VIP%E5%85%A8%E6%B0%91%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/crn
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_6295VIP%E5%85%A8%E6%B0%91%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/O1y
- 科学健身方法的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_6295VIP%E5%85%A8%E6%B0%91%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/022=olm
- 个人信息保护的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_6295VIP%E5%85%A8%E6%B0%91%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/nah=866
- 城市住房服务的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_6295VIP%E5%85%A8%E6%B0%91%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/MZE=qpZ
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/286
- 职业技能学习的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/isy
- 科普展览体验的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/yy9
- 传统节日科普的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/855=ven
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/zea=507
- 食品安全科普的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/jmT=6BY
- 灵活就业交流的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3625%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/983
- 通勤路线规划的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3625%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/grs
- 城市宠物友好空间中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3625%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/QbP
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3625%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/198=stn
- 校园节能行动的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3625%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/fjl=557
- 数字便民地图的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3625%E5%85%A8%E6%B0%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/FsU=V2h
- 城市可持续生活的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/780
- 社区便利生活的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/utt
- 社区邻里服务中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/KhM
- 城市可持续生活的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/241=lwa
- 社区停车服务的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/eae=411
- 小区电梯维护的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/HZb=V9Z
- 公共场所导视的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8v3%E6%96%B0%E9%A1%B5%E9%9D%A2_360%E6%85%A7%E7%9C%BC?/186
- 街区绿化养护的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8v3%E6%96%B0%E9%A1%B5%E9%9D%A2_360%E6%85%A7%E7%9C%BC?/amm
- 数字政务体验的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8v3%E6%96%B0%E9%A1%B5%E9%9D%A2_360%E6%85%A7%E7%9C%BC?/auO
- 城市公共标识的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8v3%E6%96%B0%E9%A1%B5%E9%9D%A2_360%E6%85%A7%E7%9C%BC?/116=hlz
- 社区老年食堂的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8v3%E6%96%B0%E9%A1%B5%E9%9D%A2_360%E6%85%A7%E7%9C%BC?/vvl=161
- 城市文明实践的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8v3%E6%96%B0%E9%A1%B5%E9%9D%A2_360%E6%85%A7%E7%9C%BC?/CRe=8Ei
- 医院导诊服务的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/029
- 社区修缮行动的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/jwt
- 城乡交流活动的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/zC1
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/195=qfk
- 生活技能分享的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/zrc=171
- 老年智能设备的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/PXe=gCx
- 城乡交流活动的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/810
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/loz
- 社区互助网络的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/2SO
- 公共服务预约的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/074=yjv
- 老年数字阅读的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/igm=814
- 绿色校园实践的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/9mN=ue7
- 小微企业服务的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/132
- 市民意见收集的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/hia
- 乡村电商实践的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/qdx
- 小区停车协商的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/709=nwr
- 公共场所导视的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/guf=925
- 青少年科技社团的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/KnL=OAi
- 城市空气科普的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_49%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/650
- 公共空间休憩的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_49%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/mdx
- 城市雨天出行的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_49%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/g4e
- 家庭节能实践的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_49%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/998=kpq
- 生活服务数字化的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_49%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/dfd=677
- 家庭节能实践的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_49%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/M9j=OKF
- 地方旅游导览的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_506%E4%B8%87%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/173
- 数字创意课程的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_506%E4%B8%87%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/qos
- 数字课堂应用的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_506%E4%B8%87%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/9Kk
- 数字生活课堂的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_506%E4%B8%87%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/422=tbn
- 城市雨天出行的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_506%E4%B8%87%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/fde=287
- 家庭环保习惯的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_506%E4%B8%87%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/Fj4=ZST
- 公共服务咨询的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6168%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/262
- 数字政务体验的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6168%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/nzv
- 社区活动空间的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6168%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/PNk
- 家庭急救准备的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6168%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/806=wez
- 便民维修服务的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6168%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/lir=738
- 数字支付体验的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6168%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/7PN=9dm
- 食品安全科普的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E6%99%A8%E6%8A%A5?/356
- 数据分析入门的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E6%99%A8%E6%8A%A5?/chc
- 气象科普传播的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E6%99%A8%E6%8A%A5?/XZ6
- 社区养老服务的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E6%99%A8%E6%8A%A5?/488=fps
- 农产品消费体验的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E6%99%A8%E6%8A%A5?/pni=071
- 环境监测科普的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E6%99%A8%E6%8A%A5?/Q9w=Dmo
- 老年智能设备的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_61661%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/596
- 数字生活课堂的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_61661%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/son
- 社区应急准备的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_61661%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/CAx
- 老年运动活动的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_61661%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/583=uyn
- 数字课堂应用的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_61661%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/pdy=682
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_61661%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/ZXH=OP0
- 环境教育课程的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_61%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/604
- 家庭环保习惯的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_61%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/qps
- 老年人日常照护的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_61%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/YeM
- 公共卫生宣传的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_61%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/327=blh
- 节能生活方式的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_61%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/qyh=111
- 社会体育指导的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_61%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/PhZ=u9C
- 环境教育课程的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/652
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/oqn
- 城市夜间照明的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/4RW
- 绿色校园实践的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_61%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E5%8F%B7%E7%A0%81%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/184=otj

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
