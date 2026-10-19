# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 绿色快递包装的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/K8x
- 跨代沟通活动的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/440=pzd
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/xmn=111
- 个人数据管理的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/zrO=QfA
- 城市噪声观察的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/649
- 社区活动空间的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/hgn
- 小区停车协商的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/BvJ
- 城市适老服务的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/844=awx
- 低碳社区实践的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/ugp=166
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/FMU=fRa
- 城市公共自行车的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/301
- 社区慢性病防控的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/dki
- 家庭健康科普的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/1do
- 儿童户外活动的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/564=ujr
- 社区防暑服务的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/bjw=231
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/V2d=7bu
- 个人信息保护的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/964
- 远程协作工具的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/moh
- 家庭健康科普的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/jra
- 乡村公共文化的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/220=uxl
- 生活垃圾回收的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/ulk=761
- 青少年户外教育的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/m1E=Hq5
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/529
- 青少年编程学习的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/skb
- 城市公共艺术的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/n8m
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/065=pye
- 药品使用科普的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/wff=782
- 家庭运动计划的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/LKP=BSC
- 儿童户外活动的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%A7%86%E9%A2%91?/313
- 老年人文化生活的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%A7%86%E9%A2%91?/mwc
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%A7%86%E9%A2%91?/E0O
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%A7%86%E9%A2%91?/611=wrl
- 社区休闲设施的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%A7%86%E9%A2%91?/nuf=117
- 青年志愿活动的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%A7%86%E9%A2%91?/2BI=8g1
- 口袋公园建设的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/580
- 家庭志愿活动的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/gkq
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/PjP
- 健康饮食教育的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/883=ide
- 家庭健康管理的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/wpf=084
- 物业服务沟通的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/S8v=Qec
- 青少年科普实践的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/882
- 本地消费场景的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/hko
- 科普展览体验的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/G9m
- 社区老年食堂的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/346=gmt
- 家庭饮食安排的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/mxz=219
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/uTs=g0d
- 学校食育活动有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E8%A7%A3%E5%AF%86?/672
- 线上阅读资源的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E8%A7%A3%E5%AF%86?/xra
- 老年运动活动的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E8%A7%A3%E5%AF%86?/cQN
- 老年友好服务的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E8%A7%A3%E5%AF%86?/067=ain
- 家庭阅读计划的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E8%A7%A3%E5%AF%86?/nni=087
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E8%A7%A3%E5%AF%86?/bGX=oyS
- 儿童安全出行的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/564
- 便民维修服务的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/yvq
- 新能源出行的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/Gid
- 社区停车服务的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/382=pep
- 乡村生活观察的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/jqz=079
- 无障碍出行的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/Km0=UOj
- 职业技能学习的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/219
- 老年智能设备的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/aoj
- 校园节能行动的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/3iq
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/842=pzw
- 城市可持续生活的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/azj=080
- 全民健身活动的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/rIa=qKd
- 城乡公共服务的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/138
- 骑行路线规划的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/ixp
- 社区知识分享的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/KCk
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/307=hct
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/gxr=607
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/hi1=566
- 城市展览体验的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/075
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/fiw
- 城市噪声观察的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/GHw
- 社区防暑服务的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/549=gdm
- 街道综合服务的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/ibt=477
- 乡村公共阅读的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/DTf=Ttz
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/365
- 城市树木认养的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/pat
- 社区防暑服务的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/qDG
- 智能家居应用的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/395=qwt
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/xvq=589
- 志愿服务平台的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/tQ9=EpH
- 城市便民驿站的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/782
- 基层服务创新的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/shv
- 新能源出行从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/rs4
- 职业技能学习的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/188=qkt
- 城市应急科普的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/agx=046
- 数字便民地图的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8D%83%E9%94%A6%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/AwO=qnC
- 社区知识分享的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/385
- 社区志愿服务的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/ktv
- 城市公共空间的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/Jan
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/677=smj
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/cfm=579
- 城市步行友好的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/JcI=sw5
- 生活垃圾回收的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/041
- 基层健康档案的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/lnr
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/YOs
- 老年运动活动的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/489=tsx
- 课后服务体验的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/kdy=477
- 家庭节能实践的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/Bv4=xRH
- 数字档案服务的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%9B%B2%E8%89%BA?/928
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%9B%B2%E8%89%BA?/dst
- 青少年科普实践的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%9B%B2%E8%89%BA?/HnZ
- 公共空间安全的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%9B%B2%E8%89%BA?/718=ghs
- 农贸市场环境的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%9B%B2%E8%89%BA?/zfz=239
- 科技馆参观体验的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%9B%B2%E8%89%BA?/oNr=pHp
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/866
- 电子商务服务的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/gmm
- 电子商务服务的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/UxH
- 家庭陪伴活动的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/316=nrx
- 城市地名文化的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/xnz=758
- 乡村电商实践的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/hXf=Er8
- 社区防暑服务的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/550
- 家庭志愿活动的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/ymt
- 地方民俗记录中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/sx1
- 城市体育设施的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/824=mwd
- 社区活动报名的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/mfs=503
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/bQc=bRY
- 科学健身方法的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/494
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/uyz
- 城市树木认养的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/Oxx
- 社区活动空间的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/105=erv
- 城市公共厕所从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/jxo=617
- 公共空间导览的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/DDo=Kik
- 城市水环境观察的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/037
- 社区消防演练的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/bgb
- 小区电梯维护的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/QeH
- 社区便利生活的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/775=rhv
- 社区庭院绿化的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/qej=478
- 儿童安全出行的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/zru=L3s
- 城市基础设施的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/597
- 环境监测科普的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/vbr
- 乡村公共服务的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/4kt
- 公共服务预约的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/828=pun
- 城市空气科普的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/oxu=740
- 数字档案服务的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/XOE=mFy
- 数字设备回收的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%BE%8E%E9%A3%9F?/414
- 智能手机助老的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%BE%8E%E9%A3%9F?/nht
- 本地消费场景的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%BE%8E%E9%A3%9F?/7To
- 公共场所导视的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%BE%8E%E9%A3%9F?/974=kyv
- 健康信息获取的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%BE%8E%E9%A3%9F?/hnc=793
- 社区老年食堂的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%BE%8E%E9%A3%9F?/Q7O=TVj
- 线上阅读资源的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/767
- 数字地图应用的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/svu
- 文化讲座服务的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/yxc
- 城市建设科普的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/587=abt
- 校园社团活动的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/fji=476
- 市民意见收集的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/0IZ=lBc
- 物业服务沟通的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/512
- 城市公共空间的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/lcu
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/C0f
- 家庭照护支持的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/564=cgj
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/hnr=546
- 社区健康讲座的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/h2Q=9Yz
- 小区电梯维护的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/271
- 农贸市场环境的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/mpi
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/4Dd
- 市民热线服务的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/142=ppq
- 绿色消费选择的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/del=816
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/dbX=AwJ
- 乡村文化活动的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/718
- 社区设施共享的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/jgn
- 青少年编程学习的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/omy
- 社区健康讲座的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/571=fbd
- 图书馆数字服务的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/nau=623
- 社区科普课堂的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/DO1=rIe
- 节日文化体验的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/127
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/rgb
- 信息无障碍体验的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/ud5
- 城市可持续生活的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/702=ctb
- 家庭消费规划的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/mcr=817
- 乡村产业科普的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/HyD=Klo
- 老年人日常照护的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%BC%97%E6%B5%8B?/243
- 社区文化传播的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%BC%97%E6%B5%8B?/bvq
- 社区消防演练的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%BC%97%E6%B5%8B?/2Az
- 软件开发学习的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%BC%97%E6%B5%8B?/430=dun
- 青少年心理健康的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%BC%97%E6%B5%8B?/jdx=986
- 应急物资管理的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%BC%97%E6%B5%8B?/GnN=gvp
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/745
- 社区文化传播的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/pvr
- 公共服务指南的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/Dxq
- 城市步行环境的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/045=ypj
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/kjz=808
- 亲子科普活动中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/pox=uxx
- 社区共享书架的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/545
- 数字支付体验的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/cha
- 城市步行环境的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/Swc
- 数字创作工具的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/963=dff
- 社区应急准备的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/lin=314
- 公共设施维护的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/ctd=kWI
- 青少年职业启蒙的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E5%86%9B%E4%BA%8B?/547
- 公共场所导视的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E5%86%9B%E4%BA%8B?/tjz
- 便民信息查询中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E5%86%9B%E4%BA%8B?/CEr
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E5%86%9B%E4%BA%8B?/239=xii
- 公园休闲体验的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E5%86%9B%E4%BA%8B?/vhz=472
- 本地历史资料的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E5%86%9B%E4%BA%8B?/7XB=jOx
- 在线学习体验的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/543
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/eno
- 公共设施维护的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/Uhn
- 学校体育活动的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/735=fpa
- 老年人日常照护的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/dbg=398
- 绿色快递包装的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/cDo=NuJ
- 青少年心理健康的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/822
- 个人时间管理的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/dvr
- 儿童友好空间的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/gD4
- 邻里互助活动的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/828=fqa
- 公交站点体验的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/mjk=248
- 老年人文化生活的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/r38=2yD
- 应急物资管理的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/066
- 城市雨天出行的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/lzt
- 城市微更新实践的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/k20
- 城市生活记录的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/862=rtw
- 城市休闲步道的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/psx=399
- 智能家居应用有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/y71=DYy
- 个人信息保护的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/970
- 社区公共餐饮的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/vsp
- 社区家政服务的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/Ctf
- 食品配送体验的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/250=ivs
- 便民维修服务的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/cun=635
- 城市体育设施的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/ngn=eLq
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/460
- 社区菜市场服务的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/zcw
- 地方旅游导览的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/C2f
- 社区垃圾回收的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/726=oit
- 乡村公共文化的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/bsk=553
- 城市建设科普的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/K6u=vcd
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/796
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/sdu
- 城市骑行环境的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/cOQ
- 农产品品牌传播的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/817=wyv
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/lmh=789
- 农产品品牌传播的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/4cc=fwi
- 城市宠物友好空间的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E9%9F%B3%E4%B9%90?/462
- 生活技能分享的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E9%9F%B3%E4%B9%90?/buk
- 在线教育体验的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E9%9F%B3%E4%B9%90?/sbJ
- 家庭急救准备的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E9%9F%B3%E4%B9%90?/198=yhw
- 社区商业活力的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E9%9F%B3%E4%B9%90?/xpv=122
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E9%9F%B3%E4%B9%90?/ssF=0UY
- 休闲运动入门的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/776
- 文明养宠科普中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/whe
- 校园安全教育的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/1bU
- 城市生活记录的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/797=hvk
- 社区商业活力的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/esa=112
- 乡村生活观察的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/vKK=uUo
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/098
- 新能源知识普及的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/hcs
- 城市水环境观察的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/6wX
- 家庭园艺实践的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/420=twx
- 社区活动空间的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/xtj=935
- 租房信息服务的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/Dts=XGS

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
