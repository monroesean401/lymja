# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:31**

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

- 图书馆数字服务的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/874
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/ttn
- 健康信息获取的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/wly
- 公共空间导览的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/437=gaa
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/wit=342
- 街区小店体验的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/oS6=fXA
- 社区庭院绿化的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/324
- 本地历史资料的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/wmw
- 文化讲座服务的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/rtx
- 家庭园艺实践的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/082=vch
- 地方戏曲体验的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/huh=407
- 数字便民地图的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/zEs=6Kg
- 乡村公共文化的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/184
- 公交无障碍服务的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/jss
- 生成式工具使用的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/2Ih
- 城市休闲步道的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/873=djo
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/kuh=731
- 创业经验分享的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/sxM=mfl
- 市民热线服务的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5_%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/991
- 传统节日科普的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5_%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/ajj
- 生活服务数字化的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5_%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/9Du
- 家庭志愿活动的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5_%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/352=yaf
- 城市树木认养的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5_%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/zeo=022
- 节约用水实践的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%BD%91%E6%8A%95%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5_%E9%A1%BA%E4%B8%B0%E7%9E%AD%E6%9C%9B?/WJg=MWB
- 社区邻里服务的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%8A%95%E7%BD%91%E5%8F%AF%E9%9D%A0%E5%90%97_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/755
- 老年人日常照护的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%8A%95%E7%BD%91%E5%8F%AF%E9%9D%A0%E5%90%97_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/ajz
- 电子商务服务的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%8A%95%E7%BD%91%E5%8F%AF%E9%9D%A0%E5%90%97_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/0CR
- 电子商务服务的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%8A%95%E7%BD%91%E5%8F%AF%E9%9D%A0%E5%90%97_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/593=tqx
- 日常摄影记录的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%8A%95%E7%BD%91%E5%8F%AF%E9%9D%A0%E5%90%97_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/qhm=645
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%8A%95%E7%BD%91%E5%8F%AF%E9%9D%A0%E5%90%97_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/oRM=p57
- 急救知识普及的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E7%BE%8E%E5%A6%86?/755
- 急救知识普及的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E7%BE%8E%E5%A6%86?/ubc
- 社区养老服务的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E7%BE%8E%E5%A6%86?/huv
- 社区活动报名的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E7%BE%8E%E5%A6%86?/329=fqf
- 城市绿色交通中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E7%BE%8E%E5%A6%86?/msr=320
- 公共场馆服务的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E7%BE%8E%E5%A6%86?/bLT=DGK
- 公共设施维护中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/582
- 社区绿色空间的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/ubr
- 居家防滑改造的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/4Ze
- 城市可持续生活的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/002=xpf
- 生活技能分享的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/udi=988
- 城市公共标识的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/yIV=Jzm
- 线上阅读资源的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%97%A5%E6%94%B6%E7%9B%8A%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/969
- 家庭食品保存的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%97%A5%E6%94%B6%E7%9B%8A%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/phs
- 在线学习体验的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%97%A5%E6%94%B6%E7%9B%8A%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/7IL
- 非遗体验活动的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%97%A5%E6%94%B6%E7%9B%8A%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/903=exb
- 公园休闲体验的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%97%A5%E6%94%B6%E7%9B%8A%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/qew=514
- 家庭环保行动的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%97%A5%E6%94%B6%E7%9B%8A%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/BMm=Tbs
- 家庭健康科普的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/855
- 绿色生活实践的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/azw
- 城市共享单车的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/okO
- 终身学习资源的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/130=jvv
- 运动安全知识的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/jzm=907
- 社区消防演练的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/204=q54
- 社区垃圾回收的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/609
- 食品配送体验中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/mdw
- 安全出行教育的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/HpU
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/703=ypr
- 在线学习体验的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/dtv=387
- 公共服务预约的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/jv0=lTN
- 在线教育体验中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_36%E6%B0%AA%E5%88%9B%E6%8A%95?/528
- 城市夜间生活的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_36%E6%B0%AA%E5%88%9B%E6%8A%95?/sie
- 城市文化路线的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_36%E6%B0%AA%E5%88%9B%E6%8A%95?/R0p
- 校园安全教育的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_36%E6%B0%AA%E5%88%9B%E6%8A%95?/203=ikp
- 公共空间安全的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_36%E6%B0%AA%E5%88%9B%E6%8A%95?/ola=749
- 社区信息发布的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_36%E6%B0%AA%E5%88%9B%E6%8A%95?/APQ=fmP
- 城乡交流活动的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%BD%91%E6%8A%95app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/432
- 青少年户外教育的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%BD%91%E6%8A%95app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/rgv
- 网络信息辨识的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%BD%91%E6%8A%95app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/pzX
- 社区公共议事的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%BD%91%E6%8A%95app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/707=khs
- 物业服务沟通的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%BD%91%E6%8A%95app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/knl=700
- 老年友好服务的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%BD%91%E6%8A%95app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/mQM=j6q
- 智慧城市体验的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E7%AC%AC%E4%B8%80%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9F%BA%E9%87%91?/105
- 地方旅游导览的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E7%AC%AC%E4%B8%80%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9F%BA%E9%87%91?/onv
- 信息无障碍体验的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E7%AC%AC%E4%B8%80%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9F%BA%E9%87%91?/BKF
- 健康步道使用的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E7%AC%AC%E4%B8%80%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9F%BA%E9%87%91?/856=nhl
- 图书馆数字服务的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E7%AC%AC%E4%B8%80%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9F%BA%E9%87%91?/rrw=743
- 社区阅读服务的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E4%BF%A1%E8%AA%89%E7%AC%AC%E4%B8%80%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9F%BA%E9%87%91?/Z3W=eK7
- 城市可持续生活的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E5%AF%BC%E8%88%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%BA%BA%E7%89%A9?/633
- 农贸市场环境的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E5%AF%BC%E8%88%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%BA%BA%E7%89%A9?/lrq
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E5%AF%BC%E8%88%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%BA%BA%E7%89%A9?/FSY
- 周末休闲规划的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E5%AF%BC%E8%88%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%BA%BA%E7%89%A9?/027=xve
- 乡村文化活动的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E5%AF%BC%E8%88%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%BA%BA%E7%89%A9?/oqq=834
- 城市运动公园的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%8A%95%E5%AF%BC%E8%88%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%BA%BA%E7%89%A9?/O4S=wEN
- 社区休闲设施的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%A1%B6%E7%BA%A7%E7%BD%91%E7%AB%99%E7%BD%91%E6%8A%95_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/805
- 文化场馆预约的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%A1%B6%E7%BA%A7%E7%BD%91%E7%AB%99%E7%BD%91%E6%8A%95_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/fcc
- 便民信息查询的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%A1%B6%E7%BA%A7%E7%BD%91%E7%AB%99%E7%BD%91%E6%8A%95_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/hYt
- 社区修缮行动的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%A1%B6%E7%BA%A7%E7%BD%91%E7%AB%99%E7%BD%91%E6%8A%95_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/446=lqz
- 公共交通接驳的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%A1%B6%E7%BA%A7%E7%BD%91%E7%AB%99%E7%BD%91%E6%8A%95_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/qei=303
- 家庭教育交流的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%A1%B6%E7%BA%A7%E7%BD%91%E7%AB%99%E7%BD%91%E6%8A%95_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/lB5=iOI
- 数字政务体验的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%8A%95%E7%BD%91%E5%A4%A7%E5%85%A8_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/852
- 邻里共享空间的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%8A%95%E7%BD%91%E5%A4%A7%E5%85%A8_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/evg
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%8A%95%E7%BD%91%E5%A4%A7%E5%85%A8_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/oFE
- 数字设备回收的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%8A%95%E7%BD%91%E5%A4%A7%E5%85%A8_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/168=yza
- 邻里互助活动的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%8A%95%E7%BD%91%E5%A4%A7%E5%85%A8_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/pya=769
- 社区体育组织的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%8A%95%E7%BD%91%E5%A4%A7%E5%85%A8_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/3r2=4WF
- 农村环境治理的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8410%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/609
- 药品使用科普的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8410%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/qjj
- 无障碍信息设计的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8410%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/XHa
- 亲子科普活动的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8410%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/432=avf
- 家庭急救准备的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8410%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/vxr=569
- 城乡交流活动的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8410%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/hOW=VRn
- 公共场馆服务的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8430%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/523
- 绿色生活实践的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8430%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/zzm
- 科普展览体验的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8430%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/g5p
- 小微企业服务的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8430%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/894=tve
- 节气饮食文化的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8430%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/mwn=472
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%8430%E4%B8%AA%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/jar=kKO
- 绿色消费选择的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%BF%A1%E8%AA%89%E6%8E%92%E8%A1%8C%E6%A6%9C_%E7%BD%91%E6%98%93%E6%8A%95%E7%A8%BF?/942
- 小区公共照明的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%BF%A1%E8%AA%89%E6%8E%92%E8%A1%8C%E6%A6%9C_%E7%BD%91%E6%98%93%E6%8A%95%E7%A8%BF?/tnm
- 青少年户外教育的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%BF%A1%E8%AA%89%E6%8E%92%E8%A1%8C%E6%A6%9C_%E7%BD%91%E6%98%93%E6%8A%95%E7%A8%BF?/Huw
- 农村环境治理的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%BF%A1%E8%AA%89%E6%8E%92%E8%A1%8C%E6%A6%9C_%E7%BD%91%E6%98%93%E6%8A%95%E7%A8%BF?/575=qij
- 低碳社区实践的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%BF%A1%E8%AA%89%E6%8E%92%E8%A1%8C%E6%A6%9C_%E7%BD%91%E6%98%93%E6%8A%95%E7%A8%BF?/mcw=883
- 社区学习活动的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%BF%A1%E8%AA%89%E6%8E%92%E8%A1%8C%E6%A6%9C_%E7%BD%91%E6%98%93%E6%8A%95%E7%A8%BF?/o6d=BY4
- 节假日出行安排的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A6%82%E4%BD%95%E8%BE%A8%E5%88%AB%E7%9C%9F%E5%81%87%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/356
- 个人时间管理的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A6%82%E4%BD%95%E8%BE%A8%E5%88%AB%E7%9C%9F%E5%81%87%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/kle
- 公共服务数字化的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A6%82%E4%BD%95%E8%BE%A8%E5%88%AB%E7%9C%9F%E5%81%87%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/RC7
- 生活服务数字化的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A6%82%E4%BD%95%E8%BE%A8%E5%88%AB%E7%9C%9F%E5%81%87%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/678=sfo
- 城市生活记录的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A6%82%E4%BD%95%E8%BE%A8%E5%88%AB%E7%9C%9F%E5%81%87%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/qtw=175
- 青少年心理健康的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E5%A6%82%E4%BD%95%E8%BE%A8%E5%88%AB%E7%9C%9F%E5%81%87%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/MUd=vFF
- 物业服务沟通的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%B8%8B%E5%88%86%E8%AE%A9%E6%8F%90%E4%BE%9B%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%98%AF%E4%B8%8D%E6%98%AF%E5%B0%B1%E6%98%AF%E9%BB%91%E4%BA%86__%E4%BA%AC%E4%B8%9C%E5%91%A8%E6%8A%A5?/351
- 公共空间安全的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%B8%8B%E5%88%86%E8%AE%A9%E6%8F%90%E4%BE%9B%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%98%AF%E4%B8%8D%E6%98%AF%E5%B0%B1%E6%98%AF%E9%BB%91%E4%BA%86__%E4%BA%AC%E4%B8%9C%E5%91%A8%E6%8A%A5?/ank
- 垃圾分类指导中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%B8%8B%E5%88%86%E8%AE%A9%E6%8F%90%E4%BE%9B%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%98%AF%E4%B8%8D%E6%98%AF%E5%B0%B1%E6%98%AF%E9%BB%91%E4%BA%86__%E4%BA%AC%E4%B8%9C%E5%91%A8%E6%8A%A5?/yBL
- 社区邻里服务的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%B8%8B%E5%88%86%E8%AE%A9%E6%8F%90%E4%BE%9B%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%98%AF%E4%B8%8D%E6%98%AF%E5%B0%B1%E6%98%AF%E9%BB%91%E4%BA%86__%E4%BA%AC%E4%B8%9C%E5%91%A8%E6%8A%A5?/205=mct
- 周末休闲规划的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%B8%8B%E5%88%86%E8%AE%A9%E6%8F%90%E4%BE%9B%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%98%AF%E4%B8%8D%E6%98%AF%E5%B0%B1%E6%98%AF%E9%BB%91%E4%BA%86__%E4%BA%AC%E4%B8%9C%E5%91%A8%E6%8A%A5?/xzy=545
- 垃圾分类指导的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E4%B8%8B%E5%88%86%E8%AE%A9%E6%8F%90%E4%BE%9B%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%98%AF%E4%B8%8D%E6%98%AF%E5%B0%B1%E6%98%AF%E9%BB%91%E4%BA%86__%E4%BA%AC%E4%B8%9C%E5%91%A8%E6%8A%A5?/wcJ=QLD
- 健康步道使用的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%93%E4%B8%8D%E5%BC%80%E4%BA%86_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/857
- 智慧城市体验的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%93%E4%B8%8D%E5%BC%80%E4%BA%86_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/ojn
- 应急物资管理的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%93%E4%B8%8D%E5%BC%80%E4%BA%86_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/enO
- 家庭收纳实践的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%93%E4%B8%8D%E5%BC%80%E4%BA%86_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/414=jyf
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%93%E4%B8%8D%E5%BC%80%E4%BA%86_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/yta=005
- 基层健康档案的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%BD%91%E6%8A%95%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%93%E4%B8%8D%E5%BC%80%E4%BA%86_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/6Pw=UQz
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E6%8A%95%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/446
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E6%8A%95%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/aef
- 城市公共厕所的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E6%8A%95%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/qn2
- 家庭健康科普的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E6%8A%95%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/966=xac
- 社区宠物管理的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E6%8A%95%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/iru=467
- 地方文化传播的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E6%8A%95%E5%93%AA%E4%BA%9B%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/viO=Twi
- 全民健身活动的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/707
- 城市体育设施的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/pic
- 网络安全教育的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/2gX
- 线上办事服务的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/288=exq
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/gis=653
- 通勤路线规划的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/hln=PMq
- 公共空间休憩有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%B8%AA%E4%BA%BA%E7%90%86%E8%B4%A2%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/599
- 终身学习资源的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%B8%AA%E4%BA%BA%E7%90%86%E8%B4%A2%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/iqb
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%B8%AA%E4%BA%BA%E7%90%86%E8%B4%A2%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/pR4
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%B8%AA%E4%BA%BA%E7%90%86%E8%B4%A2%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/222=nun
- 公共服务预约的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%B8%AA%E4%BA%BA%E7%90%86%E8%B4%A2%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/ooo=935
- 社区互助网络的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%B8%AA%E4%BA%BA%E7%90%86%E8%B4%A2%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/plQ=N8o
- 数字支付体验的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%9E%8B%E6%AD%A3%E8%A7%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%B6%E5%B0%9A?/756
- 无障碍出行的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%9E%8B%E6%AD%A3%E8%A7%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%B6%E5%B0%9A?/aat
- 城乡公共服务中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%9E%8B%E6%AD%A3%E8%A7%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%B6%E5%B0%9A?/8BN
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%9E%8B%E6%AD%A3%E8%A7%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%B6%E5%B0%9A?/598=rfj
- 个人信息保护的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%9E%8B%E6%AD%A3%E8%A7%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%B6%E5%B0%9A?/xkl=828
- 智能家居应用的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%9E%8B%E6%AD%A3%E8%A7%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%B6%E5%B0%9A?/mqq=Ip1
- 物业服务沟通的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/437
- 传统节日科普的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/ugu
- 数字便民地图的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/l9r
- 个人数据管理的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/232=rxy
- 乡村公共阅读的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/mot=148
- 科学运动指导的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/2IS=jAh
- 乡村文化空间中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/003
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/ipc
- 公共图书馆服务的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/z05
- 家庭消费规划的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/658=okv
- 新能源知识普及的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/dnk=917
- 志愿者培训交流的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/FbT=JUc
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%9E%8B%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/201
- 节能生活方式的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%9E%8B%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/kps
- 社区防暑服务的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%9E%8B%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/zF8
- 数字政务体验的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%9E%8B%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/831=dlr
- 社区活动报名的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%9E%8B%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/yqi=364
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%9E%8B%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/EPh=GQi
- 街区绿化养护的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%88%A9%E5%8D%9A%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/980
- 城市文明实践的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%88%A9%E5%8D%9A%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/ngf
- 居家适老化改造的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%88%A9%E5%8D%9A%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/HA9
- 数字艺术创作的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%88%A9%E5%8D%9A%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/827=dfl
- 青少年科普实践中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%88%A9%E5%8D%9A%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/azv=540
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%88%A9%E5%8D%9A%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/xob=qoS
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%9C%9F%E4%BA%BA%E5%AE%9E%E4%BD%93%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/413
- 城乡交流活动的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%9C%9F%E4%BA%BA%E5%AE%9E%E4%BD%93%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/cnd
- 社区科普课堂的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%9C%9F%E4%BA%BA%E5%AE%9E%E4%BD%93%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/kNo
- 社区慢性病防控的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%9C%9F%E4%BA%BA%E5%AE%9E%E4%BD%93%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/380=kyu
- 基层服务创新的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%9C%9F%E4%BA%BA%E5%AE%9E%E4%BD%93%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/yzd=885
- 电子商务服务的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%9C%9F%E4%BA%BA%E5%AE%9E%E4%BD%93%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/BQs=JFf
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%85%A8%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/420
- 城市应急科普的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%85%A8%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/uwb
- 节日文化体验的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%85%A8%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/HoD
- 乡村教育资源的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%85%A8%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/191=tia
- 公交站点体验的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%85%A8%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/oqa=469
- 科学教育活动的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%85%A8%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/zBm=p4o
- 青少年职业启蒙的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%B8%8D%E9%BB%91%E9%92%B1%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E7%BB%BC%E8%89%BA?/082
- 城市社区治理的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%B8%8D%E9%BB%91%E9%92%B1%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E7%BB%BC%E8%89%BA?/ncq
- 无障碍出行的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%B8%8D%E9%BB%91%E9%92%B1%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E7%BB%BC%E8%89%BA?/iTE
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%B8%8D%E9%BB%91%E9%92%B1%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E7%BB%BC%E8%89%BA?/530=qaz
- 绿色建筑理念的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%B8%8D%E9%BB%91%E9%92%B1%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E7%BB%BC%E8%89%BA?/fyd=250
- 食品安全科普的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%B8%8D%E9%BB%91%E9%92%B1%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E7%BB%BC%E8%89%BA?/dp8=uqP
- 志愿服务平台的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%BB%99%E6%88%91%E5%87%A0%E4%B8%AA%E5%8F%AF%E9%9D%A0%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/401
- 社区邻里服务的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%BB%99%E6%88%91%E5%87%A0%E4%B8%AA%E5%8F%AF%E9%9D%A0%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/gly
- 公共场所导视的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%BB%99%E6%88%91%E5%87%A0%E4%B8%AA%E5%8F%AF%E9%9D%A0%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/uq6
- 青少年户外教育的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%BB%99%E6%88%91%E5%87%A0%E4%B8%AA%E5%8F%AF%E9%9D%A0%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/614=nbn
- 社区学习活动的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%BB%99%E6%88%91%E5%87%A0%E4%B8%AA%E5%8F%AF%E9%9D%A0%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/noy=851
- 城市雨天出行的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%BB%99%E6%88%91%E5%87%A0%E4%B8%AA%E5%8F%AF%E9%9D%A0%E7%9A%84%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/T6V=Ta9
- 科学观察活动的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E7%BA%BF%E4%B8%8A%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/321
- 低碳社区实践的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E7%BA%BF%E4%B8%8A%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/oqy
- 周末休闲规划的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E7%BA%BF%E4%B8%8A%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/fNv
- 城市慢行系统的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E7%BA%BF%E4%B8%8A%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/347=yzz
- 数字课堂应用的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E7%BA%BF%E4%B8%8A%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/adw=914
- 社区儿童活动的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E7%BA%BF%E4%B8%8A%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/zTT=YNy
- 城市步行环境的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9B%B6%E6%8A%95%E8%B5%84%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/915
- 家庭养老规划的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9B%B6%E6%8A%95%E8%B5%84%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/iju
- 农产品品牌传播的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9B%B6%E6%8A%95%E8%B5%84%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/4cT
- 居家适老化改造的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9B%B6%E6%8A%95%E8%B5%84%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/259=qxq
- 社区托育服务的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9B%B6%E6%8A%95%E8%B5%84%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/orj=303
- 灵活就业交流中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9B%B6%E6%8A%95%E8%B5%84%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/L5s=pqZ
- 儿童运动体验的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/870
- 科学观察活动的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/fmd
- 城市公共标识的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/cuP
- 数字便民地图的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/541=hrt
- 地方文化传播的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/mte=296
- 公共卫生宣传的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/tOe=dmz
- 城市公共饮水的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E5%90%8D_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/633
- 节能家电使用的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E5%90%8D_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/cbd
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E5%90%8D_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/JEJ
- 家庭节能实践的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E5%90%8D_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/065=nga
- 街头绿植养护的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E5%90%8D_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/wyz=656
- 老年数字阅读的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E5%90%8D_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/Zij=1si
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E9%82%80%E8%AF%B7%E7%A0%81_360%E6%AF%8D%E5%A9%B4?/663
- 居家防滑改造的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E9%82%80%E8%AF%B7%E7%A0%81_360%E6%AF%8D%E5%A9%B4?/hlr
- 社区垃圾回收的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E9%82%80%E8%AF%B7%E7%A0%81_360%E6%AF%8D%E5%A9%B4?/aSk
- 创业经验分享中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E9%82%80%E8%AF%B7%E7%A0%81_360%E6%AF%8D%E5%A9%B4?/009=unb
- 家庭养老规划的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E9%82%80%E8%AF%B7%E7%A0%81_360%E6%AF%8D%E5%A9%B4?/dan=765
- 城市公共标识的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E9%82%80%E8%AF%B7%E7%A0%81_360%E6%AF%8D%E5%A9%B4?/5SS=at4
- 街道综合服务的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/485
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/ydh
- 科学教育活动的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/VOn
- 社会体育指导的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/110=fzy
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/mdi=392
- 城市应急广播中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/rF9=sfb
- 物业服务沟通的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%81%B5%E7%8C%AB%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_36%E6%B0%AA%E6%8A%95%E8%B5%84?/948
- 公共图书馆服务的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%81%B5%E7%8C%AB%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_36%E6%B0%AA%E6%8A%95%E8%B5%84?/aiz
- 全民阅读推广中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%81%B5%E7%8C%AB%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_36%E6%B0%AA%E6%8A%95%E8%B5%84?/4t4
- 非遗课堂体验的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%81%B5%E7%8C%AB%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_36%E6%B0%AA%E6%8A%95%E8%B5%84?/517=ced
- 生活技能分享的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%81%B5%E7%8C%AB%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_36%E6%B0%AA%E6%8A%95%E8%B5%84?/lzu=496
- 青年职业探索的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%81%B5%E7%8C%AB%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_36%E6%B0%AA%E6%8A%95%E8%B5%84?/hOY=8L3
- 节能生活方式的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0APP_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/605
- 便民服务窗口的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0APP_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/qdy
- 邻里互助活动的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0APP_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/uiS
- 公共场所导视的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0APP_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/399=vwy

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
