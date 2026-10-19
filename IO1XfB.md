# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:28**

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

- 乡村电商实践的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/052
- 开源技术交流的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/too
- 社区运动空间中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/ReS
- 城市公共空间的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/972=ykr
- 公共交通信息服务的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/bls=523
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/5OG=CpM
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/578
- 数字课堂应用的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/uei
- 科技馆参观体验的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/kCg
- 乡村产业科普的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/858=lsu
- 生成式工具使用的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/qhx=310
- 青年职业探索的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/W6i=nzl
- 便民服务地图的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E4%B8%AD%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/320
- 数字公共文化的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E4%B8%AD%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/vpr
- 社区家校合作的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E4%B8%AD%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/Vc8
- 校园安全教育的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E4%B8%AD%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/958=wgv
- 农贸市场环境的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E4%B8%AD%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/myp=427
- 数字阅读服务的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E4%B8%AD%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/mw9=PIE
- 就业技能培训的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/299
- 绿色生活实践的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/yif
- 儿童安全出行的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/K4a
- 节约用水实践的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/729=mwx
- 消防知识宣传的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/ihw=802
- 社区休闲设施的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/pPg=BAr
- 读书会组织的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91_%E6%97%A7%E7%89%88%E6%9C%AC2.0.1_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/903
- 小区停车协商的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91_%E6%97%A7%E7%89%88%E6%9C%AC2.0.1_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/zxz
- 数字档案服务的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91_%E6%97%A7%E7%89%88%E6%9C%AC2.0.1_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/Xi0
- 低碳社区实践的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91_%E6%97%A7%E7%89%88%E6%9C%AC2.0.1_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/889=vgd
- 家庭科学教育的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91_%E6%97%A7%E7%89%88%E6%9C%AC2.0.1_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/yzv=609
- 在线教育体验的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91_%E6%97%A7%E7%89%88%E6%9C%AC2.0.1_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/byl=Cxv
- 家庭运动计划的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A8%B1%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%A4%A7%E5%8E%85welcome_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/655
- 家庭运动计划的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A8%B1%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%A4%A7%E5%8E%85welcome_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/dbe
- 社区安全巡查的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A8%B1%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%A4%A7%E5%8E%85welcome_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/p8e
- 街区道路维护的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A8%B1%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%A4%A7%E5%8E%85welcome_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/296=xhj
- 基层健康服务的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A8%B1%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%A4%A7%E5%8E%85welcome_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/xdv=208
- 家庭急救准备的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A8%B1%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%A4%A7%E5%8E%85welcome_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/PFQ=2cP
- 社区庭院绿化的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91welcome%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/346
- 创业经验分享中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91welcome%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/giz
- 绿色出行服务的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91welcome%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/xjH
- 城市社区治理的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91welcome%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/288=vta
- 公共场所导视的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91welcome%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/fir=206
- 城市公共座椅的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91welcome%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/ysn=KxR
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_welcome%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/991
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_welcome%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/xzd
- 科学信息获取的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_welcome%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/9sx
- 老年友好服务的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_welcome%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/154=whl
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_welcome%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/xmt=655
- 环境教育课程的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_welcome%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/MEq=Bwl
- 居民健康教育的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E4%BD%93%E8%82%B2?/378
- 智慧停车服务的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E4%BD%93%E8%82%B2?/itn
- 儿童户外活动的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E4%BD%93%E8%82%B2?/5yj
- 老年友好服务的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E4%BD%93%E8%82%B2?/995=hhe
- 街区更新实践的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E4%BD%93%E8%82%B2?/nyj=157
- 小区电梯维护的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E4%BD%93%E8%82%B2?/giw=GzP
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/071
- 城市噪声观察的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/llt
- 社区信息发布的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/T8w
- 绿色办公实践的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/952=mmk
- 数字阅读服务有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/rwa=633
- 公共文化活动中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/90P=i9a
- 校园节能行动的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/002
- 城市公共饮水的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/oln
- 城市空气科普的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/SbT
- 家庭养老规划的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/038=xbv
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/akw=530
- 学校食育活动的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/Gf5=Qn1
- 校园社团活动的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%B4%AD%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/809
- 在线学习体验的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%B4%AD%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/bfg
- 城市适老服务的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%B4%AD%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/pdE
- 基层医疗预约的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%B4%AD%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/006=arl
- 便民信息查询的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%B4%AD%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/pnv=158
- 图书借阅体验的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%B4%AD%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/SEq=7Is
- 旧物循环利用的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/852
- 家庭饮食安排的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/elm
- 公共卫生宣传的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/ZpI
- 社区商业活力的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/465=hnh
- 地方民俗记录的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/zgp=599
- 家庭饮食安排的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/3Os=jwf
- 社区便民服务的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/018
- 数字政务体验的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/irt
- 社区运动空间的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/DX2
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/534=ije
- 健康饮水科普的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/eak=061
- 公共空间导览的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/rFy=gT6
- 公共卫生设施的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E8%B4%AD%E4%B9%B0%E6%B5%81%E7%A8%8B_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/904
- 个人信息保护的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E8%B4%AD%E4%B9%B0%E6%B5%81%E7%A8%8B_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/chj
- 绿色生活实践的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E8%B4%AD%E4%B9%B0%E6%B5%81%E7%A8%8B_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/hD0
- 邻里互助活动的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E8%B4%AD%E4%B9%B0%E6%B5%81%E7%A8%8B_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/725=kyo
- 家庭安全提示的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E8%B4%AD%E4%B9%B0%E6%B5%81%E7%A8%8B_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/fqs=204
- 社区邻里服务的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E8%B4%AD%E4%B9%B0%E6%B5%81%E7%A8%8B_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/OCl=xpH
- 社区休闲设施的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/325
- 通勤路线规划的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/vra
- 数字素养提升的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/hjV
- 社区绿色空间的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/693=snl
- 健康信息获取的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/fwv=506
- 家庭健康科普中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/Ebf=CXJ
- 城乡交流活动的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E8%AE%BA%E5%9D%9B%E4%B9%90%E5%BD%A9%E8%AE%BA%E5%9D%9B-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/479
- 城市公共饮水的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E8%AE%BA%E5%9D%9B%E4%B9%90%E5%BD%A9%E8%AE%BA%E5%9D%9B-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/sgn
- 电动汽车充电的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E8%AE%BA%E5%9D%9B%E4%B9%90%E5%BD%A9%E8%AE%BA%E5%9D%9B-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/kQf
- 公共卫生设施中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E8%AE%BA%E5%9D%9B%E4%B9%90%E5%BD%A9%E8%AE%BA%E5%9D%9B-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/716=fwc
- 社区信息发布的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E8%AE%BA%E5%9D%9B%E4%B9%90%E5%BD%A9%E8%AE%BA%E5%9D%9B-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/scd=281
- 家庭理财科普的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E8%AE%BA%E5%9D%9B%E4%B9%90%E5%BD%A9%E8%AE%BA%E5%9D%9B-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/1Nr=0AB
- 科学健身方法的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/190
- 地方文化传播的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/ukx
- 基层服务创新的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/Fic
- 生活垃圾回收的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/274=mec
- 家庭饮食安排的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/beo=504
- 节日文化体验的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/6Tl=0mK
- 全民健身活动的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BB%8A%E5%A4%A9%E4%B9%B0%E4%BB%80%E4%B9%88%E5%8F%B7%E7%A0%81%E8%83%BD%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/404
- 公共卫生设施的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BB%8A%E5%A4%A9%E4%B9%B0%E4%BB%80%E4%B9%88%E5%8F%B7%E7%A0%81%E8%83%BD%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/ydu
- 公共设施维护的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BB%8A%E5%A4%A9%E4%B9%B0%E4%BB%80%E4%B9%88%E5%8F%B7%E7%A0%81%E8%83%BD%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/yh6
- 物业服务沟通的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BB%8A%E5%A4%A9%E4%B9%B0%E4%BB%80%E4%B9%88%E5%8F%B7%E7%A0%81%E8%83%BD%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/350=cog
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BB%8A%E5%A4%A9%E4%B9%B0%E4%BB%80%E4%B9%88%E5%8F%B7%E7%A0%81%E8%83%BD%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/rzl=597
- 数字创意课程的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%BB%8A%E5%A4%A9%E4%B9%B0%E4%BB%80%E4%B9%88%E5%8F%B7%E7%A0%81%E8%83%BD%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/yar=QAt
- 公共服务评价的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%BA%A2%E4%B8%AD%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/811
- 城市水环境观察的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%BA%A2%E4%B8%AD%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/izd
- 街区小店体验的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%BA%A2%E4%B8%AD%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/ize
- 社区教育资源的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%BA%A2%E4%B8%AD%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/413=wdx
- 城市文化路线的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%BA%A2%E4%B8%AD%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/rvz=756
- 老年运动活动的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%BA%A2%E4%B8%AD%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/1ZW=Btz
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%89%80%E6%9C%89%E5%BD%A9%E7%A5%9E%E8%B4%AD%E4%B9%B0%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/409
- 城乡公共服务的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%89%80%E6%9C%89%E5%BD%A9%E7%A5%9E%E8%B4%AD%E4%B9%B0%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/esa
- 公益活动组织的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%89%80%E6%9C%89%E5%BD%A9%E7%A5%9E%E8%B4%AD%E4%B9%B0%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/Swf
- 绿色办公实践的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%89%80%E6%9C%89%E5%BD%A9%E7%A5%9E%E8%B4%AD%E4%B9%B0%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/776=kng
- 数字资源检索的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%89%80%E6%9C%89%E5%BD%A9%E7%A5%9E%E8%B4%AD%E4%B9%B0%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/nky=890
- 公共场所导视的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%89%80%E6%9C%89%E5%BD%A9%E7%A5%9E%E8%B4%AD%E4%B9%B0%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/pqS=eVH
- 社区商业活力的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Evll---%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%8A%95%E8%B5%84?/962
- 数字政务体验的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Evll---%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%8A%95%E8%B5%84?/shj
- 城市游园体验的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Evll---%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%8A%95%E8%B5%84?/iBR
- 社区花园共建的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Evll---%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%8A%95%E8%B5%84?/933=msx
- 社区学习活动的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Evll---%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%8A%95%E8%B5%84?/hst=454
- 公共健身器材的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Evll---%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%8A%95%E8%B5%84?/BeJ=4m2
- 绿色生活实践中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E4%B8%9C%E9%98%B3%E5%B8%82%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%9C%B0%E5%9D%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8D%8F?/793
- 绿色校园实践的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E4%B8%9C%E9%98%B3%E5%B8%82%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%9C%B0%E5%9D%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8D%8F?/yoh
- 生活垃圾减量的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E4%B8%9C%E9%98%B3%E5%B8%82%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%9C%B0%E5%9D%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8D%8F?/mYL
- 志愿服务平台的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E4%B8%9C%E9%98%B3%E5%B8%82%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%9C%B0%E5%9D%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8D%8F?/049=iyw
- 开放数据应用的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E4%B8%9C%E9%98%B3%E5%B8%82%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%9C%B0%E5%9D%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8D%8F?/nlf=999
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E4%B8%9C%E9%98%B3%E5%B8%82%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%9C%B0%E5%9D%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8D%8F?/trv=RjA
- 城市展览体验的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9EII%E4%B8%8B%E8%BD%BDapp_%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/156
- 公共设施维护的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9EII%E4%B8%8B%E8%BD%BDapp_%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/iye
- 公共卫生宣传的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9EII%E4%B8%8B%E8%BD%BDapp_%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/E0s
- 青少年户外教育的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9EII%E4%B8%8B%E8%BD%BDapp_%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/237=gsu
- 城乡交流活动的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9EII%E4%B8%8B%E8%BD%BDapp_%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/rmv=685
- 个人信息保护的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9EII%E4%B8%8B%E8%BD%BDapp_%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/v0W=uPw
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8ii_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/234
- 城市水环境观察的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8ii_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/lan
- 数字政务体验的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8ii_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/Xlz
- 社区学习活动的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8ii_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/255=fyv
- 社区共享书架的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8ii_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/iyl=141
- 数字课堂应用的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8ii_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/8l0=03W
- 农业科普体验的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A5%9E%E5%BD%A9V1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/946
- 医院导诊服务的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A5%9E%E5%BD%A9V1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/lit
- 社区艺术活动的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A5%9E%E5%BD%A9V1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/dTK
- 城市基础设施的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A5%9E%E5%BD%A9V1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/782=aye
- 社会体育指导的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A5%9E%E5%BD%A9V1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/kvs=316
- 学校体育活动的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A5%9E%E5%BD%A9V1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/AXW=4X7
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/379
- 乡村公共文化的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/zbq
- 城市公共艺术中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/tyA
- 基层健康服务的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/707=ljm
- 邻里共享空间的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/kuy=494
- 街区绿化养护的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/Zbl=akS
- 新能源出行的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BA%BA%E5%A4%A7?/551
- 乡村生活观察的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BA%BA%E5%A4%A7?/tjw
- 日常摄影记录的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BA%BA%E5%A4%A7?/SX1
- 邻里互助活动的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BA%BA%E5%A4%A7?/313=tmh
- 节假日出行安排的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BA%BA%E5%A4%A7?/guc=274
- 城市生活服务的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BA%BA%E5%A4%A7?/nTr=QAF
- 城市绿道建设的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A5%A8%E5%91%A2_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/982
- 学校体育活动的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A5%A8%E5%91%A2_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/wvw
- 老年人文化生活的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A5%A8%E5%91%A2_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/SKB
- 智能手机助老的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A5%A8%E5%91%A2_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/868=sap
- 社区科普课堂的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A5%A8%E5%91%A2_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/tsv=994
- 社区家政服务的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A5%A8%E5%91%A2_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/mLj=NTG
- 个人信息保护的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_360%E9%80%9A%E4%BF%A1?/876
- 家庭安全提示的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_360%E9%80%9A%E4%BF%A1?/fcr
- 城市社区治理的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_360%E9%80%9A%E4%BF%A1?/v97
- 公共设施维护的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_360%E9%80%9A%E4%BF%A1?/715=zea
- 便民维修服务的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_360%E9%80%9A%E4%BF%A1?/nyr=412
- 社区活动报名的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_360%E9%80%9A%E4%BF%A1?/hhx=C48
- 城市文化路线的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%98%AF%E8%B5%8C%E5%8D%9A%E8%BF%98%E6%98%AF%E8%AF%88%E9%AA%97_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%AE%BF?/835
- 数字生活课堂的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%98%AF%E8%B5%8C%E5%8D%9A%E8%BF%98%E6%98%AF%E8%AF%88%E9%AA%97_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%AE%BF?/gfi
- 社区商业活力的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%98%AF%E8%B5%8C%E5%8D%9A%E8%BF%98%E6%98%AF%E8%AF%88%E9%AA%97_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%AE%BF?/mLs
- 地方文化传播的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%98%AF%E8%B5%8C%E5%8D%9A%E8%BF%98%E6%98%AF%E8%AF%88%E9%AA%97_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%AE%BF?/135=tlq
- 地方旅游导览的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%98%AF%E8%B5%8C%E5%8D%9A%E8%BF%98%E6%98%AF%E8%AF%88%E9%AA%97_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%AE%BF?/jip=595
- 城市公共空间的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%98%AF%E8%B5%8C%E5%8D%9A%E8%BF%98%E6%98%AF%E8%AF%88%E9%AA%97_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%AE%BF?/kYN=BKI
- 绿色生活实践的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E8%83%BD%E6%8B%BF%E5%88%B0%E9%92%B1%E5%90%97_360%E4%B8%93%E6%A0%8F?/126
- 社区老年食堂的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E8%83%BD%E6%8B%BF%E5%88%B0%E9%92%B1%E5%90%97_360%E4%B8%93%E6%A0%8F?/qbe
- 科学信息获取的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E8%83%BD%E6%8B%BF%E5%88%B0%E9%92%B1%E5%90%97_360%E4%B8%93%E6%A0%8F?/lV6
- 青少年科技社团的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E8%83%BD%E6%8B%BF%E5%88%B0%E9%92%B1%E5%90%97_360%E4%B8%93%E6%A0%8F?/719=jjc
- 文化讲座服务的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E8%83%BD%E6%8B%BF%E5%88%B0%E9%92%B1%E5%90%97_360%E4%B8%93%E6%A0%8F?/lgh=647
- 个人数据管理的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E8%83%BD%E6%8B%BF%E5%88%B0%E9%92%B1%E5%90%97_360%E4%B8%93%E6%A0%8F?/4DY=q4T
- 小区公共照明的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97%E5%8F%AF%E9%9D%A0%E5%90%97_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/656
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97%E5%8F%AF%E9%9D%A0%E5%90%97_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/voo
- 社区垃圾回收的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97%E5%8F%AF%E9%9D%A0%E5%90%97_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/pTw
- 劳动教育实践的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97%E5%8F%AF%E9%9D%A0%E5%90%97_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/566=ugm
- 线上阅读资源的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97%E5%8F%AF%E9%9D%A0%E5%90%97_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/nzp=080
- 家庭健康管理的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97%E5%8F%AF%E9%9D%A0%E5%90%97_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/G7e=vPm
- 社区防暑服务的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91APP_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/046
- 儿童友好空间的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91APP_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/nqi
- 绿色快递包装的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91APP_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/LKB
- 读书会组织的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91APP_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/756=csw
- 社区家校合作的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91APP_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/ugv=954
- 城市地名文化从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91APP_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/ehQ=SBY
- 户外活动组织的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BC%9A%E9%80%A0%E6%88%90%E6%8B%98%E7%95%99%E5%90%97_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/532
- 小区停车协商的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BC%9A%E9%80%A0%E6%88%90%E6%8B%98%E7%95%99%E5%90%97_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/zaw
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BC%9A%E9%80%A0%E6%88%90%E6%8B%98%E7%95%99%E5%90%97_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/5FM
- 城市基础设施的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BC%9A%E9%80%A0%E6%88%90%E6%8B%98%E7%95%99%E5%90%97_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/063=nzi
- 便民服务窗口的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BC%9A%E9%80%A0%E6%88%90%E6%8B%98%E7%95%99%E5%90%97_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/ins=197
- 城市噪声观察的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BC%9A%E9%80%A0%E6%88%90%E6%8B%98%E7%95%99%E5%90%97_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/ezm=1Oc
- 青年就业服务的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B1%9E%E4%BA%8E%E8%BF%9D%E6%B3%95%E5%90%97_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/284
- 低碳社区实践的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B1%9E%E4%BA%8E%E8%BF%9D%E6%B3%95%E5%90%97_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/vag
- 老年数字阅读的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B1%9E%E4%BA%8E%E8%BF%9D%E6%B3%95%E5%90%97_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/YBl
- 校园社团活动的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B1%9E%E4%BA%8E%E8%BF%9D%E6%B3%95%E5%90%97_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/032=ffv
- 社区知识分享的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B1%9E%E4%BA%8E%E8%BF%9D%E6%B3%95%E5%90%97_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/rhq=849
- 运动安全知识的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B1%9E%E4%BA%8E%E8%BF%9D%E6%B3%95%E5%90%97_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/jQN=gEk
- 终身学习资源的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A6%82%E4%BD%95%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/280
- 社区便利生活的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A6%82%E4%BD%95%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/rey
- 光伏知识科普的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A6%82%E4%BD%95%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/NI2
- 乡村休闲旅游的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A6%82%E4%BD%95%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/412=kfy
- 老年人出行服务的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A6%82%E4%BD%95%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/lkw=279
- 社区知识分享的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A6%82%E4%BD%95%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/BE8=RHX
- 城市公共饮水的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E7%BD%91%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/901
- 公交站点体验的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E7%BD%91%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/qwf
- 志愿者培训交流的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E7%BD%91%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/akV
- 通勤路线规划的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E7%BD%91%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/464=bua
- 口袋公园建设中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E7%BD%91%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/sfn=599
- 社区知识分享的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E7%BD%91%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/NdB=vF7
- 日常摄影记录中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8F%AF%E4%BB%A5%E5%9C%A8%E5%BE%AE%E4%BF%A1%E6%8A%95%E6%B3%A8%E5%90%97_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/196
- 在线教育体验的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8F%AF%E4%BB%A5%E5%9C%A8%E5%BE%AE%E4%BF%A1%E6%8A%95%E6%B3%A8%E5%90%97_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/uqs
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8F%AF%E4%BB%A5%E5%9C%A8%E5%BE%AE%E4%BF%A1%E6%8A%95%E6%B3%A8%E5%90%97_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/SSp
- 公共设施维护的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8F%AF%E4%BB%A5%E5%9C%A8%E5%BE%AE%E4%BF%A1%E6%8A%95%E6%B3%A8%E5%90%97_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/973=rxh
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8F%AF%E4%BB%A5%E5%9C%A8%E5%BE%AE%E4%BF%A1%E6%8A%95%E6%B3%A8%E5%90%97_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/hsl=474
- 网络安全教育的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8F%AF%E4%BB%A5%E5%9C%A8%E5%BE%AE%E4%BF%A1%E6%8A%95%E6%B3%A8%E5%90%97_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/4iH=Asu
- 旧物循环利用的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%8F%AA%E8%83%BD%E5%8E%BB%E5%AE%9E%E4%BD%93%E5%BA%97%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/339
- 公共设施维护的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%8F%AA%E8%83%BD%E5%8E%BB%E5%AE%9E%E4%BD%93%E5%BA%97%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/hwa
- 环境教育课程的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%8F%AA%E8%83%BD%E5%8E%BB%E5%AE%9E%E4%BD%93%E5%BA%97%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/ne5
- 小区公共照明的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%8F%AA%E8%83%BD%E5%8E%BB%E5%AE%9E%E4%BD%93%E5%BA%97%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/723=oma
- 城市博物馆活动的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%8F%AA%E8%83%BD%E5%8E%BB%E5%AE%9E%E4%BD%93%E5%BA%97%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/gzp=401
- 社区志愿服务的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%8F%AA%E8%83%BD%E5%8E%BB%E5%AE%9E%E4%BD%93%E5%BA%97%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/IRV=Iz1
- 乡村教育资源的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/747
- 物业服务沟通的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/ivx
- 日常摄影记录的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/FwW
- 城市运动公园的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/039=iyt
- 城市应急广播的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/njp=005
- 数字地图应用的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/NJj=hBK
- 居家防滑改造的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/873
- 乡村教育资源的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/tld
- 绿色出行服务的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/CcG
- 市民热线服务的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/209=txv

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
