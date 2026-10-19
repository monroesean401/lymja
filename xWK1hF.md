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

- 社区艺术活动中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_999%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/I3b
- 骑行路线规划的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_999%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/394=bac
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_999%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/ene=947
- 青少年科技社团的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_999%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/Wl7=BFJ
- 智能手机助老的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/757
- 家庭食品保存的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/xcu
- 城市水环境观察的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/5HS
- 劳动教育实践的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/500=psx
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/wiy=398
- 城市骑行环境的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/lZh=wsn
- 社区托育服务的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/930
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/eqh
- 城市基础设施的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/NBd
- 环境教育课程的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/469=puv
- 家庭消费规划的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/oio=905
- 开源技术交流的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/yhL=Kb5
- 公交无障碍服务的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8999.com_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/365
- 旧物循环利用的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8999.com_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/jvc
- 儿童友好空间的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8999.com_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/9I7
- 社区宠物管理的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8999.com_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/625=vrb
- 旧物循环利用中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8999.com_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/fte=596
- 城市生活服务的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8999.com_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/eDB=ayi
- 街区更新实践的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_999%E5%BD%A9%E7%A5%A8-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/688
- 公共场所导视的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_999%E5%BD%A9%E7%A5%A8-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/qgr
- 家庭安全提示的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_999%E5%BD%A9%E7%A5%A8-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/9PH
- 家庭节能实践的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_999%E5%BD%A9%E7%A5%A8-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/718=rkb
- 社区文化传播的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_999%E5%BD%A9%E7%A5%A8-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/vxz=704
- 公共空间安全的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_999%E5%BD%A9%E7%A5%A8-%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/XKW=pbv
- 居家适老化改造的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_999%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/010
- 社区共享书架的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_999%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/hji
- 数字素养提升的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_999%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/RpO
- 市民热线服务的参与方式与路径 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_999%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/781=rhu
- 文明养宠科普的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_999%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/ckd=817
- 公共服务指南的便民做法梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_999%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/qil=qP6
- 城市基础设施的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_999%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/453
- 便民服务地图的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_999%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/dpx
- 乡村教育资源中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_999%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/IAG
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_999%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/339=dux
- 社区文化传播中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_999%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/qbr=953
- 乡村文化空间的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_999%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/GsH=GnF
- 公共服务预约的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/907
- 口袋公园建设中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/mut
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/MeF
- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/831=vkd
- 城市便民驿站的入门知识整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/fca=004
- 城市文化路线的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/JJ0=D45
- 社区商业活力的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/289
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/djr
- 城乡交通衔接的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/ltQ
- 文化场馆预约的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/834=ejx
- 家庭安全提示的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/djj=713
- 城市骑行环境的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/fur=Wox
- 乡村电商实践的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/398
- 青少年科技社团的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/tup
- 家庭健康科普的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/RLo
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/598=uxm
- 社区法律科普的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/vff=035
- 老旧小区改造的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/mUZ=wtl
- 社会体育指导的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8~%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/306
- 安全出行教育的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8~%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/ugu
- 社区志愿服务的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8~%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/qQR
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8~%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/204=ytv
- 家庭科学教育的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8~%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/bms=984
- 个人数据管理的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8~%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/Gtz=owK
- 乡村生态观察的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/305
- 绿色消费选择中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/gzv
- 健康饮食教育的基础设施观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/WTl
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/808=eeg
- 城市社区治理的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/drx=059
- 公共服务预约的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/rH6=ExL
- 青年志愿活动的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_tt%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/961
- 乡村生态观察的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_tt%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/tgu
- 传统手工艺体验的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_tt%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/xWK
- 老旧小区改造的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_tt%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/246=usj
- 城市公共厕所的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_tt%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/jxx=524
- 城市公共艺术的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_tt%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/rFL=0ST
- 节约用水实践的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_t%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/763
- 城乡公共服务中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_t%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/cap
- 公共设施使用的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_t%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/aFl
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_t%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/268=dcm
- 城市共享单车的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_t%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/xlq=463
- 社区生活指南的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_t%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/oXA=LUh
- 电动汽车充电的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_tt%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/630
- 社区交通安全的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_tt%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/ura
- 街道综合服务的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_tt%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/XnW
- 社区休闲设施的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_tt%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/622=zjv
- 公共场所导视的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_tt%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/nwv=773
- 本地旅行体验的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_tt%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/Cr9=vZV
- 节假日出行安排的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_tt%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/738
- 城市博物馆活动的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_tt%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/ogy
- 城市雨天出行的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_tt%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/nuW
- 科学睡眠习惯的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_tt%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/251=twt
- 城市夜间生活的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_tt%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/iio=535
- 消防知识宣传的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_tt%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/XpM=Xjh
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/707
- 气象科普传播的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/oza
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/wRe
- 节约用水实践的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/538=rfs
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/dtf=467
- 社区绿色空间的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/mLM=btm
- 社会体育指导的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/372
- 信息无障碍体验的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/bac
- 城市便民驿站的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/OZB
- 城市水环境观察的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/930=knr
- 学校体育活动的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/llj=248
- 电子商务服务的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/gfR=v8t
- 社区知识分享的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/620
- 农业科普体验的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/dho
- 非遗课堂体验的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/EQ4
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/163=iic
- 公共交通信息服务的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/czw=533
- 社区便民集市的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/ayR=b0E
- 公益活动组织的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%AC%A2%E8%BF%8E%E6%82%A8%E4%BD%93%E9%AA%8C_%E8%B4%A2%E7%BB%8F%E4%B8%93%E9%A2%98?/170
- 社区消防演练的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%AC%A2%E8%BF%8E%E6%82%A8%E4%BD%93%E9%AA%8C_%E8%B4%A2%E7%BB%8F%E4%B8%93%E9%A2%98?/kcr
- 课后服务体验的设施维护观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%AC%A2%E8%BF%8E%E6%82%A8%E4%BD%93%E9%AA%8C_%E8%B4%A2%E7%BB%8F%E4%B8%93%E9%A2%98?/GwC
- 数字艺术创作的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%AC%A2%E8%BF%8E%E6%82%A8%E4%BD%93%E9%AA%8C_%E8%B4%A2%E7%BB%8F%E4%B8%93%E9%A2%98?/135=uxt
- 农业科普体验的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%AC%A2%E8%BF%8E%E6%82%A8%E4%BD%93%E9%AA%8C_%E8%B4%A2%E7%BB%8F%E4%B8%93%E9%A2%98?/xou=613
- 城市生活服务的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%AC%A2%E8%BF%8E%E6%82%A8%E4%BD%93%E9%AA%8C_%E8%B4%A2%E7%BB%8F%E4%B8%93%E9%A2%98?/iTJ=k0Y
- 社区便利生活的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%912.6.0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/777
- 公园休闲体验中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%912.6.0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/ugy
- 环境教育课程的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%912.6.0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/zdM
- 便民服务窗口的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%912.6.0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/704=wyp
- 城市文明出行的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%912.6.0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/hpu=632
- 开源技术交流的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%912.6.0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/MTV=kQv
- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/150
- 城市地名文化的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/nqa
- 地方旅游导览中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/2M0
- 物业服务沟通的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/769=qlp
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/mrk=302
- 社区科普课堂的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/qqz=SE5
- 文明养宠科普中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/698
- 城市噪声观察的实用信息清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/ikc
- 健康饮食教育的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/DQy
- 城市农夫市集的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/910=aps
- 个人数据管理的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/vla=712
- 社区艺术活动的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/YZX=osk
- 城市人文观察的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/484
- 公园无障碍服务的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/bzf
- 节能生活方式的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/B2v
- 社区应急准备的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/725=ldy
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/ctq=902
- 便民维修服务的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/JJO=Vem
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/598
- 农产品消费体验的家庭实践清单 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/mwn
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/Hto
- 图书借阅体验的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/524=nsc
- 绿色生活实践的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/xtj=191
- 社区体育组织的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/ABh=Aio
- 社区家政服务的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_360%E4%BA%B2%E5%AD%90?/369
- 社区协商议事的活动体验回顾 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_360%E4%BA%B2%E5%AD%90?/ulh
- 信息无障碍体验的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_360%E4%BA%B2%E5%AD%90?/fbB
- 社区设施共享的便利性观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_360%E4%BA%B2%E5%AD%90?/514=knr
- 运动安全知识的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_360%E4%BA%B2%E5%AD%90?/czb=918
- 运动安全知识的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_360%E4%BA%B2%E5%AD%90?/8da=uRu
- 家庭安全提示的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E6%90%9C%E7%8B%97%E5%9B%BD%E9%99%85?/309
- 社区活动策划的服务信息整理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E6%90%9C%E7%8B%97%E5%9B%BD%E9%99%85?/bht
- 健康信息获取的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E6%90%9C%E7%8B%97%E5%9B%BD%E9%99%85?/0Kd
- 节约用水实践的家庭参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E6%90%9C%E7%8B%97%E5%9B%BD%E9%99%85?/954=rfj
- 数字阅读服务的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E6%90%9C%E7%8B%97%E5%9B%BD%E9%99%85?/eul=154
- 社区家校合作的执行流程参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E6%90%9C%E7%8B%97%E5%9B%BD%E9%99%85?/fTY=xFJ
- 公益活动组织的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%A7%91%E6%8A%80?/995
- 生活技能分享的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%A7%91%E6%8A%80?/qsj
- 绿色生活实践中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%A7%91%E6%8A%80?/YGQ
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%A7%91%E6%8A%80?/046=jgv
- 全民阅读推广的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%A7%91%E6%8A%80?/ikb=573
- 社区阅读服务的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%A7%91%E6%8A%80?/vBy=BEn
- 绿色办公实践的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/008
- 城市文化路线的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/xvi
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/RvT
- 城市夜间照明的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/692=baq
- 社区协商议事的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/gym=647
- 城市公共标识的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/GIk=OTg
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/705
- 城市农夫市集的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/sga
- 公共文化活动的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/Ljh
- 节假日出行安排的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/881=nyo
- 社区老年食堂的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/qhy=532
- 农村环境治理的社区参与观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/PNQ=SXw
- 家庭健康科普的日常使用指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E4%B8%AA%E4%BA%BA%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/524
- 户外活动组织的活动策划思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E4%B8%AA%E4%BA%BA%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/lun
- 城乡公共服务的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E4%B8%AA%E4%BA%BA%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/6mF
- 远程协作工具的空间使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E4%B8%AA%E4%BA%BA%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/066=lgd
- 家庭安全提示的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E4%B8%AA%E4%BA%BA%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/gcb=343
- 街区道路维护的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E4%B8%AA%E4%BA%BA%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/KC9=Hhv
- 乡村文化活动的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/457
- 医院导诊服务有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/yrm
- 社区知识分享的数字化应用观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/1I3
- 城市博物馆活动的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/809=hxh
- 社区商业活力的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/ryz=573
- 社区应急准备的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/EmV=kyo
- 社区读书角建设的服务质量观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%89%8D%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%9C%9F%E6%AD%A3%E8%A7%84%E8%8C%83%E3%80%81%E5%AE%89%E5%85%A8%E5%8F%AF%E9%9D%A0_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/607
- 公共服务数字化的服务细节记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%89%8D%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%9C%9F%E6%AD%A3%E8%A7%84%E8%8C%83%E3%80%81%E5%AE%89%E5%85%A8%E5%8F%AF%E9%9D%A0_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/zcb
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%89%8D%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%9C%9F%E6%AD%A3%E8%A7%84%E8%8C%83%E3%80%81%E5%AE%89%E5%85%A8%E5%8F%AF%E9%9D%A0_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/mWU
- 家庭环保习惯的公共参与指南 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%89%8D%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%9C%9F%E6%AD%A3%E8%A7%84%E8%8C%83%E3%80%81%E5%AE%89%E5%85%A8%E5%8F%AF%E9%9D%A0_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/048=vgy
- 农村环境治理的数字工具使用体验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%89%8D%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%9C%9F%E6%AD%A3%E8%A7%84%E8%8C%83%E3%80%81%E5%AE%89%E5%85%A8%E5%8F%AF%E9%9D%A0_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/caz=607
- 社区养老服务的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%89%8D%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%9C%9F%E6%AD%A3%E8%A7%84%E8%8C%83%E3%80%81%E5%AE%89%E5%85%A8%E5%8F%AF%E9%9D%A0_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/PmJ=foW
- 公共文化活动的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BE%E7%89%87_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/873
- 老旧小区改造的常见问题梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BE%E7%89%87_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/oeb
- 家庭消费规划的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BE%E7%89%87_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/LG9
- 亲子阅读活动的服务体验观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BE%E7%89%87_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/497=inn
- 公共空间照明的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BE%E7%89%87_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/zge=748
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BE%E7%89%87_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/Wxb=dDn
- 数字支付体验的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB_%E5%87%A4%E5%87%B0%E6%97%B6%E5%B0%9A?/594
- 电动汽车充电的绿色实践方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB_%E5%87%A4%E5%87%B0%E6%97%B6%E5%B0%9A?/pua
- 日常摄影记录中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB_%E5%87%A4%E5%87%B0%E6%97%B6%E5%B0%9A?/0wU
- 青少年科普实践的长期维护要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB_%E5%87%A4%E5%87%B0%E6%97%B6%E5%B0%9A?/595=lid
- 健康饮水科普的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB_%E5%87%A4%E5%87%B0%E6%97%B6%E5%B0%9A?/avq=630
- 科学观察活动的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB_%E5%87%A4%E5%87%B0%E6%97%B6%E5%B0%9A?/Lcy=iMb
- 社会体育指导的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/581
- 消防知识宣传的适老服务细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/qet
- 青年志愿活动的线下体验记录 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/So5
- 城市慢行系统的日常记录与分享 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/914=bas
- 社区活动空间的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/ohi=330
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/1ot=60V
- 图书借阅体验的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/944
- 家庭用电安全中的几个关键细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/ula
- 城市骑行环境的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/jl7
- 健康饮水科普的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/700=gym
- 社区活动空间的基础知识问答 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/gxe=943
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/Kkv=t2S
- 校园节能行动的组织方法与经验 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/694
- 社区养老服务的社区行动案例 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/fsg
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/lKe
- 文化讲座服务的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/666=swf
- 节日文化体验的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/cgc=724
- 劳动教育实践的服务范围梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/2Gl=0DE
- 亲子科普活动的便捷程度观察 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/471
- 社区邻里服务的居民参与机会 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/omy
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/5Na
- 社区应急准备的空间设计要点 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/764=cro
- 数字生活课堂的常见误区提醒 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/mri=236
- 校园安全教育的阅读与学习资源 |来源：https://github.com/fowlerdavid3/znnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/39L=VS3
- 数字创意课程的协商参与方式 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%ABwelcome_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/262
- 城市公共自行车的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%ABwelcome_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/tut
- 街道综合服务的持续改进方向 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%ABwelcome_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/p3l
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%ABwelcome_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/431=jji
- 数字设备回收的行动步骤参考 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%ABwelcome_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/pfl=776
- 环境监测科普的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%ABwelcome_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/scT=eGc
- 城乡交流活动的协作机制梳理 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/963
- 科普展览体验的日常管理方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/sgk
- 本地历史资料的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/2iF
- 社区应急准备的实际需求与回应 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/632=dqk
- 社区故事采集的资源整合思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/pkz=929
- 社区文化节活动的流程优化思路 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/7cH=OqN
- 城市社区治理的资源利用方法 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85-%E5%85%8D%E8%B4%B9%E6%8A%80%E5%B7%A7%2C2%E6%9C%9F%E5%BF%85%E4%B8%AD%2C%E8%BD%BB%E6%9D%BE%E4%B8%8A%E5%B2%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/225
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85-%E5%85%8D%E8%B4%B9%E6%8A%80%E5%B7%A7%2C2%E6%9C%9F%E5%BF%85%E4%B8%AD%2C%E8%BD%BB%E6%9D%BE%E4%B8%8A%E5%B2%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/dlv
- 儿童阅读角的活动组织技巧 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85-%E5%85%8D%E8%B4%B9%E6%8A%80%E5%B7%A7%2C2%E6%9C%9F%E5%BF%85%E4%B8%AD%2C%E8%BD%BB%E6%9D%BE%E4%B8%8A%E5%B2%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/Cx2
- 城市文明出行的安全使用提示 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85-%E5%85%8D%E8%B4%B9%E6%8A%80%E5%B7%A7%2C2%E6%9C%9F%E5%BF%85%E4%B8%AD%2C%E8%BD%BB%E6%9D%BE%E4%B8%8A%E5%B2%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/738=rhm
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85-%E5%85%8D%E8%B4%B9%E6%8A%80%E5%B7%A7%2C2%E6%9C%9F%E5%BF%85%E4%B8%AD%2C%E8%BD%BB%E6%9D%BE%E4%B8%8A%E5%B2%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/ivo=192
- 在线教育体验中的沟通与协作 |来源：https://github.com/fowlerdavid3/znnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85-%E5%85%8D%E8%B4%B9%E6%8A%80%E5%B7%A7%2C2%E6%9C%9F%E5%BF%85%E4%B8%AD%2C%E8%BD%BB%E6%9D%BE%E4%B8%8A%E5%B2%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/zhk=E39

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
