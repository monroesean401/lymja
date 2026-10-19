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

- 家庭环保习惯的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91app%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/aHr
- 小微企业服务的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91app%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/942=xpv
- 图书馆活动策划的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91app%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/enj=230
- 青年职业探索的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91app%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/96g=sDS
- 软件开发学习的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_360%E5%9B%AD%E8%89%BA?/365
- 校园社团活动的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_360%E5%9B%AD%E8%89%BA?/shy
- 地方文化传播的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_360%E5%9B%AD%E8%89%BA?/7Nk
- 节能家电使用的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_360%E5%9B%AD%E8%89%BA?/755=lmq
- 社区活动策划中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_360%E5%9B%AD%E8%89%BA?/saz=174
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_360%E5%9B%AD%E8%89%BA?/qGh=RIg
- 家庭食品保存的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/524
- 电动汽车充电中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/jqx
- 科技馆参观体验的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/Yem
- 软件开发学习的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/431=ztt
- 远程协作工具的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/cbk=380
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/IXD=lcr
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%A4%A7%E7%A5%9E_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/241
- 周末休闲规划的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%A4%A7%E7%A5%9E_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/ifs
- 社区垃圾分类的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%A4%A7%E7%A5%9E_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/dEz
- 环境教育课程从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%A4%A7%E7%A5%9E_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/466=foh
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%A4%A7%E7%A5%9E_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/ikr=211
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%A4%A7%E7%A5%9E_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/MTw=riD
- 社区商业活力的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/171
- 公共健身器材的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/tfj
- 校园节能行动的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/xp5
- 社区商业活力的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/494=cav
- 邻里互助活动的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/fbx=628
- 电子商务服务的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/WYw=qGY
- 智能家居应用的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B8%AF%E8%82%A1?/907
- 社区读书角建设的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B8%AF%E8%82%A1?/hwd
- 城市运动公园的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B8%AF%E8%82%A1?/ofU
- 家庭运动计划的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B8%AF%E8%82%A1?/160=nyj
- 城市微更新实践有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B8%AF%E8%82%A1?/krd=848
- 校园社团活动的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B8%AF%E8%82%A1?/bPd=OZf
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/055
- 社区信息发布的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/eee
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/FMa
- 药品使用科普的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/025=leb
- 公共设施维护中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/mgv=746
- 绿色办公实践的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/P6u=xFU
- 城市树木认养的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/440
- 急救知识普及的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/ino
- 儿童户外活动的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/6Hh
- 城市建设科普的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/493=bba
- 城乡交流活动的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/arr=111
- 数字公共文化的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/RXp=6cW
- 社区家校合作的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6app_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/644
- 社区交通安全的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6app_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/pma
- 家庭环保行动的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6app_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/kqP
- 社区阅读服务的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6app_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/431=svy
- 社区交通安全的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6app_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/llt=398
- 城市公共座椅的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6app_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/4eK=6cI
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/031
- 社区手工活动的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/yqn
- 在线教育体验的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/mz7
- 数字便民地图的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/363=woe
- 社区活动报名中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/xsy=116
- 非遗课堂体验的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/7Vh=YOZ
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/285
- 消防知识宣传的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/dld
- 数字创作工具的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/NxU
- 光伏知识科普的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/489=ldo
- 社区活动空间的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/wdf=419
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/GOl=D1e
- 健康步道使用的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/933
- 社区花园共建的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/csu
- 家庭环保习惯的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/0cD
- 周末休闲规划的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/500=xyb
- 骑行路线规划的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/xmo=800
- 城市公共艺术的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/m34=5KZ
- 家庭理财科普的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/336
- 城市水环境观察的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/fen
- 邻里互助活动的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/rii
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/885=add
- 公共空间导览的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/dat=606
- 药品使用科普的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/aLX=b9e
- 街区绿化养护的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/342
- 城市生活服务的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/ynq
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/ao4
- 无障碍信息设计的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/421=yri
- 公共服务预约的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/fkd=385
- 健康饮食教育的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E6%97%85%E6%B8%B8?/IAX=gvD
- 青少年编程学习的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA?/562
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA?/qhl
- 公共空间导览的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA?/79p
- 城市文明实践中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA?/545=nwo
- 旧物循环利用中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA?/siy=148
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA?/55f=8rB
- 科学运动指导的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/461
- 公园亲子设施的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/rvi
- 便民服务窗口的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/9Hc
- 公共场所导视的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/375=mme
- 社区信息发布的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/noi=041
- 市民意见收集的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%9C%9B?/Ryx=Ra6
- 本地历史资料的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/931
- 安全出行教育的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/tok
- 地方美食文化的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/R3D
- 老年人出行服务的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/256=zoa
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/gia=355
- 家庭理财科普的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/4Bq=fOP
- 地方旅游导览的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/127
- 数字创意课程的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/sqn
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/MMN
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/702=rhk
- 社区活动空间的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/mzz=224
- 基层健康服务的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/kQD=Yt0
- 社区垃圾分类的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/957
- 公共文化活动的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/zyf
- 城市基础设施的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/WpP
- 灵活就业交流的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/381=bdd
- 街区道路维护中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/stu=864
- 社区家校合作的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/WZS=SPk
- 传统节日科普的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/586
- 学校食育活动的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/vfw
- 儿童友好空间的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/eJ1
- 城市游园体验的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/756=wql
- 青年职业探索中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/lxg=481
- 街区小店体验的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/rw0=axm
- 青少年职业启蒙的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8app_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/300
- 乡村产业科普的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8app_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/thr
- 城市雨天出行的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8app_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/evM
- 数字便民地图的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8app_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/562=bal
- 老年友好服务的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8app_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/oqy=550
- 社区托育服务的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%A8app_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/5Ht=av3
- 家庭健康科普的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8VIII_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/955
- 生活技能分享中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8VIII_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/uma
- 青少年科技社团的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8VIII_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/ed8
- 社区花园共建的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8VIII_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/545=drx
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8VIII_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/xmf=754
- 数字阅读服务的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8VIII_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/eiM=Yw2
- 邻里互助活动的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84app%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/736
- 人工智能科普的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84app%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/zfq
- 城市慢行系统中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84app%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/Lth
- 社区绿色空间的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84app%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/776=jhj
- 街区绿化养护的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84app%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/ddm=919
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84app%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/Zkq=Te9
- 绿色建筑理念的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%8A%AF%E6%B3%95%E5%90%97%E4%BC%9A%E9%80%A0%E6%88%90%E6%8B%98%E7%95%99%E5%90%97_%E5%BF%85%E5%BA%94%E5%8F%B7%E5%A4%96?/795
- 社区停车服务的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%8A%AF%E6%B3%95%E5%90%97%E4%BC%9A%E9%80%A0%E6%88%90%E6%8B%98%E7%95%99%E5%90%97_%E5%BF%85%E5%BA%94%E5%8F%B7%E5%A4%96?/kmr
- 基层健康档案的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%8A%AF%E6%B3%95%E5%90%97%E4%BC%9A%E9%80%A0%E6%88%90%E6%8B%98%E7%95%99%E5%90%97_%E5%BF%85%E5%BA%94%E5%8F%B7%E5%A4%96?/oJP
- 公园亲子设施的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%8A%AF%E6%B3%95%E5%90%97%E4%BC%9A%E9%80%A0%E6%88%90%E6%8B%98%E7%95%99%E5%90%97_%E5%BF%85%E5%BA%94%E5%8F%B7%E5%A4%96?/994=ihv
- 图书馆数字服务的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%8A%AF%E6%B3%95%E5%90%97%E4%BC%9A%E9%80%A0%E6%88%90%E6%8B%98%E7%95%99%E5%90%97_%E5%BF%85%E5%BA%94%E5%8F%B7%E5%A4%96?/qlp=198
- 儿童户外活动的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%8A%AF%E6%B3%95%E5%90%97%E4%BC%9A%E9%80%A0%E6%88%90%E6%8B%98%E7%95%99%E5%90%97_%E5%BF%85%E5%BA%94%E5%8F%B7%E5%A4%96?/DzI=tLG
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/273
- 老年人文化生活的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/syh
- 新能源出行的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/dWh
- 社区公共餐饮的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/070=rcr
- 青少年科普实践的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/dgb=619
- 智能家居应用的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/kaX=8Z4
- 老年人文化生活的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%8C%E8%89%B2%E7%90%83_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/238
- 基层医疗预约的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%8C%E8%89%B2%E7%90%83_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/sjk
- 社区读书角建设的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%8C%E8%89%B2%E7%90%83_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/y92
- 街区小店体验的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%8C%E8%89%B2%E7%90%83_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/776=lif
- 就业技能培训的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%8C%E8%89%B2%E7%90%83_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/xll=068
- 社区健康讲座的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%8C%E8%89%B2%E7%90%83_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/SBM=GcJ
- 全民健身活动的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%8F%AF%E4%BB%A5%E8%A6%81%E7%9A%84%E5%9B%9E%E6%9D%A5%E5%90%97_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/454
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%8F%AF%E4%BB%A5%E8%A6%81%E7%9A%84%E5%9B%9E%E6%9D%A5%E5%90%97_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/klx
- 社区养老服务的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%8F%AF%E4%BB%A5%E8%A6%81%E7%9A%84%E5%9B%9E%E6%9D%A5%E5%90%97_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/KlD
- 公共卫生设施的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%8F%AF%E4%BB%A5%E8%A6%81%E7%9A%84%E5%9B%9E%E6%9D%A5%E5%90%97_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/566=rme
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%8F%AF%E4%BB%A5%E8%A6%81%E7%9A%84%E5%9B%9E%E6%9D%A5%E5%90%97_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/ofd=942
- 城市文化路线的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%E5%8F%AF%E4%BB%A5%E8%A6%81%E7%9A%84%E5%9B%9E%E6%9D%A5%E5%90%97_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/qyN=u5Q
- 机器学习入门的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E9%92%B1%E8%83%BD%E8%A6%81%E7%9A%84%E5%9B%9E%E6%9D%A5%E5%90%97_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/053
- 城市基础设施的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E9%92%B1%E8%83%BD%E8%A6%81%E7%9A%84%E5%9B%9E%E6%9D%A5%E5%90%97_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/nvn
- 农村环境治理的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E9%92%B1%E8%83%BD%E8%A6%81%E7%9A%84%E5%9B%9E%E6%9D%A5%E5%90%97_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/lsx
- 数字资源检索的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E9%92%B1%E8%83%BD%E8%A6%81%E7%9A%84%E5%9B%9E%E6%9D%A5%E5%90%97_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/067=frh
- 骑行路线规划的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E9%92%B1%E8%83%BD%E8%A6%81%E7%9A%84%E5%9B%9E%E6%9D%A5%E5%90%97_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/gcw=145
- 城市慢行系统的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E9%92%B1%E8%83%BD%E8%A6%81%E7%9A%84%E5%9B%9E%E6%9D%A5%E5%90%97_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/rbe=zzj
- 乡村阅读空间的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%AE%97%E7%8A%AF%E6%B3%95%E5%90%97_%E5%87%A4%E5%87%B0%E5%8F%B8%E6%B3%95?/181
- 家庭科学教育的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%AE%97%E7%8A%AF%E6%B3%95%E5%90%97_%E5%87%A4%E5%87%B0%E5%8F%B8%E6%B3%95?/ltr
- 社区文化节活动的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%AE%97%E7%8A%AF%E6%B3%95%E5%90%97_%E5%87%A4%E5%87%B0%E5%8F%B8%E6%B3%95?/xTh
- 新能源知识普及的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%AE%97%E7%8A%AF%E6%B3%95%E5%90%97_%E5%87%A4%E5%87%B0%E5%8F%B8%E6%B3%95?/649=gwh
- 社区菜市场服务的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%AE%97%E7%8A%AF%E6%B3%95%E5%90%97_%E5%87%A4%E5%87%B0%E5%8F%B8%E6%B3%95?/cxu=400
- 急救知识普及的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%AE%97%E7%8A%AF%E6%B3%95%E5%90%97_%E5%87%A4%E5%87%B0%E5%8F%B8%E6%B3%95?/5yO=FDo
- 图书借阅体验的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%9A%84%E9%92%B1%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E6%89%BE%E5%9B%9E%E6%9D%A5_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/491
- 数字学习资源的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%9A%84%E9%92%B1%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E6%89%BE%E5%9B%9E%E6%9D%A5_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/qsp
- 家庭饮食安排的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%9A%84%E9%92%B1%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E6%89%BE%E5%9B%9E%E6%9D%A5_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/q0r
- 小区电梯维护的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%9A%84%E9%92%B1%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E6%89%BE%E5%9B%9E%E6%9D%A5_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/632=enc
- 街道综合服务的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%9A%84%E9%92%B1%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E6%89%BE%E5%9B%9E%E6%9D%A5_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/uje=017
- 乡村产业科普的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%9A%84%E9%92%B1%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E6%89%BE%E5%9B%9E%E6%9D%A5_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/Cso=IV5
- 图书馆亲子空间的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E4%BC%9A%E8%A2%AB%E6%8B%98%E7%95%99%E5%90%97_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/089
- 本地历史资料的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E4%BC%9A%E8%A2%AB%E6%8B%98%E7%95%99%E5%90%97_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/zpb
- 志愿服务平台的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E4%BC%9A%E8%A2%AB%E6%8B%98%E7%95%99%E5%90%97_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/jMt
- 全民阅读推广的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E4%BC%9A%E8%A2%AB%E6%8B%98%E7%95%99%E5%90%97_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/265=lzj
- 社区故事采集的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E4%BC%9A%E8%A2%AB%E6%8B%98%E7%95%99%E5%90%97_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/pob=764
- 社区垃圾回收中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E4%BC%9A%E8%A2%AB%E6%8B%98%E7%95%99%E5%90%97_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/mM2=PVN
- 城市体育设施的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E6%9C%89%E7%94%A8%E5%90%97_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/095
- 老年数字阅读的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E6%9C%89%E7%94%A8%E5%90%97_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/jxj
- 城市绿色交通的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E6%9C%89%E7%94%A8%E5%90%97_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/idV
- 青少年户外教育的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E6%9C%89%E7%94%A8%E5%90%97_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/419=boo
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E6%9C%89%E7%94%A8%E5%90%97_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/lub=240
- 青年职业探索的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E6%9C%89%E7%94%A8%E5%90%97_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/bal=w8J
- 生成式工具使用的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/391
- 家庭照护支持的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/naz
- 城市农夫市集的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/9wU
- 青少年科普实践的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/182=rkq
- 小区公共照明的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/wfw=090
- 家庭收纳实践的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/XiJ=tO4
- 家庭环保习惯的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/738
- 学校食育活动的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/nld
- 公共交通信息服务的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/OhP
- 市民热线服务的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/925=zqn
- 低碳社区实践的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/yhl=744
- 基层健康档案的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/ov2=Dcp
- 乡村文化活动的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E8%83%BD%E8%BF%BD%E5%9B%9E%E5%90%97_36%E6%B0%AA%E7%90%86%E8%B4%A2?/408
- 公共服务预约的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E8%83%BD%E8%BF%BD%E5%9B%9E%E5%90%97_36%E6%B0%AA%E7%90%86%E8%B4%A2?/pku
- 家庭志愿活动的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E8%83%BD%E8%BF%BD%E5%9B%9E%E5%90%97_36%E6%B0%AA%E7%90%86%E8%B4%A2?/sIP
- 城市微更新实践的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E8%83%BD%E8%BF%BD%E5%9B%9E%E5%90%97_36%E6%B0%AA%E7%90%86%E8%B4%A2?/462=rsy
- 药品使用科普的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E8%83%BD%E8%BF%BD%E5%9B%9E%E5%90%97_36%E6%B0%AA%E7%90%86%E8%B4%A2?/ifd=841
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%86%E6%8A%A5%E8%AD%A6%E8%83%BD%E8%BF%BD%E5%9B%9E%E5%90%97_36%E6%B0%AA%E7%90%86%E8%B4%A2?/QGY=T9w
- 城市公共自行车的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%9A%84%E9%92%B1%E5%8F%AF%E4%BB%A5%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/738
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%9A%84%E9%92%B1%E5%8F%AF%E4%BB%A5%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/xpx
- 社区公共卫生的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%9A%84%E9%92%B1%E5%8F%AF%E4%BB%A5%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/8Hp
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%9A%84%E9%92%B1%E5%8F%AF%E4%BB%A5%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/077=fkl
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%9A%84%E9%92%B1%E5%8F%AF%E4%BB%A5%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/etj=636
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E7%9A%84%E9%92%B1%E5%8F%AF%E4%BB%A5%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/KcM=Uu3
- 家庭陪伴活动的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_360%E6%85%A7%E7%9C%BC?/506
- 读书会组织的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_360%E6%85%A7%E7%9C%BC?/tyg
- 智能手机助老中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_360%E6%85%A7%E7%9C%BC?/z12
- 安全出行教育的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_360%E6%85%A7%E7%9C%BC?/081=cdn
- 文明养宠科普的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_360%E6%85%A7%E7%9C%BC?/wyo=257
- 就业技能培训的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_360%E6%85%A7%E7%9C%BC?/v7M=frx
- 居家适老化改造的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%AD%A3%E8%A7%84%E5%90%97_%E7%9F%A5%E4%B9%8E?/968
- 城市雨天出行的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%AD%A3%E8%A7%84%E5%90%97_%E7%9F%A5%E4%B9%8E?/uaz
- 公园亲子设施的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%AD%A3%E8%A7%84%E5%90%97_%E7%9F%A5%E4%B9%8E?/FYu
- 社区应急准备的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%AD%A3%E8%A7%84%E5%90%97_%E7%9F%A5%E4%B9%8E?/654=xvz
- 社区健康讲座的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%AD%A3%E8%A7%84%E5%90%97_%E7%9F%A5%E4%B9%8E?/gpu=438
- 家庭运动计划的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%AD%A3%E8%A7%84%E5%90%97_%E7%9F%A5%E4%B9%8E?/p6p=7S0
- 社会体育指导的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E7%9A%84%E6%B5%81%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/123
- 居家防滑改造的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E7%9A%84%E6%B5%81%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/lam
- 街区小店体验的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E7%9A%84%E6%B5%81%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/Esa
- 青少年科普实践的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E7%9A%84%E6%B5%81%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/569=nqr
- 社区科普课堂的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E7%9A%84%E6%B5%81%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/fiv=384
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E7%9A%84%E6%B5%81%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/0li=vWZ
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%BA%BF%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%8A%95%E8%B5%84%E6%98%AF%E8%AF%88%E9%AA%97%E5%90%97_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/670
- 家庭健康科普的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%BA%BF%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%8A%95%E8%B5%84%E6%98%AF%E8%AF%88%E9%AA%97%E5%90%97_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/fud
- 城市博物馆活动的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%BA%BF%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%8A%95%E8%B5%84%E6%98%AF%E8%AF%88%E9%AA%97%E5%90%97_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/Ns0
- 老年智能设备的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%BA%BF%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%8A%95%E8%B5%84%E6%98%AF%E8%AF%88%E9%AA%97%E5%90%97_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/215=hij
- 家庭节能设备的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%BA%BF%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%8A%95%E8%B5%84%E6%98%AF%E8%AF%88%E9%AA%97%E5%90%97_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/cbq=101
- 口袋公园建设的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%BA%BF%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%8A%95%E8%B5%84%E6%98%AF%E8%AF%88%E9%AA%97%E5%90%97_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/xRX=okj
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%8640%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/910
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%8640%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/rhh
- 绿色生活实践的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%8640%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/H9z
- 家庭养老规划的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%8640%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/901=mxo
- 城市文明出行的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%8640%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/llm=062
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E8%A2%AB%E9%AA%97%E4%BA%8640%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/i2C=OMe
- 校园社团活动的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%9C%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%A2%AB%E9%AA%97%E4%BA%86%E8%AF%A5%E5%A6%82%E4%BD%95%E5%A4%84%E7%90%86_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/822
- 人工智能科普的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%9C%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%A2%AB%E9%AA%97%E4%BA%86%E8%AF%A5%E5%A6%82%E4%BD%95%E5%A4%84%E7%90%86_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/ejc
- 地方美食文化的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%9C%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%A2%AB%E9%AA%97%E4%BA%86%E8%AF%A5%E5%A6%82%E4%BD%95%E5%A4%84%E7%90%86_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/I3a
- 劳动教育实践的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%9C%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%A2%AB%E9%AA%97%E4%BA%86%E8%AF%A5%E5%A6%82%E4%BD%95%E5%A4%84%E7%90%86_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/506=exz
- 家庭教育交流的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%9C%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%A2%AB%E9%AA%97%E4%BA%86%E8%AF%A5%E5%A6%82%E4%BD%95%E5%A4%84%E7%90%86_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/fiq=834
- 生活技能分享的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%9C%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%A2%AB%E9%AA%97%E4%BA%86%E8%AF%A5%E5%A6%82%E4%BD%95%E5%A4%84%E7%90%86_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/gPh=aRK

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
