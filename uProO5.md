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

- 终身学习资源的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/rro=804
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/k28=lQW
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/562
- 数字素养提升的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/ocv
- 个人时间管理的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/N80
- 新能源出行的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/092=stu
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/qcl=966
- 农产品消费体验的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/Ard=yRJ
- 食品配送体验的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/550
- 绿色校园实践的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/pau
- 公园无障碍服务从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/0qP
- 社区协商议事的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/710=upq
- 校园节能行动的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/usj=670
- 节约用水实践的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/4HS=q7y
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%A0%E5%86%9B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/583
- 学校食育活动的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%A0%E5%86%9B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/fsj
- 城市步行环境的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%A0%E5%86%9B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/tNU
- 灵活就业交流的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%A0%E5%86%9B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/933=zii
- 低碳社区实践中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%A0%E5%86%9B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/xrm=295
- 家庭运动计划的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%A0%E5%86%9B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/Fin=DBY
- 数字课堂应用的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%B4%E5%A4%A7%E4%B8%8D%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%9C%88%E5%AD%90?/771
- 城市慢行系统的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%B4%E5%A4%A7%E4%B8%8D%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%9C%88%E5%AD%90?/ixi
- 社区读书角建设的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%B4%E5%A4%A7%E4%B8%8D%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%9C%88%E5%AD%90?/llv
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%B4%E5%A4%A7%E4%B8%8D%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%9C%88%E5%AD%90?/159=rxk
- 生活服务数字化的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%B4%E5%A4%A7%E4%B8%8D%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%9C%88%E5%AD%90?/gtj=827
- 非遗课堂体验的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A4%B4%E5%A4%A7%E4%B8%8D%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%9C%88%E5%AD%90?/sYq=IHA
- 城市基础设施的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/776
- 便民信息查询的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/paw
- 社区信息发布的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/WRr
- 小区停车协商的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/282=nzy
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/yyq=865
- 家庭科学教育的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/8vQ=rbq
- 本地旅行体验的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/901
- 数字学习资源的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/fdr
- 青少年编程学习的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/iK0
- 在线学习体验中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/816=qxh
- 社区公共卫生的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/hje=660
- 居家防滑改造的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/YeT=YtA
- 社区停车服务的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E8%B4%B4%E5%90%A7_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/166
- 城市文明实践的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E8%B4%B4%E5%90%A7_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/qal
- 全民健身活动的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E8%B4%B4%E5%90%A7_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/PZx
- 乡村教育资源的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E8%B4%B4%E5%90%A7_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/884=hbl
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E8%B4%B4%E5%90%A7_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/ynr=437
- 小区电梯维护的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E8%B4%B4%E5%90%A7_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/D8T=Qy1
- 公共服务评价的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E7%A8%B3%E5%AE%9A%E8%83%9C%E7%8E%87_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/045
- 个人信息保护的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E7%A8%B3%E5%AE%9A%E8%83%9C%E7%8E%87_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/ovl
- 社区儿童活动的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E7%A8%B3%E5%AE%9A%E8%83%9C%E7%8E%87_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/BFP
- 居家防滑改造的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E7%A8%B3%E5%AE%9A%E8%83%9C%E7%8E%87_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/678=hlb
- 老年数字阅读的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E7%A8%B3%E5%AE%9A%E8%83%9C%E7%8E%87_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/gew=544
- 家庭运动计划的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E7%A8%B3%E5%AE%9A%E8%83%9C%E7%8E%87_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/rCf=MQM
- 小区停车协商的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E8%A7%84%E5%88%99_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/450
- 社区花园共建的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E8%A7%84%E5%88%99_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/bby
- 学校体育活动的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E8%A7%84%E5%88%99_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/Xb8
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E8%A7%84%E5%88%99_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/886=xqe
- 乡村产业科普的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E8%A7%84%E5%88%99_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/nrg=183
- 城乡交通衔接的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E8%A7%84%E5%88%99_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/bXX=C6m
- 社区快递服务的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/188
- 读书会组织的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/par
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/S9A
- 在线学习体验的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/258=rec
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/nbv=469
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/h7Z=Vc5
- 城市慢行系统的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%8D%95%E5%8F%8C%E4%B8%8E%E5%A4%A7%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/889
- 图书借阅体验的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%8D%95%E5%8F%8C%E4%B8%8E%E5%A4%A7%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/dwr
- 农贸市场环境的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%8D%95%E5%8F%8C%E4%B8%8E%E5%A4%A7%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/NVP
- 终身学习资源的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%8D%95%E5%8F%8C%E4%B8%8E%E5%A4%A7%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/919=ofx
- 社区设施共享的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%8D%95%E5%8F%8C%E4%B8%8E%E5%A4%A7%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/kva=343
- 食品配送体验的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%8D%95%E5%8F%8C%E4%B8%8E%E5%A4%A7%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/SlV=IBq
- 公共场馆服务的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%AF%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E6%B0%91%E7%94%9F?/817
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%AF%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E6%B0%91%E7%94%9F?/okj
- 社区活动策划的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%AF%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E6%B0%91%E7%94%9F?/ctk
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%AF%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E6%B0%91%E7%94%9F?/652=mbz
- 周末休闲规划的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%AF%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E6%B0%91%E7%94%9F?/qvu=815
- 青年就业服务的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%AF%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E6%B0%91%E7%94%9F?/kRb=zRh
- 环境监测科普的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E?/893
- 社区养老服务的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E?/amb
- 城市运动公园的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E?/o5W
- 节气饮食文化的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E?/276=xlo
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E?/osl=304
- 社区知识分享的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E?/mQu=SxF
- 传统节日科普的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%94%B5%E8%84%91%E7%89%88_36%E6%B0%AA%E8%88%86%E6%83%85?/194
- 绿色出行服务的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%94%B5%E8%84%91%E7%89%88_36%E6%B0%AA%E8%88%86%E6%83%85?/cgw
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%94%B5%E8%84%91%E7%89%88_36%E6%B0%AA%E8%88%86%E6%83%85?/SrP
- 运动安全知识的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%94%B5%E8%84%91%E7%89%88_36%E6%B0%AA%E8%88%86%E6%83%85?/634=crk
- 科普展览体验的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%94%B5%E8%84%91%E7%89%88_36%E6%B0%AA%E8%88%86%E6%83%85?/yva=517
- 社区阅读服务的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%94%B5%E8%84%91%E7%89%88_36%E6%B0%AA%E8%88%86%E6%83%85?/eoS=WXJ
- 城乡公共服务的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E8%AE%AF?/424
- 城市休闲步道的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E8%AE%AF?/zwt
- 城市应急科普的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E8%AE%AF?/7g6
- 电子商务服务的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E8%AE%AF?/339=mzh
- 校园安全教育的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E8%AE%AF?/yiy=477
- 青年职业探索的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E8%AE%AF?/iUt=e6A
- 数字课堂应用的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E6%80%A7_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/154
- 数字资源检索的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E6%80%A7_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/qpg
- 传统手工艺体验的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E6%80%A7_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/CJw
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E6%80%A7_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/502=ygu
- 便民服务窗口的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E6%80%A7_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/jps=972
- 公共文化活动中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E6%80%A7_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/Xsg=CZ9
- 城市公共座椅的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/909
- 地方民俗记录的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/rsz
- 社区安全巡查的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/asJ
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/128=dbd
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/xiu=593
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/I5C=7up
- 数字学习资源的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E9%A2%9C%E8%89%B2%E7%9A%84_360%E5%85%AC%E5%BC%80%E8%AF%BE?/800
- 家庭食品保存的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E9%A2%9C%E8%89%B2%E7%9A%84_360%E5%85%AC%E5%BC%80%E8%AF%BE?/iiw
- 青少年科技社团的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E9%A2%9C%E8%89%B2%E7%9A%84_360%E5%85%AC%E5%BC%80%E8%AF%BE?/2yd
- 数字地图应用的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E9%A2%9C%E8%89%B2%E7%9A%84_360%E5%85%AC%E5%BC%80%E8%AF%BE?/419=mcx
- 机器人科普活动有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E9%A2%9C%E8%89%B2%E7%9A%84_360%E5%85%AC%E5%BC%80%E8%AF%BE?/xba=428
- 机器学习入门的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E9%A2%9C%E8%89%B2%E7%9A%84_360%E5%85%AC%E5%BC%80%E8%AF%BE?/KW5=ZbT
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/225
- 城乡公共服务的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/cxy
- 软件开发学习中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/Kqz
- 城市农夫市集的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/279=wfu
- 数字阅读服务的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/xpg=240
- 科学信息获取的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/l8x=9wS
- 城市适老服务的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/170
- 基层健康服务的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/but
- 志愿服务平台的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/YRi
- 绿色消费选择的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/499=rme
- 家庭用电安全的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/ovu=372
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/PCk=hgO
- 家庭用电安全的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%87%A4%E5%87%B0%E7%88%86%E6%96%99?/191
- 地方美食文化的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%87%A4%E5%87%B0%E7%88%86%E6%96%99?/gis
- 社区文化节活动中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%87%A4%E5%87%B0%E7%88%86%E6%96%99?/oJ4
- 公共健身器材的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%87%A4%E5%87%B0%E7%88%86%E6%96%99?/097=yfi
- 社区邻里服务的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%87%A4%E5%87%B0%E7%88%86%E6%96%99?/nwp=747
- 小微企业服务的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%87%A4%E5%87%B0%E7%88%86%E6%96%99?/elP=f6p
- 社区设施共享的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/159
- 公共场馆服务有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/igy
- 数字创作工具的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/1mz
- 家庭急救准备的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/803=omr
- 传统手工艺体验的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/ldw=011
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/V3w=Be2
- 公共卫生设施的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/738
- 校园节能行动的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/fyj
- 家庭急救准备的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/8jB
- 本地历史资料的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/008=sck
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/yfz=670
- 旧物循环利用的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/RqP=v2q
- 社区互助网络的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8A%A9%E6%89%8B_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/069
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8A%A9%E6%89%8B_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/cgl
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8A%A9%E6%89%8B_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/4X3
- 街区小店体验的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8A%A9%E6%89%8B_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/764=kkg
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8A%A9%E6%89%8B_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/egt=013
- 社区停车服务的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8A%A9%E6%89%8B_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/yfZ=PJX
- 数字档案服务的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/198
- 线上办事服务的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/woz
- 个人时间管理的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/mc9
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/760=wqq
- 社区艺术活动的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/nhy=380
- 电子商务服务的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/T8o=EWo
- 社区法律科普的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BF%A1%E8%AA%89_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/300
- 社区学习活动的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BF%A1%E8%AA%89_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/gou
- 生活服务数字化的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BF%A1%E8%AA%89_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/WTI
- 城乡交通衔接的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BF%A1%E8%AA%89_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/269=znf
- 社区文化节活动的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BF%A1%E8%AA%89_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/sbn=502
- 节约用水实践的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BF%A1%E8%AA%89_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/chp=yEw
- 社区学习活动的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/332
- 城市夜间生活的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/zqp
- 旧物循环利用的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/OOX
- 城市水环境观察的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/137=mbq
- 公共卫生宣传的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/qem=792
- 社区阅读服务的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/s6u=M5G
- 社区菜市场服务的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_36%E6%B0%AA%E5%AE%89%E9%98%B2?/393
- 社区故事采集的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_36%E6%B0%AA%E5%AE%89%E9%98%B2?/shf
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_36%E6%B0%AA%E5%AE%89%E9%98%B2?/tte
- 校园社团活动的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_36%E6%B0%AA%E5%AE%89%E9%98%B2?/365=dqg
- 文化场馆预约中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_36%E6%B0%AA%E5%AE%89%E9%98%B2?/sxh=001
- 老年运动活动的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_36%E6%B0%AA%E5%AE%89%E9%98%B2?/VCm=PQG
- 气象科普传播的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E5%87%A4%E5%87%B0%E6%97%85%E6%B8%B8?/756
- 日常摄影记录的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E5%87%A4%E5%87%B0%E6%97%85%E6%B8%B8?/kqt
- 地方旅游导览的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E5%87%A4%E5%87%B0%E6%97%85%E6%B8%B8?/zsX
- 公共交通信息服务的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E5%87%A4%E5%87%B0%E6%97%85%E6%B8%B8?/470=gsp
- 科学观察活动的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E5%87%A4%E5%87%B0%E6%97%85%E6%B8%B8?/uzm=933
- 志愿服务平台的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E5%87%A4%E5%87%B0%E6%97%85%E6%B8%B8?/tTH=PEx
- 科学观察活动中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/006
- 公共空间安全的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/boe
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/Fer
- 本地旅行体验的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/645=ilt
- 健康饮水科普的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/bbj=058
- 应急物资管理的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/WUH=N8H
- 家庭环保习惯的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/881
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/rdk
- 文化场馆预约的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/qOp
- 日常摄影记录的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/267=xhp
- 城市住房服务的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/ukr=558
- 公共服务指南从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/Ng0=Zjd
- 城市步行环境的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/489
- 数字公共文化的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/cby
- 公益活动组织的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/GmB
- 劳动教育实践的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/778=hmo
- 社区活动策划的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/ihv=042
- 数字公共文化的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/PHk=MDA
- 社区健康讲座的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/904
- 社区互助网络的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/kkg
- 小微企业服务的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/Ajb
- 药品使用科普的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/738=uoy
- 数字生活课堂的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/cul=581
- 城市住房服务的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/5Lg=Tlu
- 科学运动指导的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/974
- 社区教育资源的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/pgm
- 公共服务评价的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/OsD
- 青年志愿活动的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/527=sny
- 数字课堂应用的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/vqp=798
- 城市公共空间的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/R9n=RJY
- 课后服务体验的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/795
- 农业科普体验的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/wgj
- 绿色办公实践的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/uPi
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/619=vei
- 社区协商议事的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/fdd=490
- 儿童友好空间的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/jRx=3tC
- 城市便民驿站的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/242
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/gfd
- 网络信息辨识的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/phq
- 小区电梯维护的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/423=zcr
- 绿色出行服务的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/uxg=924
- 老年人日常照护的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/20M=4Qw
- 公共服务数字化的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%A8%B3%E5%AE%9A%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/643
- 邻里互助活动的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%A8%B3%E5%AE%9A%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/jqw
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%A8%B3%E5%AE%9A%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/uz6
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%A8%B3%E5%AE%9A%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/362=jtr
- 儿童友好空间的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%A8%B3%E5%AE%9A%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/yhr=716
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%A8%B3%E5%AE%9A%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/TkJ=dkG
- 校园阅读活动的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/619
- 小区停车协商的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/srv
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/q7t
- 智慧停车服务的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/649=dfc
- 城市公共标识的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/jsh=140
- 社区法律科普的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/Wlj=0j8
- 社区阅读服务的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E6%8A%80%E5%B7%A7%E5%92%8C%E8%A7%84%E5%BE%8B%E8%AF%A6%E8%A7%A3_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/252
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E6%8A%80%E5%B7%A7%E5%92%8C%E8%A7%84%E5%BE%8B%E8%AF%A6%E8%A7%A3_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/gve
- 本地旅行体验的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E6%8A%80%E5%B7%A7%E5%92%8C%E8%A7%84%E5%BE%8B%E8%AF%A6%E8%A7%A3_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/DZm
- 社区活动策划的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E6%8A%80%E5%B7%A7%E5%92%8C%E8%A7%84%E5%BE%8B%E8%AF%A6%E8%A7%A3_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/427=wgw
- 居家防滑改造的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E6%8A%80%E5%B7%A7%E5%92%8C%E8%A7%84%E5%BE%8B%E8%AF%A6%E8%A7%A3_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/hse=089
- 智能手机助老的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E6%8A%80%E5%B7%A7%E5%92%8C%E8%A7%84%E5%BE%8B%E8%AF%A6%E8%A7%A3_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/N6x=YRZ
- 社区生活指南的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E6%AD%A3%E7%A1%AE%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/216
- 机器学习入门的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E6%AD%A3%E7%A1%AE%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/spi
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E6%AD%A3%E7%A1%AE%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/ehW
- 城市博物馆服务的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E6%AD%A3%E7%A1%AE%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/656=yyt
- 公共场所导视的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E6%AD%A3%E7%A1%AE%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/yfk=205
- 社区健康讲座的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E6%AD%A3%E7%A1%AE%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/ywW=ibE
- 公共服务数字化的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB%EF%BC%8F3%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/245
- 数字地图应用从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB%EF%BC%8F3%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/gwe
- 邻里互助活动的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB%EF%BC%8F3%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/fmU
- 城市游园体验的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB%EF%BC%8F3%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/565=yvf
- 乡村教育资源的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB%EF%BC%8F3%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/rwn=038
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB%EF%BC%8F3%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/0OB=8FB
- 城市公共饮水的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/756
- 零废弃生活尝试的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/yaz

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
