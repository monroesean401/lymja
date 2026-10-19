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

- 家庭环保行动的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%911688_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/uKV
- 老年人日常照护的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%911688_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/846=ajw
- 个人数据管理的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%911688_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/lha=744
- 亲子科普活动的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%911688_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/jD2=NBd
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/142
- 社区心理支持的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/waf
- 智慧城市体验的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/qDm
- 城市绿色交通的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/674=nqi
- 应急物资管理的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/wed=735
- 通勤路线规划的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9app%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/Jjd=jLA
- 便民信息查询的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9app%E6%89%8B%E8%AE%A1%E5%88%92%E7%89%88_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/235
- 传统节日科普的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9app%E6%89%8B%E8%AE%A1%E5%88%92%E7%89%88_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/hkm
- 公共空间导览的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9app%E6%89%8B%E8%AE%A1%E5%88%92%E7%89%88_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/t9s
- 城市绿道建设的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9app%E6%89%8B%E8%AE%A1%E5%88%92%E7%89%88_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/565=lww
- 城市可持续生活的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9app%E6%89%8B%E8%AE%A1%E5%88%92%E7%89%88_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/jsq=193
- 科学健身方法的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9app%E6%89%8B%E8%AE%A1%E5%88%92%E7%89%88_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/l7N=JzN
- 线上办事服务的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/155
- 便民维修服务的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/bxj
- 生活垃圾回收的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/LSt
- 绿色消费选择的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/585=wpx
- 社区科普课堂的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/thf=558
- 社区停车服务的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/aIl=eeO
- 本地消费场景的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%80%89%E5%8F%B7_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/557
- 传统节日科普的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%80%89%E5%8F%B7_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/mob
- 社区休闲设施的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%80%89%E5%8F%B7_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/E1W
- 城乡公共服务的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%80%89%E5%8F%B7_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/836=wkr
- 公共卫生设施的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%80%89%E5%8F%B7_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/ixa=400
- 家庭健康科普的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%80%89%E5%8F%B7_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/OQz=Eq2
- 无障碍信息设计的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BE%A4_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/304
- 城市适老服务的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BE%A4_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/czh
- 开放数据应用的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BE%A4_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/0Lj
- 图书馆数字服务的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BE%A4_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/311=bni
- 社区法律科普的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BE%A4_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/ugw=075
- 社区便民集市的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BE%A4_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/Lwg=erE
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%92%8C%E5%80%BC_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/292
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%92%8C%E5%80%BC_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/jzh
- 居家防滑改造中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%92%8C%E5%80%BC_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/fRM
- 家庭园艺实践的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%92%8C%E5%80%BC_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/294=oiw
- 乡村公共阅读的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%92%8C%E5%80%BC_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/unb=181
- 公益活动组织的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%92%8C%E5%80%BC_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/zyN=Iae
- 通勤路线规划的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/310
- 社区庭院绿化的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/sbh
- 城市展览体验的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/PRk
- 网络信息辨识的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/701=vuz
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/qrz=347
- 绿色消费选择的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/im3=tbl
- 青少年科普实践的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/232
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/qfj
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/u9M
- 社区便民服务的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/596=eea
- 消防知识宣传的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/lad=567
- 垃圾分类指导的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/iyS=nrA
- 街道综合服务的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/194
- 休闲运动入门的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/vmo
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/6GB
- 小区公共照明的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/998=nsp
- 儿童友好空间的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/dot=769
- 骑行路线规划的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/fWF=CyL
- 非遗体验活动的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/356
- 终身学习资源的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/jdq
- 全民阅读推广的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/grW
- 急救知识普及的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/953=ald
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/hck=698
- 消防知识宣传的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/8ip=RCn
- 机器学习入门的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B5%B0%E5%8A%BF%E5%9B%BE_360%E5%85%AC%E5%BC%80%E8%AF%BE?/543
- 家庭节能设备的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B5%B0%E5%8A%BF%E5%9B%BE_360%E5%85%AC%E5%BC%80%E8%AF%BE?/aji
- 节日文化体验的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B5%B0%E5%8A%BF%E5%9B%BE_360%E5%85%AC%E5%BC%80%E8%AF%BE?/RDC
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B5%B0%E5%8A%BF%E5%9B%BE_360%E5%85%AC%E5%BC%80%E8%AF%BE?/250=dxf
- 科学睡眠习惯从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B5%B0%E5%8A%BF%E5%9B%BE_360%E5%85%AC%E5%BC%80%E8%AF%BE?/eeh=810
- 电子商务服务的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B5%B0%E5%8A%BF%E5%9B%BE_360%E5%85%AC%E5%BC%80%E8%AF%BE?/Wht=yck
- 青少年编程学习的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/765
- 社区养老服务的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/zhc
- 家庭节能实践的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/Pth
- 社区托育服务的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/532=jvn
- 城市夜间生活的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/fvi=653
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/JQs=J1o
- 机器人科普活动的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%9B%9E%E8%A1%80_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/046
- 开放式学习空间的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%9B%9E%E8%A1%80_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/edg
- 软件开发学习的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%9B%9E%E8%A1%80_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/KZB
- 城市绿色交通的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%9B%9E%E8%A1%80_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/252=nxj
- 城市展览体验的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%9B%9E%E8%A1%80_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/jos=377
- 居家适老化改造的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%9B%9E%E8%A1%80_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/pXn=kiV
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8A%E5%B2%B8_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/185
- 社区垃圾回收的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8A%E5%B2%B8_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/ccu
- 食品配送体验的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8A%E5%B2%B8_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/Xlg
- 地方美食文化的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8A%E5%B2%B8_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/230=vzt
- 消防知识宣传的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8A%E5%B2%B8_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/pwk=336
- 在线学习体验的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8A%E5%B2%B8_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/gMA=UCl
- 邻里互助活动的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/224
- 公共服务指南的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/pij
- 非遗课堂体验的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/omX
- 公交站点体验的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/993=elu
- 社区家政服务的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/eop=087
- 节假日出行安排的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/TPu=PHu
- 公共空间安全的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%A5%BC%E5%B8%82?/742
- 小区公共照明的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%A5%BC%E5%B8%82?/cmj
- 便民信息查询的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%A5%BC%E5%B8%82?/FOu
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%A5%BC%E5%B8%82?/131=qed
- 新能源出行的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%A5%BC%E5%B8%82?/ply=687
- 街区更新实践的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%A5%BC%E5%B8%82?/1dy=dbi
- 街头绿植养护的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/864
- 社区读书角建设的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/evz
- 公园休闲体验的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/I6D
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/351=xcf
- 社区停车服务的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/nag=520
- 社区文化节活动的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/hta=wVy
- 网络信息辨识的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/289
- 环境教育课程的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/kff
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/ljD
- 基层健康服务的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/001=neq
- 青年就业服务的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/xup=876
- 城市夜间照明的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/JX7=bcb
- 社区便民集市的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/318
- 绿色出行服务的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/gfw
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/T8q
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/578=shj
- 课后服务体验的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/gpv=853
- 通勤路线规划中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/FeD=mb6
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/495
- 环境教育课程的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/kah
- 城市应急广播的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/Eik
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/065=etc
- 科普展览体验的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/mja=454
- 周末休闲规划的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/m1i=bkT
- 文明养宠科普的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%83%BD%E6%BA%90?/186
- 城市博物馆服务的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%83%BD%E6%BA%90?/sxs
- 农贸市场环境的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%83%BD%E6%BA%90?/3mE
- 街头绿植养护的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%83%BD%E6%BA%90?/029=zom
- 农产品品牌传播的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%83%BD%E6%BA%90?/lrk=167
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%83%BD%E6%BA%90?/2pN=l89
- 在线学习体验中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/549
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/ctp
- 老年数字阅读的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/7Sx
- 城市骑行环境的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/772=nee
- 地方文化传播的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/sje=071
- 公园亲子设施的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/yix=Jbg
- 文化场馆预约的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/927
- 城乡交通衔接的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/bcw
- 志愿服务平台的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/VCG
- 人工智能科普的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/051=pjg
- 人工智能科普的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/fai=133
- 软件开发学习中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/I6S=lyU
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/839
- 儿童安全出行的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/yqd
- 家庭科学教育的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/2BM
- 智能手机助老的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/162=iwp
- 智慧停车服务的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/wlw=943
- 数字创作工具的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/jfB=e8H
- 气象科普传播的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/800
- 乡村公共文化的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/nme
- 城市可持续生活的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/K0g
- 老年人出行服务的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/076=aho
- 社区公共议事的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/dns=829
- 物业服务沟通的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/qfl=l2W
- 街区更新实践的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/094
- 城市游园体验的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/xnw
- 亲子科普活动的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/Qhr
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/509=fik
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/xly=688
- 公共空间休憩的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/F7H=o33
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%85%A7%E7%9C%BC?/611
- 创业经验分享的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%85%A7%E7%9C%BC?/ceo
- 基层服务创新的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%85%A7%E7%9C%BC?/2BW
- 青少年户外教育的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%85%A7%E7%9C%BC?/127=lya
- 生活技能分享的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%85%A7%E7%9C%BC?/kfz=410
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%85%A7%E7%9C%BC?/ksC=ZYm
- 终身学习资源的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/704
- 环境教育课程的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/vuw
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/GNW
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/856=lfi
- 乡村产业科普的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/lwx=647
- 数字素养提升的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/7Kl=vCK
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/522
- 节约用水实践的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/zhs
- 城市可持续生活的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/C2U
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/781=hsl
- 乡村生态观察的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/jlq=893
- 个人时间管理的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/OCl=ZGZ
- 数字支付体验的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/830
- 城市公共饮水的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/qge
- 社区宠物管理的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/BGD
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/019=lwe
- 家庭节能实践的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/fif=200
- 科学运动指导的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/Gvm=2OX
- 社区生活指南的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/571
- 线上办事服务的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/ndf
- 健康饮水科普的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/Cme
- 电动汽车充电中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/285=awm
- 数字便民地图从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/bve=371
- 城市绿色交通的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/xmt=28r
- 急救知识普及的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/461
- 乡村教育资源的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/bdp
- 亲子科普活动的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/mRV
- 灵活就业交流的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/383=lcm
- 垃圾分类指导的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/xsk=256
- 居家防滑改造的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/joy=Hpl
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/412
- 城市展览体验的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/oot
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/qeX
- 城市步行环境的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/931=axm
- 终身学习资源的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/cpw=903
- 非遗体验活动的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/JA6=bva
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/768
- 口袋公园建设中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/jdh
- 城乡公共服务的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/KWM
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/954=kov
- 社区读书角建设的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/wje=553
- 居家适老化改造的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/TTv=z18
- 公共服务咨询的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/889
- 科技馆参观体验的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/oya
- 校园阅读活动的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/JhP
- 社区修缮行动的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/258=emj
- 公共图书馆服务的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/vpf=203
- 乡村产业科普的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/8Se=GPP
- 社区菜市场服务的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/664
- 城乡交流活动的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/koi
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/Slm
- 农业科普体验的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/327=oay
- 健康饮食教育有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/mgl=149
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/8Rm=IiW
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/717
- 图书馆活动策划的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/bhz
- 家庭阅读计划的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/Xw3
- 数字创意课程的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/889=yya
- 市民热线服务的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/dup=515
- 校园安全教育的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/wot=rOJ
- 城市住房服务的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/160
- 城市生活服务的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/cjp
- 社区法律科普的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/81m
- 城市运动公园的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/780=nul
- 口袋公园建设的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/wog=407
- 气象科普传播的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/WxX=Gvg
- 城市博物馆活动的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/274
- 应急物资管理的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/bgu
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/oB2
- 本地消费场景的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/594=zlq
- 线上阅读资源的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/dfv=458
- 社区垃圾分类的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/thN=Tw8
- 数字创意课程的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF?/337
- 城市适老服务的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF?/qpw
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF?/lVA
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF?/771=yqu
- 急救知识普及的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF?/uvb=748
- 就业技能培训的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF?/kZm=KRB
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/517
- 网络安全教育的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/xsf
- 城市应急广播的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/o98
- 家庭网络使用的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/331=mbj
- 社区便民服务的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/xuk=541
- 文化讲座服务的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/ray=6cx

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
