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

- 地方戏曲体验的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/hvq=091
- 数据分析入门的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/Lr6=Q8y
- 传统节日科普的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/617
- 数字艺术创作的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/stq
- 环境教育课程的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/KMn
- 社区垃圾分类的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/307=czw
- 小区停车协商的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/sax=726
- 骑行路线规划的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/33u=w5y
- 社区便民集市的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/564
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/zsr
- 运动安全知识的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/GNG
- 农村环境治理的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/308=jip
- 社区托育服务的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/fmt=494
- 城市公共厕所的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/xf1=vmB
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%9B%86?/978
- 街区小店体验的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%9B%86?/rkj
- 本地旅行体验的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%9B%86?/20t
- 社区宣传栏更新的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%9B%86?/924=osl
- 旧物循环利用的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%9B%86?/rwn=139
- 公共交通接驳的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%9B%86?/crT=Tkz
- 创业经验分享的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/042
- 在线学习体验的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/gkz
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/koa
- 城市共享单车的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/015=avu
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/idh=497
- 城市公共厕所的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/dx0=1qs
- 公共空间导览的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/864
- 社区邻里服务的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/yrb
- 城市公共艺术中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/m64
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/206=aay
- 网络信息辨识的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/siq=424
- 居民健康教育的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/ENz=CnF
- 社区花园共建的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%82%A1%E7%A5%A8?/610
- 社区快递服务的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%82%A1%E7%A5%A8?/ndx
- 智慧停车服务的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%82%A1%E7%A5%A8?/4zt
- 健康信息获取的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%82%A1%E7%A5%A8?/369=lie
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%82%A1%E7%A5%A8?/gtk=314
- 家庭安全提示的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%82%A1%E7%A5%A8?/AJ6=gEm
- 机器人科普活动的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/724
- 家庭节能实践的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/ykp
- 社区便利生活的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/zWR
- 社区体育组织的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/396=fqh
- 社区文化节活动的绿色实践方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/csg=426
- 应急物资管理的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/F8U=aUk
- 城市运动公园的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/365
- 老年运动活动的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vqe
- 智慧城市体验的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ea0
- 文化场馆预约从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/640=hrs
- 科学教育活动的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ipq=290
- 在线教育体验的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/PF4=frk
- 乡村公共文化的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/798
- 文化场馆预约的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/vwz
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/vGs
- 社区生活指南的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/246=ihz
- 公共服务沟通的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/ner=848
- 社区快递服务的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/oNC=sj3
- 公共文化活动的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/748
- 开源技术交流的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/uez
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/z5L
- 校园阅读活动的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/443=dzl
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/kwq=267
- 无障碍信息设计的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/muz=LQG
- 生活垃圾减量的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/278
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/obs
- 职业技能学习的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/GcD
- 社区生活指南的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/117=yre
- 社区休闲设施的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/tna=056
- 街道综合服务的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/hLP=i4o
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/394
- 数字创意课程的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/xlt
- 灵活就业交流的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/HmW
- 公共服务评价的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/280=zpn
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/htt=332
- 公共卫生设施的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/nob=c87
- 家庭食品保存中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/520
- 青年就业服务的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/azu
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/54A
- 志愿者培训交流的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/802=bau
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/izb=159
- 公共服务咨询的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/Pqd=L5o
- 社区防暑服务的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/800
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/aig
- 节能家电使用的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/SGD
- 校园阅读活动的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/002=bmw
- 青年志愿活动的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/eiy=143
- 城市基础设施的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/1R1=CZK
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/472
- 小区电梯维护的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/amr
- 城市展览体验的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/eMg
- 社区快递服务的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/317=pvq
- 社区交通安全的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/jbq=377
- 家庭理财科普的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/sCP=pw6
- 社区设施共享的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89?/102
- 城市展览体验有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89?/oip
- 居家适老化改造的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89?/4Kq
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89?/639=rpt
- 公共服务评价的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89?/mxx=497
- 科学教育活动的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89?/VZc=1KX
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/855
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/orm
- 居民健康教育的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/rY8
- 家庭运动计划的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/665=ecl
- 城市展览体验的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/gsf=543
- 智慧停车服务的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/RGk=7SH
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/179
- 数字档案服务的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/ftn
- 城市文明实践的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/Lrh
- 社区艺术活动的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/946=qry
- 儿童友好空间的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/xwm=072
- 校园社团活动的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/hJ9=NeN
- 社区艺术活动的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/070
- 社区儿童活动的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/aau
- 家庭节能设备的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/fYu
- 公共空间安全的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/328=tqa
- 校园社团活动的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/ngi=217
- 地方戏曲体验的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/aq0=bbp
- 社区花园共建的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/297
- 城市夜间照明的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/pgx
- 远程协作工具的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/wQs
- 城市适老服务的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/410=foz
- 城乡交通衔接的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/lfo=842
- 小区公共照明的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/pBm=818
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/141
- 家庭园艺实践的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/srn
- 便民服务窗口的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/4Mf
- 街区更新实践的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/551=ltx
- 社区老年食堂的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/zzp=987
- 地方旅游导览的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/npi=3XV
- 社区便民集市的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/999
- 科学教育活动的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ofr
- 社区法律科普的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/aZJ
- 公共场馆服务的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/326=itc
- 应急物资管理的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/lwz=343
- 公共交通信息服务的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/62T=Ixv
- 社区共享书架的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/268
- 节日文化体验的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/wyv
- 图书借阅体验的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/6ge
- 志愿服务平台的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/540=twp
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/myo=773
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/7N3=L0G
- 数字资源检索的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/988
- 家庭陪伴活动的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/ppv
- 新能源出行中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/lQN
- 城市体育设施的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/693=oaw
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/kbx=270
- 邻里互助活动的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/52b=l1r
- 公共空间照明的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/791
- 城市树木认养的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/fgd
- 社区手工活动的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/Olt
- 城市步行环境的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/103=nxb
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/duf=194
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/ne4=ner
- 职业技能学习的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/746
- 社区应急准备的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/uyo
- 校园社团活动中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/JAC
- 健康步道使用的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/033=fbm
- 智慧停车服务的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/eeh=549
- 社区读书角建设的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/1C0=goi
- 家庭安全提示的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/204
- 信息无障碍体验的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/qsp
- 城市休闲步道的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/fGZ
- 社会体育指导的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/696=fzp
- 市民热线服务的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/gpy=725
- 软件开发学习的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/svb=1TF
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/612
- 青少年心理健康的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/cua
- 地方美食文化的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/EhL
- 消防知识宣传的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/115=esk
- 乡村电商实践的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/zzx=241
- 城市公共自行车的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/oB9=WjC
- 文化场馆预约的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/801
- 社区消防演练的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/hth
- 城市微更新实践的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/vZ7
- 文化场馆预约的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/144=rwy
- 数字素养提升的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/fjd=216
- 传统节日科普的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/MEW=ZyR
- 本地历史资料的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/841
- 校园阅读活动的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/pgr
- 数字阅读服务的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/M3X
- 社区老年食堂的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/336=snh
- 社区停车服务的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/znn=885
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/Rjx=jG2
- 城市休闲步道的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0?/313
- 便民信息查询中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0?/wcv
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0?/I3S
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0?/025=eer
- 城市公共标识的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0?/hkq=526
- 小微企业服务的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0?/s0Z=EP9
- 社区家校合作的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/337
- 城市水环境观察的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/cqc
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/D48
- 公益活动组织的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/317=tuv
- 青年志愿活动中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/ogy=994
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/53H=lTB
- 城市树木认养的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/322
- 创业经验分享的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/ydf
- 无障碍出行的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/vLW
- 网络安全教育的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/206=qok
- 青年就业服务中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/egl=830
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/z6e=6Nd
- 节约用水实践的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/902
- 校园阅读活动的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/tlm
- 社区环保活动的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/uMw
- 智慧城市体验的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/344=obp
- 在线教育体验的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/nsm=463
- 图书借阅体验的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/svC=RJh
- 绿色消费选择的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/183
- 家庭园艺实践的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/qal
- 社区老年食堂的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/VuG
- 图书借阅体验的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/951=ukw
- 城乡交通衔接的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/mbv=520
- 健康步道使用的基础知识问答 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/uUn=wEQ
- 光伏知识科普的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/286
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/lxn
- 个人信息保护的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/WdB
- 城市骑行环境的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/138=ejr
- 城市噪声观察的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/bde=025
- 街头绿植养护的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/2k5=z0A
- 校园安全教育的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E7%A4%BE%E8%AE%BA?/700
- 社区活动空间的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E7%A4%BE%E8%AE%BA?/thx
- 公共交通接驳的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E7%A4%BE%E8%AE%BA?/p0V
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E7%A4%BE%E8%AE%BA?/686=ehy
- 家庭志愿活动的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E7%A4%BE%E8%AE%BA?/rgn=008
- 社区养老服务的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E7%A4%BE%E8%AE%BA?/7fE=8io
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/099
- 街头绿植养护的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/xvk
- 城市骑行环境的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/SAn
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/363=ira
- 社区便民集市的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/cyo=217
- 城市夜间生活的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/6MO=R2B
- 便民信息查询的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/347
- 社区环保活动的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/svm
- 远程协作工具的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/ijO
- 文化讲座服务的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/001=kwy
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/wbn=217
- 网络安全教育的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/Kg9=63D
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/891
- 数字地图应用的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/rji
- 志愿服务平台的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/QKM
- 乡村产业科普的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/079=nmq
- 传统节日科普的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/czo=530
- 家庭健康管理的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/pJx=oz9
- 低碳社区实践的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/843
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/woy
- 家庭阅读计划的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/5yV
- 家庭教育交流的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/074=fid
- 社区修缮行动的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/mbv=165
- 职业技能学习的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/Qh5=qJY
- 家庭用电安全的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/102
- 便民信息查询的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/wvs

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
