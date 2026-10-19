# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 在线学习体验的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/353
- 城市生活记录的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/euz
- 节日文化体验的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/wIf
- 社区公共餐饮的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/282=dxy
- 小区电梯维护的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/yfp=628
- 家庭照护支持的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/356=5Wz
- 社区公共卫生的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E9%B8%BF%E8%BF%90-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/695
- 地方文化传播的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E9%B8%BF%E8%BF%90-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/qfz
- 家庭收纳实践的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E9%B8%BF%E8%BF%90-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/4Fr
- 城市文明实践的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E9%B8%BF%E8%BF%90-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/420=txe
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E9%B8%BF%E8%BF%90-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/ngr=086
- 小微企业服务的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E9%B8%BF%E8%BF%90-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/t4o=y02
- 机器人科普活动的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/483
- 社区商业活力的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/mpe
- 公共文化活动中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/Wob
- 青年就业服务的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/859=ndg
- 城市空气科普的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/cjg=716
- 城市树木认养的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/XtI=EGj
- 居民健康教育的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/508
- 青少年户外教育的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/new
- 数字公共文化的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/spx
- 乡村阅读活动的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/576=opb
- 老年数字阅读的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/lfm=260
- 公共健身器材的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/mQv=Dir
- 传统手工艺体验的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E9%B8%BF%E8%BF%90-APP_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/243
- 基层医疗预约的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E9%B8%BF%E8%BF%90-APP_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/fra
- 居家防滑改造的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E9%B8%BF%E8%BF%90-APP_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/6GV
- 社区教育资源的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E9%B8%BF%E8%BF%90-APP_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/098=hdy
- 社区消防演练的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E9%B8%BF%E8%BF%90-APP_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/zdl=337
- 城市建设科普的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E9%B8%BF%E8%BF%90-APP_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/eqd=iVB
- 智能手机助老的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E8%BF%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/265
- 社区便利生活的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E8%BF%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/okn
- 文明养宠科普的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E8%BF%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/XH0
- 乡村产业科普的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E8%BF%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/418=pur
- 社区读书角建设的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E8%BF%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/fni=823
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E8%BF%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/XE3=LhD
- 城市文明出行的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/337
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/hma
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/oj0
- 城市公共自行车的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/634=wbx
- 公共服务预约的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/tmr=876
- 本地旅行体验的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/WZI=RqW
- 城市文明实践的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/212
- 公交无障碍服务的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/ccl
- 节气饮食文化的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/x1x
- 公共空间导览的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/170=yop
- 就业技能培训的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/spa=568
- 文化遗产保护科普的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/jQy=a74
- 邻里共享空间的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/355
- 老年人文化生活的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/xmj
- 城市夜间生活的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/azy
- 科技馆参观体验的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/814=asw
- 城市水环境观察的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/iih=578
- 社区花园共建的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/GMJ=20Z
- 老年数字阅读的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E9%B8%BF%E8%BF%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/940
- 城乡交流活动的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E9%B8%BF%E8%BF%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/xur
- 城市运动公园的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E9%B8%BF%E8%BF%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/dNu
- 数字创意课程的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E9%B8%BF%E8%BF%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/962=wrd
- 休闲运动入门的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E9%B8%BF%E8%BF%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/iez=691
- 节能家电使用的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E9%B8%BF%E8%BF%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/S4q=F1j
- 地方旅游导览的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/677
- 城市应急科普的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/brd
- 数字艺术创作的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/mJm
- 家庭用电安全的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/699=jen
- 街区更新实践的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/bxn=519
- 社区防暑服务的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%B8%BF%E8%BF%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/IF4=WgF
- 社区便民集市的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/871
- 城市应急科普的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/ksu
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/ETH
- 日常摄影记录的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/259=lls
- 社区共享书架的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/vxk=113
- 无障碍出行的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/1Pl=JA7
- 社区知识分享的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/048
- 数字阅读服务的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/rbu
- 城市体育设施的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/lfA
- 家庭园艺实践的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/083=yeo
- 便民维修服务的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/kkz=753
- 城市住房服务的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/V2r=Pg0
- 乡村教育资源的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E8%BF%90-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/378
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E8%BF%90-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/ajl
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E8%BF%90-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/qNy
- 健康饮水科普的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E8%BF%90-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/947=ugv
- 公共健身器材的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E8%BF%90-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/bdh=104
- 城市公共标识的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E8%BF%90-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/41K=ndk
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/182
- 基层健康档案的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/lwp
- 地方文化传播的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/Rre
- 城市可持续生活的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/855=lna
- 社区防暑服务的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/skg=165
- 基层医疗预约的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E9%B8%BF%E8%BF%90-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/qRP=cjR
- 街区更新实践的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/958
- 开放式学习空间的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/fdp
- 地方戏曲体验的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/Hs6
- 乡村阅读空间的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/431=sob
- 公共交通接驳的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/aek=855
- 居民健康教育中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/oRd=Wyu
- 社区法律科普的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/751
- 城市树木认养的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/qav
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/ntE
- 亲子科普活动中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/687=uhc
- 社区便民服务中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/ger=881
- 邻里互助活动的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/mBv=Rec
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/980
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/adk
- 社区志愿服务的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/nGT
- 健康饮水科普的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/155=brd
- 老年人日常照护的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/hdg=437
- 社区共享书架中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/Yjo=bCw
- 数字学习资源的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/211
- 节假日出行安排的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/gvd
- 公共场馆服务的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/PV3
- 乡村电商实践的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/244=txn
- 公共服务数字化的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/fmc=318
- 数字支付体验的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/lpR=H4w
- 家庭环保习惯的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/200
- 家庭照护支持的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/xco
- 社区防暑服务的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/jCZ
- 城市便民驿站的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/567=tpv
- 绿色办公实践的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/amp=582
- 城乡公共服务的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/3lC=p5m
- 无障碍出行的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/192
- 节能生活方式的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/vpr
- 公共设施维护的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/vk1
- 绿色快递包装的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/914=twz
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/enp=567
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/9Ti=SVs
- 公共服务评价的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/321
- 城乡交流活动的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/heq
- 城市博物馆活动的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/EZd
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/081=jok
- 儿童运动体验的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/cth=324
- 社区运动空间的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/tyT=dd2
- 线上阅读资源的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/835
- 节日文化体验的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/urv
- 在线教育体验的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/Xdh
- 乡村文化活动的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/692=jbs
- 在线学习体验的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/epu=217
- 社区修缮行动中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/0pD=41C
- 社区文化节活动的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/259
- 街区更新实践的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/teu
- 生活服务数字化的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/B47
- 基层健康档案的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/717=hql
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/bfz=955
- 农村环境治理的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/Zl2=qfJ
- 乡村文化活动的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/119
- 创业经验分享的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/sgz
- 城市游园体验的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/jvj
- 社区活动策划的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/022=iwi
- 城市适老服务的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/llp=989
- 城市游园体验的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/uhK=VHk
- 社区交通安全的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%9F%8E%E4%BA%8B?/496
- 街道综合服务的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%9F%8E%E4%BA%8B?/mgd
- 食品安全科普的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%9F%8E%E4%BA%8B?/VsP
- 城市可持续生活的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%9F%8E%E4%BA%8B?/479=jel
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%9F%8E%E4%BA%8B?/hdr=529
- 城市文明实践的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%9F%8E%E4%BA%8B?/BZk=BKX
- 志愿者培训交流的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/012
- 公共服务指南从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/sfc
- 小区公共照明的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/gVb
- 医院导诊服务的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/084=lsh
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/mkb=914
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/yBh=1GF
- 家庭网络使用的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/886
- 便民信息查询的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/ssr
- 学校体育活动的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/bbY
- 非遗课堂体验的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/499=rmm
- 数字艺术创作的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/otv=056
- 图书馆数字服务的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/Tqm=gBY
- 街区绿化养护中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/310
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/kog
- 生成式工具使用的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/w5A
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/305=qsd
- 社区教育资源的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/yjz=362
- 智慧城市体验中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/VDz=jun
- 绿色出行服务的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/081
- 社区邻里服务的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/zys
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/b3W
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/825=hsa
- 校园节能行动的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/zpx=952
- 消防知识宣传的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/zoc=LoO
- 节日文化体验的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%AE%8F%E8%A7%82?/552
- 城市可持续生活的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%AE%8F%E8%A7%82?/vkt
- 地方文化传播的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%AE%8F%E8%A7%82?/7J7
- 农村环境治理的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%AE%8F%E8%A7%82?/283=hja
- 便民服务窗口的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%AE%8F%E8%A7%82?/ftd=866
- 职业技能学习的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%AE%8F%E8%A7%82?/KBO=RD4
- 线上阅读资源的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/014
- 农产品品牌传播的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/hit
- 社区防暑服务的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/PBv
- 科技馆参观体验的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/199=myr
- 社区生活指南的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/dwk=439
- 就业技能培训的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/bXe=dUB
- 城市宠物友好空间中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/794
- 数字公共文化的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/zdp
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/nnS
- 城市生活服务的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/754=frz
- 城市雨天出行的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/gik=967
- 乡村文化空间的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%A9%E7%A5%A8?/tbz=jjv
- 在线学习体验的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/145
- 医院导诊服务的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/kqx
- 气象科普传播的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/HxH
- 青少年科技社团的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/699=tnv
- 社区体育组织的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/kgb=987
- 社区志愿服务的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/quk=XG4
- 数字公共文化的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/681
- 数字便民地图的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/gyu
- 志愿者培训交流的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/RXw
- 公共设施维护的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/884=vsm
- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/lzt=662
- 社区便民服务的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/hE0=LTP
- 城市步行环境的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E5%9F%8E%E4%BA%8B?/756
- 学校体育活动的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E5%9F%8E%E4%BA%8B?/gpq
- 社区绿色空间的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E5%9F%8E%E4%BA%8B?/PjC
- 日常摄影记录的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E5%9F%8E%E4%BA%8B?/032=xto
- 数字支付体验的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E5%9F%8E%E4%BA%8B?/mat=909
- 邻里互助活动的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E5%9F%8E%E4%BA%8B?/NR4=kgk
- 城市建设科普的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/322
- 新能源知识普及的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/flr
- 农业科普体验的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/Wtd
- 便民信息查询的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/043=isc
- 公交站点体验的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/tio=721
- 老年友好服务的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/N7r=KBp
- 老年运动活动的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9B%AD%E8%89%BA?/798
- 光伏知识科普的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9B%AD%E8%89%BA?/lyi
- 小区停车协商的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9B%AD%E8%89%BA?/Ni6
- 街区道路维护的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9B%AD%E8%89%BA?/689=vpt
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9B%AD%E8%89%BA?/fwx=275
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9B%AD%E8%89%BA?/HUc=Gki
- 线上阅读资源的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/065
- 环境教育课程的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/uox
- 电子商务服务的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/Pd6
- 老旧小区改造的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/260=nvd
- 城市公共厕所中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/gxx=888
- 环境教育课程的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/1zl=qjY
- 社区垃圾回收的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/958
- 乡村生态旅游的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/sdj
- 乡村文化活动的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/mqx
- 社区设施共享的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/199=nyw
- 图书借阅体验的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/kgh=055
- 公园亲子设施的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/pVk=Bpz
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/216
- 社区垃圾回收的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/yzh
- 青年职业探索的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/DSH
- 街区小店体验的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/485=kli
- 家庭健康科普的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/dcz=015
- 城市应急广播的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/N3t=Iaa
- 城市文明实践的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/870
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/txc
- 家庭科学教育的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/MmT
- 无障碍出行从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/125=rqz

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
