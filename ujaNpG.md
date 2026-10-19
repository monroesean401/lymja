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

- 城市人文观察的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/BHA
- 个人数据管理的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/487=kzh
- 气象科普传播的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/unp=496
- 社区花园共建的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/Nou=iXq
- 城市农夫市集的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/088
- 创业经验分享的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/dpl
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/xvI
- 开源技术交流的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/750=elo
- 志愿服务平台的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/aju=502
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/4TN=GEG
- 家庭照护支持的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/193
- 居家防滑改造的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/xuw
- 城市休闲步道的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/17x
- 新能源出行的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/712=txd
- 社区活动空间中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/whg=604
- 老年友好服务的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/kJD=ngY
- 在线学习体验的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/623
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/ugv
- 社区知识分享的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/NSR
- 骑行路线规划的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/768=svb
- 便民服务窗口的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/ofx=801
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/msM=8Eg
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/551
- 社区志愿服务的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/tcc
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/aAK
- 公共交通信息服务的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/250=fld
- 绿色生活实践的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/eho=725
- 城市夜间生活的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/aYa=JDm
- 居民健康教育中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/461
- 传统手工艺体验的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/cov
- 城市宠物友好空间的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/c6k
- 公共文化活动的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/367=hxm
- 公交无障碍服务有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/pru=303
- 智能家居应用的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/rME=bUd
- 生成式工具使用的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/002
- 社区邻里服务中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/yge
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/Ifz
- 市民意见收集的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/535=rpv
- 数字学习资源的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/yds=441
- 儿童友好空间的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/fbS=AGK
- 绿色校园实践的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/029
- 小区公共照明的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/nek
- 公共空间导览的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/esp
- 社区手工活动的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/620=tug
- 便民信息查询的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/ufn=044
- 公共空间导览的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/h1X=ljq
- 生活服务数字化的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/567
- 乡村生态旅游的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/rsf
- 学校食育活动的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/t2a
- 志愿服务平台的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/550=fkj
- 小区公共照明的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/ohy=035
- 城市公共艺术的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/QCL=KRC
- 公共卫生宣传的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/697
- 科学教育活动的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/qgb
- 老年运动活动的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/JuF
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/278=wot
- 公共服务咨询的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/ggv=639
- 文化场馆预约的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/Q4r=i7x
- 科学信息获取的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E7%BD%91_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/652
- 户外活动组织的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E7%BD%91_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/fzh
- 社区共享书架的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E7%BD%91_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/bGH
- 社区托育服务的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E7%BD%91_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/899=naj
- 社区文化节活动的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E7%BD%91_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/etm=757
- 城市骑行环境的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E7%BD%91_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/PD4=DsZ
- 社区安全巡查的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/394
- 城市夜间照明的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/xki
- 农贸市场环境的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/ILZ
- 健康饮食教育的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/060=xsg
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/zmu=336
- 街道综合服务的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/KJJ=EVR
- 城市可持续生活的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/215
- 社区学习活动的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/tqe
- 农产品品牌传播的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/fB9
- 地方文化传播的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/951=krl
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/wlc=155
- 社区便利生活的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/VVw=iDQ
- 儿童友好街区的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-APP_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/120
- 旧物循环利用的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-APP_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/odw
- 节能生活方式的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-APP_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/wOs
- 小微企业服务的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-APP_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/383=zor
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-APP_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/xjj=030
- 城市生活服务的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-APP_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/IFm=LgJ
- 公共服务指南的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/790
- 生活垃圾减量的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/qgs
- 个人信息保护的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/DKc
- 社区互助网络的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/905=ute
- 城市人文观察的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/xyi=684
- 消防知识宣传的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/IDG=UQv
- 文化讲座服务的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%A1%A3%E6%A1%88?/119
- 市民意见收集的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%A1%A3%E6%A1%88?/fha
- 小微企业服务的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%A1%A3%E6%A1%88?/b9U
- 农业科普体验的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%A1%A3%E6%A1%88?/117=cwt
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%A1%A3%E6%A1%88?/xci=028
- 社区活动报名的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%A1%A3%E6%A1%88?/Hv7=RkE
- 城市便民驿站的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/436
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/yat
- 街区更新实践的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/zBV
- 生成式工具使用的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/789=ovh
- 社区便利生活的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/pzp=325
- 文明养宠科普中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/346=c8m
- 光伏知识科普的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/273
- 劳动教育实践的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/hrl
- 科学睡眠习惯的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/g7m
- 公共设施维护的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/845=fsx
- 读书会组织的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/pch=217
- 城市博物馆活动的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/kNe=7J6
- 社会体育指导的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/742
- 社区慢性病防控的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/lkn
- 地方美食文化的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/jCK
- 公共文化活动的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/239=baj
- 家庭园艺实践的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/fhh=165
- 城市基础设施的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/Rmv=B6w
- 线上阅读资源的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/177
- 城市社区治理的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/vyn
- 环境教育课程从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/6HS
- 公共服务数字化的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/795=dbt
- 儿童户外活动的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/hjg=420
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/KmX=CA5
- 校园阅读活动的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/772
- 课后服务体验的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/cyu
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/hag
- 生活垃圾减量的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/628=tse
- 社区互助网络的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/fsy=657
- 读书会组织的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/XrN=Poq
- 乡村阅读空间的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/398
- 社区故事采集的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/sdf
- 节假日出行安排的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/CBF
- 亲子阅读活动的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/746=wje
- 青年职业探索的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/slx=036
- 社区邻里服务的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/yzX=Ivr
- 老旧小区改造的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/041
- 社区便利生活的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/ron
- 食品安全科普的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/EgX
- 口袋公园建设的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/101=fit
- 社区学习活动的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/fwl=859
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/MdO=BQh
- 社区协商议事的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91?/603
- 亲子阅读活动的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91?/pvh
- 城市空气科普的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91?/7mF
- 公共卫生宣传的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91?/436=ahk
- 物业服务沟通的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91?/jlm=735
- 社区便民集市的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%97%BA%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91?/AT6=Wqv
- 城市公共标识的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BE%AE%E8%81%8A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/763
- 节假日出行安排的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BE%AE%E8%81%8A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/mvu
- 小区停车协商的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BE%AE%E8%81%8A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/vsY
- 数字创作工具的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BE%AE%E8%81%8A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/587=nff
- 全民阅读推广的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BE%AE%E8%81%8A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/drl=021
- 数字学习资源的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BE%AE%E8%81%8A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/HNQ=Ro6
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/976
- 家庭节能实践的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/era
- 老旧小区改造的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/9kg
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/726=iot
- 环境监测科普的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/vqw=282
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/8p6=Sws
- 公共服务数字化的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/391
- 公共空间照明的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/jgi
- 口袋公园建设的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/q3f
- 城市社区治理的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/461=fvh
- 生活技能分享的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/gsr=867
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/MLv=v9i
- 本地旅行体验的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/260
- 城市体育设施的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/nud
- 绿色消费选择中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/UDy
- 城市适老服务的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/531=ere
- 市民意见收集的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/egh=426
- 社会体育指导的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/Dyw=IdU
- 社区知识分享的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/965
- 乡村教育资源的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/gbz
- 社区防暑服务的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/4DJ
- 老年数字阅读的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/806=gps
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/xkf=307
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/WNO=e64
- 小微企业服务的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/188
- 社区协商议事的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/olj
- 社区邻里服务的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/Uh8
- 城市展览体验的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/776=hbs
- 基层健康档案的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/hwq=355
- 无障碍出行的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%AE%A0%E7%89%A9?/UIz=H08
- 社区志愿服务的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/330
- 城市建设科普的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/mex
- 社区家校合作的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/VyV
- 地方美食文化的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/488=vpn
- 社区共享书架中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/aqf=879
- 城市噪声观察的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/M5F=Rhh
- 城市适老服务的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/419
- 城市空气科普的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/zup
- 就业技能培训中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/KgL
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/725=wfo
- 城市人文观察的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/aow=352
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/YxA=G8g
- 社区垃圾回收的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BE%AE%E8%81%8A-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/630
- 城市绿道建设的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BE%AE%E8%81%8A-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/tgj
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BE%AE%E8%81%8A-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/4lq
- 户外活动组织中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BE%AE%E8%81%8A-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/002=grh
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BE%AE%E8%81%8A-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/ojg=480
- 青少年编程学习的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BE%AE%E8%81%8A-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/EDF=7kf
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/329
- 文明养宠科普的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/riz
- 公共设施使用的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/wGS
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/598=zte
- 智慧城市体验的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/pwc=581
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BE%AE%E8%81%8A-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/bnQ=gjA
- 城市可持续生活的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BE%AE%E8%81%8A-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/522
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BE%AE%E8%81%8A-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/obb
- 街头绿植养护的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BE%AE%E8%81%8A-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/ZM3
- 数字创作工具的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BE%AE%E8%81%8A-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/691=wqp
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BE%AE%E8%81%8A-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/jxw=241
- 公交站点体验的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BE%AE%E8%81%8A-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/w4U=DeN
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BE%AE%E8%81%8A-APP_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/338
- 城市公共饮水的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BE%AE%E8%81%8A-APP_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/qer
- 社区宠物管理的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BE%AE%E8%81%8A-APP_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/8yi
- 城市展览体验的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BE%AE%E8%81%8A-APP_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/575=hhz
- 乡村文化活动的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BE%AE%E8%81%8A-APP_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/fju=906
- 绿色建筑理念的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BE%AE%E8%81%8A-APP_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/5IO=Np3
- 环境教育课程的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/752
- 乡村产业科普的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/aai
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/dSu
- 家庭节能实践的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/364=hxk
- 图书借阅体验的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/ppm=200
- 文化讲座服务的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BE%AE%E8%81%8A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/ZSx=568
- 节约用水实践的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/924
- 在线学习体验的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/rxj
- 便民信息查询的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/DZj
- 社区商业活力的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/985=sxx
- 公共场所导视的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/ndv=535
- 在线教育体验的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%BD%E5%86%85?/ZHb=yun
- 公共空间导览的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/991
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/wuq
- 城市夜间照明的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/bgj
- 社区便民集市的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/970=qih
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/eni=255
- 节日文化体验的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BE%AE%E8%81%8A-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/rND=lr1
- 公共服务咨询的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BE%AE%E8%81%8A-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/549
- 数字学习资源的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BE%AE%E8%81%8A-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/rpw
- 租房信息服务的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BE%AE%E8%81%8A-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/uoQ
- 地方美食文化的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BE%AE%E8%81%8A-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/590=pds
- 基层健康服务的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BE%AE%E8%81%8A-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/rde=264
- 数字生活课堂的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BE%AE%E8%81%8A-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/HG3=SbO
- 职业技能学习的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BE%AE%E8%81%8A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/986
- 家庭节能实践的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BE%AE%E8%81%8A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/jim
- 公共文化活动的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BE%AE%E8%81%8A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/EEN
- 远程协作工具从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BE%AE%E8%81%8A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/846=ndf
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BE%AE%E8%81%8A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/ukm=955
- 城乡交流活动的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BE%AE%E8%81%8A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/0a8=Rpk
- 社区绿色空间的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BE%AE%E8%81%8A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/453
- 公共空间照明的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BE%AE%E8%81%8A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/eeh
- 老年人文化生活的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BE%AE%E8%81%8A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/XGn
- 城市树木认养的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BE%AE%E8%81%8A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/897=dov
- 光伏知识科普的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BE%AE%E8%81%8A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/moq=447
- 社区体育组织中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BE%AE%E8%81%8A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/mqn=8ck

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
