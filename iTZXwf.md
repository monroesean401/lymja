# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 公益活动组织的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_360%E7%9B%B4%E6%92%AD?/204
- 机器学习入门的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_360%E7%9B%B4%E6%92%AD?/kap
- 乡村公共服务的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_360%E7%9B%B4%E6%92%AD?/FVL
- 基层健康服务的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_360%E7%9B%B4%E6%92%AD?/813=rat
- 运动安全知识的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_360%E7%9B%B4%E6%92%AD?/ttb=159
- 校园安全教育的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_360%E7%9B%B4%E6%92%AD?/XFd=8Qg
- 乡村生态旅游的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/417
- 家庭安全提示的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/hbm
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/kT3
- 数字便民地图的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/102=fxj
- 社区消防演练的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/vip=095
- 公共服务咨询的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/mtV=IVr
- 老年人日常照护的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/353
- 家庭照护支持的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/hfi
- 社区互助网络的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/lfL
- 线上阅读资源的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/587=wjt
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/oiu=137
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/15E=l1A
- 公共服务数字化的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/882
- 社区活动报名的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/qms
- 街道综合服务的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/Dlq
- 职业技能学习的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/734=wnt
- 安全出行教育的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/ozv=506
- 城市公共标识的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/k1N=rOb
- 城市农夫市集的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/242
- 社区便民服务的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/ydn
- 绿色出行服务的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/auW
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/833=qyw
- 农村环境治理的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/uwq=242
- 公共服务数字化的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/CL4=cYs
- 家庭环保行动的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A4%BE%E5%8C%BA?/553
- 数字设备回收的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A4%BE%E5%8C%BA?/dfs
- 绿色办公实践的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A4%BE%E5%8C%BA?/SjG
- 社区邻里服务的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A4%BE%E5%8C%BA?/614=eqg
- 居家适老化改造的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A4%BE%E5%8C%BA?/jei=407
- 城市休闲步道的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A4%BE%E5%8C%BA?/u3i=fIf
- 社区艺术活动的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%8A%95%E7%A8%BF?/957
- 城市雨天出行的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%8A%95%E7%A8%BF?/xay
- 居家适老化改造的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%8A%95%E7%A8%BF?/GIt
- 老年学习活动的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%8A%95%E7%A8%BF?/661=xay
- 老年智能设备的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%8A%95%E7%A8%BF?/fyd=137
- 城乡公共服务的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%8A%95%E7%A8%BF?/sf1=7Qo
- 社区商业活力的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/480
- 社区艺术活动的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/mqi
- 城市体育设施的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/BRp
- 节日文化体验的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/639=pvr
- 文明养宠科普中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/ihz=475
- 社区停车服务的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/lxI=50z
- 社区文化传播从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/985
- 骑行路线规划的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/tlu
- 传统手工艺体验的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/rdc
- 城市公共标识的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/231=wdy
- 社区文化节活动的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/dhb=617
- 城市公共空间的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/vFg=zEg
- 城市公共艺术的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/100
- 社区体育组织的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/utr
- 城市建设科普的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/7G4
- 创业经验分享的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/478=tte
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/zky=573
- 乡村电商实践的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/V0e=zg1
- 青少年科技社团的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/508
- 开放式学习空间的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/sgp
- 社区生活指南的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/f4b
- 城市基础设施的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/389=rfp
- 公园休闲体验的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/dee=274
- 社区邻里服务的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/MCS=jAb
- 社区环保活动的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/198
- 社区故事采集的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/ulu
- 城市慢跑路线的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/5o3
- 街区道路维护中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/746=txc
- 市民热线服务的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/glg=982
- 城市展览体验的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/daD=4iT
- 青少年科普实践的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/938
- 传统节日科普的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/gaw
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/ZLU
- 社区共享书架的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/998=zjm
- 农产品品牌传播的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/sqn=418
- 公共空间导览的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/9rC=bzw
- 亲子科普活动的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E8%8A%92%E6%9E%9C%E6%97%85%E6%B8%B8?/941
- 城市适老服务的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E8%8A%92%E6%9E%9C%E6%97%85%E6%B8%B8?/tjs
- 社区便利生活的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E8%8A%92%E6%9E%9C%E6%97%85%E6%B8%B8?/vmZ
- 垃圾分类指导的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E8%8A%92%E6%9E%9C%E6%97%85%E6%B8%B8?/446=zny
- 科学信息获取的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E8%8A%92%E6%9E%9C%E6%97%85%E6%B8%B8?/hjr=873
- 家庭教育交流的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E8%8A%92%E6%9E%9C%E6%97%85%E6%B8%B8?/q2b=n5Z
- 基层健康档案的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/454
- 本地旅行体验的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/qnx
- 健康饮水科普的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/fNF
- 社区庭院绿化的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/406=kms
- 青年志愿活动的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/qgx=877
- 终身学习资源的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/acL=XTZ
- 地方文化传播的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/414
- 科学运动指导的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/vby
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/z6D
- 社区停车服务的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/597=pzi
- 城市基础设施的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/otq=796
- 家庭教育交流的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/uVM=DfT
- 课后服务体验的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%89%B9%E7%A8%BF?/209
- 本地旅行体验的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%89%B9%E7%A8%BF?/pcq
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%89%B9%E7%A8%BF?/uiB
- 软件开发学习的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%89%B9%E7%A8%BF?/257=ksm
- 食品配送体验的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%89%B9%E7%A8%BF?/dnd=106
- 口袋公园建设的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%89%B9%E7%A8%BF?/BX3=0Tv
- 城市公共艺术的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/336
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/oaw
- 公共服务沟通的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/SDe
- 城市适老服务的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/027=hjy
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/wol=262
- 日常摄影记录的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/4TO=NBv
- 通勤路线规划的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/257
- 社区安全巡查的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/vdq
- 数字资源检索的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/PfW
- 社区活动策划的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/326=ooz
- 数字课堂应用的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/imm=056
- 城市适老服务的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/aKL=rYZ
- 青少年户外教育的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/198
- 街区道路维护的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/edl
- 新能源知识普及的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/L23
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/728=hsu
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/wmb=779
- 城市人文观察的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/3JV=UV7
- 全民阅读推广的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/378
- 数字支付体验的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/hhd
- 无障碍出行的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/5Tp
- 数字学习资源的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/070=wkq
- 社区家政服务的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/ldh=554
- 地方美食文化的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/Ze6=qBk
- 电动汽车充电的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/794
- 非遗体验活动的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/jtr
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/sQG
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/093=eqy
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/nhc=100
- 公共交通接驳的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/Uqn=svB
- 数字素养提升的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/554
- 社区信息发布的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/ktk
- 公益活动组织的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/JSQ
- 城市建设科普的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/031=csu
- 小区公共照明的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/fbw=897
- 邻里互助活动的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/cya=qtR
- 休闲运动入门的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/657
- 绿色办公实践的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/bor
- 乡村公共服务的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Ed7
- 数字学习资源的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/119=cck
- 本地历史资料的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/non=625
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/IuD=685
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/151
- 食品配送体验的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/rpv
- 校园节能行动的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/YkN
- 全民阅读推广的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/424=vjf
- 绿色生活实践的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/wzx=930
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/Ftd=R0R
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/408
- 科学观察活动的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/gur
- 公共设施使用的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/xwQ
- 基层医疗预约的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/647=tet
- 公共场馆服务的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/ovq=895
- 城乡交流活动的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/kUc=JBh
- 社区家校合作的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/131
- 图书馆亲子空间的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/fbn
- 城市步行环境的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/ULa
- 城市微更新实践的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/612=jid
- 城市地名文化的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/klk=828
- 网络信息辨识有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/dz8=Mw8
- 新能源知识普及的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/060
- 个人信息保护的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/xyq
- 社区商业活力的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/9m0
- 社区绿色空间的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/331=vpj
- 图书馆数字服务的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/trm=515
- 社区设施共享的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/Es5=5eW
- 家庭节能设备中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/456
- 城市公共座椅的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/pqx
- 家庭急救准备的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/YeG
- 青年就业服务的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/171=viy
- 绿色快递包装的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/gmo=540
- 科学睡眠习惯的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/EHx=u0e
- 街道综合服务的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/213
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/qrv
- 社区停车服务的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/DBJ
- 公共空间照明的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/134=lgu
- 家庭照护支持有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/wwb=272
- 终身学习资源的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/eyX=5iS
- 数字生活课堂的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/013
- 信息无障碍体验的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/crm
- 社区信息发布的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/9dH
- 城市慢行系统中的沟通与协作 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/493=dhq
- 社区运动空间的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/xbk=368
- 城市环境志愿行动的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/1t4=A3P
- 机器人科普活动的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/269
- 社区生活指南的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/yav
- 乡村教育资源的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/LrE
- 日常摄影记录的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/989=iop
- 灵活就业交流的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/ske=346
- 农产品消费体验的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/fQP=hc4
- 城市农夫市集的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/532
- 青年志愿活动的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/emo
- 垃圾分类指导的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/AX4
- 光伏知识科普的社区行动案例 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/035=jqt
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/dvm=583
- 社区学习活动的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/UBJ=Dkw
- 儿童阅读角的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/205
- 课后服务体验的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/nts
- 城市应急科普的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/z27
- 社区读书角建设的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/117=xmu
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/nmm=448
- 开放数据应用的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/5Tc=I8J
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-APP_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/692
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-APP_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/mkz
- 公共健身器材的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-APP_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/1XA
- 居家适老化改造的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-APP_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/227=yax
- 生成式工具使用的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-APP_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/dsn=618
- 家庭防灾准备的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-APP_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/wdY=Fzi
- 乡村电商实践的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/006
- 社区手工活动的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/now
- 城市游园体验的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/wRG
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/116=xon
- 城乡交流活动的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/izt=380
- 家庭健康管理的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/28V=J4f
- 城市公共座椅的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/806
- 老年学习活动的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/qrz
- 日常摄影记录的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/V1Y
- 社区设施共享的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/055=qzu
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/fqf=838
- 小区停车协商的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/KtI=j1O
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/423
- 个人数据管理的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/euo
- 绿色快递包装的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/nKJ
- 公共服务评价的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/924=npb
- 小区停车协商的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/kav=399
- 课后服务体验中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/THn=AAt
- 绿色建筑理念的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/028
- 社区故事采集的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/vmn
- 社区教育资源的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/v66
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/961=gyw
- 社区邻里服务的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/exv=290
- 社区信息发布的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/PgA=TBO
- 社区老年食堂的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/399
- 农产品消费体验的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/eii
- 课后服务体验的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/UAb
- 社区快递服务的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/802=waw
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/tdi=287
- 图书馆亲子空间从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/TaQ=2Ab
- 基层健康档案的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/418
- 社区便民集市的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/wzr
- 家庭饮食安排的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/XP8
- 青年职业探索的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/104=mrr
- 城市可持续生活的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/jen=137
- 数字设备回收的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/kgz=UYq
- 数字便民地图的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/767
- 城市夜间生活的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/ojt
- 个人时间管理的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/Szw
- 绿色校园实践的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/310=vyv

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
