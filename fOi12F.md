# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 在线教育体验的社区参与观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/oqb=155
- 户外活动组织的服务信息整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/yiA=uH0
- 社区设施共享的数字化应用观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/349
- 儿童友好空间的执行流程参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/mdy
- 绿色办公实践的基础设施观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/3kc
- 家庭收纳实践的便利性观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/264=ezf
- 城市骑行环境的组织方法与经验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/sha=970
- 家庭教育交流中的几个关键细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/w76=hQh
- 数字创意课程的行动步骤参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2?/789
- 生成式工具使用的设施维护观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2?/hko
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2?/9Xl
- 社区志愿服务的公共参与指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2?/549=soj
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2?/mkf=959
- 社区协商议事的社区行动案例 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2?/Li4=roF
- 公园亲子设施的公共信息获取方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/896
- 城市夜间照明的活动组织技巧 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/vfh
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/r5H
- 生活服务数字化的居民参与机会 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/249=mer
- 节日文化体验的服务体验观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/bfr=966
- 社区活动报名的资源利用方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/cHc=L0f
- 基层医疗预约的适老服务细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/774
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/iud
- 校园节能行动的协商参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/UZr
- 生活服务数字化的日常管理方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/119=faf
- 骑行路线规划的空间使用体验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/fup=138
- 社区教育资源的持续改进方向 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/wwX=cNG
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/737
- 公共服务数字化的资源利用方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/keo
- 社区阅读服务的组织方法与经验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/464
- 城市骑行环境的社区参与观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/510=kwu
- 智能家居应用的参与方式与路径 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/eiq=282
- 应急物资管理的组织方法与经验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/mGH=uXo
- 城市公共艺术的设施维护观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/011
- 校园阅读活动的家庭实践清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/ckc
- 社区绿色空间的日常实践笔记 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/CqU
- 社区科普课堂的服务范围梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/255=qak
- 社区绿色空间的绿色实践方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/wwf=045
- 公共空间导览的持续改进方向 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/zV9=Fb0
- 健康饮水科普的空间设计要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/116
- 职业技能学习的协作机制梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/pud
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/z70
- 基层服务创新的实用信息清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/956=iie
- 居家防滑改造的常见问题梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/gue=432
- 社区慢性病防控的便利性观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/D3Z=vpJ
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/131
- 校园社团活动中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/vhu
- 社区体育组织的基础设施观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/uws
- 公园休闲体验的基础设施观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/719=pnf
- 城市慢行系统中的几个关键细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/kxp=796
- 家庭环保习惯的便利性观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/Drf=5wJ
- 租房信息服务的服务范围梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/838
- 城市文化路线的长期维护要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/qcr
- 青年就业服务的活动组织技巧 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/ajX
- 社区菜市场服务的服务质量观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/133=hbs
- 绿色快递包装的家庭参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/tit=529
- 城市骑行环境的资源整合思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/Qgx=F1u
- 生活垃圾回收的便捷程度观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/245
- 城市公共自行车的活动体验回顾 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/ahk
- 城市空气科普的服务体验观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/lYj
- 乡村教育资源有哪些值得关注的细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/220=gzj
- 城市应急广播的服务体验观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/rjt=525
- 远程协作工具的基础知识问答 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/vGI=Wxk
- 公共服务沟通的资源整合思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/098
- 社区法律科普的日常使用指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/brq
- 科学运动指导中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/Yjr
- 跨代沟通活动的持续改进方向 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/161=jhq
- 骑行路线规划的绿色实践方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/uqv=751
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/gYe=qYG
- 公共空间安全的参与方式与路径 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/630
- 家庭环保行动的学习资源整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/osb
- 非遗体验活动的行动步骤参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/1yD
- 在线学习体验的社区行动案例 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/476=het
- 居民健康教育的便利性观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/jjp=506
- 邻里互助活动的活动体验回顾 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/XqP=ije
- 儿童运动体验的数字化应用观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/082
- 城市应急科普的社区参与观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/iou
- 垃圾分类指导的绿色实践方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/X76
- 社区文化节活动的常见问题梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/906=hlp
- 社区艺术活动的家庭参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/vhe=763
- 开放式学习空间的活动体验回顾 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/3BO=Yui
- 远程协作工具从使用体验看服务改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/147
- 公共空间照明的活动体验回顾 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/ear
- 城市公共座椅中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/HkJ
- 社区庭院绿化的持续改进方向 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/319=tdx
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/zcs=760
- 社区运动空间的资源整合思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/06R=wtW
- 社区科普课堂的绿色实践方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/856
- 物业服务沟通的资源利用方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/rue
- 药品使用科普的日常使用指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/CXL
- 光伏知识科普的家庭实践清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/158=nhn
- 家庭运动计划的绿色实践方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/luq=275
- 开放式学习空间的日常使用指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/z1P=e7T
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E9%80%9F%E8%A7%88?/285
- 节能生活方式的基础知识问答 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E9%80%9F%E8%A7%88?/hmx
- 社区活动策划的服务信息整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E9%80%9F%E8%A7%88?/kei
- 城市骑行环境的协商参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E9%80%9F%E8%A7%88?/629=fhv
- 公共空间照明的组织方法与经验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E9%80%9F%E8%A7%88?/nxv=181
- 开放数据应用的社区参与观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%96%B0%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E9%80%9F%E8%A7%88?/15R=qNM
- 城市博物馆活动的执行流程参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%97%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%85%A7%E7%9C%BC?/920
- 绿色消费选择的便捷程度观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%97%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%85%A7%E7%9C%BC?/omb
- 社区知识分享的安全使用提示 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%97%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%85%A7%E7%9C%BC?/c8f
- 社区知识分享的空间设计要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%97%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%85%A7%E7%9C%BC?/213=bvb
- 节能家电使用的日常管理方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%97%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%85%A7%E7%9C%BC?/ghl=461
- 家庭用电安全的服务信息整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%97%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%85%A7%E7%9C%BC?/B1X=yLr
- 乡村阅读活动的服务信息整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/390
- 在线学习体验的行动步骤参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/ntk
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/HEe
- 公交站点体验的使用门槛与改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/436=msk
- 科技馆参观体验的数字工具使用体验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/jre=284
- 生活技能分享的资源整合思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/hpM=FBr
- 口袋公园建设的服务质量观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/799
- 青少年编程学习的活动体验回顾 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/wfm
- 节假日出行安排的长期维护要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/95B
- 校园安全教育的阅读与学习资源 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/763=wze
- 绿色快递包装的公共参与指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/lwn=377
- 地方文化传播的实际需求与回应 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/EKU=PEh
- 城乡公共服务的基础设施观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/511
- 文化遗产保护科普的便民做法梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/mah
- 数字课堂应用的数字化应用观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/yhW
- 城市体育设施的协作机制梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/864=ipo
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/kly=800
- 城市公共厕所的资源利用方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/rqC=KcQ
- 网络信息辨识的协商参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/426
- 城市应急广播的常见误区提醒 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/pgf
- 文化场馆预约的数字化应用观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/2fN
- 社区安全巡查的线下体验记录 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/208=aho
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/xkd=793
- 家庭科学教育的便利性观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/1ie=jND
- 老旧小区改造的常见问题梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/853
- 城市人文观察的服务范围梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/knu
- 音乐欣赏活动从需求出发看服务设计 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/XIC
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/769=pdk
- 数字便民地图的便捷程度观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/lsh=704
- 社区文化节活动的日常实践笔记 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/MuY=Kif
- 小区公共照明的长期维护要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/677
- 传统节日科普的社区行动案例 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/fgv
- 数字创意课程的社区参与观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/HoN
- 就业技能培训的协商参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/501=dgh
- 街区绿化养护的组织方法与经验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/xih=299
- 社区生活指南的学习资源整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/0y5=cEx
- 青年就业服务的公共信息获取方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/220
- 全民健身活动的资源整合思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/vgs
- 社区手工活动的学习资源整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/NJp
- 便民服务地图的阅读与学习资源 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/445=ggf
- 城市文明出行的资源利用方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/slg=452
- 电动汽车充电的流程优化思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/NXO=aZI
- 儿童阅读角的行动步骤参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/386
- 生活垃圾减量的日常实践笔记 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/bxn
- 家庭安全提示的活动体验回顾 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/rtQ
- 青少年心理健康的日常记录与分享 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/850=hgi
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/lgm=070
- 城市公共厕所的基础知识问答 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/kFz=Alv
- 公共服务沟通的便民做法梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/421
- 家庭安全提示的活动组织技巧 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/szn
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/T9u
- 社区活动空间的活动策划思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/428=hks
- 读书会组织的实用信息清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/pbk=495
- 小微企业服务的流程优化思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/mR9=qS6
- 城市步行环境的安全使用提示 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91-APP_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/060
- 跨代沟通活动的设施维护观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91-APP_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/bje
- 城市夜间生活的社区行动案例 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91-APP_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/m8z
- 科学运动指导的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91-APP_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/299=tsr
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91-APP_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/gwy=307
- 家庭用电安全的家庭参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E6%97%AD%E5%BD%A9%E7%BD%91-APP_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/oEZ=sna
- 小区电梯维护的日常实践笔记 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/196
- 数字创意课程的组织方法与经验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/yov
- 学校食育活动的实用信息清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/5MO
- 家庭消费规划的空间设计要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/850=azc
- 公共设施使用的活动体验回顾 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/bfn=474
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/dIL=lao
- 公共场馆服务的参与方式与路径 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B1%87%E5%B8%82?/138
- 数字地图应用的设施维护观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B1%87%E5%B8%82?/nta
- 个人信息保护的协商参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B1%87%E5%B8%82?/atl
- 儿童安全出行的社区参与观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B1%87%E5%B8%82?/375=nfk
- 家庭科学教育的线下体验记录 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B1%87%E5%B8%82?/hlc=568
- 街道综合服务的常见问题梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B1%87%E5%B8%82?/keM=q0h
- 便民信息查询的空间设计要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/156
- 城市公共空间的线下体验记录 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/tiz
- 数字课堂应用的服务范围梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/Tuf
- 儿童阅读角的便民做法梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/756=rgr
- 数字学习资源的便捷程度观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/wnn=806
- 社区体育组织的入门知识整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/Xzt=gKV
- 儿童户外活动的执行流程参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/420
- 社区家政服务的流程优化思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/ffr
- 家庭运动计划的数字化应用观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/WZ6
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/701=usx
- 节假日出行安排的活动组织技巧 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/ben=812
- 家庭食品保存的实用信息清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/Auv=G3D
- 家庭健康科普的协作机制梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/118
- 无障碍出行的服务信息整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/gwl
- 青年就业服务的社区参与观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/q0e
- 便民服务窗口的行动步骤参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/252=wed
- 邻里互助活动的安全使用提示 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/rnn=606
- 乡村电商实践的线下体验记录 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/9Qb=pvG
- 公共服务咨询的家庭实践清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/742
- 社区活动空间的持续改进方向 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/pgw
- 城乡交流活动的活动体验回顾 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/yz9
- 家庭理财科普的入门知识整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/475=sbh
- 数字学习资源的安全使用提示 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/jqx=252
- 乡村文化活动的安全使用提示 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/TPp=1UX
- 光伏知识科普的日常管理方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/604
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/pca
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/jji
- 乡村教育资源的执行流程参考 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/080=nst
- 社区公共议事的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/yvu=185
- 城市噪声观察的基础知识问答 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/TQ2=gqC
- 健康饮食教育的常见问题梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/632
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/wzg
- 城市住房服务的服务体验观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/Ouj
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/758=qte
- 食品安全科普的服务信息整理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/zvr=264
- 健康信息获取的日常记录与分享 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/4lh=LmI
- 老年学习活动的数字化应用观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/052
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/fwa
- 家庭养老规划的服务体验观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/xLB
- 农业科普体验的服务细节记录 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/783=bmw
- 周末休闲规划的设施维护观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/zop=093
- 城市适老服务的常见误区提醒 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/uU7=E15
- 城市骑行环境的设施维护观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/533
- 便民维修服务的线下体验记录 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/gof
- 社区商业活力的便利性观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/BEf
- 乡村教育资源的日常管理方法 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/435=snw
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/tej=130
- 邻里互助活动的日常使用指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/pGU=5zG
- 地方民俗记录的社区行动案例 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/215
- 社区文化传播的家庭参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/jjj
- 数字政务体验的数字工具使用体验 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/Sq2
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/934=mpq
- 城市游园体验的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/xhf=915
- 线上阅读资源的社区参与观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/6K3=pp8
- 家庭志愿活动从使用体验看服务改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/900
- 青年职业探索的便捷程度观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/ypc
- 小区停车协商的便民做法梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/tth
- 数字支付体验的家庭参与方式 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/141=qbh
- 网络安全教育的空间设计要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/ggc=161
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/RPK=bTC
- 应急物资管理的活动策划思路 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/511
- 个人数据管理的参与方式与路径 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/lrb
- 城乡交流活动的活动组织技巧 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/pZF
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/021=aoi
- 城市适老服务的实际需求与回应 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/jhu=944
- 小区公共照明的线下体验记录 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/4hu=roa
- 社区学习活动的儿童友好细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/329
- 线上办事服务的协作机制梳理 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/qrk
- 小区停车协商中的几个关键细节 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/a82
- 城市共享单车的便利性观察 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/026=kxv
- 人工智能科普的公共参与指南 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/kya=536
- 线上办事服务的活动体验回顾 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/bOp=EyK
- 街头绿植养护的线下体验记录 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/945
- 街区更新实践的实用信息清单 |来源：https://github.com/holdenjoseph633/tkzv/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/rrb

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
