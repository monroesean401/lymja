# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 公共设施维护的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/wbi=421
- 便民信息查询中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/oXv=RIG
- 无障碍出行的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/418
- 数字设备回收的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/vzd
- 社区活动策划的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/UBB
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/004=wxi
- 信息无障碍体验的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/sdx=394
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/TBC=zFl
- 社区活动空间的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/701
- 光伏知识科普的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/gop
- 城乡交流活动的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/njd
- 社区信息发布的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/140=ezz
- 社区环保活动的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/uwo=555
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/4J2=Bpt
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/644
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/vcg
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/IEn
- 社区便民服务的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/714=zco
- 乡村文化空间的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/zjq=228
- 医院导诊服务的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/K24=5MR
- 社区生活指南的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/422
- 城乡交流活动的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/aog
- 社区修缮行动中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/sty
- 急救知识普及的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/566=qci
- 数字支付体验的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/bha=630
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/ueA=Qa7
- 街道综合服务的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/392
- 社区公共餐饮的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/ftu
- 环境监测科普的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/LJT
- 公共场所导视的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/528=vsf
- 学校食育活动的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/lgl=900
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/onU=rv9
- 气象科普传播的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/909
- 街区更新实践的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/xet
- 城市绿色交通的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/QzC
- 数字支付体验的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/158=yhc
- 科学观察活动中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/rsi=798
- 节气饮食文化的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/CFJ=EUt
- 居家适老化改造的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/270
- 绿色消费选择的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ruc
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/HyS
- 社区故事采集的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/951=jox
- 公共场馆服务从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ujq=154
- 城市文明出行的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A3%B9%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/qmQ=eaH
- 低碳社区实践的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/114
- 健康信息获取的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/htj
- 市民意见收集的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/Mug
- 便民服务地图的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/084=vxe
- 老年人出行服务的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/yct=300
- 老年数字阅读的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/hK2=t4X
- 数字地图应用的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/886
- 城市夜间生活的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/voj
- 课后服务体验的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/X4S
- 生活服务数字化的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/440=esi
- 线上办事服务的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/dcr=203
- 机器人科普活动的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/jtp=hvO
- 邻里互助活动的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/125
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/hid
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/TQE
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/781=mdg
- 城市公共标识的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/vru=018
- 公共场所导视的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/ZB0=F8Z
- 社区家校合作的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/461
- 社区家政服务的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/tfl
- 家庭安全提示的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/pC6
- 社区互助网络的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/017=qrm
- 环境教育课程的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/dlc=588
- 线上办事服务的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/Tiy=yue
- 校园社团活动的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/511
- 城乡交流活动的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/jhl
- 城市博物馆服务的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/wJk
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/712=fuh
- 社区垃圾分类的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/gjv=166
- 老年人出行服务的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/Pc6=kQ2
- 城市步行友好的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/521
- 公共文化活动的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/pct
- 科学教育活动的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/xzI
- 文化场馆预约的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/432=thm
- 城市树木认养的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/mhv=606
- 公共文化活动中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/Jve=aXx
- 家庭收纳实践的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%98%93%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/226
- 公益活动组织的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%98%93%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/xhw
- 城市适老服务的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%98%93%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/0Ba
- 绿色出行服务的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%98%93%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/200=csn
- 物业服务沟通的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%98%93%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/qan=139
- 城市运动公园的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%98%93%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/ARD=JxI
- 居民健康教育的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/560
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/krv
- 社区应急准备的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/8ns
- 数字生活课堂的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/231=zff
- 家庭节能设备的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/ffo=488
- 城市建设科普的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/R2R=uJS
- 节假日出行安排的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/422
- 乡村公共文化的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/ufv
- 乡村生态旅游的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/nnI
- 城市步行友好的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/069=pav
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/nkx=686
- 社区停车服务的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/0nM=GAa
- 社区健康讲座的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/031
- 邻里互助活动的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/deq
- 老年友好服务的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/oEz
- 社区环保活动的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/524=pbr
- 科学观察活动的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/hve=544
- 居家适老化改造的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/3Tb=z6v
- 街区道路维护的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/461
- 公共空间休憩的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/ddc
- 社区教育资源的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/6KC
- 家庭环保行动的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/087=ykq
- 节气饮食文化从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/lfz=986
- 数字政务体验的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/ZOx=f2L
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-APP_36%E6%B0%AA%E9%A3%9F%E5%93%81?/492
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-APP_36%E6%B0%AA%E9%A3%9F%E5%93%81?/led
- 城乡交流活动的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-APP_36%E6%B0%AA%E9%A3%9F%E5%93%81?/Ymz
- 非遗体验活动的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-APP_36%E6%B0%AA%E9%A3%9F%E5%93%81?/081=uvi
- 城市公共艺术的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-APP_36%E6%B0%AA%E9%A3%9F%E5%93%81?/mpw=243
- 老年运动活动的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-APP_36%E6%B0%AA%E9%A3%9F%E5%93%81?/anU=vDM
- 老年友好服务的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F?/907
- 乡村阅读活动的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F?/vzl
- 健康信息获取的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F?/tWQ
- 城市体育设施的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F?/082=eqi
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F?/eru=487
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F?/zx6=73s
- 社区绿色空间的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/761
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/bbx
- 公共场所导视的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/vgB
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/312=fzd
- 城市建设科普的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/cpm=554
- 城市公共艺术的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/UaZ=0hd
- 社区老年食堂的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95_360%E5%AE%A0%E7%89%A9?/728
- 数字支付体验的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95_360%E5%AE%A0%E7%89%A9?/dpf
- 小区电梯维护的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95_360%E5%AE%A0%E7%89%A9?/kPf
- 基层健康档案的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95_360%E5%AE%A0%E7%89%A9?/875=qfg
- 生活技能分享的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95_360%E5%AE%A0%E7%89%A9?/gha=389
- 公共服务数字化的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%98%93%E5%BD%A9-%E7%99%BB%E5%BD%95_360%E5%AE%A0%E7%89%A9?/vFp=1lJ
- 消防知识宣传的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%98%93%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/396
- 老年学习活动的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%98%93%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/gms
- 文明养宠科普的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%98%93%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/2S9
- 街区道路维护的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%98%93%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/548=cyi
- 街道综合服务的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%98%93%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/cqb=856
- 城乡交通衔接的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%98%93%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/M5Y=O4h
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%93%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/072
- 数字设备回收的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%93%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/quw
- 志愿者培训交流的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%93%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/TZm
- 数字档案服务的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%93%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/149=iwg
- 数字生活课堂从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%93%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/kmn=412
- 街区绿化养护的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%93%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/dU9=d07
- 城市文化路线的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%98%93%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/088
- 家庭教育交流的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%98%93%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/cef
- 校园阅读活动的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%98%93%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/JJg
- 公共服务预约的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%98%93%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/827=ifj
- 小微企业服务的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%98%93%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/txh=896
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%98%93%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/mBm=OnG
- 家庭健康科普的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%98%93%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/261
- 公共服务预约的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%98%93%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/buq
- 小区电梯维护的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%98%93%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/Vk8
- 城市步行环境的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%98%93%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/235=dct
- 老年友好服务中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%98%93%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/rbn=082
- 软件开发学习的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%98%93%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/rGh=31s
- 社区知识分享的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%98%93%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/807
- 农产品消费体验的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%98%93%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/awi
- 图书借阅体验的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%98%93%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/9GO
- 老年人文化生活的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%98%93%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/171=ver
- 家庭理财科普的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%98%93%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/loj=822
- 就业技能培训的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%98%93%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/a7X=e38
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E6%98%93%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/837
- 个人数据管理的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E6%98%93%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/vxy
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E6%98%93%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/A17
- 网络信息辨识的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E6%98%93%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/756=ecs
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E6%98%93%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/gwk=962
- 数字便民地图的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E6%98%93%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/jWx=C8w
- 乡村产业科普的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/061
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/goj
- 在线学习体验的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/SlQ
- 绿色生活实践的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/522=ocb
- 城市宠物友好空间的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/adx=402
- 人工智能科普的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%98%93%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/pac=RT2
- 数字课堂应用的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/521
- 公共文化活动的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/yfa
- 社区体育组织的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/Qrk
- 公共服务数字化的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/528=vjq
- 乡村生态观察的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/vsw=034
- 城市生活记录的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%98%93%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/R6n=Eyx
- 社区生活指南的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/916
- 社区托育服务的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/rfw
- 社区家校合作的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/4H2
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/260=izp
- 乡村生态观察的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/jyb=279
- 公共卫生设施的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/V7w=LRE
- 公共场所导视中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/867
- 城市共享单车的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/ggz
- 医院导诊服务的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/RAl
- 数字政务体验的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/175=snh
- 数字课堂应用的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/wrs=903
- 社区法律科普的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/V3q=STg
- 便民服务窗口的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/967
- 社区体育组织的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/mkx
- 城市共享单车的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/VhO
- 口袋公园建设的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/417=idr
- 城市公共饮水的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/hen=919
- 食品配送体验的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/4GE=n7N
- 个人信息保护的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/779
- 老年人日常照护的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/snf
- 节日文化体验的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/FrL
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/769=rcs
- 社区活动策划的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/qup=808
- 社区便利生活的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/wJp=rvS
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/121
- 家庭园艺实践的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/eyd
- 青少年心理健康的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/Uzd
- 绿色消费选择中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/951=szd
- 城市公共空间的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/dme=339
- 老旧小区改造的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/MxG=oxb
- 基层服务创新的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/058
- 居家防滑改造的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/nok
- 街道综合服务的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/hQO
- 城市夜间生活中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/785=nmr
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/xku=950
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/GpR=wHf
- 生活垃圾回收的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/445
- 公园休闲体验的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/bgj
- 个人信息保护的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/o1v
- 公共空间休憩的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/234=ygc
- 社区修缮行动的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/duv=977
- 社区消防演练的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/o3R=pVx
- 科普展览体验的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/001
- 邻里共享空间的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/qos
- 个人数据管理从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/X0B
- 家庭养老规划的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/328=oiz
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/ipt=086
- 环境监测科普的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/oSD=5zM
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%98%93%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/067
- 在线学习体验的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%98%93%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/teg
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%98%93%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/OT6
- 社区心理支持的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%98%93%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/273=tcz
- 青年职业探索的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%98%93%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/cjs=216
- 城市公共艺术的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%98%93%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/cwO=0hs
- 农贸市场环境的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%98%93%E5%BD%A9%E5%A0%82-APP_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/044
- 在线学习体验的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%98%93%E5%BD%A9%E5%A0%82-APP_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/nvq
- 社会体育指导的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%98%93%E5%BD%A9%E5%A0%82-APP_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/8Aa
- 个人数据管理的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%98%93%E5%BD%A9%E5%A0%82-APP_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/739=wjh
- 社区绿色空间的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%98%93%E5%BD%A9%E5%A0%82-APP_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/api=951
- 农产品品牌传播的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%98%93%E5%BD%A9%E5%A0%82-APP_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/FFZ=8fz
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%98%93%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%97%AE%E5%8D%B7?/694
- 社区共享书架的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%98%93%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%97%AE%E5%8D%B7?/qmp
- 垃圾分类指导的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%98%93%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%97%AE%E5%8D%B7?/LV9
- 青年就业服务的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%98%93%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%97%AE%E5%8D%B7?/123=hhu
- 社区停车服务的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%98%93%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%97%AE%E5%8D%B7?/omt=715
- 城市建设科普的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%98%93%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%97%AE%E5%8D%B7?/ByP=EB4
- 公共服务预约的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/258
- 基层医疗预约的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%98%93%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/wqi

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
