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

- 老年友好服务的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/893
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/vpn
- 社区宠物管理的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/HIW
- 街区绿化养护的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/862=dbk
- 城市文明出行的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/vxo=206
- 乡村阅读活动的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/Sz7=FFK
- 环境教育课程的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%94%BE?/517
- 基层健康服务的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%94%BE?/ynb
- 周末休闲规划的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%94%BE?/yZa
- 城市适老服务的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%94%BE?/116=jhv
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%94%BE?/jwd=796
- 社区活动策划的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%94%BE?/Mev=V8M
- 学校食育活动的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%BD%E9%99%85?/103
- 节能生活方式的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%BD%E9%99%85?/iwu
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%BD%E9%99%85?/yz1
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%BD%E9%99%85?/382=zxt
- 青少年科普实践的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%BD%E9%99%85?/ohv=969
- 社区养老服务的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%BD%E9%99%85?/fqm=yvP
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/425
- 电子商务服务的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/ods
- 城市树木认养的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/eDO
- 社区宣传栏更新的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/484=eee
- 社区知识分享的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/ect=429
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/uyZ=3dS
- 个人数据管理的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/439
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/itw
- 家庭收纳实践的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/W0g
- 街区道路维护的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/673=ufz
- 青少年科普实践的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/yfw=694
- 乡村电商实践的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/4ey=SG0
- 家庭理财科普的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/866
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/sje
- 城市水环境观察的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/d7C
- 社区花园共建的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/037=aun
- 公共设施维护的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/tpl=683
- 市民热线服务的日常实践笔记 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/AL6=4El
- 乡村文化空间的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/809
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/ngh
- 城市基础设施的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/Ciy
- 公共设施使用的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/497=hwv
- 数字公共文化的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/knn=202
- 城市夜间生活的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/wjW=jEO
- 家庭饮食安排的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/334
- 社区慢性病防控的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/gjb
- 健康信息获取的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/PFr
- 地方民俗记录的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/677=qhq
- 绿色快递包装的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/kvg=229
- 绿色办公实践的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/wEo=rC9
- 社区邻里服务中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/074
- 城市文化路线从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/lfy
- 社区宣传栏更新的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/DmK
- 城市可持续生活中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/873=zus
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/cbi=488
- 科技馆参观体验的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/IU5=xjw
- 数字素养提升的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/170
- 亲子科普活动的流程优化思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/upn
- 老年运动活动的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/1tS
- 家庭急救准备的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/398=bvd
- 电子商务服务的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ahf=257
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/9cX=ZAb
- 开放数据应用的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/724
- 儿童友好空间的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/wfl
- 城市适老服务的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/4iC
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/532=hbc
- 科技馆参观体验的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/doh=805
- 家庭陪伴活动的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/VDE=lP3
- 数据分析入门的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/296
- 社区便民集市的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/lzc
- 公共空间休憩的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/A7Q
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/012=fdy
- 租房信息服务的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/jtm=046
- 家庭运动计划的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/BBx=tKi
- 市民热线服务的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/625
- 老年友好服务的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/kgi
- 新能源出行的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/7XQ
- 休闲运动入门的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/629=dmp
- 绿色建筑理念的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/qle=668
- 校园阅读活动的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/xfo=UN7
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/035
- 城市基础设施中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/kxg
- 城市住房服务中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/KT6
- 无障碍信息设计的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/733=nqu
- 社区休闲设施的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/eyr=198
- 安全出行教育的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/wFx=RGy
- 社区健康讲座中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/251
- 社区垃圾分类的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/myb
- 电动汽车充电的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/SUA
- 公共服务指南的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/247=ncq
- 生成式工具使用的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/akc=510
- 公共空间安全的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/TWa=PyP
- 家庭健康管理的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-APP_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/705
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-APP_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/ljh
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-APP_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/fMf
- 城市适老服务的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-APP_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/687=efu
- 居民健康教育的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-APP_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/xli=600
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%BB%A1%E5%A0%82%E5%BD%A9-APP_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/xqb=8ZF
- 家庭运动计划的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%89%B9%E7%A8%BF?/109
- 农业科普体验的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%89%B9%E7%A8%BF?/ibe
- 社区法律科普的服务质量观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%89%B9%E7%A8%BF?/i7r
- 老年人日常照护的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%89%B9%E7%A8%BF?/041=ggn
- 社区菜市场服务的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%89%B9%E7%A8%BF?/ixo=924
- 居家防滑改造的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%89%B9%E7%A8%BF?/btO=ALu
- 基层健康服务的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/531
- 街区小店体验的公共参与指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/ard
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/MtC
- 开源技术交流的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/202=wxt
- 居民健康教育的参与方式与路径 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/tvu=486
- 儿童运动体验的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/nY7=VoF
- 社区活动报名的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/370
- 绿色校园实践的日常管理方法 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/jxz
- 城市人文观察的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/U7x
- 家庭运动计划的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/836=fye
- 新能源出行的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/ofu=573
- 生活垃圾减量的入门知识整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/EwS=GVi
- 家庭教育交流的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/113
- 社区交通安全的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/kwi
- 地方民俗记录的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/nYA
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/004=hai
- 社区读书角建设的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/kqk=517
- 社区协商议事的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/po3=VpA
- 智能手机助老的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%AF%BB%E5%9B%BE?/277
- 新能源知识普及的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%AF%BB%E5%9B%BE?/iow
- 数字艺术创作的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%AF%BB%E5%9B%BE?/3D8
- 城市社区治理的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%AF%BB%E5%9B%BE?/673=ext
- 公园休闲体验中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%AF%BB%E5%9B%BE?/kgy=559
- 街区道路维护中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%AF%BB%E5%9B%BE?/Y1z=hNk
- 绿色快递包装的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/440
- 地方美食文化的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/crz
- 公园亲子设施的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/6xe
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/827=yqp
- 街区更新实践的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/xfg=493
- 食品安全科普的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/qCj=cb8
- 电动汽车充电的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/106
- 数字创作工具的家庭参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/uov
- 节能生活方式的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/uJj
- 社区便利生活的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/650=ypf
- 地方文化传播的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/fwy=678
- 终身学习资源的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/aD2=US9
- 气象科普传播的居民参与机会 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/067
- 家庭环保行动的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/krk
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/PHx
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/267=cxm
- 骑行路线规划的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/onk=809
- 城市应急科普的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%BB%A1%E5%A0%82%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/Qmc=qIK
- 个人信息保护的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E8%AF%84%E8%AE%BA?/471
- 社区便利生活的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E8%AF%84%E8%AE%BA?/wng
- 线上办事服务的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E8%AF%84%E8%AE%BA?/MHG
- 数字设备回收的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E8%AF%84%E8%AE%BA?/357=dya
- 社区养老服务的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E8%AF%84%E8%AE%BA?/rjt=324
- 城市共享单车的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E8%AF%84%E8%AE%BA?/dge=AFZ
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/769
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/eoz
- 节约用水实践的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/a1d
- 社区学习活动的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/728=ufs
- 数字艺术创作的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/dkk=641
- 邻里互助活动的日常使用指南 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BB%A1%E5%A0%82%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/LUL=DId
- 老年数字阅读的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0?/487
- 消防知识宣传的线下体验记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0?/hrb
- 城市应急科普的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0?/fFJ
- 图书馆活动策划的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0?/215=ysl
- 老年友好服务中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0?/gqf=154
- 乡村文化活动的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0?/pKJ=fRh
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%BD%A9%E7%A5%A8?/676
- 城市噪声观察的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%BD%A9%E7%A5%A8?/ahr
- 绿色办公实践的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%BD%A9%E7%A5%A8?/Kps
- 城市生活服务的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%BD%A9%E7%A5%A8?/384=ojr
- 信息无障碍体验的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%BD%A9%E7%A5%A8?/uez=661
- 志愿者培训交流的资源利用方法 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%BD%A9%E7%A5%A8?/u1D=uG8
- 绿色办公实践的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/048
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/mtr
- 生活服务数字化的基础设施观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/tL7
- 青少年编程学习的便民做法梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/022=xnx
- 城市社区治理的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/yem=385
- 社区活动策划的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/rfv=I3i
- 城市基础设施的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/640
- 城市微更新实践的活动组织技巧 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/iyg
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/cFp
- 图书借阅体验的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/898=ksk
- 社区菜市场服务的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/ybh=046
- 生活垃圾回收的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/DfY=Whz
- 城市绿道建设的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%86%9B%E4%BA%8B?/058
- 数字课堂应用的活动体验回顾 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%86%9B%E4%BA%8B?/zfy
- 城乡交流活动的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%86%9B%E4%BA%8B?/mHR
- 城市运动公园的社区参与观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%86%9B%E4%BA%8B?/048=jnn
- 开源技术交流的空间设计要点 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%86%9B%E4%BA%8B?/cfv=922
- 绿色办公实践的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%86%9B%E4%BA%8B?/VkD=aM5
- 邻里共享空间的常见问题梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/018
- 社区应急准备的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/slz
- 家庭急救准备的持续改进方向 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/MJE
- 乡村阅读空间的便利性观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/846=tsu
- 本地历史资料的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/chn=891
- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/w5b=rhP
- 信息无障碍体验的服务体验观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/920
- 文化讲座服务的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/jrm
- 就业技能培训的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/Avy
- 城市绿色交通的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/813=hwy
- 社区活动空间的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/rsr=320
- 乡村生活观察的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/iMS=xSD
- 科学观察活动的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/229
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/uyx
- 课后服务体验的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/oTf
- 生活服务数字化的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/502=ybj
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/kwz=093
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/4lk=PWo
- 社区艺术活动的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%83%AD%E6%A6%9C?/463
- 社区花园共建的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%83%AD%E6%A6%9C?/gsg
- 生活垃圾减量的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%83%AD%E6%A6%9C?/264
- 地方美食文化的社区行动案例 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%83%AD%E6%A6%9C?/101=ljm
- 城市博物馆活动的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%83%AD%E6%A6%9C?/oyc=524
- 社区活动报名的常见误区提醒 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%83%AD%E6%A6%9C?/b32=AtV
- 城市水环境观察的便捷程度观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/999
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/bay
- 社区共享书架的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/t1Y
- 公共场所导视的数字工具使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/687=xph
- 儿童友好街区的数字化应用观察 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/ffa=441
- 家庭用电安全的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/dcF=Gh2
- 社区安全巡查的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/227
- 个人信息保护的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/kac
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/1Sl
- 老年智能设备的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/041=xjt
- 居民健康教育中的沟通与协作 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/mya=220
- 学校食育活动中的几个关键细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/Krb=4uw
- 社区慢性病防控的活动策划思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/739
- 社区垃圾回收的协作机制梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/gfj
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/kDw
- 乡村生态观察的执行流程参考 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/127=gve
- 城市夜间生活的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/zvl=178
- 日常摄影记录的实际需求与回应 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/htk=QEd
- 健康步道使用的学习资源整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%AC%E5%91%8A?/901
- 社区共享书架的长期维护要点 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%AC%E5%91%8A?/chp
- 便民服务窗口的空间使用体验 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%AC%E5%91%8A?/OAf
- 社区互助网络的安全使用提示 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%AC%E5%91%8A?/798=pis
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%AC%E5%91%8A?/yyy=939
- 读书会组织的儿童友好细节 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%AC%E5%91%8A?/Be8=pPP
- 社区学习活动的日常记录与分享 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/109
- 老年运动活动的协商参与方式 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/fby
- 公共文化活动的家庭实践清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/BqC
- 老年人文化生活的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/001=ttz
- 街道综合服务的服务信息整理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/ezz=985
- 线上阅读资源的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/e5S=CK4
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/514
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/abg
- 基层健康档案的设施维护观察 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/KmW
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/636=riv
- 社区手工活动的实用信息清单 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/icc=405
- 电动汽车充电的资源整合思路 |来源：https://github.com/baileykatie82/wagc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/qUY=bFv
- 社区运动空间的行动步骤参考 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/734
- 城市建设科普的阅读与学习资源 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/rcr
- 图书馆活动策划的组织方法与经验 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/VHh
- 周末休闲规划的适老服务细节 |来源：https://github.com/baileykatie82/wagc/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E6%BB%A1%E5%A0%82%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/749=kgi

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
