# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 家庭园艺实践的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/jEx
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/797=gqd
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/feh=227
- 青年就业服务的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_1889%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/Xi1=Z08
- 开放式学习空间的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_1889%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/359
- 亲子科普活动的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_1889%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/eqe
- 城市游园体验的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_1889%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/yxC
- 社区故事采集的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_1889%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/894=eot
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_1889%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/tza=465
- 乡村教育资源的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_1889%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/5ej=24S
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/547
- 社区环保活动的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/xco
- 地方文化传播的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/o7e
- 软件开发学习的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/131=eyz
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/axn=830
- 老年人日常照护的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/4gf=FmT
- 无障碍出行的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83%E5%BD%A9%28kxc%29_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/671
- 文明养宠科普的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83%E5%BD%A9%28kxc%29_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/ofk
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83%E5%BD%A9%28kxc%29_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/Xud
- 地方旅游导览的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83%E5%BD%A9%28kxc%29_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/753=jzq
- 乡村文化活动的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83%E5%BD%A9%28kxc%29_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/jie=722
- 社区故事采集的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83%E5%BD%A9%28kxc%29_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/ML1=HhX
- 社区艺术活动的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/467
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/xzn
- 居家适老化改造的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/9LX
- 城市绿道建设的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/233=pvm
- 城市可持续生活的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/ztj=026
- 社区健康讲座的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/RDz=hS5
- 社区绿色空间的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/749
- 邻里互助活动的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/scx
- 本地消费场景的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/csE
- 街区绿化养护的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/789=fpi
- 音乐欣赏活动的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/sxd=945
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/Rt3=MvV
- 城市展览体验的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BB%BC%E8%89%BA?/182
- 读书会组织的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BB%BC%E8%89%BA?/kri
- 城市树木认养的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BB%BC%E8%89%BA?/VZx
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BB%BC%E8%89%BA?/121=jvn
- 科学信息获取的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BB%BC%E8%89%BA?/qcr=076
- 社区安全巡查的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BB%BC%E8%89%BA?/W1w=bR2
- 家庭环保习惯的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/577
- 家庭急救准备的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/jqx
- 个人信息保护的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/O4I
- 机器人科普活动的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/488=obm
- 社区休闲设施的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/lgz=521
- 数字创意课程的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/8h5=tHE
- 数字设备回收的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA?/690
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA?/sxm
- 便民服务地图的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA?/k2F
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA?/390=oth
- 健康步道使用的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA?/mtk=045
- 生成式工具使用的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA?/zSV=lmN
- 数字课堂应用的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/685
- 社区手工活动的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/ssk
- 城市游园体验的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/z8z
- 公共空间照明的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/633=mez
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/lsr=508
- 社区学习活动的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/XV2=3RF
- 垃圾分类指导的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/489
- 个人时间管理的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/nln
- 街区道路维护的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/Gjm
- 社区环保活动的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/061=cof
- 街区道路维护的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/lfm=429
- 社区健康讲座的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/5In=r2F
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/576
- 个人数据管理的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/dzk
- 就业技能培训的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/KgM
- 社区健康讲座的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/845=wgx
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/vsw=326
- 读书会组织的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/5N9=lsc
- 家庭节能实践的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-welcome_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/890
- 儿童运动体验的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-welcome_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/fyk
- 家庭节能设备的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-welcome_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/dgW
- 灵活就业交流的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-welcome_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/993=kre
- 科普展览体验的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-welcome_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/zyc=516
- 电子商务服务的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-welcome_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/Xff=fFN
- 农贸市场环境的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%97%85%E6%B8%B8?/392
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%97%85%E6%B8%B8?/ohv
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%97%85%E6%B8%B8?/ShM
- 户外活动组织的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%97%85%E6%B8%B8?/596=utp
- 公交站点体验的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%97%85%E6%B8%B8?/lei=518
- 家庭理财科普的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%97%85%E6%B8%B8?/kOw=Glj
- 家庭环保行动的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/906
- 城市宠物友好空间的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/uxj
- 城市建设科普的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/Xmm
- 灵活就业交流的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/390=lpn
- 城市夜间照明的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/ysl=229
- 生活垃圾回收的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/Ee4=kZ3
- 口袋公园建设的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/229
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/txv
- 城市树木认养的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/Qlo
- 数字阅读服务的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/499=vtl
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/ryk=760
- 社区防暑服务的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%90%89%E5%88%A9welcome%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%9B%AD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/o5N=UtO
- 本地消费场景的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%A0%81_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/864
- 城市公共自行车的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%A0%81_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/dol
- 新能源知识普及的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%A0%81_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/js3
- 社区活动策划的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%A0%81_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/629=vbh
- 社区慢性病防控的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%A0%81_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/fzy=046
- 医院导诊服务的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%A0%81_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/SWw=nhK
- 家庭食品保存的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%90%89%E5%88%A9%E8%81%8A%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/321
- 街区更新实践中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%90%89%E5%88%A9%E8%81%8A%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/shi
- 青少年户外教育的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%90%89%E5%88%A9%E8%81%8A%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/uc1
- 节能生活方式的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%90%89%E5%88%A9%E8%81%8A%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/341=fvo
- 数字艺术创作的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%90%89%E5%88%A9%E8%81%8A%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/tzc=043
- 科学健身方法的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%90%89%E5%88%A9%E8%81%8A%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/ffx=lDd
- 数字素养提升的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%90%97_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/491
- 社区安全巡查的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%90%97_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/psv
- 青年志愿活动中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%90%97_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/yFS
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%90%97_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/161=kau
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%90%97_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/xgy=203
- 老年数字阅读的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%90%97_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/OVW=IQX
- 家庭用电安全的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/329
- 职业技能学习的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/dfz
- 城市雨天出行的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/iSy
- 城乡交通衔接的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/756=uxx
- 社区文化节活动的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/mkj=227
- 健康步道使用的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/1qr=cwN
- 社区休闲设施的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/700
- 小区停车协商的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/isy
- 社区家校合作的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/OdE
- 城乡交流活动的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/142=eap
- 社区文化节活动的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/umd=830
- 社区商业活力的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/ywm=Jp6
- 线上办事服务的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/658
- 老年运动活动的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/dfs
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/o0m
- 基层健康档案的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/851=aur
- 社会体育指导的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/grq=695
- 社区应急准备的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/M5b=aNR
- 数字公共文化的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/186
- 城市博物馆服务从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/bwd
- 科学观察活动的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/WmT
- 绿色快递包装的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/485=vxj
- 在线学习体验的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/cnd=200
- 通勤路线规划的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/Wwm=DPm
- 社区托育服务的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/217
- 城市休闲步道中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/hsd
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/BAN
- 数字阅读服务的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/796=zzw
- 全民阅读推广的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/wiu=908
- 社区法律科普的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/Ruc=o6C
- 家庭食品保存的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/481
- 社区托育服务的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/lqg
- 社区绿色空间的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/Fu7
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/484=obe
- 校园节能行动的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/bsj=672
- 基层服务创新的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/ItX=BZg
- 乡村生活观察的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/952
- 机器学习入门的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/bon
- 老年数字阅读的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/5K1
- 社区菜市场服务的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/053=rfm
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/gqf=368
- 儿童阅读角的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/Bez=Wuc
- 社区设施共享的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/775
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/aln
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/vZV
- 租房信息服务中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/427=vge
- 终身学习资源的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/adf=920
- 街区道路维护中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/KLx=1YP
- 城市夜间照明的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/499
- 线上阅读资源中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/zdd
- 数字艺术创作的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/OWm
- 文明养宠科普中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/578=ikt
- 街区绿化养护的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/ehn=090
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/8KR=ysD
- 零废弃生活尝试的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/566
- 社区停车服务的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/qrb
- 城市水环境观察的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/lkE
- 社区阅读服务的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/689=mqr
- 城市运动公园的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/qkj=690
- 家庭环保行动的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/1G5=loH
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E9%87%91%E6%BB%A1%E5%9C%B0%E6%88%BF%E5%9C%B0%E4%BA%A7%E5%BC%80%E5%8F%91%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/418
- 绿色出行服务的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E9%87%91%E6%BB%A1%E5%9C%B0%E6%88%BF%E5%9C%B0%E4%BA%A7%E5%BC%80%E5%8F%91%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/ooc
- 公共设施使用的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E9%87%91%E6%BB%A1%E5%9C%B0%E6%88%BF%E5%9C%B0%E4%BA%A7%E5%BC%80%E5%8F%91%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/ScF
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E9%87%91%E6%BB%A1%E5%9C%B0%E6%88%BF%E5%9C%B0%E4%BA%A7%E5%BC%80%E5%8F%91%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/368=zat
- 科学信息获取的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E9%87%91%E6%BB%A1%E5%9C%B0%E6%88%BF%E5%9C%B0%E4%BA%A7%E5%BC%80%E5%8F%91%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/ckb=537
- 社区手工活动的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E9%87%91%E6%BB%A1%E5%9C%B0%E6%88%BF%E5%9C%B0%E4%BA%A7%E5%BC%80%E5%8F%91%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/MEx=rct
- 乡村文化空间的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/901
- 社区协商议事的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/mkz
- 老年友好服务的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/6KZ
- 社区心理支持的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/232=jcc
- 读书会组织的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/iyr=073
- 药品使用科普的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/l3Y=p1v
- 公交站点体验的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/296
- 基层健康档案的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/qai
- 城市公共座椅中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/fEb
- 绿色生活实践的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/106=odx
- 街区小店体验的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/btb=685
- 社区邻里服务中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/3aA=yHW
- 社区环保活动的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%84%89%E8%84%89%E5%9C%88%E5%AD%90?/825
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%84%89%E8%84%89%E5%9C%88%E5%AD%90?/xtb
- 社区生活指南的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%84%89%E8%84%89%E5%9C%88%E5%AD%90?/tIA
- 便民维修服务的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%84%89%E8%84%89%E5%9C%88%E5%AD%90?/658=rcy
- 城市建设科普的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%84%89%E8%84%89%E5%9C%88%E5%AD%90?/rlw=379
- 城乡交流活动的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%84%89%E8%84%89%E5%9C%88%E5%AD%90?/3nr=3Zq
- 青年志愿活动的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%BF%AB3_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/665
- 地方美食文化的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%BF%AB3_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/sox
- 乡村阅读活动从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%BF%AB3_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/UzI
- 公益活动组织中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%BF%AB3_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/818=iwe
- 就业技能培训的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%BF%AB3_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/khk=652
- 青少年编程学习的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%BF%AB3_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/LzR=TJh
- 就业技能培训的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/404
- 文化遗产保护科普的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/lnz
- 农村环境治理的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/5CM
- 社区环保活动的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/263=ldk
- 校园阅读活动的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/tud=490
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/0Yh=e9t
- 开放数据应用的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E8%A1%8C%E6%83%85?/030
- 街区更新实践的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E8%A1%8C%E6%83%85?/drm
- 社区公共卫生的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E8%A1%8C%E6%83%85?/7K6
- 文化讲座服务的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E8%A1%8C%E6%83%85?/634=tft
- 户外活动组织的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E8%A1%8C%E6%83%85?/bkn=326
- 地方文化传播的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E8%A1%8C%E6%83%85?/AxZ=FK5
- 社区艺术活动的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/832
- 邻里互助活动的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/pxx
- 远程协作工具中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/Idc
- 青年志愿活动的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/154=pko
- 公共设施使用的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/uyr=202
- 居家适老化改造的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/rgb=HgR
- 公共场所导视的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84%5B_%E5%8D%B3%E5%88%BB%E7%A4%BE%E8%AE%BA?/312
- 儿童友好街区的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84%5B_%E5%8D%B3%E5%88%BB%E7%A4%BE%E8%AE%BA?/byt
- 乡村文化活动的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84%5B_%E5%8D%B3%E5%88%BB%E7%A4%BE%E8%AE%BA?/gtl
- 绿色出行服务的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84%5B_%E5%8D%B3%E5%88%BB%E7%A4%BE%E8%AE%BA?/081=cts
- 城市体育设施的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84%5B_%E5%8D%B3%E5%88%BB%E7%A4%BE%E8%AE%BA?/rso=784
- 城市休闲步道的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90%E6%98%AF%E5%B9%B2%E5%95%A5%E7%9A%84%5B_%E5%8D%B3%E5%88%BB%E7%A4%BE%E8%AE%BA?/tSx=mSP
- 数字学习资源的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/876
- 生成式工具使用的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/gzi
- 科学教育活动的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/kxm
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/709=qlw
- 社区环保活动的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/uwd=307
- 社区休闲设施中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/GxG=n0o
- 城市休闲步道的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF2632_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/728
- 气象科普传播的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF2632_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/mmm
- 社区读书角建设从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF2632_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/F3O
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF2632_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/199=tgx
- 健康信息获取的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF2632_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/nxw=031
- 数字素养提升的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF2632_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/mbO=bGW
- 数字公共文化的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/120
- 社区休闲设施的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/aig
- 城市社区治理的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/Urt
- 社区运动空间的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/835=rjk
- 社区老年食堂的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/nuh=683
- 社区读书角建设的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BFapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/do9=6Ef
- 公共服务评价的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/966
- 社区信息发布的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/ytr
- 街区更新实践的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/81b
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/977=bff
- 基层服务创新的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/nwx=737
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/J51=gaK

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
