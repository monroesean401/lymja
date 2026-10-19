# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:17**

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

- 职业技能学习中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%95%8C%E9%9D%A2%E8%BD%AC%E8%BD%BD?/744
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%95%8C%E9%9D%A2%E8%BD%AC%E8%BD%BD?/xof
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%95%8C%E9%9D%A2%E8%BD%AC%E8%BD%BD?/AxS
- 社区儿童活动的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%95%8C%E9%9D%A2%E8%BD%AC%E8%BD%BD?/336=rlc
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%95%8C%E9%9D%A2%E8%BD%AC%E8%BD%BD?/xay=062
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%95%8C%E9%9D%A2%E8%BD%AC%E8%BD%BD?/aLD=Vk5
- 便民服务地图的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/626
- 乡村电商实践的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/npp
- 在线教育体验的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/N1y
- 社区家校合作的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/162=wuz
- 基层健康档案的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/gas=068
- 小区停车协商的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/KtB=jkB
- 城市步行友好的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/300
- 家庭安全提示的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/drw
- 租房信息服务的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/ClH
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/200=bla
- 公共场馆服务的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/xxd=996
- 社区活动策划的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/z3z=RYL
- 街区道路维护的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/788
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/yna
- 城市运动公园的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/kxz
- 食品配送体验中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/701=ipr
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/gwl=952
- 科普展览体验的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/U3w=WT8
- 城市住房服务的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/985
- 地方戏曲体验的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/cbw
- 城市公共自行车的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/rbz
- 公共设施维护的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/454=xwf
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/tud=122
- 个人数据管理的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/qSu=QfP
- 数字设备回收的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/265
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/qfm
- 城市人文观察的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/gd5
- 城市步行环境的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/844=scp
- 数字便民地图的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/eop=120
- 社区消防演练的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/MaP=7Ov
- 食品安全科普的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/751
- 城市体育设施的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/sed
- 科普展览体验的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/c3v
- 地方美食文化的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/024=uyw
- 社区活动策划的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/gqx=968
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/ygW=6dx
- 城乡交流活动的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/285
- 社区科普课堂的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/spw
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/AZA
- 公共空间导览的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/544=xwn
- 食品配送体验的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/orp=592
- 城市骑行环境的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/6aP=cK0
- 科学健身方法的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/866
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/gmi
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/bqm
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/694=svp
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/vmf=558
- 本地历史资料的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/2SS=WTe
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/628
- 社区故事采集的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/oiv
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/0hw
- 家庭养老规划的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/603=ysh
- 公共空间照明的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/ius=734
- 传统节日科普的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/540=Dfp
- 电子商务服务的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%901%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/859
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%901%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/hgs
- 农村环境治理的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%901%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/8xJ
- 科技馆参观体验的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%901%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/152=hym
- 公共场所导视的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%901%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/wqc=237
- 乡村电商实践的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%901%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AF%84?/rri=yJX
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/958
- 灵活就业交流的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/qua
- 社区菜市场服务从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/B0m
- 社区文化节活动的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/912=uex
- 城市宠物友好空间的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/dol=657
- 基层健康档案的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/r8I=sUL
- 乡村阅读空间的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/642
- 药品使用科普的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/zmq
- 小微企业服务的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/D6f
- 劳动教育实践的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/656=ysx
- 家庭安全提示的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/kkl=563
- 数字创作工具的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/IAZ=TNw
- 城市适老服务的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/911
- 健康信息获取的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/yoo
- 无障碍信息设计的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/Eop
- 社区宣传栏更新的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/517=oka
- 城市夜间生活的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/vex=200
- 节能生活方式的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/KNx=557
- 城市骑行环境的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_360%E5%8F%B8%E6%B3%95?/739
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_360%E5%8F%B8%E6%B3%95?/jmb
- 消防知识宣传的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_360%E5%8F%B8%E6%B3%95?/A7V
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_360%E5%8F%B8%E6%B3%95?/415=lgk
- 街道综合服务的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_360%E5%8F%B8%E6%B3%95?/pck=777
- 读书会组织的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_360%E5%8F%B8%E6%B3%95?/4Zt=cM3
- 老年学习活动的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_36%E6%B0%AA%E9%94%90%E8%AF%84?/066
- 学校体育活动的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_36%E6%B0%AA%E9%94%90%E8%AF%84?/kyt
- 社区花园共建的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_36%E6%B0%AA%E9%94%90%E8%AF%84?/tYC
- 全民健身活动的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_36%E6%B0%AA%E9%94%90%E8%AF%84?/012=erw
- 老年学习活动的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_36%E6%B0%AA%E9%94%90%E8%AF%84?/pxi=566
- 智慧城市体验的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_36%E6%B0%AA%E9%94%90%E8%AF%84?/fx9=fHh
- 基层服务创新的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/368
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/zla
- 社区设施共享的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/Kkt
- 社区便民服务的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/923=alu
- 老年人日常照护的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/syl=098
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/lOu=bv9
- 生活技能分享的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E6%B1%87%E5%B8%82?/508
- 社区共享书架的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E6%B1%87%E5%B8%82?/twu
- 小区电梯维护的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E6%B1%87%E5%B8%82?/fvV
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E6%B1%87%E5%B8%82?/450=ukz
- 志愿者培训交流的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E6%B1%87%E5%B8%82?/gqb=827
- 城市休闲步道的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E6%B1%87%E5%B8%82?/F2b=FBL
- 乡村阅读空间的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/020
- 食品配送体验的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/otj
- 校园社团活动中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/jCx
- 邻里互助活动的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/221=nun
- 生活技能分享的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/atf=293
- 校园节能行动的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/0Y5=RQL
- 开源技术交流的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E7%99%BE%E5%BA%A6%E7%BB%BC%E8%89%BA?/638
- 智慧城市体验的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E7%99%BE%E5%BA%A6%E7%BB%BC%E8%89%BA?/qrh
- 社区活动空间的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E7%99%BE%E5%BA%A6%E7%BB%BC%E8%89%BA?/6eX
- 学校体育活动的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E7%99%BE%E5%BA%A6%E7%BB%BC%E8%89%BA?/628=sxi
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E7%99%BE%E5%BA%A6%E7%BB%BC%E8%89%BA?/qtt=458
- 非遗体验活动的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E7%99%BE%E5%BA%A6%E7%BB%BC%E8%89%BA?/Xgh=kbg
- 城市公共饮水的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/890
- 城市基础设施的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/hzh
- 医院导诊服务的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/YlV
- 便民服务地图的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/693=bxn
- 社区手工活动的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/cgy=130
- 智慧城市体验的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/3jA=jwf
- 家庭消费规划的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/958
- 城市人文观察的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/usk
- 城市步行友好的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/FUu
- 志愿服务平台的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/501=ddq
- 文化遗产保护科普的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/vsq=549
- 地方文化传播的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/E2S=I4l
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/430
- 家庭运动计划的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/hoq
- 社区休闲设施的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/QFc
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/833=smk
- 家庭照护支持的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/kep=641
- 家庭安全提示的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/6Ir=ZVO
- 街区小店体验的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/861
- 老年人文化生活的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/svp
- 社区快递服务的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/S2c
- 本地消费场景的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/120=wee
- 青少年科技社团的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/qje=968
- 城市应急科普的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/Kav=uAz
- 公共设施使用的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/457
- 小微企业服务的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/icg
- 城市宠物友好空间的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/ZmD
- 社区协商议事的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/373=byd
- 城市骑行环境的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/shu=989
- 健康信息获取的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/sA9=j8G
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/328
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/uly
- 城市博物馆活动的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/0Nf
- 个人数据管理的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/006=koc
- 低碳社区实践中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/eth=343
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/Lub=AMm
- 城市夜间生活的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/187
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/zju
- 社区交通安全的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/kPB
- 社区停车服务的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/047=pcc
- 家庭急救准备的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/lrn=960
- 城市绿道建设的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/ElI=3B8
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/633
- 城乡公共服务的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/ykj
- 市民热线服务的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/7Yl
- 城市文化路线的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/807=vsz
- 旧物循环利用中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/iqp=922
- 乡村公共服务有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/Sdd=tOd
- 食品配送体验的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/182
- 青少年编程学习的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/nqv
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/wJx
- 数字阅读服务的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/477=bah
- 城市公共标识的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/rgb=594
- 社区健康讲座的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/UOl=J6R
- 课后服务体验的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9B%B2%E8%89%BA?/611
- 社区便利生活的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9B%B2%E8%89%BA?/rpr
- 基层医疗预约的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9B%B2%E8%89%BA?/LaN
- 机器学习入门的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9B%B2%E8%89%BA?/368=fki
- 乡村阅读活动的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9B%B2%E8%89%BA?/wuu=388
- 乡村公共服务的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9B%B2%E8%89%BA?/ewb=6Mh
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/862
- 公共空间照明的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/zho
- 老年友好服务的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/P4L
- 环境教育课程的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/000=zhe
- 劳动教育实践的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/dbf=817
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/CzT=I7G
- 青少年科普实践的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/794
- 青少年编程学习的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/ewi
- 公共健身器材的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/opP
- 公益活动组织的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/006=iwj
- 家庭网络使用的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/ahe=035
- 便民维修服务的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/Ff5=6gH
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/145
- 开放数据应用的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/mxx
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/XkE
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/115=ksn
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/ihp=886
- 药品使用科普的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/MNm=sh2
- 在线学习体验的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/041
- 生活服务数字化的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/naj
- 社区生活指南的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/xHb
- 城市便民驿站的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/546=mka
- 社区志愿服务的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/qzh=188
- 公共场馆服务的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/8W2=24a
- 街区绿化养护的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/397
- 城乡交流活动的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/iaf
- 城市文明出行的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/jMx
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/538=bjr
- 城市步行环境的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/vfj=215
- 物业服务沟通的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/y1x=3io
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/250
- 城市骑行环境的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/mdd
- 城市微更新实践的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/HzN
- 全民健身活动的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/488=mks
- 社区便民集市的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/lle=252
- 公共服务数字化的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/NED=b7N
- 开放式学习空间的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/935
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/fkp
- 公园亲子设施的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/SeJ
- 社区防暑服务的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/234=vjj
- 城市环境志愿行动的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/fvp=349
- 运动安全知识的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/MrH=7WU
- 社区知识分享的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/541
- 科学教育活动的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/vtf
- 食品配送体验的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/3eZ
- 社区活动空间的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/121=vob
- 低碳社区实践的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/shw=015
- 乡村生态旅游的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/mUg=Rwg
- 本地消费场景的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/027
- 数字创作工具的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/krx
- 城市文明出行的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/rdA
- 家庭健康管理的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/201=zyy
- 绿色出行服务的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/muo=729
- 数字档案服务的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/VM2=OAX
- 社区托育服务的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/467
- 垃圾分类指导的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/kco
- 社区手工活动的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/pOw
- 社区体育组织的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/865=jgg
- 药品使用科普的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/pkq=662
- 志愿者培训交流的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/m2v=0YE
- 日常摄影记录的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3_%E8%84%89%E8%84%89%E5%81%A5%E5%BA%B7?/703
- 环境教育课程的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3_%E8%84%89%E8%84%89%E5%81%A5%E5%BA%B7?/sdv
- 节假日出行安排的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3_%E8%84%89%E8%84%89%E5%81%A5%E5%BA%B7?/lq4
- 文化讲座服务的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3_%E8%84%89%E8%84%89%E5%81%A5%E5%BA%B7?/227=ypf
- 社区便民集市的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3_%E8%84%89%E8%84%89%E5%81%A5%E5%BA%B7?/rem=143
- 运动安全知识的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3_%E8%84%89%E8%84%89%E5%81%A5%E5%BA%B7?/scR=l6n
- 社区宠物管理的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/297
- 青年志愿活动的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/pdg
- 城市博物馆服务的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/EHk
- 环境监测科普的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/333=vqr

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
