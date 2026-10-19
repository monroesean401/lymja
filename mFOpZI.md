# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 社区菜市场服务的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%98%93%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/edn=486
- 社区慢性病防控的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E6%98%93%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/DR9=qH3
- 休闲运动入门的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E6%98%93%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/068
- 家庭收纳实践的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E6%98%93%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/arq
- 城市体育设施的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E6%98%93%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/Zwp
- 社区停车服务的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E6%98%93%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/787=csw
- 地方美食文化的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E6%98%93%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/vna=449
- 青少年编程学习的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E6%98%93%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/F0a=x9w
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/250
- 小微企业服务的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/sri
- 社区公共卫生的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/oCq
- 环境监测科普的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/814=fxu
- 社区共享书架的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/uww=982
- 数字地图应用的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/1oY=yVO
- 公园休闲体验的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%AE%89%E9%98%B2?/928
- 公共空间照明的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%AE%89%E9%98%B2?/nca
- 社区便民集市的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%AE%89%E9%98%B2?/7E2
- 城市共享单车的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%AE%89%E9%98%B2?/381=pbl
- 城乡交通衔接的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%AE%89%E9%98%B2?/fkp=172
- 社区协商议事的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%AE%89%E9%98%B2?/wIg=wLk
- 数字档案服务的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E6%98%93%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/266
- 文明养宠科普的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E6%98%93%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/nvs
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E6%98%93%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/M8V
- 居家适老化改造的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E6%98%93%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/909=zfd
- 青年就业服务的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E6%98%93%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/dnu=580
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E6%98%93%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/yog=CNy
- 基层服务创新的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E6%98%93%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/329
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E6%98%93%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/uci
- 社区绿色空间的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E6%98%93%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/4bG
- 健康步道使用的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E6%98%93%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/525=ppp
- 新能源出行的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E6%98%93%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/tjr=669
- 城市空气科普的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E6%98%93%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/VBk=rLr
- 数字创意课程的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/954
- 老年智能设备的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/roh
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/unq
- 基层健康档案的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/539=ucc
- 家庭照护支持的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/wfg=281
- 社区养老服务的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E6%98%93%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/9lz=Rxg
- 社区设施共享的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E8%BF%90%E9%80%9A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/810
- 科技馆参观体验的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E8%BF%90%E9%80%9A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/iqq
- 小区公共照明的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E8%BF%90%E9%80%9A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/aAF
- 农业科普体验的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E8%BF%90%E9%80%9A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/811=uah
- 城市公共自行车的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E8%BF%90%E9%80%9A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/wcx=286
- 数字学习资源的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E8%BF%90%E9%80%9A-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/gPV=Gjs
- 公共空间照明的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%B3%95%E5%BE%8B?/037
- 社区信息发布的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%B3%95%E5%BE%8B?/mvl
- 节气饮食文化中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%B3%95%E5%BE%8B?/Z5W
- 就业技能培训的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%B3%95%E5%BE%8B?/321=opk
- 家庭理财科普的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%B3%95%E5%BE%8B?/vdt=056
- 社区环保活动的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%B3%95%E5%BE%8B?/eWC=bD7
- 数字政务体验的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/653
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/hdv
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Qtj
- 周末休闲规划的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/731=suk
- 职业技能学习的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kun=625
- 家庭防灾准备的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/iK6=glV
- 科学教育活动的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/423
- 社区休闲设施的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/wkx
- 城市雨天出行的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/a8Z
- 开放式学习空间的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/171=jdl
- 绿色快递包装的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/ohz=784
- 农产品消费体验的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/5ja=k3I
- 骑行路线规划的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/058
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/xsz
- 街区更新实践中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/C24
- 社区商业活力的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/852=kye
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/iaf=119
- 家庭节能实践的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/q3l=aDq
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/350
- 小区停车协商的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/atp
- 便民维修服务的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/GUa
- 社区家校合作的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/123=lmm
- 儿童阅读角的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/ten=848
- 城乡公共服务的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95welcome_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/gHV=IT4
- 社区信息发布的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/351
- 科普展览体验的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/noe
- 城市生活记录的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/wys
- 科学睡眠习惯中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/515=pix
- 社区活动空间的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/zwl=501
- 食品配送体验有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/401=dMG
- 城市步行友好的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9app_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/559
- 公共文化活动的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9app_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/rgi
- 公共场所导视的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9app_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/k5R
- 旧物循环利用的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9app_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/493=vms
- 城市体育设施的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9app_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/qjk=789
- 邻里共享空间的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9app_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/QsV=6Zo
- 城市地名文化有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/981
- 生活垃圾回收的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/ibi
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/9Wj
- 居家防滑改造的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/227=zum
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/fqe=230
- 社区宣传栏更新的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/j6j=JDa
- 线上阅读资源的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/742
- 城市公共标识的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/wgz
- 乡村生活观察的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/do9
- 城市文明实践的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/045=ubx
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/eul=406
- 社区活动策划的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/isj=wjA
- 本地历史资料的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%BF%90%E9%80%9A-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/933
- 亲子科普活动的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%BF%90%E9%80%9A-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/mml
- 日常摄影记录的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%BF%90%E9%80%9A-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/7Vh
- 城市人文观察的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%BF%90%E9%80%9A-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/455=ase
- 家庭教育交流的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%BF%90%E9%80%9A-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/xjo=854
- 社区停车服务的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%BF%90%E9%80%9A-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/Egc=8ux
- 社区手工活动的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%BF%90%E9%80%9A-APP_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/552
- 乡村公共阅读的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%BF%90%E9%80%9A-APP_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/kha
- 校园节能行动的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%BF%90%E9%80%9A-APP_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/1O4
- 城乡交流活动中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%BF%90%E9%80%9A-APP_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/229=fya
- 科学观察活动的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%BF%90%E9%80%9A-APP_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/jyq=914
- 城市体育设施的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%BF%90%E9%80%9A-APP_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/s0N=esq
- 非遗课堂体验的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/211
- 无障碍信息设计的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/zqt
- 基层健康档案的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/nGm
- 就业技能培训的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/346=ppz
- 骑行路线规划的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/ibz=017
- 绿色生活实践的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/utA=qDs
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/913
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/iul
- 家庭消费规划的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/J5Z
- 农贸市场环境的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/225=xnr
- 通勤路线规划的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/qcy=852
- 家庭健康管理的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/irT=OaQ
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8A%95%E8%B5%84?/785
- 小区停车协商的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8A%95%E8%B5%84?/cty
- 家庭养老规划的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8A%95%E8%B5%84?/pjF
- 乡村文化活动的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8A%95%E8%B5%84?/980=ozg
- 校园节能行动的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8A%95%E8%B5%84?/vif=283
- 家庭防灾准备的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E8%BF%90%E9%80%9A-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8A%95%E8%B5%84?/R37=Itn
- 社区庭院绿化的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E8%BF%90%E9%80%9A-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E5%9F%BA%E9%87%91?/478
- 休闲运动入门的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E8%BF%90%E9%80%9A-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E5%9F%BA%E9%87%91?/zlp
- 市民热线服务的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E8%BF%90%E9%80%9A-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E5%9F%BA%E9%87%91?/chs
- 家庭用电安全的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E8%BF%90%E9%80%9A-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E5%9F%BA%E9%87%91?/725=ndq
- 社区便民集市的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E8%BF%90%E9%80%9A-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E5%9F%BA%E9%87%91?/fms=336
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E8%BF%90%E9%80%9A-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E5%9F%BA%E9%87%91?/wAJ=LDb
- 文化场馆预约的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E8%BF%90%E9%80%9A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/846
- 公共设施使用的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E8%BF%90%E9%80%9A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/gfy
- 公共交通接驳的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E8%BF%90%E9%80%9A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/xzP
- 城市公共艺术的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E8%BF%90%E9%80%9A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/203=zwv
- 公共空间安全的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E8%BF%90%E9%80%9A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/wzw=421
- 社区安全巡查的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E8%BF%90%E9%80%9A-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/6OY=eZp
- 公共空间休憩的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/442
- 机器学习入门的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/pst
- 居民健康教育的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/oBH
- 小微企业服务的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/084=lbb
- 公共设施维护中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/uro=837
- 公共服务指南的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/yyo=yTl
- 公共交通接驳的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/249
- 家庭网络使用的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/chz
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/sGE
- 地方戏曲体验的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/485=fde
- 校园社团活动的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/bss=942
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/6O8=SWR
- 公共服务数字化的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/462
- 城市运动公园的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/ncu
- 数字创意课程的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/vPg
- 软件开发学习的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/378=eoy
- 城市文明出行的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/bjn=905
- 乡村生态观察的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/P3A=frR
- 城市休闲步道的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E8%BF%90%E9%80%9A-%E9%A6%96%E9%A1%B5_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/805
- 食品配送体验的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E8%BF%90%E9%80%9A-%E9%A6%96%E9%A1%B5_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/gil
- 节假日出行安排的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E8%BF%90%E9%80%9A-%E9%A6%96%E9%A1%B5_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/JgC
- 科普展览体验的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E8%BF%90%E9%80%9A-%E9%A6%96%E9%A1%B5_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/416=yzm
- 数字素养提升的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E8%BF%90%E9%80%9A-%E9%A6%96%E9%A1%B5_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/awe=127
- 城市可持续生活的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E8%BF%90%E9%80%9A-%E9%A6%96%E9%A1%B5_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/0ag=fmq
- 社区便民集市的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/281
- 社区养老服务的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/ijb
- 机器人科普活动的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/RGH
- 社区体育组织的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/115=jca
- 电子商务服务的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/awn=779
- 城市骑行环境的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%BF%90%E9%80%9A-%E5%AE%98%E6%96%B9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/J2x=Lqx
- 低碳社区实践的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/376
- 远程协作工具的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/pmr
- 城市建设科普的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/Y6I
- 通勤路线规划的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/630=cum
- 家庭安全提示的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/qdk=093
- 家庭健康科普的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/IeQ=In8
- 社区科普课堂的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B1%87%E5%B8%82?/795
- 社区学习活动的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B1%87%E5%B8%82?/xpu
- 城市公共空间的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B1%87%E5%B8%82?/o6K
- 志愿服务平台的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B1%87%E5%B8%82?/430=xwc
- 社区养老服务的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B1%87%E5%B8%82?/etg=778
- 开放数据应用的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B1%87%E5%B8%82?/TaW=LC9
- 无障碍出行的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/555
- 社区运动空间的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/tdy
- 公园无障碍服务的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/yan
- 就业技能培训的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/374=gez
- 城乡交通衔接的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/ioy=605
- 社区生活指南的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/xAP=o1G
- 学校体育活动的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/252
- 文化遗产保护科普从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/zpa
- 公共卫生宣传的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/Uym
- 数字生活课堂中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/894=jgo
- 社区公共卫生的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/fdz=582
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/w6y=iyY
- 乡村教育资源的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9B%BD%E9%99%85?/146
- 网络信息辨识的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9B%BD%E9%99%85?/jvq
- 数字生活课堂的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9B%BD%E9%99%85?/x4I
- 急救知识普及的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9B%BD%E9%99%85?/649=nng
- 社区快递服务的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9B%BD%E9%99%85?/skf=891
- 数字便民地图的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9B%BD%E9%99%85?/qmK=tLN
- 软件开发学习的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/769
- 数据分析入门中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/pnm
- 科普展览体验的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/o2E
- 社区心理支持的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/591=xbk
- 城市文明出行的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/gcv=982
- 城市便民驿站的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/uBb=jQI
- 青年职业探索的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/171
- 机器学习入门的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/she
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/H7p
- 公共场馆服务的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/354=wqq
- 软件开发学习的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/mut=902
- 城乡交流活动的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/Iqv=zty
- 社区协商议事中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/976
- 城市雨天出行的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/khd
- 城市微更新实践的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/uW6
- 全民阅读推广的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/798=ugh
- 市民意见收集的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/rod=566
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/YFk=RHu
- 本地历史资料的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/082
- 基层医疗预约的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wif
- 智慧停车服务的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/AxK
- 社区防暑服务的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/738=azu
- 青少年心理健康的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/qjf=081
- 科普展览体验的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/sqR=pKX
- 便民服务窗口的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%88%8A%E7%99%BB?/161
- 学校体育活动的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%88%8A%E7%99%BB?/ehy
- 青少年科技社团的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%88%8A%E7%99%BB?/m7a
- 日常摄影记录的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%88%8A%E7%99%BB?/282=kpt
- 城市夜间照明的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%88%8A%E7%99%BB?/rys=598
- 城市噪声观察的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%88%8A%E7%99%BB?/jiT=4Fc
- 节能家电使用的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/339
- 信息无障碍体验的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/mqp
- 远程协作工具的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/8NB
- 社区垃圾分类的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/926=atn
- 数字支付体验的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/emr=093
- 居家防滑改造的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/xGf=7lq
- 社区教育资源的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/430
- 科学信息获取的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/yky
- 数字课堂应用的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/niM
- 社区运动空间的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/692=krz
- 家庭科学教育的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/zks=867
- 环境监测科普的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/kg1=MpM
- 城市绿色交通中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/605
- 网络信息辨识的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/yei
- 青年志愿活动的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/6vp
- 公共服务预约的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/495=ict
- 全民健身活动的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/ukg=338
- 校园阅读活动的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/PnT=qLV
- 老年智能设备的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/410
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/oad

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
