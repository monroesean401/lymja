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

- 数字支付体验中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/gaq=129
- 家庭节能实践的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/6B6=Fze
- 网络信息辨识中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A93d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/613
- 校园节能行动从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A93d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/zcu
- 生活技能分享的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A93d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/Rm3
- 社区体育组织的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A93d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/544=sbe
- 社区商业活力的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A93d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/shv=788
- 基层健康服务的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A93d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/abf=gnu
- 乡村公共服务的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_3d%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/314
- 健康饮水科普的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_3d%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/xvo
- 社区便民服务的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_3d%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/lvk
- 公共空间导览的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_3d%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/679=eix
- 城市水环境观察的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_3d%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/pzy=090
- 地方文化传播的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_3d%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/XkD=1nJ
- 家庭阅读计划的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_3D%E5%92%8C%E5%80%BC_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/094
- 公益活动组织的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_3D%E5%92%8C%E5%80%BC_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/znh
- 绿色建筑理念的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_3D%E5%92%8C%E5%80%BC_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/ZpA
- 绿色校园实践的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_3D%E5%92%8C%E5%80%BC_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/075=stb
- 亲子阅读活动的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_3D%E5%92%8C%E5%80%BC_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/ccg=167
- 节能生活方式的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_3D%E5%92%8C%E5%80%BC_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/3vZ=pgl
- 口袋公园建设的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E5%92%8C%E5%80%BC_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/640
- 亲子阅读活动的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E5%92%8C%E5%80%BC_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/bmg
- 科学教育活动的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E5%92%8C%E5%80%BC_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/hlT
- 绿色快递包装的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E5%92%8C%E5%80%BC_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/195=tko
- 公共场所导视的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E5%92%8C%E5%80%BC_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/hyb=415
- 骑行路线规划的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E5%92%8C%E5%80%BC_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/TJY=d0J
- 老年友好服务的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E5%B0%BE3d_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/018
- 老年友好服务的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E5%B0%BE3d_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/fnw
- 青年职业探索的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E5%B0%BE3d_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/YmD
- 社区法律科普的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E5%B0%BE3d_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/734=kwe
- 公共交通接驳的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E5%B0%BE3d_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/ttk=641
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E5%B0%BE3d_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/kke=5ai
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3D%E5%92%8C%E5%80%BC%E6%8C%AF%E5%B9%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/966
- 节约用水实践的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3D%E5%92%8C%E5%80%BC%E6%8C%AF%E5%B9%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/smy
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3D%E5%92%8C%E5%80%BC%E6%8C%AF%E5%B9%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/e9e
- 家庭网络使用的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3D%E5%92%8C%E5%80%BC%E6%8C%AF%E5%B9%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/068=juj
- 乡村生态旅游的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3D%E5%92%8C%E5%80%BC%E6%8C%AF%E5%B9%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/tbf=752
- 公共空间照明的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3D%E5%92%8C%E5%80%BC%E6%8C%AF%E5%B9%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/M0i=bc3
- 公共服务预约的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_3d%E5%92%8C%E5%80%BC1000%E6%9C%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/401
- 公共交通信息服务的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_3d%E5%92%8C%E5%80%BC1000%E6%9C%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/ubu
- 城市便民驿站的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_3d%E5%92%8C%E5%80%BC1000%E6%9C%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/TfC
- 家庭照护支持的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_3d%E5%92%8C%E5%80%BC1000%E6%9C%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/690=dgp
- 城市绿道建设的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_3d%E5%92%8C%E5%80%BC1000%E6%9C%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/mrw=972
- 乡村教育资源的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_3d%E5%92%8C%E5%80%BC1000%E6%9C%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/4fN=5LL
- 家庭节能实践的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%BA%943d%E5%A4%A7%E5%B0%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/864
- 环境监测科普的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%BA%943d%E5%A4%A7%E5%B0%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/vmv
- 绿色建筑理念的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%BA%943d%E5%A4%A7%E5%B0%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/ilU
- 软件开发学习的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%BA%943d%E5%A4%A7%E5%B0%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/540=rcs
- 线上阅读资源的协商参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%BA%943d%E5%A4%A7%E5%B0%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/ebw=253
- 家庭养老规划的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%BA%943d%E5%A4%A7%E5%B0%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/5bZ=ien
- 市民意见收集的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_3d%E8%B7%A8%E5%BA%A6%E6%8C%AF%E5%B9%85_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/794
- 老旧小区改造的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_3d%E8%B7%A8%E5%BA%A6%E6%8C%AF%E5%B9%85_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/cyp
- 城市游园体验的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_3d%E8%B7%A8%E5%BA%A6%E6%8C%AF%E5%B9%85_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/5yr
- 机器学习入门的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_3d%E8%B7%A8%E5%BA%A6%E6%8C%AF%E5%B9%85_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/460=gsi
- 智慧城市体验的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_3d%E8%B7%A8%E5%BA%A6%E6%8C%AF%E5%B9%85_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/ycg=837
- 个人时间管理的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_3d%E8%B7%A8%E5%BA%A6%E6%8C%AF%E5%B9%85_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/8S1=MKN
- 乡村教育资源的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%85%A8%E5%9B%BE_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/695
- 乡村教育资源的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%85%A8%E5%9B%BE_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/asv
- 便民维修服务的协作机制梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%85%A8%E5%9B%BE_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/sQo
- 便民服务窗口的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%85%A8%E5%9B%BE_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/601=ygv
- 城市适老服务的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%85%A8%E5%9B%BE_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/gkl=731
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_3d%E5%92%8C%E5%80%BC%E8%A1%A8%E5%85%A8%E5%9B%BE_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/oiY=Ekw
- 本地旅行体验的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/465
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/sla
- 气象科普传播的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/ujw
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/243=bvs
- 消防知识宣传的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/ytj=375
- 灵活就业交流的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/yT1=TCN
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_3d%E4%BB%8A%E6%97%A5%E6%99%9A%E7%A7%8B%E5%92%8C%E5%80%BC%E8%B0%9C_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/836
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_3d%E4%BB%8A%E6%97%A5%E6%99%9A%E7%A7%8B%E5%92%8C%E5%80%BC%E8%B0%9C_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/cxp
- 社区防暑服务的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_3d%E4%BB%8A%E6%97%A5%E6%99%9A%E7%A7%8B%E5%92%8C%E5%80%BC%E8%B0%9C_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/7Pk
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_3d%E4%BB%8A%E6%97%A5%E6%99%9A%E7%A7%8B%E5%92%8C%E5%80%BC%E8%B0%9C_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/604=nex
- 社区环保活动的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_3d%E4%BB%8A%E6%97%A5%E6%99%9A%E7%A7%8B%E5%92%8C%E5%80%BC%E8%B0%9C_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/wxd=346
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_3d%E4%BB%8A%E6%97%A5%E6%99%9A%E7%A7%8B%E5%92%8C%E5%80%BC%E8%B0%9C_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/6Kk=mIx
- 城市地名文化的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/758
- 城市公共艺术的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/cjo
- 社区公共卫生的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/7hl
- 家庭网络使用的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/568=hpf
- 家庭养老规划的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/poh=256
- 绿色消费选择的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E5%B0%BE%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/swT=rgo
- 城乡交通衔接的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E6%8A%95%E6%B3%A8%E8%A1%A8%E9%87%91%E9%A2%9D_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/809
- 城市社区治理的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E6%8A%95%E6%B3%A8%E8%A1%A8%E9%87%91%E9%A2%9D_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/ziv
- 骑行路线规划的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E6%8A%95%E6%B3%A8%E8%A1%A8%E9%87%91%E9%A2%9D_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/hty
- 城市环境志愿行动的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E6%8A%95%E6%B3%A8%E8%A1%A8%E9%87%91%E9%A2%9D_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/423=arx
- 地方旅游导览的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E6%8A%95%E6%B3%A8%E8%A1%A8%E9%87%91%E9%A2%9D_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/wfp=341
- 社区公共议事的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3d%E5%92%8C%E5%80%BC%E6%8A%95%E6%B3%A8%E8%A1%A8%E9%87%91%E9%A2%9D_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/Uqk=ysa
- 城市慢行系统的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_3d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/499
- 城市夜间生活的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_3d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/myd
- 社区老年食堂的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_3d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/Cw1
- 城市人文观察的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_3d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/980=kuy
- 城市噪声观察的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_3d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/uwj=359
- 市民热线服务的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_3d%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A1%A8%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/wMi=8kQ
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E4%BB%8A%E6%99%9A3d%E5%92%8C%E5%80%BC%E9%87%8D%E7%82%B9%E5%92%8C%E5%80%BC_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/999
- 儿童安全出行的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E4%BB%8A%E6%99%9A3d%E5%92%8C%E5%80%BC%E9%87%8D%E7%82%B9%E5%92%8C%E5%80%BC_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/mwb
- 社区商业活力的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E4%BB%8A%E6%99%9A3d%E5%92%8C%E5%80%BC%E9%87%8D%E7%82%B9%E5%92%8C%E5%80%BC_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/hJ1
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E4%BB%8A%E6%99%9A3d%E5%92%8C%E5%80%BC%E9%87%8D%E7%82%B9%E5%92%8C%E5%80%BC_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/247=hpb
- 老年学习活动的资源利用方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E4%BB%8A%E6%99%9A3d%E5%92%8C%E5%80%BC%E9%87%8D%E7%82%B9%E5%92%8C%E5%80%BC_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/yfm=534
- 家庭教育交流的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E4%BB%8A%E6%99%9A3d%E5%92%8C%E5%80%BC%E9%87%8D%E7%82%B9%E5%92%8C%E5%80%BC_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/9ax=QEw
- 食品配送体验的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3d%E5%92%8C%E5%80%BC%E8%A1%A8%28%E5%9B%BE%E7%89%87%29_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/685
- 家庭照护支持中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3d%E5%92%8C%E5%80%BC%E8%A1%A8%28%E5%9B%BE%E7%89%87%29_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/pqd
- 家庭志愿活动的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3d%E5%92%8C%E5%80%BC%E8%A1%A8%28%E5%9B%BE%E7%89%87%29_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/Qtz
- 节约用水实践的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3d%E5%92%8C%E5%80%BC%E8%A1%A8%28%E5%9B%BE%E7%89%87%29_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/757=jsy
- 公共卫生宣传的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3d%E5%92%8C%E5%80%BC%E8%A1%A8%28%E5%9B%BE%E7%89%87%29_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/uvo=229
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3d%E5%92%8C%E5%80%BC%E8%A1%A8%28%E5%9B%BE%E7%89%87%29_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/JPN=Ife
- 线上阅读资源的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/070
- 校园安全教育的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/ghj
- 社区信息发布的公共参与指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/yKj
- 读书会组织的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/864=vwk
- 个人时间管理的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/wiw=288
- 老年人日常照护的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/3lj=yR9
- 网络信息辨识的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/103
- 文明养宠科普的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/zsp
- 社区法律科普的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/Fpm
- 农产品品牌传播的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/923=hhq
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/jhd=199
- 乡村文化空间的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/E8b=Z98
- 老年人日常照护的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E9%87%87%E9%9B%86%E9%87%8D%E7%82%B9%E8%AF%8D_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/994
- 社区应急准备的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E9%87%87%E9%9B%86%E9%87%8D%E7%82%B9%E8%AF%8D_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/rtf
- 农业科普体验的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E9%87%87%E9%9B%86%E9%87%8D%E7%82%B9%E8%AF%8D_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/7CZ
- 城市地名文化的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E9%87%87%E9%9B%86%E9%87%8D%E7%82%B9%E8%AF%8D_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/065=ecl
- 青年就业服务的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E9%87%87%E9%9B%86%E9%87%8D%E7%82%B9%E8%AF%8D_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/nst=181
- 家庭环保行动的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E9%87%87%E9%9B%86%E9%87%8D%E7%82%B9%E8%AF%8D_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/m7v=erM
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/647
- 社区文化传播的日常管理方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/mpr
- 农业科普体验的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/ygG
- 社区体育组织的空间使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/231=msx
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/uhi=639
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/KyO=eYk
- 节能生活方式的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/402
- 社区商业活力的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/yed
- 城市博物馆服务的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/g8Y
- 科学运动指导的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/338=jwh
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/xnx=869
- 开源技术交流的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/vY5=yRA
- 电动汽车充电的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88_%E7%95%8C%E9%9D%A2%E7%9B%98%E7%82%B9?/700
- 城市夜间照明的活动策划思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88_%E7%95%8C%E9%9D%A2%E7%9B%98%E7%82%B9?/vyl
- 公共卫生宣传的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88_%E7%95%8C%E9%9D%A2%E7%9B%98%E7%82%B9?/x6m
- 城市人文观察的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88_%E7%95%8C%E9%9D%A2%E7%9B%98%E7%82%B9?/117=yst
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88_%E7%95%8C%E9%9D%A2%E7%9B%98%E7%82%B9?/imk=230
- 健康信息获取的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88_%E7%95%8C%E9%9D%A2%E7%9B%98%E7%82%B9?/xYn=1DD
- 儿童友好空间的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/225
- 家庭节能设备的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/tzi
- 居家适老化改造的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/XW5
- 城市应急科普的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/527=ufm
- 数字资源检索的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/mpm=802
- 城市社区治理从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/Y0f=4T4
- 城市农夫市集的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91-%E4%BF%A1%E8%AA%89-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/959
- 科学睡眠习惯的服务体验观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91-%E4%BF%A1%E8%AA%89-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/gud
- 城市文化路线的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91-%E4%BF%A1%E8%AA%89-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/o2e
- 社区应急准备的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91-%E4%BF%A1%E8%AA%89-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/879=nhj
- 儿童阅读角的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91-%E4%BF%A1%E8%AA%89-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/tqf=644
- 数字设备回收的流程优化思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91-%E4%BF%A1%E8%AA%89-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/SCF=Q6y
- 校园节能行动的活动组织技巧 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/476
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/uuf
- 气象科普传播的长期维护要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/tTq
- 城乡公共服务的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/060=zyz
- 在线教育体验的服务范围梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/jpe=948
- 在线学习体验的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/9Bi=w1g
- 个人信息保护的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%9C%9F%E9%BB%91_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/824
- 老年人文化生活的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%9C%9F%E9%BB%91_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/nna
- 节日文化体验的设施维护观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%9C%9F%E9%BB%91_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/8NQ
- 家庭饮食安排的执行流程参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%9C%9F%E9%BB%91_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/846=bob
- 基层健康服务的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%9C%9F%E9%BB%91_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/vsm=415
- 食品安全科普的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%9C%9F%E9%BB%91_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/zE9=Iur
- 城市住房服务的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/472
- 校园节能行动的服务细节记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/lwe
- 家庭运动计划的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/BSh
- 气象科普传播的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/585=grw
- 社区志愿服务的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/uqq=392
- 健康饮水科普的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/YXE=fh9
- 小区电梯维护的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/177
- 老年运动活动的公共信息获取方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/jhu
- 休闲运动入门的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/z1t
- 读书会组织的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/278=xzl
- 城市生活记录的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/glz=130
- 城市公共艺术的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/kNQ=Ly9
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/410
- 公共服务预约的日常实践笔记 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/viz
- 数字政务体验的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/MlI
- 老旧小区改造的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/973=vgq
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/yij=694
- 社区设施共享的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/1Nn=cX6
- 社区共享书架的实际需求与回应 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E7%BD%91%E5%9D%80_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/596
- 地方美食文化中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E7%BD%91%E5%9D%80_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/pbp
- 骑行路线规划的资源整合思路 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E7%BD%91%E5%9D%80_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/i3P
- 社区环保活动的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E7%BD%91%E5%9D%80_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/591=owp
- 图书借阅体验的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E7%BD%91%E5%9D%80_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/mfh=155
- 社区修缮行动的便利性观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E7%BD%91%E5%9D%80_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/NNs=kaJ
- 公共卫生设施的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/260
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/lpy
- 社区环保活动的服务反馈渠道 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/dyP
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/063=fko
- 数字设备回收的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/oze=292
- 数字资源检索的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/rOZ=Lxm
- 社区心理支持的参与方式与路径 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%BE%A4%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/446
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%BE%A4%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/zyz
- 城市公共厕所的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%BE%A4%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/iOR
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%BE%A4%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/640=wml
- 终身学习资源的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%BE%A4%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/glj=749
- 运动安全知识的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%BE%A4%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/4ys=wjM
- 基层健康档案的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/120
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/kfs
- 社区活动报名的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/FkM
- 儿童运动体验的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/087=bbl
- 社区安全巡查的持续改进方向 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/tps=651
- 城乡交流活动中的几个关键细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A3%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/5kv=Kde
- 家庭理财科普的学习资源整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/037
- 乡村电商实践的数字工具使用体验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/cnd
- 社区互助网络的绿色实践方法 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/8M3
- 小区停车协商的服务信息整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/676=zfn
- 城市绿道建设的日常记录与分享 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/evi=907
- 城市噪声观察的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/85q=36X
- 文化场馆预约的行动步骤参考 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/024
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/nkm
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/T3Q
- 健康步道使用的线下体验记录 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/831=ncs
- 数字创作工具的组织方法与经验 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/hsu=526
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/ecf=OIz
- 城市可持续生活的常见问题梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_10%E5%85%83%E6%8A%95%E8%B5%84%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/632
- 公交站点体验的家庭参与方式 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_10%E5%85%83%E6%8A%95%E8%B5%84%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/llx
- 老年人日常照护的空间设计要点 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_10%E5%85%83%E6%8A%95%E8%B5%84%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/NOh
- 社区垃圾回收的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_10%E5%85%83%E6%8A%95%E8%B5%84%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/665=uza
- 应急物资管理的社区行动案例 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_10%E5%85%83%E6%8A%95%E8%B5%84%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/ytf=763
- 社区设施共享的基础设施观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_10%E5%85%83%E6%8A%95%E8%B5%84%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/503=aSt
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/046
- 读书会组织从使用体验看服务改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/dsa
- 儿童友好街区的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/y1n
- 机器人科普活动的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/687=iag
- 公共设施维护的数字化应用观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/guv=885
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/nSO=c4d
- 绿色办公实践的社区参与观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/064
- 公共场所导视的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/ine
- 社区修缮行动的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/8M3
- 基层服务创新的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/562=hyo
- 文明养宠科普的便捷程度观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/dbd=915
- 地方旅游导览的便民做法梳理 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/6mR=Q2C
- 社区消防演练的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/791
- 社区停车服务的使用门槛与改进 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/hci
- 老年运动活动的安全使用提示 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/Mmm
- 家庭陪伴活动的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/021=zyk
- 公共图书馆服务的适老服务细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/lbj=910
- 城市空气科普的阅读与学习资源 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/YAX=Yla
- 城市运动公园的服务质量观察 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_app%E6%B3%A8%E5%86%8C%E5%BD%A9%E9%87%9138%E4%B8%8B_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/487
- 乡村公共文化的入门知识整理 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_app%E6%B3%A8%E5%86%8C%E5%BD%A9%E9%87%9138%E4%B8%8B_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/ecc
- 城市公共饮水的日常使用指南 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_app%E6%B3%A8%E5%86%8C%E5%BD%A9%E9%87%9138%E4%B8%8B_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/tie
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_app%E6%B3%A8%E5%86%8C%E5%BD%A9%E9%87%9138%E4%B8%8B_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/770=yfk
- 城市骑行环境的实用信息清单 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_app%E6%B3%A8%E5%86%8C%E5%BD%A9%E9%87%9138%E4%B8%8B_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/zta=523
- 机器人科普活动的儿童友好细节 |来源：https://github.com/cruzvickie15/kypc/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_app%E6%B3%A8%E5%86%8C%E5%BD%A9%E9%87%9138%E4%B8%8B_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/vwv=H1L
- 青少年科技社团的居民参与机会 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E4%BA%BA%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C%E9%80%8138%E5%BD%A9%E9%87%91_%E7%95%8C%E9%9D%A2%E6%B1%87%E5%B8%82?/333
- 社区儿童活动的基础知识问答 |来源：https://github.com/cruzvickie15/kypc/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%96%B0%E4%BA%BA%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C%E9%80%8138%E5%BD%A9%E9%87%91_%E7%95%8C%E9%9D%A2%E6%B1%87%E5%B8%82?/nrw

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
