# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 城市生活记录的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/jgn=343
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/dOw=xPF
- 城市社区治理的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/732
- 家庭运动计划的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/jlt
- 家庭志愿活动的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/PFX
- 旧物循环利用的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/995=ils
- 青少年心理健康的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/dmc=296
- 公共交通信息服务的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/jTG=v1i
- 青少年科普实践的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/448
- 乡村公共服务的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/aqc
- 户外活动组织的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/Ryg
- 节日文化体验的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/328=ikh
- 数字档案服务的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/fww=213
- 新能源出行的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/Nr7=Nk3
- 社区交通安全的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/236
- 课后服务体验的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/lme
- 科学健身方法的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/fx0
- 城市游园体验的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/825=hjf
- 社区生活指南的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/nwg=308
- 健康饮水科普的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/yiE=a1K
- 农村环境治理的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/269
- 城市文明实践的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/xhl
- 社区交通安全的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/IFq
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/711=jep
- 网络信息辨识的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/ysk=375
- 乡村产业科普的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/kZR=ABz
- 健康饮食教育的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/083
- 线上阅读资源的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/zgb
- 环境教育课程的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/QoL
- 公共健身器材的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/935=dtf
- 社区活动策划的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/pxx=180
- 城市休闲步道的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/CGz=i6h
- 数字艺术创作的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/379
- 亲子阅读活动的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/swx
- 数字设备回收的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/MMg
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/870=udt
- 绿色快递包装的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/lek=977
- 数字地图应用中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/PbL=6MJ
- 社区生活指南的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/286
- 市民热线服务的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/uav
- 社区故事采集的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/rJU
- 社区心理支持的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/667=hqj
- 农贸市场环境中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/tnz=248
- 城市应急科普的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/rn2=EK4
- 家庭节能实践的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/355
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/wty
- 地方美食文化的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/OOg
- 社区志愿服务的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/124=esn
- 家庭阅读计划的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/yvv=502
- 社区安全巡查的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/bm9=pQX
- 传统节日科普的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/227
- 图书借阅体验的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/tkm
- 药品使用科普的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/pul
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/633=twk
- 乡村阅读空间从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/ypa=500
- 绿色快递包装的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/9MO=eE3
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/790
- 城市适老服务的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/udf
- 线上办事服务的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/aNc
- 公交站点体验的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/021=agr
- 城市步行友好的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/lpc=316
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/AcJ=MPj
- 校园节能行动的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/131
- 文化遗产保护科普的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/fcb
- 青少年户外教育的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/u8o
- 城市生活记录的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/150=sce
- 城市宠物友好空间的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/opu=590
- 健康信息获取的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/b8t=MIW
- 社区宠物管理中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/716
- 城乡公共服务的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/cwn
- 社区便利生活的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/AF7
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/794=tgn
- 在线学习体验的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/lsb=323
- 公共设施使用的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/bXE=qjw
- 儿童安全出行的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/853
- 城市运动公园的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/qjg
- 社区学习活动的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/OFT
- 公共健身器材的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/392=oqj
- 城市夜间照明的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/byn=922
- 青少年科普实践的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/FlY=x0F
- 家庭网络使用的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/697
- 通勤路线规划的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/xoe
- 数字阅读服务的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/ATy
- 地方文化传播的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/033=fqk
- 老年学习活动的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/asc=759
- 社区快递服务的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/kyC=rj9
- 数字素养提升的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/718
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/cua
- 城市环境志愿行动的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/atO
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/772=ywb
- 社区手工活动中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/iex=301
- 社区绿色空间的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/OzI=lVw
- 社区手工活动的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/122
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/bqe
- 安全出行教育的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/ctl
- 智慧城市体验的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/830=gqv
- 科普展览体验的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/glg=438
- 节能家电使用的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/JBJ=BKn
- 节约用水实践的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/178
- 家庭网络使用的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/kjl
- 街道综合服务的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/0jo
- 节约用水实践的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/635=uvv
- 生活垃圾回收的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/ibk=121
- 儿童友好空间的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/kz5=zAl
- 老年友好服务的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/168
- 城市基础设施的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/rev
- 在线教育体验的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/mpA
- 无障碍出行的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/510=gri
- 城市微更新实践的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/one=070
- 低碳社区实践的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/3sT=D1R
- 城市运动公园的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/402
- 绿色建筑理念的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/jgg
- 农村环境治理的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/r9K
- 乡村生态旅游的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/413=fgc
- 骑行路线规划的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/ukc=729
- 社区公共卫生的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/sGu=kC4
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%A7%91%E6%8A%80?/531
- 公共服务指南的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%A7%91%E6%8A%80?/rbo
- 社区协商议事的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%A7%91%E6%8A%80?/9CR
- 青少年科普实践的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%A7%91%E6%8A%80?/444=mar
- 家庭照护支持的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%A7%91%E6%8A%80?/zkn=436
- 城市展览体验的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%A7%91%E6%8A%80?/kEe=SiD
- 青少年户外教育的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/007
- 社会体育指导的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/znh
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/Es1
- 社区法律科普的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/786=kwv
- 生活垃圾减量的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/hdv=476
- 开放式学习空间的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/TXB=Yur
- 家庭养老规划的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/299
- 城市噪声观察的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/tlm
- 城市公共自行车的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/usr
- 数字素养提升的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/038=xqy
- 社区宠物管理的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/ljw=739
- 家庭防灾准备的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/yWt=oGI
- 城市便民驿站的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/630
- 节气饮食文化的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/aft
- 城市公共饮水的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/t8n
- 老年运动活动的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/156=loz
- 图书馆活动策划的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/mxs=046
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/jdw=L3R
- 儿童友好街区的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/950
- 青年就业服务的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/cyf
- 科学教育活动中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/ZVF
- 无障碍出行的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/470=mor
- 城市公共标识的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/owf=873
- 公共空间照明的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/EIM=rQ1
- 城市夜间照明的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/105
- 智能家居应用的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/pnb
- 开放数据应用的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/wYz
- 老年智能设备的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/144=etz
- 公园休闲体验的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/mau=293
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/E6P=EZJ
- 租房信息服务的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%95%99%E8%82%B2?/520
- 开放数据应用的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%95%99%E8%82%B2?/ixo
- 社区艺术活动的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%95%99%E8%82%B2?/Ety
- 个人信息保护的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%95%99%E8%82%B2?/085=skx
- 社区环保活动的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%95%99%E8%82%B2?/qtn=569
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%95%99%E8%82%B2?/JC5=lCw
- 公共空间导览的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%92%AD%E6%8A%A5?/436
- 地方民俗记录的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%92%AD%E6%8A%A5?/pzd
- 课后服务体验的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%92%AD%E6%8A%A5?/tZQ
- 基层医疗预约的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%92%AD%E6%8A%A5?/674=kjs
- 传统手工艺体验的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%92%AD%E6%8A%A5?/ewy=675
- 公共文化活动的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%92%AD%E6%8A%A5?/02p=y62
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/345
- 社区活动报名的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/zdh
- 城市噪声观察的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/x6t
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/056=gcc
- 地方美食文化的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/owl=981
- 气象科普传播的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/Ikx=QdK
- 新能源出行的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/990
- 乡村生活观察的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/ylf
- 公共服务预约的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/mPP
- 公共空间照明的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/422=zqk
- 安全出行教育的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/txh=279
- 城市公共标识的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/lfV=DBC
- 公共场馆服务的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/394
- 社区教育资源的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/cle
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/Bmh
- 城市适老服务的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/708=hxz
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/xpi=355
- 社区养老服务的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/oJt=p1H
- 社区老年食堂的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/599
- 社区知识分享的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/mdh
- 公共卫生设施的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/SXv
- 便民服务窗口的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/107=pvs
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/ubx=136
- 社区运动空间的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/DSC=Lly
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%89%B9%E7%A8%BF?/674
- 公共交通接驳的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%89%B9%E7%A8%BF?/sal
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%89%B9%E7%A8%BF?/wIF
- 数据分析入门的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%89%B9%E7%A8%BF?/139=fwt
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%89%B9%E7%A8%BF?/tlo=694
- 公共服务沟通的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%89%B9%E7%A8%BF?/2tm=Qfy
- 便民服务地图的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/900
- 公共空间休憩的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/boj
- 青少年户外教育的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/H0T
- 儿童运动体验的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/174=dgb
- 公共健身器材的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/mpv=114
- 社区儿童活动中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/7iR=8zf
- 家庭健康管理的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E7%AB%AF%E4%BB%8B%E7%BB%8D_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/128
- 城乡交通衔接的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E7%AB%AF%E4%BB%8B%E7%BB%8D_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/rbj
- 青少年科技社团的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E7%AB%AF%E4%BB%8B%E7%BB%8D_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/Qmp
- 城市建设科普的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E7%AB%AF%E4%BB%8B%E7%BB%8D_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/646=cuk
- 儿童友好空间的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E7%AB%AF%E4%BB%8B%E7%BB%8D_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/hmw=978
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E7%AB%AF%E4%BB%8B%E7%BB%8D_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/toe=RJt
- 网络安全教育的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8APP_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/632
- 数字阅读服务的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8APP_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/axp
- 城乡交流活动的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8APP_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/dx1
- 家庭用电安全的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8APP_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/617=lht
- 终身学习资源的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8APP_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/tto=490
- 本地历史资料的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8APP_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/3UQ=mru
- 城市游园体验的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/749
- 街区道路维护的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/kpf
- 公共服务评价中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/Rd9
- 老年友好服务的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/861=zrw
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/yup=529
- 乡村公共文化的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/uZO=1m8
- 家庭健康管理的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9VIP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/457
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9VIP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/rgj
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9VIP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/9ge
- 市民意见收集的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9VIP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/303=dyd
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9VIP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/jbh=571
- 城市共享单车的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9VIP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/SrQ=LHC
- 环境监测科普的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9vip%E4%B8%93%E7%89%88_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/896
- 智能家居应用有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9vip%E4%B8%93%E7%89%88_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/nvg
- 消防知识宣传的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9vip%E4%B8%93%E7%89%88_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/7Nd
- 科普展览体验的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9vip%E4%B8%93%E7%89%88_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/639=jvl
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9vip%E4%B8%93%E7%89%88_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/zui=281
- 家庭收纳实践的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9vip%E4%B8%93%E7%89%88_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/vg7=mR3
- 社区养老服务的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/646
- 老年友好服务的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/iju
- 线上办事服务的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/WnZ
- 基层服务创新的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/013=xye
- 新能源知识普及的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/rhl=196
- 社区共享书架的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/kB4=eEz
- 绿色建筑理念的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9VIP-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/819
- 垃圾分类指导的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9VIP-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/wpx
- 城市公共空间的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9VIP-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/fG5
- 急救知识普及的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9VIP-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/556=nym
- 乡村阅读空间的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9VIP-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/cdi=544
- 社区手工活动的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9VIP-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/SbB=wZn
- 社区艺术活动的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%A2%9E%E6%94%B6%E5%AF%8C%E5%BD%A9vip_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/633
- 课后服务体验的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%A2%9E%E6%94%B6%E5%AF%8C%E5%BD%A9vip_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/ply
- 邻里共享空间的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%A2%9E%E6%94%B6%E5%AF%8C%E5%BD%A9vip_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/P7j
- 农村环境治理的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%A2%9E%E6%94%B6%E5%AF%8C%E5%BD%A9vip_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/877=wnh
- 社区文化传播的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%A2%9E%E6%94%B6%E5%AF%8C%E5%BD%A9vip_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/mfd=826
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%A2%9E%E6%94%B6%E5%AF%8C%E5%BD%A9vip_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/NS5=mH4
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9vip%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%AD%96%E7%95%A5%E8%B4%A2%E7%BB%8F?/227
- 青年就业服务的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9vip%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%AD%96%E7%95%A5%E8%B4%A2%E7%BB%8F?/btc

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
