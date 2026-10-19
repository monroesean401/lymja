# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 科技馆参观体验的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/glk=081
- 环境教育课程的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/lws=MbQ
- 电子商务服务的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/982
- 城市博物馆服务的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/lcj
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/gbZ
- 社区教育资源的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/993=qtp
- 城市农夫市集的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/lbo=567
- 社区消防演练的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/1hX=3a0
- 社区慢性病防控的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E7%BD%91%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/655
- 社区防暑服务的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E7%BD%91%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/rpb
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E7%BD%91%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/mYm
- 非遗课堂体验的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E7%BD%91%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/031=aob
- 公园休闲体验的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E7%BD%91%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/neb=504
- 基层服务创新的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E7%BD%91%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/fhf=gcA
- 社区宣传栏更新的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/081
- 科学健身方法的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/gmp
- 健康步道使用的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/fJ3
- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/527=hyq
- 公共设施维护的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/zpf=197
- 公共设施使用的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/ljU=bFG
- 休闲运动入门的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%BD%A9%E7%A5%A8~%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/303
- 社区停车服务的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%BD%A9%E7%A5%A8~%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/mro
- 青少年心理健康的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%BD%A9%E7%A5%A8~%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/4XO
- 公共空间导览的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%BD%A9%E7%A5%A8~%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/707=hyk
- 老旧小区改造的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%BD%A9%E7%A5%A8~%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/nfb=775
- 地方民俗记录的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%BD%A9%E7%A5%A8~%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/z7T=63D
- 非遗体验活动的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%90%89%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E4%BA%A7?/476
- 家庭健康管理的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%90%89%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E4%BA%A7?/jrx
- 社区读书角建设的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%90%89%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E4%BA%A7?/ewS
- 非遗课堂体验的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%90%89%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E4%BA%A7?/285=ctm
- 社区互助网络的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%90%89%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E4%BA%A7?/vwk=517
- 急救知识普及的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%90%89%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E4%BA%A7?/B8V=N2P
- 乡村生态观察的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/961
- 城市慢行系统的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/fuc
- 文明养宠科普的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/UT5
- 家庭理财科普的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/515=lmq
- 开放式学习空间的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/vbg=045
- 城市步行友好的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/610=Wor
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/406
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/omj
- 青年职业探索的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/LLD
- 社区宣传栏更新的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/088=xqw
- 家庭安全提示的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/tlh=101
- 生活服务数字化的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/72w=tO1
- 绿色建筑理念的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/368
- 家庭志愿活动的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/jdn
- 数字创意课程的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/V4t
- 公共服务数字化的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/666=pej
- 非遗课堂体验的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/nmq=308
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/Y36=JU3
- 基层健康档案的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/003
- 通勤路线规划的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/txx
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/WMB
- 基层服务创新的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/170=dpo
- 社区艺术活动的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/wzd=136
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/CTc=viG
- 节约用水实践的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/561
- 社区消防演练的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/abo
- 城市生活记录的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/swh
- 城市适老服务的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/765=qtg
- 个人数据管理的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/uej=795
- 城市适老服务的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/ZDc=4IN
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_49%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/192
- 居民健康教育的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_49%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/dwh
- 数字课堂应用的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_49%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/ALc
- 社区垃圾分类的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_49%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/530=nxm
- 城市夜间生活的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_49%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/xca=815
- 学校食育活动的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_49%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/LKY=3O6
- 便民服务窗口的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/538
- 社区阅读服务的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/lvh
- 社区菜市场服务的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/v44
- 社区学习活动的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/724=ibk
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/snh=891
- 老年数字阅读的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/tVK=FGN
- 社区法律科普的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_857%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%8E%A2%E6%BA%90?/414
- 农村环境治理的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_857%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%8E%A2%E6%BA%90?/xcr
- 街区更新实践中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_857%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%8E%A2%E6%BA%90?/6pw
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_857%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%8E%A2%E6%BA%90?/423=byd
- 城市噪声观察的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_857%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%8E%A2%E6%BA%90?/atv=805
- 校园社团活动的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_857%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%8E%A2%E6%BA%90?/pis=W1S
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A98com%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/554
- 口袋公园建设的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A98com%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/rou
- 数字设备回收的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A98com%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/hCa
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A98com%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/171=cle
- 社区安全巡查的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A98com%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/eyf=615
- 绿色生活实践的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A98com%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/EyG=qB5
- 校园节能行动的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_998%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/924
- 新能源出行的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_998%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/wqf
- 机器学习入门的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_998%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/xlw
- 旧物循环利用的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_998%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/071=hbb
- 数字创意课程的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_998%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/nnr=227
- 健康饮食教育的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_998%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/ucs=NIU
- 本地历史资料的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/294
- 社区互助网络的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/nig
- 社区文化节活动的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/JHS
- 文化遗产保护科普从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/773=yjk
- 亲子科普活动中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/ukb=241
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/rkz=V6y
- 社区宣传栏更新的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/542
- 社区便民服务的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/dpy
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/Ozt
- 网络安全教育的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/576=iqt
- 社区信息发布的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/xtd=982
- 城市体育设施中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/JrC=GAx
- 线上办事服务的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%80%9F%E5%8F%91365%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/189
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%80%9F%E5%8F%91365%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/zql
- 学校体育活动的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%80%9F%E5%8F%91365%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/KyW
- 社区生活指南的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%80%9F%E5%8F%91365%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/922=hig
- 公共服务沟通的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%80%9F%E5%8F%91365%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/aca=856
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%80%9F%E5%8F%91365%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/gfe=9RA
- 社区防暑服务的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365-app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/794
- 户外活动组织的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365-app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/igy
- 数字档案服务的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365-app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/xu2
- 公共空间照明的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365-app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/579=wzq
- 地方民俗记录的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365-app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/fdx=042
- 公益活动组织的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365-app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/DB3=OpE
- 社区知识分享的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/522
- 社区便民服务的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/lrt
- 公共卫生宣传的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/Z1H
- 数据分析入门的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/887=kex
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/vnj=746
- 生活垃圾回收的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/E2r=lNG
- 医院导诊服务的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_360%E7%90%86%E8%B4%A2?/558
- 城市运动公园的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_360%E7%90%86%E8%B4%A2?/dbl
- 社区公共卫生的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_360%E7%90%86%E8%B4%A2?/cpJ
- 校园社团活动的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_360%E7%90%86%E8%B4%A2?/622=eum
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_360%E7%90%86%E8%B4%A2?/fdb=724
- 乡村产业科普的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_360%E7%90%86%E8%B4%A2?/ozr=2F3
- 公共卫生设施的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/086
- 绿色建筑理念从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/zom
- 数字公共文化的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/TY3
- 社区菜市场服务的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/922=pct
- 社区应急准备的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/rgd=259
- 绿色生活实践的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%B8%B8%E6%88%8F_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/aLs=fc8
- 家庭健康科普的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/186
- 药品使用科普的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/jkd
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/Yzd
- 青少年户外教育中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/544=tby
- 休闲运动入门从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/uke=352
- 乡村文化活动的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/r8f=UQH
- 公交站点体验的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%81%94%E7%9B%9F-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/449
- 城市地名文化的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%81%94%E7%9B%9F-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/mjs
- 乡村电商实践的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%81%94%E7%9B%9F-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/mDs
- 社区体育组织的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%81%94%E7%9B%9F-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/936=smg
- 社区邻里服务的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%81%94%E7%9B%9F-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/sxo=980
- 绿色消费选择的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%81%94%E7%9B%9F-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/P2k=SIc
- 数字资源检索的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B9%90%E8%B6%A3%E5%BD%A9~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/605
- 社区养老服务的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B9%90%E8%B6%A3%E5%BD%A9~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/yok
- 社区交通安全的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B9%90%E8%B6%A3%E5%BD%A9~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/2X7
- 公共文化活动的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B9%90%E8%B6%A3%E5%BD%A9~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/552=mpp
- 公交站点体验的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B9%90%E8%B6%A3%E5%BD%A9~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/tcf=054
- 基层健康服务的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B9%90%E8%B6%A3%E5%BD%A9~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/3jP=BzR
- 社区公共卫生的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E7%99%BB%E5%BD%95_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/258
- 城市公共空间的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E7%99%BB%E5%BD%95_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/kcl
- 人工智能科普的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E7%99%BB%E5%BD%95_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/9dG
- 骑行路线规划的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E7%99%BB%E5%BD%95_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/302=itb
- 公共空间休憩有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E7%99%BB%E5%BD%95_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/rul=468
- 社区绿色空间的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E7%99%BB%E5%BD%95_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/BPS=XWq
- 药品使用科普的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%A4%B4%E6%9D%A1%E6%9B%B2%E8%89%BA?/418
- 人工智能科普的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%A4%B4%E6%9D%A1%E6%9B%B2%E8%89%BA?/cnl
- 城市雨天出行的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%A4%B4%E6%9D%A1%E6%9B%B2%E8%89%BA?/hsh
- 乡村文化活动的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%A4%B4%E6%9D%A1%E6%9B%B2%E8%89%BA?/887=lkl
- 地方美食文化的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%A4%B4%E6%9D%A1%E6%9B%B2%E8%89%BA?/epb=841
- 城市游园体验的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%A4%B4%E6%9D%A1%E6%9B%B2%E8%89%BA?/QbE=jfa
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E7%9B%88-APP-%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/634
- 公共设施使用的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E7%9B%88-APP-%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/nta
- 城市运动公园的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E7%9B%88-APP-%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/mwd
- 地方文化传播的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E7%9B%88-APP-%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/630=xbq
- 社区公共餐饮的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E7%9B%88-APP-%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/col=297
- 城市噪声观察的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E7%9B%88-APP-%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/YEl=vyY
- 数字公共文化的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/247
- 节约用水实践的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/qmz
- 新能源知识普及的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/bZv
- 青年职业探索的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/934=evg
- 城市微更新实践的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/hqz=482
- 网络信息辨识的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/zj2=wrK
- 数字艺术创作的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500%E4%B8%AD%E5%BF%83%E7%89%88_360%E6%B3%95%E5%BE%8B?/845
- 科普展览体验的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500%E4%B8%AD%E5%BF%83%E7%89%88_360%E6%B3%95%E5%BE%8B?/tcm
- 科普展览体验的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500%E4%B8%AD%E5%BF%83%E7%89%88_360%E6%B3%95%E5%BE%8B?/2h3
- 城市夜间照明的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500%E4%B8%AD%E5%BF%83%E7%89%88_360%E6%B3%95%E5%BE%8B?/199=qtt
- 生成式工具使用的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500%E4%B8%AD%E5%BF%83%E7%89%88_360%E6%B3%95%E5%BE%8B?/veb=775
- 公园亲子设施的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500%E4%B8%AD%E5%BF%83%E7%89%88_360%E6%B3%95%E5%BE%8B?/eLe=n5s
- 社区知识分享的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/186
- 消防知识宣传的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/prl
- 城市地名文化的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/g8l
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/395=yof
- 数字创意课程的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/hmf=374
- 城市骑行环境的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/CQv=hNI
- 农贸市场环境的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/681
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/rca
- 校园节能行动的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/tEI
- 家庭志愿活动的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/737=omc
- 科学教育活动的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/rje=808
- 数字素养提升的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/3Ne=heU
- 城市基础设施有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/761
- 城市基础设施的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/cru
- 家庭阅读计划的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/ey1
- 城乡交流活动的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/357=cjb
- 生活技能分享的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/wkq=537
- 社区心理支持的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/Vs9=1MZ
- 农产品消费体验的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/914
- 科学观察活动的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/see
- 生活技能分享的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/xWe
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/879=qsb
- 社区读书角建设中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/geg=437
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/C5h=kQK
- 乡村产业科普的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%BE%B3%E9%97%A8%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/312
- 城市树木认养的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%BE%B3%E9%97%A8%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/btk
- 无障碍出行的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%BE%B3%E9%97%A8%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/KNx
- 便民维修服务的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%BE%B3%E9%97%A8%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/525=waw
- 城市夜间照明的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%BE%B3%E9%97%A8%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/erb=268
- 数字地图应用的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%BE%B3%E9%97%A8%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/QrU=548
- 城市可持续生活的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/643
- 公交无障碍服务的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/sgg
- 城市便民驿站的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/8xx
- 旧物循环利用的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/310=pyl
- 公共设施维护的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/keg=197
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/1W4=ZkP
- 安全出行教育的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/955
- 农产品消费体验的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/fwb
- 社区活动策划的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/i4Z
- 家庭安全提示的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/545=ysf
- 乡村公共文化的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/xhl=514
- 居家适老化改造的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/UQo=Vki
- 老年运动活动的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%8C%BA_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/295
- 城市体育设施的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%8C%BA_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/gjy
- 农产品品牌传播的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%8C%BA_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/pzK
- 社区防暑服务的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%8C%BA_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/593=hjj
- 环境监测科普的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%8C%BA_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/phx=013
- 食品配送体验的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%8C%BA_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/mwX=aE9
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/860
- 便民信息查询的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/vtv
- 邻里共享空间中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/8xg
- 城市绿色交通的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/917=nih
- 社区便民集市的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/qbo=257
- 家庭饮食安排的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/P64=ATm
- 社区科普课堂的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85PG%E5%AE%98%E7%BD%91%E7%89%88_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/695
- 社区科普课堂的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85PG%E5%AE%98%E7%BD%91%E7%89%88_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/ucn
- 社区养老服务的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85PG%E5%AE%98%E7%BD%91%E7%89%88_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/IaO
- 家庭科学教育的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85PG%E5%AE%98%E7%BD%91%E7%89%88_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/176=qvf
- 城市基础设施的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85PG%E5%AE%98%E7%BD%91%E7%89%88_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/nct=814
- 文化讲座服务的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85PG%E5%AE%98%E7%BD%91%E7%89%88_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/nTs=p1U
- 科技馆参观体验的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/284
- 公共服务咨询的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/smp
- 社区修缮行动的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/7q9
- 社区公共议事的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/481=wud
- 邻里互助活动的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/ceb=009
- 智能家居应用的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/qzt=cE7
- 传统手工艺体验的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85pg%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/619
- 居家适老化改造的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85pg%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/afb

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
