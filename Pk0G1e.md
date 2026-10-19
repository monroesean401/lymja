# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:22**

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

- 街区小店体验的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/291
- 城乡交通衔接的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/swj
- 电子商务服务的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/Saw
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/138=nvw
- 健康饮食教育的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/bom=695
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/1qh=am3
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/385
- 远程协作工具的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/pwl
- 音乐欣赏活动的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/wAQ
- 校园社团活动的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/910=kzx
- 小区公共照明的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/fho=795
- 节气饮食文化的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/Zwv=ufg
- 居家防滑改造的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/943
- 儿童友好空间的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/jqv
- 节日文化体验的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/sCE
- 无障碍信息设计的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/733=wwf
- 休闲运动入门的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/bgi=161
- 城市慢跑路线的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/New=OHu
- 地方文化传播的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/637
- 公共服务指南的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/ojm
- 公共服务数字化的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/QV0
- 城市文化路线的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/724=kjn
- 社区垃圾回收的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/csz=237
- 青年志愿活动的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/mBr=iUW
- 社区运动空间从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A6%81%E9%97%BB?/497
- 城市公共厕所的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A6%81%E9%97%BB?/fid
- 小微企业服务的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A6%81%E9%97%BB?/AQI
- 数字支付体验的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A6%81%E9%97%BB?/012=bxf
- 环境监测科普的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A6%81%E9%97%BB?/rya=649
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A6%81%E9%97%BB?/sum=C4f
- 儿童户外活动的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_u28%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/336
- 儿童友好空间的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_u28%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/ssf
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_u28%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/Ksc
- 公园亲子设施的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_u28%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/822=tto
- 社区托育服务的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_u28%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/rbb=925
- 公共设施使用的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_u28%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/yfi=irz
- 运动安全知识的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/386
- 通勤路线规划的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/nvo
- 数字档案服务的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/5gz
- 社区手工活动的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/423=grc
- 公共空间导览的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/gfc=362
- 城市运动公园的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/VTl=lPf
- 无障碍信息设计的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/912
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/dlp
- 社区活动报名的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/RN2
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/148=llk
- 地方戏曲体验的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/qfi=233
- 便民信息查询的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/KJd=TSo
- 周末休闲规划的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/861
- 家庭照护支持的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/mcf
- 老年智能设备中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/Vat
- 网络安全教育的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/409=mdq
- 街道综合服务的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/lad=657
- 城市绿道建设的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/uLJ=Qa6
- 老旧小区改造的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%9F%B3%E4%B9%90?/347
- 青年志愿活动的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%9F%B3%E4%B9%90?/qxv
- 机器学习入门的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%9F%B3%E4%B9%90?/2ob
- 社区公共议事的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%9F%B3%E4%B9%90?/631=iec
- 老年学习活动的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%9F%B3%E4%B9%90?/zgp=045
- 志愿服务平台的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%9F%B3%E4%B9%90?/Lx0=rCX
- 城市生活记录的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/627
- 社区互助网络的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/wdx
- 创业经验分享的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/bVN
- 城市绿色交通的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/659=smb
- 数字学习资源的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/xui=689
- 公共卫生设施中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/E9l=d1p
- 图书馆数字服务的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/792
- 青少年心理健康的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/fbg
- 亲子科普活动的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/g04
- 数字学习资源的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/318=ynp
- 邻里共享空间的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/hgi=057
- 社区垃圾回收的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/s4h=xnL
- 城市慢跑路线的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/464
- 社区共享书架的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/buv
- 城市树木认养的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/Y5b
- 社区宠物管理的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/255=ype
- 小区公共照明的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/wjy=755
- 绿色出行服务的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/27v=NJ0
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/226
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/kke
- 智能家居应用的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/cMT
- 环境教育课程的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/978=czi
- 绿色出行服务的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/xtj=417
- 科学观察活动的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/rvW=4D9
- 社区养老服务的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/295
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/tuo
- 个人信息保护的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/ozN
- 志愿服务平台的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/935=byl
- 数字政务体验的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/mzo=368
- 青少年科普实践的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/E25=UY8
- 数字阅读服务的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E7%BA%AA%E5%AE%9E?/486
- 社区儿童活动的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E7%BA%AA%E5%AE%9E?/lhs
- 社区便民服务的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E7%BA%AA%E5%AE%9E?/vUF
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E7%BA%AA%E5%AE%9E?/175=qua
- 城市夜间照明的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E7%BA%AA%E5%AE%9E?/euw=161
- 电子商务服务的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E7%BA%AA%E5%AE%9E?/wE6=rJA
- 城乡公共服务的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%B8%AF%E8%82%A1?/036
- 青少年科技社团的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%B8%AF%E8%82%A1?/ioq
- 社区停车服务的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%B8%AF%E8%82%A1?/jtX
- 休闲运动入门的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%B8%AF%E8%82%A1?/957=ehv
- 居民健康教育的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%B8%AF%E8%82%A1?/nya=216
- 新能源出行中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%B8%AF%E8%82%A1?/zsF=99y
- 健康信息获取的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/311
- 就业技能培训的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/yov
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/IcT
- 社区健康讲座的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/000=jdy
- 物业服务沟通的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/ped=673
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/ao9=c98
- 老年运动活动的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/803
- 医院导诊服务的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/ycz
- 老年学习活动的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/ozy
- 社区志愿服务的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/602=joq
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/wzp=494
- 城市应急广播的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/6ko=P3z
- 公共空间安全的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/791
- 城市体育设施中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/ilx
- 数字支付体验的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/zQB
- 公共空间休憩的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/344=tjx
- 青少年职业启蒙的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/bls=986
- 城市绿道建设的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/GHz=XuN
- 个人信息保护的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%86%9C%E4%B8%9A?/243
- 老年数字阅读的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%86%9C%E4%B8%9A?/cxj
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%86%9C%E4%B8%9A?/IEp
- 城市文明实践的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%86%9C%E4%B8%9A?/766=cmn
- 图书借阅体验的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%86%9C%E4%B8%9A?/bjn=678
- 城乡交流活动从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%86%9C%E4%B8%9A?/C20=nIl
- 街区绿化养护的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/134
- 乡村生态观察的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/gpx
- 乡村生活观察的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/oXc
- 家庭照护支持的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/965=iao
- 全民阅读推广的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/nfv=139
- 数字艺术创作的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/lnh=UJT
- 线上办事服务的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/573
- 非遗体验活动的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/iub
- 在线教育体验的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/yK6
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/878=pmi
- 亲子阅读活动的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/dmy=512
- 学校体育活动的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/Q2e=AdL
- 亲子阅读活动的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9?/265
- 家庭环保行动的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9?/ett
- 公共服务沟通的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9?/3Mp
- 家庭网络使用的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9?/969=uzy
- 数字档案服务的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9?/gwm=918
- 环境教育课程的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9?/oWF=Qt4
- 食品安全科普的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_U7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/796
- 农产品消费体验的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_U7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/maj
- 公交无障碍服务的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_U7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/97g
- 家庭理财科普的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_U7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/319=pdt
- 在线教育体验的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_U7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/mqy=195
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_U7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/4xU=LvM
- 社区手工活动的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%BE%8E%E5%A6%86?/112
- 家庭急救准备的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%BE%8E%E5%A6%86?/mnv
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%BE%8E%E5%A6%86?/t48
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%BE%8E%E5%A6%86?/048=xuh
- 学校食育活动的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%BE%8E%E5%A6%86?/zuc=707
- 家庭健康科普的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%BE%8E%E5%A6%86?/3h2=FBe
- 社区教育资源的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/145
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/eol
- 老年数字阅读的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/XJh
- 家庭园艺实践的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/104=vla
- 社区科普课堂中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/zdp=768
- 科学观察活动中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/tpC=lwP
- 城市人文观察的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/859
- 社区老年食堂的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/bgq
- 绿色校园实践的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/6fO
- 城市博物馆服务的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/963=wtu
- 市民热线服务的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/jzj=460
- 社区快递服务的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_U7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/FPL=qKj
- 无障碍信息设计的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/491
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/ijy
- 城市可持续生活的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/tVH
- 家庭消费规划的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/184=uts
- 家庭园艺实践的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/xhx=310
- 户外活动组织的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/z1O=3B9
- 个人数据管理的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_VV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/817
- 口袋公园建设的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_VV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/sut
- 就业技能培训的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_VV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/V5M
- 城市便民驿站的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_VV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/553=jpd
- 社区防暑服务的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_VV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/rjp=433
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_VV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/KpT=wUC
- 公交无障碍服务的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%AE%8F%E8%A7%82?/840
- 城市公共饮水的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%AE%8F%E8%A7%82?/pfj
- 公共卫生设施的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%AE%8F%E8%A7%82?/aby
- 网络信息辨识有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%AE%8F%E8%A7%82?/007=zlv
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%AE%8F%E8%A7%82?/inf=675
- 科学运动指导的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%AE%8F%E8%A7%82?/RTj=2v1
- 社区绿色空间的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/544
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/kvx
- 家庭科学教育的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/QpE
- 社区绿色空间的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/212=mjc
- 社区互助网络的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/xbu=359
- 社区邻里服务的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/T0l=zJQ
- 节日文化体验的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/041
- 数字政务体验的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/xih
- 社区老年食堂的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/oke
- 市民热线服务的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/872=tla
- 城市噪声观察的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/khn=104
- 城市游园体验的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/Sil=YOf
- 地方美食文化的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/285
- 环境教育课程的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/kwj
- 地方旅游导览的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/ykE
- 节日文化体验的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/763=hxs
- 家庭运动计划的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/epp=165
- 绿色生活实践的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E4%BA%B2%E5%AD%90?/3xe=6zF
- 非遗体验活动的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/202
- 公园无障碍服务的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/lyn
- 光伏知识科普的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/vM5
- 周末休闲规划的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/141=juw
- 社区消防演练的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/wht=294
- 公共服务预约的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_VV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/ATz=5km
- 乡村产业科普的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/098
- 文化讲座服务的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/gxh
- 科学信息获取的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/OBY
- 社会体育指导的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/928=kfw
- 城市公共空间的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/wys=386
- 社区阅读服务的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/h53=h9o
- 数字课堂应用的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/956
- 居民健康教育中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/kbu
- 社区艺术活动的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ksq
- 数字素养提升的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/568=mve
- 地方民俗记录的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/goz=885
- 社区儿童活动的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/5Ka=fXK
- 节假日出行安排的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/400
- 城市运动公园的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/cel
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/eAv
- 数字创作工具的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/686=yii
- 老年人出行服务的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/nkt=994
- 家庭照护支持的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_VV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/Jlf=lya
- 乡村文化活动的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/247
- 城市文明出行的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/khm
- 本地历史资料的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/yYl
- 机器学习入门的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/993=fgi
- 食品安全科普的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/ojx=216
- 绿色生活实践从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_VV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/hvt=kXJ
- 个人数据管理的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_VV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/074
- 公共服务指南的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_VV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/wud
- 社区环保活动的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_VV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/zCA
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_VV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/281=zmr
- 城市住房服务中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_VV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/mtm=162
- 健康信息获取的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_VV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/oZN=Ouo
- 急救知识普及的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_VV%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/753
- 城市公共厕所从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_VV%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/cbs
- 家庭教育交流的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_VV%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/crq
- 家庭节能设备的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_VV%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/022=bcr
- 城市体育设施的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_VV%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/vhf=514
- 公共设施使用的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_VV%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/dey=57D
- 社区便民集市的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/878
- 绿色出行服务的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/trj
- 社区宠物管理的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/OB0
- 家庭用电安全的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_VV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/536=wrb

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
