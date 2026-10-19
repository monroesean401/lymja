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

- 公共空间安全中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%B7_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/vxi=884
- 街区小店体验的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%B7_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/uqX=jpi
- 图书借阅体验的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/255
- 公共空间休憩的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/apt
- 城市应急广播的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/GnY
- 家庭用电安全的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/079=xzk
- 青少年科技社团的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/anu=883
- 城市体育设施的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/Bjz=UCj
- 传统节日科普的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/509
- 社区商业活力的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/kks
- 科学教育活动的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/h7n
- 无障碍出行的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/088=ovi
- 邻里互助活动的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/pxf=971
- 街道综合服务的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/Zi6=jpX
- 家庭园艺实践的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/825
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/cvu
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/5MY
- 公共健身器材的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/262=ewu
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/rkg=896
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/KUo=yIW
- 城市生活记录的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/490
- 乡村电商实践的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/kyv
- 社区故事采集的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/fOM
- 城市地名文化的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/418=lth
- 家庭环保行动的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/qfy=618
- 全民阅读推广的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/Tvm=xfz
- 绿色办公实践的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3%E5%A4%A7%E5%85%A8%E5%88%86%E4%BA%AB_%E5%BF%85%E5%BA%94%E5%BF%AB%E6%8A%A5?/852
- 居家适老化改造的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3%E5%A4%A7%E5%85%A8%E5%88%86%E4%BA%AB_%E5%BF%85%E5%BA%94%E5%BF%AB%E6%8A%A5?/dbj
- 电动汽车充电中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3%E5%A4%A7%E5%85%A8%E5%88%86%E4%BA%AB_%E5%BF%85%E5%BA%94%E5%BF%AB%E6%8A%A5?/t7E
- 地方戏曲体验的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3%E5%A4%A7%E5%85%A8%E5%88%86%E4%BA%AB_%E5%BF%85%E5%BA%94%E5%BF%AB%E6%8A%A5?/491=vib
- 儿童友好空间的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3%E5%A4%A7%E5%85%A8%E5%88%86%E4%BA%AB_%E5%BF%85%E5%BA%94%E5%BF%AB%E6%8A%A5?/tae=388
- 城市应急科普的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3%E5%A4%A7%E5%85%A8%E5%88%86%E4%BA%AB_%E5%BF%85%E5%BA%94%E5%BF%AB%E6%8A%A5?/SmL=V5q
- 数字创意课程的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E6%B6%88%E8%B4%B9?/050
- 城市步行环境的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E6%B6%88%E8%B4%B9?/tbs
- 健康信息获取的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E6%B6%88%E8%B4%B9?/hMD
- 老年人出行服务的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E6%B6%88%E8%B4%B9?/464=kom
- 绿色校园实践的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E6%B6%88%E8%B4%B9?/rtt=246
- 公共服务数字化的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E6%B6%88%E8%B4%B9?/5WD=8ld
- 青年志愿活动的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/501
- 垃圾分类指导的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/itg
- 社区文化传播的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/DlD
- 家庭节能实践的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/093=auv
- 城市便民驿站的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/dkp=360
- 学校食育活动的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/bYc=R9l
- 终身学习资源的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/727
- 社区文化传播的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/knp
- 儿童阅读角的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/83l
- 社区宣传栏更新的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/815=bxm
- 灵活就业交流的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/frc=114
- 社区庭院绿化的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/Oms=UPZ
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/553
- 小区停车协商的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/xss
- 社区儿童活动的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/65c
- 社区活动空间的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/499=mlx
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/rxa=753
- 城市公共空间的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/rcH=bPx
- 老年人文化生活的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/460
- 医院导诊服务的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/lci
- 老年运动活动的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/Da9
- 城市夜间照明中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/597=gly
- 社区环保活动的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/zho=250
- 骑行路线规划的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/WBB=6fk
- 街区更新实践的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/693
- 电动汽车充电的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/qgr
- 就业技能培训的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/cYf
- 城市建设科普的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/465=dfr
- 城市雨天出行的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/dqe=075
- 绿色快递包装的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/tjL=RtL
- 社区公共议事的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/041
- 节气饮食文化的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/wch
- 城市公共饮水的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/NRf
- 志愿服务平台的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/735=cdk
- 社区生活指南的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/tft=485
- 科学观察活动的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/x76=eJo
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/127
- 食品安全科普的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/xbh
- 乡村文化活动的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/wpS
- 城市公共厕所的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/419=xts
- 数字创意课程的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/yxi=963
- 公共场所导视的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/cxW=ksG
- 社区文化节活动的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/505
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/xpw
- 城市应急科普的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/29g
- 线上阅读资源的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/316=dbb
- 课后服务体验的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/rym=893
- 青年职业探索的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/ru5=Yxq
- 食品配送体验的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/319
- 社区文化节活动的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/dwb
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/gZA
- 城市基础设施的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/166=wet
- 智慧停车服务的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/qod=114
- 社区阅读服务的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/0F6=HNM
- 社区托育服务的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/061
- 社区老年食堂的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/xus
- 社区防暑服务的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/MgT
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/141=psa
- 公共设施使用的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/dcb=772
- 城市噪声观察的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Q3S=QsP
- 数字阅读服务的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E5%AE%98%E7%BD%91%E5%BC%80%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/269
- 医院导诊服务的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E5%AE%98%E7%BD%91%E5%BC%80%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/rsm
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E5%AE%98%E7%BD%91%E5%BC%80%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/kYD
- 青少年户外教育的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E5%AE%98%E7%BD%91%E5%BC%80%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/242=ezc
- 智慧停车服务的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E5%AE%98%E7%BD%91%E5%BC%80%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/mar=581
- 科学教育活动的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E5%AE%98%E7%BD%91%E5%BC%80%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/vg7=7q5
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6app_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/885
- 家庭安全提示的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6app_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/tfi
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6app_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/1tz
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6app_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/863=kro
- 社区家校合作的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6app_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/pjr=189
- 电动汽车充电的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6app_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/2Sm=dKD
- 公交无障碍服务的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/777
- 社区菜市场服务的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/upx
- 农贸市场环境的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/Bgg
- 地方旅游导览的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/403=axi
- 亲子科普活动的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/jnl=357
- 文化遗产保护科普的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/nJc=Xfs
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%9C%80%E9%AB%98%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/287
- 家庭网络使用的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%9C%80%E9%AB%98%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/gsq
- 市民意见收集的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%9C%80%E9%AB%98%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/VDd
- 地方戏曲体验的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%9C%80%E9%AB%98%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/127=yes
- 公共场馆服务的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%9C%80%E9%AB%98%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/rxq=781
- 城市共享单车的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%9C%80%E9%AB%98%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/ZzW=Bc8
- 非遗体验活动的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/453
- 家庭养老规划的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/pax
- 课后服务体验的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/Bp2
- 职业技能学习的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/467=sbp
- 绿色快递包装的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/eji=436
- 数字公共文化有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/2ln=9U3
- 数字学习资源的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E9%AB%98%E7%BA%A7%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/401
- 小微企业服务中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E9%AB%98%E7%BA%A7%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/hmr
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E9%AB%98%E7%BA%A7%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/2fr
- 城市慢行系统中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E9%AB%98%E7%BA%A7%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/357=fka
- 数字阅读服务的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E9%AB%98%E7%BA%A7%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/cii=433
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E9%AB%98%E7%BA%A7%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/gus=sfY
- 农贸市场环境中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%9D%A0%E8%B0%B1%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/998
- 社区绿色空间的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%9D%A0%E8%B0%B1%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/yqe
- 绿色生活实践的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%9D%A0%E8%B0%B1%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/lAO
- 线上办事服务的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%9D%A0%E8%B0%B1%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/290=yzs
- 乡村电商实践的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%9D%A0%E8%B0%B1%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/jfc=440
- 通勤路线规划的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%9D%A0%E8%B0%B1%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/gAP=1hF
- 小区停车协商的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%99%E6%8E%88_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/685
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%99%E6%8E%88_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/kgp
- 社区信息发布中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%99%E6%8E%88_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/UtK
- 科普展览体验的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%99%E6%8E%88_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/711=ryh
- 数字资源检索的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%99%E6%8E%88_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/xur=217
- 公园休闲体验的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%99%E6%8E%88_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/WHy=gnr
- 公共空间安全的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pk%E6%8B%BE%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/627
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pk%E6%8B%BE%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/mmn
- 家庭急救准备的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pk%E6%8B%BE%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/Nfz
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pk%E6%8B%BE%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/863=lep
- 数字设备回收的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pk%E6%8B%BE%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/qid=973
- 节假日出行安排的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pk%E6%8B%BE%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/c2E=uQ0
- 图书馆活动策划的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_PK%E6%8B%BE%E5%89%8D%E4%BA%8C%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/649
- 节能生活方式的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_PK%E6%8B%BE%E5%89%8D%E4%BA%8C%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/tob
- 街区小店体验的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_PK%E6%8B%BE%E5%89%8D%E4%BA%8C%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/766
- 地方戏曲体验的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_PK%E6%8B%BE%E5%89%8D%E4%BA%8C%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/103=oxv
- 社区生活指南的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_PK%E6%8B%BE%E5%89%8D%E4%BA%8C%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/vwr=896
- 社区托育服务的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_PK%E6%8B%BE%E5%89%8D%E4%BA%8C%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/luB=oE7
- 城市适老服务的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_PK0%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/685
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_PK0%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/opu
- 传统节日科普的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_PK0%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/K2D
- 地方民俗记录的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_PK0%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/454=iug
- 地方文化传播的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_PK0%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/wgl=183
- 科学教育活动的公共信息获取方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_PK0%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/G6i=ouL
- 绿色校园实践中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%9C%80%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/698
- 公共文化活动的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%9C%80%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/ens
- 乡村文化活动的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%9C%80%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/0bn
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%9C%80%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/381=ree
- 居民健康教育中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%9C%80%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/xxz=447
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%9C%80%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/LYw=F9L
- 光伏知识科普的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9C%80%E7%A8%B3%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E9%9F%B3%E4%B9%90?/982
- 城市运动公园的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9C%80%E7%A8%B3%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E9%9F%B3%E4%B9%90?/nlx
- 公共空间休憩的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9C%80%E7%A8%B3%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E9%9F%B3%E4%B9%90?/LN1
- 社区应急准备的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9C%80%E7%A8%B3%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E9%9F%B3%E4%B9%90?/135=gob
- 城市博物馆活动的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9C%80%E7%A8%B3%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E9%9F%B3%E4%B9%90?/syi=314
- 城市游园体验的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9C%80%E7%A8%B3%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E9%9F%B3%E4%B9%90?/A7L=yTH
- 城市公共艺术的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/563
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/mus
- 安全出行教育的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/Rwo
- 公共空间照明的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/841=qet
- 社区互助网络的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/vqz=545
- 校园阅读活动的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/WZa=Huf
- 绿色办公实践的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E6%9C%80%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/093
- 城乡公共服务的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E6%9C%80%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/rgg
- 青年职业探索的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E6%9C%80%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/xjW
- 读书会组织的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E6%9C%80%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/528=fgv
- 校园社团活动的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E6%9C%80%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/kse=377
- 全民阅读推广的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E6%9C%80%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/hbS=p0i
- 校园社团活动的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E7%95%85%E6%B8%B8?/151
- 城市公共艺术的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E7%95%85%E6%B8%B8?/fib
- 休闲运动入门的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E7%95%85%E6%B8%B8?/6Ew
- 公交无障碍服务的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E7%95%85%E6%B8%B8?/174=tti
- 地方美食文化的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E7%95%85%E6%B8%B8?/eeh=286
- 开放数据应用的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E7%95%85%E6%B8%B8?/JVV=1QZ
- 社区教育资源的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/447
- 社区手工活动的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/oea
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/q1m
- 乡村公共阅读的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/672=vff
- 家庭健康科普中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/grd=668
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/UVP=rRM
- 青少年编程学习有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%A4%A7%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/504
- 线上阅读资源的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%A4%A7%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/iok
- 家庭急救准备的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%A4%A7%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/P1U
- 医院导诊服务的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%A4%A7%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/899=ynq
- 家庭安全提示的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%A4%A7%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/hdb=953
- 城乡交流活动的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%A4%A7%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/J67=GcC
- 机器人科普活动有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/332
- 老年人日常照护的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/rih
- 农产品品牌传播的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/enF
- 数字艺术创作的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/229=odm
- 城市文化路线的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/ifz=890
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/zSY=SWw
- 家庭教育交流中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%B0%8F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/994
- 儿童安全出行的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%B0%8F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/ofn
- 城市游园体验的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%B0%8F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/2Mp
- 生活技能分享的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%B0%8F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/361=zmk
- 绿色快递包装的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%B0%8F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/dee=502
- 乡村阅读空间从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%B0%8F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/Pu6=zap
- 社区生活指南有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%89%BE%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B0%81%E6%9C%89_%E7%BD%91%E6%98%93%E7%9B%98%E7%82%B9?/688
- 低碳社区实践的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%89%BE%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B0%81%E6%9C%89_%E7%BD%91%E6%98%93%E7%9B%98%E7%82%B9?/hil
- 公共空间照明的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%89%BE%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B0%81%E6%9C%89_%E7%BD%91%E6%98%93%E7%9B%98%E7%82%B9?/qbi
- 消防知识宣传的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%89%BE%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B0%81%E6%9C%89_%E7%BD%91%E6%98%93%E7%9B%98%E7%82%B9?/876=mqw
- 农村环境治理的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%89%BE%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B0%81%E6%9C%89_%E7%BD%91%E6%98%93%E7%9B%98%E7%82%B9?/usp=895
- 社区垃圾回收的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%89%BE%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B0%81%E6%9C%89_%E7%BD%91%E6%98%93%E7%9B%98%E7%82%B9?/vyC=Usq
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%89%BE%E5%AE%9E%E5%8A%9B%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/166
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%89%BE%E5%AE%9E%E5%8A%9B%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/fyq
- 城市共享单车的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%89%BE%E5%AE%9E%E5%8A%9B%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/vmW
- 城市便民驿站的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%89%BE%E5%AE%9E%E5%8A%9B%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/340=spn
- 创业经验分享的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%89%BE%E5%AE%9E%E5%8A%9B%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/whe=379
- 社区安全巡查的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%89%BE%E5%AE%9E%E5%8A%9B%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/gKv=9vb
- 城市适老服务的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AF%9A%E4%BF%A1%E8%80%81%E7%BE%A4_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/720
- 学校食育活动的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AF%9A%E4%BF%A1%E8%80%81%E7%BE%A4_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/oep
- 乡村电商实践的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AF%9A%E4%BF%A1%E8%80%81%E7%BE%A4_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/B0I
- 校园安全教育的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AF%9A%E4%BF%A1%E8%80%81%E7%BE%A4_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/857=tju
- 新能源出行中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AF%9A%E4%BF%A1%E8%80%81%E7%BE%A4_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/ogt=052
- 劳动教育实践的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AF%9A%E4%BF%A1%E8%80%81%E7%BE%A4_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/cfD=GvW
- 社区艺术活动的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4%E8%A7%84%E5%BE%8B_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/272
- 绿色生活实践的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4%E8%A7%84%E5%BE%8B_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/orb
- 绿色生活实践的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4%E8%A7%84%E5%BE%8B_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/LLR
- 城市博物馆服务的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4%E8%A7%84%E5%BE%8B_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/084=cyt
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4%E8%A7%84%E5%BE%8B_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/zrf=961
- 社区家政服务的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4%E8%A7%84%E5%BE%8B_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/80U=Cee
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/213
- 公共服务指南的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/xmm
- 城市骑行环境的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/IM2
- 小微企业服务的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/322=xjm
- 本地旅行体验的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/pgx=932
- 节气饮食文化的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/x4H=taN
- 城市公共厕所的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%8F%8D%E6%B0%B4%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/272
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%8F%8D%E6%B0%B4%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/cej

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
