# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/kOd
- 青少年科普实践的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/990=bfk
- 本地消费场景的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/ohp=562
- 城市应急广播的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/HUY=xXd
- 数字创意课程的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/688
- 家庭健康管理的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/vha
- 农产品品牌传播的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/pLH
- 青少年户外教育的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/233=san
- 公共空间安全的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/mxb=979
- 小区停车协商的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/Uo3=PCN
- 家庭科学教育的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/654
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/fxh
- 城市空气科普的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/LyF
- 社区运动空间的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/683=yxk
- 社区法律科普中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/zvg=799
- 智慧停车服务的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/VjD=Du4
- 城市应急广播的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%861%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/064
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%861%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/kgp
- 青少年户外教育的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%861%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/Iue
- 绿色生活实践的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%861%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/496=fua
- 城市共享单车的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%861%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/qyy=130
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%861%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/iKT=IAh
- 健康饮水科普的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/411
- 绿色快递包装的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/ryx
- 公共服务沟通的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/bWA
- 城市绿色交通的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/759=fnp
- 家庭健康管理的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/vbl=807
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/DZH=3IV
- 在线教育体验的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E6%BE%8E%E6%B9%83%E6%B6%88%E8%B4%B9?/174
- 校园社团活动的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E6%BE%8E%E6%B9%83%E6%B6%88%E8%B4%B9?/stb
- 志愿者培训交流的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E6%BE%8E%E6%B9%83%E6%B6%88%E8%B4%B9?/Mpx
- 公共空间休憩的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E6%BE%8E%E6%B9%83%E6%B6%88%E8%B4%B9?/022=hxp
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E6%BE%8E%E6%B9%83%E6%B6%88%E8%B4%B9?/vwo=327
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E6%BE%8E%E6%B9%83%E6%B6%88%E8%B4%B9?/HT9=7NU
- 社区防暑服务的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E8%84%89%E8%84%89%E6%88%BF%E4%BA%A7?/059
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E8%84%89%E8%84%89%E6%88%BF%E4%BA%A7?/uid
- 环境教育课程的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E8%84%89%E8%84%89%E6%88%BF%E4%BA%A7?/M1g
- 青年职业探索的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E8%84%89%E8%84%89%E6%88%BF%E4%BA%A7?/706=snd
- 基层健康档案的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E8%84%89%E8%84%89%E6%88%BF%E4%BA%A7?/hws=727
- 家庭环保行动的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E8%84%89%E8%84%89%E6%88%BF%E4%BA%A7?/BSG=NPK
- 儿童安全出行的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/507
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/upn
- 居家适老化改造的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/n6S
- 家庭急救准备的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/974=qna
- 全民阅读推广的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/flg=898
- 节能家电使用的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/lD1=qjh
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/120
- 无障碍出行的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/qnv
- 城市休闲步道的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/wd1
- 家庭环保行动的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/462=dbz
- 个人数据管理的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/hrs=088
- 乡村教育资源的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/kZS=GUU
- 新能源出行的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A_360%E9%80%9A%E4%BF%A1?/289
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A_360%E9%80%9A%E4%BF%A1?/beg
- 城市博物馆服务的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A_360%E9%80%9A%E4%BF%A1?/RcK
- 电动汽车充电的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A_360%E9%80%9A%E4%BF%A1?/555=rph
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A_360%E9%80%9A%E4%BF%A1?/dma=539
- 城市绿道建设的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A_360%E9%80%9A%E4%BF%A1?/BAV=KdH
- 地方美食文化的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/124
- 城市生活记录的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/mtw
- 公共空间安全的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/gMO
- 老年人日常照护的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/293=rsx
- 公共场馆服务从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/dky=798
- 日常摄影记录的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/lmB=sHY
- 儿童运动体验的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%8E%A9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/235
- 药品使用科普的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%8E%A9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/csg
- 社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%8E%A9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/HEJ
- 社区文化节活动的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%8E%A9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/701=xdc
- 老年人出行服务的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%8E%A9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/rxl=786
- 家庭健康管理的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%8E%A9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/eyH=lrI
- 城市体育设施的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/464
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/gsk
- 儿童安全出行的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/MsC
- 城市骑行环境的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/966=xxb
- 家庭教育交流的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/njy=302
- 街区道路维护的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/caq=KcG
- 家庭防灾准备的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/880
- 数字便民地图的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/zjx
- 绿色生活实践中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/bOd
- 社区艺术活动的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/546=krg
- 公共服务指南的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/lar=188
- 信息无障碍体验的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/LPP=zUE
- 社区便民集市的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/982
- 社区便利生活的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/psk
- 城市可持续生活的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/uaY
- 智能家居应用的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/281=jjl
- 社区生活指南中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/pax=458
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/N36=cqs
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%88%B7%E6%B5%81%E6%B0%B4%E5%8C%85%E8%B5%94_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/788
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%88%B7%E6%B5%81%E6%B0%B4%E5%8C%85%E8%B5%94_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/mhj
- 乡村公共服务的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%88%B7%E6%B5%81%E6%B0%B4%E5%8C%85%E8%B5%94_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/SE3
- 邻里共享空间的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%88%B7%E6%B5%81%E6%B0%B4%E5%8C%85%E8%B5%94_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/320=izx
- 公共设施维护的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%88%B7%E6%B5%81%E6%B0%B4%E5%8C%85%E8%B5%94_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/dly=447
- 数字政务体验的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%88%B7%E6%B5%81%E6%B0%B4%E5%8C%85%E8%B5%94_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/eJY=5Gl
- 科学信息获取的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/536
- 全民健身活动的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/rqz
- 城市社区治理的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/rQI
- 街区更新实践中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/260=tsp
- 数字政务体验的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/enm=264
- 校园安全教育的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/Qzk=7w6
- 机器学习入门的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/232
- 市民意见收集的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/vao
- 城市骑行环境的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/fN5
- 社区体育组织的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/895=hxe
- 社区体育组织的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/dno=073
- 儿童运动体验的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/umQ=LIe
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/499
- 社区休闲设施的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/ixt
- 数字阅读服务的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/AuI
- 城市绿色交通的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/185=tjm
- 休闲运动入门的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/izt=231
- 公益活动组织的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/YAK=ToI
- 智能手机助老的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A81%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%91%98_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/883
- 职业技能学习的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A81%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%91%98_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/gaw
- 生成式工具使用的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A81%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%91%98_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/aUS
- 公共服务沟通的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A81%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%91%98_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/479=tmu
- 居家防滑改造的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A81%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%91%98_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/fes=253
- 社区体育组织的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A81%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%91%98_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/q9e=ceW
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/179
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/zsh
- 城乡交通衔接的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/fyU
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/691=hzt
- 社区设施共享的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/xwt=720
- 地方美食文化的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/rgt=ZpC
- 社区知识分享的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/693
- 课后服务体验的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/vmu
- 开放式学习空间的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/e0W
- 社区家政服务的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/940=wrm
- 数字便民地图的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/rgg=754
- 城市运动公园的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/ehY=srU
- 科学观察活动的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E5%87%BA%E5%90%8D%E7%9A%84%E5%9B%A2%E9%98%9F_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/321
- 数字公共文化的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E5%87%BA%E5%90%8D%E7%9A%84%E5%9B%A2%E9%98%9F_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/jwm
- 公共场所导视的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E5%87%BA%E5%90%8D%E7%9A%84%E5%9B%A2%E9%98%9F_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/eMe
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E5%87%BA%E5%90%8D%E7%9A%84%E5%9B%A2%E9%98%9F_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/743=oxv
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E5%87%BA%E5%90%8D%E7%9A%84%E5%9B%A2%E9%98%9F_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/xqr=692
- 城市地名文化的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E5%87%BA%E5%90%8D%E7%9A%84%E5%9B%A2%E9%98%9F_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/Y3o=NOq
- 家庭消费规划的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/758
- 网络安全教育的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/hqz
- 公共设施维护中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/GXq
- 家庭安全提示的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/905=hid
- 气象科普传播的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/cpe=746
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/zyz=5Ei
- 家庭节能实践的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%8D%B3%E5%88%BB%E8%A1%8C%E6%83%85?/211
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%8D%B3%E5%88%BB%E8%A1%8C%E6%83%85?/ebx
- 开源技术交流的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%8D%B3%E5%88%BB%E8%A1%8C%E6%83%85?/6Iv
- 城乡公共服务的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%8D%B3%E5%88%BB%E8%A1%8C%E6%83%85?/429=koe
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%8D%B3%E5%88%BB%E8%A1%8C%E6%83%85?/xdq=158
- 农贸市场环境中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%8D%B3%E5%88%BB%E8%A1%8C%E6%83%85?/UYW=QWY
- 城市绿色交通的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/433
- 城市共享单车的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/iuv
- 亲子科普活动的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/91N
- 社区体育组织的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/122=omq
- 节日文化体验的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/doq=127
- 社区儿童活动的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%9B%9E%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/U7U=tOm
- 光伏知识科普的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/908
- 生活服务数字化的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/yag
- 线上阅读资源的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/UfB
- 远程协作工具的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/604=yya
- 城市慢行系统的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/ehj=514
- 绿色生活实践的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/1Sp=arU
- 公共服务预约的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E5%87%BA%E6%AC%BE%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/864
- 乡村文化活动的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E5%87%BA%E6%AC%BE%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/ixy
- 周末休闲规划的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E5%87%BA%E6%AC%BE%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/i0w
- 公共空间导览的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E5%87%BA%E6%AC%BE%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/631=lyq
- 街区更新实践的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E5%87%BA%E6%AC%BE%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/wou=481
- 公园休闲体验的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E5%87%BA%E6%AC%BE%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/eUb=hgS
- 数字公共文化的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/888
- 城市公共厕所中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/idw
- 课后服务体验的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/JQi
- 数字公共文化的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/770=ogd
- 社区体育组织的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/gnx=807
- 农产品消费体验的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/0Ol=Zqz
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/287
- 家庭理财科普的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/wuc
- 地方美食文化的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/zBt
- 社区健康讲座的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/241=osr
- 老年智能设备的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/lqo=567
- 家庭理财科普的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/5bw=Xs2
- 社区共享书架的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/153
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/jgp
- 学校食育活动的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/hzF
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/881=lkx
- 公共交通接驳的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/cye=126
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/0vB=ttX
- 垃圾分类指导的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E5%9B%A2%E9%98%9F_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/648
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E5%9B%A2%E9%98%9F_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/njj
- 数字创意课程的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E5%9B%A2%E9%98%9F_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/ruV
- 公交无障碍服务的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E5%9B%A2%E9%98%9F_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/710=uuw
- 在线教育体验的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E5%9B%A2%E9%98%9F_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/egh=380
- 城市公共艺术中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E5%9B%A2%E9%98%9F_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/6qe=eYS
- 城市休闲步道的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/202
- 儿童友好空间的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/boe
- 青年志愿活动中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/mHj
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/154=urd
- 健康饮食教育的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/pou=841
- 公交站点体验的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/rAI=iwU
- 健康步道使用的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/573
- 线上办事服务的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/hng
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/e4G
- 公共服务数字化中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/457=hzb
- 社区文化传播的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/mjc=970
- 家庭健康管理的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/FEC=54y
- 运动安全知识的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/541
- 家庭健康管理的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/dwh
- 儿童友好街区的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/TPb
- 社区科普课堂的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/784=ree
- 老年友好服务的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/zip=915
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/BwS=j7D
- 校园社团活动的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A7%81%E5%B8%A6%E7%9B%88%E5%88%A9%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/009
- 农产品消费体验的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A7%81%E5%B8%A6%E7%9B%88%E5%88%A9%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/ezg
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A7%81%E5%B8%A6%E7%9B%88%E5%88%A9%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/kmx
- 街区道路维护的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A7%81%E5%B8%A6%E7%9B%88%E5%88%A9%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/000=jgm
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A7%81%E5%B8%A6%E7%9B%88%E5%88%A9%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/jnf=582
- 节假日出行安排的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A7%81%E5%B8%A6%E7%9B%88%E5%88%A9%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/J2H=WiT
- 老旧小区改造的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/874
- 公共服务沟通的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/kzw
- 社区应急准备的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/eog
- 城市步行环境的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/101=crg
- 社区法律科普的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/cgm=237
- 公共空间导览的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/DBP=KuX
- 职业技能学习的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AF%84?/973
- 社区文化传播的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AF%84?/shv
- 数字学习资源的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AF%84?/pqd
- 公共空间休憩的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AF%84?/072=zzi
- 科学健身方法的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AF%84?/uln=304
- 城市适老服务的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AF%84?/ywY=oDO
- 家庭用电安全的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/289
- 城市微更新实践的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/yge
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/ps0
- 小区停车协商的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/834=gka
- 家庭健康管理的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/htq=020
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/efq=GCJ
- 垃圾分类指导的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/666
- 城市公共自行车的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/pkw
- 城市空气科普的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/AvR
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/483=onc
- 城乡交流活动的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/mto=125
- 数字学习资源的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/hcP=ybP
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9C%9F%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E6%BC%AB%E8%AF%84?/849
- 农产品品牌传播的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9C%9F%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E6%BC%AB%E8%AF%84?/fes
- 新能源知识普及的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9C%9F%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E6%BC%AB%E8%AF%84?/Xr4
- 乡村文化空间的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9C%9F%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E6%BC%AB%E8%AF%84?/632=tqi
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9C%9F%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E6%BC%AB%E8%AF%84?/wfr=366
- 无障碍出行的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9C%9F%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E6%BC%AB%E8%AF%84?/FrT=Fsz
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84qq_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/512
- 城市微更新实践的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84qq_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/xur
- 乡村教育资源的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84qq_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/LEp
- 公园休闲体验的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84qq_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/595=sdv
- 社区便民集市的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84qq_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/zdy=316
- 社区体育组织的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84qq_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/y4J=C42

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
