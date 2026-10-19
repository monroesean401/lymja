# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:22**

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

- 老年数字阅读的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_3550%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/rvy
- 社区共享书架的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_3550%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/400=ofh
- 骑行路线规划的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_3550%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/wko=871
- 城市文明实践的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_3550%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/PzU=Di1
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_3550%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%9C%AD%E8%AE%B0?/874
- 便民维修服务的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_3550%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%9C%AD%E8%AE%B0?/dfy
- 网络信息辨识的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_3550%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%9C%AD%E8%AE%B0?/5eP
- 家庭用电安全的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_3550%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%9C%AD%E8%AE%B0?/411=yoi
- 家庭理财科普的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_3550%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%9C%AD%E8%AE%B0?/szf=308
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_3550%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%9C%AD%E8%AE%B0?/1BI=kpg
- 绿色出行服务的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/938
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/svd
- 科技馆参观体验的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/vHB
- 社区设施共享的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/023=dtb
- 智慧城市体验中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/asn=563
- 社区邻里服务的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/IBO=Bcf
- 全民健身活动的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%8C%96?/325
- 乡村阅读空间的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%8C%96?/yhb
- 电动汽车充电的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%8C%96?/p3t
- 城市空气科普的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%8C%96?/296=lsq
- 社区环保活动中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%8C%96?/gce=337
- 灵活就业交流的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%8C%96?/zGP=q2m
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E4%BF%A1%E8%B4%B7?/247
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E4%BF%A1%E8%B4%B7?/ual
- 食品安全科普的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E4%BF%A1%E8%B4%B7?/xTN
- 社区宠物管理的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E4%BF%A1%E8%B4%B7?/659=pos
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E4%BF%A1%E8%B4%B7?/txv=851
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E4%BF%A1%E8%B4%B7?/nCd=47Y
- 消防知识宣传的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/799
- 城市便民驿站的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/jok
- 数字生活课堂的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/P17
- 老年数字阅读的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/710=pqi
- 城市慢行系统的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/lac=738
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/WgY=o4i
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/494
- 个人时间管理的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/vhw
- 家庭用电安全的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/fF6
- 周末休闲规划的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/343=dwp
- 节气饮食文化的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/utw=600
- 城市休闲步道的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/0U0=yFg
- 租房信息服务的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/266
- 市民意见收集的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/rpo
- 课后服务体验的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/367
- 科学健身方法的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/401=zsu
- 便民服务地图的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/hkh=634
- 城市空气科普的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/vDX=I4l
- 公共文化活动的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8C%BB%E8%8D%AF?/462
- 绿色办公实践的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8C%BB%E8%8D%AF?/vqr
- 城市慢行系统的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8C%BB%E8%8D%AF?/V3y
- 节日文化体验的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8C%BB%E8%8D%AF?/526=jeg
- 亲子科普活动的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8C%BB%E8%8D%AF?/fnr=636
- 社区快递服务的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8C%BB%E8%8D%AF?/tHx=RyT
- 乡村阅读活动的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E4%BC%97%E6%B5%8B?/781
- 职业技能学习的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E4%BC%97%E6%B5%8B?/njd
- 健康饮水科普的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E4%BC%97%E6%B5%8B?/iYl
- 传统手工艺体验的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E4%BC%97%E6%B5%8B?/286=exv
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E4%BC%97%E6%B5%8B?/emw=920
- 公园休闲体验的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E4%BC%97%E6%B5%8B?/mN3=jSg
- 乡村阅读空间的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/795
- 社区宠物管理的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/bed
- 公园休闲体验的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/23Y
- 光伏知识科普的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/471=nzu
- 网络安全教育的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/wiy=038
- 绿色出行服务的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/qTX=piv
- 科学睡眠习惯的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%99%E8%82%B2?/132
- 智能家居应用的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%99%E8%82%B2?/snm
- 本地历史资料的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%99%E8%82%B2?/lns
- 食品配送体验的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%99%E8%82%B2?/725=ppu
- 公共设施使用的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%99%E8%82%B2?/yyl=594
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%99%E8%82%B2?/T58=hsa
- 老年友好服务的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/638
- 城市夜间生活的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/pyh
- 街区更新实践的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/eE8
- 老年人日常照护的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/867=qiy
- 社区交通安全的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/gye=402
- 城市共享单车的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/UiE=3Nz
- 街道综合服务的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%A7%A3%E5%AF%86?/355
- 居民健康教育的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%A7%A3%E5%AF%86?/oba
- 旧物循环利用的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%A7%A3%E5%AF%86?/1AB
- 老旧小区改造的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%A7%A3%E5%AF%86?/226=gvm
- 创业经验分享的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%A7%A3%E5%AF%86?/qqw=186
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%A7%A3%E5%AF%86?/5Sr=OSD
- 青年志愿活动的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/563
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/cky
- 城市共享单车的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/TTi
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/521=eyw
- 亲子阅读活动的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/wku=682
- 急救知识普及的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/pM4=J8D
- 城市步行环境的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/772
- 数字课堂应用的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/uak
- 运动安全知识的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/nAb
- 家庭志愿活动的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/983=odz
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/oxw=503
- 公交站点体验的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/5gM=ef3
- 城市社区治理的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/014
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/lgl
- 节气饮食文化的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/7aj
- 绿色办公实践的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/059=ewv
- 家庭饮食安排的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/ukw=686
- 户外活动组织的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/hNI=baq
- 家庭食品保存的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%BB%BC%E8%89%BA?/329
- 公园亲子设施的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%BB%BC%E8%89%BA?/fom
- 城市公共厕所的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%BB%BC%E8%89%BA?/9Cu
- 社区便民服务的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%BB%BC%E8%89%BA?/573=jqs
- 老年友好服务的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%BB%BC%E8%89%BA?/cdy=897
- 数字学习资源的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%BB%BC%E8%89%BA?/kkN=3W9
- 农村环境治理的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/262
- 校园节能行动的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/ueo
- 城市骑行环境的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/snL
- 节约用水实践的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/984=ubg
- 劳动教育实践的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/jrk=886
- 节日文化体验的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/K9O=L7c
- 小区电梯维护的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/477
- 社区邻里服务的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/vng
- 智能手机助老的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/yyo
- 数字资源检索的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/394=yug
- 城市体育设施的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/vyy=740
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/Isz=3wS
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/254
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/rpx
- 社区活动策划的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/Ch4
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/284=ywk
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/wiv=974
- 绿色生活实践的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/iRe=6IG
- 社区便民服务的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_355%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/891
- 社区休闲设施的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_355%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/fel
- 社区志愿服务的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_355%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/OhW
- 绿色出行服务的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_355%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/350=znx
- 邻里共享空间的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_355%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/giy=047
- 校园社团活动的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_355%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/X1D=4QX
- 家庭科学教育的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/393
- 青少年职业启蒙的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/jfv
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/Uom
- 创业经验分享的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/846=tzp
- 家庭收纳实践的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/lqr=674
- 社区托育服务的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/O1V=3P0
- 应急物资管理的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/550
- 数字创作工具从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/rrn
- 数字设备回收的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/ghE
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/645=nco
- 街区更新实践的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/zaq=226
- 在线学习体验的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/Oh5=dld
- 社区生活指南的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/600
- 本地旅行体验的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/hwx
- 社区共享书架的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/Ib3
- 学校体育活动的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/795=hoh
- 开放数据应用的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/uny=724
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/nBG=rKW
- 线上办事服务的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/685
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/stc
- 青少年心理健康的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/Yw0
- 消防知识宣传的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/352=qky
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/toa=095
- 骑行路线规划的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/7PA=W8H
- 小区电梯维护的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/683
- 社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/xtc
- 运动安全知识的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/EjL
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/273=gfx
- 社区菜市场服务的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/inl=172
- 社区垃圾分类的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/s8C=ibA
- 家庭环保行动的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%94%B6%E8%97%8F?/256
- 社区邻里服务的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%94%B6%E8%97%8F?/gsd
- 读书会组织的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%94%B6%E8%97%8F?/iM5
- 公共场所导视的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%94%B6%E8%97%8F?/510=fux
- 城市人文观察的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%94%B6%E8%97%8F?/ila=137
- 社区商业活力的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%94%B6%E8%97%8F?/t3n=cwT
- 社区交通安全的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/749
- 社区消防演练的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/lob
- 基层健康档案的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/2ju
- 数字支付体验的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/806=ljz
- 零废弃生活尝试的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/jbw=241
- 气象科普传播的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/Phy=cS3
- 社区活动报名的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/101
- 公共交通信息服务的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/lfq
- 地方文化传播的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/OYv
- 社区消防演练的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/919=obb
- 老年人文化生活的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/nzy=611
- 乡村文化空间的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/rA4=VxS
- 城市农夫市集的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/992
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/dhc
- 图书馆活动策划的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/YQN
- 家庭运动计划的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/131=cit
- 药品使用科普的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/hax=088
- 儿童友好空间的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/HIf=7X8
- 公共健身器材的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_355%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/286
- 环境教育课程的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_355%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/dxw
- 城市博物馆活动的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_355%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/ann
- 社区公共议事的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_355%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/231=awr
- 小微企业服务的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_355%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/pxb=434
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_355%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/UoL=LEh
- 城市共享单车的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-APP_%E4%BA%AC%E4%B8%9C%E8%AE%B2%E5%9D%9B?/924
- 青年就业服务的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-APP_%E4%BA%AC%E4%B8%9C%E8%AE%B2%E5%9D%9B?/eme
- 旧物循环利用的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-APP_%E4%BA%AC%E4%B8%9C%E8%AE%B2%E5%9D%9B?/0mE
- 社区快递服务的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-APP_%E4%BA%AC%E4%B8%9C%E8%AE%B2%E5%9D%9B?/846=azg
- 线上阅读资源的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-APP_%E4%BA%AC%E4%B8%9C%E8%AE%B2%E5%9D%9B?/pjj=694
- 青少年科技社团的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-APP_%E4%BA%AC%E4%B8%9C%E8%AE%B2%E5%9D%9B?/bIG=Dkf
- 生活垃圾回收的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/497
- 地方美食文化的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/rux
- 公园亲子设施的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/z6b
- 数字档案服务的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/088=kik
- 地方文化传播的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/zzp=174
- 家庭养老规划的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/0SJ=S3V
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/834
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/fgv
- 青年志愿活动的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/2VX
- 家庭消费规划的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/921=jrr
- 城市公共饮水的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/whi=060
- 城市人文观察的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/lgw=Lhm
- 智能手机助老的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/304
- 市民意见收集的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/jdn
- 家庭急救准备的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/FZ8
- 儿童阅读角的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/306=ned
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/vcy=583
- 街头绿植养护的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/kX3=gKt
- 生活垃圾减量的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_355%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/421
- 邻里共享空间的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_355%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/mky
- 社区交通安全的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_355%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/8zH
- 老年人日常照护的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_355%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/723=nlo
- 乡村文化活动的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_355%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/qhg=744
- 城市文明实践的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_355%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/uBk=ZQ7
- 电动汽车充电的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_355%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/643
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_355%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ege
- 社区生活指南的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_355%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/WIi
- 公共场所导视的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_355%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/203=anv
- 社区修缮行动的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_355%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/tzn=384
- 乡村电商实践的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_355%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lfa=5s3
- 网络安全教育的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_355%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/171
- 物业服务沟通的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_355%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/wtf
- 儿童友好空间的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_355%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/Pea
- 儿童友好空间的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_355%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/740=pbc
- 公共交通接驳的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_355%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/cpg=354
- 街头绿植养护的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_355%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/IFI=q6m
- 数字生活课堂的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/922
- 城市基础设施的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/lso
- 网络信息辨识的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/9xe
- 街区绿化养护的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/194=mpb
- 公共卫生设施的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/rnn=765
- 本地旅行体验的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/Ws6=aI8
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_355%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/516
- 家庭节能设备的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_355%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/ptg
- 数字阅读服务的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_355%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/0lL
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_355%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/083=afg
- 文化场馆预约的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_355%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/oqc=042
- 智能家居应用的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_355%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/xo5=Zgx
- 儿童阅读角的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%95%B0%E7%A0%81?/198
- 儿童友好街区的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%95%B0%E7%A0%81?/gkv
- 音乐欣赏活动的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%95%B0%E7%A0%81?/tgp
- 城市人文观察的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%95%B0%E7%A0%81?/847=boc
- 街区道路维护的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%95%B0%E7%A0%81?/ajf=911
- 城市社区治理的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%95%B0%E7%A0%81?/jUZ=Ggo

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
