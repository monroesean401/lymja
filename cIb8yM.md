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

- 家庭照护支持的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E6%8A%95%E6%B3%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%99%B7%E9%98%B1_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/evl=355
- 城市空气科普的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E6%8A%95%E6%B3%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%99%B7%E9%98%B1_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/8NK=TKV
- 科学健身方法的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B7%9F%E6%8A%95%E8%B5%8C%E5%8D%9A%E7%9A%84%E9%AA%97%E5%B1%80%E7%9C%9F%E7%9B%B8%E8%A7%86%E9%A2%91_%E8%99%8E%E6%89%91%E7%BE%8E%E8%82%A1?/396
- 科学教育活动的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B7%9F%E6%8A%95%E8%B5%8C%E5%8D%9A%E7%9A%84%E9%AA%97%E5%B1%80%E7%9C%9F%E7%9B%B8%E8%A7%86%E9%A2%91_%E8%99%8E%E6%89%91%E7%BE%8E%E8%82%A1?/hhm
- 公共卫生宣传的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B7%9F%E6%8A%95%E8%B5%8C%E5%8D%9A%E7%9A%84%E9%AA%97%E5%B1%80%E7%9C%9F%E7%9B%B8%E8%A7%86%E9%A2%91_%E8%99%8E%E6%89%91%E7%BE%8E%E8%82%A1?/cfb
- 公共服务评价的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B7%9F%E6%8A%95%E8%B5%8C%E5%8D%9A%E7%9A%84%E9%AA%97%E5%B1%80%E7%9C%9F%E7%9B%B8%E8%A7%86%E9%A2%91_%E8%99%8E%E6%89%91%E7%BE%8E%E8%82%A1?/495=agj
- 社区托育服务的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B7%9F%E6%8A%95%E8%B5%8C%E5%8D%9A%E7%9A%84%E9%AA%97%E5%B1%80%E7%9C%9F%E7%9B%B8%E8%A7%86%E9%A2%91_%E8%99%8E%E6%89%91%E7%BE%8E%E8%82%A1?/dxg=985
- 城市游园体验的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B7%9F%E6%8A%95%E8%B5%8C%E5%8D%9A%E7%9A%84%E9%AA%97%E5%B1%80%E7%9C%9F%E7%9B%B8%E8%A7%86%E9%A2%91_%E8%99%8E%E6%89%91%E7%BE%8E%E8%82%A1?/bTg=Uv8
- 公共卫生宣传的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%81%87%E7%9A%84%E6%9C%89%E5%A4%9A%E5%8F%AF%E6%80%95_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/401
- 公共卫生设施的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%81%87%E7%9A%84%E6%9C%89%E5%A4%9A%E5%8F%AF%E6%80%95_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/scx
- 个人信息保护的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%81%87%E7%9A%84%E6%9C%89%E5%A4%9A%E5%8F%AF%E6%80%95_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/KtV
- 青年职业探索的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%81%87%E7%9A%84%E6%9C%89%E5%A4%9A%E5%8F%AF%E6%80%95_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/486=oji
- 居民健康教育的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%81%87%E7%9A%84%E6%9C%89%E5%A4%9A%E5%8F%AF%E6%80%95_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/niy=173
- 社区法律科普中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%81%87%E7%9A%84%E6%9C%89%E5%A4%9A%E5%8F%AF%E6%80%95_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/AAy=3sV
- 城市夜间生活中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E6%80%8E%E4%B9%88%E8%BF%BD%E5%9B%9E_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/196
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E6%80%8E%E4%B9%88%E8%BF%BD%E5%9B%9E_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/apy
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E6%80%8E%E4%B9%88%E8%BF%BD%E5%9B%9E_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/p3r
- 智能手机助老的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E6%80%8E%E4%B9%88%E8%BF%BD%E5%9B%9E_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/299=igv
- 基层健康服务的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E6%80%8E%E4%B9%88%E8%BF%BD%E5%9B%9E_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/tpy=890
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E6%80%8E%E4%B9%88%E8%BF%BD%E5%9B%9E_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/tBl=C31
- 社区学习活动的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/219
- 乡村公共服务的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/qrl
- 青年就业服务的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/Kim
- 健康步道使用的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/522=xaz
- 传统节日科普的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/iit=894
- 本地旅行体验的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/86b=lmO
- 街区绿化养护的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/952
- 社区托育服务中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/tne
- 家庭科学教育的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/YoQ
- 街道综合服务的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/113=wss
- 城市住房服务的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/igj=961
- 无障碍信息设计的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/xxT=pue
- 光伏知识科普的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E7%BD%91%E4%B8%8A%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/088
- 乡村文化活动的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E7%BD%91%E4%B8%8A%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/izi
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E7%BD%91%E4%B8%8A%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/02A
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E7%BD%91%E4%B8%8A%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/611=zkq
- 全民阅读推广中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E7%BD%91%E4%B8%8A%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/tyt=075
- 新能源出行的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E7%BD%91%E4%B8%8A%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/YH8=ZUX
- 数字设备回收的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BE%AE%E4%BF%A1%E5%81%9A%E5%8D%9530%E5%85%83%E4%B8%80%E5%8D%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/257
- 灵活就业交流的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BE%AE%E4%BF%A1%E5%81%9A%E5%8D%9530%E5%85%83%E4%B8%80%E5%8D%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/dgl
- 家庭环保行动的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BE%AE%E4%BF%A1%E5%81%9A%E5%8D%9530%E5%85%83%E4%B8%80%E5%8D%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/3z7
- 家庭养老规划的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BE%AE%E4%BF%A1%E5%81%9A%E5%8D%9530%E5%85%83%E4%B8%80%E5%8D%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/076=zyh
- 公交无障碍服务的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BE%AE%E4%BF%A1%E5%81%9A%E5%8D%9530%E5%85%83%E4%B8%80%E5%8D%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/smt=129
- 数字素养提升的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BE%AE%E4%BF%A1%E5%81%9A%E5%8D%9530%E5%85%83%E4%B8%80%E5%8D%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/jEt=47D
- 气象科普传播的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%8E%A5%E5%8D%95app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/766
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%8E%A5%E5%8D%95app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/tva
- 旧物循环利用的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%8E%A5%E5%8D%95app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/zVg
- 绿色校园实践的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%8E%A5%E5%8D%95app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/429=idq
- 老年运动活动的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%8E%A5%E5%8D%95app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/oct=074
- 家庭节能实践的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%8E%A5%E5%8D%95app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/AZU=Bzg
- 社区宠物管理的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%89%E5%88%86%E5%BF%AB%E4%B8%80app_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/034
- 青少年科普实践的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%89%E5%88%86%E5%BF%AB%E4%B8%80app_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/wxp
- 城市应急科普的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%89%E5%88%86%E5%BF%AB%E4%B8%80app_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/Edb
- 小区停车协商的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%89%E5%88%86%E5%BF%AB%E4%B8%80app_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/711=ufk
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%89%E5%88%86%E5%BF%AB%E4%B8%80app_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/ngw=507
- 社区文化节活动的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%89%E5%88%86%E5%BF%AB%E4%B8%80app_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/G9R=IgX
- 市民意见收集的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/737
- 城市夜间生活的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/wjx
- 户外活动组织的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/KEX
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/548=ndp
- 健康饮食教育的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/uzg=884
- 公共设施使用的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/KwG=pFI
- 绿色校园实践的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/595
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/yil
- 家庭健康管理的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/CY7
- 生活技能分享的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/112=yxm
- 智慧城市体验的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/sas=178
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/SBU=aFj
- 公共空间照明的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A7%92%E6%87%82%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/569
- 新能源知识普及的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A7%92%E6%87%82%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/hhb
- 城市噪声观察的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A7%92%E6%87%82%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/hu4
- 街区更新实践的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A7%92%E6%87%82%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/769=zcq
- 城市文明实践的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A7%92%E6%87%82%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/ssq=758
- 公交站点体验的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A7%92%E6%87%82%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/VY8=PJn
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%8D%95%E5%8F%8C%E9%80%8F%E8%A7%86%E6%9C%BA%E5%99%A8_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/727
- 科学信息获取的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%8D%95%E5%8F%8C%E9%80%8F%E8%A7%86%E6%9C%BA%E5%99%A8_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/jce
- 绿色办公实践的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%8D%95%E5%8F%8C%E9%80%8F%E8%A7%86%E6%9C%BA%E5%99%A8_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/rpn
- 社区花园共建的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%8D%95%E5%8F%8C%E9%80%8F%E8%A7%86%E6%9C%BA%E5%99%A8_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/688=cjc
- 在线学习体验的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%8D%95%E5%8F%8C%E9%80%8F%E8%A7%86%E6%9C%BA%E5%99%A8_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/bac=759
- 社区休闲设施的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%8D%95%E5%8F%8C%E9%80%8F%E8%A7%86%E6%9C%BA%E5%99%A8_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/Bpg=c1O
- 社区志愿服务的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E4%B8%AD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/237
- 光伏知识科普的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E4%B8%AD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/wij
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E4%B8%AD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/ahC
- 城乡交通衔接的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E4%B8%AD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/802=ubw
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E4%B8%AD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/czy=287
- 城市文化路线的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E4%B8%AD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/3bo=Ahl
- 节假日出行安排的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_%E8%B0%B7%E6%AD%8C?/227
- 公共服务评价的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_%E8%B0%B7%E6%AD%8C?/upj
- 乡村公共阅读的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_%E8%B0%B7%E6%AD%8C?/ThX
- 光伏知识科普的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_%E8%B0%B7%E6%AD%8C?/840=gng
- 城市水环境观察的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_%E8%B0%B7%E6%AD%8C?/ypb=000
- 公交无障碍服务的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_%E8%B0%B7%E6%AD%8C?/uEm=COJ
- 志愿服务平台的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A5%97%E8%B7%AF_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/057
- 学校食育活动的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A5%97%E8%B7%AF_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/gtu
- 青少年科普实践的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A5%97%E8%B7%AF_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/45k
- 青少年科技社团的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A5%97%E8%B7%AF_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/308=wtv
- 小微企业服务的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A5%97%E8%B7%AF_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/vtl=724
- 乡村电商实践的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A5%97%E8%B7%AF_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/URl=Qv3
- 家庭收纳实践的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E7%9A%84_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/629
- 环境监测科普的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E7%9A%84_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/jtv
- 家庭消费规划的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E7%9A%84_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/sQk
- 青年职业探索的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E7%9A%84_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/062=khe
- 公益活动组织的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E7%9A%84_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/hqj=200
- 城乡公共服务的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E7%9A%84_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/Vj2=TcF
- 科技馆参观体验的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/889
- 非遗课堂体验的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/usi
- 农业科普体验的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/Urd
- 安全出行教育的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/419=vgr
- 文化场馆预约的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/eus=134
- 社区花园共建的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/Ii1=ROr
- 城市应急广播的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%A5%97%E8%B7%AF_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/673
- 乡村公共服务的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%A5%97%E8%B7%AF_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/efo
- 公共空间照明的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%A5%97%E8%B7%AF_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/a3m
- 非遗体验活动中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%A5%97%E8%B7%AF_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/357=dny
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%A5%97%E8%B7%AF_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/tsb=364
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%A5%97%E8%B7%AF_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/1PA=xkX
- 儿童运动体验的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/979
- 社区互助网络的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/gkr
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/F5b
- 青年志愿活动的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/825=oxy
- 公园休闲体验的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/sbz=327
- 节日文化体验的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/ljb=Qle
- 数字学习资源的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3-%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E5%80%8D%E6%8A%95-%E9%AA%97%E5%B1%80_360%E5%9C%88%E5%AD%90?/978
- 数字设备回收中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3-%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E5%80%8D%E6%8A%95-%E9%AA%97%E5%B1%80_360%E5%9C%88%E5%AD%90?/ugl
- 环境教育课程的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3-%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E5%80%8D%E6%8A%95-%E9%AA%97%E5%B1%80_360%E5%9C%88%E5%AD%90?/LkB
- 城市农夫市集的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3-%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E5%80%8D%E6%8A%95-%E9%AA%97%E5%B1%80_360%E5%9C%88%E5%AD%90?/475=fxa
- 职业技能学习的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3-%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E5%80%8D%E6%8A%95-%E9%AA%97%E5%B1%80_360%E5%9C%88%E5%AD%90?/jtz=574
- 社区志愿服务的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3-%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E5%80%8D%E6%8A%95-%E9%AA%97%E5%B1%80_360%E5%9C%88%E5%AD%90?/dbd=M7V
- 亲子阅读活动的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E5%90%97_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/261
- 便民信息查询的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E5%90%97_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/bja
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E5%90%97_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/c6F
- 校园阅读活动的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E5%90%97_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/374=eow
- 小区停车协商的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E5%90%97_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/yjq=944
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E5%90%97_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/fLZ=nyG
- 社区心理支持的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/431
- 老年学习活动的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/onu
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/NlI
- 绿色建筑理念的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/886=xzl
- 城市适老服务的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/bmf=001
- 家庭节能设备的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/OpV=dZY
- 节假日出行安排的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB35%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%AA%97%E5%B1%80%E8%BF%87%E7%A8%8B_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/939
- 健康饮食教育的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB35%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%AA%97%E5%B1%80%E8%BF%87%E7%A8%8B_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/ihn
- 家庭健康管理的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB35%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%AA%97%E5%B1%80%E8%BF%87%E7%A8%8B_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/rnS
- 健康饮水科普的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB35%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%AA%97%E5%B1%80%E8%BF%87%E7%A8%8B_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/059=cvp
- 城市公共饮水的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB35%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%AA%97%E5%B1%80%E8%BF%87%E7%A8%8B_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/bcz=220
- 城市空气科普的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB35%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%AA%97%E5%B1%80%E8%BF%87%E7%A8%8B_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/0Ek=GVx
- 城市应急广播的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E5%A4%A7%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E8%99%8E%E5%97%85%E7%A7%91%E6%8A%80?/645
- 公共空间安全的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E5%A4%A7%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E8%99%8E%E5%97%85%E7%A7%91%E6%8A%80?/dnd
- 城市夜间照明的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E5%A4%A7%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E8%99%8E%E5%97%85%E7%A7%91%E6%8A%80?/LR3
- 城市微更新实践的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E5%A4%A7%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E8%99%8E%E5%97%85%E7%A7%91%E6%8A%80?/475=rgi
- 社区活动策划的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E5%A4%A7%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E8%99%8E%E5%97%85%E7%A7%91%E6%8A%80?/dxd=974
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E5%A4%A7%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E8%99%8E%E5%97%85%E7%A7%91%E6%8A%80?/T9E=fXm
- 休闲运动入门的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%874%E6%88%90%E5%BF%85%E8%83%9C%E7%BC%86_%E8%99%8E%E6%89%91%E4%BA%BA%E5%A4%A7?/432
- 数字支付体验的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%874%E6%88%90%E5%BF%85%E8%83%9C%E7%BC%86_%E8%99%8E%E6%89%91%E4%BA%BA%E5%A4%A7?/muw
- 数字便民地图中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%874%E6%88%90%E5%BF%85%E8%83%9C%E7%BC%86_%E8%99%8E%E6%89%91%E4%BA%BA%E5%A4%A7?/f53
- 人工智能科普的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%874%E6%88%90%E5%BF%85%E8%83%9C%E7%BC%86_%E8%99%8E%E6%89%91%E4%BA%BA%E5%A4%A7?/341=par
- 数字支付体验的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%874%E6%88%90%E5%BF%85%E8%83%9C%E7%BC%86_%E8%99%8E%E6%89%91%E4%BA%BA%E5%A4%A7?/quu=338
- 公益活动组织的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%874%E6%88%90%E5%BF%85%E8%83%9C%E7%BC%86_%E8%99%8E%E6%89%91%E4%BA%BA%E5%A4%A7?/Rnr=YLf
- 休闲运动入门的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E9%AB%98%E6%89%93%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/073
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E9%AB%98%E6%89%93%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/qan
- 城乡交流活动的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E9%AB%98%E6%89%93%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/CEd
- 城市步行友好中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E9%AB%98%E6%89%93%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/901=hhf
- 家庭健康科普的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E9%AB%98%E6%89%93%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/tza=769
- 城市公共空间的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E9%AB%98%E6%89%93%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/K5R=t6A
- 公共服务预约的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E6%9C%80%E9%AB%98_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/017
- 乡村教育资源的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E6%9C%80%E9%AB%98_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/tfu
- 城市水环境观察的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E6%9C%80%E9%AB%98_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/Vl8
- 数字创作工具的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E6%9C%80%E9%AB%98_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/023=hoo
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E6%9C%80%E9%AB%98_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/qff=821
- 便民维修服务的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E6%9C%80%E9%AB%98_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/1lF=obL
- 垃圾分类指导的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/187
- 个人时间管理的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/tgr
- 社区文化传播的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/HGe
- 日常摄影记录的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/604=ahz
- 公共图书馆服务的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/wji=761
- 社区养老服务的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/bZG=OMp
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E6%B3%95_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/686
- 健康信息获取的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E6%B3%95_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/fnz
- 乡村公共文化的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E6%B3%95_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/vjz
- 文化讲座服务的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E6%B3%95_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/282=rwm
- 社区文化节活动的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E6%B3%95_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/tmk=467
- 公共交通信息服务从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E6%B3%95_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/07Y=z4B
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/766
- 青少年心理健康的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/qsc
- 家庭急救准备的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/Qjj
- 绿色快递包装的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/469=lic
- 公共服务数字化的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/wau=450
- 公园休闲体验的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/sGf=XXB
- 全民健身活动的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%80%E4%B9%B0%E5%B0%B1%E8%BE%93_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/603
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%80%E4%B9%B0%E5%B0%B1%E8%BE%93_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/acd
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%80%E4%B9%B0%E5%B0%B1%E8%BE%93_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/dMg
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%80%E4%B9%B0%E5%B0%B1%E8%BE%93_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/784=dgf
- 城市农夫市集的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%80%E4%B9%B0%E5%B0%B1%E8%BE%93_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/dkj=502
- 城市公共座椅的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%80%E4%B9%B0%E5%B0%B1%E8%BE%93_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/cmf=t1m
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%93%AA%E4%B8%AA%E6%A6%82%E7%8E%87%E9%AB%98_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/190
- 家庭健康科普的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%93%AA%E4%B8%AA%E6%A6%82%E7%8E%87%E9%AB%98_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/nsi
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%93%AA%E4%B8%AA%E6%A6%82%E7%8E%87%E9%AB%98_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/EO3
- 急救知识普及的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%93%AA%E4%B8%AA%E6%A6%82%E7%8E%87%E9%AB%98_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/005=jug
- 地方旅游导览的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%93%AA%E4%B8%AA%E6%A6%82%E7%8E%87%E9%AB%98_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/ksg=684
- 城市公共饮水的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%93%AA%E4%B8%AA%E6%A6%82%E7%8E%87%E9%AB%98_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/wNo=qRu
- 社区养老服务的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E7%95%85%E6%B8%B8?/564
- 邻里共享空间的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E7%95%85%E6%B8%B8?/mut
- 社区儿童活动的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E7%95%85%E6%B8%B8?/BPc
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E7%95%85%E6%B8%B8?/349=jpw
- 便民服务地图的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E7%95%85%E6%B8%B8?/xda=058
- 气象科普传播的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E7%95%85%E6%B8%B8?/Z14=msU
- 志愿服务平台的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/515
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/knb
- 公共服务数字化的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/x5C
- 社区科普课堂的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/820=noj
- 城市地名文化的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/kvq=237
- 应急物资管理的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/FAp=y3L
- 图书借阅体验的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E7%94%A8%E6%A6%82%E7%8E%87%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/302
- 开放式学习空间的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E7%94%A8%E6%A6%82%E7%8E%87%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/utl
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E7%94%A8%E6%A6%82%E7%8E%87%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/Kd3
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E7%94%A8%E6%A6%82%E7%8E%87%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/456=xcm
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E7%94%A8%E6%A6%82%E7%8E%87%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/cuk=387
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E7%94%A8%E6%A6%82%E7%8E%87%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/Dja=4F5
- 家庭安全提示的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/804
- 职业技能学习的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/pbp
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/A3A
- 乡村阅读活动的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/768=taf
- 光伏知识科普的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/hgx=340
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/Bi4=K0l
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/246
- 城乡交流活动的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/xjm
- 社区绿色空间的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/cM0
- 老年人出行服务的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/467=izm
- 健康信息获取的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/uji=264
- 乡村文化活动的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/XKN=r08
- 街道综合服务的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/962
- 街区更新实践的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/uvz
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/4BC
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/513=uqo
- 青少年编程学习的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/ryo=188
- 数字阅读服务的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/hmM=R3v
- 绿色消费选择的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E4%B8%93%E9%A2%98?/828
- 社区活动策划的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E4%B8%93%E9%A2%98?/ieu
- 城市噪声观察的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E4%B8%93%E9%A2%98?/QbA
- 社区共享书架的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E4%B8%93%E9%A2%98?/715=xgx
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E4%B8%93%E9%A2%98?/lyq=581
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E4%B8%93%E9%A2%98?/2Sl=Gef
- 农产品消费体验的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/862
- 城市农夫市集的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/rpv
- 校园社团活动的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/UGL
- 街区绿化养护的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/290=vtk
- 儿童友好空间的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/kai=925
- 数字生活课堂的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/9Zc=dhE
- 公共空间安全的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/032
- 家庭运动计划的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/yid

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
