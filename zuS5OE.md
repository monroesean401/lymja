# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 周末休闲规划的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/pJQ
- 便民服务窗口的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/113=teb
- 城市步行友好的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/wsy=570
- 公园亲子设施中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/owo=eFD
- 城乡公共服务的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B810%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/462
- 基层健康服务的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B810%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/hra
- 无障碍信息设计的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B810%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/2HQ
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B810%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/141=zip
- 文明养宠科普中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B810%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/pdr=859
- 人工智能科普的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B810%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/7sn=Oi5
- 家庭照护支持有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/597
- 基层健康档案的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/gaa
- 绿色建筑理念的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/Ep2
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/091=toi
- 本地消费场景的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/pvy=863
- 本地消费场景的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/7xu=0Vr
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E4%B9%90%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/137
- 家庭急救准备的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E4%B9%90%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/qtq
- 通勤路线规划的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E4%B9%90%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/3DE
- 校园社团活动的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E4%B9%90%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/289=liq
- 数字支付体验的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E4%B9%90%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/wwu=213
- 居家防滑改造的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E4%B9%90%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/uVt=qhj
- 城市微更新实践的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Elv%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/109
- 城市生活服务的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Elv%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/igm
- 城市应急广播的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Elv%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/MH8
- 图书借阅体验的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Elv%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/712=dbc
- 环境监测科普的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Elv%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/jhw=208
- 公园无障碍服务中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Elv%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/Fkm=3bi
- 劳动教育实践的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Vlll_%E6%BE%8E%E6%B9%83%E6%A1%A3%E6%A1%88?/508
- 地方美食文化中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Vlll_%E6%BE%8E%E6%B9%83%E6%A1%A3%E6%A1%88?/opj
- 公共空间照明中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Vlll_%E6%BE%8E%E6%B9%83%E6%A1%A3%E6%A1%88?/1QF
- 日常摄影记录的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Vlll_%E6%BE%8E%E6%B9%83%E6%A1%A3%E6%A1%88?/015=uuu
- 健康饮水科普的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Vlll_%E6%BE%8E%E6%B9%83%E6%A1%A3%E6%A1%88?/ogk=409
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8Vlll_%E6%BE%8E%E6%B9%83%E6%A1%A3%E6%A1%88?/GMX=cPF
- 社区安全巡查的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/242
- 小微企业服务的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/htu
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/UWm
- 社区志愿服务的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/206=yip
- 家庭饮食安排的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/eua=012
- 小区电梯维护的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/rLd=CUv
- 公共卫生设施的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/353
- 城乡公共服务的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/bod
- 科学教育活动的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/FXj
- 小微企业服务的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/198=gxd
- 社区文化传播的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/gwb=484
- 社区阅读服务的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/5dV=UpD
- 网络信息辨识的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%EF%BD%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/561
- 节日文化体验的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%EF%BD%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/rlz
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%EF%BD%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/nKt
- 绿色出行服务的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%EF%BD%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/436=ivv
- 青年志愿活动的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%EF%BD%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/bco=513
- 科学健身方法的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%EF%BD%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/Wfq=Def
- 骑行路线规划的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_Welcome500%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/925
- 数字阅读服务的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_Welcome500%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/jxi
- 城市公共厕所的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_Welcome500%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/gZY
- 社区修缮行动的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_Welcome500%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/652=tal
- 社区便利生活的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_Welcome500%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/vtp=211
- 电子商务服务的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_Welcome500%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/DhM=sOX
- 乡村产业科普的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/460
- 基层服务创新的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/juf
- 公共服务评价的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/oSH
- 市民意见收集的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/375=lwf
- 消防知识宣传的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/jnh=087
- 社区邻里服务的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/yWj=WFs
- 城市休闲步道的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/925
- 乡村公共服务的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/pxm
- 公共设施维护的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/b0x
- 城市步行环境的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/705=iiz
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/wfd=822
- 城市公共自行车的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/Zup=3DP
- 公园无障碍服务的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E4%B8%8D%E4%BA%86_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/379
- 居家适老化改造的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E4%B8%8D%E4%BA%86_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/rln
- 节约用水实践的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E4%B8%8D%E4%BA%86_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/Vpk
- 市民热线服务的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E4%B8%8D%E4%BA%86_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/238=hgp
- 地方戏曲体验的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E4%B8%8D%E4%BA%86_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/pyl=912
- 城市运动公园的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E4%B8%8D%E4%BA%86_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/6sW=d5W
- 社区公共餐饮的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evlll%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_360%E8%BE%9F%E8%B0%A3?/165
- 公园亲子设施的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evlll%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_360%E8%BE%9F%E8%B0%A3?/vom
- 生活垃圾回收的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evlll%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_360%E8%BE%9F%E8%B0%A3?/LaJ
- 社区应急准备有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evlll%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_360%E8%BE%9F%E8%B0%A3?/034=myh
- 地方文化传播的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evlll%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_360%E8%BE%9F%E8%B0%A3?/cmp=722
- 社区手工活动的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evlll%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_360%E8%BE%9F%E8%B0%A3?/f7E=mMM
- 社区志愿服务中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%BD%91%E4%B8%8A%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/044
- 家庭志愿活动的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%BD%91%E4%B8%8A%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/xqz
- 基层健康服务的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%BD%91%E4%B8%8A%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/VRv
- 信息无障碍体验的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%BD%91%E4%B8%8A%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/288=nzv
- 社区垃圾分类的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%BD%91%E4%B8%8A%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/udq=243
- 城市水环境观察从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E7%BD%91%E4%B8%8A%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/f3f=Wpx
- 社区协商议事的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/075
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/hys
- 数字便民地图的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/3Da
- 城市建设科普的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/330=rci
- 家庭用电安全的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/hkg=288
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/Jwo=ms5
- 校园阅读活动的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_360%E7%BE%8E%E8%82%A1?/110
- 公共服务沟通的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_360%E7%BE%8E%E8%82%A1?/wya
- 儿童友好空间的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_360%E7%BE%8E%E8%82%A1?/B93
- 数字设备回收的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_360%E7%BE%8E%E8%82%A1?/292=maf
- 邻里共享空间的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_360%E7%BE%8E%E8%82%A1?/hfa=252
- 绿色快递包装的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_360%E7%BE%8E%E8%82%A1?/4gi=Upy
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evll%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E7%A8%8E%E5%8A%A1?/208
- 气象科普传播的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evll%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E7%A8%8E%E5%8A%A1?/ggr
- 乡村产业科普的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evll%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E7%A8%8E%E5%8A%A1?/SIw
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evll%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E7%A8%8E%E5%8A%A1?/136=faj
- 休闲运动入门的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evll%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E7%A8%8E%E5%8A%A1?/bnz=657
- 老年数字阅读的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evll%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E7%A8%8E%E5%8A%A1?/l5o=uq5
- 基层健康档案中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E9%A2%86%E5%8F%96%E8%AF%9D%E8%B4%B9_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/738
- 城市文明实践的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E9%A2%86%E5%8F%96%E8%AF%9D%E8%B4%B9_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/nak
- 智能家居应用的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E9%A2%86%E5%8F%96%E8%AF%9D%E8%B4%B9_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/AKH
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E9%A2%86%E5%8F%96%E8%AF%9D%E8%B4%B9_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/613=ses
- 农产品品牌传播的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E9%A2%86%E5%8F%96%E8%AF%9D%E8%B4%B9_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/mip=228
- 社区设施共享的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E9%A2%86%E5%8F%96%E8%AF%9D%E8%B4%B9_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/BFt=bw5
- 青年就业服务的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/888
- 个人信息保护的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/kbf
- 学校食育活动的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/7gp
- 社区快递服务的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/765=pcw
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/qwj=866
- 城市应急广播的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/FAM=uYR
- 节日文化体验的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_24123%E5%BD%A9%E7%A5%A8%E6%99%92%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/728
- 城市农夫市集的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_24123%E5%BD%A9%E7%A5%A8%E6%99%92%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/ymc
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_24123%E5%BD%A9%E7%A5%A8%E6%99%92%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/RuV
- 老年友好服务的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_24123%E5%BD%A9%E7%A5%A8%E6%99%92%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/699=xwq
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_24123%E5%BD%A9%E7%A5%A8%E6%99%92%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/tgv=903
- 信息无障碍体验的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_24123%E5%BD%A9%E7%A5%A8%E6%99%92%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/tc4=9Yi
- 运动安全知识的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/738
- 便民维修服务的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/jfr
- 社区手工活动的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/NJB
- 社区便利生活的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/614=zzl
- 城市共享单车的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/vfd=035
- 城市文明出行的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/rXK=g4a
- 农业科普体验的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E6%97%A7%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AF%84?/089
- 低碳社区实践的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E6%97%A7%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AF%84?/jdx
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E6%97%A7%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AF%84?/rl6
- 传统手工艺体验的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E6%97%A7%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AF%84?/385=zmw
- 乡村公共文化的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E6%97%A7%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AF%84?/ybr=589
- 家庭健康科普的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E6%97%A7%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AF%84?/nbW=zfz
- 公交站点体验的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/926
- 绿色出行服务的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/rid
- 校园节能行动的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/8IV
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/418=uwo
- 公共空间导览的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/zvx=620
- 社区养老服务的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/2Vc=WQG
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_welcome%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/204
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_welcome%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/qxm
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_welcome%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/VmX
- 信息无障碍体验的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_welcome%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/852=knz
- 数字便民地图的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_welcome%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/vkl=789
- 图书借阅体验的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_welcome%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/dCt=Nbj
- 医院导诊服务中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/440
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/fps
- 家庭教育交流的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/9PP
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/965=fua
- 街区小店体验的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/uba=252
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/kGH=PZU
- 公共空间安全的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E9%97%AE%E7%AD%94?/905
- 公共服务数字化的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E9%97%AE%E7%AD%94?/dyy
- 社区停车服务的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E9%97%AE%E7%AD%94?/a65
- 街头绿植养护的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E9%97%AE%E7%AD%94?/049=rmi
- 家庭安全提示的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E9%97%AE%E7%AD%94?/mum=518
- 青年就业服务的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E9%97%AE%E7%AD%94?/R3h=pxS
- 公共交通接驳的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E4%B9%88_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/540
- 儿童安全出行的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E4%B9%88_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/kve
- 社会体育指导的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E4%B9%88_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/pPS
- 科学运动指导的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E4%B9%88_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/191=fbv
- 农贸市场环境的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E4%B9%88_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/nvv=570
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E4%B9%88_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/9YV=z8H
- 电动汽车充电的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eiv%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/182
- 城乡公共服务的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eiv%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/onr
- 公园休闲体验的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eiv%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/2Ts
- 家庭志愿活动的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eiv%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/136=xrv
- 线上办事服务的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eiv%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/tec=133
- 生活垃圾回收的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eiv%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/djm=wGe
- 社区修缮行动的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97__%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/739
- 创业经验分享的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97__%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/iqd
- 健康信息获取的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97__%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/3wT
- 数字阅读服务有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97__%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/639=clt
- 社区商业活力的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97__%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/acj=388
- 老年人出行服务的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97__%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/YvR=aLi
- 农村环境治理的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/984
- 小区电梯维护的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/tvy
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/1qj
- 开放式学习空间的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/849=xuz
- 社区志愿服务的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/txy=147
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/xBI=kty
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%9C%A8%E7%BA%BF%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/310
- 运动安全知识的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%9C%A8%E7%BA%BF%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/egz
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%9C%A8%E7%BA%BF%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/yeU
- 非遗体验活动的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%9C%A8%E7%BA%BF%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/075=jut
- 读书会组织的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%9C%A8%E7%BA%BF%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/vkn=082
- 社区知识分享的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%9C%A8%E7%BA%BF%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/hJm=ikj
- 运动安全知识的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/171
- 急救知识普及的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/auf
- 农贸市场环境中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/DKH
- 城乡公共服务的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/949=psq
- 本地消费场景的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/iiv=344
- 城市便民驿站的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/CqW=WtP
- 数字档案服务的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/978
- 城市夜间生活的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/uxh
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/ufb
- 社区便民集市的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/366=lng
- 社区家校合作的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/jjq=296
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/B4S=3wW
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/759
- 就业技能培训的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/txb
- 日常摄影记录的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/ZBo
- 家庭节能实践的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/992=nuz
- 家庭收纳实践的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/jbj=816
- 城市共享单车的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/KBM=6Cg
- 垃圾分类指导的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/165
- 文化讲座服务的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/uxo
- 青少年科普实践的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/lLa
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/488=apx
- 传统节日科普的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/uez=959
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/XSE=eHs
- 生活服务数字化的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/070
- 城乡交通衔接的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/rsa
- 社区消防演练的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/HEt
- 小区停车协商的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/272=yag
- 公共交通接驳的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/new=971
- 信息无障碍体验的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/q54=LQ3
- 科学观察活动的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%A7%82%E7%82%B9?/910
- 网络信息辨识的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%A7%82%E7%82%B9?/xoj
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%A7%82%E7%82%B9?/Dv3
- 口袋公园建设的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%A7%82%E7%82%B9?/351=afy
- 城市水环境观察的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%A7%82%E7%82%B9?/idg=772
- 城市公共空间的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%A7%82%E7%82%B9?/HTY=p7A
- 老年学习活动的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85123_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/058
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85123_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/tpm
- 家庭饮食安排的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85123_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/AJB
- 新能源知识普及的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85123_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/007=fzc
- 地方美食文化的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85123_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/cre=684
- 城市公共自行车的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85123_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/KEN=HjI
- 青少年科技社团的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/015
- 开放式学习空间的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/vbu
- 儿童安全出行的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/72C
- 乡村生态旅游的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/079=ynh
- 青少年科普实践的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/sua=132
- 社区安全巡查的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/DzM=8OX
- 光伏知识科普的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/640
- 乡村阅读空间的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/hto
- 绿色办公实践的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/Bq5
- 家庭健康管理的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/840=hzg
- 社区垃圾回收的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/pvw=983
- 公共服务数字化的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/pq3=9Pp
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%87%A4%E5%87%B0vip%E5%BD%A9%E7%A5%A8_360%E5%88%9B%E6%8A%95?/821
- 城市展览体验的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%87%A4%E5%87%B0vip%E5%BD%A9%E7%A5%A8_360%E5%88%9B%E6%8A%95?/eda
- 软件开发学习的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%87%A4%E5%87%B0vip%E5%BD%A9%E7%A5%A8_360%E5%88%9B%E6%8A%95?/BrH
- 社区慢性病防控的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%87%A4%E5%87%B0vip%E5%BD%A9%E7%A5%A8_360%E5%88%9B%E6%8A%95?/880=drl
- 社区共享书架的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%87%A4%E5%87%B0vip%E5%BD%A9%E7%A5%A8_360%E5%88%9B%E6%8A%95?/iah=601
- 数字资源检索的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%87%A4%E5%87%B0vip%E5%BD%A9%E7%A5%A8_360%E5%88%9B%E6%8A%95?/aqi=AT9

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
