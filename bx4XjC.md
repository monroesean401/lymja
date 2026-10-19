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

- 安全出行教育的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9ic-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/stc=049
- 青少年编程学习的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9ic-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/Qps=Xqu
- 数字阅读服务的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F_36%E6%B0%AA%E9%80%9F%E8%A7%88?/618
- 开放式学习空间的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F_36%E6%B0%AA%E9%80%9F%E8%A7%88?/ezs
- 公园亲子设施的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F_36%E6%B0%AA%E9%80%9F%E8%A7%88?/Tjs
- 农村环境治理的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F_36%E6%B0%AA%E9%80%9F%E8%A7%88?/921=xnd
- 地方美食文化的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F_36%E6%B0%AA%E9%80%9F%E8%A7%88?/wmc=013
- 社区生活指南中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F_36%E6%B0%AA%E9%80%9F%E8%A7%88?/QAj=yH0
- 无障碍出行的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%B9%B8%E8%BF%90%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/010
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%B9%B8%E8%BF%90%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/uto
- 社区共享书架的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%B9%B8%E8%BF%90%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/t9M
- 消防知识宣传的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%B9%B8%E8%BF%90%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/392=ems
- 安全出行教育的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%B9%B8%E8%BF%90%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/iqv=628
- 社区活动策划的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%B9%B8%E8%BF%90%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/nAW=SB0
- 城市可持续生活的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%2C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/747
- 生活服务数字化的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%2C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/pap
- 家庭运动计划的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%2C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/FSD
- 小微企业服务的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%2C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/266=vyj
- 家庭志愿活动的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%2C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/hhw=303
- 公共交通接驳的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%2C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/u6a=bZs
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/380
- 农村环境治理的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/eue
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/gzb
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/384=pjo
- 城市适老服务的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/mhr=202
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/OHA=x85
- 城市农夫市集的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%88%B0%E5%BA%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/048
- 青少年心理健康的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%88%B0%E5%BA%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/kmh
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%88%B0%E5%BA%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/1WT
- 骑行路线规划的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%88%B0%E5%BA%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/891=jki
- 乡村阅读空间的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%88%B0%E5%BA%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/prv=060
- 社区公共卫生的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%88%B0%E5%BA%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/Au1=cPc
- 街区更新实践的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/278
- 基层健康档案的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/fpq
- 农业科普体验的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/6UT
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/410=cye
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/myy=579
- 租房信息服务的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/EAJ=9iO
- 社区活动报名中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/252
- 公共场所导视的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/okf
- 食品安全科普的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/mA0
- 城市展览体验中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/633=hkf
- 生活技能分享的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/tnw=619
- 本地消费场景的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/Itp=aZi
- 无障碍出行的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/495
- 城市绿道建设的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/uri
- 社区庭院绿化的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/VXw
- 青少年户外教育的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/326=zsc
- 社区消防演练的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/imj=998
- 绿色出行服务的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/jPU=4hT
- 数字生活课堂的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_welcome1388%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/395
- 乡村公共服务的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_welcome1388%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/jbu
- 街区更新实践的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_welcome1388%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/mA2
- 社区故事采集的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_welcome1388%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/418=thx
- 图书馆亲子空间的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_welcome1388%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/sls=441
- 低碳社区实践的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_welcome1388%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/YCZ=5fP
- 数字学习资源的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_5%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8F%BD_360%E8%AE%BA%E5%9D%9B?/059
- 绿色出行服务的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_5%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8F%BD_360%E8%AE%BA%E5%9D%9B?/kyv
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_5%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8F%BD_360%E8%AE%BA%E5%9D%9B?/EVB
- 城市步行友好的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_5%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8F%BD_360%E8%AE%BA%E5%9D%9B?/121=xaz
- 家庭用电安全的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_5%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8F%BD_360%E8%AE%BA%E5%9D%9B?/muz=839
- 城市噪声观察的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_5%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8F%BD_360%E8%AE%BA%E5%9D%9B?/FkT=GVW
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/754
- 社区垃圾分类的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/liv
- 文化场馆预约的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/v5x
- 城市树木认养的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/014=awd
- 公共设施维护的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/its=329
- 城市树木认养的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/JMp=kAU
- 校园社团活动的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%8F%E9%AA%8C_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/777
- 社区快递服务的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%8F%E9%AA%8C_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/evm
- 无障碍出行的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%8F%E9%AA%8C_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/9xd
- 乡村文化空间中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%8F%E9%AA%8C_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/439=vak
- 社区快递服务的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%8F%E9%AA%8C_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/dsb=291
- 乡村公共文化的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%8F%E9%AA%8C_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/jqt=R5X
- 家庭环保习惯的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/383
- 传统手工艺体验的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/amt
- 社区学习活动的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/kHR
- 城市文化路线从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/709=aoo
- 环境教育课程的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/qhm=397
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/ifX=f7p
- 科学信息获取的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/834
- 社区协商议事的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/qfx
- 开放数据应用的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/C8z
- 公共空间安全的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/862=mxy
- 数字公共文化的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/tsd=479
- 便民服务地图的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/xRc=6bw
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E6%95%99%E8%82%B2?/369
- 社区消防演练的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E6%95%99%E8%82%B2?/bio
- 科学健身方法的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E6%95%99%E8%82%B2?/zGf
- 社区手工活动的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E6%95%99%E8%82%B2?/211=exw
- 社区健康讲座的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E6%95%99%E8%82%B2?/lke=427
- 社区安全巡查的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_36%E6%B0%AA%E6%95%99%E8%82%B2?/7at=hcW
- 机器人科普活动的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E4%B8%AD%E5%A5%96_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/103
- 生活技能分享的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E4%B8%AD%E5%A5%96_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/plb
- 户外活动组织的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E4%B8%AD%E5%A5%96_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/4CM
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E4%B8%AD%E5%A5%96_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/111=mxi
- 开放式学习空间的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E4%B8%AD%E5%A5%96_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/rey=456
- 职业技能学习的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E4%B8%AD%E5%A5%96_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/E5i=LSR
- 职业技能学习的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/940
- 智慧停车服务的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/ijz
- 个人数据管理的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/cpb
- 青年志愿活动的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/657=dxc
- 社区家政服务的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/dju=440
- 科学信息获取的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/mhx=MtQ
- 食品配送体验的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%89%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/203
- 数字便民地图的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%89%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/ubg
- 生活技能分享的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%89%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/7bf
- 邻里共享空间的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%89%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/320=ykz
- 邻里互助活动的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%89%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/wpa=337
- 非遗课堂体验的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%89%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/J8Z=Hcg
- 城市文化路线的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A5%A8?/982
- 非遗课堂体验的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A5%A8?/cgk
- 家庭消费规划的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A5%A8?/9Ra
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A5%A8?/514=elx
- 终身学习资源有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A5%A8?/acq=725
- 家庭志愿活动的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A5%A8?/6W2=AxP
- 电动汽车充电的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%8E%A9%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/191
- 城市树木认养的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%8E%A9%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/ngo
- 数字阅读服务的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%8E%A9%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/5h6
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%8E%A9%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/359=dbz
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%8E%A9%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/otn=914
- 低碳社区实践的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%8E%A9%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/2N2=8fv
- 本地旅行体验的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/518
- 公共服务指南的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/jnk
- 家庭食品保存的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/ge9
- 科学健身方法的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/092=qek
- 青年职业探索的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/web=691
- 城市慢跑路线的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/2jp=ubf
- 志愿者培训交流的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/784
- 文化讲座服务的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/nqo
- 科学信息获取的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/B1T
- 数字学习资源的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/935=tec
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/xep=809
- 城市生活服务的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/8Wa=VoD
- 药品使用科普的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%AE%E5%88%AE%E4%B9%90_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/664
- 城市展览体验的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%AE%E5%88%AE%E4%B9%90_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/owm
- 城市可持续生活的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%AE%E5%88%AE%E4%B9%90_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/RwA
- 智能手机助老的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%AE%E5%88%AE%E4%B9%90_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/335=wjc
- 绿色出行服务的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%AE%E5%88%AE%E4%B9%90_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/pmp=566
- 环境教育课程的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%AE%E5%88%AE%E4%B9%90_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/N9s=R8a
- 城市步行友好的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/017
- 数字创意课程的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/ovl
- 家庭教育交流的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/T89
- 绿色消费选择中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/694=nba
- 市民意见收集的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/isn=402
- 社区停车服务的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/DZ4=P9N
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/520
- 街区更新实践中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/lte
- 家庭网络使用的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/QFe
- 家庭收纳实践的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/397=tyk
- 乡村阅读空间的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/tjz=885
- 急救知识普及的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/mts=nkr
- 周末休闲规划的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/202
- 社区协商议事的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/cvk
- 公共交通接驳的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/RHO
- 城乡公共服务的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/817=hdj
- 城市慢行系统的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/qwz=905
- 社区知识分享的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/IJN=NBI
- 社区生活指南的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/778
- 开放数据应用的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/gej
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/eiu
- 文明养宠科普的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/860=qbm
- 便民维修服务的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/wxb=930
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/QzG=iCr
- 基层健康档案的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/417
- 社区垃圾回收的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/ocz
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/Fz0
- 音乐欣赏活动的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/139=vsn
- 城市体育设施的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/mmu=283
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/CHG=spI
- 居家防滑改造的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/306
- 社区交通安全的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/oht
- 在线教育体验的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/zRh
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/136=ypf
- 个人信息保护的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/gaf=106
- 社区故事采集的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/F63=YTj
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/881
- 家庭节能实践的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/uqo
- 乡村文化活动的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/z8S
- 开放式学习空间的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/266=epr
- 城市树木认养的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/iup=271
- 家庭收纳实践的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/GpK=Eds
- 节约用水实践的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%94%BB%E7%95%A5_%E8%8A%92%E6%9E%9C?/562
- 农村环境治理的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%94%BB%E7%95%A5_%E8%8A%92%E6%9E%9C?/mkc
- 城市便民驿站的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%94%BB%E7%95%A5_%E8%8A%92%E6%9E%9C?/yts
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%94%BB%E7%95%A5_%E8%8A%92%E6%9E%9C?/015=nwh
- 家庭健康管理的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%94%BB%E7%95%A5_%E8%8A%92%E6%9E%9C?/qlo=957
- 社会体育指导的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%94%BB%E7%95%A5_%E8%8A%92%E6%9E%9C?/lz5=CNt
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/186
- 社区公共议事的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/iqu
- 社区宠物管理的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/ovS
- 本地消费场景的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/089=fff
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/uhu=609
- 地方戏曲体验的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/DJ4=0xT
- 社区艺术活动的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E7%89%88_%E6%90%9C%E7%8B%97%E8%82%A1%E7%A5%A8?/113
- 数字学习资源的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E7%89%88_%E6%90%9C%E7%8B%97%E8%82%A1%E7%A5%A8?/ewd
- 社区公共卫生的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E7%89%88_%E6%90%9C%E7%8B%97%E8%82%A1%E7%A5%A8?/wr7
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E7%89%88_%E6%90%9C%E7%8B%97%E8%82%A1%E7%A5%A8?/188=uoi
- 乡村教育资源的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E7%89%88_%E6%90%9C%E7%8B%97%E8%82%A1%E7%A5%A8?/tks=974
- 农业科普体验的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E7%89%88_%E6%90%9C%E7%8B%97%E8%82%A1%E7%A5%A8?/fpn=suK
- 数字设备回收的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/664
- 城市文明出行的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/gut
- 城市绿色交通的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/vDt
- 家庭收纳实践的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/348=uja
- 城市噪声观察的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/vas=244
- 城市博物馆服务的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/aqK=4Ln
- 老旧小区改造的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_pc28%E6%8A%80%E5%B7%A7%E4%B8%8E%E5%BF%83%E5%BE%97_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/624
- 电子商务服务中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_pc28%E6%8A%80%E5%B7%A7%E4%B8%8E%E5%BF%83%E5%BE%97_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/zts
- 居家适老化改造的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_pc28%E6%8A%80%E5%B7%A7%E4%B8%8E%E5%BF%83%E5%BE%97_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/vro
- 公共图书馆服务的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_pc28%E6%8A%80%E5%B7%A7%E4%B8%8E%E5%BF%83%E5%BE%97_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/022=yzf
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_pc28%E6%8A%80%E5%B7%A7%E4%B8%8E%E5%BF%83%E5%BE%97_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/xiy=359
- 社区托育服务的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_pc28%E6%8A%80%E5%B7%A7%E4%B8%8E%E5%BF%83%E5%BE%97_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/fF3=DXP
- 城市休闲步道的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%A8%BB%E8%8D%89%E4%BA%BA%E5%85%8D%E8%B4%B9%E8%AF%BB_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/044
- 智能家居应用的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%A8%BB%E8%8D%89%E4%BA%BA%E5%85%8D%E8%B4%B9%E8%AF%BB_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/xjc
- 亲子阅读活动的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%A8%BB%E8%8D%89%E4%BA%BA%E5%85%8D%E8%B4%B9%E8%AF%BB_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/lmv
- 城市游园体验的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%A8%BB%E8%8D%89%E4%BA%BA%E5%85%8D%E8%B4%B9%E8%AF%BB_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/046=zgm
- 乡村文化活动的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%A8%BB%E8%8D%89%E4%BA%BA%E5%85%8D%E8%B4%B9%E8%AF%BB_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/mpy=657
- 老年学习活动的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%A8%BB%E8%8D%89%E4%BA%BA%E5%85%8D%E8%B4%B9%E8%AF%BB_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/ACn=422
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1?/265
- 城市夜间生活的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1?/vlg
- 无障碍信息设计的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1?/UFX
- 城市建设科普的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1?/200=yrf
- 社区修缮行动的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1?/ppv=444
- 绿色生活实践的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1?/NMI=HJV
- 乡村产业科普的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/512
- 公共服务评价的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/tux
- 儿童阅读角的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/oN5
- 社区教育资源的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/918=mia
- 数字阅读服务的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/zof=123
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/X6w=Gog
- 便民信息查询的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%BA%AE%E7%82%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/620
- 社区艺术活动的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%BA%AE%E7%82%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/bwx
- 公共卫生宣传的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%BA%AE%E7%82%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/s5l
- 数字地图应用的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%BA%AE%E7%82%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/217=eia
- 社区商业活力的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%BA%AE%E7%82%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/ozb=645
- 城市可持续生活的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%BA%AE%E7%82%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/IzD=NrO
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/981
- 日常摄影记录的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/arn
- 机器学习入门的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/GXp
- 乡村电商实践的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/883=obk
- 安全出行教育的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/ifu=681
- 城市微更新实践的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/k2d=FwA
- 家庭养老规划的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/423
- 非遗课堂体验的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/kjf
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/V1v
- 社区菜市场服务从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/961=rpw
- 市民热线服务的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/zxf=396
- 邻里共享空间的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/6I3=rKw
- 老年友好服务的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%EF%BC%8F3%E5%8A%A9%E6%89%8Bapp_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/412
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%EF%BC%8F3%E5%8A%A9%E6%89%8Bapp_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/vod

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
