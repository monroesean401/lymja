# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 周末休闲规划的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85~welcome_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/M60
- 公共图书馆服务的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85~welcome_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/045=cgr
- 本地旅行体验的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85~welcome_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/vcq=772
- 校园社团活动的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85~welcome_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/zZR=JjC
- 学校体育活动的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/789
- 图书借阅体验的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/tkl
- 社区运动空间的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/Ul4
- 公共健身器材的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/094=rka
- 数字素养提升的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/kbv=547
- 社区邻里服务的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/oow=aSC
- 节能家电使用的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/540
- 节能家电使用的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/miq
- 科学运动指导的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/Ntw
- 科学信息获取的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/825=ssl
- 城市慢行系统的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/kbe=404
- 社会体育指导的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/Hym=FLh
- 农村环境治理的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/335
- 农产品品牌传播的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/jhx
- 校园安全教育的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/XWq
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/649=vgu
- 社区学习活动的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/rws=071
- 城市公共饮水的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/ufC=vAJ
- 户外活动组织中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%8A%95%E8%B5%84?/141
- 青少年科普实践的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%8A%95%E8%B5%84?/beu
- 个人信息保护的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%8A%95%E8%B5%84?/hbn
- 农产品消费体验的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%8A%95%E8%B5%84?/709=tqf
- 便民服务窗口的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%8A%95%E8%B5%84?/elu=956
- 公共空间导览的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%8A%95%E8%B5%84?/wdf=wH4
- 绿色快递包装的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/622
- 数字素养提升的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/dsg
- 青少年心理健康的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/pYc
- 线上阅读资源的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/260=skp
- 儿童阅读角的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/osh=982
- 青年就业服务的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/isw=mMi
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8welcom_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/432
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8welcom_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/xxg
- 街头绿植养护的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8welcom_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/jBO
- 城市公共座椅的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8welcom_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/753=adr
- 个人数据管理的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8welcom_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/agv=137
- 应急物资管理的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8welcom_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/ZF2=jXc
- 儿童安全出行的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/842
- 个人数据管理的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/oip
- 社区停车服务的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/RUI
- 乡村文化活动的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/826=zcb
- 城市住房服务的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/dqj=219
- 机器学习入门的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/VDD=dcC
- 公共设施维护中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/692
- 公共健身器材的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/uhj
- 乡村阅读活动的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/A5P
- 网络安全教育的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/564=goe
- 青年志愿活动的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/fus=522
- 节能生活方式的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/meQ=pGm
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/789
- 社区互助网络的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/opd
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/1dZ
- 城市建设科普的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/966=snn
- 乡村产业科普的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/xam=379
- 低碳社区实践中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/Uvu=93N
- 机器人科普活动的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/920
- 邻里互助活动的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/kyj
- 家庭安全提示中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/eBH
- 骑行路线规划的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/447=rpq
- 街区道路维护的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/brh=204
- 城市公共厕所的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/zQZ=GOl
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/887
- 社区活动策划的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/bek
- 文化场馆预约的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/RaV
- 居民健康教育的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/330=zfy
- 城市体育设施的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/fzw=754
- 青少年科技社团从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/DZw=qUi
- 城市夜间生活的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/769
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/znm
- 城市文明出行的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/Odc
- 社区活动空间的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/298=pcn
- 本地历史资料的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/esl=776
- 个人信息保护的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/10O=Q2v
- 社区垃圾分类的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%91%A8%E6%8A%A5?/223
- 城市运动公园的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%91%A8%E6%8A%A5?/jcc
- 社区公共卫生的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%91%A8%E6%8A%A5?/BUf
- 家庭安全提示的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%91%A8%E6%8A%A5?/279=yzq
- 社区便民服务的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%91%A8%E6%8A%A5?/nwp=307
- 邻里共享空间从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%91%A8%E6%8A%A5?/1b1=lBA
- 食品安全科普的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84?/813
- 城市水环境观察的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84?/fsb
- 城市空气科普的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84?/iXj
- 家庭志愿活动的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84?/536=ogr
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84?/vbg=589
- 社区协商议事的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%83%E5%85%AD%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84?/gbZ=74t
- 智能手机助老的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%B8%83%E5%85%ADC.%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/836
- 城市展览体验有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%B8%83%E5%85%ADC.%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/cpx
- 居民健康教育的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%B8%83%E5%85%ADC.%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/JQg
- 青少年户外教育的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%B8%83%E5%85%ADC.%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/412=tta
- 家庭急救准备的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%B8%83%E5%85%ADC.%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/vfh=913
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%B8%83%E5%85%ADC.%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/rax=p1U
- 无障碍出行的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E6%96%87%E5%8C%96?/925
- 全民健身活动的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E6%96%87%E5%8C%96?/fub
- 儿童户外活动的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E6%96%87%E5%8C%96?/Gxc
- 城市绿色交通的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E6%96%87%E5%8C%96?/413=egj
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E6%96%87%E5%8C%96?/kcz=197
- 城市公共艺术的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E5%BD%A9-%E9%A6%96%E9%A1%B5_360%E6%96%87%E5%8C%96?/VoZ=EiG
- 老年人日常照护的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E?/574
- 家庭饮食安排的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E?/ace
- 课后服务体验的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E?/8Dk
- 开源技术交流的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E?/272=ozf
- 城市共享单车的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E?/urm=371
- 社区菜市场服务的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E?/sjs=4i8
- 公共空间照明的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/741
- 家庭园艺实践的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/szo
- 公共服务评价中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/YHf
- 城市便民驿站的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/192=wws
- 乡村教育资源的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/tpx=900
- 科技馆参观体验的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/bC4=raQ
- 家庭健康科普中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/629
- 城市微更新实践的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/tjw
- 本地消费场景的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/IQe
- 城市住房服务的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/834=slu
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/wnd=119
- 数字创意课程的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/heb=Qx7
- 户外活动组织的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/762
- 社区绿色空间的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/lqm
- 生活垃圾回收的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/4g2
- 校园安全教育的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/878=irm
- 城市水环境观察的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/uki=777
- 社区学习活动的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/4p6=EKj
- 租房信息服务的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/611
- 便民维修服务的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/ghk
- 智慧停车服务的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/Aid
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/846=szb
- 城市文明出行的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/oap=475
- 医院导诊服务的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/lp7=LMz
- 社区修缮行动的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/861
- 文化场馆预约的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/kmj
- 网络信息辨识的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/4mQ
- 社区便民集市的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/513=kcd
- 城市文明出行的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/mnh=176
- 青少年户外教育的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/RsB=oPy
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/934
- 城市人文观察的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/bxg
- 线上阅读资源的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Eel
- 家庭环保行动的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/009=znt
- 家庭环保行动的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/zqk=879
- 文明养宠科普的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/8uM=KOZ
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/430
- 城市基础设施的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/hdt
- 农村环境治理的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/vHk
- 家庭运动计划的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/723=ucp
- 社区活动报名的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/jfo=379
- 社区共享书架的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/ySk=tJO
- 租房信息服务的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/640
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/tfu
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/HaP
- 物业服务沟通的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/572=nwl
- 生活垃圾回收的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/oga=569
- 公共服务评价中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/jtq=RGW
- 家庭健康管理的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/310
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/qvi
- 健康步道使用中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/KCk
- 小区电梯维护的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/865=ioo
- 传统节日科普的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/jcm=536
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/wn9=rcS
- 骑行路线规划的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A81_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/768
- 城市文明实践的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A81_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/vgf
- 农贸市场环境中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A81_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/wm9
- 智能手机助老的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A81_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/846=cgg
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A81_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/pli=944
- 居家防滑改造中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A81_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/Sdz=CZY
- 城市游园体验的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/449
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/kfk
- 社区商业活力的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/A8e
- 食品配送体验的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/232=rlt
- 城市农夫市集的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/sge=560
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/dLL=lJY
- 劳动教育实践的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%B9%A6%E7%94%BB?/783
- 数字创意课程的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%B9%A6%E7%94%BB?/sml
- 急救知识普及的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%B9%A6%E7%94%BB?/52B
- 终身学习资源的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%B9%A6%E7%94%BB?/556=lxk
- 农产品品牌传播的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%B9%A6%E7%94%BB?/ojf=336
- 社区文化传播的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%B9%A6%E7%94%BB?/XkJ=j6v
- 社区快递服务的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/798
- 口袋公园建设的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/jlx
- 智慧停车服务的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/NA7
- 电动汽车充电的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/087=yqp
- 社区家校合作的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/did=777
- 街区小店体验的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/W96=fLw
- 全民健身活动的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BA%BA%E7%89%A9?/943
- 应急物资管理的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BA%BA%E7%89%A9?/bro
- 城乡公共服务的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BA%BA%E7%89%A9?/slF
- 公共服务预约的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BA%BA%E7%89%A9?/848=doj
- 社区手工活动的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BA%BA%E7%89%A9?/idv=440
- 老年友好服务的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BA%BA%E7%89%A9?/pSp=Ujc
- 通勤路线规划的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%B8%93%E6%A0%8F?/228
- 无障碍出行的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%B8%93%E6%A0%8F?/dlw
- 社区花园共建的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%B8%93%E6%A0%8F?/Dyw
- 节日文化体验的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%B8%93%E6%A0%8F?/654=grh
- 新能源出行的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%B8%93%E6%A0%8F?/amc=078
- 便民信息查询的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E4%B8%93%E6%A0%8F?/Z8o=4q1
- 节能家电使用的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/979
- 读书会组织的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/dpo
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/zq3
- 公交无障碍服务的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/872=xpk
- 城市雨天出行的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/ouv=360
- 地方美食文化的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/ig0=Zhk
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/585
- 全民阅读推广的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/mkl
- 城市空气科普的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/EkP
- 个人时间管理的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/611=nnn
- 公共服务沟通的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/uhj=808
- 乡村产业科普的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/16y=8DW
- 城乡交流活动的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB_%E8%84%89%E8%84%89%E5%81%A5%E5%BA%B7?/378
- 图书馆数字服务有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB_%E8%84%89%E8%84%89%E5%81%A5%E5%BA%B7?/izy
- 农贸市场环境的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB_%E8%84%89%E8%84%89%E5%81%A5%E5%BA%B7?/5Pg
- 儿童友好空间的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB_%E8%84%89%E8%84%89%E5%81%A5%E5%BA%B7?/869=bah
- 小区停车协商的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB_%E8%84%89%E8%84%89%E5%81%A5%E5%BA%B7?/boe=249
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB_%E8%84%89%E8%84%89%E5%81%A5%E5%BA%B7?/1U4=2BD
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%89%BE%E4%B8%8D%E5%88%B0%E4%BA%86_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/143
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%89%BE%E4%B8%8D%E5%88%B0%E4%BA%86_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/whx
- 学校体育活动的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%89%BE%E4%B8%8D%E5%88%B0%E4%BA%86_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/D0m
- 城市公共标识的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%89%BE%E4%B8%8D%E5%88%B0%E4%BA%86_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/064=rjo
- 乡村公共服务的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%89%BE%E4%B8%8D%E5%88%B0%E4%BA%86_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/zni=367
- 开放数据应用的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%89%BE%E4%B8%8D%E5%88%B0%E4%BA%86_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/JQx=RHF
- 城市慢行系统的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8._%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/618
- 街道综合服务中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8._%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/psm
- 数字政务体验的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8._%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/2E7
- 创业经验分享的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8._%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/412=fli
- 小区公共照明的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8._%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/thp=372
- 绿色建筑理念的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8._%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/yoI=jQy
- 校园安全教育的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/174
- 社区文化节活动的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/lsw
- 社区绿色空间中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/pgq
- 社区安全巡查的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/676=ciy
- 城市慢跑路线的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/rqh=428
- 数字创意课程的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%9B%9B%E4%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/ZSi=EM0
- 数字课堂应用的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85welcome_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/616
- 远程协作工具的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85welcome_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/mds
- 数字支付体验的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85welcome_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/mkM
- 机器学习入门的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85welcome_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/891=zjh
- 家庭急救准备的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85welcome_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/xeg=533
- 小区停车协商的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85welcome_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/4MU=6kg
- 社区活动空间的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/737
- 节假日出行安排的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/qng
- 城市地名文化的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/T2l
- 城市住房服务的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/099=wyq
- 消防知识宣传的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/fke=384
- 地方文化传播的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/2d7=R0x
- 社区邻里服务的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/929
- 基层健康服务的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/pih
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/WJs
- 数字设备回收的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/189=xxu
- 公园亲子设施的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/mcd=530
- 健康信息获取的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/k9F=s29

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
