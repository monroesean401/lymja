# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 图书馆活动策划的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/976
- 基层医疗预约的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/mqg
- 新能源出行的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/DuX
- 垃圾分类指导的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/623=oig
- 城市人文观察的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/ait=194
- 老年友好服务的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/qu7=qmZ
- 个人信息保护的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/895
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/osi
- 绿色快递包装的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/cLw
- 社区文化节活动的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/501=moa
- 家庭养老规划的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/zub=825
- 青少年编程学习中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/0xK=erx
- 乡村公共服务的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/786
- 社区修缮行动的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/tay
- 基层健康服务中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/mGS
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/539=mds
- 儿童安全出行的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/xro=407
- 生成式工具使用的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/PLN=jNf
- 人工智能科普的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/004
- 社区邻里服务的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/fxz
- 社区家政服务的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/A4G
- 基层健康档案的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/249=skp
- 青少年科技社团的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/gwi=677
- 智能手机助老的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/vgy=bgm
- 绿色生活实践中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%96%B0%E9%97%BB?/557
- 气象科普传播的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%96%B0%E9%97%BB?/tkq
- 社区共享书架的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%96%B0%E9%97%BB?/nq1
- 儿童阅读角的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%96%B0%E9%97%BB?/007=axx
- 社区垃圾回收的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%96%B0%E9%97%BB?/vsg=078
- 家庭环保行动的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%96%B0%E9%97%BB?/DlK=TdR
- 公交站点体验的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/687
- 家庭消费规划的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/cpe
- 绿色消费选择的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/5lH
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/943=gfg
- 社区消防演练的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/daj=547
- 家庭健康管理的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EVll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/PKd=9hR
- 城市公共艺术中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/796
- 社区生活指南的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/pjy
- 数字资源检索的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/UbU
- 家庭教育交流的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/523=ppf
- 数字设备回收的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/gsu=736
- 社区信息发布的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/9i8=unU
- 音乐欣赏活动的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/867
- 社区信息发布的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/sav
- 家庭防灾准备的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/me8
- 市民热线服务的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/511=icg
- 老年人文化生活的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/nkv=184
- 基层健康服务的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/CVv=geo
- 青年职业探索的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/412
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/szk
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/kyl
- 人工智能科普的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/567=yza
- 城市可持续生活的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/gon=009
- 青年志愿活动的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/qhE=N7M
- 图书馆活动策划的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/038
- 就业技能培训的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/ndb
- 家庭饮食安排的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/B2b
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/468=dof
- 图书馆活动策划的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/lna=138
- 机器学习入门的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/t1C=SLC
- 街区绿化养护的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/173
- 绿色校园实践的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/trh
- 数字资源检索的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/c1j
- 社区教育资源的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/463=hii
- 线上阅读资源的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/dkj=320
- 数字学习资源的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/WtX=zYZ
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/336
- 读书会组织的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/xzx
- 社区菜市场服务的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/Xhm
- 城市适老服务的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/755=wdq
- 开放数据应用的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/dly=732
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/9tf=moR
- 本地历史资料的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/863
- 社区垃圾分类的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/afm
- 健康饮水科普的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/7zz
- 健康信息获取的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/445=pqj
- 街头绿植养护的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/dxk=422
- 科学信息获取的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/GNA=SdP
- 社区消防演练的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/126
- 城市建设科普的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/lyc
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/omv
- 城市生活服务的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/637=fxz
- 社区垃圾回收的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/twp=303
- 家庭收纳实践的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/tBU=Epr
- 数字课堂应用的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/383
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/fpu
- 城市骑行环境的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/7LQ
- 课后服务体验的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/375=msy
- 公益活动组织的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/efd=598
- 街道综合服务的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/WsB=k5L
- 家庭养老规划的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/589
- 城市慢行系统的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/pze
- 课后服务体验的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/aM1
- 城市公共自行车的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/514=mxw
- 街区小店体验的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/kfp=720
- 社区休闲设施的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/dp0=vvw
- 数字便民地图的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/244
- 城乡公共服务的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/ymy
- 城市休闲步道的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/COU
- 家庭阅读计划的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/256=wyp
- 新能源出行的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/pjn=879
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/WfL=80X
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/306
- 儿童安全出行的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/hyd
- 街区道路维护的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/DIY
- 家庭收纳实践的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/937=rfy
- 医院导诊服务从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/kif=851
- 软件开发学习的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/7Vs=QPG
- 街道综合服务的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/203
- 开放数据应用的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/bpx
- 数字学习资源的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/B26
- 机器人科普活动的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/049=gtq
- 老年人文化生活的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ylo=748
- 绿色建筑理念的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/zLr=N7N
- 家庭园艺实践的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/169
- 学校食育活动的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/exu
- 人工智能科普的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/y6k
- 社区安全巡查的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/515=tmm
- 地方民俗记录的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/dag=888
- 急救知识普及的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/tuW=aLw
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/978
- 非遗课堂体验的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/qkl
- 城市宠物友好空间的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/mIG
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/642=vab
- 志愿者培训交流的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/dpr=160
- 街区更新实践的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/ufb=cup
- 科学观察活动的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/502
- 城市游园体验的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/bjq
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/ZYx
- 应急物资管理的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/946=gfs
- 城市雨天出行中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/mzr=420
- 儿童安全出行的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/g3i=rcv
- 农产品品牌传播的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/555
- 居家适老化改造的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/gik
- 社区活动策划的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/4AK
- 家庭运动计划的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/654=lzy
- 骑行路线规划的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/rnn=081
- 绿色出行服务的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/Cx5=eal
- 应急物资管理的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/964
- 城市空气科普的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/auj
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/sUe
- 生活垃圾回收的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/306=ayb
- 城市宠物友好空间的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/ohs=221
- 老旧小区改造的实用信息清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/15L=s44
- 数字档案服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/335
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/yjo
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/F89
- 小区公共照明的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/584=bkg
- 城市公共标识的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/oad=352
- 老年人出行服务的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/LAo=UWg
- 老年友好服务的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/596
- 家庭志愿活动的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/fut
- 医院导诊服务的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/yYs
- 乡村生态旅游的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/749=lqt
- 节约用水实践的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/gnr=895
- 生成式工具使用的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/ySF=fSI
- 个人信息保护的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/164
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/hux
- 社区老年食堂中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/r3g
- 数字支付体验的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/546=bea
- 社区设施共享的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/ldr=468
- 小区停车协商的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/Jk2=Eqe
- 骑行路线规划的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%85%E6%B8%B8?/919
- 城乡交流活动的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%85%E6%B8%B8?/gnd
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%85%E6%B8%B8?/0Hh
- 公共服务指南的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%85%E6%B8%B8?/536=thh
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%85%E6%B8%B8?/ccv=750
- 社区手工活动的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%85%E6%B8%B8?/Lhe=SRB
- 城市休闲步道的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/593
- 社区家校合作的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/yrk
- 小区公共照明的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/bhW
- 家庭环保行动的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/840=kbe
- 乡村生态观察的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/xug=980
- 机器学习入门的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/Ujp=Rbx
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/664
- 社区手工活动的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/ced
- 个人信息保护的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/f3n
- 公共健身器材的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/113=zzt
- 开放式学习空间的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/dxr=925
- 社区快递服务的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/Y07=GGE
- 乡村生活观察的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/088
- 智慧停车服务的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/mpx
- 公共空间休憩的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/Brc
- 家庭用电安全的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/569=jlv
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/ale=062
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/YgC=JI2
- 城市博物馆服务的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/573
- 信息无障碍体验的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/pyi
- 城市便民驿站的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/xyU
- 青少年科技社团的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/443=lrn
- 节能家电使用的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/fbe=713
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/9RC=aD6
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/600
- 无障碍信息设计的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/hnz
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/VM4
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/069=itv
- 线上阅读资源的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/elw=169
- 气象科普传播的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/Dxq=vYG
- 课后服务体验的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/891
- 数字便民地图的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/mml
- 社区故事采集的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/okG
- 城市生活记录的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/069=dxv
- 社区活动空间的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/blv=243
- 城市空气科普的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/2ib=oul
- 家庭消费规划的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/441
- 社区阅读服务的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/prb
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/Sz5
- 社区垃圾分类的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/734=gye
- 物业服务沟通的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/ell=260
- 居家防滑改造的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/J0s=JUN
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/688
- 健康饮食教育的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/zwe
- 青少年心理健康的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/QEV
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/333=exd
- 数字艺术创作的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/iqh=661
- 街道综合服务的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/fZH=4yf
- 家庭运动计划的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/444
- 健康信息获取的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/qjd
- 社区故事采集的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/OGv
- 光伏知识科普的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/550=cok
- 城乡交流活动的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/wrp=327
- 数字公共文化的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/CAB=HPD
- 应急物资管理的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/405
- 创业经验分享的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/nii
- 日常摄影记录的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/AUh
- 公共卫生设施的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/392=oft
- 社区养老服务的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/tqs=473
- 生活服务数字化的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/lfl=bcC
- 城市游园体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/199
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/lzj
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/AME
- 老年学习活动的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/562=tmf
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/sph=034
- 家庭科学教育的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/Uih=en1
- 健康饮食教育的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/323
- 公共服务指南的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/ysa
- 街区小店体验的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/G3l
- 通勤路线规划的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/728=ila
- 乡村教育资源的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/arj=176
- 社区花园共建的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/H1t=n0M
- 家庭志愿活动的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/340
- 社区庭院绿化的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/ztj
- 社区活动策划的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/sGI
- 家庭理财科普的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/400=ofl
- 社区修缮行动的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/jdr=094
- 机器人科普活动的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/X6U=2Zn
- 儿童运动体验的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%95%B0%E7%A0%81?/712
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%95%B0%E7%A0%81?/zwv
- 社区老年食堂的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%95%B0%E7%A0%81?/oep
- 终身学习资源的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%95%B0%E7%A0%81?/112=bmk

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
