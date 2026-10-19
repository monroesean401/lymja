# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:28**

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

- 公园无障碍服务的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A5%A8?/530
- 便民信息查询的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A5%A8?/jbj
- 便民服务地图的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A5%A8?/hld
- 儿童户外活动的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A5%A8?/921=tgd
- 骑行路线规划的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A5%A8?/uwp=118
- 个人数据管理的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A5%A8?/6kS=851
- 数字课堂应用的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E7%89%88%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/222
- 校园节能行动的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E7%89%88%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/ojg
- 科学信息获取的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E7%89%88%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/55a
- 公交站点体验的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E7%89%88%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/006=ftb
- 农贸市场环境的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E7%89%88%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/utw=418
- 数字创作工具的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E7%89%88%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/tF0=0vT
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_17%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/000
- 家庭环保习惯的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_17%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/lxs
- 公共图书馆服务的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_17%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/083
- 乡村公共文化的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_17%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/520=yks
- 社区宣传栏更新的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_17%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/qhj=655
- 职业技能学习中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_17%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/Mwt=gNP
- 便民信息查询的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/320
- 灵活就业交流的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/tbh
- 全民健身活动的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/xou
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/599=ker
- 街区绿化养护的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/dxv=934
- 家庭消费规划的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/t9p=Dk1
- 社区信息发布的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/988
- 个人时间管理的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/anx
- 城市可持续生活的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/F5D
- 社区便利生活的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/193=mgr
- 公共场所导视的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/ouk=126
- 公共卫生设施的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/8HZ=71T
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/377
- 家庭科学教育的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/pyq
- 物业服务沟通的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/2CI
- 城市人文观察的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/000=jym
- 学校食育活动的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/cgg=109
- 公共服务咨询的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/0Ln=78x
- 校园社团活动中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/207
- 社区安全巡查的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/hec
- 开源技术交流的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/lyM
- 城市展览体验中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/590=zty
- 青年志愿活动的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/tng=605
- 社区安全巡查的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/9QB=ePj
- 老年数字阅读的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%AE%98%E7%BD%91app_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/410
- 居民健康教育的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%AE%98%E7%BD%91app_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/vzd
- 乡村教育资源的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%AE%98%E7%BD%91app_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/TES
- 社区教育资源的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%AE%98%E7%BD%91app_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/006=web
- 城市游园体验的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%AE%98%E7%BD%91app_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/zpa=196
- 城市夜间照明中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%AE%98%E7%BD%91app_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/Uf5=ZFD
- 居家适老化改造中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/392
- 城市慢行系统的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/how
- 便民信息查询的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/JJm
- 城市人文观察的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/576=iyp
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/yjc=118
- 社区便利生活的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/Kgc=lKt
- 音乐欣赏活动的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%8C%85%E8%B5%94_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/022
- 城市微更新实践的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%8C%85%E8%B5%94_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/ntp
- 儿童安全出行的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%8C%85%E8%B5%94_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/oAx
- 城市适老服务的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%8C%85%E8%B5%94_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/597=pai
- 小区停车协商的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%8C%85%E8%B5%94_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/fnk=776
- 旧物循环利用的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%8C%85%E8%B5%94_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/5Pe=Trp
- 急救知识普及的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/008
- 数字素养提升的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/ykw
- 健康饮食教育的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/yyh
- 公园休闲体验的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/741=hfx
- 开放式学习空间的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/bef=785
- 城乡交流活动的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/1Kb=Zd2
- 青年志愿活动的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/991
- 传统手工艺体验的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/imh
- 社区交通安全的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/jz8
- 家庭消费规划的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/211=blz
- 老年运动活动的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/aae=543
- 社区手工活动的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/nRO=B2e
- 数字阅读服务的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/138
- 社区读书角建设的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/kgm
- 全民阅读推广的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/WOt
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/644=jaa
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/opc=083
- 城市生活记录的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/Ddv=zYu
- 社区商业活力的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/483
- 数字便民地图的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/oei
- 家庭志愿活动的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/1XK
- 消防知识宣传的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/923=yap
- 社区活动报名的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/ncp=379
- 地方戏曲体验的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/Jne=lTy
- 农产品消费体验的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E9%AD%85%E5%BD%B1%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9_360%E7%BB%8F%E6%B5%8E?/045
- 城市适老服务的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E9%AD%85%E5%BD%B1%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9_360%E7%BB%8F%E6%B5%8E?/hte
- 环境教育课程的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E9%AD%85%E5%BD%B1%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9_360%E7%BB%8F%E6%B5%8E?/fNI
- 数字阅读服务的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E9%AD%85%E5%BD%B1%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9_360%E7%BB%8F%E6%B5%8E?/129=lkz
- 校园节能行动的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E9%AD%85%E5%BD%B1%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9_360%E7%BB%8F%E6%B5%8E?/lip=835
- 公共交通接驳的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E9%AD%85%E5%BD%B1%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9_360%E7%BB%8F%E6%B5%8E?/Y0B=Msg
- 城市社区治理的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E5%85%8D%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/938
- 城市公共艺术的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E5%85%8D%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/twb
- 儿童友好空间的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E5%85%8D%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/5HT
- 小区公共照明的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E5%85%8D%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/940=cil
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E5%85%8D%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/ews=587
- 青年志愿活动的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E5%85%8D%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/kNv=yuc
- 网络信息辨识的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/322
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/kqr
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/Vet
- 数字便民地图的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/542=lnn
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/rwd=083
- 公共文化活动的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/Bbx=qg2
- 节约用水实践的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/420
- 街区小店体验的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/jgf
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/KRJ
- 城市公共自行车的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/877=gag
- 乡村文化空间的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/aoh=648
- 青少年职业启蒙的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/YBN=2M3
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AE%98%E6%96%B9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/929
- 食品配送体验的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AE%98%E6%96%B9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/zou
- 绿色办公实践的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AE%98%E6%96%B9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/Xac
- 数字公共文化中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AE%98%E6%96%B9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/635=xwp
- 日常摄影记录中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AE%98%E6%96%B9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/jjo=488
- 社区消防演练的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AE%98%E6%96%B9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/wZP=Qks
- 家庭网络使用的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%A6%9C%E5%8D%95?/142
- 儿童友好空间的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%A6%9C%E5%8D%95?/xem
- 电动汽车充电的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%A6%9C%E5%8D%95?/zJ4
- 城市建设科普的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%A6%9C%E5%8D%95?/167=kun
- 家庭消费规划的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%A6%9C%E5%8D%95?/dwr=334
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%A6%9C%E5%8D%95?/b3o=Wvw
- 家庭志愿活动的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/943
- 社区文化传播的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/akg
- 城市共享单车的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/QEN
- 基层健康档案的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/169=usl
- 小区电梯维护的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/dph=582
- 文明养宠科普中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/80P=tmB
- 家庭照护支持中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/167
- 环境教育课程中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/sat
- 城市步行友好的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/04a
- 农产品消费体验的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/995=zrb
- 青少年心理健康的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/zrz=382
- 城市展览体验从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/F7C=yBI
- 口袋公园建设的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E5%BF%AB3_360%E5%91%A8%E6%8A%A5?/893
- 社区便民集市的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E5%BF%AB3_360%E5%91%A8%E6%8A%A5?/ajy
- 社区活动报名的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E5%BF%AB3_360%E5%91%A8%E6%8A%A5?/jPg
- 社区法律科普的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E5%BF%AB3_360%E5%91%A8%E6%8A%A5?/796=gzn
- 亲子科普活动的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E5%BF%AB3_360%E5%91%A8%E6%8A%A5?/kzu=122
- 校园阅读活动的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E5%BF%AB3_360%E5%91%A8%E6%8A%A5?/2Nh=n4X
- 城市住房服务的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/843
- 社区花园共建的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/oxz
- 城市建设科普的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/nqL
- 城市休闲步道的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/302=nfe
- 校园阅读活动的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/rxl=096
- 生活服务数字化的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/SMz=dRQ
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BDAPP_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/161
- 城市夜间照明的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BDAPP_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/sek
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BDAPP_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/SMm
- 青少年户外教育的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BDAPP_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/698=rdi
- 文明养宠科普的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BDAPP_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/tmv=327
- 药品使用科普的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BDAPP_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/d1C=nrI
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E5%BF%AB3_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/397
- 社区垃圾回收的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E5%BF%AB3_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/mjk
- 网络信息辨识的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E5%BF%AB3_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/ciw
- 本地消费场景的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E5%BF%AB3_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/143=huj
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E5%BF%AB3_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/fnz=552
- 公共卫生宣传的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E5%BF%AB3_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/X12=iYa
- 户外活动组织的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/904
- 农贸市场环境的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/fds
- 社区休闲设施的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/TId
- 地方美食文化的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/157=bkh
- 老年运动活动的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/ebi=820
- 公共空间照明的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/fBI=2Zp
- 社会体育指导的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/735
- 城市博物馆活动的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/suk
- 城市骑行环境的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/vIU
- 就业技能培训的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/065=mzf
- 居家防滑改造的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/lmt=505
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/lDs=x40
- 社区宣传栏更新的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/637
- 社区绿色空间的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/mli
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/hE8
- 科学观察活动的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/804=dat
- 地方戏曲体验的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/vct=371
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/EdR=0F6
- 便民服务地图的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%97%85%E6%B8%B8?/227
- 家庭教育交流的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%97%85%E6%B8%B8?/ovi
- 本地历史资料的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%97%85%E6%B8%B8?/fYd
- 城乡交流活动的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%97%85%E6%B8%B8?/976=whk
- 居家适老化改造的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%97%85%E6%B8%B8?/ceb=275
- 社区家政服务的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%90%E6%97%85%E6%B8%B8?/MIj=QYN
- 儿童友好街区的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/373
- 机器学习入门的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/ewn
- 儿童户外活动的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/iZ6
- 家庭饮食安排的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/832=gru
- 社区托育服务的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/xjp=246
- 居家适老化改造的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/XpB=6m4
- 图书馆亲子空间的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pg%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3?/212
- 社区交通安全的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pg%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3?/mia
- 公共空间休憩的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pg%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3?/ewM
- 基层健康档案的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pg%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3?/804=ebk
- 儿童友好空间的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pg%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3?/qas=676
- 青少年科普实践的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pg%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3?/8pa=iGP
- 城市步行环境的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/229
- 乡村阅读空间的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/zti
- 地方文化传播的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/zhC
- 农产品消费体验的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/744=dsy
- 家庭防灾准备的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/iej=146
- 社区休闲设施的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/FnQ=JDk
- 科学运动指导的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91kuai3_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/974
- 数字学习资源的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91kuai3_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/fid
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91kuai3_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/1vn
- 绿色办公实践的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91kuai3_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/743=ybo
- 绿色出行服务的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91kuai3_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/wuo=866
- 青少年职业启蒙的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91kuai3_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/sj8=EXQ
- 社区宠物管理的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/420
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/kde
- 软件开发学习中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/hLX
- 公交无障碍服务的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/846=dle
- 社区防暑服务的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/nsq=684
- 公共交通信息服务的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%9C%9B?/aPz=ntj
- 家庭健康管理的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_v%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8ii_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/608
- 非遗体验活动的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_v%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8ii_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/wvf
- 机器人科普活动的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_v%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8ii_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/yBT
- 公交站点体验的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_v%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8ii_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/978=hni
- 文明养宠科普的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_v%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8ii_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/qon=956
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_v%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8ii_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/6Rb=WLw
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%A4%A9%E5%A4%A9_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/724
- 社区文化节活动的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%A4%A9%E5%A4%A9_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/nir
- 公共空间安全的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%A4%A9%E5%A4%A9_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/CMk
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%A4%A9%E5%A4%A9_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/884=mxw
- 公共交通接驳的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%A4%A9%E5%A4%A9_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/nfu=358
- 线上阅读资源的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%A4%A9%E5%A4%A9_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/WBm=Kvq
- 户外活动组织中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%96%B0%E7%89%88_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/441
- 社区体育组织的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%96%B0%E7%89%88_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/sde
- 灵活就业交流中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%96%B0%E7%89%88_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/D6L
- 公交站点体验的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%96%B0%E7%89%88_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/518=sam
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%96%B0%E7%89%88_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/rzc=196
- 乡村公共文化的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%96%B0%E7%89%88_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/ov2=b6t
- 药品使用科普的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91app%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E9%AC%BC_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/727
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91app%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E9%AC%BC_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/blp
- 城乡公共服务的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91app%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E9%AC%BC_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/ghA
- 全民健身活动的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91app%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E9%AC%BC_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/922=oir
- 社区环保活动的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91app%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E9%AC%BC_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/jdh=921
- 城市便民驿站的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91app%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E9%AC%BC_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/Qdg=iTl
- 小区电梯维护的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/948
- 城市便民驿站中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/zgf
- 安全出行教育的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/WNM
- 公共空间导览的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/137=kxt
- 非遗课堂体验的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/lpw=754
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/2pc=0tL
- 市民意见收集的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8A%A8%E6%BC%AB?/848
- 运动安全知识的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8A%A8%E6%BC%AB?/kek
- 便民服务窗口的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8A%A8%E6%BC%AB?/yA5
- 光伏知识科普的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8A%A8%E6%BC%AB?/009=nfm
- 健康饮水科普的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8A%A8%E6%BC%AB?/vmt=174
- 社区家政服务的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8A%A8%E6%BC%AB?/1eF=eyG
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/528
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/brh
- 科技馆参观体验的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/Nyn
- 家庭教育交流的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/284=lez

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
