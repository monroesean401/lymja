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

- 公共空间照明中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/clz=523
- 文化场馆预约的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/Fga=hU8
- 家庭收纳实践的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%90%97%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/957
- 数字创意课程的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%90%97%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/smn
- 开放式学习空间的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%90%97%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/Zso
- 城市建设科普的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%90%97%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/377=qss
- 公共空间安全的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%90%97%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/ahs=335
- 食品安全科普的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%90%97%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/qJ9=rNb
- 城市人文观察的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/375
- 家庭照护支持的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/dmh
- 个人数据管理的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/CTE
- 青年志愿活动的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/448=hfc
- 居民健康教育的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/ajr=049
- 本地历史资料的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/sjw=AyA
- 社区公共卫生的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%9B%A2%E9%98%9F_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/866
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%9B%A2%E9%98%9F_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/kob
- 健康信息获取的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%9B%A2%E9%98%9F_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/J7u
- 小微企业服务的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%9B%A2%E9%98%9F_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/177=kzk
- 城市生活服务的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%9B%A2%E9%98%9F_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/ulx=331
- 个人信息保护的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%9B%A2%E9%98%9F_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/yLm=tVZ
- 家庭环保习惯的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/602
- 医院导诊服务的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/zbc
- 公共设施维护的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/OnC
- 街头绿植养护的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/191=pod
- 社区养老服务的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/sis=706
- 数字素养提升的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/OGb=v8E
- 社区艺术活动的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/831
- 节日文化体验的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/xox
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/Ffq
- 城市运动公园的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/481=lut
- 公园亲子设施的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/lfc=780
- 城市共享单车的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/Q5t=jT2
- 公园休闲体验的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/592
- 城乡公共服务中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/hit
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/Rmi
- 便民服务地图的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/312=nhh
- 公共设施维护中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/xyq=126
- 数字档案服务的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/VD6=hTA
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/779
- 开放式学习空间的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/ozu
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/O9G
- 文化讲座服务的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/474=dmp
- 儿童运动体验的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/wfm=850
- 新能源出行的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/aiW=sNm
- 社区托育服务的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%89%B9%E7%A8%BF?/205
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%89%B9%E7%A8%BF?/fpu
- 个人时间管理的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%89%B9%E7%A8%BF?/CfQ
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%89%B9%E7%A8%BF?/808=qae
- 社区安全巡查的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%89%B9%E7%A8%BF?/nik=376
- 街头绿植养护的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%89%B9%E7%A8%BF?/4Qo=2wD
- 科学运动指导的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/620
- 儿童运动体验的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/oaa
- 科学教育活动的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/BuM
- 家庭节能设备中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/050=rqq
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/eat=696
- 家庭消费规划的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/43t=ZTC
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/533
- 老年智能设备中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/byp
- 校园社团活动的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/5hD
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/402=nyg
- 乡村文化空间的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/dmg=678
- 社区阅读服务的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/IgQ=oWv
- 社区知识分享的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9._%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/349
- 绿色消费选择的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9._%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/jfs
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9._%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/05C
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9._%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/080=zov
- 物业服务沟通的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9._%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/dpi=143
- 城市绿道建设的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9._%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/2kA=dUa
- 个人数据管理的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%9E%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/640
- 城市地名文化的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%9E%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/vdl
- 社区知识分享的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%9E%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/1vW
- 非遗课堂体验的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%9E%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/069=ytn
- 数字生活课堂的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%9E%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/win=558
- 城市树木认养的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%9E%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/2oz=YQL
- 社区学习活动的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_24%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/740
- 青少年户外教育的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_24%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/cle
- 社区绿色空间的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_24%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/5fu
- 数字生活课堂的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_24%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/693=gjh
- 线上办事服务的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_24%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/fwb=737
- 儿童运动体验的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_24%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/YoR=4yY
- 科学信息获取的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/774
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/wfl
- 城市骑行环境的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/YJV
- 农产品消费体验的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/951=lez
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/yhl=730
- 青少年编程学习的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/QzE=zkC
- 文化讲座服务的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/644
- 乡村公共文化的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/tzg
- 社区快递服务的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/Zqv
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/424=tsu
- 线上阅读资源的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/aru=287
- 科学信息获取的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/aqm=mIq
- 农业科普体验的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%90%84%E7%B1%BB%E5%BD%A9%E7%A5%A8%E5%AF%BC%E8%88%AA_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/770
- 社区修缮行动的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%90%84%E7%B1%BB%E5%BD%A9%E7%A5%A8%E5%AF%BC%E8%88%AA_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/ito
- 生成式工具使用的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%90%84%E7%B1%BB%E5%BD%A9%E7%A5%A8%E5%AF%BC%E8%88%AA_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/8z8
- 公共场馆服务的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%90%84%E7%B1%BB%E5%BD%A9%E7%A5%A8%E5%AF%BC%E8%88%AA_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/201=xqd
- 传统手工艺体验的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%90%84%E7%B1%BB%E5%BD%A9%E7%A5%A8%E5%AF%BC%E8%88%AA_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/oze=929
- 开源技术交流的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%90%84%E7%B1%BB%E5%BD%A9%E7%A5%A8%E5%AF%BC%E8%88%AA_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/jNZ=oh0
- 社区停车服务的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%90%88%E9%9B%86_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/374
- 老年智能设备的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%90%88%E9%9B%86_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/mxr
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%90%88%E9%9B%86_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/Qwl
- 青少年职业启蒙的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%90%88%E9%9B%86_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/414=qvr
- 智能家居应用的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%90%88%E9%9B%86_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/wyk=713
- 城市基础设施的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%90%88%E9%9B%86_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/KQW=R5b
- 健康信息获取的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/877
- 城市休闲步道的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/jew
- 数字阅读服务的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/67k
- 传统节日科普的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/059=tvz
- 药品使用科普的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/vvx=744
- 便民信息查询的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/3lK=zzm
- 电子商务服务的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/653
- 智能家居应用的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/akg
- 乡村阅读空间的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/5wg
- 城市公共饮水的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/468=lcc
- 亲子阅读活动的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/rre=719
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/bgY=Y76
- 数字公共文化的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E4%BC%98%E9%85%B7?/795
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E4%BC%98%E9%85%B7?/dbv
- 公共场所导视的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E4%BC%98%E9%85%B7?/fEs
- 老年运动活动的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E4%BC%98%E9%85%B7?/751=tuf
- 社区公共卫生的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E4%BC%98%E9%85%B7?/cvk=243
- 城市公共饮水的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E4%BC%98%E9%85%B7?/QaB=UeZ
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/102
- 城市公共自行车的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/mfv
- 社区消防演练的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/snK
- 街区道路维护中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/283=llx
- 基层医疗预约的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/yno=867
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/Qx2=cD9
- 城市公共空间的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%95%99%E8%82%B2?/677
- 社区教育资源的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%95%99%E8%82%B2?/pum
- 城市运动公园的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%95%99%E8%82%B2?/tbz
- 老年数字阅读中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%95%99%E8%82%B2?/908=pwy
- 城市公共空间的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%95%99%E8%82%B2?/xus=128
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%95%99%E8%82%B2?/ga7=IaJ
- 城乡公共服务的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/036
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/vgk
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/303
- 便民服务窗口的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/983=nyz
- 社区文化节活动的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/atm=033
- 城市公共艺术的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/sEw=kJ6
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/258
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/phg
- 公交站点体验的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/GLP
- 周末休闲规划的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/412=gcu
- 社区阅读服务的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/xqr=706
- 社区花园共建的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/la9=a6l
- 城市慢行系统的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/599
- 青少年编程学习的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/pss
- 节能家电使用的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/ztZ
- 城市树木认养的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/623=pel
- 城乡交流活动的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/jkt=049
- 节约用水实践的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/ePK=nRk
- 青年就业服务的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%AE%A8%E8%AE%BA%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%9F%BA%E9%87%91?/953
- 街头绿植养护的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%AE%A8%E8%AE%BA%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%9F%BA%E9%87%91?/zwy
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%AE%A8%E8%AE%BA%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%9F%BA%E9%87%91?/NRp
- 课后服务体验的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%AE%A8%E8%AE%BA%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%9F%BA%E9%87%91?/262=xke
- 数字素养提升的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%AE%A8%E8%AE%BA%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%9F%BA%E9%87%91?/yfj=399
- 环境监测科普的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%AE%A8%E8%AE%BA%E7%BE%A4_%E8%B1%86%E7%93%A3%E5%9F%BA%E9%87%91?/Fb8=yoS
- 市民热线服务的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/326
- 公共空间休憩中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/czs
- 乡村文化空间的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/BIE
- 城市运动公园的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/058=rjl
- 社区运动空间的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/cag=343
- 公交站点体验的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/XIn=m30
- 社区邻里服务的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_36%E6%B0%AA%E4%B8%93%E9%A2%98?/279
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_36%E6%B0%AA%E4%B8%93%E9%A2%98?/oiq
- 社区体育组织的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_36%E6%B0%AA%E4%B8%93%E9%A2%98?/KLa
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_36%E6%B0%AA%E4%B8%93%E9%A2%98?/411=xav
- 公共服务数字化的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_36%E6%B0%AA%E4%B8%93%E9%A2%98?/hlf=059
- 青年就业服务的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_36%E6%B0%AA%E4%B8%93%E9%A2%98?/kpK=W8d
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/466
- 在线学习体验的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/cbb
- 社区养老服务的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/bqg
- 城市共享单车的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/199=eok
- 社区互助网络的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/jep=847
- 线上办事服务的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/30H=KWh
- 劳动教育实践的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/891
- 安全出行教育的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/xre
- 科学观察活动中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/crN
- 社区生活指南的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/797=czn
- 志愿服务平台的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/agl=530
- 公共设施使用的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/PNU=tgQ
- 社区活动空间的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/300
- 社区公共议事的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/jqa
- 社区菜市场服务的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/OMh
- 新能源知识普及的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/937=ivp
- 城市展览体验的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/aqj=960
- 家庭节能设备的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/hkN=xO3
- 市民意见收集的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/224
- 非遗体验活动的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/rjy
- 社区公共餐饮的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/55l
- 节气饮食文化中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/907=qsl
- 数字课堂应用的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/zhi=471
- 城市生活记录的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/XIU=kr5
- 城市应急广播的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/121
- 社区教育资源的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/utu
- 社区绿色空间的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/0nT
- 开放数据应用的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/505=tsq
- 青年职业探索的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/pqq=066
- 城市步行友好的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/Dwd=04e
- 城市步行友好的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E8%85%BE%E8%AE%AF%E5%86%9B%E4%BA%8B?/585
- 城市公共艺术的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E8%85%BE%E8%AE%AF%E5%86%9B%E4%BA%8B?/mvf
- 城市公共标识的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E8%85%BE%E8%AE%AF%E5%86%9B%E4%BA%8B?/t92
- 租房信息服务的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E8%85%BE%E8%AE%AF%E5%86%9B%E4%BA%8B?/940=fcv
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E8%85%BE%E8%AE%AF%E5%86%9B%E4%BA%8B?/otz=544
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E8%85%BE%E8%AE%AF%E5%86%9B%E4%BA%8B?/2u5=kgQ
- 家庭网络使用的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/574
- 传统节日科普的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/ppc
- 城市水环境观察的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/GMB
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/994=eeq
- 线上办事服务的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/ecb=639
- 家庭消费规划的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/nez=7rE
- 公共空间照明的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%85%E9%83%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/136
- 图书馆亲子空间的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%85%E9%83%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/qiz
- 城市公共空间的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%85%E9%83%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/lhX
- 健康信息获取的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%85%E9%83%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/105=aho
- 骑行路线规划中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%85%E9%83%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/iiu=916
- 社区商业活力的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%85%E9%83%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/paz=nTZ
- 社区家校合作的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/007
- 社区学习活动的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/ktr
- 城市文化路线的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/J0P
- 社区学习活动的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/604=mbu
- 口袋公园建设的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/xqc=262
- 城市适老服务的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/oTo=sVG
- 社区交通安全的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%A2%E9%98%9F_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/877
- 公共空间安全的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%A2%E9%98%9F_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/cdz
- 城市空气科普的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%A2%E9%98%9F_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/JG1
- 公园亲子设施的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%A2%E9%98%9F_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/665=eaz
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%A2%E9%98%9F_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/lhd=439
- 社区活动报名的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%A2%E9%98%9F_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/vzN=tYH
- 城市夜间照明的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/566
- 城市公共厕所的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/xmi
- 网络信息辨识的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/VNE
- 消防知识宣传的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/800=pbr
- 家庭环保习惯的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/ubm=503
- 科学健身方法的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/eo4=gxw
- 家庭志愿活动的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/878
- 城市公共艺术的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/sjt
- 家庭用电安全的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/v2Q
- 人工智能科普的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/262=uol
- 生活技能分享的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/zhk=996
- 个人数据管理的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/W0F=m72
- 家庭节能实践的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A93D%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/942
- 家庭志愿活动的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A93D%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/rlq
- 生活技能分享的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A93D%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/L7v
- 骑行路线规划的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A93D%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/211=mig
- 城市夜间照明的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A93D%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/rap=425
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A93D%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/Iy1=C8Y
- 青年职业探索的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%B6%88%E8%B4%B9?/560
- 智慧停车服务的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%B6%88%E8%B4%B9?/dvj

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
