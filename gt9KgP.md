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

- 食品安全科普的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/4PV
- 口袋公园建设的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/501=dqs
- 家庭食品保存的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/kui=094
- 社区文化传播的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/Gso=5tb
- 社区宣传栏更新的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/881
- 休闲运动入门的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/fzh
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/rEZ
- 城市步行友好的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/033=rwr
- 口袋公园建设中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/vrz=540
- 社区心理支持的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/ow0=Iro
- 家庭急救准备的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/181
- 健康信息获取的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/kya
- 线上阅读资源的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/G4t
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/858=khn
- 城市人文观察的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/tjy=251
- 户外活动组织的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/i9G=CSD
- 本地历史资料的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%BF%A1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/769
- 校园社团活动的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%BF%A1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/twz
- 街头绿植养护的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%BF%A1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/ybj
- 街区小店体验的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%BF%A1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/933=szd
- 环境监测科普的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%BF%A1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/ank=724
- 数字公共文化的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%BF%A1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/7hc=T2e
- 青年志愿活动的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E4%BF%A1-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/113
- 城乡公共服务的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E4%BF%A1-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/svu
- 绿色出行服务的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E4%BF%A1-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/h3s
- 街区更新实践的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E4%BF%A1-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/860=aio
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E4%BF%A1-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/quo=959
- 城市雨天出行的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E4%BF%A1-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/QYa=O9R
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/522
- 家庭科学教育的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/vea
- 数字学习资源的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/U2y
- 青少年户外教育的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/806=wtv
- 城市空气科普的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/uej=527
- 街区道路维护的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/tur=8yD
- 周末休闲规划的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/346
- 社区垃圾回收的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/fiq
- 食品安全科普的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/IJA
- 老年人文化生活的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/694=znu
- 本地旅行体验的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/wyy=998
- 社区邻里服务的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/gyW=MfH
- 城市共享单车的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/794
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/blf
- 农贸市场环境的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/c9O
- 乡村电商实践的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/105=eek
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/sdm=803
- 户外活动组织的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/nqN=h0v
- 城乡交通衔接的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/548
- 软件开发学习的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/owg
- 绿色生活实践的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/SCI
- 地方美食文化的居民参与机会 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/293=oob
- 图书馆活动策划的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/gos=720
- 社区应急准备的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/1ad=cL0
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E4%BF%A1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/817
- 低碳社区实践的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E4%BF%A1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/rvr
- 本地消费场景的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E4%BF%A1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/Jk5
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E4%BF%A1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/549=hca
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E4%BF%A1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/jta=537
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E4%BF%A1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/O8e=PCU
- 乡村文化空间的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/095
- 网络安全教育的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/zup
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/ZGl
- 老年人文化生活的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/565=kfy
- 个人信息保护的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/lhy=005
- 城市共享单车的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/wOe=B3P
- 安全出行教育的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/113
- 基层服务创新的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/kqu
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/lsS
- 公共服务预约的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/202=tpo
- 职业技能学习的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/upl=843
- 城市应急科普的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/9eo=l0x
- 城市适老服务的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%BF%A1-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/581
- 就业技能培训的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%BF%A1-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/nnj
- 城市共享单车的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%BF%A1-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/Em3
- 小区停车协商的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%BF%A1-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/325=aex
- 软件开发学习的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%BF%A1-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/lpc=005
- 校园节能行动的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%BF%A1-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/4L1=nqJ
- 社区快递服务的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BD%A9%E4%BF%A1-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%9C%AD%E8%AE%B0?/873
- 家庭运动计划的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BD%A9%E4%BF%A1-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%9C%AD%E8%AE%B0?/osa
- 城市绿道建设的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BD%A9%E4%BF%A1-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%9C%AD%E8%AE%B0?/6KJ
- 生活技能分享的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BD%A9%E4%BF%A1-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%9C%AD%E8%AE%B0?/747=fvw
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BD%A9%E4%BF%A1-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%9C%AD%E8%AE%B0?/xra=278
- 公共卫生宣传的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BD%A9%E4%BF%A1-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%9C%AD%E8%AE%B0?/7fO=9DR
- 社区商业活力的活动策划思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-APP_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/639
- 公共交通信息服务的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-APP_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/vjr
- 个人数据管理的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-APP_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/Zix
- 网络安全教育的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-APP_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/891=kgh
- 青少年科普实践的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-APP_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/fmc=682
- 居民健康教育的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-APP_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/Mku=f2c
- 青少年户外教育的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E4%BF%A1-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/546
- 健康步道使用的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E4%BF%A1-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/mfk
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E4%BF%A1-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/UAq
- 儿童户外活动的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E4%BF%A1-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/889=ikm
- 健康信息获取的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E4%BF%A1-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/phk=373
- 社区交通安全的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E4%BF%A1-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/sMz=Vtl
- 社区法律科普的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%BF%A1-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/183
- 城市运动公园的日常实践笔记 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%BF%A1-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/dpa
- 便民服务窗口的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%BF%A1-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/x5z
- 乡村文化活动的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%BF%A1-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/978=hpf
- 城市生活记录的设施维护观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%BF%A1-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/cyg=912
- 健康饮水科普的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%BF%A1-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/Frj=5V4
- 气象科普传播的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/355
- 灵活就业交流的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/fzq
- 本地历史资料的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/zMa
- 城市夜间生活的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/445=tcq
- 机器人科普活动的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/ujg=681
- 食品安全科普的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E4%BF%A1-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/iAd=U1p
- 社区生活指南的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/337
- 乡村教育资源的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/ycd
- 机器人科普活动的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/Cor
- 公益活动组织的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/699=wqo
- 城市慢行系统的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/scb=141
- 日常摄影记录中的几个关键细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E4%BF%A1-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/DNR=vYD
- 在线教育体验的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E4%BF%A1-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/650
- 音乐欣赏活动的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E4%BF%A1-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/kuy
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E4%BF%A1-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/q8m
- 城市体育设施的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E4%BF%A1-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/785=xpr
- 环境监测科普的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E4%BF%A1-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/nra=434
- 城市生活服务的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E4%BF%A1-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/Kk1=gvC
- 个人时间管理的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%BF%A1-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/723
- 家庭急救准备的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%BF%A1-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/gvk
- 数字学习资源的空间使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%BF%A1-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/OYS
- 社区安全巡查的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%BF%A1-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/912=iqa
- 社区应急准备的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%BF%A1-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/zuz=889
- 城市游园体验的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%BF%A1-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/t13=gaV
- 健康饮食教育的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E4%BF%A1-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/732
- 社区老年食堂的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E4%BF%A1-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/dna
- 城市绿道建设的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E4%BF%A1-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/HUf
- 社区托育服务的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E4%BF%A1-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/557=hbc
- 城市人文观察的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E4%BF%A1-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/pbb=735
- 户外活动组织的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E4%BF%A1-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/IAb=LbY
- 绿色办公实践的绿色实践方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%BF%A1-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A6%81%E9%97%BB?/582
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%BF%A1-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A6%81%E9%97%BB?/afq
- 智能家居应用的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%BF%A1-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A6%81%E9%97%BB?/p5e
- 家庭阅读计划的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%BF%A1-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A6%81%E9%97%BB?/197=blf
- 便民信息查询的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%BF%A1-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A6%81%E9%97%BB?/sel=307
- 数字便民地图的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%BF%A1-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A6%81%E9%97%BB?/kGR=qKl
- 社区环保活动的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%BF%A1-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/726
- 网络安全教育的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%BF%A1-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/ick
- 智能手机助老的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%BF%A1-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/sFC
- 城乡交通衔接的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%BF%A1-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/554=izm
- 绿色校园实践的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%BF%A1-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/zpl=417
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%BF%A1-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/rkS=uhr
- 老年运动活动的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/833
- 低碳社区实践的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/jsg
- 健康信息获取的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/yI2
- 课后服务体验的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/837=hxo
- 城市文明出行的资源利用方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/bcb=916
- 市民意见收集的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/hd2=Eba
- 节能家电使用的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/763
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/pvi
- 城市骑行环境的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/vl9
- 地方美食文化的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/082=fkw
- 网络安全教育的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/fid=262
- 健康步道使用的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/A1F=r39
- 家庭科学教育的服务信息整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/590
- 数字生活课堂的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/lbo
- 家庭食品保存的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/jCg
- 网络信息辨识的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/296=cye
- 数字公共文化有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/csp=788
- 社区庭院绿化的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/P1S=IYe
- 城乡交通衔接的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/831
- 街区小店体验的协商参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/twq
- 居民健康教育的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/enL
- 亲子科普活动的行动步骤参考 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/960=fhx
- 无障碍信息设计的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/pkq=352
- 信息无障碍体验的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/rru=CEV
- 城市噪声观察的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/439
- 老年学习活动的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/nrh
- 线上阅读资源的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/sFI
- 家庭网络使用的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/944=jwe
- 家庭阅读计划的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/klx=120
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/IRL=A3n
- 农产品消费体验的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/009
- 城市步行环境的日常记录与分享 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/zpd
- 城市树木认养的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/XpO
- 食品配送体验的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/588=wpp
- 社区设施共享的空间设计要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/zki=666
- 公共空间休憩的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/CMZ=SAs
- 小区停车协商的活动组织技巧 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/907
- 生活垃圾减量的服务质量观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/gxj
- 社区共享书架的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/HEW
- 小微企业服务的社区行动案例 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/836=ycj
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/opz=432
- 全民健身活动的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/WC1=UW0
- 街区小店体验的执行流程参考 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/721
- 城市共享单车的便捷程度观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/vwq
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/Fch
- 乡村电商实践的线下体验记录 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/545=kai
- 休闲运动入门的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/gva=359
- 就业技能培训的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/aab=6uJ
- 公共服务评价的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/242
- 青年职业探索的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/cjt
- 数字档案服务的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/8lv
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/393=yva
- 城市慢行系统的常见误区提醒 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/pht=928
- 无障碍出行的适老服务细节 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/MYL=5bb
- 城市人文观察的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/210
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/oee
- 乡村公共阅读的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/1r9
- 城市空气科普的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/830=oik
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/fhz=695
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/ZML=KxT
- 科普展览体验的流程优化思路 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/270
- 社会体育指导的常见问题梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/dnw
- 家庭收纳实践的学习资源整理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/rx7
- 城市休闲步道的实际需求与回应 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/365=ogs
- 智慧城市体验的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/yle=661
- 社区公共卫生的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/FGw=1ZP
- 城市游园体验的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/417
- 电动汽车充电的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/rup
- 城市夜间生活中的沟通与协作 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/9dt
- 本地旅行体验的日常管理方法 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/171=fzi
- 节日文化体验的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/mdu=581
- 农村环境治理的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/6bW=9OG
- 家庭阅读计划的安全使用提示 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/796
- 城市噪声观察的协作机制梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/ddv
- 城市社区治理的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/sr7
- 安全出行教育有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/419=piy
- 无障碍出行的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/pfm=500
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/frc=jvS
- 通勤路线规划的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/324
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/rdy
- 旧物循环利用的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/cvz
- 乡村公共服务的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/156=fao
- 非遗体验活动的服务体验观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/jgm=419
- 社区健康讲座的家庭实践清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/AKU=a3N
- 家庭安全提示的组织方法与经验 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%83%AD%E6%A6%9C?/813
- 物业服务沟通的数字化应用观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%83%AD%E6%A6%9C?/fxk
- 家庭节能实践的基础设施观察 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%83%AD%E6%A6%9C?/Otn
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%83%AD%E6%A6%9C?/110=caq
- 数字设备回收的儿童友好细节 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%83%AD%E6%A6%9C?/fmn=750
- 城市体育设施的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%83%AD%E6%A6%9C?/D5M=7q6
- 社区商业活力的持续改进方向 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/124
- 节能生活方式的基础知识问答 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/owz
- 城市生活服务的服务范围梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/XET
- 社区宠物管理的长期维护要点 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/217=ffs
- 公共服务沟通的公共参与指南 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/daf=983
- 校园节能行动的阅读与学习资源 |来源：https://github.com/vargasraymond14/lena/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/dUd=MN0
- 小区停车协商的服务细节记录 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/803
- 开源技术交流的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/qis
- 乡村公共阅读的社区参与观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/b2M
- 线上阅读资源的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/967=vwe
- 数字生活课堂的参与方式与路径 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/cqs=606
- 数字学习资源的资源整合思路 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/t6I=FC1
- 乡村文化活动的实用信息清单 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/112
- 儿童户外活动的便民做法梳理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/irs
- 社区家政服务的入门知识整理 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/SM2
- 乡村电商实践的日常使用指南 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/481=evt
- 社区垃圾回收的家庭参与方式 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/lgn=036
- 老年友好服务的便利性观察 |来源：https://github.com/vargasraymond14/lena/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/7fR=WuD

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
