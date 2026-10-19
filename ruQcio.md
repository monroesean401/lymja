# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 城市公共标识的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%A6%81%E9%97%BB?/943
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%A6%81%E9%97%BB?/cao
- 小区电梯维护的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%A6%81%E9%97%BB?/hap
- 社区手工活动的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%A6%81%E9%97%BB?/320=qyl
- 在线教育体验的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%A6%81%E9%97%BB?/eax=849
- 农贸市场环境的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%A6%81%E9%97%BB?/ULN=sFQ
- 老旧小区改造的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/634
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/xxx
- 乡村文化活动的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/wLo
- 老年智能设备的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/925=naw
- 家庭食品保存的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/gyn=965
- 绿色办公实践的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/DBO=B1w
- 气象科普传播的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/024
- 灵活就业交流的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/uew
- 家庭阅读计划的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/0mR
- 科学观察活动有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/882=tmy
- 小区电梯维护的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/jjo=489
- 本地旅行体验的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/FSd=ndP
- 食品配送体验的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/981
- 基层医疗预约的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/nss
- 城市公共空间的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/K5H
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/205=uuv
- 校园社团活动的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/ges=934
- 智慧城市体验的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/bVr=T2L
- 社区信息发布中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/372
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/jsv
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/wom
- 公共设施使用中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/047=rxy
- 社区读书角建设的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/cdh=617
- 课后服务体验的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/xDM=7ls
- 乡村生活观察的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/838
- 校园阅读活动的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/del
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/2ly
- 课后服务体验的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/654=ojl
- 城乡交通衔接的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/rfa=064
- 家庭科学教育的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/VOr=FvD
- 生成式工具使用的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/074
- 节约用水实践的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/vrs
- 城市运动公园的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/T2Z
- 物业服务沟通的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/993=bfo
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/cze=498
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/BHN=l9h
- 文化场馆预约的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/617
- 城市博物馆活动的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/mon
- 节日文化体验的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/tLz
- 绿色生活实践的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/028=hmy
- 街区更新实践的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/bne=267
- 校园节能行动的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/ycO=ZuN
- 城市噪声观察的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/313
- 城市体育设施的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/yid
- 环境教育课程的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/8TE
- 城市社区治理的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/526=pak
- 周末休闲规划从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/nrm=689
- 城乡公共服务的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/TUi=R96
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/621
- 城市文化路线的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/jbc
- 社区协商议事的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/rRf
- 城市可持续生活的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/221=ltc
- 社区修缮行动的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/osi=853
- 社区文化节活动的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/v3k=T5C
- 公共交通信息服务的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/185
- 市民热线服务的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/gri
- 家庭健康科普的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/ISr
- 在线学习体验的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/198=xtf
- 新能源出行的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/mpc=869
- 家庭环保行动的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A6%81%E9%97%BB?/PcX=W6X
- 城市地名文化的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/097
- 儿童阅读角的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/fgn
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/mUh
- 家庭消费规划的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/825=lqq
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/zaq=753
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/jBQ=hzB
- 社区运动空间的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/564
- 城市应急广播的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/bas
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/CoY
- 地方文化传播的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/298=oam
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/skw=562
- 居民健康教育的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/wMB=Ft2
- 家庭用电安全的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/009
- 城市博物馆服务的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/lmr
- 老年数字阅读的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/Yvb
- 骑行路线规划的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/057=xrk
- 城市休闲步道的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/gzq=157
- 老年运动活动的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/CH1=OBS
- 安全出行教育的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/345
- 社区学习活动的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/hjh
- 家庭阅读计划的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/svC
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/106=ksj
- 绿色校园实践的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/xbo=047
- 生活服务数字化的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/cuR=8UP
- 口袋公园建设的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/542
- 职业技能学习的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/trq
- 数字创意课程中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/rcC
- 安全出行教育的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/183=woa
- 家庭收纳实践的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/svj=683
- 社区健康讲座的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/qua=p0f
- 城市游园体验的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/991
- 数字便民地图的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/hqq
- 家庭食品保存的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/imr
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/098=wdr
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/dzk=320
- 儿童安全出行的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/bLQ=RlI
- 智能手机助老的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/092
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/hbt
- 科学教育活动的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/2lO
- 社区教育资源的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/802=zoq
- 社区花园共建的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/dzd=740
- 公益活动组织中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/VbA=Ok4
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/874
- 亲子科普活动的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/opj
- 传统节日科普的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/qZU
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/564=aid
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/tjw=092
- 乡村电商实践的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/zsU=UbS
- 家庭节能实践的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/740
- 节能生活方式的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/flo
- 公园休闲体验的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/WFP
- 本地历史资料的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/477=ngb
- 基层医疗预约的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/hwx=809
- 社区活动策划的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/yGz=bCB
- 市民热线服务的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/762
- 城市地名文化的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/mzq
- 消防知识宣传的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/z84
- 家庭环保行动的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/537=hsy
- 小区公共照明的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/tiu=226
- 本地消费场景的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/rE9=g2k
- 社区学习活动的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/841
- 光伏知识科普的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/did
- 家庭急救准备的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/iFX
- 数字便民地图的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/582=wlz
- 全民健身活动的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/koy=528
- 校园节能行动从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/KcS=c0Y
- 地方民俗记录的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/218
- 乡村公共服务的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/mtv
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/J7r
- 乡村电商实践的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/847=ati
- 电子商务服务的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/bau=285
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/JjZ=6pe
- 基层医疗预约中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/176
- 在线教育体验的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/iij
- 网络安全教育的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/A1t
- 非遗体验活动的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/508=qjq
- 基层健康档案的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/crh=236
- 老旧小区改造的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/M7F=Y1J
- 儿童安全出行的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/918
- 老年人文化生活的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/siv
- 城市文明出行的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/Ise
- 绿色消费选择的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/644=ofh
- 小区停车协商的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/qln=894
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/4Cl=0Bw
- 公共健身器材的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/925
- 家庭急救准备的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/nti
- 社区协商议事的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/mLC
- 食品配送体验的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/705=zkb
- 户外活动组织中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/nbq=378
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/oPr=hNd
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/822
- 社会体育指导的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/hey
- 社区知识分享的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/gmS
- 街道综合服务的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/319=hah
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/wfd=381
- 职业技能学习的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/tcV=7sW
- 校园安全教育的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%94%BE?/584
- 课后服务体验的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%94%BE?/kvd
- 科学教育活动中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%94%BE?/nGE
- 生活垃圾减量的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%94%BE?/775=jxr
- 本地历史资料的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%94%BE?/ufw=930
- 社区休闲设施的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%9B%9E%E6%94%BE?/rcT=mBs
- 家庭用电安全的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/498
- 数字创意课程的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/kdz
- 青少年心理健康的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/nXc
- 科技馆参观体验的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/494=avr
- 城市文明实践的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/nya=266
- 创业经验分享的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/6hd=CWx
- 基层医疗预约的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/613
- 家庭园艺实践的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/pah
- 城市公共座椅的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/MhT
- 城市骑行环境的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/349=jmz
- 科学教育活动的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/srv=563
- 校园节能行动的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/r8P=tOO
- 街区小店体验的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/093
- 数字档案服务的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/gds
- 便民信息查询的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/QJi
- 绿色生活实践中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/315=cjg
- 垃圾分类指导的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/wjd=964
- 社区庭院绿化的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/mGh=Xxp
- 健康饮水科普的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/535
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/pnd
- 社区慢性病防控的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/mm3
- 全民健身活动的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/490=gta
- 青少年科技社团的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/sxz=345
- 居家适老化改造的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/ANU=raN
- 乡村文化活动的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/084
- 家庭阅读计划的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/osu
- 物业服务沟通的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/HHJ
- 居家防滑改造的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/499=wyt
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/rqp=754
- 图书借阅体验中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/Qv5=Ry3
- 公共空间安全的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/776
- 社区教育资源的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/qkd
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/jXf
- 乡村产业科普的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/892=ihl
- 绿色消费选择的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/qbc=329
- 家庭健康管理中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/KFe=4mB
- 口袋公园建设的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E5%85%AC%E5%BC%80%E8%AF%BE?/769
- 创业经验分享的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E5%85%AC%E5%BC%80%E8%AF%BE?/syn
- 老年人出行服务的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E5%85%AC%E5%BC%80%E8%AF%BE?/a0Y
- 老年运动活动的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E5%85%AC%E5%BC%80%E8%AF%BE?/020=wan
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E5%85%AC%E5%BC%80%E8%AF%BE?/pgu=780
- 文化场馆预约的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E5%85%AC%E5%BC%80%E8%AF%BE?/Qkc=ag9
- 电子商务服务的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/981
- 城市人文观察的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/myq
- 家庭环保行动的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/CsI
- 公共空间导览的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/073=hms
- 图书馆活动策划的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/fzr=219
- 绿色建筑理念的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/7ty=Fr4
- 乡村公共服务的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/385
- 城市文化路线的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/hae
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/J1Z
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/627=fch
- 城市文明实践的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/bfv=909
- 社区垃圾回收的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/7zQ=40N
- 智慧停车服务的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/049
- 科普展览体验的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/vhn
- 就业技能培训的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/TJF
- 儿童阅读角的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/128=uwm
- 城乡交流活动的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/rtn=166
- 社区安全巡查的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/pWV=lTy
- 社区科普课堂的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/513
- 本地消费场景的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/bky
- 物业服务沟通的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/OVp
- 无障碍出行的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/016=hju
- 户外活动组织中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/vuu=252
- 本地旅行体验的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/EJq=c1s
- 社区便利生活的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/720
- 线上办事服务的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/fso
- 社区便利生活的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/ZF7
- 公共服务沟通的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/025=kbw
- 图书馆活动策划的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/okg=763
- 公共服务咨询的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/UU5=toK
- 家庭照护支持的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/145
- 社区健康讲座的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/bzb
- 公共场馆服务的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/oy3
- 城市骑行环境的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/374=kyz
- 城市共享单车的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/puj=126
- 居家防滑改造的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/9oi=QJh
- 创业经验分享的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/433
- 青年职业探索的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/aja
- 节约用水实践的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/uDB
- 创业经验分享的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/760=cni

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
