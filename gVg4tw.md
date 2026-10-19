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

- 街区道路维护的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_168%E5%B9%B8%E8%BF%90%E4%BD%93%E5%BD%A9%E6%BE%B3%E6%B4%B25%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E7%BB%93%E6%9E%9C%E5%AE%9E_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/lzr=254
- 老年友好服务的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_168%E5%B9%B8%E8%BF%90%E4%BD%93%E5%BD%A9%E6%BE%B3%E6%B4%B25%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E7%BB%93%E6%9E%9C%E5%AE%9E_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/guj=jBt
- 节约用水实践的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD168j%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/956
- 社区停车服务的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD168j%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/kmg
- 社区快递服务的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD168j%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/sS8
- 急救知识普及的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD168j%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/603=kco
- 绿色生活实践从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD168j%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/cir=487
- 志愿者培训交流的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%8B%E8%BD%BD168j%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/03I=ZnO
- 社区便民集市的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_168%E8%AE%A1%E5%88%92%E7%BD%91-%E6%9C%80%E4%B8%93%E4%B8%9A%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B8%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/806
- 城市住房服务的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_168%E8%AE%A1%E5%88%92%E7%BD%91-%E6%9C%80%E4%B8%93%E4%B8%9A%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B8%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/pby
- 社区慢性病防控的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_168%E8%AE%A1%E5%88%92%E7%BD%91-%E6%9C%80%E4%B8%93%E4%B8%9A%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B8%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/LVf
- 乡村文化活动的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_168%E8%AE%A1%E5%88%92%E7%BD%91-%E6%9C%80%E4%B8%93%E4%B8%9A%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B8%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/644=cul
- 乡村阅读活动的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_168%E8%AE%A1%E5%88%92%E7%BD%91-%E6%9C%80%E4%B8%93%E4%B8%9A%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B8%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/ojl=671
- 城市公共空间的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_168%E8%AE%A1%E5%88%92%E7%BD%91-%E6%9C%80%E4%B8%93%E4%B8%9A%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B8%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/wGp=LD1
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_168%E8%AE%A1%E5%88%92%E7%BD%91APP_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/426
- 户外活动组织的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_168%E8%AE%A1%E5%88%92%E7%BD%91APP_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/pnw
- 数据分析入门的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_168%E8%AE%A1%E5%88%92%E7%BD%91APP_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/bYQ
- 公共文化活动的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_168%E8%AE%A1%E5%88%92%E7%BD%91APP_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/262=gbw
- 公共服务预约的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_168%E8%AE%A1%E5%88%92%E7%BD%91APP_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/dik=906
- 社区运动空间的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_168%E8%AE%A1%E5%88%92%E7%BD%91APP_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/bW7=gUi
- 居民健康教育的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/904
- 药品使用科普的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/ecn
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/FBA
- 家庭运动计划的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/772=zgt
- 便民维修服务的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/mvb=336
- 社区休闲设施的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/qry=MFs
- 社区运动空间的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/196
- 乡村公共服务的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/rot
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/K1L
- 科普展览体验的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/287=dmj
- 家庭运动计划的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/vtt=234
- 社区志愿服务的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/14a=tdu
- 公共设施使用的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%8E%8C%E4%B8%8A168a%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/087
- 城市地名文化的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%8E%8C%E4%B8%8A168a%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/qts
- 数字便民地图的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%8E%8C%E4%B8%8A168a%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/k8h
- 老旧小区改造的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%8E%8C%E4%B8%8A168a%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/055=gaw
- 青少年户外教育的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%8E%8C%E4%B8%8A168a%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/lny=797
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%8E%8C%E4%B8%8A168a%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/FCO=Hnt
- 老年人文化生活的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/097
- 公共服务沟通的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/wck
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/TJO
- 电动汽车充电的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/683=lsu
- 邻里互助活动的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/raj=109
- 城市应急科普的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/dhT=WYZ
- 社区庭院绿化的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%BA%86_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/034
- 生活垃圾减量的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%BA%86_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/ovt
- 社区托育服务的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%BA%86_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/cvm
- 基层健康档案的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%BA%86_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/050=leu
- 青少年户外教育的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%BA%86_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/ktu=791
- 图书馆亲子空间的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%BA%86_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/RDC=G5r
- 校园安全教育的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%BC%97%E8%B5%A2%E5%9B%BD%E9%99%85%E7%89%88%28%E5%85%8D%E8%B4%B9%29_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/940
- 社区绿色空间的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%BC%97%E8%B5%A2%E5%9B%BD%E9%99%85%E7%89%88%28%E5%85%8D%E8%B4%B9%29_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/yan
- 健康饮食教育的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%BC%97%E8%B5%A2%E5%9B%BD%E9%99%85%E7%89%88%28%E5%85%8D%E8%B4%B9%29_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/90X
- 租房信息服务的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%BC%97%E8%B5%A2%E5%9B%BD%E9%99%85%E7%89%88%28%E5%85%8D%E8%B4%B9%29_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/889=bwb
- 周末休闲规划的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%BC%97%E8%B5%A2%E5%9B%BD%E9%99%85%E7%89%88%28%E5%85%8D%E8%B4%B9%29_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/ygl=734
- 家庭教育交流的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%BC%97%E8%B5%A2%E5%9B%BD%E9%99%85%E7%89%88%28%E5%85%8D%E8%B4%B9%29_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/csO=wR1
- 亲子科普活动的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_13458%E8%B7%9F02679%E5%AE%9E%E6%88%98%E4%B9%B0%E6%B3%95_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/784
- 气象科普传播的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_13458%E8%B7%9F02679%E5%AE%9E%E6%88%98%E4%B9%B0%E6%B3%95_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/swu
- 乡村公共阅读的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_13458%E8%B7%9F02679%E5%AE%9E%E6%88%98%E4%B9%B0%E6%B3%95_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/Adi
- 城市绿色交通的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_13458%E8%B7%9F02679%E5%AE%9E%E6%88%98%E4%B9%B0%E6%B3%95_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/000=oht
- 数字政务体验的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_13458%E8%B7%9F02679%E5%AE%9E%E6%88%98%E4%B9%B0%E6%B3%95_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/kiw=912
- 在线学习体验的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_13458%E8%B7%9F02679%E5%AE%9E%E6%88%98%E4%B9%B0%E6%B3%95_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/Gkd=3XO
- 市民热线服务的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_3-8%E5%90%8D%E9%A3%9E%E8%89%87%E6%9C%80%E7%AE%80%E5%8D%95%E6%89%93%E6%B3%95%E5%9B%BE%E8%A7%A3_%E8%85%BE%E8%AE%AF%E7%88%86%E6%96%99?/385
- 老年数字阅读的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_3-8%E5%90%8D%E9%A3%9E%E8%89%87%E6%9C%80%E7%AE%80%E5%8D%95%E6%89%93%E6%B3%95%E5%9B%BE%E8%A7%A3_%E8%85%BE%E8%AE%AF%E7%88%86%E6%96%99?/oau
- 街区绿化养护中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_3-8%E5%90%8D%E9%A3%9E%E8%89%87%E6%9C%80%E7%AE%80%E5%8D%95%E6%89%93%E6%B3%95%E5%9B%BE%E8%A7%A3_%E8%85%BE%E8%AE%AF%E7%88%86%E6%96%99?/xjL
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_3-8%E5%90%8D%E9%A3%9E%E8%89%87%E6%9C%80%E7%AE%80%E5%8D%95%E6%89%93%E6%B3%95%E5%9B%BE%E8%A7%A3_%E8%85%BE%E8%AE%AF%E7%88%86%E6%96%99?/508=ixd
- 文化讲座服务的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_3-8%E5%90%8D%E9%A3%9E%E8%89%87%E6%9C%80%E7%AE%80%E5%8D%95%E6%89%93%E6%B3%95%E5%9B%BE%E8%A7%A3_%E8%85%BE%E8%AE%AF%E7%88%86%E6%96%99?/tpb=999
- 社区文化传播有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_3-8%E5%90%8D%E9%A3%9E%E8%89%87%E6%9C%80%E7%AE%80%E5%8D%95%E6%89%93%E6%B3%95%E5%9B%BE%E8%A7%A3_%E8%85%BE%E8%AE%AF%E7%88%86%E6%96%99?/ACz=5YL
- 校园安全教育的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_01%E8%AE%A1%E5%88%92com01%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/693
- 地方民俗记录的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_01%E8%AE%A1%E5%88%92com01%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/olh
- 食品配送体验的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_01%E8%AE%A1%E5%88%92com01%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/2RT
- 家庭养老规划的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_01%E8%AE%A1%E5%88%92com01%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/182=tfp
- 个人信息保护的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_01%E8%AE%A1%E5%88%92com01%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/pzh=433
- 家庭阅读计划的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_01%E8%AE%A1%E5%88%92com01%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/kXh=EcV
- 社区运动空间的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/030
- 社区法律科普中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/zda
- 社区活动报名的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/mwX
- 社区家校合作的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/442=ycb
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/smp=357
- 信息无障碍体验的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/v2W=iIo
- 个人时间管理的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/553
- 公共文化活动的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/qhn
- 电子商务服务的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/Jm4
- 社区公共议事的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/303=rvv
- 日常摄影记录的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/jpn=060
- 传统手工艺体验的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/UjK=v4v
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E5%A4%A7%E4%BC%97%E7%82%B9%E8%AF%84_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/633
- 消防知识宣传的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E5%A4%A7%E4%BC%97%E7%82%B9%E8%AF%84_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/dpe
- 家庭阅读计划的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E5%A4%A7%E4%BC%97%E7%82%B9%E8%AF%84_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/dy7
- 老年人文化生活的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E5%A4%A7%E4%BC%97%E7%82%B9%E8%AF%84_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/910=yyj
- 社区教育资源的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E5%A4%A7%E4%BC%97%E7%82%B9%E8%AF%84_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/efw=860
- 地方文化传播的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E5%A4%A7%E4%BC%97%E7%82%B9%E8%AF%84_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/a4t=xvV
- 社区设施共享的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/795
- 小区停车协商的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/hpu
- 志愿服务平台的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/QUf
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/411=rnv
- 公园无障碍服务的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/qic=560
- 地方民俗记录的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/d0u=u8N
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%9D%A0%E8%B0%B1%E7%BE%A4%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/304
- 社区快递服务的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%9D%A0%E8%B0%B1%E7%BE%A4%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/czi
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%9D%A0%E8%B0%B1%E7%BE%A4%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/cUv
- 电子商务服务从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%9D%A0%E8%B0%B1%E7%BE%A4%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/716=ywi
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%9D%A0%E8%B0%B1%E7%BE%A4%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/yzw=945
- 无障碍出行的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%9D%A0%E8%B0%B1%E7%BE%A4%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/0dh=Qwv
- 城市文化路线的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/731
- 租房信息服务的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/fbm
- 青年就业服务的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/BM5
- 家庭食品保存的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/717=yui
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/zyf=893
- 农贸市场环境的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/WBy=P40
- 城市可持续生活的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/739
- 休闲运动入门的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/slf
- 城市基础设施的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/Unm
- 城市地名文化的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/451=wcp
- 城市建设科普的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/ooj=240
- 老年运动活动的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/MY0=aEo
- 本地消费场景的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/977
- 社区信息发布的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/ayg
- 全民健身活动的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/DIs
- 节气饮食文化的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/466=uni
- 城市文化路线的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/avu=531
- 城市生活记录的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/2RI=M80
- 数字政务体验的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_75%E7%A7%92%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/060
- 生活垃圾减量从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_75%E7%A7%92%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/bkm
- 基层服务创新的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_75%E7%A7%92%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/TVJ
- 数字地图应用中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_75%E7%A7%92%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/761=mbt
- 城市夜间照明的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_75%E7%A7%92%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/upv=243
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_75%E7%A7%92%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/zUx=7yU
- 社区庭院绿化的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/088
- 科学健身方法的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/bpe
- 居家防滑改造的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/rLo
- 乡村公共服务的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/923=gqz
- 物业服务沟通的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/vmu=428
- 社区环保活动的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/1an=wVa
- 家庭运动计划的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/681
- 家庭运动计划的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/vnl
- 街头绿植养护的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/dCW
- 老年运动活动的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/787=rsi
- 家庭防灾准备的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/hds=440
- 社区老年食堂的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/ZLN=Z7h
- 儿童户外活动的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/853
- 社区绿色空间的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/gwp
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/LFR
- 绿色办公实践的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/777=dsj
- 公共交通接驳的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/uda=929
- 青少年户外教育的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/83a=L85
- 家庭志愿活动的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/489
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/rza
- 便民维修服务的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/ele
- 城市地名文化的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/151=fgz
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/rkq=413
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/jjl=wZU
- 社区家校合作的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/587
- 科普展览体验的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/las
- 健康饮水科普的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/6NT
- 社区共享书架的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/858=jiz
- 城市噪声观察的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/dod=903
- 传统节日科普的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/31S=r23
- 社区生活指南的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/698
- 城市游园体验的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/mgk
- 邻里互助活动的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/Wwv
- 城市住房服务的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/066=hzs
- 小区电梯维护的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/ndj=826
- 城市绿色交通的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/RXM=h1x
- 社区环保活动的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/421
- 城市基础设施的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/mzv
- 公共卫生宣传的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/uFl
- 非遗课堂体验的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/369=lzz
- 健康步道使用的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/qbf=559
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/o8w=KPd
- 绿色快递包装的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/628
- 家庭收纳实践的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/eou
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/yGu
- 职业技能学习的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/636=slr
- 光伏知识科普的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/glu=179
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/cXZ=OKB
- 节假日出行安排中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/334
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/tmn
- 科学运动指导的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/Q3C
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/960=wjt
- 生活垃圾减量的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/ymq=215
- 邻里互助活动的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/63a=Eq6
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/652
- 家庭教育交流的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/ris
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/enS
- 街区更新实践的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/344=omy
- 农贸市场环境中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/skc=008
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/khJ=1EF
- 城乡公共服务的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%A8%8E%E5%8A%A1?/747
- 乡村公共阅读的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%A8%8E%E5%8A%A1?/xpr
- 公共交通信息服务的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%A8%8E%E5%8A%A1?/PdF
- 租房信息服务的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%A8%8E%E5%8A%A1?/535=axd
- 数字政务体验的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%A8%8E%E5%8A%A1?/rlx=190
- 周末休闲规划从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%A8%8E%E5%8A%A1?/LPJ=njF
- 社区宠物管理的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E6%89%91%E5%8A%A8%E6%BC%AB?/680
- 智能手机助老的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E6%89%91%E5%8A%A8%E6%BC%AB?/pia
- 远程协作工具的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E6%89%91%E5%8A%A8%E6%BC%AB?/Cy8
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E6%89%91%E5%8A%A8%E6%BC%AB?/981=wgo
- 街头绿植养护的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E6%89%91%E5%8A%A8%E6%BC%AB?/cdy=287
- 科普展览体验的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E6%89%91%E5%8A%A8%E6%BC%AB?/dfs=4Rz
- 绿色消费选择的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/050
- 校园安全教育的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/mhc
- 节日文化体验的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/SwF
- 社区活动空间的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/319=uvz
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/wio=191
- 城市人文观察的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/A6d=AdP
- 新能源出行的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/721
- 职业技能学习的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/flc
- 社区环保活动的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/j6z
- 机器学习入门的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/857=vps
- 城市骑行环境的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/dtm=705
- 邻里互助活动的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/05G=BET
- 社区便民服务的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/295
- 公园休闲体验的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/yvr
- 地方文化传播的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/IAN
- 机器学习入门的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/659=kpu
- 邻里共享空间的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/rou=491
- 家庭饮食安排的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/A5u=Gek
- 社区休闲设施的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/145
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/icm
- 数字创意课程的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/908
- 公共设施维护的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/310=juj
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/ozv=704
- 科学教育活动的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/ZtX=Nkr
- 街区更新实践的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/747
- 小区电梯维护的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/msd
- 乡村文化活动的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/cp6
- 乡村文化空间中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/425=udz
- 食品配送体验的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/iej=680
- 气象科普传播的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/nwL=ZaH
- 劳动教育实践的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/569
- 城市地名文化的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/zth
- 基层医疗预约的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/nkZ
- 社区文化节活动的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/117=hcc
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/owt=955
- 乡村公共文化的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/p4y=uCd
- 个人数据管理的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/376
- 乡村文化活动的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/alt
- 社区托育服务的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/70y
- 公共场馆服务的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/653=mij
- 家庭志愿活动的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/uom=558
- 城市文明出行的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/Mkt=In8
- 青年职业探索的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/550
- 数字生活课堂的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/efc
- 城市噪声观察的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/coO
- 青少年科技社团的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/924=ajv
- 家庭消费规划的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/aoz=387
- 小区电梯维护的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/pCD=PZq
- 环境教育课程中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%89%B4?/471
- 社区安全巡查的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%89%B4?/qmw

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
