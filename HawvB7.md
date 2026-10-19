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

- 无障碍信息设计的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_1388%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/441
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_1388%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/xut
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_1388%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/3aJ
- 家庭用电安全的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_1388%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/741=kep
- 数字地图应用的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_1388%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/vmd=280
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_1388%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/Vil=LzD
- 社区活动策划的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_1388%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/266
- 智慧停车服务的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_1388%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/dsx
- 社区环保活动的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_1388%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/sdd
- 公共空间导览的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_1388%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/500=pkq
- 基层服务创新的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_1388%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/xaw=533
- 老年数字阅读的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_1388%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/wjI=mWY
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_1388%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/694
- 社区宠物管理中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_1388%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/pke
- 家庭健康管理的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_1388%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/NB0
- 地方民俗记录的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_1388%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/590=orw
- 城乡交流活动的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_1388%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/ujs=652
- 口袋公园建设的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_1388%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/1Lr=crX
- 社区托育服务的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_1388%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/258
- 家庭运动计划的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_1388%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/tkv
- 租房信息服务的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_1388%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/CCn
- 城市应急广播中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_1388%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/558=dwy
- 城市绿色交通的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_1388%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/rru=772
- 绿色生活实践的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_1388%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/PEt=qd5
- 生活服务数字化的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/371
- 应急物资管理的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/mgd
- 科学观察活动的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/QrL
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/065=gal
- 图书馆活动策划的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/eto=153
- 非遗体验活动的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/WOE=tDI
- 城市农夫市集的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_1388%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/828
- 社区便民服务的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_1388%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/yny
- 便民服务地图的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_1388%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/RF6
- 课后服务体验的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_1388%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/569=cuy
- 数字档案服务的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_1388%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/ugt=912
- 在线学习体验的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_1388%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/3vw=RpN
- 开放数据应用的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/995
- 城市便民驿站的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/leu
- 社区互助网络的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/Es0
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/976=hci
- 城市慢行系统的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/ztc=144
- 城市步行友好的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/qTc=xPI
- 公共图书馆服务的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_1388%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/960
- 社区养老服务的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_1388%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/pdk
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_1388%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/mvd
- 志愿者培训交流的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_1388%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/323=dza
- 便民服务地图的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_1388%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/gno=432
- 青年就业服务的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_1388%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/tFD=sNs
- 便民服务窗口的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_1388%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/592
- 家庭环保习惯的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_1388%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/ikb
- 社区邻里服务的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_1388%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/FFE
- 城市绿色交通的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_1388%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/441=puj
- 文化场馆预约的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_1388%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/ehr=791
- 青年职业探索的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_1388%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/9v0=a7Q
- 数字便民地图的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/863
- 社区花园共建的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/edm
- 亲子科普活动的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/U9p
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/619=ker
- 本地历史资料的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/fds=557
- 家庭用电安全的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/t6h=lcq
- 社区协商议事的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/855
- 城市人文观察的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/ckc
- 儿童运动体验的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/JuG
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/886=ihc
- 个人信息保护的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/adw=251
- 社区邻里服务的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/IUb=b7G
- 生活服务数字化中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_1388%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/475
- 公共空间安全的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_1388%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/dmt
- 老年运动活动的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_1388%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/DgU
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_1388%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/242=leg
- 社区养老服务的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_1388%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/vse=896
- 公共设施维护的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_1388%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/5Yn=PFA
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1388%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/262
- 城市微更新实践的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1388%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/hnx
- 城乡公共服务的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1388%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/0Yy
- 物业服务沟通的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1388%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/797=nnb
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1388%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/vly=879
- 公共服务数字化的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1388%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/t9J=Wg0
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/826
- 农产品消费体验的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/ura
- 社区志愿服务的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/0m6
- 数字阅读服务的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/027=oso
- 租房信息服务的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/ifg=930
- 城市噪声观察的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/KJC=yeW
- 个人时间管理的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/745
- 城市公共标识的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/dbs
- 数字便民地图的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/RjC
- 数字生活课堂的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/726=fiq
- 校园社团活动的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/uaf=604
- 绿色办公实践的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/MkX=ixh
- 骑行路线规划的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/477
- 科学运动指导的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/tol
- 乡村产业科普的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/cao
- 社区故事采集的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/483=btv
- 劳动教育实践的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/xmh=460
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/YsL=5u8
- 日常摄影记录的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/286
- 科普展览体验的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/hpo
- 低碳社区实践的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/oyN
- 社区垃圾分类的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/482=fml
- 网络安全教育的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/hqu=399
- 周末休闲规划中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/WZX=II7
- 青少年科技社团的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/846
- 青少年户外教育的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/ogk
- 老年运动活动的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/1fq
- 老年人文化生活的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/737=ipg
- 社区休闲设施中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/fuz=240
- 城市人文观察的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/Ax3=95H
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/189
- 健康饮食教育的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/llp
- 社区共享书架的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/dgG
- 社区体育组织的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/445=erm
- 乡村公共服务的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/qpx=111
- 城市微更新实践的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/EHY=bmr
- 社区儿童活动的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/510
- 青少年科普实践的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/uol
- 乡村电商实践从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/w7H
- 科普展览体验的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/636=kxl
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/bqk=290
- 城市博物馆活动的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/o8q=73t
- 生成式工具使用的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/539
- 城市农夫市集的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/urz
- 城市绿道建设的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/hmK
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/554=lbk
- 老年学习活动的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/uqk=005
- 基层医疗预约的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/iSA=wEZ
- 青少年户外教育的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/805
- 休闲运动入门的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/lvb
- 社区菜市场服务从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/nbV
- 传统节日科普的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/057=zwo
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/otk=056
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/agU=qBx
- 健康饮水科普的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_1889%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/469
- 智慧停车服务的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_1889%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/hpu
- 乡村生活观察的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_1889%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/J1r
- 社区托育服务的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_1889%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/357=mgn
- 社区知识分享的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_1889%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/xdd=668
- 无障碍出行的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_1889%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/EFJ=FNu
- 日常摄影记录的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_1889%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/804
- 社区体育组织的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_1889%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/jzw
- 家庭消费规划的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_1889%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/pyo
- 电子商务服务的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_1889%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/314=yrl
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_1889%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/uxb=005
- 公共服务指南有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_1889%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/J2p=zX1
- 科学健身方法的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/964
- 居民健康教育的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/wcg
- 节假日出行安排的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/NmH
- 应急物资管理的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/263=vip
- 终身学习资源的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/wmd=182
- 运动安全知识的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/373=U5a
- 社区家政服务的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E7%A0%81?/862
- 职业技能学习的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E7%A0%81?/rpt
- 基层健康服务的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E7%A0%81?/3j5
- 周末休闲规划的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E7%A0%81?/593=zkx
- 便民信息查询的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E7%A0%81?/kxp=649
- 本地历史资料中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E7%A0%81?/sca=1xB
- 小微企业服务的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E6%8E%A2%E5%BA%97?/712
- 地方文化传播的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E6%8E%A2%E5%BA%97?/ore
- 城市可持续生活的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E6%8E%A2%E5%BA%97?/9n4
- 社区设施共享的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E6%8E%A2%E5%BA%97?/923=tnm
- 家庭节能实践的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E6%8E%A2%E5%BA%97?/qif=038
- 公益活动组织的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E6%8E%A2%E5%BA%97?/T3T=3Ta
- 老年人出行服务的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1889%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%95%B0%E8%AF%BB?/391
- 光伏知识科普的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1889%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%95%B0%E8%AF%BB?/hev
- 乡村阅读空间的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1889%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%95%B0%E8%AF%BB?/l5d
- 城市农夫市集的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1889%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%95%B0%E8%AF%BB?/118=eag
- 网络信息辨识的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1889%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%95%B0%E8%AF%BB?/wii=701
- 农产品消费体验的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1889%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%95%B0%E8%AF%BB?/J9g=eb9
- 非遗体验活动的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/825
- 家庭阅读计划的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/pbg
- 公共空间休憩有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/Ne2
- 地方美食文化的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/671=slq
- 低碳社区实践的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/lco=753
- 社区家政服务的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/pDy=bCN
- 安全出行教育的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/385
- 城市应急广播的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/zrr
- 本地旅行体验的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/TiL
- 社区学习活动的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/770=dkp
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/tni=210
- 社区活动报名的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/yZk=eBn
- 公共服务咨询的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/217
- 科学健身方法的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/fnz
- 城市地名文化的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/Sx9
- 社区垃圾回收的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/539=ush
- 社区学习活动的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/qkm=690
- 城市应急科普的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_1889%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/8kh=Ace
- 数据分析入门的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/110
- 街区绿化养护的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/qhj
- 人工智能科普的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/jWY
- 小微企业服务的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/731=unn
- 家庭急救准备的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/wui=924
- 社区健康讲座的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/nnt=Tjr
- 城市展览体验的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_1899%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/519
- 新能源出行的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_1899%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/idj
- 城市绿色交通中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_1899%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/dsJ
- 数字素养提升的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_1899%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/343=uju
- 口袋公园建设的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_1899%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/bzk=788
- 基层医疗预约的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_1899%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/Jd9=XBl
- 城市可持续生活的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/782
- 生活垃圾回收的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/hvw
- 劳动教育实践的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/yZ6
- 青少年户外教育的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/679=tjj
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/apm=637
- 公共服务数字化的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/MKh=Iiy
- 家庭节能实践的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/735
- 生活技能分享的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/eve
- 城市夜间照明的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/nIQ
- 节约用水实践的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/934=fel
- 家庭食品保存的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/xei=873
- 无障碍出行的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/Nbu=vvL
- 社区慢性病防控的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9B%AD%E8%89%BA?/923
- 安全出行教育的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9B%AD%E8%89%BA?/ckq
- 新能源知识普及的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9B%AD%E8%89%BA?/vqc
- 非遗课堂体验的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9B%AD%E8%89%BA?/942=qfr
- 城市步行友好的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9B%AD%E8%89%BA?/uvi=423
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9B%AD%E8%89%BA?/VMv=6Hk
- 数字公共文化中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/251
- 开源技术交流的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/cts
- 开源技术交流的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/o5m
- 城市社区治理的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/999=jjs
- 药品使用科普的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/rvs=153
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/Wcr=gou
- 医院导诊服务的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/022
- 公共空间安全的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/iet
- 城市公共自行车的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/sIf
- 节日文化体验的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/485=ylu
- 传统手工艺体验的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/kmj=138
- 基层医疗预约的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/A2D=STi
- 图书馆数字服务的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/014
- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/gwj
- 个人数据管理的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/zqt
- 社区便民集市的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/561=ajt
- 公园休闲体验的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/uwy=836
- 社区活动策划的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/HFy=rXw
- 社区停车服务的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/553
- 急救知识普及的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/gus
- 社区法律科普的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/63M
- 文化场馆预约的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/565=skv
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/mpw=729
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/CW2=ao2
- 社区消防演练的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/676
- 节假日出行安排的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/pzn
- 新能源出行的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/sOT
- 社区心理支持的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/390=tno
- 公共服务评价的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/uer=257
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/caP=ZSF
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/795
- 地方戏曲体验的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/aue
- 劳动教育实践的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/cyx
- 城市公共座椅的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/757=ayo

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
