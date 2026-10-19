# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:17**

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

- 小微企业服务的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/HhL
- 健康信息获取的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/897=sfv
- 城市休闲步道的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/afp=010
- 城市公共厕所的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/SWB=5dn
- 公共服务预约的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/244
- 街区绿化养护的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/emd
- 邻里互助活动的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/FuY
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/250=tmq
- 社区快递服务中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/hhz=300
- 城市噪声观察的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/nUD=9Gf
- 乡村公共服务的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/932
- 电动汽车充电中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/qkk
- 城市公共饮水的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/t1L
- 社区法律科普的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/088=seo
- 乡村文化活动的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/dtt=845
- 社区环保活动的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/1t0=DXm
- 地方文化传播的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/300
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/ens
- 街区小店体验的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/3TY
- 青少年科普实践的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/202=aio
- 社区垃圾回收的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/auq=540
- 公共设施使用的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/wKM=aQ1
- 绿色校园实践的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/231
- 数字学习资源的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/yhg
- 乡村公共服务的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/wOx
- 劳动教育实践的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/847=gcz
- 数字档案服务的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/zdm=130
- 居家适老化改造的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/J5w=c05
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/130
- 本地消费场景的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/mje
- 非遗课堂体验的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/JTg
- 本地旅行体验的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/358=cwh
- 小区公共照明的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/iwf=465
- 城乡交流活动的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/HCI=xYp
- 新能源出行的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/455
- 公共场馆服务的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/whb
- 新能源出行的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/iqO
- 急救知识普及的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/763=woi
- 城市夜间生活的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/zha=651
- 社区体育组织的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/IxN=wsu
- 城市展览体验的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/925
- 光伏知识科普的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/ijd
- 老年学习活动的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/xnk
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/566=ppj
- 地方文化传播的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/vco=345
- 传统节日科普的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/bCa=KvX
- 街区绿化养护中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/013
- 线上办事服务的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/rye
- 休闲运动入门的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/DNp
- 城市便民驿站的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/300=rsg
- 数据分析入门的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/efo=809
- 图书借阅体验的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/CaX=mok
- 绿色生活实践的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3?/285
- 节气饮食文化的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3?/mfx
- 社区停车服务的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3?/jrl
- 乡村文化空间的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3?/302=dse
- 社区交通安全的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3?/bla=496
- 基层健康档案的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3?/WDN=qFX
- 城市文明实践的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/639
- 城市空气科普的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/hli
- 文化场馆预约的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/ehd
- 老年人出行服务的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/052=knz
- 社区生活指南的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/lif=922
- 社区快递服务的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/NrL=kRS
- 城市文明实践的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/080
- 文明养宠科普的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/enx
- 社区公共卫生的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/tzN
- 社区活动空间的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/286=lze
- 个人数据管理的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/enp=586
- 图书馆活动策划的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/9Vk=lEk
- 无障碍出行的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/638
- 公共空间休憩的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/qht
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/LOn
- 数字设备回收的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/826=mge
- 亲子阅读活动的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/hoo=142
- 社区教育资源的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/bkO=GZv
- 科普展览体验的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/491
- 基层健康档案的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/fbh
- 校园安全教育的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/LFs
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/093=dml
- 旧物循环利用的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/rre=884
- 科技馆参观体验的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/8ah=tDO
- 城市住房服务的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/937
- 老年人出行服务的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/hat
- 数字资源检索的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/dg3
- 老年友好服务的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/025=qhn
- 社区健康讲座的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/wod=301
- 乡村公共文化的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/pyX=Jxu
- 城市公共饮水的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/059
- 儿童友好空间的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/bvb
- 休闲运动入门的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/2qg
- 城乡公共服务的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/549=dsg
- 小区电梯维护的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/ltw=638
- 城市公共自行车的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/BUZ=lHk
- 本地消费场景的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A8%8E%E5%8A%A1?/696
- 公共空间照明的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A8%8E%E5%8A%A1?/zsw
- 街区绿化养护的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A8%8E%E5%8A%A1?/QFa
- 家庭养老规划的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A8%8E%E5%8A%A1?/294=rco
- 社区便利生活的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A8%8E%E5%8A%A1?/txw=379
- 社区养老服务的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A8%8E%E5%8A%A1?/fSW=J26
- 城市文化路线的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/849
- 健康饮水科普的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/xxy
- 节能生活方式的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/i7H
- 城市博物馆服务的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/782=dhn
- 城市树木认养的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/llf=538
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/oFI=YdJ
- 数字支付体验的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%9B%98%E7%82%B9?/673
- 公园亲子设施的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%9B%98%E7%82%B9?/ram
- 零废弃生活尝试中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%9B%98%E7%82%B9?/Bdi
- 通勤路线规划的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%9B%98%E7%82%B9?/978=nra
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%9B%98%E7%82%B9?/jvv=799
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%9B%98%E7%82%B9?/H5F=Kwi
- 课后服务体验的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%96%87%E5%8C%96?/833
- 乡村阅读空间的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%96%87%E5%8C%96?/ucj
- 社区停车服务的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%96%87%E5%8C%96?/Y2u
- 城市共享单车的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%96%87%E5%8C%96?/754=npp
- 食品配送体验的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%96%87%E5%8C%96?/ffo=087
- 健康信息获取的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%96%87%E5%8C%96?/e2g=Q2N
- 城市雨天出行的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/798
- 科学教育活动的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/mzr
- 图书馆活动策划的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/zWu
- 老年人日常照护的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/697=pfj
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/lwk=469
- 老年学习活动的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/FOh=eB7
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/714
- 绿色消费选择的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/xen
- 城市夜间生活的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/y2A
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/282=lkq
- 城市雨天出行的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/hql=522
- 非遗体验活动的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/xUo=6LC
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/860
- 数字生活课堂的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/flm
- 基层医疗预约的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/Cfd
- 公共空间休憩的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/856=pfw
- 公共服务评价的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/xes=468
- 社区安全巡查的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/u1t=HfM
- 街区道路维护的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/296
- 药品使用科普的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/sgm
- 城市展览体验的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/yCd
- 社区养老服务的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/557=lqf
- 传统节日科普的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/hzk=436
- 医院导诊服务的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/Skx=Ceg
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/567
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/ejy
- 全民阅读推广的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/BGp
- 城乡交流活动的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/709=yik
- 公共卫生宣传的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/scp=958
- 家庭防灾准备的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/BT4=Nxx
- 城市噪声观察的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_360%E9%97%AE%E5%8D%B7?/947
- 图书借阅体验的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_360%E9%97%AE%E5%8D%B7?/rai
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_360%E9%97%AE%E5%8D%B7?/reV
- 城市应急科普的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_360%E9%97%AE%E5%8D%B7?/778=fed
- 城乡交流活动的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_360%E9%97%AE%E5%8D%B7?/vuu=322
- 乡村电商实践的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_360%E9%97%AE%E5%8D%B7?/hud=gtz
- 远程协作工具的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/810
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/wnz
- 租房信息服务的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/0BR
- 公共空间安全的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/380=pef
- 基层健康档案的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/tyy=298
- 城市游园体验的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/fW8=iS4
- 读书会组织的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%AE%8F%E8%A7%82?/610
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%AE%8F%E8%A7%82?/zjg
- 开放式学习空间的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%AE%8F%E8%A7%82?/yyT
- 乡村阅读活动的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%AE%8F%E8%A7%82?/997=bet
- 社区读书角建设的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%AE%8F%E8%A7%82?/xhv=159
- 城市骑行环境的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%AE%8F%E8%A7%82?/c6D=1Mc
- 老年友好服务的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_360%E6%88%BF%E4%BA%A7?/198
- 生活垃圾减量的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_360%E6%88%BF%E4%BA%A7?/icw
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_360%E6%88%BF%E4%BA%A7?/xRT
- 节约用水实践的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_360%E6%88%BF%E4%BA%A7?/885=zgj
- 城市文明出行的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_360%E6%88%BF%E4%BA%A7?/wlm=559
- 居家适老化改造的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_360%E6%88%BF%E4%BA%A7?/5Tr=qTJ
- 乡村产业科普的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/341
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/qds
- 数字设备回收的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/QfW
- 本地历史资料的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/687=mqc
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/zjf=536
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/EWQ=eww
- 城市社区治理的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/574
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/xzf
- 科学教育活动的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/uLu
- 社区应急准备的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/679=opq
- 社区阅读服务的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/uyc=716
- 城市文明出行的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/RmU=t3y
- 租房信息服务的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/680
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/dtj
- 数字地图应用的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/92B
- 医院导诊服务的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/766=bsi
- 机器人科普活动的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/rds=032
- 城市人文观察的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/e3o=vfW
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%AE%BF?/330
- 老年人出行服务的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%AE%BF?/tft
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%AE%BF?/BTE
- 社区安全巡查的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%AE%BF?/166=mio
- 机器人科普活动的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%AE%BF?/eda=310
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%AE%BF?/oTc=hSr
- 城市运动公园的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/143
- 绿色校园实践的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/yzu
- 运动安全知识的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/ZTq
- 社区宠物管理中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/077=idj
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/wpw=825
- 城市可持续生活的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/UIM=0jk
- 公共服务沟通的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/511
- 绿色校园实践的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/osx
- 公共文化活动的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/4Yn
- 公共卫生设施的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/609=eun
- 街区绿化养护的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/swq=169
- 青年志愿活动中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/I0P=sVr
- 青少年科技社团的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%BF%E5%9F%9F?/362
- 公园亲子设施中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%BF%E5%9F%9F?/rhq
- 家庭健康科普的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%BF%E5%9F%9F?/qET
- 电动汽车充电的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%BF%E5%9F%9F?/910=fap
- 社区家政服务的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%BF%E5%9F%9F?/pjo=171
- 公共设施维护的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%BF%E5%9F%9F?/6ee=veQ
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/696
- 应急物资管理的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/lxv
- 乡村产业科普的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/3Li
- 健康步道使用的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/493=win
- 社区学习活动的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/vww=291
- 健康信息获取的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/mvs=1aU
- 绿色办公实践的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/977
- 基层健康档案的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/pfe
- 社区公共卫生的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/ixI
- 周末休闲规划的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/492=gtk
- 社区阅读服务的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/tjg=577
- 城市公共标识的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/jRE=GHb
- 儿童友好街区的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/521
- 街道综合服务的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/mny
- 社区宣传栏更新的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/3wC
- 生活服务数字化的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/944=uoe
- 公共空间安全的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/kvj=504
- 数字学习资源的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/AMn=3qj
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/500
- 科学观察活动的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/rrv
- 乡村产业科普的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/kno
- 通勤路线规划的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/399=xhw
- 小微企业服务的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/oem=202
- 电动汽车充电的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/wKx=vDf
- 社区活动空间中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/248
- 城市公共饮水的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/ran
- 城市水环境观察的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/oty
- 社区阅读服务的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/256=lpo
- 城市水环境观察的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/fdz=926
- 社区养老服务的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/7Y6=VJU
- 基层健康档案中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/691
- 志愿者培训交流的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/jde
- 社区消防演练的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/Est
- 公共服务指南的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/393=klf
- 家庭运动计划的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/nbr=437
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/oSt=3jj

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
