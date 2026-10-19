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

- 开放数据应用的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_379%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/553
- 科学观察活动的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_379%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/nct
- 社区菜市场服务的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_379%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/M8J
- 数字阅读服务的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_379%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/563=rol
- 社区公共卫生的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_379%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/yud=789
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_379%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/w2m=Xba
- 基层健康档案的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_379%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B8%E6%B3%95?/241
- 青年志愿活动的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_379%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B8%E6%B3%95?/fjl
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_379%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B8%E6%B3%95?/zgp
- 公园无障碍服务的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_379%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B8%E6%B3%95?/091=wpn
- 节气饮食文化的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_379%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B8%E6%B3%95?/ivi=954
- 绿色办公实践的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_379%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B8%E6%B3%95?/ufe=Ejh
- 线上办事服务的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/647
- 节能家电使用的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/lgt
- 数字地图应用的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/05I
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/048=mpc
- 周末休闲规划的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/rbn=361
- 家庭收纳实践的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/X0j=iNf
- 公共服务预约的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/586
- 街区更新实践的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/yla
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/q0A
- 网络安全教育的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/356=elh
- 城市夜间照明的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/ybt=074
- 个人时间管理的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/lnq=EtC
- 老年友好服务的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%86%9B%E4%BA%8B?/785
- 社区学习活动的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%86%9B%E4%BA%8B?/uxs
- 公共空间安全的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%86%9B%E4%BA%8B?/oGR
- 环境教育课程的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%86%9B%E4%BA%8B?/855=ubn
- 图书馆数字服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%86%9B%E4%BA%8B?/kek=912
- 食品安全科普的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%86%9B%E4%BA%8B?/Put=ew2
- 城市公共标识的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/315
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/vmg
- 户外活动组织的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/0Tn
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/974=xjg
- 家庭消费规划的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/eue=892
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/T00=x6b
- 社区知识分享的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/620
- 个人信息保护的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/klu
- 社区垃圾回收的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/Rpg
- 城市环境志愿行动的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/724=pvp
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/epm=942
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/0eS=CWf
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/191
- 开放式学习空间的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/mym
- 绿色校园实践的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/gQX
- 公共交通接驳的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/082=urd
- 家庭养老规划的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/sdu=662
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/ryY=9LG
- 低碳社区实践的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/582
- 家庭科学教育的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/rqc
- 城市便民驿站的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/Gba
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/178=bqv
- 社区心理支持的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/zsz=872
- 口袋公园建设的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/T74=Npw
- 农产品消费体验的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/794
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/zgc
- 社区法律科普的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/ONq
- 老年人日常照护的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/116=gxo
- 青少年户外教育的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/xqe=088
- 周末休闲规划的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/5YP=iBf
- 社区艺术活动的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/633
- 邻里互助活动的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/nkf
- 城市可持续生活的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/QFT
- 城市步行友好的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/903=dyd
- 家庭照护支持的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/nnp=648
- 环境监测科普的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/ekd=2S9
- 公共空间休憩中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/157
- 家庭节能实践中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/ldg
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/g1n
- 社区托育服务的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/672=iot
- 健康步道使用的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/rvb=885
- 乡村阅读空间的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/1tR=5l0
- 社区设施共享的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/111
- 社区养老服务的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/tex
- 数据分析入门的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/7bx
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/502=jfh
- 小区电梯维护的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/obe=619
- 图书借阅体验的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/ggg=CVE
- 家庭健康管理的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/814
- 信息无障碍体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/gro
- 急救知识普及的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/0xJ
- 公园无障碍服务的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/061=hsg
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/sgn=888
- 人工智能科普的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/7hJ=gn0
- 家庭饮食安排的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/969
- 城市休闲步道的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/piq
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/GQE
- 城市公共座椅的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/538=wut
- 传统节日科普的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/efo=266
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/JDQ=zo3
- 城市可持续生活的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/112
- 社区法律科普的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/ryw
- 社区文化传播的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/HRP
- 家庭阅读计划的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/471=rts
- 家庭教育交流的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/ask=858
- 社区老年食堂的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/RCv=S9I
- 社区体育组织的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/453
- 物业服务沟通中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/ale
- 科学教育活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/q39
- 社区志愿服务的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/603=gmu
- 家庭理财科普的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/oyx=169
- 城市噪声观察的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/6Tc=Ss5
- 公共服务数字化的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/060
- 社区故事采集的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/eyl
- 生成式工具使用中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/CsR
- 数字资源检索的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/734=hya
- 公共交通信息服务的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/abv=754
- 社区读书角建设的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/caI=3xg
- 城市文明出行的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/132
- 在线教育体验的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/byf
- 图书借阅体验的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/rI7
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/642=nba
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/xqi=210
- 家庭网络使用的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/JjK=7ZC
- 公共设施维护的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/947
- 开源技术交流的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/szp
- 城市微更新实践的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/DSy
- 户外活动组织的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/530=svg
- 乡村生态观察的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/sgg=067
- 家庭网络使用的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/GvN=ku2
- 儿童运动体验的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%BD%AC%E8%BD%BD?/510
- 家庭照护支持有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%BD%AC%E8%BD%BD?/khy
- 城市共享单车的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%BD%AC%E8%BD%BD?/QqL
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%BD%AC%E8%BD%BD?/597=cll
- 社区信息发布的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%BD%AC%E8%BD%BD?/ngc=670
- 邻里互助活动的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%BD%AC%E8%BD%BD?/67q=iKH
- 家庭消费规划的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/911
- 城市慢行系统的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/car
- 城市社区治理的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/86r
- 光伏知识科普的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/450=nxa
- 文明养宠科普的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/lum=559
- 个人信息保护的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/ejH=nkM
- 软件开发学习的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/360
- 家庭养老规划的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/qzr
- 街区更新实践的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/uDF
- 城市生活记录的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/967=emu
- 乡村文化空间的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/pmv=353
- 数字艺术创作的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/nDz=QJd
- 通勤路线规划的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/718
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/uys
- 地方文化传播的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/kHn
- 城市慢跑路线的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/182=acr
- 数字学习资源的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/abq=019
- 科学信息获取的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_3%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/7zd=yx6
- 城市文化路线的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/446
- 社区应急准备的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/djw
- 街区更新实践的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/82D
- 个人数据管理的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/150=jfi
- 城市公共标识的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/uvb=703
- 社区读书角建设的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/ivb=BW9
- 家庭饮食安排的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_3%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/314
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_3%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/jxs
- 家庭节能设备中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_3%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/bXX
- 家庭教育交流中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_3%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/768=rvb
- 社区交通安全的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_3%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/fuc=865
- 社区托育服务的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_3%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/ALe=5jE
- 城市公共厕所的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%AF%BB%E4%B9%A6?/074
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%AF%BB%E4%B9%A6?/uyi
- 数字资源检索的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%AF%BB%E4%B9%A6?/MXd
- 便民维修服务的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%AF%BB%E4%B9%A6?/418=rdw
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%AF%BB%E4%B9%A6?/kqn=032
- 租房信息服务的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%AF%BB%E4%B9%A6?/Url=m5L
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/702
- 社区体育组织的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/ueb
- 城市骑行环境的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/Kor
- 城乡交流活动的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/578=kex
- 社区便民集市的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/wyc=903
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/5w8=PHD
- 城市适老服务的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/629
- 家庭健康管理的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/skq
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/7mz
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/422=jbe
- 城市生活服务的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/xxi=598
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/dgb=U2s
- 校园节能行动的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/720
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/cvc
- 本地历史资料的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/zZg
- 社区消防演练的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/604=dzf
- 公共服务指南的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/eld=022
- 个人数据管理的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/zFI=8A1
- 社区活动策划的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/221
- 城市运动公园的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/jxc
- 社区慢性病防控的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/FA9
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/501=wyb
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/itj=840
- 儿童户外活动的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%9B%98%E7%82%B9?/5HN=WuN
- 读书会组织的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/044
- 社区运动空间的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/uqy
- 城市文明出行的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/QhQ
- 社区菜市场服务的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/837=rqb
- 人工智能科普的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/xev=168
- 数字创意课程的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/VXI=qb6
- 全民健身活动的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/450
- 城市雨天出行的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/kch
- 青少年户外教育的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/2hh
- 亲子阅读活动的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/800=vjd
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/mpl=776
- 城市应急科普的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/4zV=cYf
- 社区公共议事的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/353
- 城市文明实践的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/cuf
- 公园亲子设施的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/60i
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/270=tyu
- 数字阅读服务的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/cke=726
- 智能家居应用有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/RKW=A8y
- 青年志愿活动的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/787
- 城市游园体验的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/dxm
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/qda
- 气象科普传播有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/073=ijb
- 城市建设科普的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/rps=224
- 本地消费场景的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/fK4=P6d
- 城市空气科普的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_3%E5%8F%B7%E5%A8%B1%E4%B9%90-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/535
- 社区垃圾分类的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_3%E5%8F%B7%E5%A8%B1%E4%B9%90-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/uki
- 社区故事采集的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_3%E5%8F%B7%E5%A8%B1%E4%B9%90-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/iqE
- 创业经验分享的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_3%E5%8F%B7%E5%A8%B1%E4%B9%90-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/747=zik
- 社区阅读服务的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_3%E5%8F%B7%E5%A8%B1%E4%B9%90-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/els=288
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_3%E5%8F%B7%E5%A8%B1%E4%B9%90-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/TGI=NTb
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_3%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/822
- 社区读书角建设的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_3%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/wks
- 文化场馆预约的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_3%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/t9T
- 社区老年食堂的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_3%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/319=zru
- 街区道路维护的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_3%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/fdm=349
- 老年友好服务的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_3%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/hut=GBV
- 地方文化传播的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/488
- 社区艺术活动的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/jpg
- 开源技术交流的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/NcJ
- 公共服务评价的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/129=cwy
- 公共卫生宣传的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/rqz=547
- 基层医疗预约的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/iH7=b9o
- 基层医疗预约的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/315
- 社区垃圾分类的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/wku
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/dY1
- 乡村生态观察的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/603=ygb
- 家庭理财科普的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/ant=015
- 文化讲座服务的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/Okh=4mF
- 乡村电商实践的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/066
- 社区交通安全的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/ooq
- 数字地图应用中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/7PJ
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/656=zis
- 城市水环境观察的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/lnn=920
- 社区运动空间的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/65d=RPH
- 科学运动指导的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/196
- 创业经验分享的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/jyn
- 数字支付体验的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/Zw0
- 灵活就业交流的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/651=bwv
- 乡村阅读活动的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/per=369
- 节能生活方式的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/DRa=Xf8
- 数字课堂应用的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E9%97%AE%E5%8D%B7?/800
- 社区生活指南的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E9%97%AE%E5%8D%B7?/khq
- 老年运动活动的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E9%97%AE%E5%8D%B7?/qo4
- 城市骑行环境的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E9%97%AE%E5%8D%B7?/569=ffy

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
