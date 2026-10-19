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

- 乡村公共阅读的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/318
- 地方文化传播的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/lin
- 科学运动指导的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/EyP
- 志愿者培训交流的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/078=qsl
- 儿童友好空间的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/cal=570
- 绿色消费选择的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/HQd=Fwm
- 城市噪声观察的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/507
- 个人数据管理的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/dzf
- 校园节能行动的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/C5H
- 公共服务指南的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/808=ptt
- 生活垃圾减量的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/mcz=849
- 远程协作工具的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/1Zq=7se
- 户外活动组织的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/879
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/tuh
- 社区休闲设施的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/rcr
- 社区庭院绿化的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/636=vth
- 城市生活服务的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/crm=824
- 农产品消费体验的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/lcQ=zGd
- 社区安全巡查的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E9%AB%98%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/075
- 城市生活服务的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E9%AB%98%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/juo
- 公共场所导视的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E9%AB%98%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/7mF
- 智慧城市体验的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E9%AB%98%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/506=btq
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E9%AB%98%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/jly=159
- 城市文明出行的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E9%AB%98%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/PHk=ecj
- 社区学习活动的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/820
- 城市应急广播的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/gzy
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/6Dz
- 家庭健康管理的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/567=xgg
- 家庭收纳实践的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/chf=535
- 节日文化体验的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/8s8=Xnb
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0%E6%AF%8D%E5%A9%B4?/129
- 骑行路线规划的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0%E6%AF%8D%E5%A9%B4?/yvp
- 公共服务评价的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0%E6%AF%8D%E5%A9%B4?/F8l
- 社区花园共建的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0%E6%AF%8D%E5%A9%B4?/230=iol
- 地方文化传播的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0%E6%AF%8D%E5%A9%B4?/vnw=640
- 街区绿化养护的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0%E6%AF%8D%E5%A9%B4?/Lz7=ghv
- 家庭养老规划的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_168%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/501
- 基层健康服务的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_168%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/bsx
- 城市公共艺术的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_168%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/jyB
- 公共空间休憩的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_168%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/498=qhl
- 个人时间管理的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_168%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/vzo=804
- 社区宠物管理的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_168%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E5%AF%B9%E7%85%A7%E8%A1%A8_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/uPZ=K86
- 青年志愿活动的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%AE%97%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/243
- 街头绿植养护的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%AE%97%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/dps
- 开放数据应用的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%AE%97%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/boJ
- 电动汽车充电的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%AE%97%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/456=dof
- 公共服务评价的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%AE%97%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/nrv=457
- 家庭环保行动的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%AE%97%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/7Kp=Pbj
- 社区便民服务的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A6%82%E4%BD%95%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E5%97%85?/786
- 社区便利生活的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A6%82%E4%BD%95%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E5%97%85?/dtl
- 地方戏曲体验的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A6%82%E4%BD%95%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E5%97%85?/fB1
- 社区公共卫生的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A6%82%E4%BD%95%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E5%97%85?/425=xtz
- 青少年户外教育的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A6%82%E4%BD%95%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E5%97%85?/cml=403
- 数字课堂应用的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A6%82%E4%BD%95%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E5%97%85?/NSc=Op6
- 老年学习活动的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E5%81%9A_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/849
- 文化讲座服务的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E5%81%9A_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/zwk
- 社区便民集市的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E5%81%9A_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/oWD
- 智能手机助老的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E5%81%9A_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/996=puh
- 户外活动组织的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E5%81%9A_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/pff=378
- 社区托育服务的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E5%81%9A_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/Ene=9Rv
- 社区法律科普的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/809
- 全民阅读推广的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/mmd
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/kRj
- 乡村文化空间的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/748=zrp
- 城市共享单车的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/utv=521
- 社区信息发布的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/hbS=ily
- 社区共享书架的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%85%A8%E5%A4%A9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%9224%E5%B0%8F%E6%97%B6%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/727
- 社区庭院绿化的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%85%A8%E5%A4%A9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%9224%E5%B0%8F%E6%97%B6%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/ikz
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%85%A8%E5%A4%A9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%9224%E5%B0%8F%E6%97%B6%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/bBD
- 城市便民驿站的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%85%A8%E5%A4%A9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%9224%E5%B0%8F%E6%97%B6%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/746=zko
- 无障碍出行的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%85%A8%E5%A4%A9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%9224%E5%B0%8F%E6%97%B6%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/iuo=336
- 日常摄影记录的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%85%A8%E5%A4%A9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%9224%E5%B0%8F%E6%97%B6%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/4oX=40y
- 小微企业服务的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%A4%AA%E5%A4%9A%E4%BA%86_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/771
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%A4%AA%E5%A4%9A%E4%BA%86_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/oqt
- 老年友好服务的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%A4%AA%E5%A4%9A%E4%BA%86_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/VEW
- 城市社区治理的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%A4%AA%E5%A4%9A%E4%BA%86_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/833=ncu
- 城市休闲步道的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%A4%AA%E5%A4%9A%E4%BA%86_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/btq=423
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%A4%AA%E5%A4%9A%E4%BA%86_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/NVW=k94
- 医院导诊服务的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/625
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/osj
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/0XU
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/936=wtp
- 老年友好服务的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/crx=688
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/rag=SLw
- 绿色生活实践的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/626
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/uur
- 节约用水实践的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/Qe0
- 创业经验分享的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/225=skk
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/zjs=407
- 租房信息服务的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/YcR=lfg
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/559
- 街道综合服务的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/bvg
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/ZPL
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/398=rre
- 无障碍出行的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/tvx=434
- 市民热线服务的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/1MP=RM8
- 城市公共厕所的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/638
- 社区科普课堂的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/lyp
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/Z3v
- 老年友好服务的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/148=ccj
- 公共卫生宣传的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/dgy=109
- 数字便民地图的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/ejk=X2g
- 小区停车协商的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/372
- 乡村电商实践的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/gyd
- 数字支付体验的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/4e0
- 图书馆活动策划的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/870=qti
- 家庭节能实践的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/uyc=097
- 开放数据应用的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/Lt4=Jtu
- 医院导诊服务的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E6%B1%BD%E8%BD%A6?/146
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E6%B1%BD%E8%BD%A6?/woj
- 居家适老化改造中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E6%B1%BD%E8%BD%A6?/81l
- 音乐欣赏活动的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E6%B1%BD%E8%BD%A6?/658=lvc
- 城市空气科普的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E6%B1%BD%E8%BD%A6?/joj=535
- 休闲运动入门的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E6%B1%BD%E8%BD%A6?/syq=g6p
- 社区公共餐饮的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/029
- 青少年户外教育的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/xoj
- 公共场馆服务的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/vdP
- 城市博物馆服务的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/336=xqp
- 街头绿植养护的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/jml=623
- 便民信息查询的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/dCT=AMS
- 新能源知识普及的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/896
- 绿色校园实践的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/dff
- 社区共享书架的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/bFE
- 居家适老化改造的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/288=jqq
- 校园节能行动的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/vku=511
- 物业服务沟通的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/y6i=1eX
- 社区手工活动的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AE%9E%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/594
- 公共健身器材的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AE%9E%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/cpe
- 家庭用电安全的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AE%9E%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/Lm3
- 乡村产业科普的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AE%9E%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/624=hzz
- 社区体育组织的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AE%9E%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/jwv=166
- 数字创作工具的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AE%9E%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/ABV=za5
- 线上阅读资源的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%9C%9F%E6%AD%A3%E7%8E%A9%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E7%9A%84%E6%96%B9%E6%B3%95_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/862
- 社区宠物管理的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%9C%9F%E6%AD%A3%E7%8E%A9%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E7%9A%84%E6%96%B9%E6%B3%95_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/joj
- 物业服务沟通的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%9C%9F%E6%AD%A3%E7%8E%A9%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E7%9A%84%E6%96%B9%E6%B3%95_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/Wi6
- 社区快递服务的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%9C%9F%E6%AD%A3%E7%8E%A9%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E7%9A%84%E6%96%B9%E6%B3%95_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/120=djh
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%9C%9F%E6%AD%A3%E7%8E%A9%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E7%9A%84%E6%96%B9%E6%B3%95_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/bwq=384
- 家庭节能设备的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%9C%9F%E6%AD%A3%E7%8E%A9%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E7%9A%84%E6%96%B9%E6%B3%95_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/jKg=dgQ
- 环境教育课程的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%8E%A8%E5%B9%BF%E8%AF%9D%E6%9C%AF_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/289
- 城市人文观察的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%8E%A8%E5%B9%BF%E8%AF%9D%E6%9C%AF_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/mib
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%8E%A8%E5%B9%BF%E8%AF%9D%E6%9C%AF_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/kpq
- 市民热线服务的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%8E%A8%E5%B9%BF%E8%AF%9D%E6%9C%AF_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/220=niy
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%8E%A8%E5%B9%BF%E8%AF%9D%E6%9C%AF_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/jvc=952
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%8E%A8%E5%B9%BF%E8%AF%9D%E6%9C%AF_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/t0c=6rK
- 城市步行环境的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/380
- 在线学习体验的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/ctz
- 家庭用电安全的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/ns7
- 跨代沟通活动的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/146=awd
- 青少年心理健康的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/pfc=448
- 小微企业服务的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/at3=rm9
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E9%95%BF%E6%9C%9F%E5%B8%A6%E8%B5%9A_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/840
- 城市噪声观察的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E9%95%BF%E6%9C%9F%E5%B8%A6%E8%B5%9A_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/qtu
- 公园休闲体验的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E9%95%BF%E6%9C%9F%E5%B8%A6%E8%B5%9A_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/D30
- 乡村公共服务的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E9%95%BF%E6%9C%9F%E5%B8%A6%E8%B5%9A_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/389=xjl
- 城市生活记录的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E9%95%BF%E6%9C%9F%E5%B8%A6%E8%B5%9A_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/fxw=527
- 儿童友好街区的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E9%95%BF%E6%9C%9F%E5%B8%A6%E8%B5%9A_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/2pQ=fes
- 公共设施维护中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/361
- 城乡公共服务的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/kzw
- 城市应急广播的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/RVQ
- 社区文化节活动的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/479=svp
- 家庭节能设备的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/knz=811
- 跨代沟通活动的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/Yyi=7x0
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/877
- 城市公共空间的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/odo
- 全民健身活动有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/jZN
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/821=cbb
- 老年人日常照护的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/gqg=647
- 街区小店体验的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/PPr=cNN
- 就业技能培训的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%9C%80%E4%BD%B3%E6%8A%95%E6%B3%A8%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/714
- 公共服务预约的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%9C%80%E4%BD%B3%E6%8A%95%E6%B3%A8%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/kyg
- 邻里共享空间的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%9C%80%E4%BD%B3%E6%8A%95%E6%B3%A8%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/jQI
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%9C%80%E4%BD%B3%E6%8A%95%E6%B3%A8%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/051=vyx
- 社区协商议事的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%9C%80%E4%BD%B3%E6%8A%95%E6%B3%A8%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/niu=557
- 社区法律科普的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%9C%80%E4%BD%B3%E6%8A%95%E6%B3%A8%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/iqV=gVc
- 志愿服务平台的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94a%EF%BC%8Fp%EF%BC%8Fp_%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/198
- 数字便民地图的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94a%EF%BC%8Fp%EF%BC%8Fp_%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/drw
- 农村环境治理的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94a%EF%BC%8Fp%EF%BC%8Fp_%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/kIs
- 家庭健康科普的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94a%EF%BC%8Fp%EF%BC%8Fp_%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/152=evc
- 市民意见收集的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94a%EF%BC%8Fp%EF%BC%8Fp_%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/vyy=032
- 科学运动指导的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94a%EF%BC%8Fp%EF%BC%8Fp_%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/DDo=IT4
- 数字创作工具的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/931
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/lmy
- 社区活动空间的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/AXh
- 亲子阅读活动的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/658=bnd
- 校园阅读活动的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/lws=240
- 文化讲座服务的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/y0k=cHD
- 家庭收纳实践的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%89%93%E6%B3%95_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/356
- 读书会组织的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%89%93%E6%B3%95_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/uhg
- 农贸市场环境中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%89%93%E6%B3%95_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/FEj
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%89%93%E6%B3%95_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/531=wea
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%89%93%E6%B3%95_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/wld=463
- 城市体育设施的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%89%93%E6%B3%95_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/rWi=62W
- 数字档案服务的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1QQ%E7%BE%A4_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/639
- 城市步行环境的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1QQ%E7%BE%A4_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/ajf
- 人工智能科普的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1QQ%E7%BE%A4_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/QA4
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1QQ%E7%BE%A4_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/367=taq
- 家庭阅读计划的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1QQ%E7%BE%A4_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/tpi=440
- 本地消费场景的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1QQ%E7%BE%A4_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/nYr=GqR
- 数据分析入门的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/198
- 学校体育活动的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/rrq
- 社区儿童活动的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/hKl
- 城市运动公园的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/020=hox
- 志愿服务平台的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/zbu=631
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/99s=0nG
- 无障碍出行的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/594
- 公共交通接驳的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/sry
- 乡村休闲旅游从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/UvE
- 城市休闲步道中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/427=pim
- 公共设施使用的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/nit=884
- 社区商业活力的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/fuF=9z1
- 远程协作工具的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/736
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/yum
- 社区垃圾回收的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/ohC
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/131=bet
- 绿色消费选择的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/kru=235
- 家庭急救准备的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/kgG=LXo
- 人工智能科普的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%B9%B0%E5%B0%8F%E5%A4%A7%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/457
- 社区读书角建设的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%B9%B0%E5%B0%8F%E5%A4%A7%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/uss
- 小区公共照明的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%B9%B0%E5%B0%8F%E5%A4%A7%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/7gW
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%B9%B0%E5%B0%8F%E5%A4%A7%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/752=ycp
- 公共场所导视的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%B9%B0%E5%B0%8F%E5%A4%A7%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/aml=364
- 农产品品牌传播的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%B9%B0%E5%B0%8F%E5%A4%A7%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/JNh=pdB
- 生成式工具使用的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/800
- 校园安全教育的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/igm
- 居家防滑改造的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/4Xv
- 城市绿色交通中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/305=jqg
- 小区电梯维护的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/lxc=347
- 生活垃圾回收的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/Fn5=zkx
- 城市噪声观察的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/886
- 志愿服务平台的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/thn
- 城市宠物友好空间的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/Vk1
- 社区安全巡查的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/397=hgt
- 地方文化传播的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/ven=551
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/Bcc=SPu
- 家庭安全提示的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/907
- 社区故事采集的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/wea
- 社区宣传栏更新的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/pmD
- 城市文明出行的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/386=tbn
- 公园休闲体验的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/nkx=241
- 地方旅游导览的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/Lnq=OGa
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E8%A7%82%E5%AF%9F?/991
- 数字生活课堂的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E8%A7%82%E5%AF%9F?/ksn
- 社区健康讲座的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E8%A7%82%E5%AF%9F?/zGe
- 小区停车协商的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E8%A7%82%E5%AF%9F?/939=xax
- 数字设备回收的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E8%A7%82%E5%AF%9F?/axn=477
- 社区活动策划的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E8%A7%82%E5%AF%9F?/COw=ylT
- 非遗体验活动的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/642
- 社区活动报名的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/ttv
- 读书会组织的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/CGu
- 数字艺术创作的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/903=byo

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
