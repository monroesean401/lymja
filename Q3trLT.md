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

- 城市可持续生活的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_6768%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/570
- 社区儿童活动的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_6768%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/pin
- 校园节能行动的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_6768%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/08q
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_6768%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/235=etf
- 城市步行环境的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_6768%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/bph=496
- 线上阅读资源的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_6768%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/gyU=eeO
- 健康信息获取的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E7%BF%81%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/158
- 城市地名文化的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E7%BF%81%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/wft
- 社区文化节活动的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E7%BF%81%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/Mvh
- 文明养宠科普的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E7%BF%81%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/551=wfh
- 老年人日常照护的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E7%BF%81%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/kdf=201
- 文化遗产保护科普的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E7%BF%81%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/bN5=YSU
- 社区便民集市的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/001
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/kcx
- 数字阅读服务的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/cXF
- 学校体育活动的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/727=ydv
- 绿色建筑理念的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/epm=777
- 气象科普传播的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/cQv=yY8
- 城市博物馆活动的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/485
- 社区手工活动的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/gvi
- 乡村阅读空间的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/kLi
- 节日文化体验的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/913=xcy
- 公共交通信息服务的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/url=509
- 家庭养老规划的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/LRr=PgM
- 本地旅行体验的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BE%85%E5%8A%A9%E5%B7%A5%E5%85%B7app_%E5%8D%B3%E5%88%BB?/355
- 数字政务体验的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BE%85%E5%8A%A9%E5%B7%A5%E5%85%B7app_%E5%8D%B3%E5%88%BB?/jyt
- 居家适老化改造的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BE%85%E5%8A%A9%E5%B7%A5%E5%85%B7app_%E5%8D%B3%E5%88%BB?/5Jz
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BE%85%E5%8A%A9%E5%B7%A5%E5%85%B7app_%E5%8D%B3%E5%88%BB?/168=xwy
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BE%85%E5%8A%A9%E5%B7%A5%E5%85%B7app_%E5%8D%B3%E5%88%BB?/biz=886
- 职业技能学习的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BE%85%E5%8A%A9%E5%B7%A5%E5%85%B7app_%E5%8D%B3%E5%88%BB?/Gul=81K
- 城市应急广播的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8FApp_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/170
- 街道综合服务的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8FApp_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/zrz
- 数字地图应用的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8FApp_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/mX2
- 社区商业活力的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8FApp_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/203=urr
- 开放数据应用的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8FApp_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/rqa=735
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8FApp_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/RH6=duM
- 骑行路线规划的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E7%A8%B3%E5%AE%9A%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/774
- 亲子阅读活动的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E7%A8%B3%E5%AE%9A%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/mxb
- 数字素养提升的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E7%A8%B3%E5%AE%9A%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/QIx
- 老年人日常照护的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E7%A8%B3%E5%AE%9A%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/300=pid
- 节假日出行安排的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E7%A8%B3%E5%AE%9A%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/xtx=707
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E7%A8%B3%E5%AE%9A%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/eBC=iPa
- 社区教育资源的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/591
- 农产品品牌传播的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/hip
- 青少年职业启蒙的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/UB4
- 公共空间照明的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/015=vtu
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/bve=007
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/zbi=wM5
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB%EF%BC%8F3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92q%EF%BC%8Fq%E7%BE%A4_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/952
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB%EF%BC%8F3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92q%EF%BC%8Fq%E7%BE%A4_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/wph
- 社区手工活动的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB%EF%BC%8F3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92q%EF%BC%8Fq%E7%BE%A4_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/JTU
- 食品安全科普的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB%EF%BC%8F3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92q%EF%BC%8Fq%E7%BE%A4_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/592=nuv
- 家庭饮食安排的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB%EF%BC%8F3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92q%EF%BC%8Fq%E7%BE%A4_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/ggc=534
- 城市人文观察的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB%EF%BC%8F3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92q%EF%BC%8Fq%E7%BE%A4_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/CxE=0UU
- 周末休闲规划的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/194
- 社区公共卫生的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/rrx
- 城市公共饮水的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/xaC
- 城市体育设施的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/750=fya
- 创业经验分享的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/pcz=893
- 校园安全教育的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/zOI=Jxk
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Cqq%E7%BE%A4_360%E5%85%AC%E5%91%8A?/597
- 青少年科普实践的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Cqq%E7%BE%A4_360%E5%85%AC%E5%91%8A?/uqt
- 家庭饮食安排的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Cqq%E7%BE%A4_360%E5%85%AC%E5%91%8A?/k05
- 社区教育资源的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Cqq%E7%BE%A4_360%E5%85%AC%E5%91%8A?/757=iqd
- 社区垃圾分类的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Cqq%E7%BE%A4_360%E5%85%AC%E5%91%8A?/bwv=615
- 校园节能行动的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Cqq%E7%BE%A4_360%E5%85%AC%E5%91%8A?/22o=uJy
- 周末休闲规划的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/797
- 家庭陪伴活动从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/ijf
- 数据分析入门的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/P38
- 绿色消费选择的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/681=nti
- 科技馆参观体验的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/fbd=893
- 乡村教育资源的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/n0s=ZRP
- 社区文化节活动的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%28%E8%AF%BE%E5%A0%82%EF%BC%8F%E5%BD%A9%E6%B0%91%29%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/298
- 城市应急广播中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%28%E8%AF%BE%E5%A0%82%EF%BC%8F%E5%BD%A9%E6%B0%91%29%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/qsi
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%28%E8%AF%BE%E5%A0%82%EF%BC%8F%E5%BD%A9%E6%B0%91%29%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/TGm
- 城市游园体验的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%28%E8%AF%BE%E5%A0%82%EF%BC%8F%E5%BD%A9%E6%B0%91%29%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/089=wch
- 社区花园共建的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%28%E8%AF%BE%E5%A0%82%EF%BC%8F%E5%BD%A9%E6%B0%91%29%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/auf=030
- 乡村阅读空间的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%28%E8%AF%BE%E5%A0%82%EF%BC%8F%E5%BD%A9%E6%B0%91%29%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/gCi=oI8
- 智能家居应用的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92QQ%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/189
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92QQ%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/xkp
- 便民信息查询的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92QQ%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/HjR
- 农业科普体验的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92QQ%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/649=psw
- 生活垃圾减量的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92QQ%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/eyp=509
- 在线教育体验的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92QQ%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/exJ=AwQ
- 公共服务预约的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/734
- 社区托育服务的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/kmq
- 软件开发学习的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/Haw
- 老年友好服务的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/718=kri
- 社区便利生活的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/imu=838
- 智慧城市体验的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/hCt=rne
- 地方民俗记录的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/549
- 生成式工具使用的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/wen
- 乡村电商实践的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/F2O
- 街区更新实践的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/289=ayt
- 科学观察活动的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/lpd=442
- 个人时间管理的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/5bA=pxF
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/583
- 公共场所导视的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/afh
- 个人时间管理的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/9Xd
- 公共服务指南的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/909=kwr
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/xzf=261
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/xdh=m8Y
- 节约用水实践的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%913d%E8%AE%A1%E5%88%92%E8%BF%BD%E5%8F%B7_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/310
- 城市住房服务的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%913d%E8%AE%A1%E5%88%92%E8%BF%BD%E5%8F%B7_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/okh
- 志愿者培训交流的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%913d%E8%AE%A1%E5%88%92%E8%BF%BD%E5%8F%B7_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/NjZ
- 无障碍出行的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%913d%E8%AE%A1%E5%88%92%E8%BF%BD%E5%8F%B7_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/971=oiv
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%913d%E8%AE%A1%E5%88%92%E8%BF%BD%E5%8F%B7_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/fgc=168
- 社区邻里服务的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%913d%E8%AE%A1%E5%88%92%E8%BF%BD%E5%8F%B7_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/Rv9=x5n
- 乡村电商实践的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%913d%E8%AE%A1%E5%88%92%E6%95%B0%E5%AD%97_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/291
- 城市游园体验的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%913d%E8%AE%A1%E5%88%92%E6%95%B0%E5%AD%97_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/jxg
- 气象科普传播的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%913d%E8%AE%A1%E5%88%92%E6%95%B0%E5%AD%97_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/aEl
- 公共交通信息服务从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%913d%E8%AE%A1%E5%88%92%E6%95%B0%E5%AD%97_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/057=vtx
- 医院导诊服务的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%913d%E8%AE%A1%E5%88%92%E6%95%B0%E5%AD%97_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/tnr=637
- 数字公共文化中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%913d%E8%AE%A1%E5%88%92%E6%95%B0%E5%AD%97_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/LgT=nRf
- 公共交通信息服务的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%913d5%E7%A0%81%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/931
- 社区活动策划的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%913d5%E7%A0%81%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/clg
- 公益活动组织的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%913d5%E7%A0%81%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/4hX
- 公交站点体验的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%913d5%E7%A0%81%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/331=ugv
- 家庭消费规划的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%913d5%E7%A0%81%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/ohq=243
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%913d5%E7%A0%81%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/3p0=jAJ
- 乡村公共文化的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%913d%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%8E%A9_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/310
- 城市步行友好的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%913d%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%8E%A9_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/ugk
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%913d%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%8E%A9_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/BZI
- 口袋公园建设的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%913d%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%8E%A9_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/790=xfu
- 社区消防演练的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%913d%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%8E%A9_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/rib=385
- 青少年户外教育的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%913d%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%8E%A9_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/xLg=6ny
- 乡村电商实践的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/262
- 城市夜间生活的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/xse
- 学校体育活动的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/3UV
- 社区慢性病防控的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/574=sry
- 小微企业服务的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/hrt=416
- 生活垃圾回收的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/d1z=cKH
- 家庭环保习惯的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E7%BD%91_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/137
- 社区邻里服务的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E7%BD%91_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/xgu
- 城市可持续生活的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E7%BD%91_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/ugo
- 数据分析入门的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E7%BD%91_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/511=ndh
- 公共设施维护的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E7%BD%91_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/vrw=051
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E7%BD%91_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/AgR=HSm
- 城市游园体验的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_v%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A98ii_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/561
- 城市夜间照明的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_v%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A98ii_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/xxo
- 城市休闲步道的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_v%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A98ii_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/KCI
- 儿童户外活动的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_v%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A98ii_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/816=job
- 城市生活记录的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_v%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A98ii_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/rxq=326
- 在线学习体验的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_v%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A98ii_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/Aqa=siq
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8viiv_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/235
- 文化场馆预约的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8viiv_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/qmo
- 课后服务体验的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8viiv_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/5a0
- 社区心理支持的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8viiv_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/808=jlt
- 乡村阅读空间的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8viiv_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/bsn=984
- 亲子科普活动的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8viiv_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/m93=1hd
- 社区绿色空间的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/184
- 人工智能科普的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/isj
- 健康信息获取的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/yRZ
- 节气饮食文化的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/146=edg
- 公交站点体验的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/uxq=552
- 绿色校园实践的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/lvy=lZx
- 城市应急科普的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85app_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/532
- 老年人文化生活的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85app_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/yyo
- 社区法律科普的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85app_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/F2t
- 电子商务服务的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85app_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/928=kci
- 老年数字阅读的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85app_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/iim=314
- 社区学习活动的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85app_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/iN2=qri
- 安全出行教育的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%89%E8%A3%85_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/735
- 城市雨天出行的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%89%E8%A3%85_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/svu
- 地方文化传播的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%89%E8%A3%85_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/kj0
- 社区商业活力中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%89%E8%A3%85_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/726=lts
- 科学信息获取的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%89%E8%A3%85_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/ufv=163
- 节日文化体验的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%89%E8%A3%85_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/1Dq=KV8
- 城市噪声观察的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/155
- 城市建设科普的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/exx
- 社区共享书架的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/4dR
- 公共卫生设施的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/122=rdn
- 公共场所导视的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/pgk=918
- 旧物循环利用的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/A5r=GMS
- 城市建设科普的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/478
- 社区文化节活动的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/kzl
- 安全出行教育的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/ix5
- 地方文化传播的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/066=ffo
- 药品使用科普的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/sbw=337
- 社区志愿服务的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/hLH=Xc6
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/654
- 地方旅游导览的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/wyu
- 线上办事服务的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/5qz
- 智慧城市体验的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/942=uha
- 城市夜间生活的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/kew=617
- 图书借阅体验的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/lp9=isg
- 节气饮食文化的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F?/527
- 学校体育活动的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F?/dxr
- 社区设施共享的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F?/dRt
- 创业经验分享的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F?/268=rhv
- 青年志愿活动的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F?/cev=938
- 绿色出行服务的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F?/swL=siJ
- 公交站点体验的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/378
- 社区艺术活动的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/qnt
- 节假日出行安排的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/5av
- 乡村电商实践的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/746=rwn
- 社区便利生活的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/frx=864
- 节能家电使用的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/qNI=Kp9
- 公共健身器材的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9150%E5%9D%97%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/704
- 城市适老服务的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9150%E5%9D%97%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/hqw
- 老年智能设备的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9150%E5%9D%97%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/xfS
- 便民服务窗口的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9150%E5%9D%97%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/098=ohy
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9150%E5%9D%97%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/ldv=576
- 电子商务服务的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9150%E5%9D%97%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/GmS=mXl
- 小区停车协商的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%A2%E9%98%9F%E4%B8%93%E4%B8%9A%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/292
- 城市文明实践中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%A2%E9%98%9F%E4%B8%93%E4%B8%9A%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/clu
- 社区托育服务的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%A2%E9%98%9F%E4%B8%93%E4%B8%9A%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/7o5
- 电动汽车充电的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%A2%E9%98%9F%E4%B8%93%E4%B8%9A%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/408=hxg
- 新能源出行的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%A2%E9%98%9F%E4%B8%93%E4%B8%9A%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/nhf=753
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%9B%A2%E9%98%9F%E4%B8%93%E4%B8%9A%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/AB9=UF8
- 家庭收纳实践的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/356
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/oji
- 节能生活方式的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/L2d
- 校园节能行动的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/800=xwh
- 家庭食品保存的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/fvm=435
- 社区读书角建设的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/2VH=zrb
- 校园节能行动中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/140
- 社区养老服务的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/ggq
- 公共服务咨询的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/I1g
- 社区文化传播的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/964=yxq
- 邻里共享空间的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/mes=857
- 城市住房服务的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/ono=JLH
- 非遗体验活动的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B7%9F%E5%AF%BC%E5%B8%88%E4%B9%B0%E5%BD%A9%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/048
- 城市博物馆服务的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B7%9F%E5%AF%BC%E5%B8%88%E4%B9%B0%E5%BD%A9%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/hsq
- 家庭健康管理的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B7%9F%E5%AF%BC%E5%B8%88%E4%B9%B0%E5%BD%A9%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/xTK
- 校园安全教育的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B7%9F%E5%AF%BC%E5%B8%88%E4%B9%B0%E5%BD%A9%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/691=bjd
- 开放式学习空间的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B7%9F%E5%AF%BC%E5%B8%88%E4%B9%B0%E5%BD%A9%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/sgv=578
- 社区设施共享的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B7%9F%E5%AF%BC%E5%B8%88%E4%B9%B0%E5%BD%A9%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/66P=CsH
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/507
- 城市文明出行的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/qxg
- 数字档案服务的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/NMb
- 社区教育资源的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/131=daq
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/fhw=346
- 智能手机助老的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/YrN=ROu
- 城市便民驿站的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E7%B3%BB%E7%BB%9F_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/051
- 终身学习资源的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E7%B3%BB%E7%BB%9F_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/zpa
- 社区艺术活动的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E7%B3%BB%E7%BB%9F_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/bRZ
- 社区设施共享的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E7%B3%BB%E7%BB%9F_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/029=lxa
- 社区设施共享的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E7%B3%BB%E7%BB%9F_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/fjq=283
- 社区休闲设施的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E7%B3%BB%E7%BB%9F_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/bnS=zL9
- 数字艺术创作中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/759
- 街头绿植养护的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/qmw
- 科学睡眠习惯的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/RWU
- 城市公共座椅的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/946=uur
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/bta=674
- 光伏知识科普的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/Ne8=Rr7
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/006
- 公共卫生设施的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/gpj
- 公共图书馆服务的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/3kV
- 社区活动报名的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/933=hkz

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
