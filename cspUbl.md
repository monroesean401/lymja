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

- 社区知识分享的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/t4g
- 乡村文化活动的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/452=nee
- 科技馆参观体验的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/xde=295
- 社区家校合作的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/H6k=YCd
- 线上办事服务的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/364
- 乡村生态旅游的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/skj
- 在线教育体验的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/Nna
- 家庭饮食安排的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/920=vqt
- 居家适老化改造的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/rbo=208
- 乡村生态观察的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/lzv=Vv9
- 街区小店体验的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/642
- 社区公共餐饮的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/ziu
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/MXF
- 社区庭院绿化的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/832=vmh
- 社区设施共享的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/cwd=551
- 便民服务窗口的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/RhQ=b3F
- 社区邻里服务的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%8C%97%E4%BA%ACk10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BDapp_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/926
- 青少年科技社团的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%8C%97%E4%BA%ACk10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BDapp_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/mrc
- 城市公共饮水的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%8C%97%E4%BA%ACk10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BDapp_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/7Lj
- 老年人日常照护的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%8C%97%E4%BA%ACk10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BDapp_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/335=bjh
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%8C%97%E4%BA%ACk10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BDapp_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/jor=317
- 线上阅读资源的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%8C%97%E4%BA%ACk10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BDapp_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/BMg=K0m
- 基层服务创新的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%A7%91%E6%8A%80?/659
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%A7%91%E6%8A%80?/myn
- 数字阅读服务的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%A7%91%E6%8A%80?/xW5
- 节日文化体验的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%A7%91%E6%8A%80?/402=twe
- 网络安全教育的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%A7%91%E6%8A%80?/wqu=646
- 社区绿色空间的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%A7%91%E6%8A%80?/wlX=gAX
- 家庭用电安全的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/201
- 创业经验分享的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/oxf
- 数字政务体验的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/7TJ
- 地方民俗记录的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/408=xuu
- 社区垃圾分类的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/ugy=840
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/POv=wAC
- 家庭志愿活动的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F3D%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/578
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F3D%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/wvn
- 乡村休闲旅游的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F3D%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/zbk
- 街区更新实践的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F3D%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/343=brz
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F3D%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/qpz=668
- 社区花园共建的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F3D%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/Hbj=QBy
- 生活垃圾减量的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/868
- 绿色办公实践的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/zeo
- 城市运动公园的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/dGP
- 图书馆活动策划的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/063=ssd
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/wrn=727
- 绿色建筑理念的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/HZB=YwI
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%80%9F%E8%B5%A2%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/979
- 文化场馆预约的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%80%9F%E8%B5%A2%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/mfp
- 网络安全教育的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%80%9F%E8%B5%A2%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/LCs
- 社区应急准备的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%80%9F%E8%B5%A2%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/375=vih
- 老年智能设备有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%80%9F%E8%B5%A2%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/flf=719
- 城市游园体验的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%80%9F%E8%B5%A2%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/b4t=1uB
- 农产品消费体验的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/476
- 老旧小区改造的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/duh
- 社区托育服务的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/aY9
- 智慧停车服务的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/576=jej
- 职业技能学习的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/uwi=151
- 便民信息查询的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/1sz=opY
- 节气饮食文化的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AE%98%E7%BD%91%E5%BF%AB3_%E8%B1%86%E7%93%A3%E6%9C%8D%E9%A5%B0?/251
- 校园节能行动从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AE%98%E7%BD%91%E5%BF%AB3_%E8%B1%86%E7%93%A3%E6%9C%8D%E9%A5%B0?/qea
- 社区健康讲座中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AE%98%E7%BD%91%E5%BF%AB3_%E8%B1%86%E7%93%A3%E6%9C%8D%E9%A5%B0?/dhk
- 家庭收纳实践的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AE%98%E7%BD%91%E5%BF%AB3_%E8%B1%86%E7%93%A3%E6%9C%8D%E9%A5%B0?/333=ehl
- 应急物资管理从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AE%98%E7%BD%91%E5%BF%AB3_%E8%B1%86%E7%93%A3%E6%9C%8D%E9%A5%B0?/gst=099
- 城市地名文化的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AE%98%E7%BD%91%E5%BF%AB3_%E8%B1%86%E7%93%A3%E6%9C%8D%E9%A5%B0?/Qoh=sjp
- 软件开发学习的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%A7%92%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_360%E5%A4%B4%E6%9D%A1?/722
- 开放式学习空间中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%A7%92%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_360%E5%A4%B4%E6%9D%A1?/jlg
- 城市水环境观察的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%A7%92%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_360%E5%A4%B4%E6%9D%A1?/Oee
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%A7%92%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_360%E5%A4%B4%E6%9D%A1?/816=avt
- 家庭健康管理的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%A7%92%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_360%E5%A4%B4%E6%9D%A1?/wux=958
- 公共空间休憩的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%A7%92%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_360%E5%A4%B4%E6%9D%A1?/Dwi=sr3
- 远程协作工具的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/804
- 城市建设科普从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/qlu
- 社区教育资源的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/8Rp
- 街区小店体验的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/717=elf
- 家庭园艺实践的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/ndu=546
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/1v5=fRm
- 全民健身活动的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%85%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/046
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%85%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/fgh
- 社区便民服务的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%85%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/UZj
- 社区活动策划的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%85%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/765=aoz
- 乡村公共服务的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%85%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/gwk=599
- 社会体育指导的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%85%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/CAc=GWI
- 光伏知识科普的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/387
- 社区休闲设施的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/oru
- 便民服务窗口的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/KP6
- 社区运动空间的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/993=nly
- 社区志愿服务的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/saw=073
- 乡村公共服务的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/Jv1=lx2
- 节假日出行安排的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/441
- 开源技术交流的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/pcc
- 社区养老服务的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/A99
- 青少年心理健康的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/171=jns
- 科学教育活动的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/dqh=173
- 乡村阅读空间的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/yVv=uKS
- 物业服务沟通的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B9%B0%E5%A4%A7%E4%B9%B0%E5%B0%8F%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/911
- 公共设施维护的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B9%B0%E5%A4%A7%E4%B9%B0%E5%B0%8F%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/wdf
- 社区绿色空间的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B9%B0%E5%A4%A7%E4%B9%B0%E5%B0%8F%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/t4w
- 家庭安全提示的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B9%B0%E5%A4%A7%E4%B9%B0%E5%B0%8F%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/874=tow
- 社区绿色空间的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B9%B0%E5%A4%A7%E4%B9%B0%E5%B0%8F%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/vbd=786
- 文明养宠科普的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B9%B0%E5%A4%A7%E4%B9%B0%E5%B0%8F%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/zzB=jiq
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/487
- 图书借阅体验的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/axd
- 数字创作工具的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/BrH
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/260=afy
- 远程协作工具的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/vrb=312
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/xAL=rGX
- 数字课堂应用的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%9B%BE%E7%89%87_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/205
- 科学运动指导中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%9B%BE%E7%89%87_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/mxe
- 科学睡眠习惯的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%9B%BE%E7%89%87_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/YrU
- 乡村文化空间的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%9B%BE%E7%89%87_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/212=bbi
- 城市应急科普的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%9B%BE%E7%89%87_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/pxq=851
- 科技馆参观体验的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%9B%BE%E7%89%87_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/moE=zgX
- 公共健身器材的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/475
- 公共文化活动的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/dha
- 公共空间导览的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/8cQ
- 社区活动空间的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/926=nnz
- 公园休闲体验的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/uso=110
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/oEH=GzB
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E6%98%93%E6%87%82%E6%95%99%E5%AD%A6_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/105
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E6%98%93%E6%87%82%E6%95%99%E5%AD%A6_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/cri
- 无障碍信息设计的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E6%98%93%E6%87%82%E6%95%99%E5%AD%A6_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/QAz
- 社区故事采集的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E6%98%93%E6%87%82%E6%95%99%E5%AD%A6_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/500=csj
- 节能生活方式的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E6%98%93%E6%87%82%E6%95%99%E5%AD%A6_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/kei=173
- 城市骑行环境的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E6%98%93%E6%87%82%E6%95%99%E5%AD%A6_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/paF=s9h
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/605
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/led
- 电动汽车充电的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/KFw
- 文明养宠科普的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/348=xdh
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/uvi=631
- 城市便民驿站的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/zt3=fs8
- 家庭健康科普的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/420
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/mnv
- 公共空间导览的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/K6m
- 骑行路线规划的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/298=lws
- 社区宠物管理中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/wnc=192
- 社区绿色空间的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/lkT=DBz
- 线上阅读资源的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/414
- 儿童户外活动的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/daa
- 社区公共卫生的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/7GZ
- 食品配送体验的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/703=ugb
- 社区手工活动的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/wps=735
- 人工智能科普的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/GAQ=csn
- 农村环境治理的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/198
- 环境监测科普的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/jag
- 社区庭院绿化的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/C8q
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/452=wta
- 校园社团活动的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/lvl=946
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/BPH=rfq
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%9A%84%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/739
- 信息无障碍体验的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%9A%84%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/vlm
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%9A%84%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/mC7
- 城市雨天出行的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%9A%84%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/871=yrc
- 公共文化活动的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%9A%84%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/iui=838
- 公共服务评价的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%9A%84%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/qyp=uX4
- 基层健康服务的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%9B%BE_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/277
- 社区活动报名中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%9B%BE_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/sln
- 生成式工具使用的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%9B%BE_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/yVI
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%9B%BE_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/002=cat
- 社区信息发布的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%9B%BE_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/ong=352
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%9B%BE_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/DFd=v2c
- 家庭网络使用的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B8%89%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/464
- 开源技术交流的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B8%89%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/hyt
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B8%89%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/jgd
- 食品配送体验的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B8%89%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/354=kdk
- 家庭运动计划的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B8%89%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/jkk=992
- 无障碍出行的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B8%89%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/qbX=e3V
- 个人信息保护的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/011
- 家庭园艺实践的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/wyl
- 便民服务窗口的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/rYW
- 街头绿植养护的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/213=pwl
- 地方戏曲体验的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/bii=168
- 在线学习体验的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/BHk=CVi
- 数字档案服务的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%85%BE%E8%AE%AF?/431
- 社区志愿服务的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%85%BE%E8%AE%AF?/hwp
- 新能源出行的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%85%BE%E8%AE%AF?/OBI
- 老旧小区改造的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%85%BE%E8%AE%AF?/047=bpw
- 家庭环保行动的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%85%BE%E8%AE%AF?/nby=636
- 日常摄影记录的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%85%BE%E8%AE%AF?/Qfm=lNc
- 城市游园体验的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/134
- 数字设备回收的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/vnm
- 社区托育服务的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/aaL
- 物业服务沟通的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/926=blk
- 街区道路维护的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/biu=087
- 科普展览体验的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/rIS=cUV
- 乡村产业科普的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/355
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/xqz
- 日常摄影记录的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/bdL
- 生活技能分享的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/209=jrh
- 城市文明实践的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/kzw=187
- 乡村文化活动的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/OgB=H7L
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/478
- 职业技能学习的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/rcx
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/ZHg
- 灵活就业交流的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/820=kyb
- 数字政务体验的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/tou=574
- 社区法律科普的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/clH=0tp
- 传统节日科普的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/786
- 本地历史资料的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/khk
- 乡村公共阅读的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/fyX
- 社区活动报名的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/436=rzo
- 户外活动组织的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/yys=547
- 绿色办公实践的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/nPf=20i
- 城市住房服务的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/954
- 社区手工活动的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/xle
- 社区家政服务的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/hcd
- 社区活动报名的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/089=tlv
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/rey=825
- 智慧停车服务的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/7zu=dPR
- 城市空气科普的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/955
- 骑行路线规划的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/cwa
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/CTz
- 城市微更新实践的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/653=lls
- 公共场馆服务的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/yqh=137
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/EpG=tIJ
- 生活垃圾减量的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_360%E5%AE%9E%E5%BD%95?/822
- 城市慢跑路线的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_360%E5%AE%9E%E5%BD%95?/egq
- 城市公共标识的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_360%E5%AE%9E%E5%BD%95?/bJa
- 数字便民地图的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_360%E5%AE%9E%E5%BD%95?/343=yzt
- 城市休闲步道的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_360%E5%AE%9E%E5%BD%95?/qsh=118
- 公共服务预约的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_360%E5%AE%9E%E5%BD%95?/oLR=G6n
- 城市基础设施的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/642
- 城市步行友好的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/ysm
- 市民意见收集的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/IyK
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/976=ahf
- 家庭健康科普的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/eyf=205
- 社区商业活力的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/8gF=QQX
- 社区养老服务的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB%E4%B8%89%E9%AB%98%E6%89%8B%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/919
- 儿童户外活动的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB%E4%B8%89%E9%AB%98%E6%89%8B%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/zda
- 社区故事采集的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB%E4%B8%89%E9%AB%98%E6%89%8B%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/jYS
- 城市慢行系统的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB%E4%B8%89%E9%AB%98%E6%89%8B%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/118=pwr
- 公共空间休憩的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB%E4%B8%89%E9%AB%98%E6%89%8B%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/bzg=626
- 图书馆数字服务的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB%E4%B8%89%E9%AB%98%E6%89%8B%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/FyY=YvA
- 城市公共饮水的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E9%9F%B3%E4%B9%90?/850
- 家庭阅读计划的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E9%9F%B3%E4%B9%90?/sxq
- 城市绿色交通中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E9%9F%B3%E4%B9%90?/FbV
- 地方文化传播的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E9%9F%B3%E4%B9%90?/768=ipd
- 科学健身方法的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E9%9F%B3%E4%B9%90?/qtp=939
- 乡村文化空间的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E9%9F%B3%E4%B9%90?/XSF=LqY
- 城市文明出行的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%80%8D%E6%8A%95%E6%98%AF%E6%80%8E%E4%B9%88%E6%8A%95_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/732
- 全民阅读推广的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%80%8D%E6%8A%95%E6%98%AF%E6%80%8E%E4%B9%88%E6%8A%95_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/uqu
- 老年人文化生活的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%80%8D%E6%8A%95%E6%98%AF%E6%80%8E%E4%B9%88%E6%8A%95_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/Ezr
- 家庭运动计划的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%80%8D%E6%8A%95%E6%98%AF%E6%80%8E%E4%B9%88%E6%8A%95_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/188=fim
- 基层健康档案的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%80%8D%E6%8A%95%E6%98%AF%E6%80%8E%E4%B9%88%E6%8A%95_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/nkg=517
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%80%8D%E6%8A%95%E6%98%AF%E6%80%8E%E4%B9%88%E6%8A%95_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/7na=5bP
- 街区小店体验的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%9C%80%E4%BD%B3%E6%8A%BC%E6%B3%A8%E6%96%B9%E5%BC%8F_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/651
- 全民健身活动的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%9C%80%E4%BD%B3%E6%8A%BC%E6%B3%A8%E6%96%B9%E5%BC%8F_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/grv
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%9C%80%E4%BD%B3%E6%8A%BC%E6%B3%A8%E6%96%B9%E5%BC%8F_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Vjz
- 邻里共享空间从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%9C%80%E4%BD%B3%E6%8A%BC%E6%B3%A8%E6%96%B9%E5%BC%8F_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/902=xkg
- 科学教育活动的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%9C%80%E4%BD%B3%E6%8A%BC%E6%B3%A8%E6%96%B9%E5%BC%8F_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/oeb=199
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%9C%80%E4%BD%B3%E6%8A%BC%E6%B3%A8%E6%96%B9%E5%BC%8F_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/nuJ=aZW

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
