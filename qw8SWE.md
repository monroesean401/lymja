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

- 城市空气科普的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360%E8%A6%81%E9%97%BB?/Yyz
- 老年人文化生活的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360%E8%A6%81%E9%97%BB?/292=pcm
- 社区活动策划的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360%E8%A6%81%E9%97%BB?/kil=111
- 社区菜市场服务的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360%E8%A6%81%E9%97%BB?/1Wh=KLg
- 老年人文化生活的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/177
- 城市农夫市集的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/cum
- 老年人出行服务的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/Nqi
- 家庭网络使用的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/981=eou
- 老年人出行服务的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/jse=282
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/RHT=lzX
- 社区儿童活动的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/198
- 老年人日常照护的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/fjc
- 数字课堂应用的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/9Dm
- 电动汽车充电的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/869=wtv
- 个人数据管理的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/oef=044
- 社区艺术活动的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/YCr=EWB
- 社区学习活动的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/988
- 文化场馆预约的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/epo
- 社区应急准备的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/RHM
- 全民健身活动的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/875=rlr
- 新能源知识普及的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/lju=186
- 智慧停车服务的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/y3A=knc
- 社区心理支持的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_52888%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/035
- 城市共享单车的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_52888%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/hti
- 休闲运动入门从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_52888%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/85C
- 社区故事采集的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_52888%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/262=qcy
- 城市生活记录的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_52888%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/qwz=479
- 网络安全教育的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_52888%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/1Im=07q
- 老年运动活动的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/349
- 城市基础设施的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/iwb
- 新能源出行的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/aGu
- 社区应急准备的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/130=vfw
- 数字支付体验的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/rwg=553
- 城市树木认养的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/SGf=EVc
- 社区教育资源的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/539
- 远程协作工具的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/rcv
- 小区停车协商的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/WtZ
- 地方民俗记录的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/259=bdn
- 乡村教育资源的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/vnp=052
- 社区活动空间的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/MHd=J4r
- 信息无障碍体验的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/928
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/spk
- 物业服务沟通的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/PGl
- 儿童友好空间的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/742=ncy
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/pow=982
- 数字资源检索的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/QgN=Kqq
- 城市公共座椅的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/593
- 城市展览体验的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/qrc
- 家庭阅读计划的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/Nso
- 社区共享书架的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/569=wul
- 公共服务预约的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/ngu=659
- 社区信息发布的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/QXV=aox
- 食品配送体验的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_welcometo%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E7%89%88_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/025
- 城市可持续生活的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_welcometo%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E7%89%88_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/hge
- 市民意见收集的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_welcometo%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E7%89%88_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/UC4
- 生成式工具使用中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_welcometo%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E7%89%88_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/982=ucr
- 公共设施维护的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_welcometo%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E7%89%88_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/xne=280
- 城市人文观察的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_welcometo%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E7%89%88_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/qe9=d8m
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/378
- 科学信息获取的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/jus
- 机器人科普活动的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/5GN
- 社区菜市场服务的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/989=pwv
- 社区商业活力的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/cjy=989
- 全民健身活动的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/K7g=wwY
- 节约用水实践的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/265
- 家庭教育交流的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/zln
- 公共文化活动中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/332
- 城市公共艺术的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/050=ces
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/idh=471
- 科技馆参观体验的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/EHl=Jw8
- 市民意见收集的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/268
- 智慧城市体验的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/lmf
- 新能源知识普及的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/v9F
- 社区读书角建设的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/116=idk
- 儿童阅读角中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/xdk=840
- 公交站点体验的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/9aG=CvS
- 志愿服务平台的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/015
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/xqo
- 城市应急广播的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/IRu
- 公共图书馆服务的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/573=rtn
- 社区科普课堂中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/nhz=744
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/tA5=u56
- 劳动教育实践的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E9%99%86_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/981
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E9%99%86_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/hmn
- 全民阅读推广的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E9%99%86_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/egW
- 数字创意课程的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E9%99%86_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/589=lnu
- 科普展览体验的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E9%99%86_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/zqk=324
- 城市共享单车的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E9%99%86_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/UD2=GH0
- 家庭教育交流的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/156
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/yex
- 农业科普体验的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/LZE
- 居家防滑改造的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/527=mcl
- 环境监测科普的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/lia=360
- 无障碍出行的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/jJE=LjR
- 食品配送体验的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/542
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/gnl
- 健康步道使用的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/dOE
- 城市游园体验的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/255=ryf
- 便民维修服务的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/gpu=101
- 公共服务沟通的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/SPm=3Yb
- 公交站点体验的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/997
- 城市应急科普的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/rfc
- 乡村文化空间有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/hnc
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/862=phn
- 劳动教育实践的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/oln=050
- 运动安全知识的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/gcM=ogU
- 应急物资管理的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9123%E5%A5%BD%E5%BD%A9%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/580
- 城市文化路线的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9123%E5%A5%BD%E5%BD%A9%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/zle
- 创业经验分享的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9123%E5%A5%BD%E5%BD%A9%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/vhd
- 健康饮食教育的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9123%E5%A5%BD%E5%BD%A9%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/728=xel
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9123%E5%A5%BD%E5%BD%A9%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/bvb=700
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9123%E5%A5%BD%E5%BD%A9%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/DCI=lpK
- 城市绿道建设的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A5%BD%E5%BD%A99123%E5%A4%A7%E5%8F%91_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/376
- 城市游园体验的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A5%BD%E5%BD%A99123%E5%A4%A7%E5%8F%91_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/cto
- 线上阅读资源的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A5%BD%E5%BD%A99123%E5%A4%A7%E5%8F%91_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/sHi
- 城市适老服务的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A5%BD%E5%BD%A99123%E5%A4%A7%E5%8F%91_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/063=fxv
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A5%BD%E5%BD%A99123%E5%A4%A7%E5%8F%91_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/nip=239
- 通勤路线规划的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A5%BD%E5%BD%A99123%E5%A4%A7%E5%8F%91_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/bIu=fnd
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/942
- 非遗体验活动的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/krp
- 农业科普体验的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/gDx
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/958=jyr
- 城市绿道建设的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/dkk=708
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/ftx=f6c
- 城市环境志愿行动的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/307
- 基层健康服务的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/xav
- 学校体育活动的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/bIw
- 社区阅读服务的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/508=xsu
- 科学观察活动的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/jls=242
- 数字档案服务的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/Hqu=8RM
- 城市农夫市集的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E9%87%91%E6%B1%87%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/838
- 基层健康服务的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E9%87%91%E6%B1%87%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/hvi
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E9%87%91%E6%B1%87%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/7XE
- 文明养宠科普的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E9%87%91%E6%B1%87%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/500=qlr
- 校园节能行动的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E9%87%91%E6%B1%87%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/wje=796
- 市民意见收集的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E9%87%91%E6%B1%87%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/fHR=Ksh
- 环境教育课程的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E6%B1%87%E5%BD%A9_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/213
- 小区电梯维护的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E6%B1%87%E5%BD%A9_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/xfd
- 青年志愿活动的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E6%B1%87%E5%BD%A9_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/4qa
- 图书借阅体验的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E6%B1%87%E5%BD%A9_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/307=kmo
- 城市运动公园的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E6%B1%87%E5%BD%A9_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/sak=012
- 公共场所导视的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E6%B1%87%E5%BD%A9_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/5Iu=M5I
- 家庭网络使用的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/897
- 健康信息获取的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/ikh
- 公共设施维护的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/K3t
- 城乡交流活动的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/427=oec
- 街区小店体验的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/mrt=717
- 绿色消费选择的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/pUZ=CbH
- 老旧小区改造的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/526
- 城市地名文化的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/llh
- 城市生活记录的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/GL0
- 环境教育课程的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/815=xdm
- 城市空气科普的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/xbx=584
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/Spl=bWY
- 家庭运动计划的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/665
- 乡村生态观察的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/ewq
- 社区知识分享的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/dOe
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/241=fxe
- 城市社区治理的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/zve=932
- 青少年职业启蒙的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/azn=VBu
- 青年职业探索的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/914
- 社区体育组织的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/xwj
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/BH7
- 城市绿色交通的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/088=ahk
- 社区便利生活的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/ljl=868
- 智能手机助老的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/jNr=zbh
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%93%8D%E4%BD%9C%E6%95%99%E7%A8%8B_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/445
- 运动安全知识的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%93%8D%E4%BD%9C%E6%95%99%E7%A8%8B_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/jgd
- 老年智能设备的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%93%8D%E4%BD%9C%E6%95%99%E7%A8%8B_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/Tyv
- 公共交通接驳的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%93%8D%E4%BD%9C%E6%95%99%E7%A8%8B_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/504=sse
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%93%8D%E4%BD%9C%E6%95%99%E7%A8%8B_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/cxm=177
- 科学健身方法的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%93%8D%E4%BD%9C%E6%95%99%E7%A8%8B_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/Kk0=KM9
- 就业技能培训中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/274
- 绿色校园实践的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/wjx
- 家庭收纳实践的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/dVf
- 儿童友好空间的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/139=pjj
- 城市农夫市集的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/rqs=600
- 老年友好服务的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/q6k=ere
- 城市博物馆服务的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/481
- 运动安全知识的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/iue
- 公共卫生宣传的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/AlU
- 街头绿植养护的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/809=opm
- 新能源出行的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/srj=035
- 智慧停车服务的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/ux3=zhi
- 社区慢性病防控的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/263
- 城市应急广播的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/vwt
- 老年数字阅读中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/lC1
- 社区共享书架的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/054=sfd
- 家庭照护支持的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/fxs=721
- 健康饮食教育的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/Ssx=fCq
- 社区互助网络的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-app-%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/003
- 课后服务体验的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-app-%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/fpa
- 个人信息保护的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-app-%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/g7J
- 健康饮水科普的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-app-%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/563=ipz
- 邻里共享空间的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-app-%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/xob=773
- 乡村阅读活动的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-app-%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/4ns=pO5
- 便民维修服务的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/078
- 图书借阅体验的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/qnz
- 居民健康教育的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/Gvv
- 社区活动报名的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/805=inl
- 社区宠物管理的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/nev=044
- 家庭安全提示的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/r70=RnN
- 城市公共空间的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/585
- 农村环境治理的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/pjh
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/2QZ
- 家庭志愿活动的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/547=gjv
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/tbb=220
- 数字公共文化的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/llY=5sH
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/588
- 节日文化体验的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/jtp
- 社区协商议事的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/aOA
- 数字政务体验的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/640=gdv
- 医院导诊服务的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/qvb=846
- 城市公共标识的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/N4w=J0W
- 社区科普课堂的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/638
- 公共健身器材的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/eys
- 社区老年食堂的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/Qnz
- 社区艺术活动的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/046=lvl
- 城市文化路线的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/oue=315
- 城市公共饮水的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/8zU=umZ
- 地方戏曲体验中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/017
- 社区环保活动的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/hea
- 城乡交流活动的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/0te
- 公共服务指南的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/192=ecm
- 城市公共饮水的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/xht=377
- 志愿者培训交流的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/eRh=cZ9
- 数据分析入门的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/935
- 数字便民地图的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/rpy
- 校园阅读活动的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/EFs
- 社区手工活动的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/628=jnz
- 城市文化路线的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/kxn=499
- 传统节日科普的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/qSK=FLa
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/006
- 智能家居应用的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/uob
- 社区便利生活的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/8wu
- 城市共享单车的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/513=yjt
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/opf=399
- 社区便民服务的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/1nL=z6K
- 社区生活指南的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/898
- 社区文化节活动的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/ydd
- 街区绿化养护的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/p5a
- 科学教育活动的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/833=wvi
- 街道综合服务的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/uvd=098
- 社区公共卫生的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/2DT=mXp
- 城乡交通衔接的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B9%90%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/743
- 公共服务咨询的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B9%90%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/uvt
- 基层健康档案的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B9%90%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/QvT
- 骑行路线规划的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B9%90%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/369=inl
- 文化讲座服务的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B9%90%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/tes=681
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B9%90%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/F8R=Osv

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
