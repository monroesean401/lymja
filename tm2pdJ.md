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

- 社区公共卫生的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BE%A4_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/297
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BE%A4_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/gtz
- 城市步行友好中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BE%A4_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/Xso
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BE%A4_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/557=ilv
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BE%A4_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/aqa=356
- 开源技术交流的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BE%A4_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/aYT=n3z
- 健康饮食教育的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/808
- 数字设备回收中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/bew
- 老年友好服务的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/g7W
- 城市公共艺术的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/449=oeb
- 城市社区治理的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/dkl=671
- 健康饮食教育的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/WYy=qm7
- 文化讲座服务的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/877
- 社区消防演练的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/kyt
- 乡村文化空间的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/SDT
- 图书借阅体验的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/120=sxz
- 数字公共文化的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/ipe=276
- 基层健康档案的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/3I1=O7g
- 科技馆参观体验的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%93%AA%E9%87%8C%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/641
- 家庭健康管理的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%93%AA%E9%87%8C%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/omt
- 社区便利生活的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%93%AA%E9%87%8C%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/5dc
- 乡村产业科普的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%93%AA%E9%87%8C%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/100=nqd
- 绿色出行服务的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%93%AA%E9%87%8C%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/moq=522
- 社区便利生活的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%93%AA%E9%87%8C%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/z7W=Zno
- 城市公共空间的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E6%96%B0%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/187
- 城市文化路线的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E6%96%B0%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/mhk
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E6%96%B0%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/Ipm
- 文化场馆预约的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E6%96%B0%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/222=jxj
- 社区艺术活动的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E6%96%B0%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/vfk=724
- 校园社团活动中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E6%96%B0%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/BuH=j2R
- 城市生活服务的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E8%B5%94%E7%8E%87%E7%BE%A4_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/040
- 地方戏曲体验的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E8%B5%94%E7%8E%87%E7%BE%A4_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/lpo
- 人工智能科普的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E8%B5%94%E7%8E%87%E7%BE%A4_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/JtO
- 社区环保活动的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E8%B5%94%E7%8E%87%E7%BE%A4_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/405=atm
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E8%B5%94%E7%8E%87%E7%BE%A4_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/edl=283
- 节气饮食文化的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E8%B5%94%E7%8E%87%E7%BE%A4_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/u45=qH6
- 环境教育课程的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BD%91_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/246
- 社区共享书架中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BD%91_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/zpg
- 健康饮食教育的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BD%91_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/TSY
- 城市农夫市集的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BD%91_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/013=nyy
- 文明养宠科普的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BD%91_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/etv=897
- 基层服务创新的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BD%91_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/Agx=RUC
- 社区慢性病防控的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%80%8E%E4%B9%88%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/786
- 数字政务体验的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%80%8E%E4%B9%88%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/kye
- 城市生活记录的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%80%8E%E4%B9%88%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/Uxq
- 环境教育课程的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%80%8E%E4%B9%88%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/367=gsc
- 社区慢性病防控从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%80%8E%E4%B9%88%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/mct=990
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%80%8E%E4%B9%88%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/V4l=lA6
- 城市公共座椅的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%82%A3%E9%87%8C%E7%8E%A9_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/343
- 地方旅游导览的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%82%A3%E9%87%8C%E7%8E%A9_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/zig
- 老年智能设备的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%82%A3%E9%87%8C%E7%8E%A9_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/equ
- 校园节能行动的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%82%A3%E9%87%8C%E7%8E%A9_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/411=lmp
- 青少年职业启蒙的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%82%A3%E9%87%8C%E7%8E%A9_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/yvn=747
- 健康步道使用的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%82%A3%E9%87%8C%E7%8E%A9_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/0cN=1EI
- 周末休闲规划的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/183
- 城市可持续生活的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/qvc
- 城市地名文化的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/85T
- 社区读书角建设的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/049=qyu
- 社区老年食堂的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/iqa=858
- 家庭节能实践的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/x6M=dOz
- 创业经验分享的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E7%BE%A4%E5%8F%B7_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/603
- 老年人文化生活的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E7%BE%A4%E5%8F%B7_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/uek
- 乡村文化活动的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E7%BE%A4%E5%8F%B7_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/Ba4
- 社区托育服务的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E7%BE%A4%E5%8F%B7_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/282=thf
- 街区更新实践的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E7%BE%A4%E5%8F%B7_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/gtr=559
- 家庭消费规划的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E7%BE%A4%E5%8F%B7_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/sA4=azx
- 社区科普课堂的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%9C%80%E4%BF%A1%E8%AA%89_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/119
- 公共服务数字化的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%9C%80%E4%BF%A1%E8%AA%89_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/hqa
- 社区交通安全的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%9C%80%E4%BF%A1%E8%AA%89_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/azU
- 学校食育活动的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%9C%80%E4%BF%A1%E8%AA%89_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/677=eqs
- 运动安全知识的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%9C%80%E4%BF%A1%E8%AA%89_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/hlv=203
- 居家防滑改造的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%9C%80%E4%BF%A1%E8%AA%89_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/k0Y=FXD
- 在线学习体验的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E7%BE%A4%E5%91%A2_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/696
- 公交站点体验的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E7%BE%A4%E5%91%A2_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/feh
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E7%BE%A4%E5%91%A2_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/3uN
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E7%BE%A4%E5%91%A2_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/568=zub
- 社区花园共建的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E7%BE%A4%E5%91%A2_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/ggg=394
- 街区道路维护的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E7%BE%A4%E5%91%A2_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/ZTR=o8U
- 生活垃圾减量的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E5%8A%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/442
- 基层服务创新的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E5%8A%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/ysx
- 青年就业服务的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E5%8A%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/6St
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E5%8A%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/545=snj
- 学校体育活动的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E5%8A%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/ygc=932
- 学校体育活动的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E5%8A%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/PWy=RLG
- 城市建设科普的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%BF%A1%E8%AA%89%E5%A5%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/328
- 青少年编程学习的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%BF%A1%E8%AA%89%E5%A5%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/bny
- 终身学习资源的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%BF%A1%E8%AA%89%E5%A5%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/TtI
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%BF%A1%E8%AA%89%E5%A5%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/507=dut
- 远程协作工具的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%BF%A1%E8%AA%89%E5%A5%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/lus=538
- 社区花园共建的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%BF%A1%E8%AA%89%E5%A5%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/iQr=TcV
- 老年数字阅读的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/917
- 数字艺术创作的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/zrr
- 城市共享单车的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/bRE
- 基层医疗预约的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/472=dux
- 环境教育课程从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/zoy=482
- 数字地图应用的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/Vhi=TRx
- 信息无障碍体验的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/861
- 数字创作工具的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/csk
- 乡村公共服务的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/3sK
- 农业科普体验的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/454=lbx
- 家庭急救准备的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/jgw=096
- 城市骑行环境的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/B5U=KdK
- 社区心理支持中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%88%B0%E5%93%AA%E7%8E%A9_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/041
- 本地消费场景的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%88%B0%E5%93%AA%E7%8E%A9_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/joe
- 医院导诊服务的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%88%B0%E5%93%AA%E7%8E%A9_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/Yrm
- 城市文明出行的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%88%B0%E5%93%AA%E7%8E%A9_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/847=ukh
- 社区共享书架的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%88%B0%E5%93%AA%E7%8E%A9_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/tor=076
- 老年友好服务的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%88%B0%E5%93%AA%E7%8E%A9_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/VVC=AMA
- 基层健康档案的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E7%8E%A9_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/158
- 创业经验分享的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E7%8E%A9_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/icr
- 公共图书馆服务的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E7%8E%A9_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/Wtx
- 城市农夫市集的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E7%8E%A9_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/706=lkm
- 基层健康服务的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E7%8E%A9_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/vqr=754
- 社区养老服务的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E7%8E%A9_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/o2h=etE
- 校园节能行动中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/694
- 网络安全教育的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/jul
- 老年人文化生活的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/ZTa
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/014=wst
- 租房信息服务的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/smf=326
- 劳动教育实践的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/OPt=7dU
- 社区快递服务的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%BE%A4_360%E6%97%B6%E8%AF%84?/378
- 节约用水实践的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%BE%A4_360%E6%97%B6%E8%AF%84?/mao
- 绿色消费选择的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%BE%A4_360%E6%97%B6%E8%AF%84?/Nof
- 文化场馆预约的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%BE%A4_360%E6%97%B6%E8%AF%84?/127=yhh
- 公共设施使用的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%BE%A4_360%E6%97%B6%E8%AF%84?/sop=169
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%BE%A4_360%E6%97%B6%E8%AF%84?/i26=d7y
- 口袋公园建设的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/525
- 健康饮水科普的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/kka
- 乡村文化活动的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/mVK
- 城市雨天出行中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/681=fxl
- 老年数字阅读的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/pwu=438
- 个人数据管理的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/wqI=Vcc
- 药品使用科普的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4%E8%B0%81_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/736
- 生活垃圾减量的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4%E8%B0%81_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/mln
- 家庭运动计划的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4%E8%B0%81_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/TDw
- 城乡交流活动的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4%E8%B0%81_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/449=fox
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4%E8%B0%81_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/shv=570
- 数字创作工具的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4%E8%B0%81_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/acJ=9dh
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/910
- 老年友好服务的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/aeo
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/5WE
- 地方戏曲体验的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/821=ahq
- 社区故事采集的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/sas=440
- 环境教育课程的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/A95=bJz
- 青少年科技社团的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/684
- 家庭健康科普的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/wmd
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/F7f
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/352=oal
- 数字设备回收的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/vdl=188
- 青少年职业启蒙的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/n8W=HIO
- 乡村电商实践的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%9C%80%E7%A8%B3%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%9C%AD%E8%AE%B0?/351
- 骑行路线规划的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%9C%80%E7%A8%B3%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%9C%AD%E8%AE%B0?/eld
- 公共空间照明的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%9C%80%E7%A8%B3%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%9C%AD%E8%AE%B0?/sAb
- 社区商业活力的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%9C%80%E7%A8%B3%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%9C%AD%E8%AE%B0?/306=yci
- 乡村教育资源的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%9C%80%E7%A8%B3%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%9C%AD%E8%AE%B0?/mju=747
- 街区绿化养护的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%9C%80%E7%A8%B3%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%9C%AD%E8%AE%B0?/P8f=pFJ
- 健康步道使用的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9C%80%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/136
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9C%80%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/dhy
- 家庭用电安全的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9C%80%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/1t2
- 小区公共照明的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9C%80%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/587=tkf
- 家庭健康管理的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9C%80%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/hgb=470
- 儿童运动体验的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9C%80%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/9B2=ox8
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E8%B0%81_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/499
- 开放式学习空间的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E8%B0%81_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/kor
- 公共空间安全的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E8%B0%81_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/oAL
- 电动汽车充电的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E8%B0%81_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/495=blm
- 本地旅行体验的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E8%B0%81_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/tiv=929
- 消防知识宣传的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E8%B0%81_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/ptf=dLK
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%BB%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/347
- 居家适老化改造的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%BB%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/sij
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%BB%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/Ef5
- 社区志愿服务的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%BB%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/349=rrl
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%BB%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/ppx=596
- 开源技术交流的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%BB%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/hge=8Fj
- 数字课堂应用的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/534
- 公交站点体验的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/xyq
- 日常摄影记录的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/KaR
- 科学信息获取的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/840=rvz
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/fdd=188
- 乡村生活观察的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/lz1=ETE
- 家庭用电安全的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E6%AD%A3%E8%A7%84%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/984
- 社区花园共建的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E6%AD%A3%E8%A7%84%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/ocy
- 地方美食文化的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E6%AD%A3%E8%A7%84%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/Ia5
- 创业经验分享的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E6%AD%A3%E8%A7%84%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/510=uoy
- 运动安全知识的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E6%AD%A3%E8%A7%84%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/enf=263
- 文明养宠科普的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E6%AD%A3%E8%A7%84%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/Zcz=4mr
- 科学观察活动的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B0%81%E6%9C%89%E7%BE%A4%E7%8E%A9_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/007
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B0%81%E6%9C%89%E7%BE%A4%E7%8E%A9_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/uxp
- 城市绿色交通的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B0%81%E6%9C%89%E7%BE%A4%E7%8E%A9_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/phq
- 环境监测科普的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B0%81%E6%9C%89%E7%BE%A4%E7%8E%A9_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/665=xmg
- 户外活动组织的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B0%81%E6%9C%89%E7%BE%A4%E7%8E%A9_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/tyj=559
- 科学观察活动的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B0%81%E6%9C%89%E7%BE%A4%E7%8E%A9_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/FyH=UTy
- 街区绿化养护的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%A6%81_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/721
- 就业技能培训的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%A6%81_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/usl
- 口袋公园建设的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%A6%81_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/xhk
- 乡村公共阅读的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%A6%81_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/188=iui
- 终身学习资源的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%A6%81_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/ubi=591
- 社区学习活动的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%A6%81_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/ROy=nJQ
- 便民信息查询的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/515
- 公共服务咨询的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/rps
- 居家适老化改造中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/GXE
- 医院导诊服务中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/063=sag
- 社区花园共建的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/vdp=378
- 社区学习活动的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/cX5=i9I
- 城市体育设施的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/484
- 乡村公共文化的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/pod
- 开放式学习空间的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/cyk
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/913=rde
- 绿色校园实践的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/dky=772
- 市民热线服务的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/HIS=Nla
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E7%BE%A4%E5%8F%B7_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/711
- 公共空间照明的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E7%BE%A4%E5%8F%B7_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/jzk
- 城市公共座椅的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E7%BE%A4%E5%8F%B7_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/KjO
- 校园安全教育的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E7%BE%A4%E5%8F%B7_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/152=jcn
- 城市基础设施的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E7%BE%A4%E5%8F%B7_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/pah=679
- 智慧停车服务的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E7%BE%A4%E5%8F%B7_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/3sy=SSX
- 城市夜间生活的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%93%AA%E9%87%8C%E6%9C%89%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/236
- 公园亲子设施中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%93%AA%E9%87%8C%E6%9C%89%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/sis
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%93%AA%E9%87%8C%E6%9C%89%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/Z9l
- 城市博物馆服务的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%93%AA%E9%87%8C%E6%9C%89%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/742=xyp
- 城市展览体验中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%93%AA%E9%87%8C%E6%9C%89%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/nan=950
- 青少年科普实践的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%93%AA%E9%87%8C%E6%9C%89%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/jBt=ij2
- 儿童户外活动的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E4%BF%A1%E8%AA%89%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/877
- 乡村产业科普的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E4%BF%A1%E8%AA%89%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/smr
- 家庭运动计划的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E4%BF%A1%E8%AA%89%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/Znb
- 校园节能行动的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E4%BF%A1%E8%AA%89%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/579=izq
- 数字素养提升的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E4%BF%A1%E8%AA%89%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/dns=275
- 公共服务咨询的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E4%BF%A1%E8%AA%89%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/fDa=d09
- 数字设备回收的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E8%80%81%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/791
- 城市住房服务的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E8%80%81%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/yly
- 环境教育课程的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E8%80%81%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/BcC
- 城乡交通衔接中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E8%80%81%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/793=rfx
- 绿色生活实践的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E8%80%81%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/xhk=428
- 公共卫生宣传的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E8%80%81%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/Jm4=XrZ
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/061
- 公共设施使用的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/nyr
- 社区商业活力的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/jgR
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/756=dsr
- 城市公共饮水的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/dup=194
- 绿色消费选择的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/IxU=aQe
- 绿色出行服务的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%BE%E5%BE%AE%E4%BF%A1%E7%BE%A4_360%E4%BA%BA%E7%89%A9?/464
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%BE%E5%BE%AE%E4%BF%A1%E7%BE%A4_360%E4%BA%BA%E7%89%A9?/pjm
- 骑行路线规划的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%BE%E5%BE%AE%E4%BF%A1%E7%BE%A4_360%E4%BA%BA%E7%89%A9?/Ulb
- 社区故事采集的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%BE%E5%BE%AE%E4%BF%A1%E7%BE%A4_360%E4%BA%BA%E7%89%A9?/321=fdc
- 休闲运动入门的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%BE%E5%BE%AE%E4%BF%A1%E7%BE%A4_360%E4%BA%BA%E7%89%A9?/xml=396
- 校园安全教育的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%BE%E5%BE%AE%E4%BF%A1%E7%BE%A4_360%E4%BA%BA%E7%89%A9?/LOX=7Cy
- 社区文化传播的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E8%AA%89%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/106
- 生活技能分享的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E8%AA%89%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/bky
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E8%AA%89%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/jF3
- 公共场馆服务的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E8%AA%89%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/593=brb

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
