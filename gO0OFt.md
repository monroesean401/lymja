# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:31**

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

- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_3d%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/hec=227
- 公园亲子设施的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_3d%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/OHz=8U4
- 绿色办公实践的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_3d%E9%A2%84%E6%B5%8B%E6%9D%80%E5%8F%B7_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/468
- 生活服务数字化的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_3d%E9%A2%84%E6%B5%8B%E6%9D%80%E5%8F%B7_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/vlo
- 农产品消费体验的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_3d%E9%A2%84%E6%B5%8B%E6%9D%80%E5%8F%B7_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/lfS
- 户外活动组织的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_3d%E9%A2%84%E6%B5%8B%E6%9D%80%E5%8F%B7_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/432=kbr
- 乡村电商实践的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_3d%E9%A2%84%E6%B5%8B%E6%9D%80%E5%8F%B7_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/ead=603
- 数字素养提升的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_3d%E9%A2%84%E6%B5%8B%E6%9D%80%E5%8F%B7_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/cPe=Bpo
- 户外活动组织的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_3d%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/706
- 公共服务指南的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_3d%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/szf
- 城市雨天出行的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_3d%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/D7N
- 城市夜间照明的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_3d%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/359=vqi
- 儿童安全出行的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_3d%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/ckj=266
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_3d%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/zmO=aPR
- 节假日出行安排的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E4%BB%8A%E5%A4%A9_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/166
- 儿童运动体验的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E4%BB%8A%E5%A4%A9_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/hbh
- 传统节日科普的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E4%BB%8A%E5%A4%A9_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/8EO
- 公共服务预约的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E4%BB%8A%E5%A4%A9_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/869=ruy
- 社区慢性病防控从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E4%BB%8A%E5%A4%A9_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/dxf=758
- 数字支付体验的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E4%BB%8A%E5%A4%A9_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/Sno=KGC
- 青少年心理健康的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_3d%E4%BB%8A%E6%99%9A%E9%A2%84%E6%B5%8B_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/379
- 家庭网络使用的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_3d%E4%BB%8A%E6%99%9A%E9%A2%84%E6%B5%8B_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/ggu
- 社区应急准备的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_3d%E4%BB%8A%E6%99%9A%E9%A2%84%E6%B5%8B_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/fq9
- 本地消费场景的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_3d%E4%BB%8A%E6%99%9A%E9%A2%84%E6%B5%8B_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/159=clm
- 社区故事采集的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_3d%E4%BB%8A%E6%99%9A%E9%A2%84%E6%B5%8B_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/iff=118
- 全民健身活动的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_3d%E4%BB%8A%E6%99%9A%E9%A2%84%E6%B5%8B_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/Jzx=6M7
- 社区设施共享的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_3d%E4%BB%8A%E6%99%9A%E5%BC%80%E5%A5%96%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/165
- 社区商业活力中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_3d%E4%BB%8A%E6%99%9A%E5%BC%80%E5%A5%96%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/nsg
- 数字公共文化的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_3d%E4%BB%8A%E6%99%9A%E5%BC%80%E5%A5%96%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/M1v
- 邻里互助活动的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_3d%E4%BB%8A%E6%99%9A%E5%BC%80%E5%A5%96%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/575=pfl
- 科学教育活动中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_3d%E4%BB%8A%E6%99%9A%E5%BC%80%E5%A5%96%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/olc=309
- 家庭教育交流的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_3d%E4%BB%8A%E6%99%9A%E5%BC%80%E5%A5%96%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/hH7=zTw
- 乡村公共阅读的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_3d%E8%83%86%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/382
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_3d%E8%83%86%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/ijy
- 城市慢行系统的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_3d%E8%83%86%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/Zop
- 休闲运动入门的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_3d%E8%83%86%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/074=wwg
- 青少年心理健康的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_3d%E8%83%86%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/eku=227
- 文化场馆预约的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_3d%E8%83%86%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/5Wy=VRp
- 科学观察活动的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_3d%E8%83%86%E7%A0%81%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/152
- 农村环境治理的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_3d%E8%83%86%E7%A0%81%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/enw
- 生活服务数字化的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_3d%E8%83%86%E7%A0%81%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/yG1
- 城市骑行环境的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_3d%E8%83%86%E7%A0%81%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/342=und
- 节假日出行安排的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_3d%E8%83%86%E7%A0%81%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/mya=306
- 公共空间导览的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_3d%E8%83%86%E7%A0%81%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/D8v=835
- 社区活动报名的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/225
- 本地历史资料的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/kmw
- 开放式学习空间的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/8H1
- 城市应急广播的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/635=mwm
- 社区文化传播的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/kmw=418
- 基层服务创新的日常管理方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/z7u=xSH
- 节气饮食文化的资源整合思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_3d%E8%83%86%E7%A0%81%E5%9B%BE_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/601
- 街道综合服务的常见误区提醒 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_3d%E8%83%86%E7%A0%81%E5%9B%BE_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/udw
- 街头绿植养护的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_3d%E8%83%86%E7%A0%81%E5%9B%BE_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/ADX
- 生活技能分享的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_3d%E8%83%86%E7%A0%81%E5%9B%BE_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/029=hyb
- 小区电梯维护的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_3d%E8%83%86%E7%A0%81%E5%9B%BE_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/stz=237
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_3d%E8%83%86%E7%A0%81%E5%9B%BE_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/izn=OPq
- 在线教育体验的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_3d%E8%83%86%E7%A0%81%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%97%E4%BF%A1%E6%89%98?/953
- 图书借阅体验的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_3d%E8%83%86%E7%A0%81%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%97%E4%BF%A1%E6%89%98?/vkd
- 急救知识普及的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_3d%E8%83%86%E7%A0%81%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%97%E4%BF%A1%E6%89%98?/I91
- 在线教育体验的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_3d%E8%83%86%E7%A0%81%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%97%E4%BF%A1%E6%89%98?/840=rnr
- 公共空间安全的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_3d%E8%83%86%E7%A0%81%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%97%E4%BF%A1%E6%89%98?/hpz=972
- 社区儿童活动的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_3d%E8%83%86%E7%A0%81%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%97%E4%BF%A1%E6%89%98?/9Vq=w1A
- 城市公共饮水的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E8%83%86%E7%A0%81%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/730
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E8%83%86%E7%A0%81%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/xmi
- 公共空间照明的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E8%83%86%E7%A0%81%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/c0Q
- 社区志愿服务的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E8%83%86%E7%A0%81%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/111=kmb
- 老年运动活动的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E8%83%86%E7%A0%81%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/fth=407
- 个人数据管理的阅读与学习资源 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3d%E8%83%86%E7%A0%81%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/FRv=VFn
- 新能源知识普及的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E6%8E%92%E5%BA%8F_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/107
- 小区公共照明的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E6%8E%92%E5%BA%8F_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/uws
- 数字艺术创作中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E6%8E%92%E5%BA%8F_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/6bd
- 青少年科技社团的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E6%8E%92%E5%BA%8F_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/574=mbs
- 社区菜市场服务的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E6%8E%92%E5%BA%8F_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/eds=607
- 数字设备回收的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E6%8E%92%E5%BA%8F_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/bmU=xg7
- 城市文化路线的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_3d%E8%83%86%E7%A0%81%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%80%BA%E5%B8%82?/628
- 市民热线服务的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_3d%E8%83%86%E7%A0%81%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%80%BA%E5%B8%82?/amu
- 本地消费场景的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_3d%E8%83%86%E7%A0%81%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%80%BA%E5%B8%82?/OqO
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_3d%E8%83%86%E7%A0%81%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%80%BA%E5%B8%82?/110=oux
- 街区道路维护的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_3d%E8%83%86%E7%A0%81%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%80%BA%E5%B8%82?/zjf=987
- 通勤路线规划的常见问题梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_3d%E8%83%86%E7%A0%81%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%80%BA%E5%B8%82?/MrX=Rii
- 便民服务地图的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_3d%E8%83%86%E7%A0%81%E6%8A%95%E6%B3%A8_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/870
- 城市噪声观察的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_3d%E8%83%86%E7%A0%81%E6%8A%95%E6%B3%A8_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/jge
- 社区垃圾回收的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_3d%E8%83%86%E7%A0%81%E6%8A%95%E6%B3%A8_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/XGP
- 户外活动组织的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_3d%E8%83%86%E7%A0%81%E6%8A%95%E6%B3%A8_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/074=rin
- 社区快递服务的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_3d%E8%83%86%E7%A0%81%E6%8A%95%E6%B3%A8_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/vzp=592
- 社区安全巡查的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_3d%E8%83%86%E7%A0%81%E6%8A%95%E6%B3%A8_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/bEw=8EK
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/920
- 社区应急准备的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/bnj
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/YDn
- 社区生活指南的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/442=zgz
- 数字设备回收的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/mxz=626
- 城市公共厕所的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3d%E8%83%86%E7%A0%81%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/GiB=MVf
- 口袋公园建设的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%87%86%E5%AE%9A%E4%BD%8D100%25_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/100
- 社区法律科普的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%87%86%E5%AE%9A%E4%BD%8D100%25_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/wlt
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%87%86%E5%AE%9A%E4%BD%8D100%25_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/JtS
- 地方民俗记录的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%87%86%E5%AE%9A%E4%BD%8D100%25_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/655=swa
- 老年人日常照护的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%87%86%E5%AE%9A%E4%BD%8D100%25_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/gzi=051
- 健康步道使用的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%87%86%E5%AE%9A%E4%BD%8D100%25_%E5%87%A4%E5%87%B0%E8%81%8C%E5%9C%BA?/iIx=suW
- 公共空间安全的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86100_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/387
- 地方旅游导览的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86100_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/dzw
- 安全出行教育的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86100_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/VXI
- 社区交通安全的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86100_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/200=bnx
- 生活垃圾回收的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86100_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/nje=214
- 智能家居应用的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86100_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/o8z=4KD
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3d%E6%9C%80%E5%87%86%E4%B8%AD%E5%A5%96%E7%9A%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/527
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3d%E6%9C%80%E5%87%86%E4%B8%AD%E5%A5%96%E7%9A%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/cvq
- 城市建设科普中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3d%E6%9C%80%E5%87%86%E4%B8%AD%E5%A5%96%E7%9A%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/l8c
- 城市应急广播的长期维护要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3d%E6%9C%80%E5%87%86%E4%B8%AD%E5%A5%96%E7%9A%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/469=hsy
- 节能家电使用的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3d%E6%9C%80%E5%87%86%E4%B8%AD%E5%A5%96%E7%9A%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/brh=277
- 家庭网络使用的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_3d%E6%9C%80%E5%87%86%E4%B8%AD%E5%A5%96%E7%9A%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/LDe=rdD
- 老年学习活动的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_3d%E9%80%89%E5%8F%B7%E8%BF%87%E6%BB%A4%E5%99%A8_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/997
- 社区垃圾分类的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_3d%E9%80%89%E5%8F%B7%E8%BF%87%E6%BB%A4%E5%99%A8_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/xhj
- 生成式工具使用的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_3d%E9%80%89%E5%8F%B7%E8%BF%87%E6%BB%A4%E5%99%A8_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/K9R
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_3d%E9%80%89%E5%8F%B7%E8%BF%87%E6%BB%A4%E5%99%A8_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/776=asd
- 地方旅游导览的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_3d%E9%80%89%E5%8F%B7%E8%BF%87%E6%BB%A4%E5%99%A8_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/jnt=332
- 青年志愿活动的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_3d%E9%80%89%E5%8F%B7%E8%BF%87%E6%BB%A4%E5%99%A8_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/i8p=HMg
- 社区防暑服务的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%B9%BF%E4%B8%9C11%E9%80%895%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/165
- 数字设备回收的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%B9%BF%E4%B8%9C11%E9%80%895%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/clp
- 公共图书馆服务的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%B9%BF%E4%B8%9C11%E9%80%895%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/1ru
- 公共空间照明的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%B9%BF%E4%B8%9C11%E9%80%895%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/321=cvz
- 儿童安全出行的入门知识整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%B9%BF%E4%B8%9C11%E9%80%895%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/cmm=000
- 社区交通安全的日常使用指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%B9%BF%E4%B8%9C11%E9%80%895%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/dSg=F9C
- 城市公共艺术的设施维护观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/046
- 公园亲子设施中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/ydd
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/57B
- 就业技能培训中的几个关键细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/176=yzg
- 公园亲子设施的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/tqx=835
- 儿童安全出行的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/04w=zdl
- 公园休闲体验的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_15%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E9%AB%98%E6%89%8B_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/026
- 地方民俗记录的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_15%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E9%AB%98%E6%89%8B_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/fow
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_15%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E9%AB%98%E6%89%8B_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/E1U
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_15%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E9%AB%98%E6%89%8B_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/335=inc
- 医院导诊服务的便民做法梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_15%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E9%AB%98%E6%89%8B_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/lss=345
- 城市公共饮水的儿童友好细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_15%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E9%AB%98%E6%89%8B_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/ibl=Nhx
- 音乐欣赏活动的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%9420%E5%88%86%E9%92%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/713
- 社区志愿服务的学习资源整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%9420%E5%88%86%E9%92%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/ukb
- 图书馆活动策划的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%9420%E5%88%86%E9%92%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/ZTx
- 校园节能行动的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%9420%E5%88%86%E9%92%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/732=shn
- 图书馆数字服务有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%9420%E5%88%86%E9%92%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/ejp=967
- 城市适老服务的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%9420%E5%88%86%E9%92%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/i7f=im3
- 城市人文观察的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/801
- 农贸市场环境的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/xpk
- 市民意见收集的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/8jP
- 网络信息辨识的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/080=gbb
- 农贸市场环境的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/kup=168
- 城市共享单车的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/p2f=qok
- 城市公共座椅的行动步骤参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%B9%BF%E4%B8%9C%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/460
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%B9%BF%E4%B8%9C%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/krm
- 气象科普传播的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%B9%BF%E4%B8%9C%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/pI7
- 老旧小区改造的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%B9%BF%E4%B8%9C%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/621=hvu
- 城市夜间照明的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%B9%BF%E4%B8%9C%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/sfy=877
- 乡村教育资源的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%B9%BF%E4%B8%9C%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/9Uh=2Jm
- 社区安全巡查的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/703
- 城市共享单车的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/rwf
- 公共服务沟通的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/ADA
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/124=zzf
- 城市公共标识的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/zro=910
- 乡村休闲旅游的活动策划思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/wss=5Ec
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%80%80%E5%B8%82_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/662
- 小区电梯维护的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%80%80%E5%B8%82_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/hte
- 传统节日科普的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%80%80%E5%B8%82_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/ckH
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%80%80%E5%B8%82_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/776=qmz
- 城市社区治理的空间使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%80%80%E5%B8%82_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/qqa=876
- 青少年户外教育的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%80%80%E5%B8%82_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/D1A=r0Q
- 城市可持续生活的空间设计要点 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/205
- 健康信息获取的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/rnr
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/2Z2
- 小区停车协商的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/909=iiy
- 城市夜间生活的日常记录与分享 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/rsl=977
- 数字公共文化中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/7ag=Wgi
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/709
- 绿色消费选择的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/mnp
- 社区文化节活动的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/OJy
- 本地旅行体验的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/262=hbc
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/qgp=602
- 城市游园体验的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/bsh=JzO
- 急救知识普及的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_11%E9%80%895%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/428
- 社区公共议事的服务质量观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_11%E9%80%895%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/vuu
- 社区体育组织的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_11%E9%80%895%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/vF4
- 城市博物馆服务的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_11%E9%80%895%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/977=uzt
- 城市共享单车的实用信息清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_11%E9%80%895%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/abz=482
- 城市应急广播中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_11%E9%80%895%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/sxn=bkr
- 图书馆数字服务的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_11%E9%80%895%E8%B5%9A%E5%B0%8F%E9%92%B1%E7%A7%98%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/494
- 公共健身器材的线下体验记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_11%E9%80%895%E8%B5%9A%E5%B0%8F%E9%92%B1%E7%A7%98%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/grw
- 儿童阅读角的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_11%E9%80%895%E8%B5%9A%E5%B0%8F%E9%92%B1%E7%A7%98%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/oTx
- 城市公共艺术的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_11%E9%80%895%E8%B5%9A%E5%B0%8F%E9%92%B1%E7%A7%98%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/729=jxa
- 城市社区治理的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_11%E9%80%895%E8%B5%9A%E5%B0%8F%E9%92%B1%E7%A7%98%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/vbt=599
- 社区阅读服务的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_11%E9%80%895%E8%B5%9A%E5%B0%8F%E9%92%B1%E7%A7%98%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/Fah=JWK
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_360%E5%8D%83%E5%B8%86?/980
- 市民热线服务的便利性观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_360%E5%8D%83%E5%B8%86?/upn
- 青少年科技社团的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_360%E5%8D%83%E5%B8%86?/Tom
- 数字创意课程从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_360%E5%8D%83%E5%B8%86?/270=oge
- 传统节日科普的参与方式与路径 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_360%E5%8D%83%E5%B8%86?/syo=249
- 基层服务创新的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_360%E5%8D%83%E5%B8%86?/6ey=yrz
- 社区手工活动的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/634
- 校园节能行动的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/bti
- 在线学习体验的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/dSg
- 城市生活记录的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/205=yvv
- 社区活动空间的日常实践笔记 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/nxh=445
- 公共空间休憩的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/wZl=OrS
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_11%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E4%B8%AD%E5%A5%96_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/219
- 社区快递服务的基础设施观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_11%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E4%B8%AD%E5%A5%96_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/wum
- 数字创意课程有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_11%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E4%B8%AD%E5%A5%96_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/Nst
- 城市人文观察的数字工具使用体验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_11%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E4%B8%AD%E5%A5%96_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/153=jmo
- 运动安全知识的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_11%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E4%B8%AD%E5%A5%96_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/fxq=762
- 儿童友好空间的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_11%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E4%B8%AD%E5%A5%96_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/AMW=hUb
- 公共服务评价的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_11%E9%80%89%E4%BA%94%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/770
- 老年人文化生活的服务体验观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_11%E9%80%89%E4%BA%94%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/fne
- 社区家校合作的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_11%E9%80%89%E4%BA%94%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/FTr
- 乡村产业科普的安全使用提示 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_11%E9%80%89%E4%BA%94%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/350=jxx
- 城市文明出行的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_11%E9%80%89%E4%BA%94%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/aar=348
- 志愿服务平台的执行流程参考 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_11%E9%80%89%E4%BA%94%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/1k3=V0U
- 乡村生态观察的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_11%E9%80%895%E8%B5%9A%E9%92%B1_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/532
- 公共服务预约的社区行动案例 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_11%E9%80%895%E8%B5%9A%E9%92%B1_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/iti
- 户外活动组织的实际需求与回应 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_11%E9%80%895%E8%B5%9A%E9%92%B1_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/gHA
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_11%E9%80%895%E8%B5%9A%E9%92%B1_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/398=pin
- 校园社团活动的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_11%E9%80%895%E8%B5%9A%E9%92%B1_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/bxi=671
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_11%E9%80%895%E8%B5%9A%E9%92%B1_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/vp3=ODn
- 全民阅读推广的公共参与指南 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_11%E9%80%895%E5%82%BB%E7%93%9C%E5%BC%8F%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/655
- 社区便民集市中的沟通与协作 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_11%E9%80%895%E5%82%BB%E7%93%9C%E5%BC%8F%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/ftt
- 基层健康服务的数字化应用观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_11%E9%80%895%E5%82%BB%E7%93%9C%E5%BC%8F%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/ygu
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_11%E9%80%895%E5%82%BB%E7%93%9C%E5%BC%8F%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/777=lgl
- 城市生活记录的活动组织技巧 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_11%E9%80%895%E5%82%BB%E7%93%9C%E5%BC%8F%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/uqe=976
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_11%E9%80%895%E5%82%BB%E7%93%9C%E5%BC%8F%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/frf=3nX
- 社区绿色空间的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_11%E9%80%895%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/463
- 气象科普传播的绿色实践方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_11%E9%80%895%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/lym
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_11%E9%80%895%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/J1n
- 本地消费场景的家庭实践清单 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_11%E9%80%895%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/030=ena
- 社区信息发布的协作机制梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_11%E9%80%895%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/gai=975
- 街区小店体验的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_11%E9%80%895%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/vdj=4A4
- 社区商业活力的持续改进方向 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_11%E9%80%895%E4%B8%87%E8%83%BD6%E7%A0%8140%E6%B3%A8_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/582
- 在线学习体验从需求出发看服务设计 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_11%E9%80%895%E4%B8%87%E8%83%BD6%E7%A0%8140%E6%B3%A8_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/ext
- 乡村公共文化的服务细节记录 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_11%E9%80%895%E4%B8%87%E8%83%BD6%E7%A0%8140%E6%B3%A8_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/UZW
- 城市公共座椅的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_11%E9%80%895%E4%B8%87%E8%83%BD6%E7%A0%8140%E6%B3%A8_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/304=qiy
- 便民服务窗口的活动体验回顾 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_11%E9%80%895%E4%B8%87%E8%83%BD6%E7%A0%8140%E6%B3%A8_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/dvf=937
- 环境教育课程的居民参与机会 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_11%E9%80%895%E4%B8%87%E8%83%BD6%E7%A0%8140%E6%B3%A8_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/SvP=nIT
- 软件开发学习的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%81%8C%E4%B8%9A11%E9%80%895%E9%AB%98%E6%89%8B%E4%B9%B0%E6%B3%95_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/166
- 农产品品牌传播的适老服务细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%81%8C%E4%B8%9A11%E9%80%895%E9%AB%98%E6%89%8B%E4%B9%B0%E6%B3%95_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/zjf
- 乡村生态旅游的服务信息整理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%81%8C%E4%B8%9A11%E9%80%895%E9%AB%98%E6%89%8B%E4%B9%B0%E6%B3%95_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/i4b
- 便民服务窗口的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%81%8C%E4%B8%9A11%E9%80%895%E9%AB%98%E6%89%8B%E4%B9%B0%E6%B3%95_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/655=qin
- 家庭用电安全的流程优化思路 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%81%8C%E4%B8%9A11%E9%80%895%E9%AB%98%E6%89%8B%E4%B9%B0%E6%B3%95_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/frh=258
- 城市文明实践的组织方法与经验 |来源：https://github.com/kleinjoseph07/cobv/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%81%8C%E4%B8%9A11%E9%80%895%E9%AB%98%E6%89%8B%E4%B9%B0%E6%B3%95_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/14E=4Vj
- 户外活动组织的服务范围梳理 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%85%A8%E5%A4%A9%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/093
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%85%A8%E5%A4%A9%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/bsk
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%85%A8%E5%A4%A9%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/2Hi
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%85%A8%E5%A4%A9%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/728=fus
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%85%A8%E5%A4%A9%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/pri=520
- 农贸市场环境的资源利用方法 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%85%A8%E5%A4%A9%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/jQS=hdz
- 社区生活指南的协商参与方式 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_11%E9%80%895%E6%9D%802%E4%B8%AA100%25%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/521
- 农村环境治理的便捷程度观察 |来源：https://github.com/kleinjoseph07/cobv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_11%E9%80%895%E6%9D%802%E4%B8%AA100%25%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/pvi

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
