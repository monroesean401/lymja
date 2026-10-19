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

- 社区读书角建设的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_59tt-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/998
- 文明养宠科普的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_59tt-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/tkp
- 社区防暑服务的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_59tt-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/NKQ
- 乡村产业科普的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_59tt-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/820=nzf
- 家庭照护支持的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_59tt-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/dmz=249
- 数字支付体验的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_59tt-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/HVX=6Dj
- 社区托育服务的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_59tt-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/547
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_59tt-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/aqm
- 就业技能培训的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_59tt-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/1jR
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_59tt-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/132=ngs
- 社区环保活动的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_59tt-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/wnr=716
- 居民健康教育的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_59tt-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/o2d=TRU
- 课后服务体验的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_59tt-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/261
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_59tt-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/xyc
- 城市共享单车的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_59tt-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/UVV
- 无障碍出行的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_59tt-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/139=jib
- 数字阅读服务的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_59tt-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/zpp=327
- 青少年科技社团的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_59tt-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/sxt=fnF
- 智慧停车服务的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_59tt-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/917
- 运动安全知识的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_59tt-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/jls
- 网络安全教育的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_59tt-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/qIS
- 绿色校园实践的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_59tt-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/613=ott
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_59tt-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/agf=780
- 个人信息保护的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_59tt-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/L2d=spk
- 城市农夫市集的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_59tt-APP_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/029
- 城市游园体验的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_59tt-APP_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/itv
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_59tt-APP_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/3IU
- 社区公共卫生的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_59tt-APP_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/350=srx
- 儿童安全出行的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_59tt-APP_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/zam=839
- 线上阅读资源的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_59tt-APP_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/ImA=sY9
- 儿童友好空间的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_59tt-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/799
- 乡村公共文化的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_59tt-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/mut
- 公共交通接驳的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_59tt-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/5zQ
- 城市夜间照明的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_59tt-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/719=bxv
- 家庭环保行动的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_59tt-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/aqk=754
- 社区生活指南的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_59tt-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/59S=atp
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/541
- 城市博物馆活动的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/iiw
- 地方戏曲体验的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/0Lp
- 生活垃圾减量的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/413=pcz
- 社区快递服务的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/ydt=116
- 城市文明出行的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/AaK=r1Z
- 社区知识分享的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_59tt-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/977
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_59tt-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/sej
- 家庭网络使用的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_59tt-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/FjR
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_59tt-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/123=rve
- 城市步行友好的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_59tt-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/vhv=492
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_59tt-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/ACF=T6Z
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_59tt-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/156
- 家庭阅读计划的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_59tt-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/dbc
- 在线教育体验的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_59tt-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/USN
- 数字地图应用的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_59tt-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/664=djp
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_59tt-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/bcq=233
- 城市步行环境的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_59tt-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/ssQ=CMA
- 校园阅读活动的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_59tt-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/835
- 城市基础设施的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_59tt-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/bcu
- 科学信息获取的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_59tt-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/9Bh
- 基层健康档案的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_59tt-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/952=vbm
- 公共卫生设施的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_59tt-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/uui=959
- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_59tt-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/Vij=Pd5
- 社区手工活动的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_59tt-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/670
- 城市步行环境的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_59tt-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/kzj
- 城市休闲步道的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_59tt-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/gVe
- 城市水环境观察的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_59tt-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/758=nwf
- 儿童安全出行的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_59tt-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/jzq=036
- 城乡交流活动的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_59tt-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/H2J=hXB
- 科学教育活动的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_59tt-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/394
- 青年就业服务的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_59tt-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/qlq
- 社区花园共建中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_59tt-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/2ED
- 本地消费场景的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_59tt-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/425=ggn
- 公共卫生设施的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_59tt-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/dul=368
- 智慧停车服务的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_59tt-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/j9h=3gY
- 乡村生活观察的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_59tt-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/711
- 学校体育活动的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_59tt-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/xht
- 科普展览体验的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_59tt-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/Cf1
- 绿色办公实践的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_59tt-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/583=rwn
- 社区安全巡查的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_59tt-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/azo=224
- 数字创意课程的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_59tt-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/KEA=CXp
- 无障碍出行的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_59tt-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/303
- 城市公共饮水的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_59tt-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/pbn
- 社区商业活力的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_59tt-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/jm0
- 社区健康讲座的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_59tt-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/878=abz
- 图书馆亲子空间的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_59tt-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/yqe=720
- 邻里共享空间的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_59tt-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/a9w=D3U
- 城市适老服务的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_59tt-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/772
- 生活服务数字化的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_59tt-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/kdp
- 读书会组织的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_59tt-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/Nep
- 小区公共照明的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_59tt-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/455=jlj
- 社区互助网络的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_59tt-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/cdf=732
- 社区读书角建设的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_59tt-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/x0w=PI0
- 乡村公共服务的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/654
- 街头绿植养护的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/gya
- 课后服务体验的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/g7n
- 生活技能分享的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/764=fwt
- 科学教育活动的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/wqs=711
- 科学健身方法的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/oKs=Vq9
- 儿童安全出行的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/496
- 农村环境治理的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/tat
- 家庭用电安全的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/HiM
- 健康饮水科普的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/428=jmg
- 社会体育指导的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/vtf=386
- 绿色办公实践的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/k93=Uk7
- 青少年心理健康的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/431
- 乡村文化空间的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/rvg
- 乡村生态旅游的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/JBl
- 电动汽车充电的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/269=ivu
- 城市噪声观察的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/ykw=542
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/55G=8gf
- 公共健身器材的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%85%AC%E5%BC%80%E8%AF%BE?/385
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%85%AC%E5%BC%80%E8%AF%BE?/wsf
- 文化遗产保护科普的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%85%AC%E5%BC%80%E8%AF%BE?/upj
- 家庭环保习惯的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%85%AC%E5%BC%80%E8%AF%BE?/404=iax
- 家庭急救准备的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%85%AC%E5%BC%80%E8%AF%BE?/geh=496
- 城乡交流活动的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%85%AC%E5%BC%80%E8%AF%BE?/W1U=OB7
- 线上办事服务的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/314
- 环境教育课程的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/bej
- 机器学习入门的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/Lbc
- 绿色出行服务的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/324=dkg
- 绿色办公实践的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/dix=358
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/ubD=Mrm
- 社区便民集市的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/283
- 城市住房服务的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/ibi
- 乡村文化空间的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/dFq
- 开源技术交流的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/985=ams
- 老年人出行服务的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/nca=193
- 公园无障碍服务的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/rcb=TRB
- 城市公共空间的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/014
- 城市生活记录的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/fgs
- 图书馆数字服务的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/orz
- 在线学习体验的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/906=tie
- 家庭养老规划的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/jke=213
- 公园休闲体验的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/Qg8=8Hq
- 公共设施使用的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/335
- 食品安全科普的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/ocq
- 在线学习体验的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/4Gz
- 家庭科学教育的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/446=riy
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/hha=608
- 科学观察活动的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/rH9=kuN
- 社区手工活动的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/952
- 社区环保活动的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wgx
- 社区花园共建的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/WyK
- 科学健身方法的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/743=qyd
- 图书借阅体验的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dou=265
- 个人信息保护的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/JVo=GZr
- 公共场所导视的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/242
- 家庭安全提示的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/lql
- 城市夜间照明中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/2sO
- 公交无障碍服务的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/964=slg
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/jcs=144
- 家庭急救准备的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/Aga=xtu
- 社区绿色空间的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_59tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/455
- 数字生活课堂的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_59tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/cfe
- 城市环境志愿行动的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_59tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/Fz9
- 城市应急广播的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_59tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/169=yjz
- 数字创意课程的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_59tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/rxy=557
- 软件开发学习的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_59tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/JdC=V6w
- 社区公共卫生的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_59tt%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/607
- 数字资源检索的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_59tt%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/zux
- 青少年心理健康的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_59tt%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/ZzQ
- 基层医疗预约的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_59tt%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/458=qal
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_59tt%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/cvm=084
- 城市游园体验的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_59tt%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/N25=J31
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/412
- 街区小店体验的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/nfz
- 城市环境志愿行动的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/Rdv
- 社区协商议事的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/053=mlc
- 社区科普课堂的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/hqr=489
- 科普展览体验的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/U4f=0Jh
- 本地消费场景的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/195
- 儿童户外活动的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/rpa
- 家庭科学教育中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/xaq
- 社区阅读服务的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/656=gbw
- 公共空间导览的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/tqy=621
- 家庭科学教育的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/iBy=siy
- 社区活动空间的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/956
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/wsc
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/71t
- 家庭食品保存的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/737=mtk
- 青少年科技社团从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/qtn=979
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/aBV=lK9
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_59tt%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/571
- 智能手机助老的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_59tt%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/nqt
- 城市住房服务的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_59tt%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/bR3
- 日常摄影记录的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_59tt%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/827=brm
- 本地旅行体验的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_59tt%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/hfy=039
- 便民服务地图的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_59tt%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/n3Q=Z0E
- 节假日出行安排的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_59tt%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/612
- 农业科普体验的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_59tt%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/ffc
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_59tt%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/Hwz
- 公共服务指南有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_59tt%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/155=brl
- 街道综合服务的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_59tt%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/nds=358
- 学校体育活动的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_59tt%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/SNA=7Uz
- 社区活动策划的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/669
- 青少年户外教育的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/yzc
- 城乡交流活动的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/Dtf
- 公共空间休憩中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/666=xxx
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/gqp=749
- 社区知识分享的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/zO4=LVS
- 城市树木认养的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/367
- 社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/wbw
- 食品配送体验的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/s44
- 公园亲子设施的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/533=zet
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/yiq=981
- 节日文化体验的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/gsp=FyL
- 图书馆活动策划的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_59tt%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/546
- 全民阅读推广的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_59tt%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/jzb
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_59tt%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/odL
- 儿童安全出行的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_59tt%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/283=oca
- 节日文化体验的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_59tt%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/ymc=307
- 城市骑行环境的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_59tt%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/d7e=phu
- 就业技能培训的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_59tt%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/418
- 农贸市场环境的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_59tt%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/lcp
- 社区公共卫生中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_59tt%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/j35
- 街区绿化养护的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_59tt%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/140=ysn
- 数字公共文化的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_59tt%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/tld=635
- 口袋公园建设的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_59tt%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/p5E=nAo
- 城乡公共服务的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/611
- 社区信息发布的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/cvk
- 小区公共照明的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/eYn
- 家庭饮食安排的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/964=fji
- 数字资源检索的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/vjx=102
- 科普展览体验的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/nIh=lhO
- 公共空间休憩的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_650%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/685
- 老年运动活动的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_650%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/wjf
- 运动安全知识的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_650%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/Cho
- 乡村生态观察的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_650%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/280=fef
- 智能手机助老的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_650%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/qfl=003
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_650%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/djD=gU4
- 社区共享书架的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_650%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/185
- 城市步行友好的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_650%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/fwf
- 老年智能设备中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_650%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/xkS
- 家庭网络使用的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_650%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/287=ltw
- 信息无障碍体验的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_650%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/cop=987
- 新能源出行的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_650%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/bQ1=PpL
- 公共服务指南的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_650%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/449
- 非遗体验活动的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_650%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/bxv
- 社区手工活动的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_650%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/2fG
- 机器人科普活动的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_650%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/270=gdz
- 数字阅读服务的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_650%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/zhq=932
- 公共图书馆服务的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_650%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/0SO=nsQ
- 社区活动策划的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_650%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/522
- 无障碍出行的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_650%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/ipz
- 家庭收纳实践的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_650%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/o64
- 家庭健康管理的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_650%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/338=gay
- 家庭网络使用的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_650%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/zso=131
- 公共交通接驳的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_650%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/LMt=IrM
- 在线学习体验的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_650%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/881
- 无障碍出行的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_650%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/xil
- 绿色出行服务的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_650%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/GQd
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_650%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/292=whp

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
