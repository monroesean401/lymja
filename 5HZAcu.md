# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 城市慢行系统中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/014
- 城市公共标识的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/eju
- 社区停车服务的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/uyp
- 无障碍出行的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/392=ecb
- 街区小店体验的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/uei=839
- 城市绿道建设的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/1fA=Qki
- 儿童阅读角的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/653
- 节约用水实践的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/ybh
- 安全出行教育的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/eB4
- 校园社团活动的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/995=muf
- 社区公共议事的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/jyw=748
- 社区托育服务的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/BT3=XaD
- 公共卫生设施的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/166
- 社区手工活动的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/pkl
- 社区设施共享的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/2Rf
- 城市博物馆服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/581=azi
- 数字资源检索的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/mvg=676
- 创业经验分享的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/cPe=IFW
- 传统节日科普的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/572
- 公共交通接驳的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/idh
- 城市空气科普的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/2kK
- 社区修缮行动的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/130=wxk
- 食品安全科普的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/tul=944
- 农业科普体验的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/sSd=OT0
- 社区花园共建的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/558
- 社区生活指南的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/knf
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/Kcv
- 社区家校合作的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/771=gfh
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/nkw=113
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/rSQ=fuA
- 智能家居应用的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/790
- 家庭照护支持的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/wns
- 家庭运动计划的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/YqG
- 城市公共饮水的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/825=ndf
- 开放式学习空间的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/ted=848
- 公交无障碍服务的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/AXQ=v8f
- 无障碍出行的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/533
- 街道综合服务的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/gsl
- 绿色生活实践的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/2aU
- 农贸市场环境的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/505=yhv
- 街区更新实践的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/jwn=184
- 乡村生活观察的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/c6g=H80
- 便民服务窗口的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/391
- 乡村公共服务的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/bxn
- 数字公共文化中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/6tA
- 社区文化节活动的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/915=gwd
- 家庭安全提示的线下体验记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/ebg=317
- 科学健身方法的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/mG6=NL3
- 数字创意课程的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/091
- 社区读书角建设的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/xtk
- 城市夜间生活的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/n1W
- 社区教育资源的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/080=gyv
- 公共空间休憩中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/cgw=994
- 城市公共厕所的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/K0q=s2W
- 公共设施维护的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/354
- 家庭节能设备的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/uwr
- 社区信息发布的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/kQM
- 社区家政服务的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/267=uzl
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/aem=883
- 数字素养提升的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/ppq=Syn
- 乡村公共阅读的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/864
- 开源技术交流的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/bfv
- 社区公共餐饮的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/XPf
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/270=jyh
- 校园阅读活动的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/tai=530
- 科学教育活动的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/WAH=3Jf
- 科技馆参观体验的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/585
- 公共服务咨询的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/hyo
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/wJI
- 食品配送体验的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/297=dop
- 科学健身方法的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/lvf=978
- 课后服务体验的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/fKH=WUY
- 城市慢跑路线的协商参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/309
- 老年人出行服务的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/ngt
- 图书借阅体验的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/a7A
- 社区协商议事的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/865=iit
- 公共交通信息服务的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/hqr=524
- 数字资源检索的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/Ck4=Ddw
- 非遗课堂体验的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/768
- 家庭科学教育的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/gdl
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/2oR
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/978=abt
- 家庭科学教育的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/lod=200
- 应急物资管理从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/75S=leJ
- 通勤路线规划的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/688
- 农产品消费体验的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/cks
- 社区宠物管理的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/C1C
- 无障碍出行的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/158=sbp
- 城市文明实践的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/htl=493
- 个人数据管理的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/2pq=fhg
- 城市慢行系统的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/122
- 志愿服务平台的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/plc
- 运动安全知识的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/iR9
- 青少年科普实践的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/574=ppo
- 绿色建筑理念的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/gnx=142
- 社区教育资源的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/vyI=ts6
- 公园休闲体验的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/231
- 家庭科学教育的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/tuy
- 乡村生态观察的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/ohG
- 地方戏曲体验的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/379=gdz
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/tnb=463
- 公共服务评价的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/Ukz=uPQ
- 社会体育指导的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/947
- 公共服务预约的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/nbz
- 老年运动活动的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/msm
- 社区公共餐饮的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/650=rvv
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/tzg=883
- 绿色出行服务的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/1NY=DHZ
- 社区养老服务的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/059
- 公共服务评价的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/mgm
- 基层健康服务的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/v6J
- 文明养宠科普的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/786=tkm
- 便民信息查询的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/cyj=484
- 地方旅游导览中的几个关键细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/v7M=MUy
- 本地消费场景的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/937
- 个人数据管理的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/xgl
- 社区垃圾分类的基础设施观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/f5G
- 社区学习活动的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/856=uca
- 基层医疗预约的活动体验回顾 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/aco=045
- 信息无障碍体验的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/LJy=QSh
- 社区阅读服务中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/524
- 个人信息保护的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/ivw
- 本地消费场景的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/BJu
- 城市水环境观察的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/505=vgv
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/tpa=766
- 全民健身活动的公共参与指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/pWY=Za0
- 老年人出行服务的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%94%BF%E5%8D%8F?/915
- 乡村教育资源的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%94%BF%E5%8D%8F?/eeo
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%94%BF%E5%8D%8F?/paY
- 灵活就业交流的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%94%BF%E5%8D%8F?/968=pfy
- 老年运动活动的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%94%BF%E5%8D%8F?/pmz=015
- 公共场馆服务的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%94%BF%E5%8D%8F?/e0V=1PN
- 家庭健康管理的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/726
- 城市便民驿站的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/bhp
- 青少年职业启蒙的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/g10
- 数字艺术创作的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/594=dnb
- 社区交通安全的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/xuu=098
- 药品使用科普的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/mZP=80a
- 城市应急广播的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/879
- 家庭环保行动的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/asm
- 城市建设科普的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/SmZ
- 农贸市场环境的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/468=hlv
- 光伏知识科普的家庭实践清单 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/ejm=554
- 街区小店体验的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/DWk=oEj
- 社区活动策划的执行流程参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/355
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/tsf
- 城市雨天出行的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/AAq
- 乡村生态旅游的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/620=kzx
- 儿童阅读角中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/lew=368
- 家庭节能实践的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/H0V=gqY
- 家庭照护支持的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_360%E5%8A%A8%E6%BC%AB?/955
- 城市博物馆活动的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_360%E5%8A%A8%E6%BC%AB?/cij
- 城市公共艺术的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_360%E5%8A%A8%E6%BC%AB?/YW8
- 地方文化传播的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_360%E5%8A%A8%E6%BC%AB?/160=jvn
- 家庭网络使用的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_360%E5%8A%A8%E6%BC%AB?/lbr=976
- 信息无障碍体验的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_360%E5%8A%A8%E6%BC%AB?/obd=yoR
- 就业技能培训的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/222
- 城市地名文化的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/upy
- 基层健康档案的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/2Ri
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/580=hkg
- 社区便民服务的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/czn=931
- 城市社区治理的服务范围梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/6f6=UHe
- 智能家居应用的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/157
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/pxm
- 城市休闲步道的实际需求与回应 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/A0z
- 社区心理支持的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/167=euf
- 城市公共饮水的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/twr=224
- 公共文化活动的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/xuy=cG2
- 公交站点体验的绿色实践方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/034
- 创业经验分享的学习资源整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/jft
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/KFO
- 节约用水实践的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/052=iuu
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/men=394
- 社区法律科普的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/emN=ecv
- 校园安全教育的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/632
- 社区老年食堂的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/kti
- 城市社区治理的儿童友好细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/Jq7
- 社区法律科普的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/376=cak
- 社区应急准备的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/rmz=057
- 智能手机助老的协作机制梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/j50=eRr
- 学校体育活动的长期维护要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/951
- 日常摄影记录的公共信息获取方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/xxw
- 电动汽车充电的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/6l2
- 科学健身方法的基础知识问答 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/351=uyp
- 乡村教育资源的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/nrx=465
- 数字阅读服务的适老服务细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/TAF=24u
- 科学信息获取的服务质量观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/856
- 城市骑行环境的日常记录与分享 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/wew
- 消防知识宣传的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/E3s
- 数字便民地图的入门知识整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/287=rjk
- 家庭健康科普的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/sta=778
- 家庭运动计划有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/aH7=4cU
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/812
- 科学信息获取的常见误区提醒 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/nph
- 青少年科普实践的日常使用指南 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/ODY
- 劳动教育实践从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/101=zec
- 市民意见收集的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/hip=205
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/UbV=6rc
- 青少年编程学习的参与方式与路径 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/512
- 社区安全巡查的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/fel
- 个人时间管理的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/rCu
- 乡村公共服务的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/749=mnv
- 志愿者培训交流的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/ylr=937
- 在线学习体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/JM3=5w1
- 绿色快递包装的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/923
- 老年人日常照护的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/yay
- 城市游园体验的服务反馈渠道 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/idd
- 社区健康讲座的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/631=vxr
- 个人时间管理的持续改进方向 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/uiq=156
- 青年志愿活动的空间使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/KCW=OW3
- 健康饮食教育的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/232
- 公共空间安全的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/elf
- 儿童阅读角的便民做法梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/281
- 社区设施共享的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/764=xjc
- 城市应急广播的便利性观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/jpq=184
- 家庭教育交流的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/fTy=aHy
- 城市应急科普的数字工具使用体验 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/572
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/jpd
- 机器人科普活动的社区行动案例 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/Hvm
- 社区活动空间的活动策划思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/912=hsq
- 市民热线服务的设施维护观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/hnn=296
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/Fdi=coE
- 智能手机助老中的沟通与协作 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/798
- 数字阅读服务的使用门槛与改进 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/njq
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/bJa
- 社区老年食堂的常见问题梳理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/045=aiy
- 社区艺术活动的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/ngr=234
- 市民热线服务的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/1rF=4b0
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/102
- 公共服务数字化的居民参与机会 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/xzy
- 社区邻里服务的服务体验观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/nXu
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/558=muc
- 社区便民服务的组织方法与经验 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/the=689
- 数字资源检索的服务信息整理 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/5xE=zlz
- 运动安全知识的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/613
- 居家适老化改造的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/swb
- 生活技能分享的服务细节记录 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/yLa
- 社区手工活动的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/167=txj
- 环境监测科普的空间设计要点 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/ifg=982
- 社区互助网络的日常实践笔记 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/Hd6=vUA
- 远程协作工具的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/187
- 家庭教育交流的行动步骤参考 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/ome
- 农村环境治理的数字化应用观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/Dk0
- 城市宠物友好空间的资源利用方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/312=kus
- 城市文化路线的日常管理方法 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/bnb=587
- 公共服务沟通的家庭参与方式 |来源：https://github.com/jonesdawn710/lrte/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/puC=QTE
- 街区道路维护的阅读与学习资源 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/881
- 科学运动指导的便捷程度观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/vso
- 公共健身器材的社区参与观察 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/LMl
- 旧物循环利用的安全使用提示 |来源：https://github.com/jonesdawn710/lrte/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/830=cao

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
