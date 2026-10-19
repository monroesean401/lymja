# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 公共空间导览中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/011
- 家庭园艺实践的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/dic
- 社区协商议事的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/J0S
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/250=ffn
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/suo=785
- 智慧停车服务的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/coj=BWp
- 社区科普课堂的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%B8%A6%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88QQ_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/072
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%B8%A6%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88QQ_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/ktg
- 城市应急科普的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%B8%A6%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88QQ_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/d39
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%B8%A6%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88QQ_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/504=jdu
- 社区宣传栏更新的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%B8%A6%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88QQ_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/bvg=009
- 老年友好服务的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%B8%A6%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88QQ_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/LQG=yei
- 校园安全教育的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/202
- 乡村公共文化的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/jzt
- 社区便民集市的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/3zP
- 气象科普传播的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/914=aoe
- 城市文化路线的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/lyp=934
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/CXy=wyk
- 家庭健康管理的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/726
- 创业经验分享的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/gvr
- 公共交通信息服务的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/Zym
- 药品使用科普的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/408=ddf
- 智慧停车服务的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/dfp=152
- 城市生活记录的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/UQm=XDa
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E8%B5%8C%E5%8D%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B7%9F%E7%9D%80%E5%AF%BC%E5%B8%88%E8%B5%B0_360%E5%86%9C%E4%B8%9A?/598
- 社区阅读服务的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E8%B5%8C%E5%8D%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B7%9F%E7%9D%80%E5%AF%BC%E5%B8%88%E8%B5%B0_360%E5%86%9C%E4%B8%9A?/llu
- 健康信息获取的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E8%B5%8C%E5%8D%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B7%9F%E7%9D%80%E5%AF%BC%E5%B8%88%E8%B5%B0_360%E5%86%9C%E4%B8%9A?/IrP
- 公园休闲体验的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E8%B5%8C%E5%8D%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B7%9F%E7%9D%80%E5%AF%BC%E5%B8%88%E8%B5%B0_360%E5%86%9C%E4%B8%9A?/960=rzn
- 健康饮水科普的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E8%B5%8C%E5%8D%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B7%9F%E7%9D%80%E5%AF%BC%E5%B8%88%E8%B5%B0_360%E5%86%9C%E4%B8%9A?/vhl=755
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E8%B5%8C%E5%8D%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B7%9F%E7%9D%80%E5%AF%BC%E5%B8%88%E8%B5%B0_360%E5%86%9C%E4%B8%9A?/DG1=AIi
- 城市地名文化的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%85%AC%E5%91%8A?/387
- 开放式学习空间的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%85%AC%E5%91%8A?/btt
- 城市人文观察的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%85%AC%E5%91%8A?/Fn0
- 音乐欣赏活动的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%85%AC%E5%91%8A?/909=uzx
- 社区防暑服务的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%85%AC%E5%91%8A?/gya=281
- 老年人日常照护的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%85%AC%E5%91%8A?/QTn=YvZ
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E7%9B%88%E5%88%A9_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/815
- 城市公共厕所的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E7%9B%88%E5%88%A9_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/yaz
- 绿色出行服务的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E7%9B%88%E5%88%A9_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/dMK
- 社区公共议事的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E7%9B%88%E5%88%A9_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/884=nts
- 急救知识普及的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E7%9B%88%E5%88%A9_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/wdw=205
- 绿色生活实践的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E7%9B%88%E5%88%A9_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/Qh1=mQx
- 社区共享书架的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/695
- 社区故事采集的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/xzd
- 社区便利生活的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/DEp
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/179=prx
- 线上办事服务的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/hvz=307
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/KgU=gB3
- 家庭志愿活动的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/814
- 社区艺术活动中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/kyk
- 应急物资管理的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/bpd
- 公共服务数字化的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/090=dmy
- 亲子科普活动的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/xol=566
- 节日文化体验的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/XFB=02Y
- 地方美食文化的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/502
- 街道综合服务的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/pxe
- 乡村生活观察的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/2Kl
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/842=cqz
- 非遗体验活动的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/upb=534
- 儿童阅读角的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/p2J=rBo
- 小区停车协商的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/463
- 社区花园共建的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/chl
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/evt
- 青年志愿活动的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/769=lkm
- 非遗课堂体验的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/kic=794
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/CkJ=txM
- 社会体育指导的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/725
- 青年志愿活动的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/ktm
- 社区文化节活动的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/1Ta
- 城乡公共服务的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/651=hga
- 邻里共享空间的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/yum=671
- 家庭健康管理的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/Ovh=Lsy
- 基层服务创新的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E5%A4%AE%E8%A7%86%E8%B5%84%E8%AE%AF?/056
- 街区绿化养护的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E5%A4%AE%E8%A7%86%E8%B5%84%E8%AE%AF?/aer
- 气象科普传播的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E5%A4%AE%E8%A7%86%E8%B5%84%E8%AE%AF?/bVy
- 公共空间休憩的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E5%A4%AE%E8%A7%86%E8%B5%84%E8%AE%AF?/066=bpu
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E5%A4%AE%E8%A7%86%E8%B5%84%E8%AE%AF?/vht=846
- 城市夜间生活的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E5%A4%AE%E8%A7%86%E8%B5%84%E8%AE%AF?/d2x=2fV
- 新能源出行的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/890
- 城市文明实践的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/vjd
- 老年数字阅读的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/6zq
- 青年志愿活动中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/642=aks
- 小微企业服务的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/sor=423
- 青少年心理健康的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/mTe=yW8
- 社区体育组织的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/863
- 城市生活记录的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/sjt
- 城市应急科普的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/Cy4
- 智慧城市体验的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/007=uml
- 儿童安全出行的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/esi=464
- 社区老年食堂的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/z52=Vvn
- 家庭健康科普的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/527
- 周末休闲规划的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/xrh
- 城市公共艺术的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/Feg
- 绿色建筑理念的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/657=nzj
- 节约用水实践的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/yex=966
- 运动安全知识的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/a4y=CGa
- 文化讲座服务的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/689
- 数字艺术创作的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/prp
- 数字课堂应用中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/4iF
- 绿色出行服务的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/941=kgz
- 邻里互助活动的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/rnu=063
- 绿色办公实践的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/VkY=Pdj
- 文明养宠科普的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%AF%BB%E6%8A%A5?/304
- 青年就业服务的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%AF%BB%E6%8A%A5?/mdd
- 公园休闲体验的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%AF%BB%E6%8A%A5?/0Zw
- 租房信息服务的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%AF%BB%E6%8A%A5?/076=tug
- 老年数字阅读的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%AF%BB%E6%8A%A5?/chi=750
- 乡村休闲旅游中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%AF%BB%E6%8A%A5?/E9B=Bc6
- 社区艺术活动的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/018
- 无障碍信息设计的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/hke
- 乡村公共文化的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/Mgy
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/753=kzg
- 社区安全巡查的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/uns=747
- 节假日出行安排的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/SCD=sHm
- 家庭饮食安排的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/107
- 骑行路线规划的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/yyn
- 个人信息保护的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/qHG
- 公园休闲体验的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/826=unw
- 公共空间照明的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vwn=703
- 城市建设科普的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/NA1=qD7
- 基层医疗预约的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E6%90%9C%E7%8B%97%E6%89%8B%E8%AE%B0?/072
- 街区更新实践的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E6%90%9C%E7%8B%97%E6%89%8B%E8%AE%B0?/wqu
- 城市人文观察的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E6%90%9C%E7%8B%97%E6%89%8B%E8%AE%B0?/X5z
- 安全出行教育的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E6%90%9C%E7%8B%97%E6%89%8B%E8%AE%B0?/925=qbf
- 节气饮食文化的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E6%90%9C%E7%8B%97%E6%89%8B%E8%AE%B0?/sds=795
- 社区托育服务的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E6%90%9C%E7%8B%97%E6%89%8B%E8%AE%B0?/bzx=80F
- 环境教育课程的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/793
- 科学信息获取的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/weu
- 无障碍信息设计的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/6zT
- 社区商业活力的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/929=zhw
- 开放数据应用的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/tec=090
- 科学观察活动的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/bI0=fjG
- 社区垃圾回收的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/122
- 老年智能设备的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/viv
- 智能家居应用的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/TZS
- 家庭收纳实践的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/953=teu
- 社区运动空间中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/puq=038
- 社区庭院绿化的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/lYB=WQv
- 街区绿化养护的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/917
- 家庭用电安全的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/gmp
- 青年职业探索的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/enR
- 家庭环保行动的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/831=iwz
- 家庭防灾准备的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/hlh=351
- 公共图书馆服务的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/iiH=yWa
- 开放数据应用的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/615
- 居民健康教育的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/xiz
- 校园阅读活动的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/JhR
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/603=fqv
- 城市人文观察的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/vrl=111
- 无障碍信息设计的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/6zz=caD
- 家庭健康科普中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/084
- 家庭节能实践的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/xsa
- 社区共享书架的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/IKr
- 环境教育课程的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/936=tcn
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/fsk=057
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/od3=wdn
- 志愿服务平台的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/904
- 老年人日常照护的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/xqs
- 城市雨天出行的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/LON
- 网络信息辨识有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/820=jtv
- 数字阅读服务的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/dqb=943
- 科普展览体验的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/VKl=Dp0
- 社区垃圾分类的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/581
- 城市公共厕所的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/vin
- 城市体育设施的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/6HR
- 社区商业活力的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/520=unc
- 城市绿道建设中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/nyc=563
- 农村环境治理的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/QJ1=DoV
- 街区绿化养护的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/170
- 城市人文观察的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/zqr
- 乡村文化活动的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/ZYc
- 社区交通安全的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/092=tdj
- 绿色校园实践的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/loh=357
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/RNS=CJH
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/519
- 乡村产业科普的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/nov
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/RAS
- 青年就业服务的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/629=txz
- 社区儿童活动的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/jtk=617
- 生活技能分享有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/v49=ime
- 城市骑行环境的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/699
- 老年友好服务的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/gzu
- 社区艺术活动的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/jYG
- 消防知识宣传的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/448=yyn
- 家庭养老规划的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/cmp=744
- 家庭节能设备的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/NA8=v97
- 数字课堂应用的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/586
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/czf
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/qRA
- 社区体育组织的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/243=crb
- 数字创意课程的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/tge=621
- 生活技能分享的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/W5O=fR0
- 家庭节能实践的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/011
- 城市地名文化的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/jkk
- 城市步行友好的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/eWf
- 科普展览体验的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/624=vdy
- 城市公共厕所的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/fhi=299
- 社区生活指南的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/KZd=70m
- 校园阅读活动的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/270
- 社区读书角建设的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/sss
- 农贸市场环境的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/YLj
- 街区更新实践的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/086=yux
- 社区商业活力的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/xga=022
- 老旧小区改造的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/62d=u6B
- 数字公共文化的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/287
- 城市微更新实践的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/ndj
- 城市应急广播中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/aNH
- 老年运动活动的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/842=daw
- 公共空间导览的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/lme=030
- 在线教育体验的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/XMJ=TkY
- 城市人文观察的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/115
- 课后服务体验的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/kza
- 社区法律科普的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/NJ4
- 公共服务指南有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/673=hmv
- 节约用水实践的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/mbc=661
- 地方文化传播的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/mYw=eRe
- 公共交通信息服务的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/149
- 乡村产业科普的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/ijf
- 零废弃生活尝试的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/dzj
- 低碳社区实践的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/770=soq
- 小区停车协商的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/gss=095
- 生活服务数字化的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/osw=GvI
- 绿色建筑理念的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%97%B6%E6%8A%A5?/677
- 城市共享单车的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%97%B6%E6%8A%A5?/zfq
- 公园休闲体验的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%97%B6%E6%8A%A5?/jnk
- 居家防滑改造的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%97%B6%E6%8A%A5?/986=owa
- 绿色出行服务的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%97%B6%E6%8A%A5?/jnw=716
- 骑行路线规划的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%97%B6%E6%8A%A5?/3Vm=ZK4
- 城乡公共服务的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/580
- 城市公共空间的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/ijv
- 青年志愿活动的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/sAC
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/091=zuq
- 城市夜间生活的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/koo=409
- 公共空间照明的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/NvF=RFu
- 机器学习入门的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/706
- 节气饮食文化有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/eba
- 社区便民服务的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/QEL
- 数字支付体验的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/776=gdz
- 社区快递服务的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/qhr=806
- 环境教育课程的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/Pac=q8Q
- 家庭收纳实践的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/671
- 老年友好服务的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/pwh
- 城市慢行系统的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/o1N
- 社区慢性病防控的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/359=ymo
- 老年学习活动的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/cmb=377
- 公园无障碍服务的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/VvA=WZD
- 城市文明出行的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/092
- 社区协商议事的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/bvf
- 乡村生活观察的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/58K
- 运动安全知识的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/453=zut

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
