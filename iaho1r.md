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

- 乡村产业科普的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A6%8F%E5%BD%A9_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/ETp
- 社区防暑服务的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A6%8F%E5%BD%A9_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/601=ulq
- 城市展览体验的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A6%8F%E5%BD%A9_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/ywn=827
- 生活服务数字化的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A6%8F%E5%BD%A9_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/P8y=37I
- 绿色消费选择的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/685
- 乡村阅读空间的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/jla
- 家庭理财科普的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/nfI
- 社区便民集市的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/626=fmu
- 数字地图应用的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/ygz=387
- 社区故事采集的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/APw=Xav
- 公共服务数字化的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/352
- 开放数据应用的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/zgk
- 社区活动报名的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/Cif
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/260=qvd
- 公共服务预约的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/lcu=787
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/nZ9=pan
- 青年职业探索的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/994
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/izy
- 社区养老服务的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/DG1
- 传统节日科普的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/266=ygc
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/mur=810
- 社区读书角建设的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/d1Z=rN4
- 运动安全知识的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BE%AE%E4%BF%A1%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99%E5%9B%BE_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/263
- 城市公共饮水的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BE%AE%E4%BF%A1%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99%E5%9B%BE_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/ejh
- 音乐欣赏活动的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BE%AE%E4%BF%A1%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99%E5%9B%BE_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/Wg0
- 邻里互助活动的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BE%AE%E4%BF%A1%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99%E5%9B%BE_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/118=kuk
- 城市生活记录的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BE%AE%E4%BF%A1%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99%E5%9B%BE_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/jsg=224
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BE%AE%E4%BF%A1%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99%E5%9B%BE_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/ZYc=c8X
- 智慧城市体验的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BA%A2%E5%8C%85%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/222
- 数字艺术创作的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BA%A2%E5%8C%85%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/uch
- 地方旅游导览中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BA%A2%E5%8C%85%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/FHu
- 小微企业服务的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BA%A2%E5%8C%85%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/429=fgx
- 数字学习资源的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BA%A2%E5%8C%85%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/ehx=202
- 城市步行友好的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BA%A2%E5%8C%85%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/hhN=PAU
- 绿色快递包装的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/407
- 便民服务窗口的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/ikd
- 新能源出行的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/3Gj
- 节能家电使用的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/783=tai
- 社区体育组织的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/mlo=361
- 数字生活课堂的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E5%99%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/Z82=sNh
- 社区志愿服务的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%8A%80_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/134
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%8A%80_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/agu
- 公共场所导视的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%8A%80_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/wxM
- 青少年户外教育的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%8A%80_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/933=ace
- 传统节日科普的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%8A%80_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/rwd=485
- 城市步行友好的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%8A%80_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/ie1=fOk
- 城市地名文化的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/925
- 开源技术交流的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/wbz
- 社区垃圾回收的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/FUI
- 基层服务创新的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/641=pwo
- 小微企业服务的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/vsm=777
- 社区协商议事的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/NCA=gjD
- 城市应急广播中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%89%88_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/617
- 社区庭院绿化的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%89%88_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/ozl
- 家庭健康管理的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%89%88_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/MVK
- 食品安全科普的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%89%88_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/761=hww
- 乡村生活观察的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%89%88_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/jfs=846
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%89%88_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/ZeK=NOR
- 家庭食品保存的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/605
- 公共空间照明的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/fle
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/AXX
- 城市公共艺术的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/272=wei
- 家庭志愿活动的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/dvx=808
- 社区花园共建的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/Lfu=8Gd
- 城市水环境观察的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95%E5%AE%98%E6%96%B9_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/733
- 开放式学习空间的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95%E5%AE%98%E6%96%B9_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/dbs
- 租房信息服务的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95%E5%AE%98%E6%96%B9_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/XqK
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95%E5%AE%98%E6%96%B9_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/650=nwv
- 城市夜间照明的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95%E5%AE%98%E6%96%B9_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/ijp=804
- 全民健身活动的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95%E5%AE%98%E6%96%B9_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/KNN=dPA
- 学校食育活动的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_360%E6%97%B6%E8%AE%AF?/101
- 社区体育组织的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_360%E6%97%B6%E8%AE%AF?/adj
- 科学信息获取的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_360%E6%97%B6%E8%AE%AF?/fHr
- 城乡交流活动的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_360%E6%97%B6%E8%AE%AF?/579=fak
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_360%E6%97%B6%E8%AE%AF?/kif=442
- 农产品消费体验的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_360%E6%97%B6%E8%AE%AF?/mG2=57o
- 本地消费场景的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/696
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/dhu
- 农贸市场环境的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/1Pz
- 城市噪声观察的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/564=kds
- 家庭用电安全的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/bdd=478
- 软件开发学习的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/DE9=kg1
- 数字阅读服务的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/357
- 城市环境志愿行动的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/upi
- 绿色生活实践的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/jmY
- 社区托育服务的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/624=bdk
- 城市公共标识中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/ddm=252
- 城市便民驿站的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/wex=h0Y
- 乡村公共文化的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/016
- 药品使用科普的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/cvu
- 老年数字阅读的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/8yo
- 农业科普体验的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/501=fls
- 家庭健康管理从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/nvl=313
- 青年就业服务的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/q2p=qi7
- 老年人文化生活的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/532
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/wsn
- 物业服务沟通的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/w2s
- 公共交通信息服务的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/891=axt
- 健康饮水科普的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/hus=415
- 休闲运动入门的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/37I=2x1
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/169
- 城市环境志愿行动的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/wyj
- 城市空气科普的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/3zx
- 社区活动空间的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/900=tyg
- 老年学习活动的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/hjt=553
- 数字资源检索的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/MjX=kPl
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/618
- 社区消防演练的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/fds
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/2xz
- 本地旅行体验的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/539=chx
- 乡村电商实践的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/voj=347
- 家庭节能实践的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/heY=Osk
- 科技馆参观体验的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2026%E5%90%88%E8%A7%84%E5%A4%87%E5%BF%98pc%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/127
- 学校食育活动的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2026%E5%90%88%E8%A7%84%E5%A4%87%E5%BF%98pc%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/ufg
- 地方美食文化的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2026%E5%90%88%E8%A7%84%E5%A4%87%E5%BF%98pc%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/aI6
- 儿童友好空间的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2026%E5%90%88%E8%A7%84%E5%A4%87%E5%BF%98pc%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/662=cvk
- 个人数据管理的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2026%E5%90%88%E8%A7%84%E5%A4%87%E5%BF%98pc%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/kuu=713
- 乡村休闲旅游的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2026%E5%90%88%E8%A7%84%E5%A4%87%E5%BF%98pc%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/FXI=bY9
- 社区便民服务的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/049
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/hiq
- 城市雨天出行的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/PHn
- 绿色办公实践的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/729=fot
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/bxz=213
- 灵活就业交流的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/32j=oMm
- 生成式工具使用的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/063
- 街区小店体验的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/gff
- 课后服务体验的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/8np
- 社区垃圾回收的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/361=msf
- 城市应急科普的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/tsx=881
- 社区菜市场服务的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/jZ5=AwZ
- 社区宠物管理中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/827
- 老年数字阅读的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qrr
- 家庭科学教育的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/fF9
- 城市人文观察的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/765=abx
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wyz=479
- 气象科普传播的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/LhX=819
- 数据分析入门中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/685
- 基层健康档案的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/gne
- 创业经验分享的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/qZy
- 社区活动策划的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/384=jqh
- 急救知识普及的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/qkt=707
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/nS8=6lw
- 城市文明实践的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/656
- 便民服务窗口的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/zea
- 社区故事采集的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/tes
- 远程协作工具从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/519=beb
- 个人数据管理的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/sjd=503
- 节气饮食文化中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/0Hl=3q9
- 公交站点体验的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/772
- 通勤路线规划的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/fvs
- 创业经验分享的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/PDl
- 居民健康教育的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/062=jos
- 老年数字阅读的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/ejs=509
- 老年人出行服务的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/cZU=8K9
- 传统节日科普的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/775
- 公共服务数字化的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/qcg
- 城市社区治理的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/zB9
- 休闲运动入门从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/728=foa
- 终身学习资源的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/tmu=442
- 社区心理支持的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/4UZ=TqP
- 老年友好服务中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%95%B0%E7%A0%81?/466
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%95%B0%E7%A0%81?/zbj
- 骑行路线规划的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%95%B0%E7%A0%81?/cOM
- 职业技能学习的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%95%B0%E7%A0%81?/557=qkw
- 城市公共艺术的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%95%B0%E7%A0%81?/hdm=387
- 数字支付体验的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%95%B0%E7%A0%81?/Ddx=CQJ
- 开放数据应用的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/063
- 社区文化传播的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/ejo
- 街区更新实践的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/TWf
- 城乡交通衔接的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/761=cmo
- 数字地图应用的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/twx=990
- 机器学习入门的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/TV7=hbH
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E9%80%86%E5%8A%BF%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/813
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E9%80%86%E5%8A%BF%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/mlm
- 公共服务预约的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E9%80%86%E5%8A%BF%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/Rma
- 城市应急科普从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E9%80%86%E5%8A%BF%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/033=jjl
- 文化讲座服务的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E9%80%86%E5%8A%BF%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/lqa=752
- 老年智能设备的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E9%80%86%E5%8A%BF%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/eY5=ns1
- 街头绿植养护的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/890
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/mlm
- 公共服务沟通的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/Bu8
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/640=rrn
- 公共交通接驳的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/puq=481
- 网络安全教育的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/p1M=ELm
- 生活垃圾减量的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/368
- 社区设施共享的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/lwp
- 开放数据应用的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/xcV
- 社区生活指南的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/388=itm
- 家庭照护支持的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/pvp=283
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/jhF=vEx
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/376
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/ain
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/502
- 节气饮食文化的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/771=qzk
- 图书馆数字服务的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/wsm=942
- 城市公共标识的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/X4L=ele
- 社区学习活动的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/601
- 社区教育资源的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/xpy
- 电动汽车充电中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/3NB
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/955=rno
- 公共图书馆服务的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/djx=527
- 个人信息保护的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/Hrj=s3h
- 家庭安全提示的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/325
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/ggc
- 公园亲子设施的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/Kwg
- 社区公共卫生的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/234=zva
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/wot=099
- 城市便民驿站的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/yEM=5YU
- 乡村公共服务的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/683
- 城市体育设施的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/rlu
- 网络信息辨识的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/F5F
- 职业技能学习的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/760=txu
- 乡村公共阅读的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/kdy=143
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/N62=1gm
- 社区家校合作的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD._%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/881
- 城市休闲步道的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD._%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/yyg
- 公共卫生宣传的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD._%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/LLm
- 灵活就业交流的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD._%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/487=hsh
- 数字资源检索的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD._%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/dxi=821
- 社区手工活动的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD._%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/vXk=fhY
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/123
- 儿童运动体验的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/lea
- 城市文明出行的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/pn3
- 城市骑行环境的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/643=qbg
- 公共设施使用的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/vpf=190
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/Et1=zQq
- 乡村生态旅游的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/188
- 城市公共艺术的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/avi
- 社区便民集市的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/rf2
- 公共卫生宣传的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/763=hfr
- 社区邻里服务的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/wth=375
- 基层医疗预约的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/zLf=CpX
- 绿色办公实践的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/711
- 家庭安全提示的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/xnj
- 青少年科普实践的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/A10
- 健康饮食教育的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/405=yja
- 家庭用电安全的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/qkm=018
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/kcz=PBs
- 乡村公共服务的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/309
- 公益活动组织的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/gzg
- 软件开发学习的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/93n
- 小区公共照明的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/193=vjo
- 亲子科普活动的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/qtb=621
- 地方戏曲体验的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/L7c=DXO
- 生活技能分享的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/834
- 小区停车协商的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/niz
- 居家适老化改造的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/8vn
- 亲子科普活动的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/536=vyi
- 生活垃圾减量的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/stx=076
- 老年数字阅读的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/j4E=Ksi

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
