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

- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%85%8D%E8%B4%B9%E9%80%8138%E5%BD%A9%E9%87%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/850
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%85%8D%E8%B4%B9%E9%80%8138%E5%BD%A9%E9%87%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/uff
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%85%8D%E8%B4%B9%E9%80%8138%E5%BD%A9%E9%87%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/EMb
- 城市步行环境的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%85%8D%E8%B4%B9%E9%80%8138%E5%BD%A9%E9%87%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/821=mwa
- 本地消费场景的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%85%8D%E8%B4%B9%E9%80%8138%E5%BD%A9%E9%87%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/gbj=648
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%85%8D%E8%B4%B9%E9%80%8138%E5%BD%A9%E9%87%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/8DZ=G25
- 绿色生活实践的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/138
- 儿童户外活动的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/dtr
- 地方美食文化中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/Alr
- 家庭节能实践中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/162=cye
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/tfl=212
- 家庭网络使用的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/LYM=J3N
- 本地历史资料的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%855%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/440
- 开放式学习空间的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%855%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/you
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%855%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/KIy
- 数字艺术创作中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%855%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/821=wou
- 数字档案服务的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%855%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/eiq=576
- 食品配送体验的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%855%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/FzK=kNm
- 儿童阅读角的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/778
- 课后服务体验的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/von
- 城市公共空间的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/O55
- 社区手工活动的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/117=vli
- 街区小店体验中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/wmv=114
- 家庭环保行动的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/Vcq=8T0
- 青年职业探索的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/907
- 家庭健康管理的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/ral
- 数字地图应用的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/RsM
- 儿童运动体验的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/450=wcg
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/fvt=480
- 生成式工具使用的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/XsP=89e
- 老年智能设备的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%B9%B8%E8%BF%90%E5%AE%98%E7%BD%91_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/625
- 健康饮食教育的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%B9%B8%E8%BF%90%E5%AE%98%E7%BD%91_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/epp
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%B9%B8%E8%BF%90%E5%AE%98%E7%BD%91_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/jS7
- 机器学习入门的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%B9%B8%E8%BF%90%E5%AE%98%E7%BD%91_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/893=tui
- 乡村文化空间的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%B9%B8%E8%BF%90%E5%AE%98%E7%BD%91_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/mpr=142
- 农业科普体验的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%B9%B8%E8%BF%90%E5%AE%98%E7%BD%91_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/U1B=BRN
- 创业经验分享的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/177
- 社区交通安全的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/yfq
- 节日文化体验的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/gwC
- 城市微更新实践的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/895=txt
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/vyl=587
- 社区信息发布的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/fFr=Lld
- 城市步行环境的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BDapp%E9%80%8138%E5%85%83%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/354
- 儿童运动体验的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BDapp%E9%80%8138%E5%85%83%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/bzq
- 开放式学习空间的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BDapp%E9%80%8138%E5%85%83%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/kju
- 科学信息获取的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BDapp%E9%80%8138%E5%85%83%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/501=bxh
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BDapp%E9%80%8138%E5%85%83%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/jfs=776
- 城市夜间生活的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BDapp%E9%80%8138%E5%85%83%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/EaY=Tge
- 社区家政服务的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/021
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/hjm
- 课后服务体验的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/sXk
- 公共空间休憩的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/519=mhc
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/chz=483
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/tTK=tQA
- 学校食育活动的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B8%E8%BF%90%E5%BF%AB3_36%E6%B0%AA%E7%90%86%E8%B4%A2?/174
- 在线教育体验的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B8%E8%BF%90%E5%BF%AB3_36%E6%B0%AA%E7%90%86%E8%B4%A2?/wqp
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B8%E8%BF%90%E5%BF%AB3_36%E6%B0%AA%E7%90%86%E8%B4%A2?/wWQ
- 公共服务沟通的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B8%E8%BF%90%E5%BF%AB3_36%E6%B0%AA%E7%90%86%E8%B4%A2?/857=zns
- 全民健身活动的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B8%E8%BF%90%E5%BF%AB3_36%E6%B0%AA%E7%90%86%E8%B4%A2?/klt=391
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B8%E8%BF%90%E5%BF%AB3_36%E6%B0%AA%E7%90%86%E8%B4%A2?/iRt=S0y
- 社会体育指导的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%BA%91%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/243
- 就业技能培训的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%BA%91%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/hbn
- 信息无障碍体验的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%BA%91%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/Vr3
- 城市微更新实践的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%BA%91%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/473=mrq
- 城市适老服务的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%BA%91%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/bvv=298
- 社区老年食堂的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%BA%91%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/PaG=7xX
- 社区宠物管理的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BF%A1%E5%8F%91%E5%9B%BD%E9%99%85%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%BE%97%E7%89%A9%E6%BC%AB%E8%AF%84?/723
- 儿童友好空间的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BF%A1%E5%8F%91%E5%9B%BD%E9%99%85%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%BE%97%E7%89%A9%E6%BC%AB%E8%AF%84?/yjk
- 农村环境治理的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BF%A1%E5%8F%91%E5%9B%BD%E9%99%85%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%BE%97%E7%89%A9%E6%BC%AB%E8%AF%84?/TSh
- 社区学习活动的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BF%A1%E5%8F%91%E5%9B%BD%E9%99%85%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%BE%97%E7%89%A9%E6%BC%AB%E8%AF%84?/960=kxp
- 邻里共享空间的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BF%A1%E5%8F%91%E5%9B%BD%E9%99%85%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%BE%97%E7%89%A9%E6%BC%AB%E8%AF%84?/afk=125
- 地方民俗记录的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BF%A1%E5%8F%91%E5%9B%BD%E9%99%85%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%BE%97%E7%89%A9%E6%BC%AB%E8%AF%84?/2o0=VxJ
- 节假日出行安排的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/720
- 灵活就业交流的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/kbp
- 社区垃圾回收的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/ctG
- 城市慢行系统的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/121=tzq
- 市民意见收集的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/wnl=931
- 科学教育活动从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/rH2=rCn
- 儿童友好空间的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E5%93%AA%E9%87%8C%E7%9A%84%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/476
- 数字支付体验的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E5%93%AA%E9%87%8C%E7%9A%84%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/plc
- 数据分析入门的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E5%93%AA%E9%87%8C%E7%9A%84%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/Ega
- 食品安全科普的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E5%93%AA%E9%87%8C%E7%9A%84%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/367=izo
- 公益活动组织的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E5%93%AA%E9%87%8C%E7%9A%84%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/xum=927
- 城市绿道建设的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E5%93%AA%E9%87%8C%E7%9A%84%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/YN3=v6h
- 公共文化活动的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_360%E6%8A%95%E7%A8%BF?/339
- 社区应急准备的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_360%E6%8A%95%E7%A8%BF?/jgu
- 城市夜间照明的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_360%E6%8A%95%E7%A8%BF?/ynj
- 科学观察活动的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_360%E6%8A%95%E7%A8%BF?/665=xzc
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_360%E6%8A%95%E7%A8%BF?/opi=797
- 城市农夫市集的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_360%E6%8A%95%E7%A8%BF?/Wp9=1lI
- 青少年户外教育的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%99%BE%E7%A7%91?/899
- 家庭消费规划的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%99%BE%E7%A7%91?/jxj
- 街区绿化养护的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%99%BE%E7%A7%91?/2o6
- 家庭照护支持的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%99%BE%E7%A7%91?/896=zcj
- 青年志愿活动的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%99%BE%E7%A7%91?/fik=165
- 电子商务服务的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%99%BE%E7%A7%91?/cWx=Iz0
- 公交无障碍服务的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%A4%AE%E8%A7%86%E7%9B%98%E7%82%B9?/542
- 家庭急救准备的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%A4%AE%E8%A7%86%E7%9B%98%E7%82%B9?/jux
- 社区法律科普的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%A4%AE%E8%A7%86%E7%9B%98%E7%82%B9?/C9M
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%A4%AE%E8%A7%86%E7%9B%98%E7%82%B9?/377=snq
- 青少年科技社团的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%A4%AE%E8%A7%86%E7%9B%98%E7%82%B9?/iel=755
- 亲子科普活动的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%A4%AE%E8%A7%86%E7%9B%98%E7%82%B9?/sIb=cq4
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/226
- 新能源出行的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/dgt
- 本地旅行体验的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/9pc
- 地方旅游导览的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/880=gvz
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/lqs=281
- 户外活动组织的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/6sl=tEn
- 家庭节能实践的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E4%B8%AD%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/373
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E4%B8%AD%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/gpn
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E4%B8%AD%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/gEW
- 社区交通安全的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E4%B8%AD%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/620=cxf
- 城市微更新实践的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E4%B8%AD%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/vol=607
- 个人数据管理的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E4%B8%AD%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/Koc=goj
- 城市建设科普的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/710
- 家庭节能实践的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/ogo
- 数字政务体验的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/8dJ
- 城市文明出行的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/510=mel
- 街区道路维护的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/vgq=198
- 家庭收纳实践的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/Abd=wIC
- 消防知识宣传中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%93%AA%E4%B8%AA%E5%A5%BD%E8%B5%A2%E9%92%B1_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/187
- 志愿者培训交流的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%93%AA%E4%B8%AA%E5%A5%BD%E8%B5%A2%E9%92%B1_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/npd
- 乡村公共服务的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%93%AA%E4%B8%AA%E5%A5%BD%E8%B5%A2%E9%92%B1_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/uZ6
- 便民服务地图的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%93%AA%E4%B8%AA%E5%A5%BD%E8%B5%A2%E9%92%B1_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/982=iri
- 通勤路线规划的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%93%AA%E4%B8%AA%E5%A5%BD%E8%B5%A2%E9%92%B1_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/iqj=513
- 智能手机助老的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%93%AA%E4%B8%AA%E5%A5%BD%E8%B5%A2%E9%92%B1_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/bso=vqT
- 乡村生态旅游的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_u9%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/752
- 租房信息服务的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_u9%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/per
- 口袋公园建设的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_u9%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/elP
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_u9%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/720=luw
- 城市便民驿站中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_u9%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/plt=202
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_u9%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/2dY=e4Q
- 健康步道使用的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/071
- 社区休闲设施的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/yik
- 家庭饮食安排的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/mHz
- 公共空间导览的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/744=dgh
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/pul=260
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/wUk=4GS
- 科学信息获取的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%905%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/037
- 社区手工活动的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%905%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/aio
- 社区故事采集的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%905%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/29e
- 校园节能行动的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%905%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/506=wda
- 远程协作工具的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%905%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/ddn=031
- 生成式工具使用的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%905%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/mpO=OG9
- 数字创意课程的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/449
- 家庭志愿活动的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/jbc
- 乡村阅读活动的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/2vK
- 家庭阅读计划的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/264=msh
- 城市文明实践的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/dqo=233
- 绿色消费选择的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/oY1=wqS
- 电动汽车充电的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/534
- 市民意见收集的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/non
- 公共文化活动的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/u5G
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/853=ndx
- 老年智能设备的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/rdf=341
- 社区设施共享的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/twi=tX1
- 老年人出行服务的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/982
- 家庭网络使用的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/lun
- 绿色消费选择中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/cj3
- 在线教育体验的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/529=oul
- 公共空间安全的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/ode=931
- 地方美食文化的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/Chg=NPe
- 家庭健康科普的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84__%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/033
- 公共设施使用的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84__%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/ogt
- 城乡交通衔接的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84__%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/ECu
- 地方旅游导览的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84__%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/340=tsw
- 本地旅行体验的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84__%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/zxz=691
- 软件开发学习的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84__%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/Ocq=BXQ
- 社区文化节活动的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_36%E6%B0%AA%E7%9B%98%E7%82%B9?/135
- 社区运动空间的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_36%E6%B0%AA%E7%9B%98%E7%82%B9?/ufs
- 生活技能分享的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_36%E6%B0%AA%E7%9B%98%E7%82%B9?/NPK
- 应急物资管理的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_36%E6%B0%AA%E7%9B%98%E7%82%B9?/548=sma
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_36%E6%B0%AA%E7%9B%98%E7%82%B9?/elu=991
- 家庭安全提示的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_36%E6%B0%AA%E7%9B%98%E7%82%B9?/8U4=yQ3
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%9D%E9%99%A9?/722
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%9D%E9%99%A9?/kvy
- 城市基础设施的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%9D%E9%99%A9?/cd6
- 智能手机助老的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%9D%E9%99%A9?/577=qfd
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%9D%E9%99%A9?/geh=109
- 社区艺术活动的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%BF%9D%E9%99%A9?/osD=H1u
- 城市地名文化的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/725
- 城市夜间照明的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/zgo
- 城市骑行环境的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/gSW
- 数据分析入门的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/994=pym
- 农产品消费体验的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/qhm=577
- 学校体育活动的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/yoU=joN
- 地方文化传播的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/275
- 图书馆数字服务的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/yyb
- 读书会组织的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/Zhp
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/663=div
- 新能源出行的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/inc=891
- 城市农夫市集的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/9U8=ZFd
- 城市生活记录的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/214
- 公共设施维护的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/mgr
- 家庭节能实践的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/UFa
- 个人时间管理的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/778=bzw
- 城市公共座椅的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/faw=560
- 社区运动空间中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/ZoE=FSQ
- 节日文化体验的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%80%9F%E8%A7%88?/153
- 亲子阅读活动的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%80%9F%E8%A7%88?/moj
- 乡村文化空间的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%80%9F%E8%A7%88?/wxp
- 小区停车协商的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%80%9F%E8%A7%88?/871=kym
- 家庭养老规划的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%80%9F%E8%A7%88?/xpz=396
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%80%9F%E8%A7%88?/yT4=qaI
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/930
- 远程协作工具的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/rpu
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/4RS
- 图书馆活动策划的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/987=bxh
- 城市公共座椅的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/olu=322
- 街区绿化养护中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/mCT=280
- 安全出行教育的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/201
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/bbq
- 城市空气科普的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/l7D
- 绿色建筑理念的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/960=buk
- 课后服务体验的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/zzo=727
- 生成式工具使用的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/Nrx=3Ae
- 社区体育组织的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90app_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/296
- 乡村电商实践从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90app_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/kou
- 数字资源检索中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90app_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/7SL
- 公共场所导视的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90app_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/961=ubq
- 创业经验分享的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90app_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/tku=179
- 城乡交流活动的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90app_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/tec=ucK
- 城市公共自行车的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/834
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/oqc
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/PU8
- 数字政务体验的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/799=iyy
- 老年智能设备的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/jkn=346
- 安全出行教育的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/CSp=vq4
- 农贸市场环境的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E7%BD%91%E7%AB%99%E6%B1%87%E6%80%BB_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/175
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E7%BD%91%E7%AB%99%E6%B1%87%E6%80%BB_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/pvs
- 公共设施使用的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E7%BD%91%E7%AB%99%E6%B1%87%E6%80%BB_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/yBE
- 消防知识宣传的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E7%BD%91%E7%AB%99%E6%B1%87%E6%80%BB_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/318=zgg
- 全民健身活动的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E7%BD%91%E7%AB%99%E6%B1%87%E6%80%BB_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/jth=316
- 地方戏曲体验的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E7%BD%91%E7%AB%99%E6%B1%87%E6%80%BB_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/nKa=Mmm
- 社区慢性病防控的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8E%BF%E5%9F%9F?/784
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8E%BF%E5%9F%9F?/mnr
- 社区心理支持的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8E%BF%E5%9F%9F?/8Mc
- 户外活动组织的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8E%BF%E5%9F%9F?/050=wko
- 城市应急广播的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8E%BF%E5%9F%9F?/upi=331
- 老旧小区改造的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8E%BF%E5%9F%9F?/1ce=Qlp
- 校园安全教育的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/735
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/bxt
- 便民维修服务的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/FV6
- 老年智能设备的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/240=elt
- 家庭节能设备的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/ucr=346
- 城市水环境观察的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/Uxk=w6f
- 城市休闲步道的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/667
- 绿色校园实践的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/yik
- 老年人出行服务的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/q29
- 城市体育设施的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/820=qax

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
