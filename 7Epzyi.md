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

- 城市住房服务的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%85%BC%E8%81%8C_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/pI2
- 远程协作工具的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%85%BC%E8%81%8C_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/877=mcp
- 公共空间导览的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%85%BC%E8%81%8C_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/neu=245
- 公共空间安全的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%85%BC%E8%81%8C_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/54B=tNQ
- 社区活动报名的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%9A%E9%92%B1_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/003
- 线上阅读资源的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%9A%E9%92%B1_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/owv
- 公共场所导视的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%9A%E9%92%B1_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/Plj
- 图书馆活动策划的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%9A%E9%92%B1_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/329=cvg
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%9A%E9%92%B1_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/frn=834
- 数字学习资源的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%9A%E9%92%B1_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/Ncf=1cv
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/629
- 农产品品牌传播的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/eky
- 社区老年食堂的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/TUV
- 小区公共照明的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/260=jgm
- 公共服务指南的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/quz=879
- 生活技能分享的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/Deu=OoO
- 低碳社区实践的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E6%8A%95%E8%B5%84%E5%8D%81%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/573
- 休闲运动入门的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E6%8A%95%E8%B5%84%E5%8D%81%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/bob
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E6%8A%95%E8%B5%84%E5%8D%81%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/dCh
- 儿童阅读角的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E6%8A%95%E8%B5%84%E5%8D%81%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/779=pik
- 社区志愿服务的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E6%8A%95%E8%B5%84%E5%8D%81%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/vba=206
- 光伏知识科普的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E6%8A%95%E8%B5%84%E5%8D%81%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/Lzq=JMt
- 在线教育体验中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91%E5%8D%81%E5%88%86%E9%92%9F%E8%B5%9A800_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/202
- 节气饮食文化的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91%E5%8D%81%E5%88%86%E9%92%9F%E8%B5%9A800_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/hrd
- 老旧小区改造的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91%E5%8D%81%E5%88%86%E9%92%9F%E8%B5%9A800_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/l5g
- 健康步道使用的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91%E5%8D%81%E5%88%86%E9%92%9F%E8%B5%9A800_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/278=zaq
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91%E5%8D%81%E5%88%86%E9%92%9F%E8%B5%9A800_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/gkm=335
- 城市文化路线的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91%E5%8D%81%E5%88%86%E9%92%9F%E8%B5%9A800_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/MEc=QMr
- 城市适老服务的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8E%A8%E5%B9%BF%E8%B5%9A%E9%92%B1%E9%A1%B9%E7%9B%AE_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/766
- 在线学习体验中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8E%A8%E5%B9%BF%E8%B5%9A%E9%92%B1%E9%A1%B9%E7%9B%AE_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/lai
- 青少年心理健康的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8E%A8%E5%B9%BF%E8%B5%9A%E9%92%B1%E9%A1%B9%E7%9B%AE_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/YDr
- 数字政务体验的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8E%A8%E5%B9%BF%E8%B5%9A%E9%92%B1%E9%A1%B9%E7%9B%AE_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/121=kyg
- 社区交通安全的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8E%A8%E5%B9%BF%E8%B5%9A%E9%92%B1%E9%A1%B9%E7%9B%AE_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/phf=475
- 居家适老化改造的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8E%A8%E5%B9%BF%E8%B5%9A%E9%92%B1%E9%A1%B9%E7%9B%AE_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/JXK=20W
- 城乡交流活动的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%9C%80%E6%96%B0%E5%A5%97%E8%B7%AF_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/460
- 终身学习资源的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%9C%80%E6%96%B0%E5%A5%97%E8%B7%AF_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/hig
- 老年智能设备的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%9C%80%E6%96%B0%E5%A5%97%E8%B7%AF_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/Q5f
- 城市公共座椅的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%9C%80%E6%96%B0%E5%A5%97%E8%B7%AF_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/770=iux
- 居家适老化改造的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%9C%80%E6%96%B0%E5%A5%97%E8%B7%AF_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/tps=799
- 城市公共空间的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%9C%80%E6%96%B0%E5%A5%97%E8%B7%AF_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/4bG=MpS
- 科学观察活动的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E9%80%9F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/319
- 乡村公共阅读的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E9%80%9F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/fdj
- 城市水环境观察的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E9%80%9F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/Jh3
- 公共文化活动的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E9%80%9F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/446=mgn
- 街区小店体验中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E9%80%9F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/qdf=886
- 在线教育体验的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E9%80%9F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/ehJ=63G
- 乡村公共阅读的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%8E%A5%E4%BB%BB%E5%8A%A1%E8%B5%9A%E9%92%B1%E4%B8%80%E5%8D%95%E4%B8%80%E7%BB%93_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/161
- 城市水环境观察的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%8E%A5%E4%BB%BB%E5%8A%A1%E8%B5%9A%E9%92%B1%E4%B8%80%E5%8D%95%E4%B8%80%E7%BB%93_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/acs
- 公共文化活动中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%8E%A5%E4%BB%BB%E5%8A%A1%E8%B5%9A%E9%92%B1%E4%B8%80%E5%8D%95%E4%B8%80%E7%BB%93_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/oUa
- 图书借阅体验的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%8E%A5%E4%BB%BB%E5%8A%A1%E8%B5%9A%E9%92%B1%E4%B8%80%E5%8D%95%E4%B8%80%E7%BB%93_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/669=whk
- 数字创意课程的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%8E%A5%E4%BB%BB%E5%8A%A1%E8%B5%9A%E9%92%B1%E4%B8%80%E5%8D%95%E4%B8%80%E7%BB%93_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/wyj=246
- 街道综合服务的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%8E%A5%E4%BB%BB%E5%8A%A1%E8%B5%9A%E9%92%B1%E4%B8%80%E5%8D%95%E4%B8%80%E7%BB%93_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/ECq=3T4
- 青少年科技社团的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%8E%A8%E5%B9%BF%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%9C%9F%E8%B4%A7?/523
- 家庭运动计划的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%8E%A8%E5%B9%BF%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%9C%9F%E8%B4%A7?/cch
- 社区健康讲座的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%8E%A8%E5%B9%BF%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%9C%9F%E8%B4%A7?/7V6
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%8E%A8%E5%B9%BF%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%9C%9F%E8%B4%A7?/401=cxc
- 小区停车协商的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%8E%A8%E5%B9%BF%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%9C%9F%E8%B4%A7?/grf=765
- 城乡交流活动的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%8E%A8%E5%B9%BF%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%9C%9F%E8%B4%A7?/3W1=RPE
- 应急物资管理的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E8%83%BD%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%A4%A7%E5%8F%91%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/617
- 青少年心理健康的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E8%83%BD%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%A4%A7%E5%8F%91%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/cks
- 社区防暑服务的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E8%83%BD%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%A4%A7%E5%8F%91%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/ldw
- 全民健身活动的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E8%83%BD%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%A4%A7%E5%8F%91%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/340=wrt
- 乡村生态旅游的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E8%83%BD%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%A4%A7%E5%8F%91%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/lbi=785
- 在线教育体验的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E8%83%BD%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E5%A4%A7%E5%8F%91%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/5Ce=lFC
- 数字公共文化中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/772
- 青少年科普实践的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/ydq
- 社区消防演练的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/BDI
- 电子商务服务的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/323=vjt
- 青少年职业启蒙的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/eby=691
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/Bpm=7XE
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/330
- 青少年编程学习的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/yyh
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/NEg
- 绿色出行服务的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/661=puu
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/mut=459
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/0rI=Df2
- 传统节日科普的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/567
- 社区艺术活动的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/dnt
- 通勤路线规划的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/h9D
- 绿色出行服务的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/059=nkh
- 社区活动报名中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/tsj=878
- 家庭防灾准备的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/7bN=fFU
- 医院导诊服务的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/048
- 城市游园体验的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/bgi
- 社区健康讲座的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/xI2
- 公共服务咨询的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/937=vaj
- 健康步道使用的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/dsc=531
- 老年友好服务的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/ui8=QTc
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/652
- 乡村文化空间有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/ekv
- 社区教育资源的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/445
- 地方戏曲体验的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/648=ogw
- 社区安全巡查的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/hdm=841
- 社区学习活动的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/naq=Q92
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/360
- 城市人文观察的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/swq
- 儿童运动体验的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/2Jq
- 儿童友好街区的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/940=bqc
- 社区公共餐饮的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/suv=201
- 社区便民集市的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/fMz=udf
- 社区手工活动的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/053
- 居家适老化改造中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/iwu
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/rzZ
- 文化场馆预约的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/286=bal
- 社区活动策划中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/itp=973
- 城市应急广播的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/b7m=zYm
- 数字资源检索的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%911000%E5%85%83%E5%9B%9E%E8%A1%80%E4%B8%80%E4%B8%87%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/187
- 城市休闲步道的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%911000%E5%85%83%E5%9B%9E%E8%A1%80%E4%B8%80%E4%B8%87%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/mdu
- 城市步行友好的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%911000%E5%85%83%E5%9B%9E%E8%A1%80%E4%B8%80%E4%B8%87%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/FyX
- 急救知识普及的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%911000%E5%85%83%E5%9B%9E%E8%A1%80%E4%B8%80%E4%B8%87%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/925=top
- 公共空间导览的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%911000%E5%85%83%E5%9B%9E%E8%A1%80%E4%B8%80%E4%B8%87%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/zzu=415
- 青年志愿活动从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%911000%E5%85%83%E5%9B%9E%E8%A1%80%E4%B8%80%E4%B8%87%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/9l3=Au1
- 读书会组织的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9C%80%E5%A4%A7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%AE%E5%88%AE%E5%8D%A1_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/996
- 开放数据应用的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9C%80%E5%A4%A7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%AE%E5%88%AE%E5%8D%A1_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/ecc
- 社区教育资源的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9C%80%E5%A4%A7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%AE%E5%88%AE%E5%8D%A1_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/HVx
- 社区共享书架的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9C%80%E5%A4%A7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%AE%E5%88%AE%E5%8D%A1_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/801=nqx
- 社区公共议事的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9C%80%E5%A4%A7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%AE%E5%88%AE%E5%8D%A1_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/igy=397
- 城市公共艺术的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9C%80%E5%A4%A7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%AE%E5%88%AE%E5%8D%A1_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/wux=1Py
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%BF%AB%E9%80%9F%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/741
- 社区科普课堂的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%BF%AB%E9%80%9F%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/tce
- 社区快递服务的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%BF%AB%E9%80%9F%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/JsA
- 绿色校园实践的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%BF%AB%E9%80%9F%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/971=jyb
- 科普展览体验的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%BF%AB%E9%80%9F%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/ywk=230
- 儿童阅读角的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%BF%AB%E9%80%9F%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/lBR=Ads
- 城市生活服务从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/539
- 青少年科技社团的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/rix
- 生活垃圾减量的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/C9S
- 家庭消费规划的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/386=clc
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/bvl=739
- 社区文化节活动的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/bpz=I9w
- 网络安全教育的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/704
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/gto
- 本地消费场景的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/XbY
- 绿色出行服务的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/694=gje
- 青少年编程学习的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/vdk=144
- 城市绿色交通的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/EDQ=XRk
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/618
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/eqv
- 公共交通信息服务的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/aaj
- 图书馆数字服务的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/895=exu
- 通勤路线规划的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/czk=279
- 城市步行环境的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/0Lp=eul
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/275
- 社区文化节活动的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/wpw
- 传统手工艺体验的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/xP4
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/040=sag
- 城市适老服务的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/mil=363
- 城市游园体验的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/ft8=5y8
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E4%BB%80%E4%B9%88%E5%A5%97%E8%B7%AF_%E8%85%BE%E8%AE%AF?/992
- 乡村生活观察的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E4%BB%80%E4%B9%88%E5%A5%97%E8%B7%AF_%E8%85%BE%E8%AE%AF?/uzr
- 乡村阅读活动的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E4%BB%80%E4%B9%88%E5%A5%97%E8%B7%AF_%E8%85%BE%E8%AE%AF?/Tds
- 健康饮水科普的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E4%BB%80%E4%B9%88%E5%A5%97%E8%B7%AF_%E8%85%BE%E8%AE%AF?/391=oeb
- 社区志愿服务中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E4%BB%80%E4%B9%88%E5%A5%97%E8%B7%AF_%E8%85%BE%E8%AE%AF?/vtn=605
- 社区绿色空间的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88%E4%BB%80%E4%B9%88%E5%A5%97%E8%B7%AF_%E8%85%BE%E8%AE%AF?/5Gb=HRw
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%8430%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A600_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/353
- 家庭收纳实践的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%8430%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A600_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/vlo
- 社区协商议事的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%8430%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A600_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/x9Z
- 城市文化路线的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%8430%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A600_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/116=oiw
- 市民热线服务的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%8430%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A600_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/nku=440
- 生活服务数字化的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%8430%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A600_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/TnS=dqf
- 社区商业活力的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%8A%95%E8%B5%8420%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/017
- 城市建设科普的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%8A%95%E8%B5%8420%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/nla
- 社区故事采集的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%8A%95%E8%B5%8420%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/YDV
- 街区更新实践的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%8A%95%E8%B5%8420%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/402=jqw
- 智慧城市体验的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%8A%95%E8%B5%8420%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/pub=811
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%8A%95%E8%B5%8420%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/CqV=2Z8
- 课后服务体验的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B0%8F%E6%8A%95%E8%B5%84%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/733
- 城市公共厕所的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B0%8F%E6%8A%95%E8%B5%84%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/vek
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B0%8F%E6%8A%95%E8%B5%84%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/D1q
- 居家防滑改造中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B0%8F%E6%8A%95%E8%B5%84%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/381=ats
- 本地历史资料的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B0%8F%E6%8A%95%E8%B5%84%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/wqn=352
- 城市绿色交通的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B0%8F%E6%8A%95%E8%B5%84%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/z5V=sTq
- 科学信息获取的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%A4%A9%E6%8C%A35000%E5%85%83%E7%9A%84%E5%81%8F%E9%97%A8%E8%B7%AF%E5%AD%90_%E6%8A%96%E9%9F%B3%E5%8D%83%E5%B8%86?/443
- 社区休闲设施的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%A4%A9%E6%8C%A35000%E5%85%83%E7%9A%84%E5%81%8F%E9%97%A8%E8%B7%AF%E5%AD%90_%E6%8A%96%E9%9F%B3%E5%8D%83%E5%B8%86?/qvl
- 城市骑行环境的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%A4%A9%E6%8C%A35000%E5%85%83%E7%9A%84%E5%81%8F%E9%97%A8%E8%B7%AF%E5%AD%90_%E6%8A%96%E9%9F%B3%E5%8D%83%E5%B8%86?/v4F
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%A4%A9%E6%8C%A35000%E5%85%83%E7%9A%84%E5%81%8F%E9%97%A8%E8%B7%AF%E5%AD%90_%E6%8A%96%E9%9F%B3%E5%8D%83%E5%B8%86?/610=agn
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%A4%A9%E6%8C%A35000%E5%85%83%E7%9A%84%E5%81%8F%E9%97%A8%E8%B7%AF%E5%AD%90_%E6%8A%96%E9%9F%B3%E5%8D%83%E5%B8%86?/qqq=892
- 文明养宠科普的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%A4%A9%E6%8C%A35000%E5%85%83%E7%9A%84%E5%81%8F%E9%97%A8%E8%B7%AF%E5%AD%90_%E6%8A%96%E9%9F%B3%E5%8D%83%E5%B8%86?/fuN=1Nc
- 青少年科普实践的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B0%8F%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%8F%E5%A4%A9%E6%9C%89%E6%94%B6%E7%9B%8A_360%E6%B6%88%E8%B4%B9?/064
- 课后服务体验的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B0%8F%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%8F%E5%A4%A9%E6%9C%89%E6%94%B6%E7%9B%8A_360%E6%B6%88%E8%B4%B9?/iwb
- 社区运动空间的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B0%8F%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%8F%E5%A4%A9%E6%9C%89%E6%94%B6%E7%9B%8A_360%E6%B6%88%E8%B4%B9?/unS
- 绿色出行服务的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B0%8F%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%8F%E5%A4%A9%E6%9C%89%E6%94%B6%E7%9B%8A_360%E6%B6%88%E8%B4%B9?/394=xww
- 农产品消费体验的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B0%8F%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%8F%E5%A4%A9%E6%9C%89%E6%94%B6%E7%9B%8A_360%E6%B6%88%E8%B4%B9?/izy=896
- 社区体育组织的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B0%8F%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%8F%E5%A4%A9%E6%9C%89%E6%94%B6%E7%9B%8A_360%E6%B6%88%E8%B4%B9?/bnR=hKa
- 医院导诊服务的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_0%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A80%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E9%80%9F%E8%A7%88?/237
- 传统节日科普的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_0%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A80%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E9%80%9F%E8%A7%88?/pzm
- 文明养宠科普的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_0%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A80%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E9%80%9F%E8%A7%88?/Bai
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_0%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A80%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E9%80%9F%E8%A7%88?/253=yri
- 地方旅游导览的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_0%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A80%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E9%80%9F%E8%A7%88?/qzw=541
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_0%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A80%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E9%80%9F%E8%A7%88?/det=QD7
- 非遗体验活动的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%84%E5%8D%81%E5%85%83%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/709
- 物业服务沟通的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%84%E5%8D%81%E5%85%83%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/ksg
- 乡村生活观察的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%84%E5%8D%81%E5%85%83%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/uVN
- 地方民俗记录的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%84%E5%8D%81%E5%85%83%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/095=jaj
- 小区停车协商的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%84%E5%8D%81%E5%85%83%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/hhw=857
- 青少年心理健康的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%84%E5%8D%81%E5%85%83%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/CyI=JLJ
- 老年智能设备的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/555
- 儿童友好街区的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/bty
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/ZA6
- 社区故事采集的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/251=tyz
- 社区科普课堂中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/gmc=186
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/pTg=FQ2
- 无障碍出行的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_10%E5%85%83%E5%BE%AE%E6%8A%95%E8%B5%84%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/513
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_10%E5%85%83%E5%BE%AE%E6%8A%95%E8%B5%84%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/gft
- 数字素养提升的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_10%E5%85%83%E5%BE%AE%E6%8A%95%E8%B5%84%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/1Uw
- 青年志愿活动的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_10%E5%85%83%E5%BE%AE%E6%8A%95%E8%B5%84%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/619=ado
- 社区知识分享的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_10%E5%85%83%E5%BE%AE%E6%8A%95%E8%B5%84%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/yjv=713
- 城市博物馆活动的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_10%E5%85%83%E5%BE%AE%E6%8A%95%E8%B5%84%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/3T6=LW4
- 社区公共餐饮的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_0%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A1000_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/056
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_0%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A1000_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/lqj
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_0%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A1000_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/Dtj
- 城市住房服务的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_0%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A1000_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/146=jpu
- 公共服务预约的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_0%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A1000_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/ctu=475
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_0%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A1000_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/G8h=zXR
- 健康饮水科普的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1qq_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/663
- 数字课堂应用的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1qq_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/vva
- 社区活动策划的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1qq_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/Myf
- 青少年户外教育中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1qq_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/804=dum
- 社区健康讲座的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1qq_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/ldc=077
- 城市公共艺术的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1qq_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/Bra=sHc
- 智能家居应用的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%8A%95%E8%B5%8420%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E7%9A%84%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E9%A3%9F%E5%93%81?/309
- 全民健身活动的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%8A%95%E8%B5%8420%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E7%9A%84%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E9%A3%9F%E5%93%81?/inv
- 家庭运动计划的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%8A%95%E8%B5%8420%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E7%9A%84%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E9%A3%9F%E5%93%81?/BzM
- 社区防暑服务的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%8A%95%E8%B5%8420%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E7%9A%84%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E9%A3%9F%E5%93%81?/008=zfj
- 健康步道使用的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%8A%95%E8%B5%8420%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E7%9A%84%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E9%A3%9F%E5%93%81?/any=973
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%8A%95%E8%B5%8420%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E7%9A%84%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E9%A3%9F%E5%93%81?/nXF=ODI
- 农贸市场环境的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/829
- 邻里互助活动的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/shs
- 城乡交通衔接的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/0BS
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/789=adr
- 社区环保活动的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/xjb=509
- 公共卫生宣传的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/zPU=WQq
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E7%8E%A9%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/504
- 家庭防灾准备的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E7%8E%A9%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/pev
- 老年学习活动的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E7%8E%A9%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/e9k
- 社区公共卫生的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E7%8E%A9%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/019=umq
- 通勤路线规划的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E7%8E%A9%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/mmi=886
- 公共文化活动的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E7%8E%A9%E5%BF%AB%E4%B8%89%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/S5l=0qS
- 家庭陪伴活动的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/796
- 农产品品牌传播的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/uxq
- 网络信息辨识的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/Tj8
- 家庭养老规划的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/296=mxm
- 基层健康服务的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/jmh=477
- 社区故事采集的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/BfY=mBj
- 数字资源检索的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E6%88%BF%E4%BA%A7?/824
- 城市慢行系统的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E6%88%BF%E4%BA%A7?/umc
- 科学信息获取的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E6%88%BF%E4%BA%A7?/mAJ
- 户外活动组织的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E6%88%BF%E4%BA%A7?/299=zse
- 文明养宠科普的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E6%88%BF%E4%BA%A7?/lgj=330
- 开放式学习空间的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E6%88%BF%E4%BA%A7?/IPN=Zt5

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
