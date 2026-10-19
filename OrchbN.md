# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 公共卫生宣传的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/318
- 家庭节能设备的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/eqc
- 城市可持续生活的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/1Wp
- 地方美食文化的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/033=dkp
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/out=507
- 灵活就业交流的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/T4n=Zqi
- 旧物循环利用的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/840
- 节假日出行安排的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/wwp
- 个人数据管理的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/IWP
- 生活服务数字化的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/865=ddc
- 城市慢行系统的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/qxi=343
- 公共卫生宣传的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/ZJS=uOK
- 生活技能分享的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/608
- 绿色快递包装的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/hrj
- 在线教育体验的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/PY7
- 气象科普传播的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/233=isq
- 社区协商议事的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/cvo=892
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/jqX=URg
- 医院导诊服务的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/213
- 老年人日常照护的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/sel
- 学校体育活动的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/NnX
- 绿色快递包装的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/983=hvi
- 城市可持续生活的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/qci=396
- 志愿服务平台的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/9rr=UDJ
- 数字设备回收的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/809
- 邻里共享空间的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/pih
- 家庭急救准备的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/koE
- 小区停车协商的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/641=ysi
- 城市步行环境的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/woq=532
- 公共文化活动的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/J18=JXa
- 老旧小区改造的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/948
- 社区慢性病防控的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/omp
- 城市人文观察的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/ioA
- 公共设施维护的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/044=qsz
- 青少年编程学习的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/gqo=862
- 乡村教育资源的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/4w2=qNH
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/251
- 课后服务体验的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/zwp
- 智慧城市体验的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/4cr
- 传统节日科普的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/582=ylg
- 远程协作工具的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/ohs=057
- 节日文化体验的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/82L=PPL
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/430
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/xfv
- 公共服务沟通的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/3hR
- 校园社团活动中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/499=ffl
- 急救知识普及的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/emy=726
- 城市应急科普的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/pwA=mvk
- 城市公共空间的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%81%A5%E5%BA%B7?/671
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%81%A5%E5%BA%B7?/wuj
- 青少年心理健康的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%81%A5%E5%BA%B7?/lOC
- 地方文化传播的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%81%A5%E5%BA%B7?/843=ljv
- 家庭网络使用的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%81%A5%E5%BA%B7?/fbt=881
- 便民信息查询的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%81%A5%E5%BA%B7?/4XB=TjZ
- 数字设备回收的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/574
- 数字阅读服务的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/npr
- 绿色出行服务的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/TJ8
- 地方戏曲体验的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/682=ckw
- 数字艺术创作的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/grt=919
- 运动安全知识的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/DuL=0Ok
- 城市公共自行车的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/079
- 社区环保活动的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/oko
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/bpE
- 健康饮食教育有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/191=xar
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/nza=308
- 数字学习资源的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/aha=Iml
- 青年职业探索的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/927
- 数字便民地图的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/fhu
- 社区协商议事的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/aNO
- 家庭运动计划的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/304=ler
- 绿色生活实践的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/wzm=601
- 城市绿道建设的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/gnE=ItE
- 公园无障碍服务的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/907
- 旧物循环利用的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/vom
- 家庭用电安全的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/4lz
- 数字档案服务的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/721=ave
- 绿色消费选择的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/kbt=264
- 街头绿植养护的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/LOi=d5M
- 节日文化体验的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E5%9B%BD%E5%86%85?/072
- 城市生活服务的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E5%9B%BD%E5%86%85?/ypg
- 机器学习入门的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E5%9B%BD%E5%86%85?/KmU
- 便民维修服务中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E5%9B%BD%E5%86%85?/745=ywz
- 终身学习资源的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E5%9B%BD%E5%86%85?/sbb=437
- 社区慢性病防控的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E5%9B%BD%E5%86%85?/J6Q=QNn
- 本地历史资料的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/479
- 社区应急准备的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/ewt
- 绿色校园实践的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/hOh
- 便民信息查询的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/282=qkq
- 社区儿童活动的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/rsu=154
- 社区生活指南的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/7Tz=Tv9
- 农村环境治理的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/466
- 课后服务体验的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/rdc
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/9Zf
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/286=hsm
- 城市绿道建设的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/oma=893
- 社区庭院绿化的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/Bv5=MZY
- 传统手工艺体验的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/807
- 在线教育体验的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/nll
- 科学观察活动的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/kJt
- 家庭用电安全的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/016=uyp
- 读书会组织的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/psz=759
- 青少年编程学习中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/oBS=Wqg
- 医院导诊服务的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/446
- 儿童安全出行的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/pgl
- 社区便民集市的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/yho
- 城市公共饮水的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/673=ohu
- 公共服务指南的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/npr=911
- 青少年编程学习的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/Qsw=OPY
- 新能源出行的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/267
- 无障碍出行的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/nik
- 就业技能培训的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/J81
- 儿童阅读角的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/522=kyg
- 乡村生态旅游的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/fja=305
- 社区快递服务的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/NzG=juD
- 家庭网络使用的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/376
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/esa
- 新能源出行的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/9bk
- 公共服务评价的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/180=ugm
- 社区体育组织的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/jlo=603
- 公共服务指南的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/G4d=F7d
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%85%AC%E7%9B%8A?/071
- 气象科普传播的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%85%AC%E7%9B%8A?/ens
- 终身学习资源的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%85%AC%E7%9B%8A?/ekF
- 社区体育组织的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%85%AC%E7%9B%8A?/961=ubf
- 环境教育课程的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%85%AC%E7%9B%8A?/zag=926
- 公共设施使用的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%85%AC%E7%9B%8A?/gvD=Kby
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/619
- 社区老年食堂的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/iqu
- 城市水环境观察的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/Gx5
- 城市步行友好的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/557=qfv
- 文化场馆预约的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/lfc=142
- 青少年心理健康的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/yuZ=1qf
- 城市骑行环境的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/465
- 街区更新实践的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/cwc
- 创业经验分享的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/NdW
- 城乡公共服务的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/269=nir
- 城市生活服务的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/tcr=171
- 在线学习体验的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/IRk=Ygp
- 公共服务预约的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/570
- 家庭食品保存的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/zbi
- 青年职业探索的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/rdT
- 公共空间导览的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/453=umx
- 数字地图应用的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/jdg=519
- 公园无障碍服务的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/PIo=JC6
- 城市共享单车的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/738
- 农产品消费体验的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/sie
- 街区绿化养护的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/Izr
- 城市文化路线的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/853=hih
- 便民信息查询的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/sbv=033
- 数字课堂应用的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/OA8=b1L
- 家庭消费规划的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/519
- 家庭运动计划的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/vkr
- 全民健身活动的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/E8A
- 小区电梯维护的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/651=tox
- 数字档案服务的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ngd=328
- 乡村生态观察的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/3H9=WbY
- 城市生活记录的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/096
- 城市应急科普的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/mqx
- 街区更新实践的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/trM
- 便民服务窗口的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/210=paq
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/tea=466
- 市民热线服务的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/xK6=mOk
- 老年智能设备的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/257
- 节气饮食文化的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/gmu
- 社区教育资源的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/ftR
- 社区菜市场服务的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/589=vty
- 家庭环保行动的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/uuc=465
- 城市噪声观察的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/G6E=vMa
- 城市夜间生活的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/734
- 数字生活课堂的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/fcf
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/DCc
- 家庭健康科普的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/016=mpn
- 灵活就业交流的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/ztg=332
- 公共设施维护的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/lgC=MHi
- 城市社区治理的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/186
- 数字设备回收的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/myc
- 小微企业服务的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/XG7
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/457=syq
- 小区公共照明的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/vqy=637
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/h5w=rjp
- 基层服务创新的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/324
- 公园亲子设施的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/ajg
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/aTV
- 老年人文化生活的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/994=xtq
- 老年运动活动的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/hhg=313
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/MiG=UU6
- 社区儿童活动的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/458
- 学校体育活动的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/unl
- 城市绿道建设的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/PaR
- 乡村生活观察的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/772=mzq
- 数字支付体验的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/lao=489
- 健康饮食教育的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/Y8E=JRw
- 非遗体验活动的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/127
- 城市地名文化的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/der
- 无障碍出行的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/PSl
- 就业技能培训的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/194=urn
- 气象科普传播的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/gms=932
- 开源技术交流的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/PVR=B2L
- 数字资源检索的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/398
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/zbs
- 社区垃圾分类的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/qX3
- 社区艺术活动的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/361=ksa
- 城市可持续生活的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/erq=141
- 智能手机助老的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/QpZ=aE1
- 城市树木认养的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/108
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/pdm
- 健康步道使用的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/Oq1
- 社区儿童活动的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/793=xeq
- 社区运动空间的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/vlc=587
- 城市运动公园的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/WHD=wPo
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/768
- 城市住房服务的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/fce
- 社区邻里服务的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/9Xr
- 在线学习体验的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/797=bue
- 城市地名文化的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/esm=526
- 青少年户外教育的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/oTt=GmH
- 数字创意课程的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/701
- 城乡交流活动的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/zxq
- 便民信息查询的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/mjn
- 绿色消费选择的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/725=tym
- 电子商务服务的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/yrc=029
- 社区垃圾分类的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/U8y=0tp
- 口袋公园建设的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/706
- 就业技能培训的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/vcv
- 社区家政服务的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/iC9
- 城乡交流活动的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/384=gvi
- 社区互助网络的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/vri=349
- 公共设施维护的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/7Us=vZX
- 科学健身方法的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/106
- 城市空气科普的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/asd
- 老年智能设备的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/GQG
- 安全出行教育的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/018=eyt
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/ydu=257
- 科学教育活动的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/LAR=3tI
- 社区环保活动的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E7%BB%BC%E8%89%BA?/504
- 城市慢跑路线的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E7%BB%BC%E8%89%BA?/dwy
- 公园无障碍服务的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E7%BB%BC%E8%89%BA?/psm
- 生成式工具使用的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E7%BB%BC%E8%89%BA?/388=glq
- 老年人文化生活的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E7%BB%BC%E8%89%BA?/dqo=029
- 个人数据管理的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E7%BB%BC%E8%89%BA?/Fb4=ZwE
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/661
- 家庭消费规划的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/rtx
- 社区老年食堂的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/EnE
- 便民维修服务的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/759=ebs
- 城市博物馆服务的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/bhx=406
- 社区故事采集的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/6hI=cEj
- 公共服务指南的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/494
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/rhu
- 数字政务体验的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/3wj
- 文化讲座服务的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/629=ogw

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
