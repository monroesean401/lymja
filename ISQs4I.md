# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 地方民俗记录的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/D4c
- 图书馆活动策划的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/307=nfo
- 本地旅行体验的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/bwr=755
- 健康饮水科普的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/IX1=e21
- 社区宠物管理的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87app_%E9%9B%85%E8%99%8E%E5%8E%BF%E5%9F%9F?/015
- 数据分析入门的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87app_%E9%9B%85%E8%99%8E%E5%8E%BF%E5%9F%9F?/oim
- 乡村文化活动的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87app_%E9%9B%85%E8%99%8E%E5%8E%BF%E5%9F%9F?/SC0
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87app_%E9%9B%85%E8%99%8E%E5%8E%BF%E5%9F%9F?/847=qpg
- 非遗课堂体验的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87app_%E9%9B%85%E8%99%8E%E5%8E%BF%E5%9F%9F?/hnw=325
- 社区共享书架的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87app_%E9%9B%85%E8%99%8E%E5%8E%BF%E5%9F%9F?/O2M=H4E
- 市民意见收集的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AF%8F%E5%A4%A9%E8%B5%A2%E4%B8%80%E5%8D%83%E5%A4%9A_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/961
- 校园节能行动的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AF%8F%E5%A4%A9%E8%B5%A2%E4%B8%80%E5%8D%83%E5%A4%9A_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/ypn
- 城市博物馆活动的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AF%8F%E5%A4%A9%E8%B5%A2%E4%B8%80%E5%8D%83%E5%A4%9A_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/zLg
- 乡村文化活动的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AF%8F%E5%A4%A9%E8%B5%A2%E4%B8%80%E5%8D%83%E5%A4%9A_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/895=dio
- 绿色出行服务的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AF%8F%E5%A4%A9%E8%B5%A2%E4%B8%80%E5%8D%83%E5%A4%9A_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/lpq=085
- 公共场所导视的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AF%8F%E5%A4%A9%E8%B5%A2%E4%B8%80%E5%8D%83%E5%A4%9A_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/niV=pYv
- 家庭照护支持的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/571
- 开放数据应用的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/cys
- 社区协商议事的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/VcC
- 居家防滑改造的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/249=wbi
- 便民维修服务的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/aod=609
- 家庭健康管理的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/x1M=wah
- 家庭急救准备的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B%E5%9B%BE_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/255
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B%E5%9B%BE_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/nci
- 在线教育体验的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B%E5%9B%BE_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/ldh
- 科技馆参观体验的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B%E5%9B%BE_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/946=sna
- 亲子阅读活动的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B%E5%9B%BE_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/isu=242
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B%E5%9B%BE_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/FS3=wxn
- 家庭消费规划的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/046
- 社区安全巡查的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/fav
- 城市文明出行的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/34b
- 城市水环境观察的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/918=lhn
- 绿色建筑理念的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/dyq=147
- 本地消费场景的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/kJy=ivV
- 社区设施共享的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A67%E7%A0%81%E7%BF%BB%E5%80%8D%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/777
- 公共空间照明的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A67%E7%A0%81%E7%BF%BB%E5%80%8D%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/jgs
- 数字公共文化有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A67%E7%A0%81%E7%BF%BB%E5%80%8D%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/B2S
- 个人信息保护的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A67%E7%A0%81%E7%BF%BB%E5%80%8D%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/913=dug
- 城市社区治理的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A67%E7%A0%81%E7%BF%BB%E5%80%8D%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/dnd=225
- 节日文化体验的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A67%E7%A0%81%E7%BF%BB%E5%80%8D%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/sTf=EaB
- 家庭安全提示的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/243
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/ebh
- 社区文化节活动的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/u8k
- 邻里共享空间的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/188=inw
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/gms=139
- 城市可持续生活的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/6vF=874
- 城市展览体验中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/996
- 社区菜市场服务的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/nsv
- 数字设备回收的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/S1S
- 机器人科普活动的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/904=ayn
- 社区文化传播从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/mlx=707
- 乡村生态观察的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/FPv=4Q2
- 开放数据应用的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E8%B5%B0%E5%8A%BF_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/947
- 城市运动公园的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E8%B5%B0%E5%8A%BF_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/bkp
- 机器学习入门的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E8%B5%B0%E5%8A%BF_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/4Gg
- 城市建设科普的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E8%B5%B0%E5%8A%BF_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/246=xkf
- 老年运动活动的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E8%B5%B0%E5%8A%BF_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/wcl=813
- 生活技能分享的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E8%B5%B0%E5%8A%BF_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/mOO=f77
- 食品配送体验的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/402
- 公园无障碍服务的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/fkp
- 城市空气科普的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/gBC
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/572=suz
- 街区小店体验的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/lha=711
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/KvN=8AA
- 数字公共文化的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%A7%84%E5%88%92%E6%8A%95%E6%B3%A8_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/713
- 社区阅读服务的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%A7%84%E5%88%92%E6%8A%95%E6%B3%A8_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/blv
- 智慧城市体验的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%A7%84%E5%88%92%E6%8A%95%E6%B3%A8_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/gHH
- 人工智能科普的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%A7%84%E5%88%92%E6%8A%95%E6%B3%A8_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/374=wcr
- 本地历史资料的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%A7%84%E5%88%92%E6%8A%95%E6%B3%A8_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/vdq=467
- 城市文化路线的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%A7%84%E5%88%92%E6%8A%95%E6%B3%A8_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/wNs=VKK
- 网络安全教育的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/621
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/gkl
- 新能源知识普及的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/g8o
- 城市步行友好的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/960=qvm
- 城市文化路线的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/idw=583
- 城市公共艺术的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/f2t=9mL
- 社区阅读服务的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E5%AE%98%E6%96%B9%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%AE%8F%E8%A7%82?/401
- 公共空间安全的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E5%AE%98%E6%96%B9%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%AE%8F%E8%A7%82?/eyw
- 图书借阅体验的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E5%AE%98%E6%96%B9%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%AE%8F%E8%A7%82?/JOd
- 社区交通安全的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E5%AE%98%E6%96%B9%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%AE%8F%E8%A7%82?/683=enh
- 社会体育指导的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E5%AE%98%E6%96%B9%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%AE%8F%E8%A7%82?/tql=610
- 社区庭院绿化的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E5%AE%98%E6%96%B9%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%AE%8F%E8%A7%82?/kH1=jGd
- 公共场馆服务的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/450
- 绿色生活实践的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/jde
- 便民服务窗口的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/Pld
- 公共服务评价的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/551=oyi
- 农贸市场环境中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/esc=605
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/k4g=MdU
- 城市骑行环境的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81_%E8%99%8E%E6%89%91%E6%97%B6%E6%8A%A5?/280
- 老年数字阅读的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81_%E8%99%8E%E6%89%91%E6%97%B6%E6%8A%A5?/ldo
- 无障碍信息设计的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81_%E8%99%8E%E6%89%91%E6%97%B6%E6%8A%A5?/U0N
- 社区环保活动的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81_%E8%99%8E%E6%89%91%E6%97%B6%E6%8A%A5?/150=oae
- 社区交通安全的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81_%E8%99%8E%E6%89%91%E6%97%B6%E6%8A%A5?/xsd=507
- 居家防滑改造的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81_%E8%99%8E%E6%89%91%E6%97%B6%E6%8A%A5?/CA5=1YT
- 开放数据应用的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E4%BC%97%E6%B5%8B?/155
- 社区邻里服务中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E4%BC%97%E6%B5%8B?/fbq
- 网络安全教育的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E4%BC%97%E6%B5%8B?/kwt
- 数字创意课程的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E4%BC%97%E6%B5%8B?/397=asv
- 科学观察活动的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E4%BC%97%E6%B5%8B?/jcv=563
- 城市适老服务的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E4%BC%97%E6%B5%8B?/zmb=Hcq
- 基层健康档案的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/303
- 在线学习体验的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/wwr
- 基层健康档案的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/4lS
- 课后服务体验的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/410=lbe
- 街区小店体验中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/eqg=799
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/nFH=7M3
- 城市人文观察的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/396
- 本地历史资料的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/cew
- 全民健身活动的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/A4A
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/708=lwd
- 家庭健康管理的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/fdw=375
- 社区互助网络的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/Y6r=4Jk
- 城市绿道建设的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_5%E5%88%86%E8%B5%9B%E8%BD%A6_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/341
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_5%E5%88%86%E8%B5%9B%E8%BD%A6_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/oxs
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_5%E5%88%86%E8%B5%9B%E8%BD%A6_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/mqy
- 社区垃圾分类的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_5%E5%88%86%E8%B5%9B%E8%BD%A6_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/228=qxw
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_5%E5%88%86%E8%B5%9B%E8%BD%A6_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/niz=465
- 社区应急准备的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_5%E5%88%86%E8%B5%9B%E8%BD%A6_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/681=Tzo
- 城市体育设施的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/328
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/uac
- 社区消防演练的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/uaW
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/560=jdi
- 绿色快递包装的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/ykp=784
- 校园节能行动的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/9Gb=O8E
- 城市住房服务的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/279
- 城市噪声观察的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/ljk
- 乡村公共阅读的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/XGE
- 创业经验分享的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/659=abl
- 公共场馆服务的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/oxh=408
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/R1s=XeA
- 街头绿植养护的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/886
- 城市步行环境的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/pny
- 乡村生态观察的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/5uN
- 城乡交通衔接的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/482=xux
- 农业科普体验的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/pip=204
- 数字公共文化的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/T7i=7cS
- 终身学习资源的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%93%AA%E9%87%8C%E7%9C%8B_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/492
- 旧物循环利用的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%93%AA%E9%87%8C%E7%9C%8B_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/wka
- 社区宠物管理的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%93%AA%E9%87%8C%E7%9C%8B_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/9DC
- 老旧小区改造的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%93%AA%E9%87%8C%E7%9C%8B_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/930=iaz
- 公共服务预约的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%93%AA%E9%87%8C%E7%9C%8B_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/scu=771
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%93%AA%E9%87%8C%E7%9C%8B_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/hHW=VBJ
- 乡村公共阅读的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E9%AA%97%E7%9A%84%E5%90%97_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/344
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E9%AA%97%E7%9A%84%E5%90%97_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/wbl
- 家庭理财科普的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E9%AA%97%E7%9A%84%E5%90%97_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/d0j
- 图书馆活动策划的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E9%AA%97%E7%9A%84%E5%90%97_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/017=hob
- 家庭用电安全的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E9%AA%97%E7%9A%84%E5%90%97_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/rea=501
- 电子商务服务的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E9%AA%97%E7%9A%84%E5%90%97_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/850=iIJ
- 音乐欣赏活动的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/232
- 智慧城市体验的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/ike
- 城市可持续生活的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/YmA
- 绿色消费选择的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/597=nuj
- 绿色办公实践的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/vxg=570
- 城市游园体验的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/wZv=tcC
- 新能源知识普及的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/166
- 物业服务沟通的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/tpm
- 社区花园共建中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/Klu
- 社区修缮行动中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/394=vdn
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/rha=397
- 城市微更新实践中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/jJ8=nKk
- 地方美食文化的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%88%99_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/364
- 儿童安全出行的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%88%99_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/zws
- 基层健康服务中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%88%99_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/Rfx
- 城市公共饮水的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%88%99_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/402=nkj
- 数字资源检索的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%88%99_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/ykm=833
- 口袋公园建设的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%88%99_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/CAp=bwW
- 全民健身活动的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/388
- 创业经验分享的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/syh
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/JpO
- 数字生活课堂中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/665=qwg
- 乡村公共服务的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/fwo=487
- 家庭消费规划的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/Rw9=jES
- 儿童户外活动的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/414
- 网络信息辨识的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/lge
- 社区慢性病防控的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/u5s
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/164=wqh
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/mvu=924
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/Tt8=dQn
- 地方旅游导览的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/779
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/zsl
- 科技馆参观体验的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/Qaw
- 青少年户外教育的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/818=qps
- 药品使用科普的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/ozv=933
- 街区小店体验的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/aHS=edq
- 城市社区治理的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/432
- 数字阅读服务的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/opg
- 街区小店体验的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/FsQ
- 社区文化传播的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/447=fpj
- 城市应急科普的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/dlp=966
- 社区文化传播的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/CG6=bbh
- 无障碍信息设计的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6qq%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/460
- 社区运动空间的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6qq%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/ugg
- 家庭网络使用的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6qq%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/KUe
- 社区文化传播的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6qq%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/320=ioa
- 社区法律科普的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6qq%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/qwu=134
- 在线学习体验的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6qq%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/N17=aEU
- 社区安全巡查的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/711
- 社区活动策划的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/ofb
- 小区公共照明的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/i6d
- 家庭志愿活动的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/414=nwv
- 城市建设科普的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/lfd=496
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/TPy=Z7C
- 社区休闲设施的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/435
- 数字便民地图的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/mij
- 软件开发学习的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/vKX
- 老年人文化生活的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/743=fok
- 校园社团活动的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/wuc=089
- 社区运动空间的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/aPE=Ac5
- 家庭网络使用的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%9C%AD%E8%AE%B0?/877
- 居家适老化改造的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%9C%AD%E8%AE%B0?/djq
- 儿童运动体验的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%9C%AD%E8%AE%B0?/g7l
- 科学健身方法的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%9C%AD%E8%AE%B0?/380=mfc
- 绿色消费选择的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%9C%AD%E8%AE%B0?/bin=280
- 乡村生态旅游的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%9C%AD%E8%AE%B0?/DEP=pXM
- 社区便民集市的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%90%97__%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE?/126
- 绿色快递包装的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%90%97__%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE?/oxj
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%90%97__%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE?/MZP
- 数字档案服务的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%90%97__%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE?/194=dsm
- 智能手机助老的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%90%97__%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE?/vqp=947
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%90%97__%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE?/fcL=Onu
- 终身学习资源的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/093
- 公共服务咨询的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/vji
- 街道综合服务的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/z8M
- 社区公共餐饮的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/235=mrj
- 地方旅游导览的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/keo=850
- 数字便民地图中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/i77=guU
- 公共场所导视的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/843
- 生活技能分享的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/djz
- 生成式工具使用的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/KTv
- 公共空间照明的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/511=iye
- 社区便民服务的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/zns=936
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/fqc=FBR
- 城市农夫市集的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E5%86%9B%E4%BA%8B?/296
- 公共服务咨询的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E5%86%9B%E4%BA%8B?/iou
- 绿色快递包装的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E5%86%9B%E4%BA%8B?/t1R
- 智慧城市体验的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E5%86%9B%E4%BA%8B?/841=pmn
- 社区养老服务的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E5%86%9B%E4%BA%8B?/qny=640
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%BA%94%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E5%86%9B%E4%BA%8B?/IiH=0ZI
- 儿童运动体验的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86pk10_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/059
- 文化讲座服务的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86pk10_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/ppe
- 节假日出行安排的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86pk10_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/MJh
- 个人数据管理的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86pk10_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/482=jpu
- 儿童运动体验的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86pk10_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/lzy=794
- 城市人文观察中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86pk10_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/jf6=Vdt
- 个人信息保护的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%A4%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/680
- 生活垃圾减量的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%A4%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/ito
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%A4%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/PHB
- 数字素养提升的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%A4%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/539=rcc
- 公共场馆服务的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%A4%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/hzt=060
- 物业服务沟通的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%A4%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/Adl=kFV

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
