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

- 地方旅游导览的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/vax=464
- 食品安全科普的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/9TM=L9m
- 公共空间安全的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/476
- 农业科普体验的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/ykb
- 城市绿道建设的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/j9I
- 居民健康教育的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/086=xpi
- 志愿服务平台的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/wze=659
- 安全出行教育的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/jEy=xH9
- 远程协作工具的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/997
- 学校体育活动的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/skz
- 节气饮食文化有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/bAY
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/847=xmw
- 街区更新实践的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/kst=704
- 线上办事服务的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/0A9=tmK
- 校园安全教育的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/960
- 数字生活课堂的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/jvl
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/Iv1
- 灵活就业交流的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/094=sey
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/wlw=175
- 家庭运动计划的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/Tc6=yqr
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/489
- 光伏知识科普的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/cup
- 城市步行友好的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/6Eb
- 居家防滑改造的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/146=xoo
- 城市绿色交通的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/fvs=852
- 数字支付体验的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/BnI=fM9
- 社区邻里服务的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/429
- 零废弃生活尝试的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/dib
- 青少年户外教育的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/ADi
- 家庭环保行动的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/341=mqj
- 小区电梯维护的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/pho=216
- 便民服务地图的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/oRU=Eo0
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/419
- 社区慢性病防控的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/vsk
- 在线教育体验的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/KHp
- 公共空间导览的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/898=ipx
- 科学健身方法的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/zhu=823
- 乡村阅读活动的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/CXT=FUn
- 乡村公共服务的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/842
- 公共空间照明的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/kze
- 城市雨天出行的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/KYR
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/956=pzz
- 邻里互助活动的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/qpd=958
- 便民维修服务的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/3H9=Q6f
- 图书馆活动策划的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/573
- 社区体育组织的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/zoy
- 邻里互助活动的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/d0Q
- 开放式学习空间的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/682=hhs
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/vfk=574
- 数字便民地图的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/j9Q=z35
- 社区防暑服务的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/976
- 家庭食品保存的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/xtd
- 社区文化传播从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/YgQ
- 城市慢行系统的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/959=tjq
- 家庭志愿活动的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/aaa=255
- 社区停车服务的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/WcI=vnk
- 乡村公共服务的基础设施观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/705
- 社区环保活动的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/lbw
- 城市人文观察的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/Fgk
- 数字素养提升的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/859=puh
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/kjz=582
- 网络安全教育的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/4t8=YIZ
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/124
- 人工智能科普的入门知识整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/ljg
- 农业科普体验的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/NiQ
- 社区手工活动的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/775=lyl
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/fwf=392
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/4eg=6nJ
- 城市适老服务中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/125
- 家庭运动计划的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/izs
- 社区读书角建设的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/ZdE
- 零废弃生活尝试的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/098=ncx
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/gqp=013
- 科普展览体验的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/igG=NPS
- 绿色生活实践的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/818
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/bua
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/Nsd
- 公交站点体验的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/229=mze
- 邻里共享空间的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/zpx=541
- 城市休闲步道的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/iGX=wVQ
- 食品安全科普的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/992
- 药品使用科普的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/hmv
- 公共空间休憩的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/iUL
- 青少年科技社团的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/276=cxo
- 周末休闲规划的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/ydb=561
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/GbK=evX
- 科学观察活动的协作机制梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/619
- 非遗体验活动的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/wlp
- 老年人出行服务的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/KE4
- 绿色办公实践的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/857=xro
- 在线学习体验的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/zzv=839
- 学校体育活动的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/x96=uXq
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%B8%AF%E8%82%A1?/650
- 口袋公园建设的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%B8%AF%E8%82%A1?/jfn
- 社区休闲设施的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%B8%AF%E8%82%A1?/2mR
- 社区活动空间中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%B8%AF%E8%82%A1?/230=bnf
- 小区停车协商的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%B8%AF%E8%82%A1?/ydv=395
- 线上阅读资源的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%B8%AF%E8%82%A1?/4nO=afW
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/695
- 城市宠物友好空间的基础知识问答 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/fxm
- 社区快递服务的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/UTQ
- 绿色办公实践的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/468=lxv
- 节能家电使用的日常管理方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/dfb=274
- 街区绿化养护的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/shq=y3W
- 社区设施共享的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/626
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/huv
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/Ou1
- 通勤路线规划的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/224=col
- 老年人日常照护的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/oaa=697
- 户外活动组织的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/kUL=Agy
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/971
- 新能源出行的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/lef
- 乡村教育资源的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/zPS
- 家庭环保行动的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/970=owy
- 终身学习资源的空间使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/zrn=373
- 城市噪声观察的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/K9s=Vyd
- 城市绿道建设的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/797
- 公共交通接驳的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/lif
- 青年志愿活动的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/Uch
- 公共空间照明的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/595=bpi
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/vpd=188
- 家庭安全提示的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/YRC=fMB
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/561
- 消防知识宣传的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/wgn
- 乡村产业科普的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/OSj
- 家庭环保习惯的日常使用指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/594=utb
- 乡村生活观察的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/hic=863
- 家庭网络使用的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/zhQ=ZTl
- 城市绿色交通的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/786
- 社区志愿服务的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/djs
- 社区志愿服务的资源利用方法 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/6w9
- 骑行路线规划的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/590=sta
- 公共设施维护的行动步骤参考 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/qoq=315
- 文化讲座服务的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/eDw=LPj
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/883
- 街区道路维护的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/tbz
- 公共服务沟通的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/gQu
- 乡村公共服务的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/788=acr
- 旧物循环利用的儿童友好细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/rol=368
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/7xO=9Cp
- 社区公共议事的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/597
- 家庭安全提示的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/qnr
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/on9
- 公共空间照明的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/331=apd
- 公共空间安全的持续改进方向 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/jqw=267
- 科学教育活动的资源整合思路 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/zZR=XwU
- 环境监测科普的便利性观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8F%B7%E5%A4%96?/733
- 公共文化活动的日常记录与分享 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8F%B7%E5%A4%96?/wuf
- 数字创意课程的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8F%B7%E5%A4%96?/zIU
- 城市步行环境的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8F%B7%E5%A4%96?/451=wxl
- 数字创意课程的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8F%B7%E5%A4%96?/fhb=057
- 儿童户外活动的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8F%B7%E5%A4%96?/cTX=vRt
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/867
- 公园休闲体验从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/kan
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/l7I
- 家庭志愿活动的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/855=gbu
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/jmi=661
- 文化场馆预约的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/IsK=HGP
- 社会体育指导的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/701
- 公园无障碍服务的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/jdb
- 在线教育体验的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Z7Q
- 城市步行环境的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/928=vmu
- 本地消费场景的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dbg=214
- 社区老年食堂的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gMW=Z6V
- 无障碍信息设计的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/454
- 社区阅读服务的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/bkz
- 公共场馆服务的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/mR6
- 健康步道使用的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/605=lee
- 数字资源检索的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/jam=489
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/2Pc=wfk
- 社区老年食堂的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/538
- 老年人日常照护的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/qrt
- 城市噪声观察的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/dLQ
- 地方戏曲体验的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/302=xzl
- 街头绿植养护的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/gyy=321
- 本地消费场景的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/SHq=oey
- 环境教育课程的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/062
- 本地旅行体验的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/aqx
- 城市可持续生活的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/6cs
- 儿童户外活动的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/370=wvb
- 机器人科普活动的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/wuh=774
- 城乡交通衔接的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/1aT=Qen
- 社区家政服务的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/831
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/isv
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/VT8
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/868=ucw
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/njy=553
- 乡村教育资源的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/epB=Xjx
- 青少年编程学习的家庭实践清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/955
- 城乡交流活动的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/tch
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/CHd
- 数字档案服务的活动体验回顾 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/514=njz
- 社区邻里服务的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/ixw=782
- 居民健康教育的服务体验观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/2TP=AVu
- 社区志愿服务的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/128
- 农村环境治理的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/eot
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/mfz
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/873=ibf
- 公共服务评价的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/yrv=292
- 公共健身器材的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/LRx=QLZ
- 绿色校园实践的安全使用提示 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E4%B8%8B%E8%BD%BD_360%E6%B8%B8%E6%88%8F?/999
- 创业经验分享的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E4%B8%8B%E8%BD%BD_360%E6%B8%B8%E6%88%8F?/nzs
- 节假日出行安排的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E4%B8%8B%E8%BD%BD_360%E6%B8%B8%E6%88%8F?/KLJ
- 社区法律科普的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E4%B8%8B%E8%BD%BD_360%E6%B8%B8%E6%88%8F?/166=wik
- 本地消费场景的日常实践笔记 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E4%B8%8B%E8%BD%BD_360%E6%B8%B8%E6%88%8F?/yne=265
- 社区垃圾回收的设施维护观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E4%B8%8B%E8%BD%BD_360%E6%B8%B8%E6%88%8F?/0Fd=p0F
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/348
- 乡村电商实践的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/dmi
- 绿色办公实践的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/dg7
- 生活垃圾减量的服务反馈渠道 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/830=vbu
- 家庭养老规划的家庭参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/liv=561
- 地方美食文化的组织方法与经验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/qDa=K9L
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%9F%8E%E4%BA%8B?/724
- 社区学习活动的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%9F%8E%E4%BA%8B?/wgm
- 基层健康服务的便捷程度观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%9F%8E%E4%BA%8B?/llO
- 老年智能设备的参与方式与路径 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%9F%8E%E4%BA%8B?/562=lpj
- 城市雨天出行的适老服务细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%9F%8E%E4%BA%8B?/pdd=013
- 生活服务数字化的居民参与机会 |来源：https://github.com/fryetara140/dywm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%9F%8E%E4%BA%8B?/YO0=G1L
- 在线教育体验的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%83%BD%E6%BA%90?/130
- 节日文化体验的执行流程参考 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%83%BD%E6%BA%90?/oyv
- 地方民俗记录的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%83%BD%E6%BA%90?/BOw
- 数字地图应用的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%83%BD%E6%BA%90?/884=mzi
- 运动安全知识的活动策划思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%83%BD%E6%BA%90?/wcg=414
- 城市博物馆活动的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%83%BD%E6%BA%90?/LYY=VVm
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/144
- 城市适老服务的服务细节记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/qum
- 文化遗产保护科普的服务范围梳理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/ENG
- 社区共享书架的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/243=ixv
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/rtn=763
- 乡村电商实践的数字工具使用体验 |来源：https://github.com/fryetara140/dywm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%AE%B6%E7%94%B5?/QpK=Btf
- 乡村生态旅游的长期维护要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/871
- 科技馆参观体验的空间设计要点 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/iwt
- 儿童安全出行的实用信息清单 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/2GO
- 家庭消费规划的协商参与方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/621=xqp
- 公共服务咨询的便民做法梳理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/plb=360
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/fryetara140/dywm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/XzD=B7N
- 电动汽车充电的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/904
- 家庭用电安全的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/gbd
- 环境监测科普的活动组织技巧 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/1Tv
- 课后服务体验的流程优化思路 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/144=iwg
- 乡村公共文化中的几个关键细节 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/mfb=626
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/fryetara140/dywm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/kld=rpn
- 公园休闲体验的实际需求与回应 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/840
- 社区共享书架的常见误区提醒 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/pko
- 机器人科普活动的学习资源整理 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/jyk
- 社区邻里服务的使用门槛与改进 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/795=uih
- 城乡交通衔接的社区参与观察 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/rnk=900
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/LZ6=G7W
- 数字学习资源的线下体验记录 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%AD%96%E7%95%A5%E8%B4%A2%E7%BB%8F?/030
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/fryetara140/dywm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%AD%96%E7%95%A5%E8%B4%A2%E7%BB%8F?/emz

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
