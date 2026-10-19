# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 家庭陪伴活动的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/486
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/ihn
- 社区信息发布的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/lNz
- 本地旅行体验的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/597=oae
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/gsc=795
- 社区养老服务的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/SHm=eeE
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/681
- 运动安全知识的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/hby
- 生活服务数字化的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/sgl
- 数字创作工具的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/827=wwv
- 家庭安全提示的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/obn=887
- 家庭运动计划的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/duL=Yts
- 城市建设科普的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9500%E5%A8%B1%E4%B9%90-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BF%E8%B0%88?/111
- 节气饮食文化的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9500%E5%A8%B1%E4%B9%90-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BF%E8%B0%88?/moo
- 社区文化传播的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9500%E5%A8%B1%E4%B9%90-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BF%E8%B0%88?/1BV
- 家庭收纳实践的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9500%E5%A8%B1%E4%B9%90-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BF%E8%B0%88?/808=uay
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9500%E5%A8%B1%E4%B9%90-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BF%E8%B0%88?/hri=591
- 社区家政服务的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9500%E5%A8%B1%E4%B9%90-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BF%E8%B0%88?/dG8=0U7
- 基层健康服务的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9500%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%95%85%E6%B8%B8?/746
- 城市生活记录的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9500%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%95%85%E6%B8%B8?/apu
- 数字学习资源的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9500%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%95%85%E6%B8%B8?/HeP
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9500%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%95%85%E6%B8%B8?/499=oke
- 青少年编程学习的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9500%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%95%85%E6%B8%B8?/zmu=620
- 城市公共饮水的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9500%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%95%85%E6%B8%B8?/1pA=nUJ
- 老年人出行服务的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/833
- 社区活动空间的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/zvs
- 社会体育指导的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/z1b
- 数字生活课堂的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/604=blq
- 公交站点体验的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/too=669
- 农村环境治理的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/ylK=0qL
- 城市夜间照明的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/086
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/yse
- 家庭运动计划的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/Rxz
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/580=ocn
- 城市住房服务的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/jwj=407
- 社区消防演练的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/chh=6Kt
- 学校食育活动的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/141
- 城市农夫市集的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/bge
- 城市噪声观察的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/sED
- 开放式学习空间的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/206=ppr
- 节能家电使用的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/mqi=711
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/9uW=wuD
- 便民服务地图的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/783
- 农产品消费体验的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/zzp
- 数字创意课程的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/Hzx
- 信息无障碍体验的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/791=fjc
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/jmb=985
- 家庭照护支持的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/Mvz=Eip
- 家庭运动计划的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/599
- 社区设施共享的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/kwt
- 社区公共卫生的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/SU7
- 乡村生态旅游的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/285=dxs
- 社区科普课堂的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/szt=601
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/I9A=0NE
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/011
- 城市应急科普的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/auh
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/ycU
- 公共服务沟通的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/412=aox
- 家庭环保行动的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/ghm=935
- 社区养老服务的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/wo1=f4E
- 健康信息获取的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9500%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/278
- 职业技能学习的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9500%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/deb
- 智慧城市体验的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9500%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/jiH
- 社区老年食堂的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9500%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/846=qzi
- 便民信息查询的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9500%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/ngs=308
- 绿色消费选择的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9500%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/2RZ=p2f
- 公共空间照明的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/007
- 非遗课堂体验的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/ubk
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/IWq
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/148=ihr
- 地方美食文化的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/kfi=895
- 城市绿道建设的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/6Hm=k5t
- 智能家居应用的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/075
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/bob
- 城市公共标识的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/5ZV
- 社区活动空间的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/409=gwc
- 乡村公共阅读的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/xww=750
- 城市绿道建设的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%BD%A9500%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/vFH=Tqk
- 传统节日科普的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/693
- 家庭网络使用的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/qdj
- 无障碍出行的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/11w
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/363=bjm
- 无障碍信息设计的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/apf=598
- 老年友好服务中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/dRo=bs2
- 地方美食文化的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/997
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/eub
- 城市生活服务的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/Qyy
- 家庭健康管理的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/632=qem
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/vfi=407
- 个人信息保护的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/XS5=og4
- 数字档案服务的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/042
- 社区应急准备的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/djp
- 社区知识分享的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/HMQ
- 乡村公共阅读的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/528=tko
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/ove=798
- 城市生活服务的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/5fu=lR0
- 新能源出行的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/975
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/ffo
- 智慧城市体验的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/CAB
- 信息无障碍体验的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/566=fmh
- 小区公共照明的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/tko=101
- 城市树木认养的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/kkZ=Y3y
- 小区停车协商的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/974
- 数字设备回收的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/nzb
- 机器学习入门的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/T5Q
- 乡村阅读空间从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/248=vvl
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/gnb=683
- 乡村产业科普的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/tYS=bSf
- 城市骑行环境的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/440
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/jyf
- 无障碍出行的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/y5s
- 社区庭院绿化的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/593=vvu
- 数字设备回收的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/dux=322
- 公共服务咨询的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/Ms3=YbS
- 非遗课堂体验的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/495
- 居家防滑改造的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/vay
- 青少年科普实践的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/f1k
- 社会体育指导的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/959=mjv
- 科普展览体验的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/iuy=122
- 社区健康讲座的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/j5V=lsL
- 基层健康档案的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/505
- 居民健康教育的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/etk
- 街区小店体验的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/blV
- 青少年编程学习中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/545=jyn
- 家庭节能设备的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/dpj=781
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/UIm=ujY
- 城市共享单车的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/389
- 课后服务体验的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/edg
- 城市运动公园的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/Wts
- 青年职业探索的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/167=oel
- 家庭养老规划的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/myk=734
- 节能家电使用的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/G6K=eKq
- 街区小店体验的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/853
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/rfd
- 旧物循环利用的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/dr6
- 城市住房服务的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/854=mzi
- 社区儿童活动的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/gne=739
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/l4W=lg3
- 新能源知识普及的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/769
- 老年数字阅读的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/bov
- 社区知识分享的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/jIf
- 城市地名文化的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/370=fap
- 社区快递服务的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/xtq=176
- 儿童友好空间的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/lZC=9hr
- 校园节能行动的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/548
- 儿童运动体验的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/fmb
- 机器学习入门的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/6bI
- 社区知识分享的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/523=vso
- 科普展览体验的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/bdo=745
- 智能手机助老的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/EJ1=cej
- 老年友好服务的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/263
- 电子商务服务的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/cjw
- 乡村教育资源的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/2tC
- 社区便民服务的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/518=rqs
- 户外活动组织的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/gzy=090
- 社区手工活动的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/UT0=ezz
- 社区读书角建设的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BD%93%E8%82%B2?/355
- 传统手工艺体验的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BD%93%E8%82%B2?/ivc
- 乡村产业科普的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BD%93%E8%82%B2?/ENr
- 图书馆数字服务的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BD%93%E8%82%B2?/255=szv
- 青年志愿活动的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BD%93%E8%82%B2?/nnu=844
- 基层健康档案的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BD%93%E8%82%B2?/Kzl=yYa
- 公共卫生设施中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/894
- 儿童友好街区的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/liu
- 城市文明出行的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/qo0
- 公益活动组织的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/574=xzl
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/qio=190
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/Dga=x4I
- 就业技能培训的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/431
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/are
- 城市游园体验的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/lsv
- 城市社区治理的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/489=mae
- 开放数据应用的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/xuw=677
- 城市生活记录的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/SRJ=aKC
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/926
- 家庭照护支持的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/jit
- 乡村阅读空间的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/2pB
- 光伏知识科普中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/004=ruo
- 家庭节能实践的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/qvl=111
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/zZq=ZBm
- 公共服务预约的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/958
- 科普展览体验的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/wmt
- 低碳社区实践中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/mFY
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/520=fcw
- 公共卫生宣传的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/uue=660
- 青年职业探索的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/jd2=Swr
- 居民健康教育的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/104
- 儿童安全出行的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/azk
- 数字创意课程的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/krA
- 地方文化传播的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/611=wir
- 节日文化体验的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/wel=595
- 学校食育活动的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/Pti=h7C
- 家庭网络使用的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/779
- 青少年科普实践的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/bsz
- 数据分析入门的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/gEb
- 儿童户外活动的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/375=byl
- 劳动教育实践的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/vfr=237
- 数字生活课堂的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/z9T=hq3
- 街区道路维护的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/595
- 科技馆参观体验的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/glh
- 家庭环保习惯的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/P6y
- 个人信息保护的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/661=yfp
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/lfz=789
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/NnA=Plh
- 公共场馆服务的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E9%97%AE%E5%8D%B7?/029
- 儿童友好空间的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E9%97%AE%E5%8D%B7?/wbq
- 城市水环境观察的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E9%97%AE%E5%8D%B7?/iEA
- 学校体育活动的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E9%97%AE%E5%8D%B7?/561=urm
- 城市雨天出行的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E9%97%AE%E5%8D%B7?/sgw=355
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E9%97%AE%E5%8D%B7?/M4O=NSU
- 便民服务地图的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/258
- 社区垃圾回收的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/pps
- 食品配送体验的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/axV
- 机器人科普活动有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/763=dhc
- 开源技术交流的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/ghh=714
- 社区手工活动的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/i4O=3C2
- 公共场馆服务的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%BB%84%E8%89%B2500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9E%AD%E6%9C%9B?/150
- 农贸市场环境的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%BB%84%E8%89%B2500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9E%AD%E6%9C%9B?/orv
- 低碳社区实践的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%BB%84%E8%89%B2500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9E%AD%E6%9C%9B?/Ke8
- 生活服务数字化的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%BB%84%E8%89%B2500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9E%AD%E6%9C%9B?/843=lxi
- 青少年户外教育的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%BB%84%E8%89%B2500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9E%AD%E6%9C%9B?/til=059
- 老年运动活动的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%BB%84%E8%89%B2500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9E%AD%E6%9C%9B?/X0m=95M
- 个人数据管理的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/367
- 远程协作工具的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/xbn
- 城市体育设施中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/qJf
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/295=xyp
- 社区活动策划的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/hfb=200
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/kmE=bTx
- 城市生活服务的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/138
- 社区运动空间的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/koq
- 户外活动组织的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/RGo
- 灵活就业交流的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/677=xcx
- 家庭阅读计划的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/sos=018
- 社区快递服务的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/PRX=u5s
- 环境监测科普的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/316
- 节气饮食文化的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/jbz
- 城市水环境观察的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/06H
- 图书馆亲子空间从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/598=zcy
- 个人信息保护中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/ujn=856
- 传统节日科普的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/5dS=136
- 公共空间休憩的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/069
- 线上办事服务的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/syj
- 社区家政服务的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/7Va
- 健康饮食教育中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/194=zrl
- 城市步行环境的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/nny=774
- 家庭照护支持的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/GbX=qim
- 社区庭院绿化的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/969
- 便民维修服务的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/oap
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/Jk7
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/155=fql

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
