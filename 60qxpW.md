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

- 学校体育活动的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/aWG
- 社区学习活动的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/512=hwv
- 小微企业服务的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/xnb=797
- 城市游园体验的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/DkT=SSJ
- 社区信息发布的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk%E6%8B%BE%E5%9C%A8%E7%BA%BF%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/236
- 药品使用科普的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk%E6%8B%BE%E5%9C%A8%E7%BA%BF%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/hij
- 乡村教育资源的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk%E6%8B%BE%E5%9C%A8%E7%BA%BF%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/1Ws
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk%E6%8B%BE%E5%9C%A8%E7%BA%BF%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/560=hvr
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk%E6%8B%BE%E5%9C%A8%E7%BA%BF%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ddl=328
- 家庭消费规划的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk%E6%8B%BE%E5%9C%A8%E7%BA%BF%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ixn=Fsp
- 创业经验分享的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E6%8C%A3%E9%92%B1%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/417
- 公共设施维护的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E6%8C%A3%E9%92%B1%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/oti
- 青少年心理健康的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E6%8C%A3%E9%92%B1%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/BXt
- 个人信息保护的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E6%8C%A3%E9%92%B1%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/037=uig
- 乡村公共服务的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E6%8C%A3%E9%92%B1%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/wkn=700
- 环境教育课程的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E6%8C%A3%E9%92%B1%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/v70=LbC
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/190
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/xhu
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/uu6
- 城市公共座椅的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/394=etg
- 社区信息发布的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/dsz=219
- 社区故事采集的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/Jy4=FCq
- 社区交通安全的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/117
- 乡村产业科普的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/jca
- 乡村生活观察的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/e0n
- 数字公共文化的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/927=gdh
- 智慧停车服务的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/jeo=823
- 课后服务体验的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/xGr=bEO
- 节能生活方式的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E5%90%A7%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/544
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E5%90%A7%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/mch
- 城市公共厕所的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E5%90%A7%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/6wH
- 社区心理支持的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E5%90%A7%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/900=ppb
- 社区学习活动的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E5%90%A7%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/ylt=980
- 新能源知识普及的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E5%90%A7%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/7W9=rIL
- 公共服务指南的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%90%A7%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/165
- 城市应急广播的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%90%A7%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/ikw
- 家庭健康管理的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%90%A7%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/L41
- 开源技术交流的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%90%A7%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/532=hqx
- 社区手工活动的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%90%A7%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/umr=614
- 社区养老服务的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%90%A7%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/pll=hmF
- 家庭健康管理的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/527
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/vkn
- 数字资源检索的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/1Nj
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/641=qou
- 就业技能培训中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/wds=144
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/mzu=tBZ
- 城市生活服务的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E6%B8%AF%E8%82%A1?/704
- 街道综合服务的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E6%B8%AF%E8%82%A1?/xyc
- 开放式学习空间的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E6%B8%AF%E8%82%A1?/9On
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E6%B8%AF%E8%82%A1?/968=icd
- 文化场馆预约的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E6%B8%AF%E8%82%A1?/ufn=726
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E6%B8%AF%E8%82%A1?/DGr=tjW
- 科学信息获取的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%B9%90%E4%BA%AB8%E5%A8%B1%E4%B9%90-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/961
- 公共场所导视的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%B9%90%E4%BA%AB8%E5%A8%B1%E4%B9%90-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/gln
- 社区休闲设施的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%B9%90%E4%BA%AB8%E5%A8%B1%E4%B9%90-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/VWX
- 家庭急救准备的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%B9%90%E4%BA%AB8%E5%A8%B1%E4%B9%90-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/575=pdg
- 智慧城市体验的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%B9%90%E4%BA%AB8%E5%A8%B1%E4%B9%90-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/kfe=879
- 口袋公园建设的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%B9%90%E4%BA%AB8%E5%A8%B1%E4%B9%90-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/onQ=9CW
- 社区共享书架的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9%E5%AE%98%E6%96%B9app%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/929
- 社区快递服务的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9%E5%AE%98%E6%96%B9app%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/vss
- 城市绿道建设的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9%E5%AE%98%E6%96%B9app%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/H2d
- 科技馆参观体验的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9%E5%AE%98%E6%96%B9app%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/869=zca
- 乡村阅读空间的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9%E5%AE%98%E6%96%B9app%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/hku=230
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9%E5%AE%98%E6%96%B9app%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/hZm=Ad8
- 公共文化活动的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_1996%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/401
- 家庭急救准备的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_1996%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/off
- 社区共享书架的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_1996%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/pac
- 健康饮食教育的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_1996%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/143=bqa
- 社区知识分享的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_1996%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/vrt=817
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_1996%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/4XE=Wdk
- 公园亲子设施的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_1996%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%94%B6%E8%97%8F?/923
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_1996%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%94%B6%E8%97%8F?/ubl
- 城市公共座椅的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_1996%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%94%B6%E8%97%8F?/3ru
- 邻里共享空间的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_1996%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%94%B6%E8%97%8F?/138=eye
- 绿色生活实践的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_1996%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%94%B6%E8%97%8F?/ahb=226
- 环境教育课程的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_1996%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%94%B6%E8%97%8F?/bLA=Jai
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_1996%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/387
- 电子商务服务中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_1996%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/uuz
- 老年学习活动的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_1996%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/NMH
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_1996%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/977=hct
- 家庭照护支持中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_1996%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/dwn=138
- 老年学习活动的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_1996%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/py3=wce
- 社区读书角建设的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1996%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/508
- 绿色出行服务的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1996%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/gzb
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1996%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/Y0e
- 社区运动空间的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1996%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/515=euf
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1996%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/kid=309
- 图书馆活动策划的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1996%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/YdP=O48
- 数字阅读服务有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1996%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/935
- 居家适老化改造的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1996%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/rzg
- 节日文化体验的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1996%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/DhL
- 公交站点体验的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1996%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/347=sgh
- 城市夜间生活有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1996%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/umy=837
- 数字生活课堂的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1996%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/EHN=qEl
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_1996%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/639
- 骑行路线规划的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_1996%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/qmm
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_1996%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/cd2
- 公共空间安全的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_1996%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/302=mfe
- 新能源出行的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_1996%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/yiu=989
- 电动汽车充电的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_1996%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/ozj=Qar
- 骑行路线规划的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%9B%9B%E4%BA%BF%E5%BD%A9APP_%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95?/073
- 城市夜间照明的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%9B%9B%E4%BA%BF%E5%BD%A9APP_%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95?/gml
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%9B%9B%E4%BA%BF%E5%BD%A9APP_%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95?/3aD
- 社区停车服务的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%9B%9B%E4%BA%BF%E5%BD%A9APP_%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95?/382=bny
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%9B%9B%E4%BA%BF%E5%BD%A9APP_%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95?/ixl=935
- 城市适老服务的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%9B%9B%E4%BA%BF%E5%BD%A9APP_%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95?/N0v=EDE
- 个人数据管理的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/052
- 公共服务预约的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/cza
- 家庭教育交流的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/bbG
- 校园节能行动的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/425=dnc
- 数字政务体验的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/cqk=084
- 青少年户外教育的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/kqR=Ub8
- 个人数据管理的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9welcome_36%E6%B0%AA%E6%94%B6%E8%97%8F?/778
- 社区休闲设施的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9welcome_36%E6%B0%AA%E6%94%B6%E8%97%8F?/dnx
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9welcome_36%E6%B0%AA%E6%94%B6%E8%97%8F?/f5y
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9welcome_36%E6%B0%AA%E6%94%B6%E8%97%8F?/564=twa
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9welcome_36%E6%B0%AA%E6%94%B6%E8%97%8F?/oiu=395
- 社区便民集市的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9welcome_36%E6%B0%AA%E6%94%B6%E8%97%8F?/OTv=1m2
- 城市可持续生活的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%A8%B1%E4%B9%90_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/396
- 公共空间安全的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%A8%B1%E4%B9%90_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/ruj
- 社区应急准备的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%A8%B1%E4%B9%90_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/h23
- 城市基础设施的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%A8%B1%E4%B9%90_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/400=gbk
- 公共设施维护的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%A8%B1%E4%B9%90_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/yae=486
- 科学运动指导的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%A8%B1%E4%B9%90_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/pRd=ZME
- 邻里互助活动的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%9B%9B%E4%BA%BF%E5%BD%A9%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/027
- 家庭健康管理的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%9B%9B%E4%BA%BF%E5%BD%A9%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/qhl
- 绿色建筑理念的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%9B%9B%E4%BA%BF%E5%BD%A9%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/Ndl
- 传统节日科普的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%9B%9B%E4%BA%BF%E5%BD%A9%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/933=ret
- 城市绿色交通的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%9B%9B%E4%BA%BF%E5%BD%A9%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/qhz=342
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%9B%9B%E4%BA%BF%E5%BD%A9%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/oCG=xPy
- 城市公共艺术的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/865
- 数字资源检索的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/ssn
- 社区故事采集的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/2Qa
- 公共交通信息服务的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/607=jgi
- 通勤路线规划的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/nbr=456
- 图书借阅体验的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/PlA=zop
- 城市地名文化的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%98%93%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/778
- 环境监测科普的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%98%93%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/cgu
- 乡村文化空间的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%98%93%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/8Mq
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%98%93%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/073=kqb
- 绿色办公实践的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%98%93%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/vsa=307
- 城市社区治理的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%98%93%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/bn1=GOf
- 城市基础设施的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/536
- 数字档案服务的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/vib
- 文化场馆预约的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/zqy
- 小区公共照明的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/576=qsh
- 小区停车协商的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/jaq=893
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%98%93%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/Hmu=7Zr
- 社区学习活动的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E6%89%8B%E6%9C%BA%E7%89%88_360%E5%86%9B%E4%BA%8B?/318
- 物业服务沟通的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E6%89%8B%E6%9C%BA%E7%89%88_360%E5%86%9B%E4%BA%8B?/xgz
- 零废弃生活尝试的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E6%89%8B%E6%9C%BA%E7%89%88_360%E5%86%9B%E4%BA%8B?/njv
- 科学健身方法的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E6%89%8B%E6%9C%BA%E7%89%88_360%E5%86%9B%E4%BA%8B?/146=zea
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E6%89%8B%E6%9C%BA%E7%89%88_360%E5%86%9B%E4%BA%8B?/owm=835
- 校园安全教育的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E6%89%8B%E6%9C%BA%E7%89%88_360%E5%86%9B%E4%BA%8B?/VRm=8kN
- 家庭阅读计划的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/204
- 城市体育设施的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/ngp
- 便民服务地图的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/eBT
- 开放数据应用的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/633=sjk
- 生活垃圾回收的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/pbb=984
- 数字课堂应用的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/Zzr=BZw
- 软件开发学习的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E6%8E%8C%E6%9F%9C-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/183
- 科学教育活动的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E6%8E%8C%E6%9F%9C-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/isg
- 家庭运动计划的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E6%8E%8C%E6%9F%9C-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/dgb
- 家庭运动计划的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E6%8E%8C%E6%9F%9C-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/988=soq
- 个人信息保护的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E6%8E%8C%E6%9F%9C-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/pld=686
- 便民维修服务的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E6%8E%8C%E6%9F%9C-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/dxZ=sPc
- 社区活动策划的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/485
- 劳动教育实践从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/drr
- 社区庭院绿化的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/kn3
- 社区文化节活动的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/455=tzn
- 环境监测科普的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/igb=629
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/B5k=KGo
- 社区应急准备的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/784
- 公共空间安全的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/zqh
- 家庭安全提示的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/8Ju
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/685=zbu
- 生活技能分享的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/cot=329
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/0lH=Zw0
- 低碳社区实践的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8E%A2%E5%BA%97?/450
- 地方美食文化的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8E%A2%E5%BA%97?/orx
- 居民健康教育的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8E%A2%E5%BA%97?/tVE
- 文化讲座服务的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8E%A2%E5%BA%97?/975=qoy
- 城市基础设施的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8E%A2%E5%BA%97?/ktv=234
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8E%A2%E5%BA%97?/46g=3GQ
- 社区活动策划的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/161
- 社区活动空间的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/ydk
- 医院导诊服务的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/GZY
- 城市适老服务的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/070=etx
- 绿色出行服务的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/bbh=128
- 乡村电商实践的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/N2I=DUA
- 公共服务预约的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/830
- 社区公共餐饮的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/fqs
- 人工智能科普的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/g4M
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/260=pvk
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/jjr=146
- 社区交通安全的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/UJQ=TiD
- 线上办事服务的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/153
- 网络安全教育的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/lqy
- 劳动教育实践有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/xKt
- 公共服务评价的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/363=cob
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/ycf=345
- 绿色生活实践的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/xGY=mB2
- 城市基础设施的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/019
- 社区协商议事的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/uhr
- 本地历史资料中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/I7F
- 家庭消费规划的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/084=rkt
- 街头绿植养护的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/bvc=405
- 社区共享书架的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/P1L=0nj
- 社区便民集市的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/516
- 城市骑行环境的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/erl
- 社区活动空间的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/9yb
- 小区公共照明的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/762=abt
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/dup=479
- 城乡交流活动的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/654=N4n
- 图书馆活动策划的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/009
- 社区绿色空间的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/eya
- 公共空间导览的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/izh
- 志愿服务平台的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/434=ydj
- 公共场所导视的绿色实践方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/jyc=323
- 城市树木认养的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/KOT=B8N
- 家庭饮食安排的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/625
- 生活服务数字化的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/usn
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/but
- 职业技能学习的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/021=zrs
- 城市基础设施的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/zyz=151
- 城市应急科普的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/KVs=H7O
- 乡村文化活动的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/997
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/tmi
- 城市住房服务的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/2Pc
- 城市公共饮水的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/746=sqj
- 家庭消费规划的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/mxs=691
- 便民服务窗口的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/4lP=LV2
- 志愿者培训交流的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/012
- 社区安全巡查的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/cam
- 城市展览体验的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/S0K
- 学校食育活动中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/842=bsq
- 绿色校园实践的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/gpl=320
- 家庭节能设备的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/Cvu=XsM
- 儿童阅读角的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/491
- 城市公共标识的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/ark
- 城市便民驿站的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/SBh
- 社区活动空间的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/625=hih
- 社区活动策划的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/nko=698
- 社区共享书架的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/s9n=b0n
- 生成式工具使用的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BE%AE%E8%81%8A%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/852
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BE%AE%E8%81%8A%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/eeo
- 城市文明出行的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BE%AE%E8%81%8A%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/6Ot
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BE%AE%E8%81%8A%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/543=ews
- 社区活动策划的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BE%AE%E8%81%8A%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/hxe=905
- 科学信息获取的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BE%AE%E8%81%8A%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/EDf=a3i

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
