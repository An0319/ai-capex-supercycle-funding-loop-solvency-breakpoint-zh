# 谁为万亿算力买单——AI资本开支超级周期的资金闭环与偿付断点

> **报告类型纪律（本报告的最高约束，优先于一切文风要求）**：这是一份 **A型结构认知报告**。其产品是"这轮周期的资金内在结构"，认知增量必须在读完全文时即交付完毕；核心产品是**结构地图，不是涨跌预言**；所有情景推演一律以条件语句呈现（"若X则Y"），不作方向押注；凡无法指向具体结构、金额、条款、触发条件的判断，一律降格为**猜想**并明确标注。
>
> **一次一转纪律**：一次对话只撰写当前指定的一个章节；该章节完稿后立即停止，严禁自行续写任何后续章节、严禁输出全书总结性收尾。每章正文之外附本"自检清单"。
>
> **快慢变量分离纪律**：循环模式、融资形态、断裂序列 = 慢变量（本报告主体）；具体金额、单一交易条款 = 快变量（一律标注"截至核验日 2026-09-06"并配监测清单）。
>
> **检索纪律**：所有数据已按执行日联网核验，来源 URL 在正文内联标注；凡付费墙/不可达项均标注置信度并说明，绝不编造。

---

# 第 0 章 · 执行日核验表（2026-09-06）

> 章内说明：本章是全文的**数据可信骨架**。所有锚点均在 2026-09-06 当日经联网核验，逐项给出"核验值 / 循环回流标记 / 信息时点（原始发布时点｜检索时点）/ 来源URL / 置信度 / 条款备注"。执行日晚于知识截止期的新增大额交易已补入地图。
>
> **循环回流标记示意**（接四线流：股权投资流 / 算力合约流 / 芯片物流 / 债务流）：
> - `[股]` = 股权投资流；`[合]` = 算力合约流；`[芯]` = 芯片物流；`[债]` = 债务流
> - `✓回流` = 该笔同时构成"卖方为买方融资→买方采购回流为卖方收入"的闭环；`✗非循环` = 与该闭环无直接关联
>
> **置信度定义**：`High`=官方/权威一手来源可复核；`Medium`=多来源交叉或权威第三方分析；`Low`=二手转述/口径不一/付费墙摘要。

---

## 0.1 核验总表（按三组数据簇）

### A 组 · 云厂商资本开支规模 + 宏观金融稳定报告

| 锚点 | 核验值（截至 2026-09-06） | 循环回流 | 信息时点（原始｜检索） | 来源URL | 置信度 | 备注 / 条款 |
|---|---|---|---|---|---|---|
| 四大云 2024 年合计 CapEx | 日历口径约 **2283 亿美元**（Amazon 83.0B / Google 52.5B / Meta 37.3B / Microsoft 55.6B）；Platformonomics 称合计"over $251B" | ✗非循环 | 2025-02｜2026-09-06 | [Fed FEDS Note](https://www.federalreserve.gov/econres/notes/feds-notes/the-ai-buildout-and-the-economy-publicly-available-data-to-assess-ais-impact-accessible-20260717.htm)；[Platformonomics](https://platformonomics.com/2025/02/follow-the-capex-cloud-table-stakes-2024-retrospective/) | High | Fed 表按日历季度，与你基线"约 2200 亿"一致。 |
| 2025 年 CapEx 合计 | 日历口径约 **3828 亿美元**（Amazon 131.8B / Google 91.5B / Meta 69.7B / Microsoft 83.1B）；Platformonomics 2025 Actual 合计 416.4B | ✗非循环 | 2026-04 / 2026-07｜2026-09-06 | [Fed FEDS Note](同上)；[Platformonomics Q1-2026](https://platformonomics.com/2026/04/follow-the-capex-q1-2026-scoreboard/) | High | 2025 未检到官方逐厂"指引"，以实际口径为最佳核验值；与你基线"3600—4000 亿"一致。 |
| 2026 年 CapEx 指引/预期 | 四厂 **6950—7250 亿美元**（Amazon ~200B / Google 180-190B / Meta 125-145B / Microsoft ~190B） | ✗非循环 | 2026-04-30 / 2026-08-11｜2026-09-06 | [Platformonomics](同上)；[ValueAddVC](https://valueaddvc.com/ai-spending) | High | 为平台整理口径，非官方统一指引。 |
| Meta 至 2028 对美投资 6000 亿美元 | "committing **over $600 billion** in the US by 2028" 支持 AI 技术/基础设施/劳动力扩张 | ✗非循环 | 2025-11-07｜2026-09-06 | [Meta Newsroom](https://about.fb.com/news/2025/11/meta-data-centers-drive-economic-growth-across-us/) | High | 是 2028 前累计承诺，非单一年度 capex。 |
| BIS / IMF 金融稳定报告（AI 专题） | IMF **GFSR 2025年10月期**《SHIFTING GROUND BENEATH THE CALM》：AI/IT 相关股票估值集中度高企、S&P500 集中度历史高位；BIS 为 **2025 年 12 月** Quarterly Review《Volatility challenges risk-taking》：M7 股价受 AI/数据中心盈利预期支撑但估值拉伸 | ✗非循环 | 2025-10 / 2025-12｜2026-09-06 | [IMF GFSR Ch1](https://www.imf.org/-/media/files/publications/gfsr/2025/october/english/ch1.pdf)；[IMF Press Briefing](https://www.imf.org/en/news/articles/2025/10/15/tr-101425-press-briefing-transcript-global-financial-stability-report-annual-meetings-2025)；[BIS QR](https://www.bis.org/publ/qtrpdf/r_qt2512a.pdf) | High | **校正**：IMF 为 10 月期（与你基线一致），BIS 校准为 12 月期。 |
| CapEx 资金来源结构（FCF vs 债务） | H1-2026 五大 Big Tech CapEx/经营现金流达 **96%**（2024 为 50%、2025 为 68%）；2025 合计 FCF 1913 亿；四家长期债务 2024 末 1320 亿 → 2026 年 6 月末 **3419 亿美元** | ✗非循环 | 2026-09-05｜2026-09-06 | [SimianX](https://www.simianx.ai/stories/ai-capex-2026-big-tech-now-spends-96-of-its-cash-flow) | Medium | 第三方基于 SEC EDGAR XBRL，非官方现金流分部；作背景锚，支撑"FCF→信用"迁移命题。 |

### B 组 · OpenAI 累计算力承诺 + 循环交易网络 + 收入侧

| 锚点 | 核验值（截至 2026-09-06） | 循环回流 | 信息时点（原始｜检索） | 来源URL | 置信度 | 备注 / 条款 |
|---|---|---|---|---|---|---|
| Stargate 项目约 5000 亿美元 | **5000 亿美元**，4 年部署、初始 1000 亿；参与方 OpenAI/SoftBank/Oracle/MGX，Nvidia 为技术伙伴 | `[合]``[芯]` ✓闭环（芯片+算力回流项） | 2025-01-21（白宫）｜2026-09-06 | [IntuitionLabs Guide](https://intuitionlabs.ai/pdfs/openai-s-stargate-project-a-guide-to-the-ai-infrastructure.pdf) | Medium | 多来源交叉，分期/条款以第三方梳理为主。 |
| Oracle 合约约 3000 亿/5.5 年 | **未核验到独立合约原文**；3000 亿仅见 Tom Tunguz 按 Stargate/基础设施口径拆分 | `[合]` ✓闭环候选 | 基线自 2025-01-21｜2026-09-06 | [TomTunguz](https://tomtunguz.com/openai-hardware-spending-2025-2035/) | Low | ⚠️ **降级**：须待独立来源确认，否则按"估算·低置信度"处理。 |
| Microsoft Azure 约 2500 亿采购 | **2500 亿美元**，期限为"未来数年"，属 2025-10-28 OpenAI 营利化重组的一部分 | `[合]` ✓闭环（Azure 回流微软） | 2025-10-28｜2026-09-06 | [Fortune](https://fortune.com/2025/10/28/openai-for-profit-restructuring-microsoft-stake/) | High | 与重组协议绑定。 |
| AWS 约 380 亿 | **380 亿美元**，多年期（报道提及 7 年），OpenAI 用 AWS 运行/扩展工作负载，结束微软云独占 | `[合]` ✓闭环（AWS 回流亚马逊） | 2025-11-03｜2026-09-06 | [SecurityOnline](https://securityonline.info/cloud-wars-openai-signs-38-billion-computing-deal-with-aws-ending-microsoft-exclusivity/) | Medium | 多方报道一致。 |
| Broadcom 定制 ASIC/10GW | **10GW**，金额未披露；OpenAI 设计加速器+系统，Broadcom 合作开发部署；机架部署 2026H2 启动、2029 底完成 | `[芯]` ✓回流候选 | 2025-10-13｜2026-09-06 | [OpenAI-Broadcom 公告](https://openai.com/index/openai-and-broadcom-announce-strategic-collaboration) | High | 官方公告。 |
| Nvidia 对 OpenAI 投资（基线上限 1000 亿） | 2025-09-22 宣布**至多 1000 亿**（以 OpenAI 部署 ≥10GW Nvidia 系统为框架，随每 GW 部署逐步投）；**2026-02 后续已弱化为约 300 亿股权**，黄仁勋称其"never a commitment" | `[股]`✓`[芯]` ✓闭环核心（投资→OpenAI采购→Nvidia数据中心收入） | 2025-09-22 宣布；2026-02 弱化口径｜2026-09-06 | [Nvidia Press](https://investor.nvidia.com/news/press-release-details/2025/OpenAI-and-NVIDIA-Announce-Strategic-Partnership-to-Deploy-10-Gigawatts-of-NVIDIA-Systems/default.aspx) | Medium | ⚠️ **关键更新**：承诺金额在 2026 年缩水，闭环节点须用新口径。 |
| AMD 6GW + 1.6 亿股期权 | **6GW AMD GPUs**；附带最多 **1.6 亿股 AMD 普通股期权/认股权**；MI450 系列首发部署 2026H2 | `[芯]` ✓回流候选 | 2025-10-06｜2026-09-06 | [AMD Newsroom](https://newsroom.amd.com/news/amd-and-openai-announce-strategic-partnership-to-d/) | High | 官方公告。 |
| OpenAI 承诺合计"超 1.4 万亿" | 原始**Altman 口径"约 1.4 万亿 / 未来 8 年"（2025-11-06）**；第三方拆分约 **1.15 万亿**；2026 年另见目标下调至约 **600 亿→随后升至约 750 亿**的报道 | — | 2025-11-06；后续｜2026-09-06 | [CaymanJournal Research](https://caymanjournal.com/research/openai-compute-liability) | Medium | ⚠️ **口径分离**：须分列"原始官方 / 第三方拆分 / 后续调整"三口径，不可混称。 |
| Nvidia 向 Anthropic 投资至多 100 亿 | **至多 100 亿美元** | `[股]`✓回流核心 | 2025-11｜2026-09-06 | [Anthropic 官方](https://www.anthropic.com/news/microsoft-nvidia-anthropic-announce-strategic-partnerships) | High | 三方战略合作。 |
| Microsoft 向 Anthropic 投资至多 50 亿 | **至多 50 亿美元** | `[股]`✓回流核心 | 2025-11｜2026-09-06 | [Anthropic 官方](同上) | High | 官方公告。 |
| Anthropic 承诺采购 300 亿 Azure 算力 | **300 亿美元**（投资与长期基础设施承诺结合的交易结构） | `[合]` ✓闭环（Azure 回流微软） | 2025-11｜2026-09-06 | [MIT Sloan India](https://mitsloanindia.com/article/anthropic-lands-15-billion-from-microsoft-nvidia-in-expansive-cloud-tie-up/) | Medium | 另一来源称 MSFT+Nvidia 合计投 $15B；金额口径需统一。 |
| 微软控股 OpenAI 27% | **约 27% 股权**（估值约 1350 亿）；交易后微软保留 OpenAI 技术访问权至 2032，解除云独占 | `[股]`✓闭环核心（既股东又供应商） | 2025-10-28｜2026-09-06 | [Fortune](https://fortune.com/2025/10/28/openai-for-profit-restructuring-microsoft-stake/) | High | 双重身份标本。 |
| OpenAI 增量采购 2500 亿 Azure | **2500 亿美元**（未来数年，2025-10-28 重组协议一部分） | `[合]` ✓闭环（Azure 回流微软） | 2025-10-28｜2026-09-06 | [Fortune](同上) | High | 与上方 Azure 2500 亿同源，勿重复计价。 |
| OpenAI 年化收入 | 2025 全年 **130.7 亿美元**（+254% YoY）；**2026-08 约 400 亿 ARR / 约 33 亿美元/月** | ✗非循环 | 2025 全年；2026-08｜2026-09-06 | [Fortune leaked financials](https://www.fortune.com/2026/06/16/openai-financials-leaked-losses-revenue-profit/) | High | ⚠️ **快变量显著上行**：2026 已远超 2025 基线，闭合路径数须用最新。 |
| 全行业 AI 收入 vs AI capex | 行业口径混乱：IDC 2026 AI 支出约 **5145 亿**；Gartner AI spending 约 **2.59 万亿**；瑞银测算 2026 超大规模资本开支约 **1.0 万亿** | ✗非循环 | 2026 各统计｜2026-09-06 | [AI Statistics 2026](https://aibusinessweekly.net/p/ai-statistics-2026)；[Gartner](https://www.gartner.com/en/newsroom/press-releases/2026-05-19-gartner-forecasts-worldwide-ai-spending-to-grow-47-percent-in-2026) | Medium | ⚠️ **口径不可混比**：报告必须保持可比口径纪律（AI 收入 ≠ AI capex ≠ AI enabled 总支出）。 |
| Nvidia 数据中心收入 | **FY2026 全年 1937 亿美元（+68%）**；Q4 FY26 单季 **623 亿（+75%）** | ✗非循环（其上游，作回流成效观测） | 2026-02｜2026-09-06 | [Nvidia China Blog](https://blogs.nvidia.cn/blog/nvidia-announces-financial-results-for-fourth-quarter-and-fiscal-2026/) | High | 已超你基线 FY2025 ~1150 亿。 |
| Microsoft Azure AI 相关收入 | FY2026 Q4 Azure 同比 **+43%**；全年 Azure 收入首破 **1000 亿美元** | ✗非循环 | 2026-07-29｜2026-09-06 | [Microsoft Q4-FY26](https://news.microsoft.com/source/2026/07/29/microsoft-cloud-and-ai-strength-fuels-fourth-quarter-results-4) | High | 作闭环回流成效观测。 |

### C 组 · 会计折旧 / GPU 租金 / 信用层 / 历史锚 / 接口数据

| 锚点 | 核验值（截至 2026-09-06） | 循环回流 | 信息时点（原始｜检索） | 来源URL | 置信度 | 备注 / 条款 |
|---|---|---|---|---|---|---|
| MSFT/Google 服务器折旧延至 6 年 | Microsoft：FY2023 起服务器/网络设备由 **4 年→6 年**，FY23 运营收入影响约 **37 亿美元**；Google：2023-01 服务器/网络设备延至 **6 年**，FY23 折旧减约 **39 亿** | ✗非循环 | 2022-07-26（MSFT）；2023-01（GOOG）｜2026-09-06 | [BuxtonHelmsley 法证框架](https://www.buxtonhelmsley.com/news-and-insights/the-useful-life-question-a-forensic-framework-for-reading-hyperscaler-depreciation-policy-in-the-artificial-intelligence-capital-expenditure-era)；[MSFT FY23Q4](https://www.microsoft.com/en-us/investor/events/fy-2023/earnings-fy-2023-q4.aspx)；[ABC Investor](https://abc.xyz/investor/news/2023/0420/) | High | 会计解剖学开篇硬证据。 |
| CoreWeave 等按 6 年折旧 GPU | CoreWeave S-1 披露技术设备（含 NVIDIA GPU）**6 年直线折旧**；Nebius 4 年、Lambda 约 5 年 | ✗非循环 | 2023—2025 披露期｜2026-09-06 | [Bizety 分析](https://bizety.com/2025/09/23/gpu-depreciation-coreweave-vs-nebius/)；[Luminix 行业分析](https://www.useluminix.com/reports/industry-analysis/deep-dive-on-the-neocloud-gpu-rental-industry-coreweave-lambda-crusoe) | High | 6 年折旧为硬事实。 |
| GPU 有效寿命 2—3 年 vs 会计 5—6 年 | 行业分析普遍将 GPU 物理损耗/训练推理负载与 5—6 年会计折旧并行比较；云数据中心 60—70% 利用率下寿命更短 | ✗非循环 | 2025—2026｜2026-09-06 | [ComputeForecast](https://www.computeforecast.com/long-reads/ai-infrastructure-depreciation-schedules-gpu-obsolescence-risk/)；[Introl](https://introl.com/blog/gpu-depreciation-strategies-asset-lifecycle-optimization-guide-2025) | Medium | 2—3 年主要来自行业分析，非单一官方。 |
| H100 租金曲线 | 2023H2 约 **7.76—7.92 美元/时**；2025-10 一年期合约低至 **1.70 美元**；2026-03 **2.35**、2026-04 区间 **2.10—2.70** 美元 | ✗非循环 | 2023；2025-10；2026-03/04｜2026-09-06 | [SiliconData](https://www.silicondata.com/blog/h100-rental-price-over-time)；[SemiAnalysis GPU Pricing](https://semianalysis.com/gpu-pricing-index/) | Medium | ⚠️ 曲线确认，但 **2026 回升至 ~2.35**，非单向下行；$1.70 为 2025 年低点；交叉观测用最新曲线。 |
| CoreWeave GPU 抵押债务 | "$8.5B DDTL 4.0"投资级延期贷款（可扩至 8.5B）+ "$3.1B DDTL 5.0"；第三方汇总称总债务超 **325 亿美元**（含 OEM/软件许可融资与 Magnetar 相关安排） | `[债]` | 2026｜2026-09-06 | [CoreWeave DDTL 4.0](https://investors.coreweave.com/news/news-details/2026/CoreWeave-Closes-Landmark-8-5-Billion-Financing-Facility-Achieving-First-Investment-Grade-Rated-GPU-backed-Financing/default.aspx)；[DDTL 5.0](https://investors.coreweave.com/news/news-details/2026/CoreWeave-Closes-3-1-Billion-Loan-Facility-Expanding-Access-to-Public-Markets-for-GPU-Backed-Financing/)；[CCIR](https://ccir.io/research/two-order-books) | Medium | 你基线"百亿级"成立；325 亿为第三方汇总，需区分债务/股权/融资安排。 |
| 首个投资级 GPU-backed 融资 | CoreWeave DDTL 4.0 含浮动 tranche **SOFR+2.25%**、固定约 **5.9%**，为**首个获投资级评级的 GPU-backed 融资** | `[债]` | 2026｜2026-09-06 | [CoreWeave](同上) | Medium | 信用层里程碑。 |
| Blue Owl 合资（基线上限 380 亿） | **未核验到 Oracle+Blue Owl 380 亿合资**；真实锚点是 **Stargate $38B 项目融资**（JPMorgan+MUFG 牵头，德州/威斯康星数据中心）与 **Meta-Blue Owl $27B Hyperion 合资**（Blue Owl 持 80%、Meta 持 20%） | `[债]` | 2025-10｜2026-09-06 | [CapitalAI](https://www.capitalaidaily.com/jpmorgan-chase-and-mufg-lead-38-billion-debt-sale-to-power-openai-stargate-initiative-report/)；[Meta-Blue Owl](https://about.fb.com/news/2025/10/meta-blue-owl-capital-develop-hyperion-data-center/amp/) | Low | ⚠️ **校正错误锚点**：你的基线"Oracle+Blue Owl 380 亿"无法核实，报告中须替换为 Stargate 38B 项目融资 + Meta-Blue Owl 27B。 |
| 私募信贷对数据中心/AI 敞口 | UBS：截至 2025 初科技公司私募借款约 **4500 亿**（同比约 +1000 亿）；约 **1250 亿**流入 Meta/Blue Owl 式项目融资；AI 相关贷款占私募信贷交易比例由过去 5 年 17% 升至 2025 年超 33%；S&P Global 称私募信贷市场近 **1460 亿** | `[债]` | 2025—2026｜2026-09-06 | [CompleteAITraining](https://completeaitraining.com/news/off-the-books-and-into-private-credit-big-techs-120-billion/)；[FSB 相关报道](https://otontechnology.com/fsb-private-credit-ai-boom-warning/)；[S&P Global](https://press.spglobal.com/2026-02-17-Private-Credit,-Tech-Issuance-fuelled-by-AI,-and-Increasing-Leverage-Among-Key-Driving-Factors-Impacting-Credit-Market-Liquidity-in-2026-according-to-S-P-Global-Ratings) | Low | 付费墙原始数据未纳入，作观测哨背景。 |
| xAI 股权+GPU 抵押 SPV 混合融资 | xAI 据报推进 **200 亿 GPU 租赁/自持** 交易，SPV 结构：约 **75 亿股权 + 125 亿债务**（债务由 GPU 担保），Nvidia 可投 20 亿股权，其余含 Apollo 等 | `[债]`✓`[股]` | 2025-10｜2026-09-06 | [ROIC](https://www.roic.ai/news/xai-pursues-20-billion-lease-to-own-deal-for-nvidia-gpus-through-spv-structure-10-16-2025)；[DataConomy](https://dataconomy.com/2025/10/08/elon-musks-xai-reportedly-raising-20-billion-in-deal-tied-to-nvidia-chips/) | Medium | 媒体口径，非 xAI 正式公告；结构特征明确。 |
| Lucent/Nortel 卖方融资 | Tom Tunguz：Lucent 承诺 **81 亿**、Nortel 延伸 **31 亿（14 亿未偿）**；另一二手口径称 Nortel 曾向运营商提供 **>70 亿**贷款 | `[合]`✓历史闭环原型 | 1999—2000；2001-02 结局｜2026-09-06 | [TomTunguz Nvidia/Nortel 对照](https://tomtunguz.com/nvidia_nortel_vendor_financing_comparison/)；[Investing.com](https://m.investing.com/analysis/nvidia-deals-round-tripping-or-vendor-financing-200669674) | Low | ⚠️ **校正**：你基线"各 70—80 亿美元"与核验口径出入，须按承诺/发放/未偿分列、口径混一后再引用。 |
| 1996—2001 电信 capex 崩塌 | 美国电信运营商 capex 从 1996 约 **300 亿** 升至 2000 峰值约 **1100—1200 亿**；FRB 通信设备投资 1996Q1 约 620 亿/年 → 2000Q4 超 1350 亿/年，此后连续 7 季同比负增；TIA 预测 2002 年较 2001 年降 **48%** | ✗非循环 | 1996—2003｜2026-09-06 | [Telecom Bubble vs AI 报告](https://beehiiv-publication-files.s3.amazonaws.com/uploads/downloadables/1cf8fa39-cfc4-4688-8d80-aa9c08c8b2e4/325524bc-013f-47f3-a9de-74b318e2ad03/Telecom_Bubble_vs_AI_Report_PDF.pdf)；[FRBRich](https://fraser.stlouisfed.org/files/docs/publications/frbrichreview/rev_frbrich200304.pdf)；[TIA](http://standards.tiaonline.org/gov_affairs/fcc_filings/documents/Nov13-2002_CapEx_QoS_Final.pdf) | Medium | ⚠️ **校正**："崩塌超八成"作为尾部极端表述证据不足；可靠为峰值后腰斩级快速收缩。 |
| dark fiber 2002—2005 点亮率 <5% | 2002 年行业文章称 carrier networks "only **5% of fiber is lit**"，另有约 3% 平均容量口径；论坛转述 2%—5% | ✗非循环 | 2002｜2026-09-06 | [Lightwave](https://www.lightwaveonline.com/business/earnings-statements/article/16648148/is-too-much-fiber-not-enough) | Low | "不足 5%"可被二手支持，但地区/结构差异大。 |
| 1920 年代 Insull 体系 | 多层控股：母公控中间控股、再控运营公用事业；以约 **2700 万美元股权控制约 5 亿美元资产**，放大杠杆；1930 年代前崩解 | `[股]`✓历史杠杆原型 | 1920s—1930s｜2026-09-06 | [HiddenFortunes](https://hiddenfortunes.io/the-electricity-trusts-private-utilities-holding-companies-financial-machines/)；[InvestorAmnesia](https://investoramnesia.com/2020/06/28/fraud-short-sellers-media/)；[NBER](https://conference.nber.org/confer/2015/SI2015/LE/Kandel_Kosenko_Morck_Yafeh.pdf) | Medium | 用于结构对照（多层杠杆+会计平滑），非精确数。 |
| SK海力士 HBM（接口：存储合约价领先指标） | 2026 聚焦 HBM-led memory supercycle；**HBM4 约 560 美元/颗（较 HBM3E 涨逾 50%）**；HBM4 约 31—32 美元/GB（HBM3E 约 17—18）；现货 HBM4 约 **3500 美元/颗**、HBM3E 约 **2100 美元** | ✗非循环 | 2025—2026｜2026-09-06 | [SK hynix Outlook](https://news.skhynix.com/2026-market-outlook-focus-on-the-hbm-led-memory-supercycle/)；[TrendForce](https://www.trendforce.com/news/2026/08/13/news-samsung-sk-hynixs-hbm4-push-puts-hbm-general-memory-pricing-in-the-spotlight-for-2h-earnings/)；[Sina Finance](https://finance.sina.com.cn/wm/2026-09-01/doc-iniqfuyq1687452.shtml) | Low | 合约/现货价均非官方全量披露，来自媒体与第三方摘要；作领先指标观测哨。 |
| 电网并网/电力约束（接口：能源物理约束） | 美国并网队列约 **2600 GW**（发电 1312 + 储能 749）；**ERCOT 大型负荷队列 2026-04 约 410 GW**（超 2025 末 233、2024 末 63），另有口径 474 GW | ✗非循环 | 2024—2026｜2026-09-06 | [Presenc](https://presenc.ai/research/grid-interconnection-queue-ai-datacenters-2026)；[Luminix](https://www.useluminix.com/reports/industry-analysis/powering-the-ai-boom-where-the-grid-breaks-first-2026-2030/source/1)；[ECMSource](https://ecmsource.com/texas-halts-data-center-power-474-gw-ghost-demand-september-2026/) | Low | 队列增速确认，具体数来自二手汇总，未核验 FERC/ERCOT 原始报告；作部署速率限制器背景。 |

---

## 0.2 口径修正与仲裁纪要（写后续章节前必须内化的 11 条）

1. **Nvidia→OpenAI"至多 1000 亿"已缩水**：2025-09-22 宣布 → 2026-02 弱化为约 300 亿股权，黄仁勋称"never a commitment"。闭环地图此节点金额须用新口径。
2. **OpenAI 承诺合计三口径分离**：原始官方"约 1.4 万亿/8 年"（2025-11-06）≠ 第三方拆分约 1.15 万亿 ≠ 2026 目标调整（600→750 亿）。全报告此后一律分列，禁止混称"超 1.4 万亿"。
3. **Oracle"3000 亿/5.5 年"待确认**：未核验到独立合约原文，仅见第三方拆分 → 降为低置信度"估算"。
4. **"Oracle+Blue Owl 380 亿"为错误锚点**：真实结构是 Stargate $38B 项目融资（JPMorgan+MUFG）+ Meta-Blue Owl $27B Hyperion 合资。此更正必须传导到信用层章节。
5. **Lucent/Nortel 口径混一**：按承诺（Lucent 81 亿 / Nortel 延伸 31 亿·14 亿未偿）分列，勿沿用"各 70—80 亿"。
6. **电信"崩塌超八成"表述降级**：改述为"峰值 $1100—1200 亿后腰斩级快速收缩，TIA 预测 2002 较 2001 降 48%"。
7. **H100 租金非单向下行**：2025-10 低点 $1.70 → 2026-03 $2.35。交叉点推演用最新曲线，勿假设直线打折。
8. **OpenAI 收入快变量已跃迁**：2025 全年 $130.7 亿 → 2026-08 约 $400 亿 ARR。闭合路径会计数用最新。
9. **行业口径不可混比**：IDC 的"AI 支出"5145 亿 ≠ Gartner 的"AI enabled spending"2.59 万亿 ≠ 超大规模 capex 1.0 万亿。"堰塞湖/赛跑"算术必须锁定同口径比较。
10. **BIS 期号校正**：AI/集中度分别在 BIS 2025-12 期与 IMF 2025-10 期，勿统称"2025-10"。
11. **Nvidia 数据中心收入已更新**：FY2026 全年 $1937 亿（+68%），勿沿用 FY2025 基线。

---

## 0.3 快慢变量划分与执行日监测清单

**慢变量（本报告主体，不受日期波动）**：循环模式（卖方融资闭环）、融资形态迁移（FCF→债券→私募信贷→GPU抵押→SPV）、断裂序列、需求五路径形态。

**快变量（一律标注"截至 2026-09-06"，并设监测哨）**：

| 监测哨 | 观测指标 | 变更即触发修订的规则 |
|---|---|---|
| 收入/capex 比值 | 全行业可比口径 AI 收入 / 超大规模 capex | 若 <0.1 持续，缺口命题强化；**重锚判据（2026-09-06，0.7-②）**：R 中心值连续两个季度站上 0.3，或 B 口径 run-rate ≥5000 亿美元——原"2027 前破 0.3"单点判据已被第 2 章基线（k 加权中心 25—30%）追平，废除（第 8 章裁决规则同步） |
| GPU 租金 | 一年期合约价 vs 会计折旧线 | 租金跌破折旧线即进入共振前置区 |
| 算力债 | SOFR+利差、条款（如 CoreWeave DDTL）、展期要求 | 利差走阔+条款收紧 = 债权人觉醒信号 |
| OpenAI/Anthropic 估值条款 | 新一轮融资估值是否下修 | 下修 = 融资叙事连续性受创 |
| 新增大额交易 | 执行日后所有新签算力/投资契约 | 扣入闭环地图对应节点，逐项补入 |
| HBM 合约价（接口） | SK海力士 HBM4/HBM3E 合约价趋势 | 全链条最前端领先指标 |
| 供电/并网队列（接口） | ERCOT/FERC 队列、变压器交付、PPA | AI 部署速率真实限制器 |

---

## 0.4 本章自检清单

**① 本章全部具体数字的来源核对结果**
- 出自核验表/联网核验：2024/2025/2026 capex（Fed FEDS Note、Platformonomics、ValueAddVC）、Meta 6000 亿、BIS/IMF、OpenAI 承诺逐项、Nvidia/AMD/Broadcom/微软/AWS 公告、OpenAI 收入、Nvidia FY2026、Azure FY2026、折旧政策（MSFT/GOOG/CoreWeave）、H100 租金、CoreWeave 债务、私募信贷、xAI、SK hynix、电网队列——以上均出自本次三路 Explore 子代理联网核验，URL 内联。
- 估算值·置信度低：Oracle 3000 亿/$5.5 年（Low）、私募信贷各口径（Low）、dark fiber 点亮率（Low）、SK hynix 与电网具体数（Low）、Lucent/Nortel 分列口径（Low）。
- 你基线中被降级/校正的项已全部在 0.2 纪要列出（11 条）。

**② 本章全部假设参数列表**
- 央行/机构 capex 表为日历口径（非财年）；各平台口径（Platformonomics/ValueAddVC）为整理值，非官方指引——已标注 High/Medium。
- "循环回流标记"二元标记不改变数据本身，仅作分析分类，无独立假设。
- 快变量全部假定"截至 2026-09-06 仍有效"，并配 0.3 监测清单持续刷新。
- 敏感性说明：OpenAI 收入采用泄漏审计/第三方口径（$130.7 亿/2025、~$400 亿 ARR/2026-08），若你以官方披露替换，比值类结论的方向不变、量级可能上移。

**③ 本章置信度最低的三处段落（供人工重点抽查）**
1. 0.1-B 组"Oracle 3000 亿/5.5 年"（Low，且直接支撑闭环地图一个节点）——须待独立来源确认方可计入承诺合计。
2. 0.1-C 组"私募信贷对数据中心敞口"（Low，付费墙未纳入）与"Blue Owl 锚点更正"（Low，原错误锚点替换为 Stargate 38B + Meta-Blue Owl 27B）。
3. 接口数据两个节点：SK hynix HBM 合约价（Low，非官方全量）与美电网并网队列（Low，二手汇总未核验 FERC/ERCOT 原始报告）——作观测哨可，作硬结论不可。

---

## 0.5 抽查复核纪要（2026-09-06 二次核验，4 项重点 + 增量补全）

> 本表是针对上一次"修正本身存疑"的项与关键口径的二次核查，并补入执行日前全部增量交易（快照=宪法基线+增量）。凡与 0.1 冲突者，以本节为准。

**复核 1 · Oracle 与 Blue Owl（错误锚点的修正本身抽查）**
结论：**修正成立但需细化**。未检索到 Oracle 直接向 Blue Owl 借款或直接合资的大额协议；更准确结构是 **Oracle 作为租户/项目方，Blue Owl 在部分 Oracle 关联项目中承担开发权益/运营（经 STACK Infrastructure），且已于 2025-12 退出 Oracle 密歇根项目**。Oracle 的股权性数据中心资金实际是**项目级 SPV / 银团贷款**：Stargate 相关 $38B（JPMorgan+MUFG，Vantage 开发）、密歇根 $16B（PIMCO+BofA 债务、Blackstone/Related 权益，Blue Owl 已退）、新墨西哥 $18B（约 20 家银行，Blue Owl 提供开发权益）。对照项 Meta-Blue Owl $27B Hyperion JV（Meta 20%/Blue Owl 80%）为直接 JV，与 Oracle 情形不同。→ 0.1-C 该行结论由"错误锚点替换为 Stargate 38B + Meta-Blue Owl 27B"**再细化**为上述口径。
来源：[TechInAsia](https://www.techinasia.com/news/oracle-nears-record-38b-loan-for-openai-data-centers)、[Based.info](https://based.info/oracles-16-billion-michigan-data-center-financing-signals-tightening-credit-conditions-for-ai-infrastructure/)、[Bullwaves](https://www.bullwaves.com/ar/blog-news/banks-lend-18-billion-for-oracle-tied-data-center-in-new-mexico)、[DailyAI](https://dailyaibrief.com/news/blue-owl-withdraws-oracle-michigan-data-center-qsC4Q1Ee)、[DataCenterFrontier](https://www.datacenterfrontier.com/hyperscale/article/55369021/blue-owl-builds-a-capital-platform-for-the-hyperscale-ai-era)、[Meta-Blue Owl PD](https://s21.q4cdn.com/399680738/files/doc_news/Meta-Announces-Joint-Venture-with-Funds-Managed-by-Blue-Owl-Capital-to-Develop-Hyperion-Data-Center-2025.pdf)，置信度 Low–Medium。

**复核 2 · Nvidia 分批生效条款**
结论：**原始 $100B 分批框架存在但未转化为约束合同**。2025-09-22 原始公告：OpenAI 部署 ≥10GW Nvidia 系统、**随每 1GW 部署逐步投资、最高 $100B**、首个 1GW 2026H2 部署。但 Nvidia 10-Q 载明风险提示"There is no assurance that we will enter into definitive agreements with respect to the OpenAI opportunity."；黄仁勋称其"never a commitment"；**$100B 框架已于 2026-01 搁置**。后续落点：**OpenAI Series I（2026-02-27）Nvidia 投入 $30B 股权**（同轮 Amazon $50B、SoftBank $30B，pre-$7300 亿/post-$8400 亿），OpenAI 另承诺 5GW Vera Rubin。→ 0.1-B6 该行更新：金额用 $30B 股权；分批按 GW 机制"存在但未落地"。
来源：[Nvidia News](https://investor.nvidia.com/news/press-release-details/2025/OpenAI-and-NVIDIA-Announce-Strategic-Partnership-to-Deploy-10-Gigawatts-of-NVIDIA-Systems/default.aspx)、[Nvidia 10-Q 提示 via Investing](https://www.investing.com/analysis/nvidia-and-openais-100-billion-deal-is-dead-what-replaced-it-matters-more-200680620)、[Fortune J.Huang](https://www.fortune.com/2026/02/02/jensen-huang-nvidia-ceo-on-openai-investment-never-a-commitment/)、[STCN](https://stcn.com/article/detail/3662038.html)，置信度 Medium。

**复核 3 · H100 租金回升（口径级）**
结论：**"回升"仅见于 1 年期长期合同口径，现货/即期口径为低位企稳**；且 **H100 与新一代型号（B200/H200/GB）不可混用**。SemiAnalysis：H100 现货/即期 $2.79→$2.82（2025-07→2026-03）几乎为零波动；H100 1y\* 长约 $1.45–1.95（2025-10 低点）→ $2.10–2.70（2026-04，低点约 $1.70，回升约 +40%）。新一代：B200 1y\* 综合 $3.68（2026-04）、现货层面更高。→ 0.1-C"租金"行修订：现货企稳、长约小幅回升；"H100 租金"指 1y\* 长约口径；勿用新一代高价冒充 H100。
来源：[SemiAnalysis GPU Pricing](https://semianalysis.com/gpu-pricing-index/)、[CompuX](https://compux.net/docs/guides/gpu-pricing-trends-2026/)、[TechExpress](https://thetechnologyexpress.com/nvidia-h100-prices-surge-as-ai-demand-outpaces-supply/)，置信度 High。

**复核 4 · OpenAI ARR 口径定义（缺口算术命门）**
结论：**$40B ARR = 约 $3.3B/月 × 12 的年化收入速度，绝非 $40B/月**。规则：这是按近期月收入年化（run-rate），**不是多年合约摊销**。成分：2026-08 CFO Sarah Friar 向投资者披露"ARR 达 $40B、企业收入已超消费者"（消费者 2026 年初约 60%→现已 <50%）；API/企业合同/Enterprise 计入企业侧，ChatGPT 订阅计入消费侧。**微软分成口径未确定**：OpenAI 仍向微软支付约 20% 收入分成、至 2030 年上限 $38B；$40B 是否已净分成未披露。→ 对闭环回流率影响：$40B 不能直接视为 OpenAI 可自由支配现金流，且不可与"数月前 $130.7 亿/2025 全年"混淆。2025 全年收入 $130.7 亿、运营亏损 $209 亿。
来源：[ValueAddVC](https://valueaddvc.com/blog/openai-revenue-2026-20b-arr-4b-month-path-to-profitability)、[SpoonAI/CNBC](https://spoonai.me/posts/2026-08-17-openai-enterprise-revenue-overtakes-consumer-40b-arr-en)、[Luminix](https://www.useluminix.com/reports/company-overviews/openai-financial-fact-sheet-june-2026)、[FourWeekMBA](https://fourweekmba.com/ai-openai-enterprise-revenue-exceeds-consumer-chatgpt-wedge/)（置信度 中高）。

---

## 0.6 执行日增量交易子表（快照=宪法基线+增量，新增项，截至 2026-09-06）

> 下表为 0.1 核验后的**新增/更新项**，第 1 章闭环地图必须全部纳入。行号以 `0.6-x` 引用。

### 0.6-A 2026 增量循环/闭环交易

| 增量交易 | 金额/期限/生效条件 | 参与方与角色 | 闭环(卖方融资) | 原始发布｜检索 | 来源URL | 置信度 |
|---|---|---|---|---|---|---|
| 0.6-1 Google↔Anthropic TPU | Google 最高投 **400 亿**（100 亿现付@$3500 亿估值 + 300 亿绩效/算力挂钩）；Anthropic 五年约 **2000 亿美元** Google Cloud 支出（含 **5GW TPU**，2027 起交付） | Google=投+云商；Anthropic=买+受投；Broadcom=TPU/GPU 供应商 | ✓三重闭环 | 2026-04/05｜2026-09-06 | [AIWiki](https://www.aiwiki.ai/wiki/anthropic_google_tpu_deal)；[OpenTools](https://opentools.ai/news/google-bets-40-billion-on-anthropic-as-claude-outpaces-gemini)；[AILearningGuides](https://ailearningguides.com/anthropic-200-billion-google-tpu-five-year-commitment/) | Medium |
| 0.6-2 Amazon↔Anthropic | Anthropic 十年内 >**1000 亿美元** AWS 支出（锁 5GW）；Amazon 即投 **50 亿** + 可追加至 **200 亿**（补足此前已投 80 亿） | Amazon=投+云商；Anthropic=买+受投 | ✓闭环 | 2026-04-20｜2026-09-06 | [Anthropic 官方](https://www.anthropic.com/news/anthropic-amazon-compute)；[CoinDeskCC](https://coindesk.cc/amazon-invests-5-billion-more-in-anthropic-secures-10-year-aws-deal-worth-100-billion-38529.html) | High |
| 0.6-3 OpenAI↔AWS | 现有 380 亿扩展 +1000 亿 = **1380 亿美元/8 年**；OpenAI 承诺约 2GW Trainium；Amazon 投 **500 亿**（150 亿即付 + 350 亿条件） | Amazon=投+云商；OpenAI=买+受投 | ✓闭环 | 2026-02-27｜2026-09-06 | [About Amazon](https://www.aboutamazon.com/news/aws/amazon-open-ai-strategic-partnership-investment) | High |
| 0.6-4 OpenAI Series I（1100 亿） | Amazon 500 + **Nvidia 300** + SoftBank 300；pre $7300 亿/post $8400 亿 | 投方兼部分供应商/生态方 | 含闭环（非全部金额回流） | 2026-02-27｜2026-09-06 | [InfoQ](https://www.infoq.cn/article/y688Ya2AFzphbj3b3CfR)；[AdwaitX](https://www.adwaitx.com/openai-microsoft-partnership-2026-funding-deal/) | Medium |
| 0.6-5 xAI E 轮 200 亿 + Nvidia 100 亿；xAI 后被 SpaceX 收购 | xAI 200 亿 E 轮，Nvidia 投 100 亿（占 50%）；SpaceX 收购后 Nvidia 持约 **210 亿 SpaceX 股**（2026-08 披露） | Nvidia=投+芯片商；xAI=买/受投 | ✓ | 2026-01/08｜2026-09-06 | [HelloMarvisAI](https://hellomarvisaitoday.com/articles/e1a557b1-8cb0-4eee-bf0d-b7ce9058bcd9) | Medium |
| 0.6-6 Google 租 xAI Colossus GPU | Google 向 SpaceX 付 **9.2 亿美元/月**，2026-10~2029-06，约 **11 万颗** NVIDIA GPU | Google=买方；xAI/SpaceX=卖方/算力方 | ✓租赁型闭环 | 2026-06-08｜2026-09-06 | [Rallies](https://rallies.ai/news/google-signs-920m-monthly-deal-for-110000-nvidia-gpus-at-spacex-data-center) | Medium |
| 0.6-7 Anthropic↔Azure（交叉确认） | Anthropic 承诺采 300 亿 Azure 算力；MSFT 投 **50 亿** + Nvidia 投 **100 亿**（合计 150 亿） | Microsoft=投+云商；Nvidia=投+芯片商；Anthropic=买+受投 | ✓典型闭环 | 2025-11-18｜2026-09-06 | [Anthropic](https://www.anthropic.com/news/microsoft-nvidia-anthropic-announce-strategic-partnerships)；[WinBuzzer](https://winbuzzer.com/2025/11/18/microsoft-nvidia-and-anthropic-forge-45-billion-alliance-to-scale-claude-on-azure-xcxwbn/) | High |
| 0.6-8 Nebius GPU 抵押融资 | **7.75 亿美元**有担保融资，GPU+合同现金流双抵押；附微软合同约 **194 亿/5 年** | Nebius=借款人；Microsoft=客户；Nvidia=供应商 | ✓ | 2026｜2026-09-06 | [TNW](https://thenextweb.com/news/lambda-1bn-private-debt-microsoft-lease-nebius-european-neocloud)；[CCIR](https://ccir.io/research/two-order-books) | Medium |
| 0.6-9 Nvidia PORTS-Pike（俄亥俄） | Nvidia 担保专属 AI 算力 4.25 IT-GW（+3.75 option）；OpenAI 为相关客户 | Nvidia=供应商+信用支持方；OpenAI=客户 | ✓供应商信用支持 | 2026-08-17｜2026-09-06 | [Nvidia News](https://nvidianews.nvidia.com/news/nvidia-guarantees-sb-energy-s-ports-pike-technology-campus-in-ohio-to-exclusively-host-nvidia-ai-compute) | Medium |
| 0.6-10 Meta↔AMD 1000 亿 GPU 协议 | 第三方报道口子（与 Nvidia 独家并存背景）；另 Oracle-Meta 200 亿云协议转述 | Meta=买；AMD=供应商 | ✓待证实 | 2026｜2026-09-06 | [Introl](https://introl.com/blog/meta-amd-100-billion-gpu-deal-nvidia-exclusivity) | Low |

### 0.6-B 非闭环融资与结构性更新

| 增量项 | 金额/要点 | 闭环 | 原始发布｜检索 | 来源URL | 置信度 |
|---|---|---|---|---|---|
| 0.6-11 Anthropic Series G | **300 亿美元**，GIC/Coatue 牵头，post-估值 **$3800 亿**，用于基础设施扩张 | ✗（纯融资） | 2026-02-12｜2026-09-06 | [Anthropic](https://www.anthropic.com/news/anthropic-raises-30-billion-series-g-funding-380-billion-post-money-valuation) | High |
| 0.6-12 OpenAI-Microsoft 排他结束 + 多云 | 微软解除 OpenAI 模型分销独家；OpenAI 可部署 AWS/Google Cloud | 结构性（开放化） | 2026-04-27/28｜2026-09-06 | [36Kr](https://m.36kr.com/p/3785761774345224) | High |
| 0.6-13 2026 capex 指引更新 | Amazon 上调至 **~2200 亿**；Google 官方演示 1800–1900 亿（次级报道 1950–2050）；Meta 收窄至 1300–1450 亿；MSFT 日历口径 1750–1900 亿 | ✗ | 2026 Q2 财报期｜2026-09-06 | [Platformonomics](https://platformonomics.com/2026/04/follow-the-capex-q1-2026-scoreboard/) | High/Medium |

---

> **执行状态**：第 0 章（执行日核验表 · 含抽查复核与增量补全）完稿。本章=宪法基线+增量快照，共 **14 条口径修正**（0.2 的 11 条 + 0.5 复核 4 项、其中与 0.2 折叠 1 项）与 0.3 监测清单。后续任何章节引用数字必须回到本章并按"截至 2026-09-06"标注。

## 0.7 宪法增补（第 2 章返工导出，2026-09-06 收尾备案，效力等同 0.2 的 11 条）

1. **置信度防洗白**：下游章节引用带置信度标签的数字时，必须**原样携带标签**（High/Medium/Low 及"推断/待增补"标注）；脱标签引用一律按**未标注数字**处理——即视同缺数，不得进入主演算。执行样例：2.4-1 关联方收入占比 20—62%（Low）被 2.13 列入重点抽查，即因该标签不可剥离。
2. **裁决线重锚备案**：第 8 章原裁决线"R 突破 0.3"已被第 2 章基线追平（2.11-B：k 加权合理中心 25—30%，逼近 0.3），单点穿越判据失效。改为：**R 中心值连续两个季度站上 0.3，或 B 口径 run-rate ≥5000 亿美元**，满足其一才构成"赛跑改写"。0.3 表首行已就地更新；第 2 章正文两处"穿越 0.3 监测哨"（2.3 敏感性、2.11-C）一律按本判据解读。
3. **矩阵引用纪律**：2.11-B 覆盖率的 13% 与 73% 端点均为**反向叠加组合**（13% = 收入下限 3200 × capex 上限 24400；73% = 收入上限 8900 × capex 下限 12200），非同一情景的自然配对。基准叙事只许引用同向带 **26—36%**；13% 与 73% 只能作为边界呈现，且必须标注"反向叠加组合"——禁止摘樱桃式引用单端点。
4. **债务分拆前置**：第 4 章压力测试必须按三类发行人分类运行，禁止混合口径：**(a) 母体 FCF 背书类**（hyperscaler 母公司债）、**(b) 项目级 SPV 无追索类**（Stargate 38B 银团、Oracle SPV 34B 等）、**(c) 纯玩家杠杆类**（CoreWeave DDTL、neocloud 私募信贷等）——三类违约传播路径不同，混算会同时高估与低估偿付断点位置（2.3 第 6 步交叉验证已暴露混合口径的测量误差）。
5. **多主体聚合口径防复发**（2026-09-06，A-2 仲裁导出）：凡跨章指令或宪法文本引用**多主体聚合口径数字**（合计/区间，如"C 合计"），必须标注**聚合范围与主体清单**；引用者不得假定读者能从上下文还原口径。执行样例：A-2 曾以"C 合计 0.93—1.73 万亿"指称 OpenAI 承诺簿，实为 OpenAI+Anthropic 聚合——已裁定改回 OpenAI 单独口径（见附录 A 与下方现行注记）。

---

# 第 1 章 · 资金闭环全景图谱

> 章内声明：本章产品是**结构地图**，不是涨跌预言。所有金额为快照值（截至 2026-09-06），引用核验表行号（`0.1-xx` / `0.5-xx` / `0.6-xx`）。循环回流率的**完整四段演算**按第 2 章"算术显式化"纪律执行；本章给出结构量级与回流回路的边集合。凡未坐实在官方公告边上的判断，一律标猜想。

## 1.1 快照与节点定义（地图边界）

**快照时点**：2026-09-06。**构成** = 宪法基线（2025 年签署的网络：`0.1-B`、`0.1-C` 主体、`0.6-7`）+ 2026 增量（`0.6-A`）。地图只收录已披露的**边**与**节点**，未披露的或有交易以**虚线**标注、不占面积。

**八类节点与各自的"不可不守之处"**（三才推演的立场框架先在此结构标注，详见第 7 章）：

| 节点 | 代表 | 不可不守之处（弈者之根） | 本闭环中的角色 |
|---|---|---|---|
| 半导体商 | Nvidia / AMD / Broadcom | 芯片定价权 + 数据中心收入增速 | **全网唯一净现金流巨头 → 实际背书人** |
| 超大规模云 | Microsoft / Google / Amazon / Oracle | 云定价权 + 自家 AI 叙事 | 既是闭环受益人又是潜在引爆人 |
| 模型实验室（最高承诺者） | OpenAI / Anthropic / xAI | 融资叙事不可间断 | 史上最烧钱的信用实体 |
| 算力租赁商（最杠杆） | CoreWeave / Nebius / Lambda | 租约续签率 + 再融资通道 | 第一张骨牌候选 |
| 债权市场（本轮新登场） | 银行 / 私募信贷 / 公开债持有人 | 只收利息 → 要求重构的态度拐点 | 沉睡的抵押权人 |
| 主权买方（X 变量） | 海湾基金 / 国家级项目 | 不按偿付逻辑出牌 | 缺口的不可预测填塞 |
| 项目 SPV / 表外结构 | Stargate / Hyperion / Colossus SPV | 透明度最低 | 断裂时放大信息不对称 |
| 电力/地理约束 | 台积电 / HBM / 电网 | 部署速率的物理上限 | 地利，物理天花板 |

## 1.2 四线流向图（边集合）

**四线定义**：`[股]` 股权投资流（卖方把钱投给买方）；`[合]` 算力合约流（买方采购回流为卖方收入）；`[芯]` 芯片物流（货真价实的 GPU/ASIC 交付）；`[债]` 债务流（第三方资金进入，抵押品为 GPU/合约现金流）。

**状态标记**：**实线** = 官方公告/高置信已签署；**虚线** = 未坐实/已弱化/或有条件（置信 Medium/Low）。

### 1.2-A Nvidia 芯片商闭环（闭环的心脏）

| 线 | 起 → 终 | 金额 | 期限/生效 | 状态 | 核验行号 |
|---|---|---|---|---|---|
| [股] | Nvidia→OpenAI | 原 $100B 框架（搁置）→ **$30B 股权**（Series I） | 2026-01 搁置原框架；$30B 于 Series I | **虚线→实线**(股权落点) | 0.1-B6、0.5-2 |
| [芯][合] | Nvidia→OpenAI→Nvidia | 10GW→5GW Vera Rubin 采购回流 | 首个 1GW 原定 2026H2 | 虚线（框架未转合同） | 0.5-2 |
| [股] | Nvidia→Anthropic | $10B | 三方合作（2025-11） | 实线 | 0.1-B9、0.6-7 |
| [股][债] | Nvidia→xAI/SpaceX | $10B 投资 → 约 $21B SpaceX 持股 | xAI 被 SpaceX 收购后转股 | 实线(中期) | 0.6-5 |
| [债/信用] | Nvidia→PORTS-Pike（俄亥俄） | 担保 4.25 IT-GW（+3.75 option），OpenAI 客户 | 2026-08-17 | 虚线（担保额无公开 $） | 0.6-9 |

### 1.2-B Microsoft 双重身份闭环（既投又卖）

| 线 | 起 → 终 | 金额 | 期限/生效 | 状态 | 核验行号 |
|---|---|---|---|---|---|
| [股] | 微软(27%)→OpenAI | 估值 $1350 亿 | 技术访问至 2032、解除云独占 | 实线 | 0.1-B12 |
| [合] | OpenAI→Azure | $250B | 未来数年 | 实线 | 0.1-B13 |
| [股] | 微软→Anthropic | $5B | 三方合作（2025-11） | 实线 | 0.1-B10、0.6-7 |
| [合] | Anthropic→Azure | $30B | 长期基础设施承诺 | 实线 | 0.1-B11、0.6-7 |
| [合] | （结构性）OpenAI/MSFT 排他结束→多云 | — | 2026-04 | 实线（开放化） | 0.6-12 |

### 1.2-C Amazon / Google / Oracle 闭环

| 线 | 起 → 终 | 金额 | 期限/生效 | 状态 | 核验行号 |
|---|---|---|---|---|---|
| [合] | OpenAI→AWS | $38B → **$138B** | 8 年；2GW Trainium | 实线 | 0.1-B4、0.6-3 |
| [股] | Amazon→OpenAI(Series I) | $50B（150 即付+350 条件） | 2026-02 | 实线 | 0.6-4 |
| [合] | Anthropic→AWS | >$100B | 10 年；5GW | 实线 | 0.6-2 |
| [股] | Amazon→Anthropic | $5B 即付 + 可 +$20B（+=既投 80 亿） | 2026-04 | 实线 | 0.6-2 |
| [股] | Google→Anthropic | $40B（100 现付@$3500 亿估 + 300 绩效） | 2026-04 | 虚线(绩效挂钩) | 0.6-1 |
| [合] | Anthropic→GCP | $200B | 5 年；5GW TPU，2027 起 | 虚线(交付期未至) | 0.6-1 |
| [合] | Google→xAI Colossus | $9.2 亿/月（≈11 万 GPU） | 2026-10~2029-06 | 实线（租赁） | 0.6-6 |
| [合] | OpenAI→Oracle | $300B | 5.5 年（待独立来源） | **虚线（低置信）** | 0.1-B2 |
| [债] | Stargate 项目融资 | $38B（JPMorgan+MUFG 银团） | Vantage 开发 TX/WI | 实线（银团） | 0.5-1 |

### 1.2-D 债务流（全链条，抵押品=GPU/合约现金流）

| 线 | 借款人→贷款方 | 金额 | 条款 | 状态 | 核验行号 |
|---|---|---|---|---|---|
| [债] | CoreWeave GPU 贷款 | $8.5B + $3.1B | SOFR+2.25% / 固定 ~5.9%，2032 到期，首个投资级 GPU-backed | 实线 | 0.1-C、0.6 |
| [债] | Nebius GPU 抵押 | $775M | GPU+合约双抵押；微软 ~$19.4B/5y 合同支撑 | 实线 | 0.6-8 |
| [债] | Meta-Blue Owl Hyperion | $27B（Blue Owl 80%/Meta 20%） | SPV 债券 | 实线 | 0.1-C、0.5-1 |
| [债] | Oracle 项目 SPV | $16B（MI）+ $18B（NM）等 | 银团/私募，Blue Owl 已退 MI | 实线(项目级) | 0.5-1 |
| [债] | xAI SPV | ~$12.5B 债务（GPU 担保）+ ~$7.5B 股权 | 200 亿租赁/自持结构 | 虚线（媒体口径） | 0.1-C |

## 1.3 三大核心闭环网络的解剖

> 本节回答：**同一批资金如何在闭环内转圈，并把"谁为谁融资→谁回流为谁的收入"钉在具体边上。**

### 1.3.1 OpenAI 网络（最大承诺买方）
- 边上的双重身份：微软（27% 股东 + Azure 供应商 + 收入分成受益人）、Amazon（Series I 500 亿 + AWS 供应商 + Trainium 受益方）、Nvidia（Series I 300 亿 + Vera Rubin 供应商的一方）。
- 收入侧命门：OpenAI ARR 约 $40B（`0.5-4`），但对微软约 20% 分成、上限 $38B 至 2030——**"账面收入"与"可支配收入"存在一个上限 $38B 的漏斗**。承诺侧：巨额算力承诺（微软 $250B、AWS $138B、Oracle $300B［低置信］…）多数随"未来数年"分期且与排他解除（`0.6-12`）后的多供应商再分布相互作用。
- 结构结论：OpenAI 的"采购"**不是**单一路径回流到单一卖方；它同时向微软、AWS、Oracle 承诺——**闭环网络是放射状+网状混合**。这降低了单一环节的绑定度，但也把缺口（承诺 vs 收入）分散在多家云商的表上，见第 2 章拆分。

### 1.3.2 Anthropic 网络（结构最完整的闭环标本）
- 一个受投方，四面伸手：**微软投 $5B + Azure 采购 $30B 回流微软；Nvidia 投 $10B（芯片配套）；Google 投 $40B + GCP 采购 $200B/5y 回流 Google；Amazon 投 $5-20B + AWS 采购 >$100B/10y 回流 Amazon。**
- 这是全图**卖方融资最纯粹的一环**：Anthropic 从三个云商各拿股权、又向三个云商各签回流采购，"股权→采购→消费"在四张表上同时加杠杆。
- 张榜口径：Series G $30B（GIC/Coatue）post-$3800 亿（`0.6-11`）为纯融资、非闭环；但把 Anthropic 的估值推到与承诺额同一量级，放大了"债务背后站着的其实是股权"的错配感（第 3 章会计解剖会把它视为表内表外的杠杆镜像）。

### 1.3.3 Microsoft 双重身份标本
- **既投又卖的极端形态**：对 OpenAI 27% 股权（`0.1-B12`）+ 对 OpenAI 收 $250B + 对 OpenAI 付分成上限 $38B；对 Anthropic $5B 投 + $30B 卖。**同一主体的"投资科目"与"应收账款"在互为镜像地增长。**
- 风险识别：若 OpenAI/Anthropic 收缩，微软同时面对**权益减记 + 应收账款减值**的双重冲击——这是"闭环共振器"论断最直接的一处支撑。

## 1.4 循环回流率：结构量级（完整演算见第 2 章）

> 第 2 章将有四段式演算（算式→输入→演算→敏感性）；此处给出供章节间引用的**定义与量级**。

- **回流率的定义**（闭环质量的核心指标）：`回流率 := 卖方对买方的投资（及相关采购返流） / 由该投资伙伴贡献的卖方收入`。分母更干净的替代：`关联方收入占比`（封闭体系很难用公开数据精确求值，见下方自检清单置信度标注）。
- **旗舰量级（Nvidia 芯片商视角）**：Nvidia 对客户全部股权投资 ≈ $30B（OpenAI，Series I）+ $10B（Anthropic）+ $10B（xAI/SpaceX）+ 或有 ≈ **$50B+**；而 Nvidia FY2026 数据中心收入 **$1937 亿**（`0.1-B、0.5-2`）。若以"投资伙伴回流占收入比例"粗估，股权投入仅是收入的 ~2.6%——**单看股权很小，但边际上这些投资正是换取"巨额采购承诺"的杠杆**。真正的放大器在采购承诺（OpenAI 5GW Vera Rubin → 芯片收入若干百亿级）。
- **缺口量级（快照）**：
  - 2026 四云 capex 指引合计 **~7000 亿**（`0.6-13`）；
  - OpenAI 承诺合计（官方口径 ~$1.4T/8y，第三方 ~$1.15T、2026 调整口径 $600–750B，`0.1-B8`）vs OpenAI ARR 约 **$40B**（`0.5-4`）——**即使按最保守承诺口径（$600B/8 年），年化 ~$75B vs ARR $40B**，仍处同一"数十亿 vs 数千亿"量级失衡；
  - 全行业可比口径 AI 收入 vs 超大规模 capex，比值处 **0.1–0.2** 量级（`0.1-B15`，口径不可混比警告）。
- **顺周期性的"快慢钟"**：闭环比值在扩张期被融资创新**抬高**（回流数量虚涨），在收缩期被收入确认/减记**压缩**——这就是"闭环既是加速器又是共振器"的量纲来源（详见 1.5）。

## 1.5 闭环的顺周期性论证：既是加速器，又是共振器

> 本小节是本报告"资金内在结构"的核心命题之一。论证分两层，缺一不可。

**（一）加速器侧（扩张期，为何越转越快）**
> 机制链条：**半导体商账面现金溢出 → 以投资换取客户采购承诺 → 采购回流为半导体/云商收入 → 收入推高市值/现金流 → 更强的融资能力 → 更大承诺。** 每一步都在强化前一步。
- 唯一天然加速源：**Nvidia 是全图上唯一拥有超额净现金流的节点**（芯片商，`0.1-B16` FY2026 收入 $1937 亿/利润率极高）。它是整个闭环的实际背书人：既有能力（现金）又有动机（绑定客户防流失、对冲切实的"客户集中度即命门"）。
- 云商的加速形态：微软/Google/Amazon 各自"先投后卖"，把股权对价转成近乎绑定的采购，等于用股权簿记去撬动云收入确认（第 3 章会计解剖展开）。
- 债权方的加速形态：私募信贷以"GPU 抵押 + 长期客户合同现金流"把杠杆接进来（CoreWeave A3 评级 → 可变出更便宜的钱），`0.1-C`、`0.6-8`——**信用让加速器能脱离 FCF 运转**，这是本轮与 2022 基线最可测的升级（FCF→信用迁移，慢变量）。

**（二）共振器侧（收缩期，为何断裂更快）**
> 机制链条：**任一节点跌破"不可不守之处" → 关联方收入占比暴露为虚增 → 权益减记 + 应收账款减值 + 信用重估 三路并发 → 传染沿"四线×多节点"的稠密边矩阵扩散。** 闭环的稠密连接在扩张期是润滑剂，在收缩期是共模故障传播通道。
- 共振的量化含义：**关联方收入占比越高，单点断裂对全网的 β 越高**。Anthropic 一个受投方对应三朵云的回流边，若它收缩，微软、Google、Amazon 三张表的"客户→投资方"同时受创（`0.6-2/1/7` 三闭环点成环）。
- 与历史对照的价值：这正好是 **1920s Insull 多层杠杆**（第 3 章）与 **Lucent/Nortel 卖方融资**（第 6 章）的现代复合体——但本轮多一个"抵押品本身按 30–50%/年贬值"的新增量（第 4 章"快钟"假说）。**这是"加速器"论成立而"共振器"论也同时成立的机制解释，不是矛盾。**
- 辩证（防选择偏差）：闭环亦可主动消化——若 Agent 能力跃迁使劳动替代收入提前爆发（不连续分支），五路径爬坡斜率陡增，顺周期性会在"收入侧"被真实产出部分对冲。**本报告对加速器·共振器作结构陈述，不因此下方向赌注。** 完整对冲检验在第 7 章，此处不越权。

## 1.6 2026 增量对地图的结构性改变（快照=宪法基线+增量）

1. **闭环多中心化（排他解除）**：微软解除 OpenAI 排他（`0.6-12`），OpenAI 寻求 AWS/Google 多云 → 从"微软单点闭环"走向"放射状多闭环"。这**降低单一绑定度，但增加全网边数**——共振器传Path更长。
2. **Nvidia 承诺形态改变**：$100B 框架搁置 → Series I $30B 股权（`0.5-2`）。**芯片商不再自曝大额投资承诺**，转向"小股权 + 高密度采购 + 信用担保（PORTS-Pike）"——背书方式从"资产负债投入"转为"隐性信用背书"，这正是要盯的新观测哨（第 4 章信用层）。
3. **Anthropic 成为全网最大"多向受投方"**：微软+Google+Amazon+Nvidia 四面，形成结构上最完整也最脆弱的闭环标本（`0.6-1/2/7`）。
4. **债务流全面提速**：CoreWeave A3/投资级（`0.1-C`）、Nebius 抵押（`0.6-8`）、Stargate $38B 银团（`0.5-1`）——**信用已在大面积替代 FCF**，支持"边际资金迁移"命题。
5. **Oracle 定位复杂化**：既是 Stargate 租户与 $300B 承诺低置信方，又是项目 SPV 融资主体（`0.5-1`）——加杠杆表观与经营回报的拉锯，是第 4 章重点剖析对象。

## 1.7 本章自检清单

**① 本章全部具体数字的来源核对结果**
- 全部金额与期限引用核验表行号（`0.1-xx`/`0.5-xx`/`0.6-xx`），来源为三路联网核验；无凭空数字。
- 估算值·置信度低：OpenAI→Oracle $300B（0.1-B2，Low）、OpenAI/$1.4T 承诺合计（多口径，0.1-B8，Medium）、Nvidia 关联方收入占比（本节为结构量级，非精确值，置信度低·须 Ch2 演算）、Google 租 xAI 单价（0.6-6，Medium）。

**② 四线流向图的实线/虚线置信度标注（用户点名要求，逐线声明）**
| 线（流类型） | 实线（高置信/已签署） | 虚线（中低置信/未坐实/已弱化/或有） |
|---|---|---|
| [股] 股权投资流 | Nvidia→Anthropic$10B；微软27%OpenAI；Amazon→OpenAI$50B；Amazon→Anthropic$5B+；微软→Anthropic$5B；Nvidia→xAI$10B | Nvidia→OpenAI 原$100B（搁置，落点$30B股权·Medium）；Google→Anthropic$40B（绩效挂钩）；xAI-为SpaceX转股（$21B·Medium） |
| [合] 算力合约流 | OpenAI→Azure$250B；OpenAI→AWS$138B；Anthropic→AWS$100B/10y；Anthropic→Azure$30B；Google→xAI月租$9.2亿 | Anthropic→GCP$200B（2027交付，交付期未至）；OpenAI→Oracle$300B（Low，未坐实） |
| [芯] 芯片物流 | Vera Rubin/TPU/Trainium/GPU 已交付与承诺流（结构性，多属框架） | OpenAI 5GW Vera Rubin / 10GW 框架（未转约束合同）；Broadcom 10GW ASIC |
| [债] 债务流 | CoreWeave$8.5B+$3.1B；Nebius$775M；Meta-Blue Owl$27B；Stargate$38B；Oracle 项目 SPV$16B/$18B | xAI SPV~$12.5B（媒体口径）；PORTS-Pike 担保额（无公开$） |

**③ 本章全部假设参数列表**
- 回流率定义假设：以"卖方对买方投资/由投资伙伴贡献收入"为口径；因公开数据无法精确拆分"Nvidia 收入中由投资伙伴贡献"部分，本章给量级、Ch2 演算给范围与敏感性。
- 快照时点假设：所有金额截至 2026-09-06 有效，配 0.3 监测清单持续刷新。
- 闭环边集合假设：只收录已披露边；未坐实边以虚线标注、不计入流量占比。
- 敏感性说明：若 OpenAI/$1.4T 采用调整后 $600B 口径，缺口量级下修但量级结构（数十亿收入 vs 数千亿承诺）不变；若微软分成口径净额化，OpenAI 可支配收入进一步下修，缺口扩大。

**④ 全章置信度最低的三处段落（供人工重点抽查）**
1. 1.4 节"回流率/关联方收入占比"（结构量级，非精确值）——最需要 Ch2 显式演算支撑。
2. 1.6-5 "Oracle 定位复杂化"的 $300B 承诺（Low）与 Nvidia 信用担保税额未公开。
3. 0.6-6 "Google 租 xAI 单价 $9.2 亿/月"（Medium，媒体口径）——若单价误差，1.2-C 该边金额整体偏移。

---

**执行状态**：第 1 章（资金闭环全景图谱）已完稿，含 1.2-A~D 四线流边集合、1.3 三大闭环网络解剖、1.4 回流率量级、1.5 顺周期性双论证、1.6 2026 增量影响、1.7 自检清单（含实线/虚线逐线置信度）。按"一次一转纪律"，本章至此结束，不续写下一章。

---

# 第 2 章 · 需求缺口算术与五路径承载力

> 章内纪律（四条，先于一切演算）：
> **① 算术显式化**：本章所有计算一律按"【算式】→【输入】（注明核验表/锚点表行号与置信度）→【演算】（逐步、禁止跳步）→【敏感性】（关键参数翻倍与减半双向检验）"四段呈现；无演算过程的结果一律无效。
> **② 时间维度对齐**：多年期承诺必须先年化（金额÷年数），才允许与年度收入/年度 capex 同框比较；存量与流量禁止混比。
> **③ 五路径重叠扣除**：同一美元可能同时计入两条路径（如企业买 Copilot 的预算本质上来自劳动替代节省），加总前必须声明重叠并扣减，禁止简单堆叠得出伪承载力。
> **④ 流量/存量分界**：本章只做"当年收入 vs 当年开支"的流量缺口；"收入能否覆盖折旧+资金成本"的存量偿付检验属第 3 章（会计层）与第 4 章（信用层），本章仅前向引用，不越权。
> 所有新增数据先入 **2.0 本章锚点表**（第 0 章核验表的本章增补件），行号 `2.0-n`；引用第 0/1 章数据沿用 `0.1-xx`/`0.5-xx`/`0.6-xx` 与第 1 章 1.4 节量级。所有快变量截至 **2026-09-06**。

## 2.0 本章锚点表（新增数据的登记与置信度）

> 本章动笔前联网核验的新增锚点。建议后续并入核验表 0.6 作为正式增补件；在此之前以 `2.0-n` 行号供本章引用。

| 行号 | 锚点 | 核验值（截至 2026-09-06） | 原始发布｜检索 | 来源URL | 置信度 | 备注 |
|---|---|---|---|---|---|---|
| 2.0-1 | Anthropic 年化收入 | **run-rate 超 650 亿美元**（2026-07 末）；2026-05 为 470 亿 | 2026-08-18 报道｜2026-09-06 | [ITP.net](https://www.itp.net/ai-automation/anthropics-annualised-revenue-run-rate-crosses-65-billion-as-claude-demand-surges)；[凤凰网](https://finance.ifeng.com/c/8w8saX8wF41) | Medium | run-rate 口径（年化速度），媒体核算非官方财报。 |
| 2.0-2 | ChatGPT 用户与付费 | 周活 **9 亿**（2026-02）；付费订阅 **5000 万+**、企业付费 **900 万+**；付费转化率约 5%；2026-08 广告扩展至欧洲 | 2026-02｜2026-09-06 | [AIWiki 汇编](https://www.aiwiki.ai/wiki/chatgpt/raw)；[新浪财经](https://cj.sina.com.cn/articles/view/7880068204/1d5b04c6c06801g396) | Medium | 转化率 5% 为第三方推算。 |
| 2.0-3 | M365 Copilot 定价 | 企业版 add-on **30 美元/用户/月**；批量折扣 2026-06-30 到期后统一牌价 | 2026｜2026-09-06 | [微软官方定价页](https://www.microsoft.com/en-us/microsoft-365-copilot/pricing)；[LLMGateway 解析](https://llmgateway.io/blog/microsoft-copilot-enterprise-pricing) | High | 牌价即溢价上限的天然锚。 |
| 2.0-4 | 企业 GenAI 支出 | 2025 年 **370 亿美元**（2024 年 115 亿，3.2x）；其中应用层 190 亿 | 2025-12｜2026-09-06 | [Menlo Ventures 年度报告](https://menlovc.com/wp-content/uploads/2025/12/menlo_ventures_enterprise_ai_report-2025-123125.pdf) | Medium-High | 路径①当期渗透率的实测锚。 |
| 2.0-5 | AI 模型与平台市场 | 2026 年全球终端支出 **640 亿美元**（2025 年 390 亿，+63.4%）；其中基础模型 234 亿（+104%） | 2026-07-20｜2026-09-06 | [Gartner 新闻稿](https://gcom.pdo.aws.gartner.com/en/newsroom/press-releases/2026-07-20-gartner-forecasts-worldwide-ai-platforms-and-models-market-to-grow-63-percent-in-2026) | High | 收入侧窄口径，与 0.1-B15 的支出侧口径严格区分。 |
| 2.0-6 | Nvidia 主权 AI 收入 | FY2026 约 **300 亿美元**（同比约 +150%~3x，约占总收入 14%） | 2026｜2026-09-06 | [第三方拆分·Zenodo](https://zenodo.org/records/20673594/files/Nvidia%20Powers%20Every%20Sovereign%20AI%20Programme%20on%20Earth.pdf?download=1)；[m8 深度](https://m8.com.cn/article/nvidia-fy2026-system-level-deep) | Medium | Nvidia 未单列主权分部，为第三方拆分。 |
| 2.0-7 | 美国劳动者报酬 | GDI 口径劳动者报酬（含福利）年化约 **15.75 万亿美元**；其中工资薪金 12.96 万亿 | 2026 最新季｜2026-09-06 | [FRED Table 1.10](https://fred.stlouisfed.org/release/tables?eid=42185&rid=53)；[FRED Table 2.1](https://fred.stlouisfed.org/release/tables?rid=53&eid=42509) | High | BLS ECEC 佐证：民用工人时均总补偿 48.05 美元（2025-06）。 |
| 2.0-8 | 全球劳动收入份额 | **52.4%**（2024，ILO 模型估计；2014 年为 53.0%） | 2025-05｜2026-09-06 | [ILO WESO Update](https://www.ilo.org/sites/default/files/2025-05/WESOUpdate_May2025_Embargo.pdf)；[ILO G20 技术报告](https://www.ilo.org/sites/default/files/2025-04/G20_TechnicalPaper%232_Policy%20measures%20to%20address%20inequalities%20and%20increase%20the%20labour%20income%20share.pdf) | High | 份额×全球 GDP 得全球劳动收入池。 |
| 2.0-9 | 生产率 J 曲线（机制出处） | Brynjolfsson–Rock–Syverson：GPT 采用期无形投资使测得生产率先低估、后反弹 | 2019 brief / 2021 AEJ:Macro｜2026-09-06 | [MIT IDE Brief](https://ide.mit.edu/sites/default/files/publications/2019-04JCurvebrief.final2_.pdf)；[MIT Sloan 解读](https://mitsloan.mit.edu/ideas-made-to-matter/a-calm-ai-productivity-storm) | High（机制） | 只给机制，**不给具体年数**（见 2.6-D）。 |
| 2.0-10 | MIT NANDA 试点实证 | 《The GenAI Divide: State of AI in Business 2025》：52 家企业访谈+300+ 公开项目+153 高管问卷，**95% 组织未见投资回报**；企业已投入 300—400 亿美元 | 2025-07/08｜2026-09-06 | [Fortune 报道](https://fortune.com/2025/08/18/mit-report-95-percent-generative-ai-pilots-at-companies-failing-cfo/)；[至顶网中文](https://m.zhiding.cn/article/3174640.htm) | Medium-High | 组织兑现率 k 的当期实证锚。 |
| 2.0-11 | 沙特主权部署 | 已部署 **150 亿美元+**（AWS 53 亿云区 + Google-PIF 100 亿 AI hub）；Humain 已收 1.8 万颗 GB200、再加 1.8 万颗、多台 Rubin 在谈 | 2026-04｜2026-09-06 | [ViaNews](https://vianews.market/tech-sector-trading-indices/saudi-arabia-deploys-15b-across-aws-google-cloud-nvidia-to-build-ai)；[MiddleEastInsider](https://themiddleeastinsider.com/2026/04/25/nvidia-saudi-arabia-2026/) | Medium | 主权路径当期流量锚之一。 |
| 2.0-12 | 全球知识工作者工资池（推算） | 美国约 1 亿知识劳动者 × 10—11 万美元 ≈ **10—11 万亿美元**；全球可触达（数字/白领）约 **25—30 万亿美元** | 2026｜2026-09-06 | [第三方方法学（LobeHub/Daniel Miessler 汇编）](https://lobehub.com/ko/skills/danielmiessler-substrate-knowledge-worker-global-salaries) | Low | 推算口径，仅作数量级锚，敏感性检验必做。 |

## 2.1 分子三级口径：A / B / C（先分类，后用数）

> 本节执行本章纪律：赛跑比值的分子**只用 A 或 B 并注明**；C 只作为"未来分母候选"单独列示，禁止混入当期比值。

### 2.1-A 三级口径定义与当期取值

**A 口径 · 实际 run-rate 年化收入**（"现在每月真实入账×12"）：

| 主体 | A 口径值 | 行号 | 置信度 |
|---|---|---|---|
| OpenAI | 约 **400 亿美元**（2026-08，约 33 亿/月×12） | 0.5-4 | High |
| Anthropic | 超 **650 亿美元**（2026-07 run-rate） | 2.0-1 | Medium |
| 其他实验室与模型 API（xAI/Mistral/Cohere/云商自研模型 API 转售） | 未系统核验，用 Gartner 模型与平台市场 640 亿（2.0-5）作行业交叉锚——注意该 640 亿与前两者之和 1050 亿**口径存在重叠与缺口并存的张力**（Gartner 统计窗口早于 7 月 run-rate 跃升），处理为区间 | 2.0-5 | Medium |
| 应用层（企业软件 AI 溢价+消费者订阅，2026 年化） | 约 **550—800 亿美元**（Menlo 应用层 190 亿为 2025 实测，2.0-4，按 +50—80%/年外推；消费者订阅见 2.7 演算） | 2.0-4、2.0-2 | Medium |

→ **A 口径行业合计：约 1600—2500 亿美元/年**（模型层 1050—1700 亿 + 应用层 550—800 亿；两半重叠部分已在应用层扣除模型 API 成本口径的粗略调整，残余重叠在 2.11 统一扣减）。

**B 口径 · 净可支配收入**（A 扣除关联方截留后才可用于支付算力账单的钱）：

| 截留项 | 机制 | 对 A 的影响 | 行号 |
|---|---|---|---|
| OpenAI→微软分成 | 约 20% 收入分成、至 2030 累计上限 380 亿美元 | OpenAI 净可支配 = 400×(1−20%) = **320 亿美元**（若 ARR 未净额化；是否已净额化未披露）；注：按 20%×400≈80 亿/年计，累计约 5 年即触及 380 亿上限——**该漏斗是暂时性结构**，触顶后回到 A 口径 | 0.5-4 |
| 云商投资附带的消费信用 | Google/Amazon/AWS 对被投方（Anthropic 等）的投资通常伴随云消费抵扣 | Anthropic 650 亿中或有 0—10% 以信用形式回流给云商 → 净额 585—650 亿 | 0.6-1、0.6-2（条款未公开，推断） |
| 行业层面综合折让 | 上述两类截留 + 关联方采购中的互惠折扣 | 对 A 打 **0—10% 折扣**（端点实证：B 下端 1455 ÷ A 下端 1600 = −9%；上端无截留 = 0%） | 本章推断（Medium） |

→ **B 口径行业合计：约 1450—2500 亿美元/年**（纯推导端点：下限 = OpenAI 320 + Anthropic 585 + 其他模型层 0 + 应用层 550 = 1455，即截留全发生；上限 = OpenAI 400 + Anthropic 650 + 其他模型层 650 + 应用层 800 = 2500，即无截留且不确定成分全取——两端均为极限情形，主用中心约 **1950 亿**）。

**C 口径 · 已签约未交付承诺**（只列示，禁入当期比值）：

| 主体 | C 口径值 | 年化（÷年数） | 行号 | 置信度 |
|---|---|---|---|---|
| OpenAI | 官方约 1.4 万亿/8 年；第三方拆分约 1.15 万亿；2026 调整口径 6000—7500 亿 | **750—1750 亿美元/年**（口径三档） | 0.1-B8 | Medium |
| Anthropic | GCP 2000 亿/5 年 + AWS >1000 亿/10 年 + Azure 300 亿（约 5 年） | **约 560 亿美元/年**（2000/5+1000/10+300/5） | 0.6-1、0.6-2、0.6-7 | High（金额）/ Medium（年化摊法） |
| xAI 及其他 | 未系统核验，**缺数**（待后续增补） | — | — | — |
| **C 合计（已核验部分）** | 约 **0.93—1.73 万亿**（OpenAI 0.60—1.40 万亿 + Anthropic 0.33 万亿，不计 xAI） | **1310—2310 亿美元/年**（750—1750 + 560；约 1300—2300） | — | Medium |

**C 口径的唯一合法用途**：未来分母候选。若 2030 年行业实际收入达到 C 口径年化值（1300—2300 亿美元），则 R 比值（对 1 万亿 capex）升至 0.13—0.23——**供给侧签约的承诺规模，恰好等于需求侧极限兑现才能支撑的收入规模**。承诺方事实上在赌五路径兑现（2.11 收束此点）。

### 2.1-B 分子口径的使用规则（本章执行声明）

- 赛跑比值 R 的分子：**用 B 口径为主**（因为偿付算力账单的是可支配的钱），A 口径为敏感性上界；每处注明。
- 任何段落出现"行业收入"字样时，必须同时标注 A/B 口径归属；C 口径只出现在"未来分母候选"语境。

## 2.2 分母口径表：机构口径差异与主口径锁定

> 执行 0.2-9 口径纪律：IDC 的"AI 支出"≠ Gartner 的"AI enabled 总支出"≠ 超大规模 capex。比值给区间，不给伪精确单点。

| 口径（机构） | 统计域 | 2026 年值 | 与"AI 算力 capex"的关系 | 行号 |
|---|---|---|---|---|
| 窄①：四大云 capex（Platformonomics/ValueAddVC 整理） | MSFT/GOOG/AMZN/META 数据中心+设备 | **6950—7250 亿美元**（更新：Amazon ~2200 亿、Google 1800—1900 亿、Meta 1300—1450 亿、MSFT 日历口径 1750—1900 亿；分项为约数，加总以核验值为准） | 最贴近但**不含** Oracle/CoreWeave/neocloud/xAI 自建 | 0.1-A3、0.6-13 |
| 窄②：超大规模资本开支（UBS） | 含 Oracle 等更全的 hyperscaler | 约 **1.0 万亿美元** | 本章主口径的上界候选 | 0.1-B15 |
| 中：IDC"AI 支出" | 硬件+软件+服务中 AI 相关 | 约 5145 亿美元 | **支出≠capex**（含软件服务），与收入不可直接比 | 0.1-B15 |
| 宽：Gartner"AI enabled 总支出" | 一切含 AI 成分的 IT 支出 | 约 **2.59 万亿美元** | 计数最通胀，**禁止**作为赛跑分母（0.2-9） | 0.1-B15 |
| 对照（收入侧）：Gartner 模型与平台市场 | 模型/平台终端支出 | 640 亿美元 | 这是**分子侧**口径（2.0-5），列出以防误用 | 2.0-5 |

**主口径锁定**：本章赛跑分母 = **6950 亿—1.0 万亿美元**（窄①至窄②区间）。中/宽口径仅作背景，不入比值。

## 2.3 核心缺口算术：赛跑比值 R（四段式）

**【算式】** `R = B 口径行业 AI 年收入 ÷ 年度 AI 算力 capex`；`缺口 = capex − B 口径收入`（流量口径，纪律④：存量偿付见第 3/4 章）。

**【输入】**
- 分子（B 口径）：1450—2500 亿美元/年，中心约 1950 亿（2.1-A 推导；构成：OpenAI 320—400 亿［0.5-4］+ Anthropic 585—650 亿［2.0-1］+ 其他模型层 0—650 亿 + 应用层 550—800 亿［2.0-2、2.0-4］；下端=截留全发生，上端=无截留）。
- 分母：6950 亿—1.0 万亿美元（2.2 主口径；0.1-A3、0.6-13、0.1-B15）。

**【演算】**（区间四则，逐步）
- 第 1 步（最小比值）：R_min = 1450 ÷ 10000 = **0.145**。
- 第 2 步（最大比值）：R_max = 2500 ÷ 6950 = **0.360**。
- 第 3 步（中心值）：分子中值 1950 亿 ÷ 分母中值 8500 亿 = **0.229**。
- 第 4 步（缺口）：G_min = 6950 − 2500 = **4450 亿美元**；G_max = 10000 − 1450 = **8550 亿美元**；中心 ≈ 8500 − 1950 = **6550 亿美元/年**。
- 第 5 步（与第 1 章 1.4 对账）：1.4 节声明"全行业可比口径比值处 0.1—0.2 量级"（`0.1-B15`）。本章细化为 **0.15—0.36、中心 0.23**——量级一致，上界上移主因是 Anthropic run-rate 跃升（2.0-1，第 1 章写作时点未纳入的增量）。此为**细化**而非改口。
- 第 6 步（与债务增量交叉验证、口径显式化）：先明确"四至五成"的分子分母。
   - **分母（算术需求，= 必须靠外部融资的年度流量）** = 中心缺口 6550 亿/年 − 云商内部可消化 2000—3000 亿/年（2.9 演算，路径④）= **3550—4550 亿/年**。注意它不是 capex 增量（2025→2026 +3100 亿，0.1-A2/A3）、也不是缺口中心值本身（6550 亿）——它是"缺口刨去内部腾挪后、真正需要外部资本市场出钱的部分"。
   - **分子（实测外部融资流量）** = 两年（2024 末→2026-06 末）表内外增量合计：四家长期债务 +2099 亿（0.1-A6：1320→3419 亿）+ 私募信贷流向项目融资约 1250 亿（0.1-C8）+ Stargate 38B 银团（0.5-1）+ Oracle 项目 SPV 34B（0.5-1）= 2099+1250+38+34 ≈ **3420 亿/两年 → 年化约 1710 亿**。
   - **比值**：1710 ÷ (3550—4550) ≈ **38%—48%**，即"四至五成"。
   - **口径对不齐的诚实声明**：分子是"两年累计实测"，分母是"年度需求"，故采用年化分子对比。**38—48% 是下界**，因分子可能低估（私募信贷与表外或有设施未完全捕获）；未含股权的部分解释的是剩余 52—62% 融资的来源结构（股权+存量现金，未逐项核验）——量级与方向一致，缺口命题获得独立数据簇支撑。

**【敏感性】**
- 分子 ×2（收入超预期，如 Agent 商业化跃升）：R = 0.29—0.72，中心 0.46——**穿越 0.3 监测哨**（0.3 章第一条裁决线改写条件）。
- 分子 ÷2（ARR 虚高证伪/退款潮）：R = 0.07—0.18，中心 0.11——回落至 0.1 附近区，缺口命题强化。
- 分母 ×2（capex 再翻倍至 1.4—2 万亿）：R = 1950 ÷ 14000—20000 = **0.10—0.14（中心 0.12）**——缺口绝对额扩至 1.2 万亿级，债务层压力倍增（第 4 章）。
- 分母 ÷2（电力约束硬顶，0.1-C14/C15，capex 增速骤停）：R = 1950 ÷ 3475—5000 = **0.39—0.56（中心 0.46）**——**比值改善但系"分母坍缩"型改善，不等于健康**（此为结构性辩证：R 上升有两种成因，收入驱动=健康，capex 崩塌=病理，须看分子分母各自斜率，见 2.11 双斜率）。

## 2.4 循环回流率与关联方收入占比（承接第 1 章 1.4 的完整演算）

> 第 1 章 1.4 给出定义与量级（股权投入 ≈ 收入的 2.6%），其自检清单声明"须 Ch2 演算"。本节兑现。两视角：Nvidia（闭环心脏）与 Anthropic（结构最完整标本，第 1 章 1.3.2）。

### 2.4-1 Nvidia 视角：股权换承诺的回收期

**【算式】** `股权投资 / 年化采购回流中的芯片份额 = 投资被年收入覆盖所需年数（回收期）`。

**【输入】**
- Nvidia 对买方股权投资：OpenAI 300 亿（Series I，0.5-2）+ Anthropic 100 亿（0.1-B9/0.6-7）+ xAI/SpaceX 100 亿（0.6-5）≈ **500 亿美元**（含 PORTS-Pike 担保则更高，担保额未公开，不计入）。
- 投资伙伴（OpenAI+Anthropic+xAI）年化采购承诺：OpenAI 750—1750 亿/年（0.1-B8 三口径）+ Anthropic 约 560 亿/年（2.1-C）+ xAI 缺数 → **1310—2310 亿/年**。
- 芯片占数据中心总成本比例：约 **50—65%**（行业通例推断：其余为土地/电力/机架/组网/运维；无单一权威出处，置信 Medium-Low，标注为推断）。

**【演算】**
- 第 1 步（回流中芯片份额）：1310—2310 亿 × 50—65% = **655—1500 亿美元/年**（这是投资伙伴采购回流中流向芯片商的量级上界——注意其中还包含 AMD/Broadcom 份额，Nvidia 实得为其一部分）。
- 第 2 步（Nvidia 实得上界）：假设 Nvidia 在上述采购中占 60—80%（其份额受 AMD 6GW、Broadcom 10GW 分流，0.1-B5/B7）→ **390—1200 亿美元/年**。
- 第 3 步（对照总收入）：Nvidia FY2026 数据中心收入 1937 亿（0.1-B16）。投资伙伴贡献的收入占比 = 390—1200 ÷ 1937 = **20%—62%**——区间过宽，正说明**公开数据无法拆分"投资伙伴贡献收入"**（第 1 章 1.7 已声明此为最低置信度项）。
- 第 4 步（回收期）：股权 500 亿 ÷ 年化实得 390—1200 亿 = **0.4—1.3 年**？——**此演算暴露一个陷阱**：采购回流是收入不是利润。Nvidia 数据中心毛利率约 70—75%（FY2026 口径，公司披露区间，Medium-High），净利率口径更窄。以毛利计：500 亿 ÷ (390—1200×70%) = **0.6—1.8 年**；以自由现金流计（假设为毛利的 50—60%）：500 ÷ (273—840 × 50—60%) = 500 ÷ 136—504 ≈ **1.0—3.7 年**。
- 第 5 步（修正第 1 章量级表述）：第 1 章 1.4 的"股权仅是收入的 ~2.6%"是**存量投资/当年流量**的静态比；正确的问题是**回收期**——按承诺全额兑现，回收期毛利口径 0.6—1.8 年、现金流口径 1.0—3.7 年，**投资本身并不亏**；但前提是"承诺全额兑现"（0.1-B8 三口径差异高达 2.3 倍，且 Oracle 3000 亿为 Low 置信）与"采购真流到 Nvidia"（受 AMD/Broadcom 分流）。**闭环的脆弱点不在回收期长短，而在承诺兑现率与分流率的乘积**。

**【敏感性】**
- 承诺兑现率 ÷2（仅一半落地）：回收期 2—7 年；÷4（电信周期式崩塌，第 6 章 Lucent 对照：承诺/发放/未偿三口径可差 5 倍，0.1-C10）：回收期 4—15 年——投资减值风险实质化。
- Nvidia 份额 ÷2（AMD/Broadcom 分流加速）：回收期 2—7 年。
- 双杀（兑现率÷2 且份额÷2）：回收期 4—15 年+，且收入基数本身下修——**这就是第 1 章 1.5"共振器"的量化入口**。

### 2.4-2 Anthropic 视角：每 1 美元股权撬动多少采购（全章最干净的闭环演算）

**【算式】** 本小节两个量必须分清（定义显式化）：
- `撬动倍数 ≡ 采购承诺总额 ÷ 买方实付股权`（存量静态比：每 1 美元实付股权撬动多少美元多年期采购承诺，无量纲倍数；演算即 3300÷300=11.0、3300÷800=4.1）。
- `覆盖比 = ARR（卖方当期收入速度）÷ 年化采购承诺（供给侧当期交付/确认速度）`（流量对流量：ARR 是否足以"覆盖"承诺的年化交付额；>1 表示 ARR 已超当年应该确认的承诺，<1 表示不足）。
- **区别**：撬动倍数的**分母**是股权（资本方出资）、**分子**是采购承诺；覆盖比的分子是 ARR（被投方收入）、分母是承诺年化——两词易混，本稿严格区分：撬动 4—11 倍是"每元股权→采购承诺元数"，覆盖比是"ARR→承诺年化"。

**【输入】**
- 实付股权：Google 100 亿现付（400 亿中 300 亿为绩效挂钩，0.6-1）+ Amazon 50 亿即付（0.6-2）+ 微软 50 亿（0.6-7）+ Nvidia 100 亿（0.6-7）= **300 亿美元实付**；上限口径（Amazon 追加至 200 亿 + Google 绩效 300 亿全落地）= **800 亿美元**。
- 采购承诺：GCP 2000 亿/5 年 + AWS >1000 亿/10 年 + Azure 300 亿 ≈ **3300 亿美元**（0.6-1、0.6-2、0.6-7）。
- Anthropic ARR：超 650 亿美元（2.0-1，Medium）。

**【演算】**
- 第 1 步（撬动倍数）：3300 ÷ 300 = **11.0 倍**（实付口径）；3300 ÷ 800 = **4.1 倍**（上限口径）。→ **每 1 美元实付股权撬动 4—11 美元采购承诺**。
- 第 2 步（年化承诺）：2000/5 + 1000/10 + 300/5 = 400 + 100 + 60 = **560 亿美元/年**。
- 第 3 步（Anthropic 覆盖比，分子=A 口径 ARR 650 亿）：650 ÷ 560 = **1.16 倍**——ARR 已超年化承诺。两端数字：分子 = Anthropic ARR 650 亿（2.0-1，A 口径；Anthropic 无微软式分成，其净可支配≈A，故不另列 B）；分母 = 年化承诺 560 亿（GCP 2000/5+AWS >1000/10+Azure 300/5，2.1-C）。
- 第 4 步（对照 OpenAI 覆盖比，分子按 A/B 两档，分母同取最保守承诺年化 750 亿即 0.1-B8）：
   - A 口径：400 ÷ 750 = **0.53 倍**；
   - B 口径（扣微软分成 20%，0.5-4）：320 ÷ 750 = **0.43 倍**；
   → OpenAI 覆盖比 = **0.43—0.53 倍**。两端数字：分子 = OpenAI ARR 400 亿（A，0.5-4）或 320 亿（B = 400×(1−20%)）；分母 = 最保守承诺年化 750 亿（0.1-B8 三口径取最低档）。
- 第 5 步（结构判读）：**Anthropic（1.16x）与 OpenAI（0.43—0.53x）是同一闭环结构的两个健康度样本**。但两点辩证保留：(a) Anthropic 的 650 亿 ARR 为 2026-07 单月年化，持续性未经验证（2026-05 才 470 亿，两个月 +38%，斜率若衰减则覆盖比回落）；(b) 承诺是未来 5—10 年的刚性支出，ARR 是当期速度——**若 ARR 增速降至承诺交付增速之下，覆盖比将反转**（条件语句，不作方向押注）。

**【敏感性】**
- ARR 衰减 ÷2（325 亿）：覆盖比 0.58x，落入 OpenAI 区间。
- 承诺加速 ×2（GCP 提前交付/追加）：年化 1120 亿，覆盖比 0.58x。
- 双向叠加（ARR÷2 且承诺×2）：覆盖比 0.29x——三家云商同时面对"应收账款+权益减记"双重冲击（第 1 章 1.3.3 微软标本的量化入口）。

**关联方收入占比（缺数声明）**：Nvidia/微软/Google/Amazon 收入中"来自投资伙伴"的精确占比，公开财报**均未拆分**。本章以 2.4-1 第 3 步的 20%—62% 区间作代理（置信 Low），正式拆分**待第 1 章增补件或后续财报专项**；在此之前，任何引用单一数值（如"过半"）的说法一律视为未核验。

## 2.5 五路径总纲：定义、重叠矩阵与加总规则

| 路径 | 定义（钱从哪个池子来） | 当期量级（2026，演算见各节） | 重叠关系 |
|---|---|---|---|
| ① 劳动替代套利 | 企业工资池中转化为 AI 工具支出的部分 | 实测 370 亿美元（2.0-4） | 与③重叠（企业软件 AI 溢价的预算源头即工资池） |
| ② 消费者订阅与广告 | 个人钱包（月费/广告变现） | 约 250—350 亿美元 | 与①③基本不重叠（C 端独立） |
| ③ 企业软件 AI 溢价 | SaaS/Office 加价传导 | 约 300—500 亿美元 | 与①重叠（同一企业预算） |
| ④ 云商利润池自我消化 | 云商既有业务现金流内部转移 | 约 2000—3000 亿美元 | **不产生外部新收入**（左口袋到右口袋），与①—③性质不同 |
| ⑤ 主权与公共部门采购 | 国家资本（不按偿付逻辑出牌，第 1 章 1.1） | 约 320—450 亿美元 | 与④部分重叠（主权合同经由云商） |

**加总规则**：外部收入 = ① + ② + ③ + ⑤ − 重叠项（①∩③ 约 100—200 亿）；④单列，不计入"收入"，计入"资金来源"。**五路径不是互斥集合**——这是承载力测算最容易被高估的地方。

## 2.6 路径① 劳动替代套利（全章重心）

> 链条四要素：**工资池（池子多大）→ 转化率（当前多少）→ 工具支出（省下的钱多少流向 AI）→ 爬坡时间线（多久）**。

### 2.6-A 工资池（W）

**【算式】** `W = 劳动收入池 × 可触达子池比例`。

**【输入】**
- 全球劳动收入：ILO 份额 52.4%（2024，2.0-8，High）× 全球名义 GDP 约 115—120 万亿美元（IMF 2025 量级，公开常引，Medium）≈ **60—63 万亿美元/年**。⚠️ 口径注记：ILO 份额为 PPP 基模型估计，配名义 GDP 属简化桥接，误差 ±20%，故只用数量级。
- 美国锚（交叉验证）：劳动者报酬 15.75 万亿（2.0-7，High）——美国约占全球劳动收入 25%，反推全球 63 万亿 ✓ 数量级自洽。
- 可触达子池（知识/数字工作者）：美国 10—11 万亿（2.0-12，Low）；全球 25—30 万亿（同源推算，Low）。

**【演算】**
- 第 1 步：全球劳动收入 60—63 万亿 × 可触达比例 40—48%（25—30÷60—63）→ **W ≈ 25—30 万亿美元**，取中心 **27 万亿**。
- 第 2 步（美国子锚）：10.5 万亿（中心）。

### 2.6-B 转化率的当期实测（p₀）

**【算式】** `p₀ = 当期企业 GenAI 支出 ÷ 可触达工资池`。

**【输入】** 企业 GenAI 支出 370 亿美元（2025，Menlo，2.0-4，Medium-High）；W = 27 万亿（2.6-A，Low）。

**【演算】**
- 第 1 步：p₀ = 370 ÷ 270000 = **0.137%**（全球可触达口径）。
- 第 2 步（美国口径交叉）：370 ÷ 105000 = 0.35%（若支出六成发生在美国，则美国本土渗透率约 0.21%）——无论哪种口径，**当期渗透率不足 0.4%**。
- 第 3 步（构成分解，验证口径自洽）：p = s_技术 × k × c（s_技术=AI 当前可处理的知识工作份额，估 20—40%；k=组织兑现率；c=工具捕获率，软件经济学惯例 10—30%）。取 s=30%、c=20% → 反解 k = 0.137% ÷ (30%×20%) = **2.3%**——与 NANDA"95% 试点未见回报、仅 5% 跨越鸿沟"（2.0-10）**数量级吻合**（2.3% vs 5%，同一量级的组织摩擦实证）。✓ 两个完全独立的数据源（Menlo 支出侧 + NANDA 组织侧）交叉锁定了 k ≈ 2—5%。

### 2.6-C 工具支出与远期情景（条件语句，非预测）

**【算式】** `路径①收入(t) = W × s_技术 × k(t) × c`。

**【输入】** W=27 万亿（Low）；s_技术=30%（区间 20—40%，推断 Medium）；k(2026)=2—5%（NANDA 反推，Medium）；c=20%（区间 10—30%，推断 Medium-Low）。

**【演算】**（2030 条件情景，k 是唯一变量）
- 第 1 步（基准情景：k 爬至 10—35%，即 J 曲线中段兑现，NANDA 失败率从 95% 降至 65—90%）：p = 30%×(10—35%)×20% = 0.6—2.1% → 收入 = 27 万亿 × 0.6—2.1% = **1600—5700 亿美元/年**。
- 第 2 步（激进情景：p 直接达 2—5%，隐含 k 过半）：收入 = **5400—13500 亿美元/年**。⚠️ 该情景隐含组织兑现率从 ~2% 跃至 50%+，**历史上没有一项企业软件在 5 年内完成这种跃迁**（ERP/CRM 渗透至 50% 用了 10—15 年量级，推断 Low）——除非发生不连续分支（2.12 前向引用，第 7 章）。
- 第 3 步（悲观情景：k 停滞于 5%）：收入 ≈ 810 亿美元/年。

**【敏感性】**（双向）
- W ×2（54 万亿，若把蓝领可自动化部分全计入）/ ÷2（13.5 万亿，仅英语市场知识工作）：基准情景收入 3200—11400 亿 / 800—2850 亿——**池子大小只影响幅度，不改变"k 是瓶颈"的结论**。
- c ×2（40%，AI 定价权极强）/ ÷2（10%，同质化竞价）：基准情景 ×2 / ÷2——**租金曲线（0.5-3：H100 长约 1.70→2.35 美元，现货 2.79→2.82 企稳）正是 c 的实时市场读数**：长约回升说明 c 短期未崩，现货企稳说明 c 也未扩张。
- s_技术 ×2（60%）/ ÷2（15%）：同比例放大/收缩。

### 2.6-D 爬坡时间线（J 曲线的出处审计——本章方法论要点）

用户基线假设"企业采用 J 曲线 3—7 年"。出处审计结果：
1. **机制出处（有）**：Brynjolfsson–Rock–Syverson《The Productivity J-Curve: How Intangibles Complement General Purpose Technologies》（2.0-9，NBER→AEJ:Macro 2021）：GPT（通用目的技术）采用需要互补性无形投资（流程再造/组织学习/数据治理），**测得生产率先降后升呈 J 形**——机制成立，但该文献**不给出具体年数**。
2. **当期实证（有）**：MIT NANDA《The GenAI Divide》（2.0-10）：企业已投 300—400 亿美元，**95% 组织未见回报**——J 曲线目前处在"下弯段"的实证。
3. **历史锚（有）**：电力（David 1990 发电机悖论，学界常引）约 40 年完成工厂级渗透；ICT/计算机化（J 曲线论文的实证对象）1990s 投资→2000s 生产率反弹，约 10—15 年。
4. **"3—7 年"区间（无单一权威出处）**：**降格声明——该区间为本报告的分析性推断**（推断链：企业软件部署 1—3 年 + 组织学习 1—2 年 + 规模化复制 1—2 年；置信度 Low），并以三条硬锚（J 曲线机制、NANDA 实证、历史 GPT 采用 10—40 年）框定其**下限不低于 3 年、上限可展至 10—15 年**。
5. **对演算的处置**：2.6-C 基准情景（k 从 2—5% 爬至 10—35%）隐含爬坡期 3—7 年（推断）；悲观情景隐含 7—14 年。**承诺交付期与之对照**：Stargate 4 年（0.1-B1）、GCP 2027 起 5 年（0.6-1）、AWS 8—10 年（0.6-2/0.6-3）——两列时间轴大体重叠（2027—2031），**但若爬坡取上限（7—14 年），2028—2032 年将出现"承诺刚性交付 vs 收入尚未爬起"的空窗**——这是缺口的时间结构本质：**池子足够大，水管足够细，而账单是按交付期刚性到期的**。

## 2.7 路径② 消费者订阅与广告

**【算式】** `收入 = 付费用户 × ARPU + 广告`。

**【输入】** ChatGPT 周活 9 亿、付费 5000 万+、企业付费 900 万+（2.0-2，Medium）；Plus 定价 20 美元/月（公开牌价，High）；OpenAI ARR 400 亿中消费者 <50%（0.5-4，High）；ChatGPT Ads 2026-08 扩展欧洲（2.0-2，Medium）。

**【演算】**
- 第 1 步（ChatGPT 订阅）：5000 万 × 20 × 12 = **120 亿美元/年**。
- 第 2 步（企业/Team 档）：900 万 × 约 300（25/月档均价估）× 12 ≈ **27 亿美元/年**。
- 第 3 步（品牌合计）：约 **150 亿美元**。交叉验证：OpenAI ARR 400 亿 × 消费者 <50% ≈ ≤200 亿（含广告与其他）✓ 两条独立路径同量级（150 vs ≤200 亿）。
- 第 4 步（行业加总，含 Gemini/Claude/Copilot Pro/Meta AI 等）：ChatGPT 占消费者市场主导（周活为五大竞品之和两倍，2.0-2），行业 ≈ **250—350 亿美元/年**。
- 第 5 步（占缺口比重）：300 亿（中心）÷ 6550 亿（2.3 缺口中心）≈ **4.6%**。

**【敏感性】**
- 转化率 ×2（5%→10%，付费破 1.8 亿）：行业 500—700 亿，占缺口 ~9%。
- 转化率 ÷2（2.5%）：行业 125—175 亿，占缺口 ~2%。
- 广告变量：Ads 欧洲扩展的增量未披露——**列为监测哨**（若广告 ARPU 达搜索级，路径②上限可上一个数量级；此为条件语句，无当期数据支撑，降格为猜想）。

## 2.8 路径③ 企业软件 AI 溢价

**【算式】** `溢价收入 = AI 加价席位 × 加价额`。

**【输入】** M365 Copilot 牌价 30 美元/用户/月（2.0-3，High）；Copilot 付费席位未披露（**缺数**，微软不单列）——用区间假设 3000 万—1 亿席（推断，Low）；Menlo 应用层 190 亿（2025，2.0-4，Medium-High）。

**【演算】**
- 第 1 步（Copilot 上界）：1 亿席 × 30 × 12 = **360 亿美元/年**；下界：3000 万席 × 360 = **108 亿美元/年**。
- 第 2 步（行业加总，Salesforce/Adobe/SAP/Google Workspace 等同类加价）：应用层 2025 实测 190 亿（2.0-4）→ 2026 年化按 +50—80% → **285—340 亿**；与第 1 步 Copilot 区间（108—360 亿）交叉印证（两法同为 300 亿量级）→ **行业 300—500 亿美元/年**（上端含 Menlo 覆盖外的席位与年化惯性）。
- 第 3 步（占缺口）：400 亿（中心）÷ 6550 亿 ≈ **6.1%**。

**【敏感性】**
- 席位 ×2：600—1000 亿；÷2：150—250 亿。
- 定价 ×2/÷2（牌价 60 或 15 美元）：同比例——注意 2.0-3 的结构性事实：**批量折扣 2026-06-30 到期、统一牌价**，说明微软当前在测试 c（捕获率）的上限而非降价走量——与 2.6-C 的租金读数（长约升/现货平）互为印证：**卖方在收 c，买方在等 k**。

## 2.9 路径④ 云商利润池自我消化

**【算式】** `内部可挪用 = 经营现金流 − CapEx`；承载力 = 该余额 + 存量现金消耗空间。

**【输入】** H1-2026 五大 CapEx/OCF = **96%**（2024 年 50%、2025 年 68%，0.1-A6，Medium）；2025 合计 FCF 1913 亿（0.1-A6）；四家长期债务 1320 亿（2024 末）→ 3419 亿（2026-06 末）（0.1-A6）；2026 四云 capex 7000 亿±（0.6-13）。

**【演算】**
- 第 1 步（隐含 OCF）：若 96% 全年成立，OCF ≈ 7000 ÷ 0.96 ≈ **7290 亿美元**。
- 第 2 步（隐含 FCF）：7290 − 7000 ≈ **290 亿美元**——对照 2025 年 FCF 1913 亿：**一年内 FCF 被压缩 85%**。
- 第 3 步（对照验证）：2025 年 OCF ≈ FCF 1913 + CapEx 3828 ≈ 5740 亿（四云口径加回）；2026 年 7290 亿 → OCF 年增 +27%——现金流仍在涨，但**全部增量+存量利润已被 capex 吸干（96%）**。
- 第 4 步（承载力结论）：路径④当期承载 = 2000—3000 亿/年（OCF 中未被 AI capex 占用的部分+可压缩的股东回报空间；股东回报精确数未核验，不硬算，以 96% 比值反推其"已被迫动用存量现金或举债"——债务两年 +2099 亿即实测证据，0.1-A6）。
- 第 5 步（结构判读）：**路径④已接近满负荷**。边际承载力 ≈ OCF 增速（约 +15—25%/年）× 基数 ≈ 每年新增 1100—1800 亿，而 capex 年增量 2025→2026 为 +3100 亿——**缺口增量已结构性溢出利润池，只能进债务层**（FCF→信用迁移，第 1 章 1.5 加速器第三形态，第 4 章展开）。

**【敏感性】**
- OCF 增速 ×2（+40—50%/年）：边际承载力 2200—3600 亿，勉强追平 capex 增量——但五大 OCF 历史 Compound 增速 10—20%，翻倍无先例（推断）。
- OCF 增速 ÷2（+7—12%）：承载力 550—900 亿，债务层压力倍增。
- 比值情景：若 CapEx/OCF 突破 100% 并持续——**净举债经营**，监测哨设 100% 线（0.3 章补充：当前 96%，距线一步）。

## 2.10 路径⑤ 主权与公共部门采购

**【算式】** `主权流量 = 已兑现年采购额；远期 = 计划 × 兑现率`。

**【输入】** Nvidia 主权 AI FY2026 约 300 亿（2.0-6，Medium）；沙特已部署 150 亿+（2.0-11，Medium）；法国 1090 亿欧元/至 2030、沙特 60 万卡、UAE Stargate 等（[ValueAddVC 汇编](https://valueaddvc.com/blog/sovereign-ai-why-every-country-is-now-building-its-own-llm)，Medium-Low）。

**【演算】**
- 第 1 步（当期）：**320—450 亿美元/年**。构成：Nvidia 主权口径 300 亿（2.0-6，第三方拆分）+ 经云商转手的主权合同年化 20—30 亿（AWS 沙特区 53 亿、Google-PIF 100 亿多年期年化，2.0-11；与 Nvidia 口径部分重叠，下端只计 20 亿净增量）；上端 450 = 拆分上浮约 40%（420 亿，经云分部交付的主权项目未被单列，推断 Low）+ 30 亿。
- 第 2 步（占缺口）：385 亿（中心）÷ 6550 亿 ≈ **5.9%**。
- 第 3 步（远期条件情景）：若法/沙/阿计划按期兑现，2028—2030 年化 500—1000 亿美元（兑现率 50—100% 区间内生）。

**【敏感性】**
- 兑现率 ÷2：160—225 亿——主权项目历史上跳票率高（无单一出处，常识性推断，Low）。
- ×1.5：480—675 亿。
- **结构性注记**（承接第 1 章 1.1"X 变量"）：主权买方不按偿付逻辑出牌——它既能填塞缺口（石油美元换算力主权），也可能因地缘/财政一夜撤单；**其贡献不可用商业模型外推，只能监测**（0.3 章监测哨"新增大额交易"）。

## 2.11 五路径加总、扣重与"双斜率赛跑"：缺口闭合的时间结构

### 2.11-A 当期加总（2026，B 口径）

| 项 | 金额（亿美元/年） | 说明 |
|---|---|---|
| ① 企业 GenAI（实测） | 370 | 2.0-4 |
| ② 消费者+广告 | 250—350 | 2.7 |
| ③ 企业软件溢价 | 300—500 | 2.8 |
| ⑤ 主权 | 320—450 | 2.10 |
| 减：①∩③ 重叠 | −(100—200) | 2.5 规则；扣重与③规模正相关（③=300 亿扣 100、③=500 亿扣 200；若按独立区间处理，加总为 1040—1570） |
| **外部收入合计** | **1140—1470**（相关扣重口径） | 与 2.1-B 口径（1450—2500 亿）对账：本表①用 2025 Menlo 滞后锚（370 亿），B 口径分子用 2026 run-rate——差值即模型层直营收入的时间差（Anthropic 两月 +38% 即实例）。五路径加总 + 模型层直营超出滞后锚的部分（0—650 亿）= 1140—2120 亿，与 B 口径下沿带（1450—2120 亿）交汇 ✓ 五路径表为保守下界 |
| ④ 内部挪用（单列） | 2000—3000 | 2.9；非收入 |
| **capex（分母）** | 6950—10000 | 2.2 |
| **缺口（capex − B 口径收入，主陈述承 2.3）** | **4450—8550（中心 6550）** | 与 2.3 演算一致 ✓；若按本表五路径滞后锚（1140—1470）计为 5480—8860——更保守的旁证，主陈述取 run-rate 口径（2.3） |

**填塞结构**：中心缺口 6550 亿 ≈ 内部挪用 2000—3000 亿（④）+ **债务/股权融资 3550—4550 亿**——与 2.3 第 6 步实测债务增量量级一致（实测约为需求的四至五成）✓。

### 2.11-B 远期情景（2030，条件语句）

| 情景 | ① | ② | ③ | ⑤ | 外部合计 | vs 2030 capex = 6950 亿—1.0 万亿 × (1+15%—25%)⁴ ≈ **1.22—2.44 万亿**（2027—2030 连续 4 年外推；②③为 2026 中心 × 1.5—3.3 倍外推，⑤承 2.10 远期） |
|---|---|---|---|---|---|---|
| 基准（k 爬至 10—35%，3—7 年 J 曲线兑现） | 1600—5700 | 500—1000 | 600—1200 | 500—1000 | **3200—8900 亿** | 覆盖 **13—73%**（3200÷24400；8900÷12200）；机械中值 33%（6050÷18300），k 加权合理中心 25—30% |
| 激进（p 达 2—5%，隐含不连续） | 5400—13500 | 700—1200 | 900—1500 | 800—1200 | **7800—17400 亿** | 覆盖 **32—143%**（7800÷24400；17400÷12200），中值 ~69% |
| 悲观（k 停滞 5%） | 810 | 250—350 | 300—450 | 300—450 | **1660—2060 亿** | 覆盖 **7—17%**（1660÷24400；2060÷12200） |

**覆盖率端点配对明细（13—73% 的完整 2×2 生成矩阵）**。2030 收入的每个端点都是"五路径收入区间端点"，对应的收入分项来源（锚点行号）：①基准 1600—5700 亿 = 2.6-C 基准情景（W=27 万亿［2.6-A］× s=30% × k 爬至 10—35%［2.0-9 J 曲线、2.0-10 NANDA］× c=20%）＋②500—1000 亿（2.7，ChatGPT 付费 5000 万［2.0-2］× ARPU 外推）＋③600—1200 亿（2.8，席位×牌价 30 美元［2.0-3］）＋⑤500—1000 亿（2.10 远期）。2030 capex 端点：下限 1.22 万亿 = 6950 亿(2.2/0.6-13)×(1.15)⁴；上限 2.44 万亿 = 1.0 万亿(2.2/0.1-B15)×(1.25)⁴（均 2027—2030 连续 4 年外推）。

| 配对 | 收入（亿）| capex（亿）| 算式 | 覆盖率 | 是否主口径 |
|---|---|---|---|---|---|
| 收入下限 × capex 上限 | 3200 | 24400 | 3200 ÷ 24400 | **13%**（全区间下限） | 是（比例下限） |
| 收入下限 × capex 下限 | 3200 | 12200 | 3200 ÷ 12200 | 26% | 否（交叉） |
| 收入上限 × capex 上限 | 8900 | 24400 | 8900 ÷ 24400 | 36% | 否（交叉） |
| 收入上限 × capex 下限 | 8900 | 12200 | 8900 ÷ 12200 | **73%**（全区间上限） | 否（"极端组合"不作主陈述） |

→ 故主口径区间的两个端点**来自不同方向的收入与 capex 组合**：13% 是"收入最差×capex最贵"（悲观叠加），73% 是"收入最好×capex最省"（乐观叠加）——**两者均非同一情景的自然配对**，真正的"同方向情景"中心落在 26—36% 区间，这正是机械中值 33% 与 k 加权中心 25—30% 介于其间的理由。

**结论（条件化陈述）**：基准情景下，五路径外部收入对 2030 年 capex 的覆盖率为全参数组合区间 **13—73%**（73% 端点对应"基准上限收入 × capex 下限"的极端组合，不作主陈述）；**机械中值 = 外部收入中值 6050 亿 ÷ capex 中值 1.83 万亿 ≈ 33%**，因 k 的概率质量集中于下段（NANDA 95% 失败率为当期实证），**概率加权后合理中心约 25—30%**——缺口闭合仍需 ④ 内部挪用 + 债务层展期；激进情景方可谈"覆盖"（上端 143%），而其成立条件（组织兑现率 k 从 ~2% 跃至 50%+）恰是第 7 章不连续分支的触发条件本身。**供给侧 C 口径承诺年化（1300—2300 亿）与悲观情景外部收入（1660—2060 亿）大体相当、全面低于基准情景下限（3200 亿）——承诺的偿付要求收入兑现不落入悲观段；若仅悲观兑现，承诺上端（2300 亿）将超出行业外部收入上端（2060 亿）约 12%，供给侧签约直接转化为偿付压力。承诺方正是在按"悲观不发生、基准下段"下注。**

### 2.11-C 双斜率赛跑（比值的方向学）

- 收入斜率（近期实测）：OpenAI ARR 130.7 亿(2025)→400 亿(2026-08) ≈ +200%/年（0.1-B14、0.5-4）；Anthropic 470→650 亿/两个月 +38%（2.0-1）；Gartner 模型市场 +63%（2.0-5）。
- capex 斜率：+67%（2025，0.1-A2）→ +83%（2026E，0.1-A3）。
- **条件推演**：若 2027—2028 收入保持 +50—100% 而 capex 增速回落至 +20—30%（电力/并网约束 0.1-C14/C15 为物理天花板），R 将于 2028—2030 触及 0.3—0.5——穿越 0.3 监测哨（0.3 章裁决线）；若收入增速衰减至 +30% 以下而 capex 维持 +30%+，R 将于 2027 跌破 0.15，缺口命题强化。
- **辩证**：R 的改善有两种成因——分子驱动（健康）与分母坍缩（病理，2.3 敏感性末条）。裁决 R 必须同时读两条斜率，单看比值会误判。**绝对缺口额（6550 亿中心）即便在 R 温和改善时仍可能扩大**（分子 +60%、基数小；分母 +25%、基数大）——比值升 ≠ 缺口缩。

## 2.12 不连续分支（前向引用，一句）

若 Agent 能力跃迁使组织兑现率 k 发生数量级跳升（2.6-C 激进情景的成立条件），上述全部流量算术将被改写——该分支的完整推演保留在第 7 章，本章不展开。

## 2.13 本章自检清单

**① 本章全部具体数字的来源核对结果**
- 出自第 0 章核验表：capex 三年序列（0.1-A1/A2/A3、0.6-13）、96%/FCF/债务（0.1-A6）、OpenAI ARR 与分成（0.5-4）、承诺三口径（0.1-B8）、Nvidia FY2026（0.1-B16）、Anthropic 闭环四边（0.6-1/2/7）、OpenAI-AWS（0.6-3）、xAI（0.6-5）、H100 租金（0.5-3）、电力约束（0.1-C14/C15）——均已在第 0 章联网核验。
- 出自本章锚点表（2.0-1 至 2.0-12，本次联网核验）：Anthropic ARR、ChatGPT 用户、Copilot 牌价、Menlo 支出、Gartner 模型市场、主权 AI、美国劳动报酬、ILO 份额、J 曲线出处、NANDA、沙特部署、知识工作者池。
- 推算值（已标置信度）：芯片占数据中心成本 50—65%（Medium-Low）、工具捕获率 c=10—30%（Medium-Low）、s_技术=20—40%（Medium）、Copilot 席位 3000 万—1 亿（Low）、全球可触达池 25—30 万亿（Low）、OCF/股东回报相关推算（Medium）。
- 明确缺数项：xAI 承诺合计（未核验）、Nvidia 收入中投资伙伴占比的官方拆分（不存在）、微软股东回报精确额（未核验，未硬算）。

**② 本章全部假设参数列表（关键 8 项）**
1. B 口径综合折让 0—10%（2.1-A 端点实证 −9%—0，推断 Medium）。
2. Anthropic 采购承诺年化摊法：GCP 5 年、AWS 10 年、Azure 假设 5 年（2.1-C，Azure 期限未披露——**假设**，Medium）。
3. 芯片占数据中心成本 50—65%；Nvidia 在投资伙伴采购中份额 60—80%（2.4-1，推断 Medium-Low）。
4. 路径①参数组：W=27 万亿、s=30%、k(2026)=2—5%、c=20%（2.6，Mixed：W/k 有锚，s/c 为推断）。
5. "3—7 年"爬坡区间为**分析性推断**（2.6-D 第 4 条，Low），非权威出处；被 J 曲线机制+NANDA 实证+历史 GPT 锚（10—40 年）框定。
6. 2030 capex 外推：2027—2030 连续 4 年 +15—25%（2.11-B，外推，Medium）。
7. 主权兑现率 50—100%（2.10，内生区间，Low-Medium）。
8. ①∩③ 重叠 100—200 亿（2.5/2.11-A，推断，Medium-Low）。

**③ 本章置信度最低的三处段落（供人工重点抽查）**
1. **2.6-A/C 的全球可触达工资池 25—30 万亿美元**（Low，第三方方法学+PPP/名义桥接误差 ±20%）——路径①全部远期情景的分母都建立在此，若该池高估一倍，基准情景收入上限从 5700 亿腰斩至 2850 亿；缓解：美国锚（2.0-7，High）独立交叉验证了数量级。
2. **2.4-1 Nvidia 视角的"投资伙伴贡献收入 20%—62%"**（Low，区间过宽恰因公开数据不可拆分）——回收期（现金流口径 1.0—3.7 年）的结论对此敏感：兑现率÷2 且份额÷2 时回收期升至 4—15 年；正式拆分待第 1 章增补件。
3. **2.6-D"3—7 年"爬坡区间与 2.11-B 基准情景的绑定**（Low，分析性推断）——这是全章时间结构结论（"空窗"）的唯一时间参数；若实际爬坡为历史 GPT 型 10—15 年，基准情景 2030 收入下修至 1000—2000 亿量级，空窗从"风险"变"基准"。

**④ 四段式执行核对**：2.3、2.4-1、2.4-2、2.6-A/B/C、2.7、2.8、2.9、2.10 共 9 处主演算全部按"算式→输入（行号）→演算（逐步）→敏感性（翻倍/减半双向）"呈现；2.6-D 为出处审计段（无演算）；无跳步演算，无未标注来源的数字。
**⑤ 返工单补全（2026-09-06 二次修订）**：(i) 2.11-B 覆盖率端点的 2×2 配对明细（13% = 收入下限 3200 ÷ capex 上限 24400；73% = 收入上限 8900 ÷ capex 下限 12200；交叉对 26%/36%）；(ii) 2.3 第 6 步"四至五成"的分子（实测外部融资 3420 亿/两年=1710 亿/年）分母（外部融资需求 = 中心缺口 6550 − 内部可消化 2000–3000 = 3550–4550 亿/年）口径显式化，并声明 38–48% 为下界（分子可能低估：私募信贷与表外或有设施未完全捕获），股权部分解释剩余 52–62% 的来源结构；(iii) 2.4-2 撬动倍数（≡承诺÷股权，分子=承诺、分母=股权）与覆盖比（分子=ARR、分母=承诺年化）定义拆分，Anthropic 覆盖比 1.16x 分子=650(A)分母=560，OpenAI 0.43–0.53x 分子=320/400(A/B)分母=750。

---

**执行状态**：第 2 章（需求缺口算术与五路径承载力）完稿，含 2.0 本章锚点表（12 项新增核验）、2.1 三级收入口径、2.2 分母口径表、2.3 赛跑比值 R 四段演算（中心 0.23，缺口 6550 亿/年，与债务增量交叉验证：实测表内外融资约为算术需求的四至五成）、2.4 回流率双视角演算（Nvidia 回收期毛利口径 0.6—1.8 年/现金流口径 1.0—3.7 年，双杀 4—15 年；Anthropic 撬动 4—11 倍、覆盖比 1.16x vs OpenAI 0.43—0.53x）、2.5—2.10 五路径各自四段式（路径①为重心：池子 27 万亿、当期渗透 0.14%、k≈2—5% 双源锁定、J 曲线出处审计含"3—7 年"降格声明）、2.11 加总扣重与双斜率赛跑（当期外部收入 1140—1470 亿；2030 基准覆盖率 13—73%、k 加权合理中心 25—30%）、2.12 不连续分支一句前向引用、2.13 自检清单。按"一次一转纪律"，本章至此结束，不续写下一章。

---

# 第 3 章 · 会计解剖

> 章内声明：本章产品是**会计政策的裂缝测绘**与**该裂缝的会计传导链**，不是对任何主体的行为定性。信用层的具体脆性结构（三类发行人分拆压力测试、到期墙、抵押品计价）已**剪切至《04-信用脆弱性图谱-草稿.md》**，由第 4 章承接，本章只保留会计维。全章执行三线用词纪律——**激进会计政策**（合规框架内的选择，本报告描述与分析的对象之一）、**监管套利**（利用规则缝隙但未越规，可写）、**会计欺诈**（仅在拥有一手证据时方可提及；本报告撰写期间未获得指向任何在世企业的一手欺诈证据，故本章不出现"欺诈"一词作为对任何主体的事实指控）。1920 年代 Insull 体系的历史结局如实陈述，作为结构对照，**不将历史罪名平移至当下企业**。凡具体数字：出处核验表（注行号）/联网核验（注来源与日期）/标注"估算值·置信度低"，三选一。情景判断一律条件句。**前向引用**：本章的会计裂缝与监管前哨信号如何转化为信用层的偿付断点，见第 4 章 4.0-4.3。

## 3.0 本章锚点表（联网新核验，`3.0-x` 行号）

| 锚点 | 核验值（截至 2026-09-06） | 信息时点 | 来源 | 置信度 |
|---|---|---|---|---|
| 3.0-1 SEC 折旧/收入确认执法状态 | **截至执行日未核验到 SEC 就 GPU/服务器折旧年限或"循环交易"收入确认，对任何美国上市公司发出的正式意见信、非正式问询或执法调查** | 2026-09-06 | SEC 公开文件检索（子代理） | High（对"无"的检索） |
| 3.0-2 SEC 规则制定请愿 petn4-903（**Rule192 非数据保护规则**） | "要求对云收入与商业纠缠实体的未实现收益进行分拆披露"请愿（Penn State 社会学博士生 Hera H. Lee 提交），直接点名 cloud credit circuit 的股权-采购-收入关联链。**⚠️ 编号澄清**：此处 Rule 192 = 17 CFR § 201.192《SEC Rules of Practice》规则制定请愿程序，**非** Reg S-P 数据泄露 Rule 192（17 CFR § 248.192）——两者不同，勿混淆 | 2026-06-07 | [SEC petn4-903](https://www.sec.gov/files/rules/petitions/2026/petn4-903.pdf)（执行日核验 PDF 有效、正文标"Pursuant to Rule 192(a)...17 CFR § 201.192(a)"） | High（文件本身已核） |
| 3.0-3 SEC 规则制定请愿 petn4-910（**Rule 192 非数据保护规则**） | "要求披露 AI 算力资产老化（vintage）、折旧与寿命敏感性、利用率、退役/减值、经济收益率并调和至 GAAP 分部"请愿（Raymond Gillis 提交）。**编号澄清同 3.0-2**（17 CFR § 201.192 程序条款，非 Reg S-P 数据保护 Rule） | 2026-07-07 | [SEC petn4-910](https://www.sec.gov/files/rules/petitions/2026/petn4-910.pdf)（执行日核验 PDF 有效、正文标"Pursuant to SEC Rule 192, 17 C.F.R. § 201.192"） | High |
| 3.0-4 FTC 6(b) 报告 | FTC Staff Report：云服务商与 AI 开发者合作与投资（Microsoft-OpenAI、Amazon-Anthropic、Google-Anthropic），披露 Google Cloud 向 Anthropic 提供 **$100 亿 cloud credits** 安排 | 2025-01-17 | [FTC pdf](https://www.ftc.gov/system/files/ftc_gov/pdf/p246201_aipartnerships6breport_redacted.pdf) | High（官方文件） |
| 3.0-5 Michael Burry 批评 | Burry 指 hyperscaler 折旧年限 5–6 年高于芯片经济寿命 2–3 年，估 2026–2028 折旧被低估约 **$176B**、Oracle 利润或被高估约 27%、Meta 约 21%；Nvidia 回应称 A100 等旧芯片仍高利用率运行有"有意义经济价值" | 2025-11 起 | [The West/CNBC](https://thewest.com.au/business/cnbc/big-short-investor-michael-burry-accuses-ai-hyperscalers-of-artificially-boosting-earnings-c-20655611)；[CapitalAIdaily](https://www.capitalaidaily.com/michael-burry-says-nvidia-throwing-straw-man-arguments-on-chip-depreciation-instead-of-addressing-real-risks/) | Medium（市场争议，非监管行动） |
| 3.0-6 Nebius FY25 审计 | 财务报表 Unqualified，但 **ICFR Adverse**，披露两项 material weaknesses：**固定资产管理**、**TripleTen 收入确认** | FY2025 | [StockTitan 20-F](https://www.stocktitan.net/sec-filings/NBIS/20-f-nebius-group-n-v-files-annual-report-foreign-issuer-df35b085304a.html) | Medium |
| 3.0-7 做空机构状态 | **截至执行日未核验到 Hindenburg/Culper 就 hyperscaler 折旧或 AI 收入循环发布正式做空报告**（Culper 仅见涉 Nvidia 中国需求内容） | 2026-09-06 | 做空数据库检索（子代理） | High（对"无"的检索） |
| 3.0-8 Insull 复用口径修订 | "$2700 万控 $5 亿"为**二手综合口径**；按 1932 楼市报道帝国合并资产约 **$40 亿**、Financial History Magazine 称峰值总资产超 **$20 亿**——需给区间 | 1932/2002｜2026-09-06 | [InvestorAmnesia](https://investoramnesia.com/2023/02/20/when-icons-fall-ftx-carnegie-and-samuel-insull/)；[FinHist Mag](https://www.moaf.org/publications-collections/financial-history-magazine/75/_res/id=Attachments/index=0/Article_75.pdf)；[Chicago Trib re-ed](https://chicagology.com/notorious-chicago/samuelinsull/) | Medium |
| 3.0-9 Insull 结局修订 | **1932-04 接管；1934/1935 两次联邦审判均判无罪**（罪名含破产法违反、侵占、邮件欺诈）；1938-07 巴黎去世；**Edward C. Kirkland 非做空者（无恶击者/举报人单点，系市场+债权人+监管合力）** | 1932–1938｜2026-09-06 | [American Heritage](https://www.4score.org/node/3473)；[JRank](https://law.jrank.org/pages/2935/Samuel-Insull-Trial-1934.html)；[Heartland](https://heartland.org/opinion/samuel-insull-getting-the-story-straight/) | Medium |
| 3.0-10 PUHCA 167 因果 | **PUHCA 1935 是全社会对公用事业控股公司体系（约 8 家控股公司控近 75% IOU）的制度回应，非 Insull 一人之单一因果**；限制超两级控股 | 1935｜2026-09-06 | [SEC testimony](https://www.sec.gov/news/testimony/020602tsich.htm)；[GAO](https://www.govinfo.gov/content/pkg/GAOREPORTS-GAO-08-289/html/GAOREPORTS-GAO-08-289.htm) | High |

## 3.1 裂缝测绘：会计折旧年限 vs 技术有效寿命（激进会计第一传导链）

**【论点】** hyperscaler 与 neocloud 对 GPU/服务器的折旧年限（5–6 年）显著长于行业公认的芯片技术有效寿命（2–3 年）——这不必然是错误，但它制造一条**随时间累积的折旧不足额**，推高账面"运营利润"、推迟减值确认，从而**在利润表上掩盖现金流恶化**。本章测绘该裂缝的量级与逐年累积。

### 3.1-A 四类主体的折旧年限全景（输入）

| 主体/类别 | 折旧年限 | 来源核验 |
|---|---|---|
| Microsoft 服务器+网络设备 | 4 年 → **6 年**（FY2023 起，FY23 运营收入 +$3.7B） | 0.1-C1（High） |
| Google 服务器+网络设备 | 4 年 → **6 年**（2023-01，FY23 折旧 −$3.9B） | 0.1-C1（High） |
| Amazon（AWS 服务器） | 2024 延至 **6 年**；2025 部分缩回 5 年（来源间有出入） | 0.1 检索（Medium） |
| Meta | 5 年 → 5.5 年（2024/2025 会计变更） | 0.1 检索（Medium） |
| CoreWeave（neocloud） | **6 年**直线（技术设备含 Nvidia GPU） | 0.1-C2（High） |
| Nebius | **4 年** | 0.1-C2（High） |
| Lambda | 约 **5 年** | 0.1-C2（High） |
| 行业公认芯片技术有效寿命 | **2–3 年**（训练/推理负载 + 60–70% 高利用率下更短） | 0.1-C3（Medium，行业分析非单一官方） |

**行业共识**：折旧年限普遍集中 4–6 年，而技术有效寿命 2–3 年——**裂缝约 2–3 年**。

### 3.1-B 折旧不足额逐年累积（四段式）

**【算式】** 年度折旧不足额 ≈ 资本化算力资产账面额 ×（1/会计年限 − 1/技术寿命）；算例以单卡为单元，规模化同比例。

**【输入】** 基准单卡（设 H100 类）；具体数：**单卡成本 $25,000 为估算值·置信度低**（非核验表直给，由 2.2 区域距语义和行业公开价区间推出）；会计年限 6 年（0.1-C2）；技术寿命取 3 年（0.1-C3 上端，作保守估计——同行惯例多取 2.5 年）。

**【演算】**（单卡，按年度费用）
- 会计口径年折旧：25000 ÷ 6 ≈ **$4,167/年**。
- 技术寿命口径年折旧：25000 ÷ 3 ≈ **$8,333/年**。
- **单卡年度折旧不足额**：8333 − 4167 = **$4,167/卡·年**（即裂缝恰为技术寿命折旧的一半）。
- 三年点（技术寿命终点）时，会计口径该卡账面仍剩 25000×(3/ 6)=$12,500 未提足——**等于当期资产水面虚高 $12,500，且该卡若已停止产生经济价值，则对应一笔未计提的隐性减值**。

**【敏感性】**（双向，翻倍/减半）
- 技术寿命减半（2.5 年而非 3 年）：8333→10000，不足额 →$5,833/卡·年（裂缝扩大 40%）。
- 技术寿命若实际 4 年（较乐观，Nvidia 声称 A100 仍高利用）：不足额 →25000×(1/6−1/4)=25000×0.0833≈**$2,083/卡·年**（裂缝收窄一半）。
- 单卡成本翻倍至 $50,000：所有绝对额同比例翻倍，裂缝结构不变。

**汇总到行业层（估算值·置信度低）**：若以 hyperscaler+neocloud 2024–2026 累计 GPU/服务器资本化额（量级见 0.1-A，2600→6950→10000 亿区间）为基数，按有效技术寿命 3 年重算，**行业年度折旧不足额的量级在数百亿美元**——与 Burry 的约 $176B/2026–2028 属于同一数量级（3.0-5，Medium，为市场估算，非监管或审计结论）。本章标注为估算、不作单一权威数字引用。

## 3.2 传导链：从利润表"合法刷高"到信用层偿付断点

**【论点】** 折旧裂缝不是会计猎奇，它构成一条可测绘的传导链，把利润表虚高与信用层断点连接起来。逐环拆解（条件句陈述）。

**环 1 · 现金流恶化的信号被利润表掩盖**：折旧是非现金费用。当一家公司把折旧年限从 4 年拉到 6 年，当期运营利润立即上升（MSFT +$3.7B、GOOG −$3.9B 折旧即 3.1-A 实证），而它的**现金流出没有任何变化**。于是：**若这家公司本就处于"现金在烧、利润靠会计政策撑起"的状态，折旧拉长会麻醉外部对现金流质量的警惕**。

**环 2 · 减记延后制造"账面资产仍在运转"的幻觉**：技术寿命 2–3 年而账面 6 年，意味着 4 年期的"退役芯片"在账上仍以 1/3 账面值计价。若租金已跌破成本线（见 3.3），则实际资产回收变差，但**减值测试（资产组可收回金额）常被推迟**——因为早期折旧条款制造了"资产还有残值"的会计先例。

**环 3 · 收入质量虚增放大偿付能力假象**：当用"运营利润/EBITDA"去衡量云商与 neocloud 的债务偿付能力（第 4 章将做），**这些指标被折旧不足额系统性注水**。第 2 章的"四至五成债务验证"分母是现金流口径；若评级机构用被注水的 EBITDA 而非现金流（第 4 章三类发行人分析将进一步拆解），偿付断点会被系统性后移。

**环 4 · 断点的条件性成立**：**当且仅当**收入增长斜率不足以覆盖（1）折旧不足额对应资产的真实经济折旧 +（2）债务利息在展期利率上，传导链才在信用层兑现为断点。若收入保持快增（2.6 路径①），裂缝可以长期填塞不爆破——**这就是本章与第 2 章"双斜率赛跑"的会计维呼应**。**前向引用（第 5 章）**：该断点从信用层兑现为系统性断口的骨牌顺序（最杠杆层→抵押品→capex→芯片/HBM→能源→搁浅资产），见第 5 章五级序列；本章只到"会计—信用"接口为止。

## 3.3 租金-折旧-寿命三曲线与交叉点（双曲线分列，禁止混合）

**【论点】** 第 0 章 0.5-3 复核已确认：**现货/即期与一年期长约是两条不同价格曲线**，H100 与新一代（B200/H200/GB）不可混用。本节分列并各自与会计折旧线求交叉点。

**【输入（租金曲线，核验表）】**
- H100 现货/即期：$2.79（2025-07）→ $2.82（2026-03），**几乎零波动，低位企稳**（0.5-3，High）。
- H100 一年期长约（1y\*）：低点 $1.70（2025-10 一度）→ $2.10–2.70（2026-04，**回升约 +40%**）（0.5-3，High；0.2-7 校正"非单向下行"）。
- B200 一年期长约综合：$3.68（2026-04）（0.5-3，High）；现货层面更高。
- 会计折旧线（H100 类，6 年）：由 3.1-B 单卡 $25,000（估算·低）÷ 年利用小时。**年利用小时取 7,000 h 为估算值·置信度低**（云数据中心 60–70% 利用率量级）。
   - 会计年折旧 $4,167 ÷ 7,000 ≈ **$0.60/h 折旧线**。
   - 技术寿命年折旧 $8,333 ÷ 7,000 ≈ **$1.19/h**。
- 需补运营成本（电力+维护+机柜）才能算总成本线：**设为折旧的 1.5–2 倍为估算值·置信度低**（行业 neocloud 毛利 40–55% 语义）。

**【演算·交叉点】**
- **会计折旧线 vs H100 出货价**：折旧底成本 $0.60/h，含成本线约 $1.5–1.8/h。当前 H100 一年期长约 $2.10–2.70 **显著高于成本线**——会计口径下租金尚有健康毛利，折旧裂缝未直接引爆。
- **技术寿命折旧线 vs H100**：$1.19/h 底成本、含运营约 $3/h+。**H100 一年期长约下沿 $2.10 已跌破"技术寿命口径含运营成本线（约 $3/h）"**——若按 2–3 年真实寿命计提，H100 长约租金当前处于**技术口径亏损区**。
- **B200 vs H100 价差的意义**：B200 长约 $3.68/h 显著高于 H100 $2.10–2.70——新一代能以更高价格出租，**正是"旧芯片经济寿命压缩、新一代承接价格溢价"的镜像**。若未来 B200 也随供给释放向 H100 看齐下滑，而账面仍 6 年计提，则 neocloud 的"会计盈利"会进一步与实际现金流脱钩。
- **两条曲线的交叉点（分列给出）**：
   - **会计折旧线**与 H100 一年期长约的交叉（跌破即会计口径亏损）约在 **H100 长约 ≤ $1.8/h**（估算·低）——当前 $2.10–2.70 尚未触及，但已进入该方向。
   - **技术寿命有效率线**已与 H100 长约下沿**交叉（当前已处于 $2.10 < 约$3/h 技术口径含运营成本）**——即**按真实技术寿命看，H100 一年期长约当前盈利为负**。
   - **新一代承接**：B200 现货更高，是会计幻觉的缓冲垫，也是有条件成立的。

**【敏感性】**
- 年利用小时从 7,000 升到 8,700（更满负载）：折旧 $/h 下降，会计与技术两线都下移约 20%，交叉点压力缓解。
- 电力成本上升（AI 电力紧张，见 0.1-C 接口）：运营成本线抬升，技术口径亏损区扩大。
- **结论（条件句）**：只要 H100 长约维持 $2.10+，**会计口径盈利尚可，技术口径已技术性亏损**——裂缝对利润表的伤害被记账年限掩盖，对现金流的伤害却是真实的（3.2 环 1）。
- **⚠️ 假设依赖声明**："技术口径已技术性亏损"结论**依赖运营成本 ≥ 折旧 1.3–1.5 倍**的假设（本段运营成本取折旧 1.5–2 倍）；**若实际运营成本低于折旧 1.3 倍，该技术性亏损结论反转**（该情形下技术口径含运营总成本约 ≤$2.74/h，逼近 $2.10—$2.70 租金区间上沿，技术性亏损幅度大幅收窄的脆弱带随之收窄）。此声明降低本节交叉结论的脆弱性。

## 3.4 循环合约的收入确认：总额法 vs 净额法、前置效应与关联方折扣

**【论点】** 第 1/2 章实测量的循环闭环（云厂商投资 → AI 公司采购 → 云厂商确认收入）存在两种会计处理差异，其结果悬殊：**总额法 vs 净额法、多年期合约的收入前置、以及关联方交易的收入质量折扣**。三者共同决定"账面收入"离"净可支配现金"距离多远。

**3.4-A 总额法 vs 净额法（principal vs agent，ASC 606）**

- **触发问题**：当一家公司既向被投方出售云资源、又在其采购中充当中间人时，须判断自己是 principal（总额法，确认全额收入）还是 agent（净额法，只确认净额）。核心判据：**是否在转移给你客户前控制了该商品/服务**（ASC 606 控制权转移测试）。
- **核验到的现实张力**：Anthropic 若 IPO，S-1 披露分析已提示其可能采用 cloud-reseller 收入 gross 列报，并引发 principal-vs-agent 讨论（3.0 子代理检索，Low——第三方 IPO 分析，非已核验 SEC 问询）；**Nebius 的 ICFR Adverse 中明确包含一项"TripleTen 收入确认"material weakness**（3.0-6，Medium）——即收入确认方式已不是纯理论，已有 neocloud 主体的内部控制缺陷被披露。
- **对循环闭环的意义（四段式，净额法压力）**
   - 云厂商从被投方（OpenAI/Anthropic）收到的采购，因投资关系趋于"总额法"的诱惑：**把被投方采购全额计入云收入**，同时把对被投方的投资作为资产，形成"采购→收入→采购"的表观循环。
   - 若按净额法（若云商实为 agent 或补贴了折扣），真实"云收入贡献"应扣除商业纠缠产生的折扣与补贴。
   - **敏感性**：若净额法普遍适用，第 2 章 B 口径收入（1450–2500 亿）与五路径外部收入（1140–1470 亿）中由**循环采购**构成的份额将被下调——对缺口（6550 亿中心）的影响方向是**扩大**（收入被削、capex 不变）。**这是本章对第 2 章缺口的财务维收紧，标注为条件句、不作为新单点提出**。

**3.4-B 多年期合约的收入前置效应**

- **机制**：供需双方签多年期算力合约（Anthropic 5 年 $200B、OpenAI-Azure $2500 亿等，见 0.1-B、0.6 子表）。若按"签署时点确认/预付确认"而非"交付时点摊认"，则**签约当年收入被前置、后续多年收入被掏空**。
- **既有约束**：第 2 章 2.1 已确立三级口径（A run-rate / B 净可支配 / C 已签约承诺），并规定**赛跑比值分子只许用 A 或 B**、C 只作"未来分母候选"。本节补充：**多年期合约能否算入当期收入，取决于收入确认是"交付制"（recommended，配 A/B）还是"签约制"（revenue upfront，会把 C 冒充进 A）**——这正是把 C 混入当期的会计漏洞之一。
- **敏感性（双向）**：若云商将签约额前置确认，C 口径（OpenAI+Anthropic 年化约 1300–2300 亿，2.1-C）会部分混入当期收入，R 比值（中心 0.23）将被**虚增**；若严格交付制，R 维持 0.23 甚至下修。二者对"赛跑是否健康"的判断截然不同。

**3.4-C 关联方交易的收入质量折扣**

- **直接实证（微软分成，0.5-4，High）**：OpenAI 向微软支付约 **20% 收入分成**、至 2030 年上限 **$38B**；$40B ARR 是否已净分成**未披露**。→ OpenAI 的真实"净可支配收入"低于账面 ARR，对应第 2 章 B 口径推导中"微软分成 20%"的取值（B = A ×(1−20%)）。
- **投资-采购循环的折扣本质**：当采购方同时也是股东/投资者（Microsoft-OpenAI、Nvidia-OpenAI、Amazon-Anthropic 等，见 0.1-B/0.6），其支付的云费带有权益捆绑，"市场化交易价格"存疑，收入质量应打折——**折扣幅度属于估算值·置信度低**（市场无统一标准，2.4 覆盖比的"净额"解释即体现此不确定性）。
- **对本章的收束**：三股力量（总额/净额法、前置效应、关联方折扣）共同压低"账面收入→净可支配现金"的转换率。**账面收入高估、净现金低估**——这正是 3.2 传导链的收入端。

## 3.5 审计与监管风险：截至执行日的真实状态（联网核验）

**【总判断】** 截至 2026-09-06，**未核验到 SEC 就 GPU 折旧或循环交易收入确认的任何正式执法/意见信/问询**（3.0-1，High）。但**制度关注的"前哨信号"已在 2025–2026 密集出现**。区分"已有监管行动"与"市场/制度压力"，是本节的纪律。

**3.5-A 制度压力（已发生的事实，非执法）**
- **两项 SEC 规则制定请愿（3.0-2/3，High）**：petn4-903（2026-06，要求分拆披露"商业纠缠实体的云收入与未实现收益"，直接点名 cloud credit circuit）；petn4-910（2026-07，要求披露算力资产老化、年份与经济收益率）。两者均依据 **《SEC Rules of Practice》Rule 192（17 CFR § 201.192，规则制定请愿程序提交）**，与 Reg S-P 数据泄露 Rule 192（17 CFR § 248.192）是**不同法典下的两个不同"192"**。**注意**：请愿≠规则，更≠执法，但它们是把"循环披露"与"算力资产老化"推上 SEC 议程的实质动作。
- **FTC 6(b) 报告（3.0-4，High）**：正式研究云商-AI 开发者合作，披露 Google-Anthropic $100 亿 cloud credits。性质是**竞争研究/背景材料**，不是 SEC 执法，也不等于"循环交易被认定违法"。
- **做空机构（3.0-7，High）**：截至执行日 Hindenburg/Culper **未发布**针对 hyperscaler 折旧或 AI 收入循环的正式做空报告——不得把"市场讨论多"夸大为"做空机构已出手"。

**3.5-B 市场争议（3.0-5，Medium）**
- Michael Burry 对 hyperscaler 折旧年限的系统性批评（估折旧低估约 $176B、Oracle 利润高估约 27%、Meta 约 21%），Nvidia 以"A100 仍高利用、有经济价值"反驳。**这是市场投资者对会计政策的公开压力，不是监管认定**——本章引用为"第三方市场估算"，与 3.1-B 的行业量级估算作证——不充当监管事实。

**3.5-C 审计师信号（已在财报中出现）**
- **Nebius FY25：ICFR Adverse + 固定资产管理 material weakness + TripleTen 收入确认 material weakness（3.0-6，Medium）**——这是**已披露的内部控制缺陷**，直接与本章两大主题（资产折旧、收入确认）重叠，是"问题已进入审计层面"的最强实证。
- CoreWeave：审计师 ratify 正常、未见意见异常（3.0 子代理，Medium）。
- **推论（条件句）**：若更多 neocloud/hyperscaler 到执行日仍未缓解类似 ICFR 关注，则"第三防线（审计）先于监管动的"模式会延续（信用层含义见第 4 章 4.0 开篇锚）。

## 3.6 历史对照：1920 年代 Insull 体系（四镜六维）

**【方法】** 用"四镜六维"对照：四镜 = 会计、融资、收入、治理；六维 = 杠杆度、利润平滑、偿付缺口、监管距离、触发结局、本轮差异。基于 3.0-8/9/10 修订口径，不凭记忆。

**3.6-A 四镜对照**

| 镜面 | Insull 历史事实（3.0-8/9） | 当代 AI 循环（前章已核验） | 异/同 |
|---|---|---|---|
| **会计镜** | 多层控股+内部融资+关联交易+账面估值复杂化；**但两次审判均无罪**（1934/35），"利润平滑/欺诈"证据弱 | hyperscaler 折旧政策激进但合规；Nebius 已现 ICFR weakness | 同：复杂结构→透明度受损；异：当代有"财报层面的内控缺陷披露"，历史无此制度化出口 |
| **融资镜** | 顶层股权 $2700 万控 $5亿–40 亿资产（区间口径）；股票/债券/信托多层叠加 | hyperscaler FCF→债→私募→GPU 抵押→SPV 逐层迁徙（0.1-A、0.6） | 同：杠杆逐层加码、顶层出资远小于控制资产；异：当代更有"资产抵押/项目 SPV"的bankability 缓释 |
| **收入镜** | 电力需求 1920s 高增、1930s 下坠，现金流承压 | AI 收入快增但循环采购占比高、关联方折扣压低净现金（3.4） | 同：需求斜率决定偿付；异：当代收入含循环成分，历史电力收入为真实终端需求 |
| **治理镜** | 中央集权、个人声誉与控股结构强绑定，60 万股东/50 万债券持有人受损 | 创始人/管理层+资本结构绑定（OpenAI/Anthropic 估值条款、双身份股东兼供应商） | 同：控制权集中放大杠杆风险；异：当代多主体、有诉讼制度化缓冲 |

**3.6-B 六维对照**

| 维度 | Insull | 当代 AI | 可比度 |
|---|---|---|---|
| 杠杆度 | $2700 万控 $5–40 亿（区间） | 双层+项目 SPV+私募抵押（0.1/0.6） | 高（但当代有抵押物） |
| 利润平滑 | 内部交易美化利润的**指控**，未定罪，证据弱 | 折旧拉长+前置确认为"合规内激进"，非欺诈指控 | 中（当代更"合规"，历史仅"被指控"） |
| 偿付缺口 | 1932 债权人（House of Morgan）拒续贷→接管 | FCF→债迁徙中，缺口由四至五成债务+股权+现金填（2.3） | 高（当代仍在迁移期，未到拒绝时点） |
| 监管距离 | 1930s 初监管不足，PUHCA 1935 后 SEC 介入（非单一因果） | SEC Rule 192 请愿、FTC 6(b) 研究（前哨，非规则） | 高（均处"监管落地前"窗口） |
| 触发结局 | 1932 接管、1934/35 **无罪**、1938 去世；损失约 $8 亿（损失口径，非资产） | 未触发偿付断点（截至执行日） | 结构可比，结局不可预判 |
| 本轮差异 | — | 见 3.6-C | — |

**3.6-C 独立小节：本轮与当时不同之处（用户指定）**
1. **有抵押可追索性**：当代 GPU-backed 融资（CoreWeave DDTL、项目 SPV 如 Stargate $38B）具备抵押物与债务追索结构，Insull 主要靠交叉持股/信誉无抵押；**违约时的回收路径当代更明确**，但也意味着"GPU 二手价崩"会成为当期传导管道（对应 3.3 折旧/租金）。
2. **收入真实终端占比不同**：Insull 的收入来自真实电力终端需求（虽有滞后），当代 AI 收入含相当比例循环采购与关联方折扣（3.4）；**当代"收入质量"的账面风险高于历史**。
3. **会计制度化差异**：当代有 ICFR/Audit 内控披露（Nebius 已触发），历史无 PCAOB 式机制；**"审计第三防线"当代先于监管动（3.5-C），历史是监管先于大溃败制度化（PUHCA 1935 在崩溃后）**——当代存在更早的预警出口。
4. **债务货币与利率环境**：当代处利率上升周期、展期成本敏感；1920s 债务成本低。**当代"借新还旧/展期"的压力更陡**。
5. **产业网络密度**：当代 GPU/云/模型三方互相持股+互相采购形成闭环（0.1-B/0.6），Insull 是单行业内部纵向控股；**当代的"循环性"跨行业，传播面可能更广**。
6. **监管框架前置度**：PUHCA 1935 是"崩后立法"；当代 SEC 请愿/FTC 研究出现在"崩前窗口"。**"前哨信号"是否转化为规则，是未来不确定性的主轴（3.5-D）**。
> **红线声明**：以上为**结构对照**，Insull 的"两次无罪"结局与其所处时代的法律环境相关；**不得将任何历史罪名平移至当代任何在世企业**。本章既不断言当代存在欺诈，也不预先排除监管演进后的任何归类。

## 3.7 本章自检清单

**① 数字来源核对结果**
- **章节边界修正（Step 0-1）**：原 3.5-D「对信用层的含义」为纯信用层内容，已**剪切至《04-信用脆弱性图谱-草稿.md》**，本章标题相应更正为「会计解剖」；3.5-C 推论改为一句前向引用（见 4.0）。本清单之数字来源均为会计维。
- 折旧年限：0.1-C1/C2/C3、0.1 检索（MSFT/GOOG/Meta/Amazon/CoreWeave/Nebius/Lambda）。
- 租金曲线：0.5-3（现货 2.79→2.82、长约 1.70→2.10–2.70 回升 40%、B200 3.68、0.2-7 校正）。
- 审计监管：本次联网核验 3.0-1~3.0-7（SEC 执法状态、两项 Rule 192 请愿、FTC 6(b)、Burry、Nebius ICFR、做空机构状态），URL 已内联。
- 历史：3.0-8/9/10（Insull 区间资产口径、两次无罪、PUHCA 非单一因果），URL 已内联。
- **估算值·置信度低**（已标注）：单卡成本 $25,000、年利用小时 7,000、单卡折旧不足额、行业层面折旧不足额数百亿量级、关联方折扣幅度、折旧线与租金线交叉估算点。
- **缺数/待核验**：OpenAI $40B ARR 是否已净微软分成（0.5-4 未定）；Anthropic cloud-reseller 总额法是否属实（3.4-A，Low）；SEC 请愿是否转化为规则（未来事，非现数）。

**② 假设参数列表（含取值理由与敏感性）**
- 单卡成本 $25,000（估算·低）：由 2.2 语义与公开 GPU 价推出；敏感性：翻倍→绝对额翻倍、结构不变。
- 技术寿命 3 年（0.1-C3 上端，保守端）：若 2.5 年，不足额扩大 40%。
- 年利用小时 7,000（估算·低）：升到 8,700 折旧线降 20%。
- 运营成本=折旧 1.5–2 倍（估算·低）：电力上升扩大技术口径亏损区。
- 微软分成 20%（0.5-4，High 实证）：净可支配推导依赖。
- 交叉点都以区间呈现，无伪精确单点（遵循第 2 章纪律）。

**③ 全章置信度最低的三处（供人工重点抽查）**
1. **单卡折旧裂缝的资产基数与行业不足额量级（数百亿）**——依赖估算单卡成本与资本化基数，"×"结构成立但绝对规模置信度低，且与 Burry 的 $176B 属两套独立估算（3.1-B）。
2. **折旧/租金交叉点的精确触发时点**——当前"技术口径已技术性亏损、会计口径尚可"为估算·低，交叉受利用率、电力成本、B 卡承接三维度共同左右（3.3）。
3. **循环收入中"总额法/净额法"的实际采用与补滑比例**——Anthropic 总额法为 Low（第三方 IPO 分析），净额法适用后的收入下调幅度为估算·低（3.4-A）。

> **执行状态**：第 3 章（会计解剖）完稿。三线用词纪律已执行（仅"激进会计/监管套利"用于描述，无指向当代企业的"欺诈"指控；Insull 两次无罪如实陈述、不平移罪名）。原 3.5-D 信用层内容已剪切至《04-信用脆弱性图谱-草稿.md》（Step 0-1），本章标题更正。按"一次一转纪律"，本章至此结束，不续写下一章。

# 第 4 章 · 信用脆弱性图谱：三类发行人的偿付断点

> 章内声明：本章产品是**信用层的脆弱性地图**，不是方向签名。它回答"哪些债务、在什么条件下、会先出问题"；**不回答"谁先倒、倒到谁"——那是第 5 章断裂序列的地盘**。本章只给三类发行人各自的断裂条件（若 X 则 Y），传导链条一律一句前向引用，不展开。凡具体数字：出处核验表《00-核验表.md》（注行号）/联网核验（注来源与日期）/标注"估算值·置信度低"，三选一。**三线用词纪律继承第 3 章**：描述对象是"杠杆结构"与"偿付条件"，不出现指向任何主体的"欺诈""欺诈嫌疑"类指控；"资本结构脆弱"是结构陈述，非行为定性。压力情景一律条件句。涉及计算的段落给演算。凡跨多主体聚合口径，标注聚合范围与主体清单（宪法 0.7-⑤）。

## 4.1 我们为什么从这里开始：分层模型与"最软层最先调整"

**分层模型（先立定义再用）**：AI 超级周期的边际资金来自四层，自下而上"软"度递增、调整成本递减：
- **第 1 类 · 母体资产负债表投资**（股权/资产负债表投入，如 Nvidia 对 OpenAI 承诺、云商股权投资）——最软，可"搁置/缩减"而**不触发任何契约违约**。
- **第 2 类 · 隐性信用背书**（供应商担保，如 PORTS-Pike 担保结构）——软，靠信誉，无法定必须履行额。
- **第 3 类 · 项目级债务**（SPV 无追索融资）——中硬，有契约现金流，违约触发资产处置。
- **第 4 类 · 一级抵押物杠杆**（GPU 抵押贷款/DDTL）——最硬，抵押物贬值直接触发减记。

**【开篇锚·实证（A-1 义务消化）】**：Nvidia 2026-01 的 $100B 分批框架搁置是整个循环中**"最软层最先调整"的第一次实证**：
- 2025-09-22 原始公告：OpenAI 部署 ≥10GW Nvidia 系统，随每 1GW 部署逐步投资、最高 $100B（`0.1-B6`，Medium）。
- 2026-01 该框架**搁置**；Nvidia 10-Q 明示"There is no assurance that we will enter into definitive agreements"（`0.5-2` 复核，Medium）。
- 落点为 OpenAI Series I $30B 股权（2026-02-27，`0.5-2`；同轮 Amazon $50B、SoftBank $30B，`0.6-4`），并由"资产负债投入"转为"隐性信用背书"（PORTS-Pike 担保，`0.6-9`）。
- **判读**：当信号变差时，**调整从最软的股权承诺层开始，先于任何债务层**。$100B 框架是"可随时缩减"的软承诺，故被第一个搁置；而同期 Stargate $38B 银团（`0.5-1`）等硬债务**一个未动**。这不是偶然顺序，而是分层结构的内生属性——**越硬，越晚调整；但也越硬，调整时越像"断裂"而非"搁置"**。

**本章问题**：已知最软层已先调了一步，接下来每一层各自的断裂条件是什么？为避免混合口径同时高估与低估断点（宪法 0.7-④），按三类借款人分拆压力测试。**断点间的传播顺序与骨牌传导留待第 5 章**，此处只画每类的断裂条件与地图。

## 4.2 规模坐标：capex 走廊 × 到期墙（叠加）

**【定义】**：到期墙 = **当年新增融资需求** 与 **存量债务再融资到期** 在时间上重合造成的再融资窗口。它不是"所有债务同一天到期"，而是"旧债展期 + 新债攀顶"在 2027–2028 叠成的压力集中区。

**【输入】（口径均标注来源）**
- 2030 capex 走廊 **1.22—2.44 万亿**（`2.11-B`，2027—2030 外推 +15—25%/年，Medium）。
- 缺口中心 **6550 亿/年**（`2.3`）；融资型需求 = 缺口 − 云商内部可消化 = **3550—4550 亿/年**（`2.3` 第 6 步，口径：算术需求）。
- 既有债务发行窗口：2025—2026 年表内长期债 +2099 亿（`0.1-A6`，1340→3419 亿，2024 末→2026-06）、私募信贷流向项目融资约 1250 亿（`0.1-C8`）、SPV/银团约 72 亿（`0.5-1`），表内外两年合计约 **3420 亿 → 年化约 1710 亿**（`2.3` 第 6 步）。

**【演算·叠加（条件句，估算值·置信度低）】**
- 第 1 步（第一波到期块·总量）：若 2025—2026 年表内新增长期债 2099 亿中，估 40—60% 落在 2027—2029 年到期的短档（基础设施/含展期选择权档，**估算·低**）→ 到期块总量 **840—1260 亿**（=2099×0.4 至 2099×0.6）。
- 第 2 步（年化到期）：若上述到期块集中在 2027—2029 三年（估算·低）→ **280—420 亿/年**（840/3 至 1260/3）。
- 第 3 步（与新增需求叠加）：融资型需求 3550—4550 亿/年 + 到期年化 280—420 亿/年 = **3830—4970 亿/年**——即 2027—2028 窗口内资本市场每年须承担的实际融资量级，**比单看新增需求高约 8%**（非 1/4—1/3；该高估来自把到期块总量误当成年化值，本步已校正）。私募信贷 1250 亿（`0.1-C8`）虽多为 7—10 年长档非集中到期，但含滚动/展期条款，其压力不在到期洪峰、而在利率上行期的**展期成本**（对应 3.6-C 第 4 条）。
- 第 4 步（非同步假设）：上述叠加**成立的条件**是 capex 仍处爬坡高位（2.11-B 外推成立）且 2025—2026 年债项有相当比例落 2027—2029 到期——二者均为**条件式假设，置信度 Low**；若 capex 增速因电力/并网约束提前骤停（`0.1-C15`），则新增需求与到期叠加减弱，到期墙被"分母坍缩"式提前解除（但这是病理式解除，见 2.11-C 辩证）。
- **结论（条件句）**：2027—2028 到期墙不是"债务洪峰单点"，而是"**新增需求持续（3550—4550 亿/年）+ 第一波短档债滚动（280—420 亿/年）**在同一再融资环境里的**边际叠加**（合计 3830—4970 亿/年，估算·低）。其烈度取决于"capex 是否继续攀顶"×"短档债占比"两因子。**给不出单点值，区间 3830—4970 亿/年作再融资窗口的量级锚**，且真实压力更多地来自"新增+展期"在利率上的双向叠加而非到期绝对量。该量级是三类发行人各自断裂条件的共同压力背景。

## 4.3 三类发行人分拆压力测试（本章主轴）

> 分类遵循宪法 0.7-④：**(a) 母体 FCF 背书类**（hyperscaler 母公司债 + 母体牵头 JV）、**(b) 项目级 SPV 无追索类**（Stargate/密歇根/新墨西哥/Oracle SPV）、**(c) 纯玩家杠杆类**（CoreWeave/Nebius/xAI）。禁止混合口径。

### 4.3-A 母体 FCF 背书类（服务能力强、传染慢）

**债务存量**：四大云合计长期债务 2026-06 末 **3419 亿**（`0.1-A6`，从 2024 末 1320 亿）；Meta 至 2028 对美累计投资承诺超过 6000 亿（`0.1-A4`，非单年度）；Meta-Blue Owl $27B Hyperion 合资，Meta 20%/Blue Owl 80%（`0.5-1`、`0.1-C7`，Low）。
**成本结构**：偿付靠 **母体现金流**而非项目本身。2025 四大云合计 FCF 1913 亿、H1-2026 CapEx/经营现金流达 96%（`0.1-A6`，Medium）——资本开支已逼近当期经营现金流，"自由现金流外溢"能力被抽空，但**负债率仍低、评级投资级**，到期再融资通道通畅（`2.3` 第 6 步旁证）。
**到期分布**：投资级长期债，久期一般 7–10 年（估算·中），非集中到期，展期不依赖个别窗口。
**压力情景断裂条件（条件句）**：
- **断裂阈值**：模型上需"CapEx/OCF 持续 ≥100% 且 FCF 滑向 ≈0 连续 2 个财季 + 评级展望负面"才可能触发**再投资减速**。**注意断裂形态**：母体类几乎**不以"债务违约"断裂**（负债率低、利息覆盖充足），而以"**削减 capex/回购/分红 → 把本是"左口袋到右口袋"的内部填塞（路径④，`2.9`）砍掉**"的方式断裂——这会在 3–6 个月后传导为下游（b）（c）类的收入/租约悬崖，但那是第 5 章链条。
- **Meta-Blue Owl JV 特殊性**：合资层面 Blue Owl 持 80%，母体 Meta 仅 20%——若数据中心租赁回报不足，**受损首先落在 Blue Owl 及其募资方（私募信贷，`0.1-C8`）**，Meta 母体仅以 20% 股权承担。JV 的断裂不直接等于 Meta 债务断裂。
- **快钟在类内敏感度**：本类对抵押品贬值（4.4）**最不敏感**——有 FCF 与投资级评级兜底。
- **一句前向引用**：母体类若先收缩再投资，其传染窗口与顺序见第 5 章（第 5 章 A 链）。

### 4.3-B 项目级 SPV 无追索类（依赖里程碑与承诺信用）

**债务存量**：Stargate $38B 银团（JPMorgan+MUFG 牵头，德州/威斯康星，`0.5-1`、`0.1-C7`）、密歇根 $16B（PIMCO+BofA 债务、Blackstone/Related 权益，Blue Owl 已退出，`0.5-1`）、新墨西哥 $18B（约 20 家银行，Blue Owl 提供开发权益，`0.5-1`）、Oracle 项目 SPV $34B（`0.5-1`，Low）。合计约 **106B**，加 Meta-Blue Owl 27B 属 (a) 类不混入本类。置信度 Low–Medium，金额为媒体口径。
**成本结构**：**无追索（non-recourse）**——SPV 现金流来自数据中心租约/里程碑付款，母体/Sponsor 不兜底。偿付能力取决于**承购人（租户）能否履约付费**：这些数据中心的主要租户是 OpenAI/Oracle，其付款能力由被投方收入决定。
**到期分布**：项目融资典型 7–10 年，含提款期/建设期/摊销还款期，分期结构化（估算·中）。
**压力情景断裂条件（条件句）**：
- **断裂条件 = "承购人付款能力 < SPV 偿债所需租约年化 × 无追索兜底缺失 × 处置不足"三因子同时成立**。
  - 承购人付款能力：OpenAI 的 B 口径净现金，0.5-4 覆盖比 **0.43—0.53 倍**（`2.4-2`）——即 OpenAI 当期 ARR 已不足以覆盖其自身承诺年化，是个**紧张信号**；若 ARR 增速低于承诺交付增速，覆盖比进一步回落（`2.4-2` 第 5 步辩证）。
  - 无追索：SPV 违约时银行**只能处置数据中心实物资产**，不能追母体——故资产处置价值（4.4 抵押折扣）成为回收上限。
- **断裂形态**：SPV 贷款违约 → 银团重组/资产处置 → 银行与投资者的资产负债表承载损失。**传染中等**：因为它把"租户信用事件"转换为"实物资产处置事件"，且银团参与者众、见效于资产负债表（`0.5-1` 多银行结构）。
- **快钟敏感度**：本类对抵押品贬值**中等敏感**——回收上限被 4.4 的折扣压降。
- **一句前向引用**：SPV 违约是否会反向拖垮其租户/银团的并发，见第 5 章（第 5 章 B 链）。

### 4.3-C 纯玩家杠杆类（租金敏感性直接传导，Domino #1 候选）

**债务存量**：CoreWeave DDTL $8.5B（投资级延期贷款，可扩至 $8.5B）+ $3.1B，第三方汇总总债务超 **$325 亿**（`0.1-C5`，Medium——含 OEM/软件许可融资与 Magnetar 安排，需区分债务/股权）；Nebius $7.75 亿有担保融资，GPU+合同现金流双抵押，附微软合同约 $194 亿/5 年（`0.6-8`），且 FY25 审计 **ICFR Adverse**、含固定资产管理 material weakness（`3.0-6`）；xAI SPV 约 $75 亿股权 + $125 亿债务（GPU 担保，`0.1-C9`，Medium），xAI 后并入 SpaceX/Nvidia 生态（`0.6-5`）。**本类是第 1 章观测哨"算力租赁商（最杠杆）= CoreWeave/Nebius/Lambda"（`1.2`）的实体对应，是全图第一张骨牌候选（断裂顺序属第 5 章 C/D 链，此处仅列断裂条件）。**
**成本结构**：偿付**唯一来源 = GPU 租赁收入**，利润率最薄、杠杆最高；Nebius 用 GPU+合同现金流双抵押，实为把"未来租金"提前抵押。
**到期分布**：DDTL 投资级延期贷款典型 **3–5 年**（SOFR+2.25% 浮动/约 5.9% 固定，`0.1-C6`，首个投资级 GPU-backed 融资）；neocloud 私募款项 5–7 年（估算·中）。**期限最短、再融资窗口最集中**。
**压力情景断裂条件（条件句）**：
- **断裂条件**：**有效租金收入 < DDTL/租金抵押融资的当期偿债额**。拆薄到单位经济：
  - H100 一年期长约 $2.10—2.70/h（`0.5-3`，High），会计含运营总成本线约 $1.5—1.8/h、**技术口径含运营成本线约 $3/h**（`3.3`）。
  - 会计口径下当前尚有毛利（$2.10—2.70 > $1.8）；**但若 H100 长约跌破会计成本线下沿 $1.8/h，则会计口径也转亏**（`3.3` 交叉点，估算·低），此时 GPU 租金净现金流 ≤0 → 抵押现金流入（Nebius）枯竭 → 无法覆盖 DDTL 利息+本金 → 违约/清算。
  - 具体阈值（演算）：单卡会计口径净现金流 = 租金×年利用小时（7000h，`3.3` 估算·低）− 会计成本线。$1.8/h×7000=$12,600 为当年成本；当长约 $/h ≤ $1.8 时净现金流 ≤0。
- **快钟在类内最敏感**：抵押物（GPU）30—50%/年贬值（4.4）直接在该类兑现为 "LTV 上升 → 追加担保/减记"，早于收入恶化传导。
- **敏感传导特点**：**租金敏感性直接传导**——不需等母公司信号，单条租约价格变化即可触发抵押债条款（`0.1-C6`、`0.6-8`）。
- **一句前向引用**：CoreWeave/Nebius 与 xAI 三者的违约先后与对云商/芯片商的回传，见第 5 章（第 5 章 C/D 链）。

## 4.4 抵押品计价：GPU 抵押折扣逻辑与"快钟假说"检验

**【逻辑】** GPU 抵押贷款的可贷值**不能按账面值（6 年直线）**放贷，而应按**抵押物在其技术寿命窗口内可产生的净现金流折现**。第 3 章的发现直接适用：账面 6 年、技术寿命 2–3 年（`0.1-C1/C3`），且 H100 已处技术口径亏损区（`3.3`）——**抵押物"账面价值"与"清算/续贷价值"分道**。

**【演算·抵押折扣（估算值·置信度低）】**
- 单卡账面 $25,000（`3.1-B`，6 年直线，估算·低）；H100 长约 $2.10—2.70/h × 7000h/年 = **毛租金 $14,700—18,900/年**；会计成本线约 $10,500—12,600/年（$1.5—1.8/h，`3.3`）。
- 会计口径净现金流 = $2,100—8,400/年。
- 抵押可贷值 = 净现金流 × 2—3 年技术寿命年金现值（折现率 10%，估算·低）：$2,100×1.74=$3,654 至 $8,400×2.49=$20,900。
- **折扣（haircut）**= 1 − 可贷值/账面$25,000 = **16%—85%**（乐观端 16%、悲观端 85%）。若转用技术口径（净现金流 ≤0，`3.3`），可贷值趋近 0。
- **含义**：贷方若按账面放贷，回收率预期严重高估；**理性的 GPU 抵押贷方应按"技术寿命 × 租金现金流"而非"账面 × 数量"校准贷款价值比**，这在现金流已转负的旧卡上体现为高折价。

**【"快钟假说"检验（第 1 章 1.5 提出）】**
- 假说内容：**第 4 类资金因抵押物 30—50%/年贬值，可能比历史周期更快断裂**（对照 Insull 1920s、电信 2000s，`0.1-C13/C11`）。
- **机制**：抵押物（GPU）贬值不需要"收入恶化"这条慢传导链——新一代（B200 $3.68 高价，`0.5-3`）一旦快速蚕食旧卡租金，**旧卡抵押价值年降 30—50%**，LTV 自动上升，触发追加担保/减记/催收条款（`0.1-C6`）。
- **检验结论（条件句）**：**部分成立**。快钟确实提供了**独立于收入恶化的信用收紧触发通道**（这是本轮独有的、历史没有的增量——Insull/电信的抵押物不存在"2 代一跳"的技术折旧）。但其**兑现需三条件同时满足**：(i) 存在 LTV 合约触发条款（CoreWeave DDTL 有评级但条款条款未全披露，部分满足）；(ii) 贷方无展期/追加意愿；(iii) 无母体或承购人兜底——对 (a) 类最钝（有 FCF/评级兜底）、(b) 类次之（无追索，但租约有承购人信用）、(c) 类最急（无兜底且抵押现金流入最薄）。
- **结论**：快钟假说的烈度在 (c) > (b) > (a)。**它是"第 4 层可能先于历史周期断"的结构论据，但非方向签名**——兑现与否取决于上述三条件的实测，列入观测哨。

## 4.5 债务融资占比修正：硬着陆情景的实际信用敞口

**【口径重申（`2.3` 第 6 步，口径显式化）】**
- 分母（融资型需求）= 中心缺口 6550 − 云商内部可消化 2000—3000 = **3550—4550 亿/年**。
- 分子（实测外部融资流量）= **3420 亿/两年 → 年化 1710 亿**（`0.1-A6` 长期债 +2099、`0.1-C8` 私募 1250、`0.5-1` 银团 38+SPV 34）。
- 比值 = 1710 ÷ (3550—4550) = **38%—48%（下界）**。**下界含义（分子低估论证版）**：分子是"已实测"口径，私募信贷与表外或有设施未完全捕获（`2.3`），故真实债务占比**不低于且可能高于** 38—48%；**剩余 52—62% 由股权与存量现金填补**（未逐项核验，`2.3` 声明）。

**【演算·硬着陆信用敞口修正（条件句）】**
- 若硬着陆，需要"违约/重组处理"的**不是缺口总额**，而是其中由债务承担的部分：
  - 缺口中心 6550 亿 → 融资型 3550—4550 亿（占 54—69%）→ 其中债务 38—48% → **债务敞口 = 3550—4550 × 0.38—0.48 ≈ 1350—2180 亿/年**。
  - 即单年硬着陆信用敞口约为**缺口总额的约 1/4—1/3（约 21—33%）**，**而非缺口总额本身**。
- **对用户口径的辩证校准**："实际信用敞口比缺口总额小一半"**方向正确、幅度仍偏保守**——按本演算其实**小约 3/4（占缺口约 1/4—1/3）**。但两处打回：(i) 真实债务占比可能高于 38—48%（分子低估），敞口上修；(ii) 敞口是**流量（单年年化）**，若硬着陆叠加存量到期墙（4.2），某一年可能同时面对新增+到期，峰值大于年化中心。故"小一半"应校准为"**约小 3/4、但峰值叠加后收窄到约小 1/2—2/3**"。
- **（据 4.3 再细分）**：即便在债务敞口内部，真正"高违约概率"的是 (c) 类纯玩家杠杆敞口（数百亿级，`0.1-C5/C9/0.6-8`，置信度低）；(a) 类不大走违约形态（4.3-A）、(b) 类走资产处置。**映射到第 7 章情景烈度**：硬着陆情景的信用冲击应按"债务敞口中心约 1350—2180 亿/年（占缺口约 1/4—1/3，峰值可上修）"设参数，而非缺口总额 6550 亿——**该参数已登记为第 7 章输入（见附录 A-A2 侧记，非本章展开）**。

## 4.6 FCF→信用迁移的实证：钱从利润池挪到债务池

**【命题】** 第 1 章 1.5 的"边际资金正从 FCF 迁向信用层"，本条给硬数据：
- H1-2026 五大 Big Tech **CapEx/经营现金流达 96%**（2024 为 50%、2025 为 68%）（`0.1-A6`，Medium）——**利润池内部的腾挪空间已耗尽**，边际资金必须外移。
- 2025 四大云合计 FCF 1913 亿，同期长期债务 2024 末 1320 亿 → **2026-06 末 3419 亿（+2099 亿）**（`0.1-A6`）。
- 表外/项目层同步：私募信贷流向项目融资约 **1250 亿**（`0.1-C8`，UBS 口径，Low）+ Stargate 银团 38B + Oracle SPV 34B（`0.5-1`）= 两年**表内外增量合计约 3420 亿 → 年化约 1710 亿**（`2.3` 第 6 步交叉验证）。
- **判读**：这 3420 亿是"FCF 之外、由信用层承接"的边际融资。它证明**债务/私募信贷正承当整个循环的边际资金职能**，恰是 4.3-(c)(b) 类负债的存量来源、与 4.2 到期墙的存量主体。**只要增量需要保持，该层就必须持续展续**——一旦展续受阻（快钟触发），边际融资断面即出现（断裂链条见第 5 章）。
- **条件句**：若未来两年 FCF 不回升（CapEx/OCF 维持 ≈100% 或更高），则 "信用层 = 边际资金来源"的依赖反而**加深**（而非缓解），304—405 亿/季的展续压力持续。

## 4.7 本章自检清单

**① 边界与义务履行检查**
- **义务 A-1 已消化**：开篇锚=Nvidia 2026-01 搁置事件，落点 4.1（`0.1-B6`、`0.5-2`、`0.6-4`、`0.6-9`），已回填附录 A 状态。
- **分类纪律（宪法 0.7-④）**：三类发行人以三小节独立运行（4.3-A/B/C），无混合口径；每类分别给债务存量、成本结构、到期分布、断裂条件四项。
- **边界警告**：全章只给断裂条件（"若 X 则 Y"），断裂序列/骨牌传导/传染顺序一律一句前向引用指向第 5 章（A/B/C/D 链），无越权展开。
**② 数字来源核对结果**
- 核验表行号直引：`0.1-A6`（96%/FCF 1913/长债 1320→3419）、`0.1-B6`（$100B→弱化）、`0.1-C5/C6/C7/C8/C9`（CoreWeave/投资级/Stargate 与 JV/私募信贷/xAI）、`0.5-1/2/3/4`（Oracle-SP 复核/Nvidia $30B/H100 租金/OpenAI ARR）、`0.6-4/8/9`（Series I/Nebius/PORTS-Pike）。
- 前章承接：缺口 6550、融资型 3550—4550、债务占比 38—48%（`2.3`）；覆盖比 0.43—0.53（`2.4-2`）；capex 走廊 1.22—2.44 万亿（`2.11-B`）；H100 成本/交叉/技术口径亏损（`3.3`）；折旧裂缝与 EBITDA 注水（`3.1/3.2`）；快钟提出（`1.5`）。
- **估算值·置信度低（已标注）**：单卡净现金流与抵押折扣区间（16—85%）、到期墙叠加区间（3830—4970 亿/年，内含第一波到期块 840—1260 亿/三年）、债务敞口（1350—2180 亿/年）、快钟三条件、SPV 金额口径（Low–Med）。
- **缺数/待核验（登记）**：DDTL/SPV 精确到期分布（未披露）；私募信贷实际余额（付费墙，`0.1-C8`）；快钟三条件的实测触发（未来事）；到期墙短档债占比（估算）。
**③ 全章置信度最低的三处（供人工重点抽查）**
1. **抵押折扣区间 16—85%（4.4）**——净现金流、折现率、技术寿命三参数均为估算·低；方向（账面高估）可信，绝对区间需抽查。
2. **到期墙再融资区间的短档债占比（4.2）**——40—60% 为估算，直接决定叠加量级。
3. **SPV 四项目的债务存量合计（4.3-B）**——Stargate 38B/密歇根 16B/新墨西哥 18B/Oracle 34B 均为媒体口径（Low–Medium），Deal level 未经审计确认。
**④ 辩证修正记录**：4.5 对用户"信用敞口比缺口小一半"口径打回校准为"约小 3/4、峰值叠加后约小 1/2—2/3"，并标注两处上修/收窄因子；该参数已传第 7 章。

> **执行状态**：第 4 章（信用脆弱性图谱）完稿。义务 A-1 已消化并回填附录 A。三类发行人次均独立运行、只给断裂条件、传导一律前向引用第 5 章；置信度标签随数字走，情景一律条件句，计算均已给演算。按"一次一转纪律"，本章至此结束，不续写下一章。

# 第 5 章 · 五级骨牌序列：触发条件的具象化与"不倒条件"

> 章内声明：本章产品是**断裂序列的触发条件地图**，不是方向签名。它回答"每一级骨牌**在什么条件下**倒下、倒之前有哪些可见信号、**凭什么它可能不倒**"；**不回答"三情景各自的综合烈度"（第 7 章 GLIM 职责）**，**不做历史四镜对照的展开（第 6 章职责）**，二者各只许一句前向引用。**反爽文纪律·本章最高警戒**：只写倒塌路径而不写存活条件即为违纪——**每一级骨牌必须附"不倒条件"（⑤）**。凡具体数字：出处核验表《00-核验表.md》（注行号，含 0.8 新增）/联网核验（注来源与日期）/标注"估算值·置信度低"，三选一。压力传导一律条件句。涉及计算的段落给演算。第 0 章行号冻结、只增不改（本章所引 0.8 子表为本执行日新增，未动既有行号）。

## 5.0 五级横截面先行（一张表看全貌）

| 级 | 骨牌（硬→软） | 触发条件（若X则Y） | 可观测指标·当前读数 | 预警时间（硬→软传导差） | 不倒条件（提要） | 来源 |
|---|---|---|---|---|---|---|
| **L1** | 最杠杆算力租赁商（(c)类） | 有效租金 < 当期偿债额 | CoreWeave DDTL $11.6B/总债 $325B+；H100 长约 $2.10–2.70 vs 会计线 $1.8 | 数周–1 季（租金重定价→违约） | 长协锁价/母公司兜底 | ch4 4.3-C；0.1-C5/C9、0.6-8 |
| **L2** | GPU 抵押利差 + 追保潮 | 抵押贬值超 covenant → LTV 触发掏押 | 利差 SOFR+2.25%（0 溢价）；三分档 30/60/85 | L1 后 1–2 季（抵押重估季频） | 抵押折扣稳于 30% 档/新卡溢价托底 | ch4 4.4；0.1-C6/C14 |
| **L3** | 超大规模厂 capex 指引下修 | 指引连续 2 季下修 / capex-OCF 反向收敛 | 2026 指引 ~7050–7450 亿；capex/OCF 96% | L2 后 2–4 季（母体 FCF 缓冲） | AI 回报斜率仍超 capex 增速 | 0.1-A3/A6、0.6-13 |
| **L4** | 芯片订单→HBM 存储→能源 PPA 重谈 | 订单下修 → HBM 高价反转 + PPA 重谈 | 现货=长协 4–5 倍；HBM4 $31–32/GB；PPA 已现 FERC 纠纷 | L3 后 4–8 季（供给调整与合同重谈周期） | HBM 短缺真实/PPA 刚性需求 | 0.8-1~0.8-6 |
| **L5** | 搁浅数据中心 & dark fiber 2.0 | 前四级阻断投资 → 空置/减记，但过剩沉淀廉价算力 | 在建规模（SPV 已批）；空置率未见权威 | 12–36 个月（减值/清算最慢） | 迭代降速→长尾再利用 | 0.5-1、0.6-6、0.1-C12 |

> **读法**：这张表是本章的"触发+指标"总纲；"断裂传播顺序的时序模拟"属第 7 章三情景，本章不展开。每级详情见 5.1–5.5。

## 5.1 第一级骨牌：最杠杆算力租赁商（引用第 4 章 (c) 类断裂条件）

**① 触发条件（若 X 则 Y，条件句）**：**若** H100/H200 等主力卡筹码的一年期长协价跌破约 $1.8/h 会计含运营成本线下沿（`0.5-3`、`3.3`，估算·低），则该卡会计口径转亏、GPU 租赁净现金流 ≤0，于是依赖"租金收入=唯一偿付源"的最杠杆玩家（CoreWeave/Nebius/xAI，第 4 章 4.3-C）**无法覆盖 DDTL/抵押债当期息本 → 违约/清算**。当前长约在上沿 $2.10–2.70（`0.5-3`）仍保有毛利，故为**条件触发、未触发**。

**② 可观测指标与当前读数**：
- CoreWeave：DDTL $8.5B+$3.1B、总债务超 **$325 亿**，OEM/软件许可融资夹杂其中需区分股权/债务口径（`0.1-C5`，Medium）。
- Nebius：$7.75 亿有担保融资（GPU+合同现金流双抵押）、微软合同约 $194 亿/5 年，FY25 审计 **ICFR Adverse**（含固定资产管理 Material Weakness，`0.6-8`、`3.0-6`）。
- xAI：SPV $75 亿股权 + $125 亿债务（GPU 担保，`0.1-C9`，Medium）；xAI 并入 SpaceX/Nvidia 生态（`0.6-5`）——使其比前两者多一道母公司信用垫。
- 读数口径：关键哨 = **一年期长协价曲线（`0.5-3`）是否向 $2.10→$1.8 滑**，而非现货价。

**③ 预警时间（按资金分层模型，硬→软传导差）**：本层是最硬层，传导**最快**——租金按月度/季频重定价、抵押条款（`0.1-C6`）季度重置，**自触发到违约约数周至 1 季**。无缓冲期，是无追索、无担保、现金流最薄的纯玩家。

**④ 来源行号与置信度**：`0.1-C5`（CoreWeave 债）、`0.1-C9`（xAI SPV）、`0.6-8`（Nebius）、`0.5-3`（H100 长约）、`3.0-6`（Nebius ICFR）；第 4 章 4.3-C 断裂条件。置信度 **Medium**（xAI/neocloud 财务不透明，金额为媒体口径）。

**⑤ 【不倒条件】（反爽文·必须写）**：本骨牌**不倒**当至少一条成立——
- **(i) 长协锁价 ≥ 会计线**：若主力客户（OpenAI/微软等）以高于 $1.8/h 的长约续租且利用小时达标，则会计口径不转亏，本层收入底可用（`0.5-3`）。
- **(ii) 母公司信用兜底**：xAI 有 SpaceX/Nvidia 生态（`0.6-5`）；Nebius 有微软现金流合同（`0.6-8`）——二者构成"虽无追索、但有外生信用"的缓冲，使违约概率低于纯裸杠杆玩家。
- **(iii) 需求侧边际不塌**：若 AI 推理需求（第 5 级 5.5 遗产逻辑）使低成本算力利用率反而上行，租金之不跌有基本面支撑。
> 一句前向引用：若本级倒，其回传云商/芯片商的骨牌位置见 5.2–5.4；三情景综合烈度归第 7 章。

## 5.2 第二级骨牌：GPU 抵押利差与追加保证金潮（抵押折扣三分档 30%/60%/85%）

**【先决·一致性质询的期限结构解析（配重指令）】** 面对"两年举债 3420 亿（=`0.1-A6` 表内长期债 +2099、`0.1-C8` 私募信贷 1250、`0.5-1` 银团/SPV 约 72，合计 3420） vs 墙内到期 840–1260 亿"的隐含期限结构，显式判定：
- **演算**：2027–2029 到期块 = 表内新增长期债 2099 亿 × 估 40–60% 短档 ≈ 840–1260 亿（`4.2`，估算·低）。则 **2028 年后到期 = 3420 − (840~1260) = 2160–2580 亿，占总量 63–75%**——即**多数的债是长档、2028 年后才到期**。
- **两说判定（取一）**：**取"短档保留快钟"**。理由在机制：**快钟（抵押品快速贬值驱动 LTV 触发）由抵押条款与重估时频决定，不由期限占比决定**。演算：设初始 LTV 55%（债 55/抵押 100）、covenant 70%；抵押年贬 30% 后抵押=70、LTV=55/70=**78.6%>70%** → 第 1 年末即可触发追保，**与这笔债是 5 年还是 7 年无关**。所以期限只决定"到期/再融资型"触发器（把到期墙**延后**到 2028 后），**不决定"margin 型"触发器**（快钟照走）。**结论：长债结构拉慢的是到期墙，而非快钟；快钟由 40–60% 短档内的抵押条款承担并保留**。此判定落为 4.2"到期墙=放大器"的依据之一。

**【三分档追保推演（禁用 16–85% 全域，只取 30/60/85）】**
设单笔 GPU 抵押：抵押值 100、债务 55（初始 LTV 55%）、covenant LTV 70%。

| 抵押折扣（贬值）档 | 重估抵押值 | LTV | 追保缺口（=债−0.70×抵押） | 处置含义 |
|---|---|---|---|---|
| **30%（温和）** | 70 | 78.6% | 55−49= **6**（约原抵押 6%） | 可现金/芯片补仓，追保后继续 |
| **60%（中档）** | 40 | 137.5% | 55−28= **27**（约原抵押 27%） | 补仓压力陡增，触发利差走阔 |
| **85%（重档）** | 15 | 366.7% | 55−10.5= **44.5**（约原债务 81%） | 无现实补仓空间 → **强制清算** |

- **利差传导**：随折扣档由 30→60→85，DDTL/neocloud 利差从当前 SOFR+2.25%/固定约 5.9%（`0.1-C6`，首个投资级 GPU-backed、**零风险溢价定价**）走阔，直至市场对高折扣档**拒续融资**（到期墙在"再融资市场关闭"情景下升级，见 5.6）。
- **当前读数**：市场对 GPU 抵押的定价是"投资级、零溢价"（`0.1-C6`）——**等于未计入任何快钟**；预设乐观档即 30% 档已是追保。故第二级**处于"未被定价"状态，是最被低估的骨牌**。

**① 触发条件**：若抵押折扣进入 60% 档（或快钟三条件中"LTV 条款 + 无展期意愿 + 无兜底"任一成立转移到 (c) 类），则追保潮出现、利差系统性走阔、`(c)` 类短档抵押债进入现金枯竭。
**② 指标与读数**：DDTL 利差（当前 +2.25%）、新发 GPU-backed 定价、旧卡转售/残值价（快钟 30–50%/年生，`4.4`/`0.1-C14`）。
**③ 预警时间**：L1 触发后 **1–2 季**（抵押重估 + covenant 重置为季频）。
**④ 来源/置信度**：`0.1-C6/C14`、ch4 4.4；追保演算为**估算·置信度低**（参数为假设）。
**⑤ 【不倒条件】**：以下至少一条——
- (i) 折扣稳于 **30% 档**且 covenant 不被触发（无需新增资本）；
- (ii) **新一代芯片（B200/HBM4）高溢价托住旧卡转售价**，阻断"旧卡抵押值崩跌"（`0.5-3`、`0.8-2`）；
- (iii) 贷方有**展期意愿**（2028 前无强制到期兑付）。
> 边界：快钟若兑现，其与 inflate 担保链（PORTS-Pike、`0.6-9`）的连带属第 5 章传导、综合烈度归第 7 章。

## 5.3 第三级骨牌：超大规模厂商 capex 指引下修（WorldCom 钟声原型，一句带过）

> **历史一句**：2000s 世通（WorldCom）靠光学 capex 加杠杆扩张、随后财务/债务崩塌，是"capex 超级开支被财务塌陷瞬间踩停"的原型钟声；此处仅作对照，展开归第 6 章四镜。

**① 触发条件**：若 2026 capex 指引（`0.1-A3` 6950–7250 亿；更新 `0.6-13` ~7050–7450 亿）**连续两季被下调**（自"上调/收窄"转"下修/回撤"），或 capex/经营现金流自 96% 高位（`0.1-A6`）**反向收敛**并伴随回购/分红暂停 → 母体层确认"边际资金收紧"，第三级倒下。
**② 指标与当前读数**：Q2-2026：Amazon ~2200 亿（上调）、Google 1800–1900、Meta 收窄 1300–1450、MSFT 日历 1750–1900（`0.6-13`，High/Med）；capex/OCF 96%、合计 FCF 1913 亿（`0.1-A6`）。**当前读数为"个别收窄、整体仍上"**，未触发。
**③ 预警时间**：**2–4 季**——母体有 FCF 缓冲（1913 亿，`0.1-A6`），先砍回购/分红、再修正指引，故下修落后于 L2 信号 2 季以上。
**④ 来源/置信度**：`0.1-A3`、`0.6-13`、`0.1-A6`；指引为官方口径（High），"下修方向"为前瞻判断。
**⑤ 【不倒条件】**：至少一条——
- (i) **AI 资本回报斜率持续超 capex 增速**（2.6 路径①收入斜率，`2.11-B`），云商维持/上调指引；
- (ii) 电价与并网约束（`0.1-C15`）**物理性限速**——capex 因物理约束而非财务恶化"自然放缓"，非病理性下修；
- (iii) 下沉需求（edge/推理）接棒训练集群，HBM4/新一代维持赚钱效应。
> 边界：若本骨牌倒，订单下修向 HBM/PPA 的传导即 5.4；三情景综合属第 7 章。

## 5.4 第四级骨牌：芯片订单→HBM 存储周期→能源 PPA 重谈（联网独立核验，执行日 2026-09-07）

**【联网核验·替代来源（记入核验表 0.8）】**
- **HBM**：36GB HBM3E 现货 **$2100**，为长协价（约 $350–500）的 **4–5 倍**（[新浪财经/东方财富](https://finance.sina.com.cn/wm/2026-09-01/doc-iniqfuyq1687452.shtml) 引 MegaGrid Supply，`0.8-1`）；SK hynix HBM4 对 Nvidia 约 **$31–32/GB**（近 HBM3E $17–18 的 2 倍，Cantor/Fubon 估，[aistockwire](https://aistockwire.com/blog/sk-hynix-hbm4-nvidia-price-estimate-samsung-august-2026)）、三星 HBM4 约 **$700/颗** +20–30%（[证券时报](http://www.cnstock.com/commonDetail/639495)，`0.8-2`）；SK 批准 54 万亿韩元扩产、三星 **70% 产能锁至 2031**（`0.8-3`）。
- **能源 PPA**：佐治亚 PSC 批 Georgia Power–OpenAI Effingham 3.2GW/$200 亿，**合同显式预留"提前终止不向 ratepayer 转嫁、取消 15 天内通知 PSC"**（[atlwire](https://atlwire.com/2026/08/29/)、[activetraderdaily](https://www.activetraderdaily.com/2026/08/29/georgia-just-wrote-the-rulebook-for-ai-power-contracts/)，`0.8-4`）；**Microsoft vs PowerHouse Hillwood** FERC 供电协议重谈纠纷（[Utility Dive](https://www.utilitydive.com/news/microsoft-powerhouse-hillwood-data-center-service-ferc/828566/)，`0.8-5`）；企业 PPA 解约费≈剩余年数×量×价×**50–100%**，故下行周期"**重谈/降负荷优先于解约付罚**"（`0.8-6`）。

**① 触发条件**：若第三级 capex/芯片订单下修（承压承诺见 `0.1-B8` OpenAI 1.4 万亿、`0.1-B1` Stargate 5000 亿）→ **HBM 从"现货=长协 4–5 倍"的极短缺**（`0.8-1`）**反转**，但供给刚性（SK 54 万亿/三星锁至 2031，`0.8-3`）使存储合约价**下修最陡**；同时能源 PPA 从"锁定"转"重谈/降负荷"（`0.8-4/5`）→ 第四级倒下。
**② 指标与当前读数**：现货=长协 4–5 倍（`0.8-1`）为"补单极度短缺"读数；HBM4 $31–32/GB（`0.8-2`）为新一代涨价；佐治亚 PPA 已批但预置终止条款、MS-PowerHouse 已起 FERC 纠纷（`0.8-4/5`）。**当前仍处供给紧、反转信号未出现**——反转的触发源是**上游订单下修**，而非存储/PPA 自身。
**③ 预警时间**：L3 触发后 **4–8 季**——订单挤压→存储供给/合同周期调整、PPA 重谈以月–季为节奏，均为长传导。
**④ 来源/置信度**：`0.1-B1/B8`、`0.8-1~0.8-6`；**Medium**（HBM 价格为分析师估算、PPA 为个案核验，非行业面）。
**⑤ 【不倒条件】**：至少一条——
- (i) **HBM 短缺足够真实（供给刚性）** 使合约价抗跌，而非随订单摆动；
- (ii) 能源 PPA 为**长期刚性需求**（24/7 CFE 结构与自专门供应要求，`0.8-4`），且数据中心有持续客户（如 xAI-Google 9.2 亿/月租约，`0.6-6`）；
- (iii) **上游订单实际未下修**——前级骨牌不倒，本楼道不塌。
> 边界一句：断裂后对实体经济（电价、资本开支就业）的映射与历史四镜对照归第 6 章。

## 5.5 第五级骨牌：搁浅数据中心与 dark fiber 2.0（遗产论证，结构性，非安慰性收尾）

**① 触发条件**：若前四级阻断新增投资→在建设施（密歇根/新墨西哥 SPV 已批，`0.5-1`）与已运转机柜空置率上行→出现"搁浅/半建成"数据中心→**触发减记（会计，归第 3 章）与信贷断裂（归第 4 章）**；但**过剩同时沉淀出"廉价算力 + 廉价带宽"的复用基础设施**——这是一枚硬币的两面。
**② 指标与当前读数**：在建设计容量与 SPV 融资已批（`0.5-1`）；已落地长租（如 Google–xAI 11 万颗 GPU/9.2 亿月租，`0.6-6`）；**空置率/未售长租比例暂无权威读数**（登记缺数，Low）。当前处于"在建高峰、空置尚未显性化"。
**③ 预警时间**：最长——**12–36 个月**（资产减值、清算、再利用需多个财季）。
**④ 来源/置信度**：`0.5-1`、`0.6-6`、`0.1-C11/C12`（电信 2000s、dark fiber 对照）；**Low–Med**（空置数据缺失）。
**⑤ 【不倒条件】与结构判读（反爽文·遗产论证）**：
- **"崩盘死的不是技术"（结构性，非安慰）**：dark fiber 1.0 的教训是——上一代光纤过剩最终**廉价化带宽**、催生内容与应用生态；本轮若过剩算力重演，**廉价化的是 GPU 推理**，拓宽的是 AI 应用边界。**资产估值缩水 ≠ 技术失效**，两者必须分离陈述：前者计入信贷断点（第 4 章），后者是下一阶段的需求底座（第 2 章路径）。
- **不倒条件**：若**迭代节奏放慢**（新一代 GPU 延迟，`0.1-C14`/`0.8-2` 反向），则搁浅资产可被**长尾推理/边缘/企业 IT 再利用**→避免全额减记；此即"过剩为下一阶段定价与铺路"的机制——**过剩产能不以"全损"终局，而以"折价再配置"进入下一轮**。
- **警示（防写成安慰）**：这**不排除**信贷与估值的即期破坏（第 4/7 章），遗产论证只说明"技术存续"，不等于"当期资产不缩水"。
> 边界一句：三情景综合烈度（硬/软/基准）归第 7 章；dark fiber/电信 2000s 的历史四镜完整对照归第 6 章。

## 5.6 配重落位：到期墙=条件放大器，与一致性质询收口

**① 到期墙已降级为条件放大器（落实配重指令）**：第 4 章 4.2 已重算——全年附加约 **280–420 亿/年（约 +8%）**，不再是独立触发器。本章依此把它定位为**放大器**：**仅当"再融资市场关闭"（rollover failure）情景出现，才升级为悬崖**——机制即 Kindleberger 式的一句话：恐慌的诱发常始于"某个重压下的融资方无法滚动其到期债务"，从而由单体展期失败转为普遍信用收缩。故到期墙不独立引爆，只在 5.2 追保潮已把市场推向"拒续融资"时放大第二级→第三级的传递烈度。
**② 一致性质询收口（已升 5.2 前置）**：两年举债 3420 亿 vs 墙内到期 840–1260 亿 ⇒ **63–75% 债项 2028 年后到期**；判定取**"短档保留快钟"**——期限长只延后"到期/再融资型"触发器（故到期墙仅放大器），但快钟本源（抵押品市值重估触发 LTV）**不由期限决定**，由 40–60% 短档内的抵押条款承担并保留（演算见 5.2）。**两说已取其一，不并存。**
**③ 信用敞口口径（强制、禁止回退）**：本章骨牌序列的量化烈度一律绑定第 4 章 4.5 口径——硬着陆情景实际信用敞口**占缺口总额约 1/4–1/3、峰值叠加收窄至 1/2–2/3**，**不以缺口总额 6550 亿作为信用冲击参数**。此口径即第 7 章三情景烈度的输入，本章不再另设敞口口径。

## 5.7 本章自检清单

**① 五要素完备性（反爽文纪律）**：L1–L5 每级均含 **①触发(若X则Y) ②指标与当前读数 ③预警时间(硬→软传导差) ④来源行号与置信度 ⑤不倒条件**；5.0 有横截面总纲表。**无任何一级只写倒塌而无存活条件。**
**② 边界检查**：三情景综合烈度→第 7 章；历史四镜（WorldCom/电信 2000s/dark fiber）→第 6 章；二者各一句前向引用，无越权展开。骨牌仅到"触发条件+指标"，不做时序模拟。
**③ 数字来源核对结果**：
- 核验表既有行号直引：`0.1-A3`（2026 指引）、`A6`（96%/FCF/长债）、`B1/B8`（Stargate/OpenAI 承诺）、`C5/C6/C9/C11/C12/C14`（CoreWeave/投资级/xAI/电信/dark fiber/HBM）、`0.5-1/3`（SPV/H100 长约）、`0.6-8`（Nebius）、`0.6-13`（指引更新）、`3.0-6`（ICFR）、ch4 4.3-C/4.4/4.5、`2.11-B`。
- **新增 0.8 子表（执行日 2026-09-07，只增不改）**：`0.8-1~0.8-6`（HBM 现货/定价/扩产、PPA 终止结构/FERC 纠纷/解约费）；未改动既有行号。
- **估算值·置信度低/登记缺数**：三分档追保演算（参数假设）、到期墙附加 280–420 亿/年、数据中心空置率（暂无权威）、HBM 价格为分析师估算（Med）。
**④ 配重落实与一致性质询收口**：到期墙定位为条件放大器（附 Kindleberger 一句）；歧义"长债 vs 快钟"已取一（短档保留快钟，演算在 5.2）；信用敞口口径绑定 4.5（占缺口 1/4–1/3、峰值 1/2–2/3），未回退到"小一半"。

> **执行状态**：第 5 章（五级骨牌序列）完稿。L1–L5 五级各含五要素、同级附"不倒条件"；断裂只到"触发条件+指标"，三情景/历史四镜各一句前向引用；联网核验 HBM 与 PPA 已记入核验表 0.8（只增不改）。按"一次一转纪律"，本章至此结束，不续写下一章。

---

# 第 6 章 · 四镜六维：超级资本周期结构对照矩阵（1840s铁路 / 1920s公用事业 / 1990s电信 / 2020s AI）

> **章内声明**：本章产品是**结构地图**，不是方向押注。四镜 = 1840s 铁路（英国铁路狂热＋1860s–70s 美欧铁路）、1920s 公用事业（Insull 体系）、1990s–2000s 电信（宽带/dark fiber）、2020s AI（本报告主体）。**六维 = 融资形态 / 需求真实性 / 会计手法 / 断裂方式 / 社会后果 / 技术遗产**（与 3.6 内部"六维"口径不同，本章按用户指定口径）。历史数据全部联网核验、来源内联；携带已知修正（0.2 纪要 11 条）。**对照锚继承**：Insull 部分**不重新考证**，直接引用 3.6 修正基线（两次审判均无罪、控制资产 $5–40 亿区间）；dark fiber 遗产论证**直接引用 5.5**，本章只做跨镜对比、不做新论断。
>
> **边界警告**：不得在本章产生新的断裂点预测（第 5 章已封笔）；不得写三情景（第 7 章职责）；历史对照服务于结构地图，不服务于方向押注。置信度标签随数字走；估算值一律标注性质。

## 6.0 方法注记：四镜六维的取数纪律

- **历史镜取数**：铁路镜、电信镜为第 6 章独立联网核验（执行日 2026-09-07，登记核验表 `0.9`，只增不改）；公用事业镜继承 3.6（其基线来自 3.0-8/9/10，`0.1` 修订口径）；AI 镜全部引用核验表既有行号（`0.1/0.5/0.6/0.8`）与前章（2.6/2.11-B、3.3/3.6、4.4/4.5、5.5）。
- **口径显式化（宪法 0.7-⑤）**：凡引入多主体聚合口径数字，必须标注聚合范围。电信镜的"崩塌"强制拆分为**运营商 capex 降幅**与**设备商营收降幅**两个口径（见 6.2-D）；铁路镜投资占 GDP 比例标注**估算性质**。
- **三个已知修正已携带**：(i) Lucent/Nortel 卖方融资**分列**（Lucent 承诺约 $81 亿 / Nortel 承诺约 $31 亿、约 $14 亿未偿），不再沿用"各约 $70–80 亿"；(ii) 电信"崩塌超八成"降级为"峰值后腰斩级快速收缩、按 TIA/FCC 口径";(iii) 铁路投资峰值约占 GDP 5.7–7% 为**估算**。

## 6.1 四镜×六维总纲矩阵

| 维度 / 镜 | 1840s 铁路 | 1920s 公用事业 | 1990s 电信 | 2020s AI |
|---|---|---|---|---|
| **融资形态** | 股权为主（部分缴付股＋催缴）；铁路股占股市市值 23%(1838)→63–71%(1848)；峰值投资约 GDP 5.7–7%（1847，估算） | 顶层股权 $2700 万控 $5–40 亿（3.6 继承）；股票/债券/信托多层叠加 | 运营商 capex 峰值 $1,131 亿(2000，TIA)；设备商卖方融资 Lucent $81 亿 / Nortel $31 亿；WorldCom 债务 $410 亿 | FCF→债→私募→GPU 抵押→SPV 逐层迁移；CapEx/OCF 96%、长债 1320→3419 亿；缺口 6550 亿、债务敞口 1350–2180 亿/年（4.5） |
| **需求真实性** | 约 1/3 获批线路未建成；股息承诺 7–10%→实际 2% | 需求 1920s 高增、1930s 下坠，现金流承压（3.6） | 1998–2001 光纤建设约 $5,000 亿；2002 点亮率 <5%；CLEC 模式脆弱 | 循环采购占比高（3.4）；路径①真实降本锚存在但 k=2–5% 瓶颈（2.6） |
| **会计手法** | Hudson 从资本付息、虚增估值；1844 法案未强制定折旧与股息上限 | 多层控股+内部融资+关联交易+账面复杂化；**两次无罪**（3.6） | WorldCom 费用资本化虚增 $38 亿→累计约 $110 亿；Lucent 不当收入确认 $11.48 亿；Nortel cookie-jar | 折旧拉长+前置确认为"合规内激进"（3.1/3.4）；Nebius ICFR weakness（3.5） |
| **断裂方式** | 1845–46 崩盘、1850.4 较峰值 -66%；1847 危机 4 家银行倒闭；1873(美) 铁路破产潮 | 1932 债权人拒续贷→接管；1934/35 无罪；损失约 $8 亿（3.6） | 运营商 capex TIA 口径 -18.2%(2001)、设备商营收更深（Lucent 2002 -42%）；WorldCom/Global Crossing 破产 | **未触发偿付断点（截至执行日）**；断裂条件见第 4 章、骨牌"不倒条件"见第 5 章 |
| **社会后果** | 散户/中产受损，损失约 £230m（≈半年国民收入，估算）；1847 银行倒闭 | 60 万股东/50 万债权持有人受损；PUHCA 1935 崩后立法（3.6） | 电信股 -75%；50 万+ 岗位流失；约 $2 万亿市值损耗（TIA 转述） | 尚在建构期；资本向头部/股权集中；触发形态未定（不写三情景） |
| **技术遗产** | 到 1850 年 6,621 英里铁路网沉淀，成为工业化基础 | 电力网成为后续技术扩散底座（3.6 继承 + 2.6-D 发电机悖论） | dark fiber 廉价化带宽，催生云计算/流媒体（5.5 继承） | 若过剩算力重演→廉价 GPU 推理拓宽 AI 应用（5.5，结构非安慰） |

> 矩阵判读总纲：**四镜的"同构"集中在融资形态与断裂方式的耦合**（顶层出资远小于控制资产、需求斜率决定偿付）；**最大"本轮差异"集中在循环结构尺度、抵押品贬值速度与缺口的形式化可见性**（详见 6.3）。

## 6.2 六维分维对照简评

### 6.2-A 融资形态

- **铁路**：股权主导、部分缴付股机制（先付少量保证金、余额随建设"催缴"），铁路股占英国股市市值从 1838 年约 23% 升至 1848 年约 63–71%（[Wallstreetbeats](https://www.wallstreetbeats.com/insights/the-railway-hallucination-the-infrastructure-that-outlived-its-shareholders)，Medium）；峰值年资本形成约 GDP 5.7%（1846）→6.7%（1847）（[Campbell 2014, QUB](https://pureadmin.qub.ac.uk/ws/files/18161511/RailwayCrisis.pdf)，High的学术估算），**该占 GDP 比例为估算性质**；另有叙事口径称约 7%（[Markethistories](https://www.markethistories.com/en/the-railway-mania-britains-victorian-tech-bubble-1840s)，Medium）。**卖方直接融资证据弱**：机钢/机车制造商接受股票或票据为货款的系统性做法未获可靠来源（核验缺证，Not established）。
- **公用事业**：**继承 3.6**——顶层股权 $2700 万控 $5–40 亿资产，股票/债券/信托多层叠加。
- **电信**：运营商 capex 峰值约 $1,131 亿（2000，TIA 向 FCC 报告口径）（[TIA/FCC CapEx](http://standards.tiaonline.org/gov_affairs/fcc_filings/documents/Nov13-2002_CapEx_QoS_Final.pdf)，High）；设备商**卖方融资是核心新药**——Lucent 2000 财年买方融资/担保承诺约 **$81 亿（占营收约 24%）**、Nortel 承诺约 **$31 亿（约 $14 亿未偿）**（[Tom Tunguz](https://tomtunguz.com/nvidia_nortel_vendor_financing_comparison)、[Buxton Helmsley](https://www.buxtonhelmsley.com/news-and-insights/the-circular-bargain-how-reciprocal-investment-and-vendor-backstops-are-manufacturing-demand-inside-the-artificial-intelligence-capital-cycleand-what-institutional-investors-must-demand-before-they-underwrite-the-next-build-out)，Low–Med）；WorldCom 破产时债务约 $410 亿（SEC/国会档案，High）。
- **AI**：融资形态逐层迁移（FCF→债→私募→GPU 抵押→SPV，0.6）；CapEx/经营现金流 96%（0.1-A6，Medium）；长债 1320→3419 亿（0.1-A6）；缺口 6550 亿、融资型 3550–4550 亿、债务敞口 1350–2180 亿/年（4.5）。
- **判读**：四镜中有三镜（铁路/电信/AI）以"外部资金承接供给侧扩张"为共同枢纽；**头部盈利不等于偿债安全**——Lucent 2000 年营收 $338 亿、也曾是巨头，但其卖方融资最终大量坏账。

### 6.2-B 需求真实性

- **铁路**：约 1/3 获批线路从未建成（[Victorian Web](https://www.victorianweb.org/economics/railwaypanic.html)，Medium）；股息承诺 7–10%→实际约 2%（Wallstreetbeats 转述，Low–Med）；Great Western 原估 £2.5m 实际 £6m（Songs from the Age of Steam，Low）。
- **公用事业**：需求 1920s 高增、1930s 下坠（继承 3.6 收入镜——历史电力为**真实终端需求**）。
- **电信**：1998–2001 电信与互联网基础设施公司投资约 **$5,000 亿**建设光纤（[Pomegra](https://pomegra.io/learn/library/market-history/infrastructure-paradox)，Medium）；2002 年已安装光纤**点亮率低于 5%**（另一口径约 2.7%，[RootByte](https://rootbyte.tech/article/dark-fiber-ghost-cables-dot-com-boom-1998)，Low–Med）；WorldCom"流量每 100 天翻倍"宣传被证伪（TIA 听证，High）。
- **AI**：循环采购占收入比重高（3.4）；**路径①存在真实降本锚**——可触达工资池 W≈27 万亿、远期基准收入 1600–5700 亿/年，但当期组织兑现率 k 仅 2–5%（NANDA 95% 试点未回报交叉锁定，2.6-B/C）。
- **判读**：**"真实需求锚"是四镜的共同宣称**——铁路确实运货、光纤确实传数据、电力确实供电、AI 确实降本；**差异在"当期已兑现的真实需求"占比**。电信与 AI 均存在"需求论证先行于兑现"的结构，历史规律是该锚在狂热期无法充当偿付的充分条件，只能充当下行期的需求底座（见 6.2-F）。

### 6.2-C 会计手法

- **铁路**：George Hudson 案——从资本支付股息、虚增资产估值、内部交易获利（[Newcastle University Collection](https://co-curate.ncl.ac.uk/george-hudson-1800-1871/)，Medium）；1844 铁路法案未强制折旧计提与股息上限（Victorian Web，Medium）；调查发现约 £600,000 相关欺诈（Wallstreetbeats 转述，Low–Med）。
- **公用事业**：**继承 3.6**——多层控股+内部融资+关联交易+账面复杂化；**但两次审判均无罪（1934/35），"利润平滑"证据弱**（不得平移罪名）。
- **电信**：WorldCom 将线路/运营成本资本化虚增利润约 **$38 亿**（SEC 诉状 [comp18605](https://www.sec.gov/litigation/complaints/comp18605.htm)，High），累计重述约 **$110 亿**（破产审查人 Thornburgh 证词，High）；Lucent 不当确认收入约 $11.48 亿（[SEC comp18715](https://www.sec.gov/files/litigation/complaints/comp18715.pdf)，High）；Nortel 用 cookie-jar reserves 平滑利润（Transparently AI 综述，Med）。
- **AI**：折旧年限拉长+前置确认为"**合规内激进**"，非欺诈指控（3.1/3.4）；已现制度化预警出口——Nebius ICFR adverse（3.5-C，Med）；抵押品估值 GPU 抵押折扣 16–85%（4.4，Low）。
- **判读**：会计手法的"同构"是**账面与现金流脱钩**；"差异"在**复旦制度化**——铁路/电信/WorldCom 为事后调查或被定罪，当代（AI 镜）在监管落地前已有 ICFR 内控披露这类"第三防线"（3.5-C），当代会计激进更"合规"、也更难被事后归类为欺诈（与 3.6-C 会计制度化差异呼应）。

### 6.2-D 断裂方式（强制双口径）

- **铁路**：1845.8–12 铁路股跌约 20%、1850.4 较峰值跌约 **66%**（[Tontine Coffeehouse](https://tontinecoffeehouse.com/2023/07/24/railway-mania/)，High）；1847 商业危机中约 **4 家银行倒闭**（Victorian Web；Campbell 2014，Medium）；美国侧 1873 震动（Jay Cooke 破产触发，[Legends of America](https://www.legendsofamerica.com/financial-panic-1873/)，Medium），新建铁路里程由 1872 年 7,439 英里降至 1876 年 1,606 英里（[Sage](https://sk.sagepub.com/ency/edvol/encyclopedia-of-us-political-history/chpt/panic-1873)，Medium）。
- **公用事业**：**继承 3.6**——1932 债权人拒续贷→接管；1934/35 无罪；损失约 $8 亿（损失口径非资产）。
- **电信·运营商 capex 降幅（口径 A）**：美国电信运营商 capex 2000 年 $1,131 亿→2001 年 $926 亿（**年降 18.2%**，TIA/FCC 口径）（[TIA/FCC](http://standards.tiaonline.org/gov_affairs/fcc_filings/documents/Nov13-2002_CapEx_QoS_Final.pdf)，High）；无线侧 2002 年再降约 25.4%（[RCRWireless 引 TIA](https://www.rcrwireless.com/20021126/archived-articles/tia-warns-fcc-about-economic-impact-of-decline-in-capex-research)，Med）。⚠️ **"2002 较 2001 降 48%"未在 TIA 官方口径中核到**，第 6 章不用该数；"腰斩级收缩"主要体现于累计两年与设备商营收侧，而非 TIA 单年官方数。
- **电信·设备商营收降幅（口径 B）**：Lucent 2001 财年营收同比 -26%、2002 财年同比 **-42%**（[SEC Lucent 2002 10-K](https://www.sec.gov/Archives/edgar/vprr/0206/02067986.pdf)，High）；Nortel 2002 Q2 营收同比大幅收缩（[SEC Nortel 2002 Q2](https://www.sec.gov/Archives/edgar/data/1119664/000113031902000694/t07613ore8vk.htm)，High）；WorldCom、Global Crossing 陆续破产（High）；Nortel 2009 破产（CBS/CorporateVault，Med）。
- **AI**：**截至执行日未触发偿付断点**；断裂条件（若 X 则 Y）归第 4 章、骨牌"不倒条件"归第 5 章；本章不做新预测。
- **判读**：**电信"崩塌"的体感主要来自设备商营收与股价（口径 B），而非运营商 capex 单年降幅（口径 A）**——这一双口径拆分是本轮 AI 报告必须复制的纪律：当"租金/营业收入"下修时，要先区分"最终用户需求降幅"与"供给侧收入降幅"，避免用后者冒充前者造成塌方式过度叙事。

### 6.2-E 社会后果

- **铁路**：投资者损失约 £230m（≈英国半年国民收入，估算；[Almost History](https://www.almosthistorypodcast.com/2843/)，Low–Med）；中产/储蓄者（牧师、寡妇、仆人等）受损普遍（[Victorian Web](https://www.victorianweb.org/economics/railwaypanic.html)，Medium）；1847 银行倒闭。
- **公用事业**：**继承 3.6**——60 万股东/50 万债券持有人受损；PUHCA 1935 为"崩后立法"。
- **电信**：电信股自 2000.4 至 2002.1 下跌约 **75%**（圣路易斯联储，High）；**50 万+** 电信岗位流失（美联储综述/参议院，High–Med）；行业市值损耗约 $2 万亿、公司债务约 $1 万亿（TIA 转述，Low–Med）。
- **AI**：**尚在建构期**——资本向头部/股权集中已现（0.1-A6），但"社会后果"（就业替代/主权写入/财富再分配）的形态未定，本章不写三情景（第 7 章职责）。
- **判读**：三面历史镜的共性是社会后果**滞后于资产价格断裂一到两个财季**、且**集中冲击储蓄层**（散户/养老基金/债券持有人）；AI 镜若设定社会后果维度，须先厘清"GDP 与就业"两个子层，而非与历史做简单数目对比。

### 6.2-F 技术遗产（继承 5.5，不重述为新论断）

- **铁路**：到 1850 年铁路网 6,621 英里、1855 年逾 8,000 英里沉淀为工业交通底座（[Markethistories](https://www.markethistories.com/en/the-railway-mania-britains-victorian-tech-bubble-1840s)、[T&F](https://www.tandfonline.com/doi/pdf/10.1080/00076791.2022.2096877)，High）；"财富毁灭 ≠ 技术失效"，资本与工程经验随后由英国输出至美/印/南美铁路（Washington Morning 转述，Low）。
- **公用事业**：电力网成为后续技术扩散的物理底座（3.6 继承；发电机悖论见 2.6-D，David 1990）。
- **电信**：**直接继承 5.5**——dark fiber 过剩廉价化带宽；破产光缆资产以 5–15 美分/美元回收（Pomegra，Low–Med）、2004 年长途批发价同比约 -55%（TechnoStatecraft，Low）；Level 3 低价收购濒危网络并在多年后成为骨干资产持有方（Pomegra，Med）——**过剩产能以"折价再配置"进入下一轮，而非"全损"终局**。
- **AI**：继承 5.5——若过剩算力重演，廉价化的是 GPU 推理、拓宽的是 AI 应用边界；**"资产估值缩水 ≠ 技术失效"必须区分陈述**（减值/断点归第 4/7 章，需求底座归第 2 章路径）。
- **判读**：四镜技术遗产维度高度同构——**每一轮过度建设都沉淀出下一轮可复用的物理/能力底座**；但"技术存续"不构成"当期资产不缩水"的慰藉，遗产论证只说明存续形态，不否定当期信贷破坏（继承 5.5 警示）。

## 6.3 最高警戒·独立小节："本轮不同之处"（先列候选，逐点验证，每个"不同"配"但相同"反证）

**执行规则（宪法 0.7-② 辩证法）**：下述七项候选差异点，逐点给【验证】（是否采用）→【但相同】→【净裁定】。**凡未验证通过或无法取得可靠历史对照者，不采用为硬论断，列 Low/待核验**。

### 6.3-① 需求端有真实降本锚（候选·引 2.6 路径①）

- **验证（采用，Medium）**：AI 路径①确有一个"当下最干净、可量化"的真实降本锚——可触达工资池 W≈27 万亿、远期基准收入 1600–5700 亿/年（2.6-A/C）；组织兑现率 k 由 NANDA（95% 试点未见回报）与 Menlo（当期渗透率 <0.4%）两路独立实测交叉锁定在 2–5%（2.6-B，Medium-High）。就"需求具备真实的企业降本理由"而言，比电信"每 100 天翻倍"的假设更扎实。
- **但相同**：**"有真实需求锚"是四镜共同宣称**——铁路当年也被视为革命性（确实有货运需求），光纤确实传数据，电力确实供电。真实需求锚在每个狂热期都存在；本轮的特征不是"有锚"，而是**问题位于另一侧（k 的兑现）**。若 k 停滞于当期，则"有锚"降级为"潜在降本"，与 1870s 铁路"有真实运输需求但过度建设"同构。
- **净裁定**：**采用为"不同"但限定在"锚已形式化、可量化"的窄义**；不纳入"已兑现需求"（k 仅 2–5%，未证实）。此点与候选 ⑤（缺口算术形式化）共享同一逻辑。

### 6.3-② 头部企业真实盈利（候选·Nvidia FCF）

- **验证（采用，Medium）**：Nvidia FY2026 数据中心收入约 $1,937 亿（+68%，0.1 #11，High），是全网唯一净现金流巨头、实际背书人（1.1）；其盈利是供给侧证据（芯片商真实拿到现金）。
- **但相同**：**电信周期供给端也曾"盈利"**——Lucent 2000 年营收约 $338 亿、也曾高增长（[Buxton Helmsley](https://www.buxtonhelmsley.com/news-and-insights/the-circular-bargain-how-reciprocal-investment-and-vendor-backstops-are-manufacturing-demand-inside-the-artificial-intelligence-capital-cycleand-what-institutional-investors-must-demand-before-they-underwrite-the-next-build-out)，Med），但卖方融资导致其应收账款最终大量坏账。**供给端盈利先于需求端偿债能力崩坏**是常见时序——Nvidia 盈利在结构上只能证明"资金在回流供给侧"，不能证明"买承诺的偿债端现金流"足够（后者恰是本报告第 4 章缺口命题的薄弱侧）。
- **净裁定**：**采用为"不同"但只作用于供给侧信号**；明确其不构成偿债端安全证明，与电信镜 Lucent 形成强对照、不得混淆。

### 6.3-③ 循环结构更极端（候选·引第 1 章闭环）

- **验证（采用，High）**：本轮循环性是**跨行业、跨身份的多方闭环**——芯片商/云商/模型实验室三方互持+互相采购（1.2/3.6-C）；Anthropic 每 1 美元股权撬动约 4.1–11 倍采购承诺（2.4-2，最干净闭环演算）；循环回流率结构量级见 1.4。其"极端"体现在**尺度**（Stargate $5,000 亿、OpenAI 承诺 $1.4 万亿量级）与**跨行业传播面**。
- **但相同**：**循环/关联结构并非本轮首创**——1920s 公用事业是单行业纵向多层控股+内部融资（3.6 继承）；电信设备商卖方融资（Lucent/Nortel 借钱给买方买自己产品）就是"卖方融资闭环"的历史原型（6.2-A）。本轮只是把循环的**身份复杂度与跨行业度**推到极值，机制（卖方融资/关联交易回购）同构。
- **净裁定**：**采用为"不同"但注明"机制非首创、差异在尺度与跨行业度"**——用于支撑"传播面可能更广"（3.6-C 第 5 点），不用于支撑"全新机制"论断。

### 6.3-④ 抵押品自带贬值属性（候选·引 4.4/5.2）

- **验证（采用，Medium）**：本轮债务高度以**特定型号算力资产（GPU）为抵押**，且该资产**半年一代更新、技术贬值快**（折旧裂缝 3.3；GPU 抵押折扣 30%/60%/85% 三分档 5.2、区间 16–85% 4.4）；HBM 现货背离长协 4–5 倍（0.8-1）直指"新一代承价、旧代承贬"的镜像。
- **但相同**：**任何抵押品在崩盘期都会缩水**——电信暗纤/光缆破产资产以 5–15 美分/美元回收（6.2-F）、铁路资产也被接管重组。贬值属性本身是历史共同点，不是本轮独有。
- **净裁定**：**差异不在"会贬值"，而在贬值速度与作为核心抵押品的权重**——GPU 半年一代的节奏对应"快钟假说"（1.5），比光纤/铁路数年折旧更快；此项**采用**，但严格定位为"抵押品快速贬值的速度差异"，而非"抵押品存在贬值"这一共同面。

### 6.3-⑤ 缺口算术已形式化 + 2×2 生成矩阵（候选·引 2.3/2.11-B）

- **验证（采用，Medium）**：本轮把缺口做成了**可受检的算术**——中心缺口 6550 亿、融资型 3550–4550 亿、债务敞口 1350–2180 亿/年（2.3/4.5）；覆盖率 2×2 生成矩阵 13–73%、同向带 26–36%（2.11-B，矩阵引用纪律见宪法 0.7-③）。
- **但相同**：**形式化的"计划"不等于"避免"**——铁路时代有里程计划/回报率承诺、电信有流量翻倍模型，形式化提升的是**可证伪/可纠错**，不是消除缺口本身。它把盲区显性化，但不改变缺口总量命题。
- **净裁定**：**采用为"方法差异"（工具进步）而非"周期性质差异"**——它更多是**写作本报告的方法论进步**（卫生约束），不是本轮资金循环的结构性独有特征，故降权为"受检性更强"的次要点。

### 6.3-⑥ 算力现货已按边际成本定价（候选·引 3.3/5.5 刀刃发现）

- **验证（采用，双面判定）**：H100 现货约 $2.79–2.82 企稳、1 年长约由低点 $1.70 回升至 $2.10–2.70（0.5-3，High），技术口径含运营成本线约 $3/h 已现交叉（3.3）——**现货端已接近边际成本定价**，供给一放大价格即时传导。
- **但相同（反向证）**：dark fiber 带宽价历史上已**跌至近零**（6.2-F：2004 长途批发价约 -55%；这正是在边际上按供给定价的同构例证）。→ **若以"按边际成本定价"为"本轮更成熟/更不同"的证据，则电信 dark fiber 已先于本轮到达该态**，说明"过度供给→边际成本坍缩"是反复出现的周期性规律，而非本轮独有。
- **净裁定**：此点**可证"不同"亦可证"相同"**——我方裁定：**按"相同偏强"归类**——即"供给过剩导致边际成本坍缩"是本轮与电信共享的重构；"不同"仅存在于机制细节（本轮既有成熟的**现货市场**实时出清，dark fiber 时代定价滞后）——该机制细节**降权为 Low**，不纳入"本轮独有优势"的加分项。

### 6.3-⑦ 信用敞口占缺口比低于电信周期（候选·引 4.5）

- **验证（核验后**部分采用·Low**）**：AI 侧硬数据确凿——债务敞口占缺口约 1/4–1/3（1350–2180 亿/年，4.5），峰值叠加后收窄至约 1/2–2/3（5.6/4.5 口径）。但**电信周期的"信用损失/总投资"聚合口径无单一权威来源**（本次子代理联网核验未检索到可比的统一比例，只有分项：WorldCom 单点债务 $410 亿、Lucent 卖方融资 $81 亿、TIA 转述的行业约 $1 万亿公司债务）。**按"不得凭空断言"纪律，此项不采用为量化硬论断**。
- **但相同（方向反证）**：AI 缺口本身含持续展期压力（4.6：CapEx/OCF 96% 下信用层是边际资金来源），且若硬着陆叠加到期墙，敞口可上修至约缺口一半——与电信"崩盘期信用冲击+市场冲击叠加"的结构量级并非干净可比。
- **净裁定**：**仅作方向性、Low 置信度表达**（"AI 债务敞口相对其缺口占比或低于电信崩盘期信用冲击占比"），**不做倍差量化、不进入硬结论**；引用必须绑定 4.5 口径（占缺口 1/4–1/3），不得另设口径。

### 6.3-C 收敛判读（"不同"的真集）

七项候选验证收敛后，真正**通过验证的"本轮不同"**仅收缩为四类：
1. **循环结构的尺度与跨行业度**（③，High）——机制非首创，尺度与传播面为本轮独有。
2. **抵押品贬值速度**（④，Medium）——GPU 半年一代 vs 光纤/铁路数年折旧，对应快钟（1.5）。
3. **真实降本锚的形式化**（①窄义+⑤，Medium）——锚确凿但证在 k 兑现、缺口算术可证伪。
4. **需求端多发高收入循环采购占比**（②供给侧对中的镜像，Medium）——均非偿债安全证明。

被**裁定为"相同偏强"或降权**的：⑥（边际成本定价→同构于 dark fiber）、⑦（信用敞口对比，Low 不采用为硬论断）、②（偿债端 vs 供给端须分清）。**净结论：本轮与电信/公用事业在"结构骨架"（顶层出资小于控制资产、需求斜率决定偿付、账面与现金流脱钩）上高度同构；"不同之处"是尺度与速度的极端化，而非机制的更替。**历史对照到此只绘制结构地图，不做第 7 章方向押注。

## 6.4 跨镜收敛：结构地图的用途与边界（不押注方向）

- **结构地图用途**：四镜六维矩阵把"超级资本周期"拆解为**可检验的维度**——任一当下的 AI 观测哨（0.3）都可在历史上找到对应维度（审计预警→ICFR 早于监管、抵押→GPU 快钟、需求→k 兑现、遗产→廉价推理）。读到观测信号时，先问"它在哪一维、历史上该维的典型结局路径是什么"，而非直接指向第 7 章情景。
- **结构地图边界**：① 不产生新断裂点预测（第 5 章已封笔）；② 三情景归第 7 章；③ **历史同构≠当期预言**——Insull 两次无罪、dark fiber 廉价化带宽证明结局各异，历史对照只框定"可能的维度"，不框定"必然的结局"（继承 3.6 红线：不平移任何历史罪名/结局至当代主体）。
- **对第 7 章的移交（一句前向引用）**：三情景烈度参数（债务敞口中心 1350–2180 亿/年、到期墙 280–420 亿/年条件放大器）已由第 4/5 章登记，第 7 章执行，本章不展开。

## 6.5 本章自检清单（三项）

**① 边界与义务履行**
- Insull 部分**未重新考证**，直接引用 3.6 修正基线（两次无罪、$5–40 亿区间）；dark fiber 遗产论证**继承 5.5**，本章只跨镜对比、无新论断。
- 无新增断裂点预测（第 5 章封笔）；无三情景（第 7 章职责）；历史对照仅服务于结构地图。
- 已知修正已携带：Lucent/Nortel **分列**（81/31 亿，0.2-⑤）；电信崩塌双口径拆分（6.2-D）；铁路占 GDP 峰值标注估算性质（5.7–7%）。
- **口径打回记录**：本次任务中"各约 $70–80 亿"沿用旧式，已按 0.2-⑤ 分列口径修正；**"2002 较 2001 降 48%"未在 TIA 官方核到，未采用**，改用 TIA/FCC 官方 -18.2%(2001)＋无线 -25.4%(2002)＋设备商 Lucent -42%(2002) 三档并列。

**② 数字来源核对结果**
- 铁路镜、电信镜：本执行日独立联网核验，来源内联于 6.2 各小节，并登记核验表 `0.9`（只增不改）。
- AI 镜：全用核验表行号（0.1/0.5/0.6/0.8）与前章（2.6/2.11-B、3.3/3.6、4.4/4.5、5.5）。
- 估算值·置信度低（已标注）：铁路投资占 GDP 5.7–7%（估算）、散户损失 £230m（估）、电信行业 $2 万亿市值损耗（TIA 转述，Low–Med）、电信"信用损失/总投资"聚合比例（**缺权威，未采用**）、6.3-⑥ 现货出清机制细节（Low）、6.3-⑦ 跨期信用敞口对比（方向性，Low）。
- 置信度标签随数字走，全章无脱标签硬数。

**③ 辩证修正记录（"本轮不同之处"裁定）**
- 7 项候选逐一【验证→但相同→净裁定】：采用 ①③④（含⑤工具维度）四类为"本轮不同"；② 限定供给侧；⑥ 裁定为"相同偏强"；⑦ Low 不采用为硬论断。每个"不同"均已配"但相同"反证，无偏废。
- **结论取向**：本轮与历史周期在结构骨架（顶层出资<控制资产、需求斜率定偿付、账面/现金流脱钩）上**同构**，"不同"是尺度与速度的极端化，非机制更替。

---

**执行状态**：第 6 章（四镜六维结构对照矩阵）完稿。历史数据全部联网核验（铁路/电信镜登记 `0.9`，只增不改）；Insull 继承 3.6、dark fiber 继承 5.5；"本轮不同之处"按宪法辩证法——先列候选、逐点验证、每个"不同"配"相同"反证——收敛为四类真差异；无新断裂预测、无三情景。按"一次一转纪律"，本章至此结束，不续写下一章。

---

# 第 7 章 · 三才推演：天地棋局与弈者之根（第一段：知人 · 知地 · 观势）

> 章内声明（先于一切推演）：
> **① 三节结构锁死**：知人→知地→观势，顺序不可乱——循"人乘地、地驱势、势驱人"之理。每节口诀为节 spine；无锚点的判断一律标注"**推演·低置信**"。
> **② 锚点纪律**：每个判断回溯前文章节锚点（章号+节号/核验表行号）；置信度标签随数字走（宪法 0.7-①，禁止脱标签引用）。
> **③ 边界纪律**：情景判断一律条件句；**不写三情景**（本章收束段职责，另行撰写）；**不产生新断裂点**（第 5 章已封笔）——观势节的"破土之处"只许引用第 5 章已封笔的触发条件与 0.3 监测哨。
> **④ 口径纪律**：债务分拆前置（宪法 0.7-④，三类发行人禁止混算）；多主体聚合口径防复发（0.7-⑤，凡聚合数标注主体清单）；矩阵引用纪律（0.7-③，13%/73% 为反向叠加组合，主陈述只用同向带 26—36%）。
> **⑤ 义务消化**：附录 A-A2（OpenAI 撬动倍数对称计算）在本章 7.1-② 执行；对抗性预注册《本轮周期为何不会破裂》（置于第 6 章后、本章前，已冻结）之【脆弱性申报】三项的逐点回应属**收束段职责**，本段只在触及对应结论（`4.5`/`2.3`/`3.3`）处标注关联，不提前裁决。
> **⑥ 时间戳**：执行日 2026-09-07，基线与主报告快照一致。

## 7.0 方法注记：三才框架与前六章的关系

三才推演术的总纲：**天地为局，人势为子。观所必然，循"人乘地、地驱势、势驱人"之理，以无私见天地。** 其通用四步法为"明地→知人→观势→造局"；本报告不按该顺序，原因结构性而非偏好性：**第 1—6 章已完成"明地"的全部测绘**——第 1 章闭环地图、第 2 章缺口算术、第 3 章会计裂缝、第 4 章信用图谱、第 5 章骨牌序列、第 6 章历史结构镜。本章的增量不是再描一遍地，而是把散布于六章的"**人**"（谁、惧什么、走哪条路）显式化，再以人观地（谁被哪块地锁死）、以地观势（哪块地正在变）、以根定终（谁的根先断）。故本章顺序为：**知人→知地→观势**，"造局"（裁决）职责由收束段三情景承担。

**八类节点→六立场的归并声明（口径显式化，宪法 0.7-⑤）**：第 1 章 1.1 表的八类节点中，"**项目 SPV/表外结构**"并入本方 ⑤ 债权市场（SPV 是债权的载体而非独立弈者——Stargate 38B 银团、密歇根 16B、新墨西哥 18B、Oracle SPV 34B，`0.5-1`，其"不可不守"＝透明度最低，即债权人的信息劣势本身）；"**电力/地理约束**"（台积电/HBM/电网）归入 7.2 知地节（它是地，不是弈者）。余下六类即本章六立场：**① Nvidia（半导体商之标本，AMD/Broadcom 为分流变量）② OpenAI（模型实验室之最高承诺者）③ 超大规模云厂商（微软/谷歌/亚马逊/Meta）④ 算力租赁商（Oracle/CoreWeave/Nebius——Oracle 多角色声明见该节）⑤ 债权市场（沉睡的抵押权人）⑥ 主权买家（X 变量）**。

**本章产品**：结构认知地图——回答"局是什么形状、谁被什么锁住、势往哪里流、绞杀点在哪张合同的哪条条款上"；**不回答**"三情景各自何时兑现、综合烈度几何"（收束段职责）。历史镜在本章的用法遵 6.4 边界：先问信号在哪一维、历史上该维的典型结局路径，不直接指向情景。

---

## 7.1 知人：三利定其趋择，立场定其轨辙

> 节 spine：**三利定其趋择，立场定其轨辙。** 三利者：求存之利（惧什么＝行为底线）、求存义之利（愿什么＝牺牲标准）、求贪欲之利（欲什么＝行为变数）；愿欲重合者行为可预测，分裂处即博弈破绽。立场者：决策权限 × 资源禀赋 × 信息视野。每方四行：三利 → 立场轨道 → 不可不守之处（弈者之根的微观基础，回溯 1.1 表）→ 数据锚。

### 7.1-① Nvidia（半导体商 · 全网唯一净现金流巨头）

- **三利**：
  - **惧（行为底线）**：客户集中度即命门（`1.5`）。FY2026 数据中心收入 **1937 亿美元（+68%）**（`0.1-B16`，High）的斜率依赖少数大客户（OpenAI/Anthropic/xAI/云商）持续采购——若集体收缩，收入斜率立断。故其一切行为以"**绑定客户、防流失**"为底线。
  - **愿（牺牲标准）**：芯片定价权 + 数据中心收入增速（`1.1` 表）。愿意为之牺牲的是**账面现金**：对买方股权投资约 **500 亿美元**（OpenAI 300 + Anthropic 100 + xAI 100，`2.4-1`），只要回收期可接受——毛利口径 **0.6—1.8 年**、现金流口径 **1.0—3.7 年**（`2.4-1`，前提"承诺全额兑现"）。
  - **欲（行为变数）**：维持"全网唯一超额净现金流节点＝实际背书人"地位（`1.5`）。2026 年的变数已显形：**$100B 资产负债表投入框架于 2026-01 搁置**（`0.5-2`），转为 **$30B 股权 + PORTS-Pike 隐性信用担保**（担保额未公开，`0.6-9`、`1.6-2`）——背书方式从"出钱"转为"**出信用**"。担保是或有负债，不出现在任何承诺簿上：这是**信息视野全网最优者**（唯一能看见所有客户订单流的弈者）的合理选择。
- **立场轨道**：决策权限＝账面现金溢出（全网唯一）；资源禀赋＝定价权 + 数据中心毛利率约 70—75%（`2.4-1`，Medium-High）；信息视野＝全客户订单流（最优）。轨道允许它走"**小股权 + 高密度采购 + 信用担保**"的轻资产背书路线；轨道不允许它走"包销兜底"路线——10-Q 风险提示"no assurance that we will enter into definitive agreements"（`0.5-2`）。
- **不可不守之处**：**芯片定价权 + 数据中心收入增速**（`1.1`）。微观基础：若下一代定价权松动（AMD 6GW、Broadcom 10GW 分流，`0.1-B5/B7`），`2.4-1` 的"份额 ÷2"敏感性即兑现（回收期升至 2—7 年）；双杀（兑现率 ÷2 且份额 ÷2）时回收期 **4—15 年+** 且收入基数本身下修——`1.5` 共振器的量化入口。
- **数据锚**：`1.1`、`1.5`、`1.6-2`、`2.4-1`、`0.1-B16`、`0.5-2`、`0.6-9`。

### 7.1-② OpenAI（模型实验室 · 最高承诺者）——含附录 A-A2 对称计算

- **三利**：
  - **惧（行为底线）**：**融资叙事不可间断**（`1.1`）。覆盖比 **0.43—0.53 倍**（`2.4-2`：A 口径 400÷750=0.53 / B 口径 320÷750=0.43）意味着当期 ARR 不足以覆盖最保守承诺年化 750 亿（`0.1-B8`）——叙事连续性是偿付的先行指标；微软分成漏斗（约 20% 分成、至 2030 上限 380 亿，`0.5-4`）进一步压低净可支配（B=320 亿）。
  - **愿（牺牲标准）**：收入斜率追上承诺交付——ARR 400 亿美元、企业收入已超消费者（`0.5-4`，High），近一年 **+200%**（130.7→400 亿）。
  - **欲（行为变数）**：**承诺簿本身即信用资产**——以 0.60—1.40 万亿承诺簿（`0.1-B8` 三口径）撬动生态投资与基础设施；Series I 1100 亿的出资方（Amazon/Nvidia/SoftBank）本身就是其供应商/生态方（`0.6-4`）——它不只融钱，它把供应链变成股东名单。
- **立场轨道**：决策权限＝"史上最烧钱的信用实体"（`1.1`）；资源禀赋＝叙事 + 模型能力；信息视野＝自身 ARR 与承诺簿可见，但对生态方的**反向依赖不可见**（它的供应商就是它的股东——单一事件同时打击其供给与融资两端）。
- **不可不守之处**：**融资叙事不可间断**（`1.1`）。
- **【附录 A-A2 对称计算：OpenAI 撬动倍数】**（公式承 `2.4-2`：撬动倍数 ≡ 采购承诺总额 ÷ 买方实付股权；口径按附录 A-A2 裁定执行）
  - **【算式】** `撬动倍数 = OpenAI 单独承诺簿 ÷ OpenAI 累计股权融资额`。
  - **【输入】** 分子（三档，`0.1-B8`，Medium；**OpenAI 单独口径，不采用混入 Anthropic 的 C 合计 0.93—1.73 万亿**——宪法 0.7-⑤）：2026 调整口径 6000—7500 亿／第三方拆分约 1.15 万亿／官方原始约 1.4 万亿。其中**已签约绑定义务子集**（A-2 口径子集锁定，禁止混入框架意向）＝ Azure 2500 亿（`0.1-B8` 微软行，High，2025-10-28 重组协议）+ AWS 1380 亿（`0.6-3`，High）≈ **3880 亿**（Oracle 3000 亿为 Low 未坐实，不计入，`0.2-3`）。分母＝OpenAI 累计股权融资额：核验表已登记锚点仅 **Series I 1100 亿**（`0.6-4`，Medium，pre-7300 亿/post-8400 亿）；更早轮次（2025-10 SoftBank 牵头轮等）**未入核验表——缺数声明**，按公开报道口径估算累计约 **1800—2000 亿**（估算·低，A-2 预期 Low：多轮融资条款未必全公开）。
  - **【演算】** 三档配对（防摘樱桃，全部列示）：
    - 全簿口径：0.60—1.40 万亿 ÷ 1800—2000 亿 ≈ **3.0—7.8 倍**（累计估算分母）；
    - 全簿 ÷ 已核验单轮 1100 亿 = **5.5—12.7 倍**（下界分母口径，因分母缺数而系统性偏高，只作边界）；
    - **已签约子集（最严配对）**：3880 亿 ÷ 1800—2000 亿 ≈ **1.9—2.2 倍**；÷1100 亿 = 3.5 倍。
  - **【推导表（补交 · 申报区修正）】** 上一会话申报"撬动 1.9—12.7 倍"**不可复算作统一区间**：其下界 1.9 取"已签约子集 ÷ 累计估算分母"、上界 12.7 取"全簿 ÷ 单轮分母"，**踩跨两个不同口径的配对**，单一口径内到不了该区间。按"申报区须单一口径可复算"裁定，**主申报区修正为 3.0—7.8 倍**（全簿 ÷ 累计估算 1800—2000 亿）；1.9 与 12.7 降级为两个边界口径的最严/最松读数，不作主申报。

    | 配对 | 分子（口径·行号） | 分子区间 | 分母（口径·行号） | 分母区间 | 倍数 | 性质 |
    |---|---|---|---|---|---|---|
    | P1 全簿÷累计估算 | 全簿三档（`0.1-B8`，Medium） | 0.60—1.40 万亿 | 累计股权融资估算（估算·低） | 1800—2000 亿 | **3.0—7.8** | **主申报区** |
    | P2 全簿÷单轮 | 全簿三档（`0.1-B8`） | 0.60—1.40 万亿 | 已核验 Series I（`0.6-4`，Medium） | 1100 亿 | 5.5—12.7 | 分母系统性偏小→边界偏高，不作主申报 |
    | P3 已签约子集÷累计估算 | Azure 2500 亿(`0.1-B8`微软行,High)+AWS 1380 亿(`0.6-3`,High) | 3880 亿 | 累计估算 | 1800—2000 亿 | 1.9—2.2 | 最严配对（刚性义务/最大分母） |
    | P4 已签约子集÷单轮 | 同上 | 3880 亿 | Series I | 1100 亿 | 3.5 | 边界 |

    > 分母说明：**1100 亿**＝已入核验表的单一锚点 Series I（`0.6-4`，pre-7300 亿/post-8400 亿，Medium）；**1800—2000 亿**＝含 2025-10 SoftBank 牵头轮等更早轮次的**累计估算**（估算·低，`0.2-3` 口径——分母缺数声明，多轮融资条款未必全公开，A-2 预期 Low）。两分母一「已核验单轮」一「累计估算」，**不可互换**：P2 用单轮分母系统性抬高倍数，仅作边界。分子均＝OpenAI 单独口径，**禁止混入 Anthropic 的 C 合计 0.93—1.73 万亿**（宪法 `0.7-⑤`）。
  - **【对照与判读：两种杠杆化路径，禁止单变量病理化】** Anthropic 撬动 **4.1—11 倍**（3300 亿承诺 ÷ 300 亿实付股权，`2.4-2`）vs OpenAI **1.9—7.8 倍**（已签约子集到全簿）。二者结构不同：**Anthropic ＝股权捆绑型**——300 亿实付股权撬动 3300 亿**全部已签约**承诺（GCP 2000/AWS 1000/Azure 300，`0.6-1/2/7`），闭环最紧、杠杆全刚性，但覆盖比 **1.16**（ARR 650 亿＞年化承诺 560 亿，`2.4-2`）当期安全；**OpenAI ＝承诺驱动型**——承诺簿体量最大（0.60—1.40 万亿）但已签约子集撬动仅约 2 倍，杠杆大头在非刚性框架层（Oracle 3000 亿 Low），真正的紧张不在撬动倍数而在覆盖比 **0.43—0.53**（不足刚性承诺年化之半）。**两个变量交叉成四象限：Anthropic 站"高撬动×覆盖超1"象限，OpenAI 站"低刚性撬动×覆盖不足"象限——各脆弱在不同变量上。** 只引用 OpenAI 的 1.4 万亿承诺簿而不同时报覆盖比、或只引用 Anthropic 的 11 倍而不报 1.16，均属单变量病理化，禁止。
  - **【敏感性】** 分子上修（框架转合同，如 Oracle 坐实+3000 亿）：全簿上限 1.7 万亿，倍数升至 8.5—9.4；分母上修（新股权轮 500 亿）：倍数整体下修约 20%。方向：**OpenAI 的倍数是动数，随框架→合同的转化率与新一轮股权融资双动**。
- **数据锚**：`1.1`、`2.4-2`、`0.1-B8`、`0.5-4`、`0.6-3/4`、`0.2-3`、附录 A-A2。

### 7.1-③ 超大规模云厂商（微软 / 谷歌 / 亚马逊 / Meta）

- **三利**：
  - **惧（行为底线）**：**FCF 底线**。H1-2026 五大 Big Tech CapEx/经营现金流达 **96%**（2024 为 50%、2025 为 68%，`0.1-A6`，Medium）——"利润池内部的腾挪空间已耗尽"（`4.6`）；2025 合计 FCF 1913 亿 vs 长期债务 2024 末 1320 亿→2026-06 末 **3419 亿（+2099 亿）**（`0.1-A6`）。云定价权与 AI 叙事（`1.1`）是其市场之根，**FCF 是其行为之底**：AI 叙事受创而 capex 已沉没时，定价权无法对冲——故其底线兑现为 5.0 L3 不倒条件："AI 回报斜率仍超 capex 增速"。
  - **愿（牺牲标准）**：以股权簿记撬动云收入确认——"先投后卖"，把股权对价转成近乎绑定的采购（`1.5`）。四家样本：微软 27% OpenAI 股权 + Azure 2500 亿（`0.1-B8`）；Amazon 投 500 亿 + AWS 1380 亿/8 年（`0.6-3`）+ Anthropic 1000 亿/10 年（`0.6-2`）；Google 投 400 亿（100 亿现付）+ GCP 2000 亿/5 年（`0.6-1`）+ 租 xAI 9.2 亿/月（`0.6-6`）；Meta 至 2028 对美承诺超 6000 亿（`0.1-A4`，非单年度）。
  - **欲（行为变数）**：**多中心占位**——微软解除 OpenAI 排他（`0.6-12`）后，从"微软单点闭环"走向"放射状多闭环"（`1.6-1`）：每家都想成为闭环网络的中心节点而非通道。变数：Anthropic 成为"全网最大多向受投方"（微软+Google+Amazon+Nvidia 四面，`1.6-3`）正是四家竞相占位的产物。
- **立场轨道**：决策权限＝路径④内部可消化 2000—3000 亿/年（`2.9`）；资源禀赋＝投资级评级 + FCF 1913 亿（`0.1-A6`）；信息视野＝全栈三重可见（自家云收入 + 被投方采购 + 芯片采购）。
- **不可不守之处**：**云定价权 + 自家 AI 叙事**（`1.1`）。断裂形态回溯：本类几乎**不以债务违约断裂**，而以"削减 capex/回购/分红 → 砍掉路径④内部填塞"断裂（`4.3-A`），3—6 个月后传导为 (b)(c) 类收入/租约悬崖——**云商的根断不倒自己，先倒下游**。
- **【浮盈回吐敞口（强制内容）】**：Lee 请愿（`3.0-2`，petn4-903，2026-06-07 提交，High——请愿文件本身已核验）主张：ASU 2016-01 框架下，投资方（云商）持有 Anthropic/OpenAI 等被投方权益的**未实现估值浮盈计入其利润**，要求分拆披露"云收入与商业纠缠实体的未实现收益"，直接点名 cloud credit circuit 的股权-采购-收入关联链。**ASU 2016-01 适用性主张＝请愿人主张·待核**（主报告仅核验请愿存在与请愿事项本身，未对该会计准则适用性作 EDGAR 独立核验）。若主张属实，含义：云商当期利润中含被投方估值浮盈——**触发条件（请愿人主张·待核）＝头部 AI 公司融资轮持平或下调**：估值下修 → 浮盈转回吐 → 利润端二次传导。关联监测：0.3 哨"OpenAI/Anthropic 估值条款下修"已在哨上，但该哨监测的是**融资端**；浮盈通道是**利润表端**的第二传导，当前哨外。
- **数据锚**：`1.1`、`1.5`、`1.6-1/3`、`2.9`、`4.3-A`、`4.6`、`0.1-A4/A6`、`0.6-1/2/3/6/12`、`3.0-2`。

### 7.1-④ 算力租赁商（Oracle / CoreWeave / Nebius）

> **Oracle 多角色声明（宪法 0.7-⑤ 口径纪律）**：主报告 `1.1` 将 Oracle 列于超大规模云，`4.3-B` 将其项目 SPV（34B，Low）列于 (b) 类，本节按其 **OCI 算力租赁业务角色**（Stargate 租户 + 3000 亿承诺 Low 未坐实，`0.2-3`）归入算力租赁商——同一主体三重身份（云商/租户/SPV 融资主体，`1.6-5`："加杠杆表观与经营回报的拉锯"），任何单角色口径都会错置其杠杆位置。凡引用 Oracle 数字处须注明角色。

- **三利**：
  - **惧（行为底线）**：**租约续签率 + 再融资通道**（`1.1`）。(c) 类断裂条件：**有效租金 < 当期偿债额**（`4.3-C`）；H100 一年期长约跌破 **$1.8/h** 会计含运营成本线即会计口径转亏（`5.1` 触发条件，估算·低）——当前长约 $2.10—2.70（`0.5-3`，High），条件触发、未触发。
  - **愿（牺牲标准）**：**长协锁价 ≥ 会计线**（`5.1` 不倒条件 (i)）——主力客户以高于 $1.8/h 长约续租且利用小时达标，则收入底可用。
  - **欲（行为变数）**：**GPU+合同现金流双抵押的扩张**（Nebius 模式，`0.6-8`）——把未来租金提前抵押换当下扩张。变数：CoreWeave 已获**首个投资级 GPU-backed 融资**（DDTL 4.0，SOFR+2.25%、固定约 5.9%，`0.1-C6`，Medium）——欲的顶点是让抵押品被评级体系接纳。
- **立场轨道**：决策权限最小、资源禀赋最薄（杠杆最高：CoreWeave 总债务超 325 亿，`0.1-C5`，Medium；期限最短：DDTL 典型 3—5 年，`4.3-C`）、信息视野窄（自家租约可见、全市场租金曲线不可控——租金是外生变量）。**第一张骨牌候选**（`4.3-C`）。
- **不可不守之处**：**租约续签率 + 再融资通道**（`1.1`）。个体差异：xAI 比本类多一道母公司信用垫（SpaceX/Nvidia 生态，`0.6-5`）；Nebius 有微软合同 194 亿/5 年的"外生信用"缓冲（`5.1` 不倒条件 (ii)）；CoreWeave 的投资级评级当前说明再融资通道通畅——**通畅是状态不是结构**，通道由债权人立场决定（见 7.1-⑤）。
- **数据锚**：`1.1`、`1.6-5`、`4.3-B/C`、`5.1`、`0.1-C5/C6`、`0.6-5/8`、`3.0-6`、`0.2-3`。

### 7.1-⑤ 债权市场（沉睡的抵押权人）

- **三利**：
  - **惧（行为底线）**：**抵押品回收率 < 放贷假设**。其惧不在违约本身（可处置抵押物），而在 `4.4` 的算术：单卡账面 $25,000（估算·低）的可贷值仅 **16%—85% 区间**——理性贷方应按"技术寿命 × 租金现金流"而非"账面 × 数量"校准 LTV；若按账面放贷，回收率预期严重高估。
  - **愿（牺牲标准）**：**利差与条款维持现状**——当前读数：SOFR+2.25%、零风险溢价（`0.1-C6`，Medium）——信用市场当前并不认为快钟在滴滴答答地走（`5.2` 自证）。
  - **欲（行为变数）**：**高收益私募信贷扩张**——科技私募借款约 4500 亿（2025 初，同比 +1000 亿）、约 1250 亿流入项目融资、AI 相关占比由 17% 升至 33%（UBS 口径，`0.1-C8`，Low——付费墙未全捕获）。
- **立场轨道**：决策权限＝分散（银团/私募/公开债三市并行）；资源禀赋＝流动性供给本身；信息视野＝**全网最劣**——表外 SPV 透明度最低（`1.1`），私募信贷合同条款不公开（`4.4` 三条件 (i)"部分满足"正因 DDTL 条款未全披露）。
- **不可不守之处**：**抵押品回收率底线**（`1.1`"只收利息 → 要求重构的态度拐点"的量化形态）。
- **【觉醒的观测指标（强制内容）】**（回溯 0.3 监测哨与第 4—5 章）：**①利差**（SOFR+利差走阔）**②条款**（如 CoreWeave DDTL 类合同收紧）**③展期要求**——"利差走阔 + 条款收紧 ＝ 债权人觉醒信号"（`0.3`）。**秒针＝私募信贷合同条款：重估频率（抵押重估季频，`5.2-③`）／LTV 触发线（`4.4` 三条件 (i)）／补仓宽限期（未见披露）——秒针在合同里，不在市场上；公开市场看见它时，秒针已走完。**
- **债务分拆前置（宪法 0.7-④，禁止混算）**：(a) 类表内 3419 亿（投资级、久期 7—10 年）；(b) 类 SPV 约 106B（无追索、7—10 年分期，Low–Medium）；(c) 类数百亿级（DDTL 3—5 年，最短）。**63—75% 债项 2028 年后到期**（`5.2` 先决：墙内到期仅 840—1260 亿，估算·低）；但**"短档保留快钟"**（`5.6-②`）——快钟本源（抵押品市值重估触发 LTV）不由期限决定，由 40—60% 短档内的抵押条款承担。
- **数据锚**：`1.1`、`0.3`、`4.4`、`5.2`、`5.6`、`0.1-C5/C6/C8`、`0.5-1`。

### 7.1-⑥ 主权买家（X 变量）

- **三利**：
  - **惧（行为底线）**：主报告定位其"不按偿付逻辑出牌"（`1.1`）——但"不按偿付逻辑"不等于无所惧。**推演·低置信**（主报告未给主权之惧的锚，此处为结构推断）：其惧＝技术主权受制于人——撤单的触发不是价格而是地缘。
  - **愿（牺牲标准）**：算力主权 + 本地产业（法国 1090 亿欧元/至 2030、沙特 60 万卡、UAE Stargate 等，`2.10`，Medium-Low）。
  - **欲（行为变数）**：石油美元换算力主权的战略置换（`2.10` 结构性注记）——既能填塞缺口，也可能因地缘/财政一夜撤单。
- **立场轨道**：决策权限＝国家资本（决策过程不透明）；资源禀赋＝外储/主权基金；信息视野＝谈判桌内、市场外——商业数据看不见它的预算表。
- **不可不守之处**：`1.1` 表未定义主权之根（其角色是 X 变量）——**推演·低置信**：战略自主不可逆让。操作含义：**其贡献不可用商业模型外推，只能监测**（`2.10` 结构性注记 + 0.3 哨"新增大额交易"）。
- **量级锚**：当期 **320—450 亿美元/年、占缺口约 5.9%**（`2.10`）；远期条件情景 2028—2030 年化 500—1000 亿（兑现率 50—100% 内生区间，`2.10`）；Nvidia 主权 AI FY2026 约 300 亿（`2.0-6`，Medium）。
- **数据锚**：`1.1`、`2.10`、`2.0-6`、`0.3`。

### 7.1-C 知人收敛：愿欲分裂度与利益网络

| 立场 | 愿（声明） | 欲（变数） | 愿欲分裂度 | 破绽位置 |
|---|---|---|---|---|
| Nvidia | 绑定客户（500 亿股权） | 轻资产信用背书（PORTS-Pike 担保） | **中**——"欲"已显形为担保，仍是表外或有 | 担保额未公开（`1.6-2`） |
| OpenAI | ARR 斜率追上交付（覆盖比→1） | 承诺簿扩张（0.60—1.40 万亿） | **高**——愿与欲方向相反（覆盖比 0.43—0.53 vs 簿还在长） | `2.4-2` |
| 超大规模云 | AI 回报斜率超 capex | 多中心占位（排他解除后） | **中**——占位竞争推高自身 capex/OCF 至 96% | `0.1-A6` |
| 算力租赁商 | 长协锁价 ≥ $1.8/h | 双抵押扩张 | **高**——欲的扩张恰放大惧的敞口（未来租金提前抵押） | `0.6-8`、`4.3-C` |
| 债权市场 | 利差与条款维持现状 | 私募份额扩张（17%→33%） | **高**——扩张建立在"快钟未走"的定价之上 | `0.1-C8`、`4.4` |
| 主权买家 | 算力主权 | 不可测 | **不可测** | 只监测不外推（`2.10`） |

**利益网络判读**：扩张期受益方联盟（Nvidia—OpenAI—云商—租赁商四方同向：每方的收入/承诺都是他方的支出/资产）与**受损方潜伏层**（债权人 + 被动指数持有人——后者无合同、无立场、无退出选项，是共振器 `1.5` 的终端承载，观势节 7.3-A 展开）。**愿欲分裂最严重处＝博弈破绽**：OpenAI（承诺簿与覆盖比反向）与债权市场（份额扩张与抵押品快钟并存）——两处破绵恰好在 7.3-B 的蓄势之池中交汇为势能，此即"人因其势而显性"。

---

## 7.2 知地：版图定其根基，制度定其结构，器物定其变迁

> 节 spine：**版图定其根基，制度定其结构，器物定其变迁。** 地之三格：版图最难速变（以年计），制度可速变于革命（以一纸规则计），器物可积累可消耗（以代计）。三格失衡处即破局点。

### 7.2-A 版图（最难速变的一格）

- **台积电产能地理**：主报告 `1.1` 表将其列为"电力/地理约束"节点之一，但**无产能地理的数字锚（缺数声明）**——本节只作结构陈述：先进制程产能地理高度集中，是芯片流 `[芯]` 的物理咽喉（**推演·低置信**，常识性结构；量化须后续核验，不入主演算）。
- **HBM 寡头（版图上最硬的一格）**：现货 36GB HBM3E $2100 ＝长协价（$350—500）的 **4—5 倍**（`0.8-1`，Medium）——现货与长协背离至历史极值；HBM4 对 Nvidia 约 **$31—32/GB**、近 HBM3E 两倍（`0.8-2`，Medium，分析师估算）；SK hynix 董事会批准 **54 万亿韩元**一揽子投资（Yongin Y2 2029 投产）、**三星 70% 产能已被锁至 2031**（`0.8-3`，Medium）。寡头格局 + 供给刚性 + 长约锁定三重叠加：**HBM 是全链条最前端的领先指标**（`0.3` 哨）。
- **电网与土地（部署速率的真实限制器）**：美国并网队列约 2600 GW、ERCOT 大型负荷队列 2026-04 约 410 GW（超 2025 末 233，`0.1-C15`，Low——二手汇总未核验 FERC/ERCOT 原始报告，作观测哨可、作硬结论不可）；佐治亚 PPA 原型：Georgia Power 向 OpenAI Effingham 数据中心供 3.2GW 合同**显式预留终止/重谈路径**且不向其他 ratepayer 转嫁缺口（`0.8-4`，Medium）；**Microsoft vs PowerHouse Hillwood** 供电协议 FERC 之争（2026-08-21 文件）——大厂与电力开发商重谈的实证（`0.8-5`，Medium）。
- **版图判读（双向性）**：**算力只能落在电力允许的地方**——版图既是扩张的物理天花板（`2.3` 敏感性末条：分母 ÷2"电力约束硬顶"情景的成因），也是收缩期的减速垫（企业 PPA 解约费＝剩余年数 × 合约量 × 单价 × 50—100%，**重谈/降负荷优先于解约付罚**，`0.8-6`，Medium）。地的刚性对两个方向都不豁免。

### 7.2-B 制度（可速变于革命的一格）

- **出口管制**：主报告无专门锚（**缺数**）——结构陈述：芯片流的地缘约束是版图与制度的叠层（**推演·低置信**）。
- **反垄断对循环交易的容忍度**：FTC 6(b) 报告（`3.0-4`，High）正式研究云商-AI 开发者合作、披露 Google-Anthropic $100 亿 cloud credits——性质是**竞争研究/背景材料，不是执法**（`3.5-A`）；截至执行日，做空机构未发布针对 hyperscaler 折旧或 AI 收入循环的正式做空报告（`3.0-7`，High）。
- **会计准则（本轮制度格的核心存量规则）**：MSFT FY2023 起服务器 4→6 年（当年运营收入影响约 +37 亿）、Google 2023-01 同延 6 年（−39 亿折旧）（`0.1-C1`，High）；CoreWeave 6 年 / Nebius 4 年 / Lambda 约 5 年（`0.1-C3`，High）；技术寿命 2—3 年 vs 会计 5—6 年（`0.1-C14`，Medium）。
- **IPO 窗口**：Anthropic IPO 分析已提示 cloud-reseller 总额法列报与 principal-vs-agent 讨论（`3.4-A`，Low——第三方 IPO 分析，非已核验 SEC 问询）——IPO 窗口是把"总额法/净额法"从学术讨论变成监管问询的通道。
- **全球最低税**：主报告无锚（**缺数**）。
- **【最高权重项：SEC 对两项 Rule 192 请愿的处置】**（`3.0-2`/`3.0-3`，High——请愿文件本身已核验 PDF 有效）：
  - **口径澄清（执行指令与登记行号的对齐）**：两项请愿登记于主报告第 3 章锚点表 **`3.0-2`/`3.0-3`**（核验表《00-核验表.md》无 0.10 子表——指令中"核验表 0.10"即此两行）。petn4-903（2026-06-07，**Hera H. Lee** 提交）：要求分拆披露"云收入与**商业纠缠实体的未实现收益**"，直接点名 cloud credit circuit 的股权-采购-收入关联链；petn4-910（2026-07-07，Raymond Gillis 提交）：要求披露 AI 算力资产**老化（vintage）、折旧与寿命敏感性、利用率、退役/减值、经济收益率**并调和至 GAAP 分部。两者均依据《SEC Rules of Practice》Rule 192（17 CFR § 201.192，规则制定请愿程序），**非** Reg S-P 数据保护 Rule 192（17 CFR § 248.192）——两个不同法典下的"192"，勿混淆（`3.0-2` 编号澄清）。
  - **二元事件判读（条件句）**：请愿 ≠ 规则 ≠ 执法（`3.5-A` 纪律）。但**若**关联方云收入拆分被采纳为规则，`2.4-1` 第 3 步那组 **20%—62%**（Nvidia 投资伙伴贡献收入占比，Low，区间过宽正因公开数据不可拆分）将从估算变成**强制披露数据**——第 3 章全部"账面收入→净可支配"折扣（`3.4-C`）获得硬数据，**会计裂缝重定价加速**；若 petn4-910 同时采纳，算力资产 vintage/利用率披露将直接检验 `3.3` 的交叉点估算。反之若两项均否决/搁置，制度压力停留在"前哨"位，裂缝延续账面计价。
  - **为何是最高权重**：**制度格是三格中唯一可在单一行政动作内速变的格**（版图以年计、器物以代计、制度以一纸规则计）；且其方向与历史镜相反——PUHCA 1935 是"崩后立法"，当代请愿/FTC 研究出现在"崩前窗口"（`3.6` 监管距离维、`6.3` 监管框架前置度）。制度变迁方向＝收紧，时点不可测——这是收束段情景分支的独立变量之一。

### 7.2-C 器物（可积累可消耗的一格）

- **芯片迭代 2—3 年 vs 会计折旧 5—6 年的裂缝**（`3.1`/`3.2`/`3.3`）：技术有效寿命由器物决定，账面寿命由制度决定——**两者错配是第 3 章全部传导链的物理基础**：现金流恶化的信号被利润表掩盖（环 1）、减记延后制造"账面资产仍在运转"幻觉（环 2）、EBITDA 注水放大偿付假象（环 3）。
- **算力现货已按边际成本定价（刀刃发现）**：H100 现货 $2.79—2.82 几乎零波动、低位企稳（`0.5-3`，High）；技术口径含运营成本线约 $3/h 已与长约下沿交叉（`3.3`）——现货端接近边际成本定价。`6.3-⑥` 已裁定此点"**相同偏强**"（dark fiber 先于本轮到达边际成本坍缩态）——器物格的这一属性是周期性常态而非本轮独有，作结构背景、不作方向证据。
- **器变则地利重分**：B200 长约综合 $3.68 vs H100 $2.10—2.70（`0.5-3`，High）——**新一代承价、旧代承贬**（`6.3-④` 镜像：HBM 现货背离 4—5 倍同理，`0.8-1`）。快钟的物理来源＝器物迭代节奏（半年一代）；其在信用层的兑现路径＝`4.4` 三条件（LTV 条款/贷方无展期/无兜底）。
- **器物格的寿命方向分化**：GPU 存量是**可消耗**的器物（技术贬值 30—50%/年，`4.4`）；电力基础设施与 HBM 产能是**可积累**的器物（版图化沉淀，`0.8-3`）——同属器物，寿命方向相反；收缩期前者加速清算、后者折价再配置（`5.5` 遗产维）。

### 7.2-D 三格交叉判断（强制：何格强、何格弱、何格在变）

| 格 | 强度 | 状态 | 对弈者的锁定 |
|---|---|---|---|
| **版图** | **最强** | 稳（HBM 锁至 2031 + 电力物理约束） | 锁死所有扩张路径的速率上限——扩张与收缩都被它托底或封顶 |
| **器物** | 中 | **正在变**（半年一代迭代 vs 制度 5—6 年折旧的错配在扩大——B200/H100 价差即错配的市场读数） | 快钟之根：器物节奏对制度节奏的碾压 |
| **制度** | **最弱** | 变量最大（请愿两件在途 + FTC 研究 + Nebius ICFR 已现，三重前哨，但零执法） | 唯一可被单一事件速变的格；也是唯一可主动补位的格 |

**三格失衡处＝破局点：器物（2—3 年迭代）与制度（5—6 年折旧 + 披露不强制）的错配。** 这正是第 3 章裂缝与 `4.4` 快钟的"地"之根源——快钟不是任何弈者的选择，是器物节奏对制度节奏的碾压。SEC 请愿若采纳，恰是把制度格拉齐器物格的动作：**制度补位则账面与清算价值收敛（快钟减速）；制度不补则错配继续扩大（快钟继续走）**。故本章将请愿处置列为制度格最高权重项——它同时是裂缝的封口与开裂两读的开关。

---

## 7.3 观势：水之就下定其向，弩之机牙定其时，弈者之根定其终

> 节 spine：**水之就下定其向，弩之机牙定其时，弈者之根定其终。** 判读顺序强制：先识水（不可逆大势）→ 再寻机牙（临界触发）→ 终察根（终盘绞杀处）。不问英雄问黎庶。

### 7.3-A 水之就下（不问英雄问黎庶）

- **企业层之水：降本是"不用 AI 即死"的万川归海**。池子 W≈**27 万亿美元**（可触达知识工作工资池，`2.6-A`，Low 但美国锚 15.75 万亿独立交叉验证数量级，`2.0-7` High）；当期渗透率 p₀＝**0.137%**（企业 GenAI 支出 370 亿 ÷ 270000 亿，`2.6-B`，Medium-High）——**不足 0.4%，已化渗透空间 >99.6%**；组织兑现率 k≈2—5% 由支出侧（Menlo）与组织侧（NANDA 95% 试点未见回报）**两路独立实测交叉锁定**（`2.6-B`）；基准情景 k 爬至 10—35% → 路径①收入 **1600—5700 亿/年**（`2.6-C`）。不可逆性判据：成本驱动 → **高**（企业降本与生存绑定，不随政策/情绪逆转）。此水是 `6.3-①` 窄义采用的"真实降本锚"——锚已形式化，证在 k 的兑现。
- **黎庶层之水：闭环收益经被动指数基金机械流入 401(k)**。已核验锚：IMF GFSR 2025-10——AI/IT 相关股票估值集中度高企、**S&P500 集中度历史高位**；BIS 2025-12——M7 股价受 AI/数据中心盈利预期支撑但估值拉伸（`0.1-A5` BIS/IMF 行，High）。机制推演（**推演·低置信 + 请愿人主张·待核**）：被动指数按市值权重机械配置 → 集中度高位意味着普通退休储蓄者**无选择地持有本轮周期的资产负债表**——黎庶不是弈者，是水的河床：他们不决策、只承受。401(k) 具体通道未核验；Lee 请愿要求的"商业纠缠实体未实现收益"分拆披露（`3.0-2`），若采纳，将首次使该传导的规模可测（主张·待核）。
- **两层水的辩证分源**：企业层之水是**需求之水**（流向 AI 服务，真实不可逆）；黎庶层之水是**资金之水**（流向 AI 股权，结构性但非需求——它随市值机械收缩）。收缩期两层水表现将不同：前者以渗透率 0.14% 起步的斜率维持，后者是 `1.5` 共振器的终端放大器。**把两层水混为一谈，会把"资金之水的退潮"误读为"需求之水的枯竭"——反之亦然。**

### 7.3-B 弩之机牙（蓄势之池 × 破土之处 ＝ 时机）

- **蓄势之池（力量已积蓄、尚未释放）**：
  1. **承诺 vs 收入堰塞湖**（`2.3`）：缺口中心 **6550 亿/年**（区间 4450—8550）；供给侧 C 口径承诺年化 **1300—2300 亿** vs 当期 B 口径收入中心 1950 亿——"供给侧签约的承诺规模，恰好等于需求侧极限兑现才能支撑的收入规模"（`2.1-C`）：承诺方正是在按"悲观不发生、基准下段"下注（`2.11-B` 结论）。
  2. **GPU 抵押贬值势能**（`4.4`）：30—50%/年、折扣区间 16—85%——账面与清算价值已分道，只待条款触发（三条件 (i) 部分满足、(ii)(iii) 未见实证）。
  3. **FCF 收缩势能**（`0.1-A6`、`4.6`）：CapEx/OCF 96%、长债 +2099 亿、私募信贷约 1250 亿（Low）——边际资金已迁移信用层，304—405 亿/季的展续压力。
  4. **浮盈回吐敞口**（Lee 请愿主张·待核，`3.0-2`）：若 ASU 2016-01 浮盈主张属实，头部估值下修时云商利润端二次传导（触发＝头部 AI 公司融资轮持平或下调——请愿人主张·待核）。
- **破土之处（力量释放的出口——全部引用第 5 章已封笔的触发条件与 0.3 监测哨，本节不产生新断裂点）**：
  1. **capex 指引首次下修**（5.0 L3 触发：指引连续 2 季下修 / capex-OCF 反向收敛）；
  2. **头部估值下修轮**（0.3 哨：OpenAI/Anthropic 新一轮融资估值下修＝融资叙事连续性受创）；
  3. **算力债信用事件**（5.0 L1/L2：有效租金 < 当期偿债额 → 抵押贬值超 covenant → LTV 触发掏押）；
  4. **SEC 请愿处置**（`3.0-2`/`3.0-3`——制度格的速变通道，7.2-D）；
  5. **会计准则变化**（6 年折旧政策的制度侧封口或开裂，`3.1`/`3.5`）。
- **交汇点＝时机（条件语句，不作预测）**：每一池对应其最短破土路径——堰塞湖→出口①；抵押贬值势能→出口③；FCF 收缩→出口①或②；浮盈回吐→出口②。**单一出口打开时，蓄势之池决定其烈度；多出口同季打开时（如估值下修与请愿采纳同窗），池与池贯通——此即弩机牙扣动的形态。** 哪一季扣动、以何种组合扣动，本报告不预测：收束段以三情景处理时序与烈度（已登记输入：信用敞口中心 **1350—2180 亿/年（占缺口 1/4—1/3，峰值叠加收窄至 1/2—2/3）**，`4.5`；到期墙 **280—420 亿/年**，`5.6`）。
- **【配重铁律（强制，第 5 章已定，本章不得颠倒）】**：**主驱动＝快钟**（重估频率与条款触发，`4.4`/`5.2`——"短档保留快钟"，`5.6-②`：快钟本源由 40—60% 短档内抵押条款承担，不由期限决定）；**到期墙 280—420 亿/年仅为计时器与条件放大器**（`5.6-①`：仅 rollover failure 情形才升级为悬崖，Kindleberger 式单体展期失败→普遍信用收缩）。**操作纪律：不看到期日历，看抵押条款。**

### 7.3-C 弈者之根（终盘绞杀之处）

**四方不可不守之处的碰撞结构**（根的碰撞点＝未来战场）：

- **Nvidia 之根（芯片定价权+收入增速）× 债权人之根（抵押品回收率）——本轮最深的结构性根冲突**：Nvidia 的"欲"（推 B200 高价）恰是旧卡抵押贬值的**加速器**（`4.4` 机制：新一代蚕食旧卡租金 → 旧卡抵押价值年降 30—50% → LTV 自动上升）。**芯片商越成功，债权人的抵押品越缩水**——这不是行为选择，是立场结构的必然：供给端的根与信用端的根长在同一块器物上，方向相反。
- **OpenAI 之根（融资叙事不可间断）× 云商之根（FCF 底线）——条件性冲突**：OpenAI 覆盖比 0.43—0.53 需要持续股权填塞；云商 CapEx/OCF 96% 意味着填塞能力逼近上限。**若云商 FCF 先于 OpenAI ARR 达标而收缩**（断裂形态＝削减 capex、砍掉路径④内部填塞 2000—3000 亿，`4.3-A`/`2.9`），Series I 模式（投资方＝供应商，`0.6-4`）不可重复——OpenAI 的承诺簿失去股权填塞来源。
- **云商之根 × 债权人之根——沉睡共存**：云商表内 +2099 亿长债与私募信贷扩张依赖债权人继续沉睡；SEC 请愿若采纳（关联方披露 + 算力资产 vintage），债权人的信息视野从全网最劣被迫改善——**制度事件是唯一能批量唤醒沉睡者的开关**（7.2-D）。

**碰撞点在地图上的位置（哪些交易 / 哪类条款）**：

1. **"投资方＝供应商＝担保人"三位一体交易**——Series I 1100 亿（`0.6-4`：Amazon/Nvidia/SoftBank）、PORTS-Pike 担保（`0.6-9`）。根冲突的载体：一人分饰多角，**任何一方的根断裂即三方资产负债表同创**——这是 `1.5` 共振器"稠密边矩阵"中边密度最高的节点簇。
2. **GPU 抵押融资的 LTV 条款与重估机制**——CoreWeave DDTL（`0.1-C5/C6`）、Nebius GPU+合同现金流双抵押（`0.6-8`）、xAI SPV 125 亿 GPU 担保债（`0.1-C9`，Medium）。**Nvidia 根 × 债权人根的碰撞战场**；重估频率（季频，`5.2-③`）是秒针——秒针走一格，一次 LTV 重算。
3. **多年期算力长协的交付重谈条款**——Anthropic GCP 2000 亿/5 年（`0.6-1`）、OpenAI-AWS 1380 亿/8 年（`0.6-3`）。**OpenAI 根 × 云商根的碰撞战场**；PPA 合同经济学（重谈/降负荷优于解约付罚，`0.8-6`）是缓冲垫原型——算力长协同理可在交付期再订价，刚性交付是假设不是物理。

**根可共存处＝合作空间**：云商 FCF 与 OpenAI 叙事在"ARR 继续翻倍"下共存（覆盖比向 1 修复）；Nvidia 定价权与债权人抵押品在"迭代降速"下共存（5.0 L5 不倒条件：迭代降速→长尾再利用）；全部六方在"**收入斜率追上交付斜率**"（`2.11-C` 双斜率）下共存。**合作空间与冲突战场共用同一变量：斜率。斜率之上全是合作，斜率之下全是绞杀——这是本章对"势"的最终判读，也是收束段三情景的分岔轴。**

### 7.3-D 三才互参收敛（一句收束）

**人乘地**：六方立场由三格锁定（Nvidia 乘 HBM 版图之硬、债权人乘制度不透明之劣、租赁商乘器物快钟之险）；**地驱势**：器物—制度错配（快钟之根）驱动信用势能积蓄，制度格的速变性（SEC 请愿处置）是三格中唯一可被单一事件触动的格；**势驱人**：斜率（水之就下）决定根的共存或绞杀。三情景（硬着陆/基准/软着陆）的时序模拟与烈度参数、对抗性预注册【脆弱性申报】三项（`4.5` 敞口口径 / `2.3` R 值 / `3.3` 交叉点）的逐点回应——归收束段，另行撰写。

---

## 7.4 自我安放（己位监测）

三才推演要求观察者先摆自己的位——本章作为推演文本，其"私"须显式申报：

1. **本报告之"私"＝缺口命题的先在框架**。本报告的中心参数（B 口径收入 1450—2500 亿、capex 6950 亿—1.0 万亿）均为半主观口径（`2.1-A` 截留拆分主观、`0.1-A3` 非官方统一指引）——对抗性预注册已将 `2.3` R 值列为最脆弱结论之一（脆弱 #2）。本章凡引用 R 与缺口处，均**继承该脆弱性**，不因三才框架的完整性而豁免。
2. **信息源偏差＝付费墙盲区**。私募信贷余额未完全捕获（`0.1-C8`，Low）系统性低估分子侧债务——**己位盲区恰在信用层最深的部分**：看不见的债务越多，本章 7.1-⑤ 债权人立场的刻画越保守。凡"债权市场"条目结论，均带此下偏风险。
3. **观察者已入场**。两项 SEC 请愿的提交者之一为 Penn State 社会学博士生（`3.0-2`）——学术观察者已直接入场成为制度弈者。本报告同理：若被任何决策者采用，即从观察者转为弈者。推演的"无私"只能逼近，不能达成——此为方法论边界，非修辞。
4. **证伪路径（本章推演若错，最可能错在哪一环）**：
   - **若知人节错**：最可能错在三利之"欲"的推断（Nvidia 隐性信用背书动机、主权之惧）——均为行为反推而非访谈实证。反面信号：相关主体公开声明与推演行为相反（如 Nvidia 公开大规模包销兜底＝推翻"轻资产背书"判读）。
   - **若知地节错**：最可能错在制度格速变性——SEC 请愿被快速否决且无后续规则动作，则 7.2-D"制度补位开关"失效，快钟错配论需重估。
   - **若观势节错**：最可能错在配重——若无任何快钟条款触发、纯粹到期墙滚动失败率先引爆，则 `5.6` "快钟为主/到期墙为放大器"的配重被证伪（该排除基于短档 40—60% 估算·低，本就是全章最软的锚）。

---

## 7.5 本段自检清单（三项）

**① 全部判断的锚点回溯核对**
- 有锚判断：六立场三利/轨道/根（`1.1` 表 + `1.5`/`1.6`/`2.4`/`2.9`/`2.10`/`4.3`/`4.4`/`5.1`/`5.6`）；知地三格（`0.8-1~6`、`0.1-C1/C3/C14/C15`、`3.0-2/3/4/7`、`3.4-A`、`3.5`）；观势三向（`2.3`/`2.6`/`2.11`/`4.4`/`4.6`/`5.0`/`5.6`/`0.1-A5`）——凡数字均带核验表行号与置信度标签（0.7-①）。
- **"推演·低置信"清单（无锚声明）**：台积电产能地理结构（7.2-A）；出口管制、全球最低税（7.2-B，缺数）；主权买家之惧与根（7.1-⑥，1.1 表未定义）；401(k) 被动通道机制（7.3-A，仅集中度锚为 High）。
- **"请愿人主张·待核"清单**：ASU 2016-01 浮盈适用性、浮盈回吐触发条件（7.1-③/7.3-B，源 `3.0-2`——请愿文件本身 High、准则适用性未核）。
- **口径纠正执行**：指令中"核验表 0.10（两项 SEC 请愿）"已对齐为主报告 `3.0-2`/`3.0-3`（核验表无 0.10 子表）；"0.10-2 Lee 请愿"＝petn4-903。

**② 结构纪律与义务检查**
- 三节顺序锁死：知人→知地→观势 ✓（口诀为各节 spine，"造局"归收束段）；六立场四行结构（三利/轨道/根/数据锚）逐项完整 ✓。
- 附录 A-A2 已消化：OpenAI 撬动倍数对称计算落于 7.1-②，口径按裁定执行——分子 OpenAI 单独承诺簿 0.60—1.40 万亿（不采用混入 Anthropic 的 C 合计，0.7-⑤）；口径子集分列"已签约绑定义务 3880 亿"与"全簿"；分母缺数声明 + 估算·低；与 Anthropic 4.1—11 倍对照呈现为"股权捆绑型 vs 承诺驱动型"两种杠杆化路径，无单变量病理化 ✓。
- 宪法纪律：置信度标签随数字走（0.7-①）✓；矩阵引用只用同向带（0.7-③，未引 13%/73% 作主陈述）✓；债务分拆前置（0.7-④，7.1-⑤ 三类分列）✓；聚合口径防复发（0.7-⑤，Oracle 三重角色声明、SPV 归并声明）✓。
- 不越权两项：无三情景（仅登记收束段输入参数）✓；无新断裂点——7.3-B"破土之处"五项全部为第 5 章已封笔触发条件与 0.3 监测哨的引用，无新增 ✓。

**③ 置信度最低的三处（供人工重点抽查）**
1. **OpenAI 累计股权融资额 1800—2000 亿**（7.1-②，估算·低）——A-2 分母的核心缺数：核验表仅登记 Series I 1100 亿（`0.6-4`），此前轮次全靠公开报道拼接；撬动倍数三档结论（1.9—12.7 倍）对此敏感。
2. **主权买家三利推断**（7.1-⑥，推演·低置信）——主报告将其定位为 X 变量、未定义其根；本章"技术主权受制于人"之惧为结构推断，若主权行为可被商业逻辑解释（如按价撤单），该节需重写。
3. **浮盈回吐敞口全链**（7.1-③/7.3-B，请愿人主张·待核）——ASU 2016-01 适用性、云商利润中浮盈规模、401(k) 通道三层均未核验；唯一已核验的只有请愿文件存在与其请愿事项（`3.0-2`，High）。该敞口若被证实，7.3-B 蓄势之池新增一池；若被证伪，删池不伤其余结构。

---

**执行状态**：第 7 章**第一段**（7.0 方法注记、7.1 知人六立场含 A-A2 对称计算、7.2 知地三格、7.3 观势三向、7.4 自我安放、7.5 自检清单）完稿。**收束段（三情景时序模拟 + 烈度参数 + 对抗性预注册【脆弱性申报】三项逐点回应）待续，另行按指令撰写。** 按"一次一转纪律"，本段至此存档即停。

---

## 7.6 造局：三情景时序模拟与烈度参数（第二段）

> 章内声明（先于一切情景推演）：
> **① 造局职责承接**：第一段 7.0 已定位"造局（裁决）职责由收束段三情景承担"。本节即该裁决——但"裁决"指的是**把第一段的蓄势池、破土处、弈者根落成"在何种条件下走向何种烈度"的条件语句组合**，**不是**给出方向签名或概率签名（宪法 0.7-②：不赌方向）。
> **② 三情景与覆盖率端点的配对纪律（宪法 0.7-③ 矩阵引用，禁止摘樱桃）**：硬着陆 ↔ **13% 角**（收入下限 3200 亿 × capex 上限 24400 亿，`2.11-B`，**悲观叠加·反向组合·边界情景**）；软着陆 ↔ **73% 角**（收入上限 8900 亿 × capex 下限 12200 亿，`2.11-B`，**乐观叠加·反向组合·边界情景**）；慢消化 ↔ **26—36% 同向带**（`2.11-B`，基准叙事主参照）。**两个端点均标"反向叠加组合·边界情景"，不作任一主情景的概率分布；主口径陈述只用同向带 26—36%。** 任何情景单独摘取 13 或 73 作"该情景会兑现"即为违纪。
> **③ 烈度输入纪律（只引第 5 章已封笔的触发与不倒条件，不产生新断裂点）**：情景烈度参数一律取——信用敞口**占缺口 1/4—1/3（1350—2180 亿/年，峰值叠加收窄至 1/2—2/3）**（`4.5`/`5.6-③`）；抵押折扣**三分档 30/60/85%**（`4.4`/`5.2`，禁用 16—85% 全域）；**浮盈回吐（`3.0-2`，Lee 请愿，ASU 2016-01 主张·待核，7.1-③）与信用渠道为并联路径，禁止串联混算**（另见 7.6-0 口径澄清）。
> **④ 时序纪律（配重铁律，`5.6`）**：**主驱动＝快钟**（重估频率与条款触发，`4.4`/`5.2`、"短档保留快钟"`5.6-②`）；**到期墙 280—420 亿/年仅为计时器与条件放大器**（`5.6-①`，仅 rollover failure 情形升级为悬崖）。**空窗 2028—2032 本节所有时序均为 Low 时间置信标签**：结构结论（谁被锁、撞点在哪）与时间窗口（何时扣动）分开陈述，时间窗置信度单独降档。
> **⑤ 观测哨纪律**：每情景 ≥3 个指标，**现金流类哨兵先于 P&L 类**（租金属债、利差属债、FCF 属债——先看现金流与偿付，后看利润表）。
> **⑥ 判读手册**：预注册修订规则（`0.3`），裁决线用**重锚版**——R 中心**连续两季站上 0.3** 或 **B 口径 run-rate ≥5000 亿**（宪法 `0.7-②`；反方论证二亦引此线）。
> **⑦ 与反方对话（《本轮周期为何不会破裂》已冻结，本文只做逐点裁决，不改其文）**：每情景八要素之⑧明示本情景隐含接受/拒绝反方哪条论证及理由；对应反方【脆弱性申报】三结论（`4.5`/`2.3`/`3.3`）的逐点回应见 7.9。

### 7.6-0 口径澄清：指令"0.11（浮盈回吐并联路径）"与核验表子表对齐

执行指令要求"浮盈回吐并联路径（0.11）"。**核验表《00-核验表.md》原无 0.10/0.11 子表**（结构原仅 0.1、0.5、0.6、0.8、0.9），与第一段"核验表 0.10（两项 SEC 请愿）"同型——指令编号指向的实为主报告第 3 章锚点表中的登记。**对齐裁定：浮盈回吐并联路径即 `3.0-2`（Lee 请愿，petn4-903，要求分拆披露"云收入与商业纠缠实体的未实现收益"，ASU 2016-01 适用性＝请愿人主张·待核），其机制推演与触发条件已落于第一段 7.1-③ 与 7.3-B 蓄势之池第 4 项。本节不再另设"0.11"新编号**（浮盈机制已由 7.1-③/7.3-B 承载，另设会造成假锚）。**收尾阶段（2026-09-08）已新增 `0.10` EDGAR 财务数据核验子表**，登记三项浮盈/AWS 支出数据的 SEC 一手核验结果（`0.10-①/②/③`，详见核验表），供本节（四）烈度输入与第 8 章哨兵引用——该表为增量登记，未改任何既有行号。

### 7.6-① 硬着陆（配对角：13%·悲观叠加·边界情景）

**(一) 配对角声明**：对应 `2.11-B` 收入下限 × capex 上限 = **3200 ÷ 24400 = 13% 覆盖率**（`2.11-B` 配对表，**反向叠加组合·边界情景**——收入最差×capex最贵，非同一方向自然配对）。本情景承担主报告的"断裂"面，但**其端点本身不作主陈述**；烈度仍按 `4.5` 信用敞口口径（占缺口 1/4—1/3）。**隐含条件**：k 兑现低于基准下段（3—7 年 J 曲线未兑现，`2.6-C`）、组织兑现率 ↑ 失败（`6.3-①` 窄义锚证伪）。

**(二) 触发条件（若 X 则 Y，条件句）**：**若** 下列任一组合实现——①有效租金跌破会计线（`5.0` L1：CoreWeave 类 (c) 玩家 H100 长约跌破约 $1.8/h，`5.1-①`）；**且/或** ②抵押折扣进入 60% 档并触发 LTV 追保潮（`5.0` L2、`5.2`）；**且** ③capex 指引连续 2 季下修（`5.0` L3、`5.3-①`）——则硬着陆成立。**单触发不倒（`5.1-⑤`—`5.5-⑤` 有不倒条件）、多触发共振才升级**。

**(三) 传导顺序（只引第 5 章骨牌，不新造）**：L1（最杠杆租赁商违约，`5.1`）→ L2（抵押利差走阔 + 追保潮，`5.2`，**主驱动=快钟**）→ L3（母体 capex 下修，`5.3`，落后 L2 2—4 季因 FCF 缓冲）→ L4（HBM/PPA 重谈反转，`5.4`）→ L5（搁浅数据中心，`5.5`，12—36 个月最慢）。**不倒条件随级引用**：L1-⑤(i)(ii)(iii)、L2-⑤(i)(ii)(iii)、L3-⑤(i)(ii)(iii)、L4-⑤(i)(ii)(iii)、L5-⑤——每级倒须先证其不倒条件全失效。

**(四) 烈度输入**：信用敞口 = **1350—2180 亿/年（占缺口 1/4—1/3）**，峰值叠加（新增+到期同窗）收窄至 **1/2—2/3**（`4.5`/`5.6-③`）；抵押折扣 **60% 档以上**（`5.2`，追保缺口约原抵押 27%）；**浮盈回吐并联路径（`3.0-2`，Lee 请愿，ASU 2016-01 主张·待核）为利润表端路径**——**2026 Q1 利润表显影总量约 500 亿量级**（Amazon 行项目 $123.3 亿 + Alphabet $377 亿，口径各异、**Anthropic 单独归因不可得——`0.10`**）；**存量量级以融资轮估值为触发**（估值持平/下调→浮盈转回吐，触发条件=请愿人主张·待核，`7.1-③`）。**归因不可得本身即 Lee 请愿（`3.0-2`）论点的第一手实证**。500 亿显影总量只作"请愿人主张·待核"的量级引用，不进入主演算；禁止单主体归因、禁止"545 亿/168 亿/377 亿单主体浮盈"表述。浮盈回吐与信用渠道（偿付端）**并联陈述**——估值浮盈回吐与 LTV 追保是两个不同传导面，若串联（"浮盈回吐→抛售→LTV"）即混算为单一链条，违纪。
> **1350 亿下方构成说明（补）**：信用敞口 1350—2180 亿/年的下界 **1350 亿**＝融资型需求下限 **3550 亿**（缺口中心 6550 − 云商内部可消化上界 3000，`2.3` 第 6 步）× 债务占比下限 **38%**（`4.5` 口径）≈ 1349 亿；上界 **2180 亿**＝融资型需求上限 4550 × 债务占比上限 48%。**该下界仅在"展期可持续 + 分子分子已完整捕获"两前提下成立**——任一破坏（私募存量升格/单季数百亿坏账/到期墙叠加，`4.5`/`5.6-③`、反方脆弱 #1 放弃数据）即须按峰值重估上移，故硬着陆烈度**默认按峰值叠加至 1/2—2/3、而非 1/4—1/3 下界**设参。

**(五) 时序（Low 时间置信标签）**：**主驱动=快钟**——L2 追保潮主导触发时序（季频重估，`5.2-③`）；**到期墙 280—420 亿/年为放大器**（`5.6-①`）——仅当 rollover failure（再融资市场关闭）出现时升级为悬崖。**空窗 2028—2032**（承诺刚性交付 vs 收入爬坡上限）：本情景在该窗内兑现的**时间点判断为 Low 置信**——结构（撞点在 L2/L3）是确定判读，何时扣动不确定。

**(六) 观测哨（≥3，现金流类先于 P&L）**：
1. **租金曲线**（现金流类，`5.1-②`）：H100 一年期长约从 $2.10—2.70 → 滑向 $1.8（先于利润表任何读数）。
2. **利差**（现金流类，`5.2-④`）：DDTL 从 SOFR+2.25% 走阔（零溢价是目前未定价状态，`0.1-C6`）。
3. **私募信贷存量**（现金流类，反方脆弱 #1 的放弃数据）：从"未捕获"升格为"显著高于表内 +2099 亿"（`0.1-C8`）。
4. **FCF/OCF 比值**（现金流类，`0.1-A6`）：CapEx/OCF 96% → 逼近/突破 100%。
5. **P&L 类最后看**：ARR 斜率（`0.5-4`）退居次位——利润表滞后于偿付端。

**(七) 判读手册（升级/降级/放弃）**：
- **升级为硬着陆**：租金破 $1.8/h + 60% 档追保 + capex 下修三触发共振（`5.0`）。
- **降级为慢消化**：租金企稳 ≥$1.8/h 两季（`5.1-⑤(i)`）且利差未走阔（`5.2-⑤(i)`）。
- **放弃本情景**：R 中心连续两季站上 0.3 或 B run-rate ≥5000 亿（`0.7-②` 裁决线、反方论证二）——收入侧健康穿越，硬着陆概率归零，转慢消化/软着陆。

**(八) 与反方对话**：本情景**拒绝**反方三条论证的"当前不成立"前提（反方 A 论证一/二/三之"局限"）——即反方自己也承认其论证依赖"再融资市场不关闭"（局限一）、"分子证伪"（局限二）、"30% 档 + 新卡托底"（局限三）。本情景接受反方**一条补充**：硬着陆真正兑现须**先证不倒条件全失效**（`5.1-⑤`—`5.5-⑤`），拒绝"未触发=即将触发"的滑坡（反方熊点②）。**净立场：硬着陆是条件组合，不是默认路径。**

### 7.6-② 软着陆（配对角：73%·乐观叠加·边界情景）

**(一) 配对角声明**：对应 `2.11-B` 收入上限 × capex 下限 = **8900 ÷ 12200 = 73% 覆盖率**（`2.11-B` 配对表，**反向叠加组合·边界情景**——收入最好×capex最省，非自然配对，**不作主陈述**）。隐含条件：k 兑现至基准上段甚至激进情景（组织兑现率 ↑ 至 35%+，`2.11-B` 激进情景 32—143%）。

**(二) 触发条件（若 X 则 Y）**：**若** 收入斜率保持 +50—100%（`2.11-C`）而 capex 增速回落至 +20—30%（电力/并网物理限速，`0.1-C14/C15`），R 于 2028—2030 触及 0.3—0.5（`2.11-C`）——则软着陆成立。**关键**：靠分子（收入）健康抬升而非分母坍缩（`2.11-C` 辩证：R 改善须读两条斜率，分子驱动才健康）。

**(三) 传导顺序**：正序骨牌**不触发**——L1—L5 全部维持"不倒条件"（`5.1-⑤`—`5.5-⑤`）。**唯一可能触及**：L3 不倒条件 (ii)"电价/并网物理限速"（`5.3-⑤(ii)`）——capex 因物理约束而非财务恶化"自然放缓"，非病理性下修。

**(四) 烈度输入**：信用敞口**趋近 0 新增违约**（软着陆名义上有到期墙，但展期可持续，`5.6`）；抵押折扣稳于 **30% 档**（`5.2-⑤(i)`，不触发 LTV）；浮盈回吐主张若成立（`3.0-2`，待核），其**回吐仅削利润表浮盈、不触发偿付断点**——并联路径无信用传导。

**(五) 时序（Low 时间置信）**：**主驱动仍为快钟但未走**——折旧换代正常接力（B200 承接 B100/H100 转售，`5.2-⑤(ii)`）而非崩塌；到期墙 280—420 亿/年作为**可滚动展期的计时器**（`5.6`）正常运转。2030 前该情景**时间点 Low 置信**。

**(六) 观测哨（≥3，现金流先于 P&L）**：
1. **capex 增速回落**（现金流类，`2.11-C`）：capex +30% 以下而收入 +50%+，R 分子驱动抬升。
2. **利差维持**（现金流类，`0.1-C6`）：无走阔、投资级定价维持。
3. **ARR 斜率**（现金流→P&L 边界，`0.5-4`）：OpenAI/Anthropic 年化 +50%+ 持续（`2.11-C`）。
4. **B 口径 run-rate**（`0.7-②`）：逼近 5000 亿（软着陆的时间护栏）。
5. **P&L 类最后**：营业收入/经营利润在 ARR 兑现后跟进。

**(七) 判读手册**：
- **升级为软着陆**：R 连续两季站上 0.3 或 B run-rate ≥5000 亿（`0.7-②` 裁决线）。
- **降级为慢消化**：capex 未回落至 +30% 以下、R 在 0.3 附近徘徊（未连续两季站上）。
- **放弃**：capex 增速重新上行至 +40%+（`0.1-A3` 指引上修）——软着陆的"分母物理限速"前提失效，转慢消化。

**(八) 与反方对话**：本情景**接受**反方论证二"R 可被收入斜率追上、不必等分母坍缩"（反方 A 论证二）——这正是软着陆的机制；**同时接受**反方熊点①"承诺交付可重谈"（`0.8-6` PPA 逻辑迁移到算力长协，递延刚性交付）。**拒绝**反方若把"可改写"推成"必改写"（反方不做此断言，此处防滑）。**净立场：软着陆是收入侧健康兑现的理想端，受 k 兑现、capex 物理限速双重约束，非默认路径。**

### 7.6-③ 慢消化（基准叙事 · 同向带 26—36% · 主参照）

**(一) 配对角声明**：对应 `2.11-B` **同向带 26—36% 覆盖率**（**26%＝收入下限 × capex 下限**（3200÷12200）、**36%＝收入上限 × capex 上限**（8900÷24400），`2.11-B` 配对表，**主口径陈述的唯一参照带**——两端均为"收入与 capex 同方向"的自然配对，不同于 13%/73% 的反向叠加）。隐含条件：k 爬至 10—35% 基准中段（`2.6-C`）、R 中心维持 0.229（`2.3`）、缺口中段靠 ④ 内部挪用 + 债务层展期消化（`2.11-B` 结论）。

**(二) 触发条件（若 X 则 Y）**：**若** 收入斜率与 capex 斜率进入"比值改善但缺口额仍扩"的黏着区（`2.11-C` 辩证：R 升 ≠ 缺口缩），且无 L1—L3 任一触发共振（`5.0`）——则慢消化成立。**机制**：快钟部分走（少数 (c) 类局部追保）但被母体/兜底吸收（`4.3-A/B`），到期墙靠展期滚动（`5.6`）。

**(三) 传导顺序**：骨牌**部分触发、全程被不倒条件兜底**——L2 触及 30% 档（追保但可补仓，`5.2`）后**不明净走阔** → L3 不倒（FCF 缓冲）→ L4/L5 以"折价再配置"而非"全损/搁浅"收尾（`5.5-⑤` 遗产论证）。**不倒条件逐级生效**：`5.1-⑤(i)`（长约锁价）、`5.2-⑤(i)(ii)`（30% 档+新卡托底）、`5.3-⑤(i)`（AI 回报斜率仍超 capex）、`5.5-⑤`（折价再配置）。

**(四) 烈度输入**：信用敞口在 **1350—2180 亿/年**区间内波动但**可控展期**（`4.5`）；抵押折扣在 **30—60% 档之间**（`5.2`，偶发追保、无系统性清算）；浮盈回吐（`3.0-2`，待核）若成立，**作为利润表波动源**与信用渠道并联存在、无系统性传导。

**(五) 时序（Low 时间置信）**：**主驱动=快钟但被延宕**——重估季频持续、偶发触发 30% 档追保但被吸收（`5.2`）；到期墙 280—420 亿/年为**持续展期的计时器**（`5.6-①`）。长期消化期拉长至 **2028—2032 空窗之后**（Low 置信）——慢消化是"打时间仗"而非"打烈度仗"。

**(六) 观测哨（≥3，现金流先于 P&L）**：
1. **利差区制**（现金流类）：SOFR+2.25% 小幅走阔但未跳档（`0.1-C6`）。
2. **到期墙滚动**（现金流类，`5.6`）：280—420 亿/年展续成功率保持在历史常态（无 rollover failure）。
3. **capex-OCF 收敛方向**（现金流类，`0.1-A6`）：96% 高位但未反向恶化（`5.3-①`）。
4. **抵押重估结果**（现金流类，`5.2-③`）：季频重估多数落 30% 档、少数落 60% 档且被补仓承接。
5. **P&L 类最后**：减记规模（`3.3` 交叉点）在可控范围内、不引发连锁。

**(七) 判读手册**：
- **升级为硬着陆**：三触发共振（`5.0`）或多发 60% 档追保无承接 → `5.2` 拒续融资。
- **升级为软着陆**：R 连续两季站上 0.3 或 B run-rate ≥5000 亿（`0.7-②`）。
- **放弃慢消化**（保持为基准叙事）：**只要 26—36% 同向带框架内部参数不崩**（k 未落悲观段 5%、capex 未逼近上限 2.44 万亿），慢消化即维持——它不是一个"会失败的情景"，而是**缺省参照系**。
**(八) 与反方对话**：本情景**接受**反方论证一（偿付压力真实镜像远弱于名义缺口，`4.5`/`5.6` 配额立场——债由债务承担部分仅 1/4—1/3、63—75% 2028 后到期、到期墙是放大器非触发器）、论证三（快钟"部分成立、三条件、"c">"b">"a""、烈度集中在体量最小的 (c) 类）。**拒绝**反方若把慢消化偷换为"不会破裂"的保证——慢消化是"延宕+展期"的景象，**不是"无断点"**（反方自己 A 论证一局限承认此层未证成）。**净立场：慢消化是主参照——不破裂不等于无恙，是结构性延宕。**

### 7.6-D 三情景一致性（一句收束）

三情景共享同一组输入（`4.5` 敞口、`5.2` 三分档、`5.6` 配重、`0.7-②` 裁决线），共享同一组观测哨（且水滴类哨兵排序一致），共享"不产生新断裂点"（全部引用 `5.0` L1—L5 已封笔触发）。**三者不是互相独立的剧本，而是同一组蓄势池在三种兑现率下的三个分岔形态**——对应第一段 7.3-C"合作空间与冲突战场共用同一变量：斜率"。**哪个兑现由 `0.3` 哨兵实测裁决，本报告不下方向签名。**

---

## 7.7 不连续分支（Agent 能力跳变 · 断裂序列作废）

> 承接：`2.12`（不连续分支前向引用）、`2.6-C` 激进情景（k 达 50%+ 成立条件）、`6.3-①/⑤`（真实降本锚形式化）。**本分支非安慰剂——同样给触发指标、观测哨与证伪条件。** 篇幅要求：≥任一主情景（7.6-①/②/③）的 1/3。

**(一) 触发条件（若 X 则 Y，条件句，非方向签名）**：**若** Agent 能力跃迁使组织兑现率 **k 发生数量级跳升至 ≥35%（激进情景成立档）**，则路径①（企业降本，`2.6`）斜率陡增 → 五路径闭合（`2.11`）→ `2.3` 缺口算术改写 → **5.0 L1—L5 断裂序列作废**。

**(二) 机制（引 `2.6`/`6.3`，不新造）**：降本锚 W≈27 万亿（`2.6-A`，Low）当期渗透率 0.137%（`2.6-B`）——**已化渗透空间 >99.6%**是"存量转化"的势能；若 k 从 2—5% 跳升至 35%+，路径① 基准收入 1600—5700 亿/年上移至激进情景 5400—13500 亿/年（`2.6-C`）→ 五路径合计 7800—17400 亿/年（`2.11-B` 激进）→ 覆盖率 32—143%（上端才是"覆盖"）。**`6.3-①` 裁定窄义反转**：降本锚从"潜在降本"（未兑现）转为"已兑现需求"即触发分支。

**(三) 观测哨（Agent 能力跃迁的可量化先行信号，现金流/P&L 均滞后、以能力信号为先）**：
1. **组织兑现率 k 实测跃迁**（核心哨，`2.6-B` 双源锁定：Menlo 支出侧 + NANDA 组织侧）——当期 2—5% → 连续两季跳升。
2. **路径① 渗透率加速**：从 0.137%（`2.6-B`）突破 0.5%/1%（`2.6-A` 池子的转化速度）。
3. **单位 agent 成本断崖**（`0.8-2` 新一代芯片的延伸）：推理成本降数量级 → 企业部署经济性反转。
4. **B 口径 run-rate**：趋向 5000 亿（`0.7-②` 裁决线，与三情景共享）。
5. **capex 非物理限速的回落**：占比性 capex 增速回落而收入斜率陡增（`2.11-C` 健康分子驱动形态）。

**(四) 与三情景的关系**：不连续分支**不是第四情景**，而是**压在三个情景之上的改写开关**——若触发，`7.6-①/②/③` 的输入全被改写（`2.3` 缺口算术失效）。**三情景的裁决线（0.7-② 重锚版）在设计上正是为捕获此分支**：R 连续两季站上 0.3 或 B run-rate ≥5000 亿，既可以是"软着陆"的健康路径，也可以是"不连续分支"的早期读数——**二者靠 k 实测区分**（软着陆 k 爬至 35% 上限；不连续分支 k 跳升至 35%+ 之下的连续加速）。

**(五) 证伪条件（防安慰剂，强制）**：
- **证伪 1**：若 k 连续两年维持 2—5% 无跳升（`2.6-B` 双源实测），本分支作废，回落三情景（基准叙事的慢消化）。
- **证伪 2**：若渗透率在两代芯片周期（约 4—6 年，`0.1-C14`）内未突破 1%，agent 能力跃迁未转化为组织采纳，本分支降级为"远期期权"而非"当期改写器"。
- **证伪 3**：**不得"微调续命"**（三才验证纪律）——若信号在 3 个观测季内未持续（如 k 跳升一季后回落），放弃分支而非改为"半触发"状态。

**(六) 与反方对话**：本分支**接受并放大**反方论证二（R 可被收入追上）——不连续分支是论证二的极限形态。**不接受**反方用"不连续分支"作为三情景硬着陆的免罪券：分支是**需持续观测证实的实证状态**，不是"只要技术进步就不会破裂"的静态保证（`5.5-⑤` 遗产论证已证技术存续 ≠ 当期资产不缩水）。**且**：即便分支触发，断裂序列作废是**改写了缺口的量级**，**不代表信用敞口归零**——(a)(b)(c) 类存量债（`4.3`）仍按原条件到期，只是增量缺口消失、到期墙仍须滚动。这是对反方"技术胜利=零断点"的证伪约束。

---

## 7.8 造局结论：弈者之根的最后判读（一句收束，承接 7.3-C）

三情景 + 不连续分支共享的价值坐标：**全部收束于斜率（`2.11-C` 双斜率 / `7.3-C` 最终判读）**——
- **斜率上去**（R 健康抬升 / k 实测跳升）→ 软着陆或不连续分支（合作空间，`7.3-C`）；
- **斜率僵持**（26—36% 同向带、Q 量黏着）→ 慢消化（延宕，`7.3-C` 根可共存）；
- **斜率崩**（有效租金破 $1.8 / 60% 档追保 / capex 下修共振）→ 硬着陆（绞杀，`7.3-C`）。

**哪个兑现由 `0.3` 哨兵实测裁决，与第一段 7.3-C"合作空间与冲突战场共用同一变量：斜率"严格对齐；本报告不下方向签名。**

---

## 7.9 对反方《本轮周期为何不会破裂》【脆弱性申报】三结论的逐点回应

### 回应一：脆弱 #1（`4.5` 信用敞口＝缺口 1/4—1/3）——**维持 + 补一段话**

- **反方主张**：该敞口依赖"债务占比 38—48% 为下界"（`2.3` 第 6 步）与"敞口是流量非存量"两前提；私募信贷未完全捕获（`0.1-C8`）、坏账一次性计提会使"流量/年"失真；1/4—1/3 被"展期可持续"默默托底。
- **主报告裁决**：**维持 4.5 为"流量口径"结论，不因反方而降级**——4.5 本身已自证"下界含义"（分子低估、真实占比不低于且可能高于 38—48%，`4.5`），且"峰值叠加收窄至 1/2—2/3"（`5.6-③`）已在流量口径之上预置了存量叠加的上修因子。反方所指"展期可持续无声托底"确为真实前提，**但主报告已在 5.6 显式把到期墙定位为放大器而非触发器**（`5.6-①`）——即"展期可持续"不是隐藏假设，而是**被显式纳入配重铁律的结构判断**。
- **让步点（诚实标注）**：**在"存量重估"这一触发下让步**——**若** 私募信贷实际存量升格为"已确认显著高于表内 +2099 亿"（反方放弃数据，`0.1-C8`），**或** 任一财季单次坏账计提达数百亿级，则 `4.5` 流量口径**失效**，三情景烈度改按峰值重估敞口（`7.6-①/③` 的 (四) 输入相应上调）。**此让步不降级 4.5 本身，而是为 4.5 增设一个反方提议的"放弃数据"硬触发。**

### 回应二：脆弱 #2（`2.3` R 中心 0.229、裁决线 0.3、"可改写"）——**接受加强 + 一步收窄**

- **反方主张**：R 的分子（B 口径 1450—2500 亿）含循环采购截留主观拆分（`2.1-A`），分母（capex 6950—1.0 万亿）非官方统一指引（`0.1-A3`）——两根都是半主观杠杆，R 的"精确感"是算术精度非事实精度。
- **主报告裁决**：**接受** R 的半主观本质（主报告 7.4 自我安放已申报 R 值脆弱性），**但收窄为方法改进而非否定**——把"可改写"从反方的乐观读法收紧为**受检的裁决框架**：正是因分子分母均半主观，主报告才把裁决线定为**重锚版**（R 连续两季站上 0.3 **或** B run-rate ≥5000 亿，`0.7-②`），而非单一高精度读数。**反方所指的"主观拆分"恰是重锚版的理由**：单点 R 不可信，才用"连续两季 + run-rate 护栏"双线裁决。
- **让步点（向下收窄）**：**若** 净额法把 B 口径收入系统性下调（`3.4-A`）或真实 capex 远超指引上限 1.0 万亿（反方放弃数据），R 实值下沉至 **<0.1 持续**（`0.3` 已设此"缺口命题强化"信号），则"可改写"叙事**放弃**，三情景中的硬着陆权重在裁决框架内上移（`7.6-①`），主报告不因 R 的"可改写"而拒绝这一更悲观的读数。

### 回应三：脆弱 #3（`3.3` 技术口径已技术性亏损、交叉点"悬崖感"）——**维持结构 + 限权为"监测"**

- **反方主张**：交叉点依赖"估算·低"参数（单卡 $25k、寿命 2—3 年、7000h、折旧 1.5—2×，`3.1-B`/`3.3`）；主报告利润表口径不看回收率（GPU 折旧≠全损，`5.5`）。
- **主报告裁决**：**维持结构**（技术寿命 vs 会计寿命的错配是 `3.1`—`3.3` 全部传导链的物理基础），**但按反方提议把"悬崖感"限权为"监测信号"而非"独立触发器"**——交叉点的角色降级为**观测哨成员**（`7.6-①/③`(六) 中"P&L 类最后看"的减记规模哨），其对三情景烈度的作用是**放大**而非**独立引爆**（主驱动仍是快钟 `4.4`/`5.6`，不是利润表交叉点）。**不接受**反方"完全不看回收率即失真"——`5.5-⑤` 遗产论证已显式分离"资产估值缩水"与"技术失效"，`4.4` 抵押折扣本就按"技术寿命 × 租金现金流"而非"账面 × 数量"计价（`4.4`）——回收率维度在主报告是**已纳入不足**、非**完全缺失**。
- **让步点（限权 · 触发器重锚 · 方案A）**：原阈值"站上会计线 $1.8/h 两季"**无区分度，已删除**——注册日以来一年期长约长期高于 $1.8（当前 $2.10—2.70，`0.5-3`，High），该条件自始即处触发态，无法充当"出现→让步"的判据，滥用为"总是让步"。代之以**方案A触发器（单轨；均为 1y 长约口径，与违约线 `5.1` 同口径，禁止与现货价 `0.5-3` 现货 $2.79—2.82 混淆）**：**若** H100 一年期长约**站稳 $2.74–2.79 上方两季**（`0.5-3` 长约当前上沿 $2.10—2.70，**注册时点尚未突破、有区分度**）→ **下调** `3.3` 交叉点"悬崖权重"（硬着陆须转靠 L2/L3 触发而非 L1，交叉警报从"技术压力证伪"转为"只作利润表旁证"）。**选A弃B理由**：方案B（跌破 $1.8/h 两季→上调悬崖权重）与 `5.1` L1 违约线**重复**（L1 已用 $1.8 作违约线），且反转让步方向**应保留向上调整空间**——故仅保留方案A、删除 $1.8 下探轨，禁止"墙头草"双向同取。

### 7.9-C 三点回应的一致性收束

三条回应遵循同一原则：**不因反方而全盘降级，不因自信而拒绝让步**——每一条都收到"在何种可观测数据出现时让步/放弃"，且让步数据全部是主报告自己 `0.3` 哨兵 / 反方放弃数据中可观测的硬信号（租金 `0.5-3`、私募存量 `0.1-C8`、B 口径 run-rate、netting `3.4-A`）。**这是主报告与自己对手之间的"对称的证伪契约"**：不是主报告赢了反方，而是两者共享同一组望远镜、只在对同一个角落的看法上分叉——`6.3-⑤` 对这组结果的定位：方法进步提升可证伪性，不消除缺口本身。

---

## 7.10 本段自检清单（三项）

**① 锚点回溯与口径纪律**
- 三情景配对全部回溯 `2.11-B` 2×2 生成矩阵，13%/73% 均标"反向叠加·边界情景"、慢消化用同向带 26—36%（`0.7-③`，主口径只用同向带）✓；无情景单独摘 13/73 作主陈述。
- 烈度输入全部绑定 `4.5`（敞口 1/4—1/3、峰值 1/2—2/3）、`5.2`（三分档 30/60/85，禁用 16—85% 全域）、`5.6`（快钟主驱动、到期墙放大器）✓；置信度标签随数字走（`0.7-①`）✓。
- **无新增断裂点**：三情景传导全部引用 `5.0` L1—L5 已封笔触发与不倒条件（`5.1-⑤`—`5.5-⑤`），未新造任何骨牌或传导链 ✓。
- **浮盈回吐并联**（`3.0-2` Lee 请愿，ASU 2016-01 主张·待核，7.1-③）与信用渠道**并联陈述、禁止串联混算** ✓。

**② 结构与义务检查**
- 三情景每情景八要素完整（配对角/触发/传导/烈度/时序/观测哨/判读手册/与反方对话）✓；观势节"造局"职责已由 7.6 承接（第一段 7.0 承诺履行）✓。
- **观测哨先后纪律**：所有情景现金流类哨兵（租金/利差/私募存量/FCF）先于 P&L 类（ARR/减记）✓。
- **时序纪律**：主驱动=快钟（`5.6-②`），到期墙 280—420 亿/年仅放大器（`5.6-①`）✓；空窗 2028—2032 所有时序带 Low 置信标签，结构结论与时间窗口分开 ✓。
- **不连续分支**（7.7）篇幅 ≥ 任一主情景的 1/3 ✓；含触发指标/观测哨/证伪条件（非安慰剂）✓。
- **反方回应**：对【脆弱性申报】三结论（`4.5`/`2.3`/`3.3`）逐点回应，每点含"维持/让步/放弃数据"，无回避 ✓。
- 义务 A-2 已由第一段 7.1-② 执行；本节无遗留附录 A 义务 ✓。

**③ 主权/边界与最低置信处（供人工重点抽查）**
- **全部情景判断为条件句，无方向押注** ✓；不连续分支非静态保证（附三重证伪）✓。
- **本节置信度最低三处**：
  1. **时间窗标签**（7.6-①/②/③ 的 (五)）：空窗 2028—2032 兑现时点全部 Low 置信——结构判读可信、时点判断不可靠，若推演错最可能错在此（不是结构性那端）。
  2. **浮盈回吐并联路径**（7.6-①/②/③ (四) + 7.1-③/7.3-B）：ASU 2016-01 适用性、云商利润中浮盈规模、401(k) 通道三层均未核验（主张·待核）——若被证伪，仅删该并联路径，不伤其余结构。
  3. **不连续分支的 k 跃迁触发**（7.7）：k 从 2—5% 跳升至 35%+ 是质变假设，历史无先例（`2.6-B`）——本分支的可靠度完全取决于 `2.6-B` 双源实测能捕到跳升；捕不到即为远期期权（证伪 2）。

**④ 边界纪律**：本段不写"全书总结性收尾"（`0.4` 一次一转）；1.5 对冲检验仍归第 7 章收束段职责，但本段已以三情景+不连续分支完成其"结构对冲"部分，**未决方向**留待全书收尾（另行指令）。**本段至此存档即停。**

---

# 第 8 章 · 证伪与检查点纪律

> 章内声明：本章是**运行手册**，不是新推演——不增加任何新断裂点、不修正任何已封笔结论，只做三件事：**(a)** 把前七章"在何种可观测数据出现时·让步/升级/放弃"写死成可勾稽的规则；**(b)** 配一张"何时看、看什么、看到什么意味着什么"的检查点日历；**(c)** 声明三种结局各自产出什么信息。**纪律**：置信度标签随数字走（`0.7-①`）；行号只增不改（新登记锚点用 `8.x-y`）；全部判读为条件句、无方向押注；禁止绕开既有裁决线自行抬高本纪律。

## 8.1 裁决线（重锚版）

> 承接宪法 `0.7-②` 重锚备案与 `0.3` 表首行就地更新。两条裁决线是本章"赛跑改写"的**唯一触发闸门**——改写的不是方向判读，而是"缺口命题"的叙事强度等级。

### 8.1-A 裁决线 R1：R 中心值连续两个季度站上 0.3

- **出处**：`0.7-②`（宪法重锚备案）、`0.3` 表首行（收入/capex 比值哨）、`2.3`（R = 0.145—0.360、中心 **0.229**，`2.3` 第 1—3 步）、`2.11-C`（双斜率赛跑）。
- **判读规则（条件句）**：**若** R 中心值连续两个季度站上 0.3（当前中心 0.229、`2.3` 第 3 步，Medium）→ "可改写"叙事成立，缺口命题从**"强／必须靠资本回收"**降级为**"双线赛跑、可被收入追上"**；三情景权重按此单向下调硬着陆、上调慢消化。
- **必读双斜率（反病理化）**：R 上升有两种成因（`2.11-C`）——**分子驱动＝健康**（收入斜率 > capex 斜率）、**分母坍缩＝病理**（capex 崩塌使比值虚升）。**仅有 R>0.3 但分子斜率跑输分母斜率时，不触发本裁决线**，改走 `2.3` 敏感性末条（分母 ÷2 → R 0.39—0.56 中心 0.46 的判别：**比值改善≠健康**）。判读时必须同时读两条斜率，单看比值会误判（`2.11-C` 辩证）。
- **修订路径**：触发后，回到 `2.11-B` 同向带（**26—36%**）与 k 加权中心（25—30%）重新标定基准情景，而非直接采 13%/73% 端点（宪法 `0.7-③` 矩阵引用纪律）；`4.5` 信用敞口结构（偿付端）**不因 R 上行而触碰**——R 是收入覆盖比、敞口是偿付端，两套账不得互相抵消（`7.6-①(四)` 并联纪律）。

### 8.1-B 裁决线 R2：B 口径 run-rate ≥ 5000 亿美元

- **出处**：`0.7-②`、`2.3` 第 1 步（当前 B 口径 1450—2500 亿、中心 **1950 亿**）、`0.5-4`（OpenAI ARR ≈400 亿）、`2.0-1`（Anthropic run-rate）。
- **判读规则（条件句）**：**若** B 口径行业 AI 年化 run-rate **≥ 5000 亿美元**（当前中心 1950 亿、`2.3`，Medium）→ 与 R1 同向触发"赛跑改写"。5000 亿 ≈ 当前中心值的 2.6×，对应 `2.3` 敏感性"分子 ×2"（R 中心 → 0.46）的上端——两条裁决线互为交叉验证。
- **口径纪律**：5000 亿取 **B 口径**（已排除循环截留、`2.1-A` 两端拆分口径）；**禁止混入 C 口径承诺年化（1300—2300 亿，`2.11-B`）**；显影口径（含未实现浮盈的交易性显影）不入 B 口径分子——`0.10` 已实证单主体归因不可得，显影不能充作可持续收入。

### 8.1-C 反让位路径（反方脆弱 #2 的放弃数据）

- **出处**：反方脆弱 #2（`05` C 节）、`2.3` 敏感性（分子 ÷2 → R 0.07—0.18 中心 0.11）、`3.4-A`（净额法）。
- **修订路径（条件句）**：**若** 第三方披露真实 capex **远超指引上限（>1.0 万亿）**，或**净额法把 B 口径收入系统性下调**（`3.4-A`）→ R 实值下沉；当 **R < 0.1 持续（`0.3` 已设此为"缺口命题强化"信号）或 B 口径因净额法被下调**时，"可改写"叙事务必**放弃**、改回"**缺口命题强化**"，并同步上调三情景硬着陆权重——**此时不是回到起点，而是带着"收入斜率跑输"的第一手实证升级**。

---

## 8.2 哨兵总表（分三梯队）

> 每一哨含：**当前读数＋行号＋置信度 → 触发阈值 → 触发后判读＝哪个情景升级/降级/放弃**。**读取次序纪律（继承 `7.10-②`）：现金流类哨兵先于 P&L 类**；触发判读一律回写对应情景（硬着陆 `7.6-①`／软着陆 `7.6-②`／慢消化 `7.6-③`）与骨牌级（`5.0` L1—L5）。新哨补登用 `8.2-s{n+1}`，行号只增不改。

### 8.2-A 第一梯队（快钟秒针）：月频乃至季频先行指标

| 哨 | 当前读数＋行号 | 置信度 | 触发阈值 | 触发后判读 |
|---|---|---|---|---|
| `8.2-s1` 私募信贷合同条款（重估频率／LTV 触发线／补仓宽限期） | 利差 SOFR+2.25%、固定约 5.9%（`0.1-C6`）；快钟三条件 i 部分满足、ii/iii 未见（`4.4`） | Medium | LTV 触发线收紧或补仓宽限期缩短，或利差显著走阔（`0.1-C6`"条款收紧＝债权人觉醒"） | **L2 升级**：硬着陆进入中档 60% 档追保潮（`5.2`），烈度按峰值叠加 1/2—2/3（`4.5`/`5.6-③`）确认，不再按 1/4—1/3 下界 |
| `8.2-s2` SEC 对两项请愿的处置（Lee 请愿 petn4-903 等） | 请愿待处理、主张·待核（`0.10-3`/`3.0-2`） | Low（处置未定） | SEC 受理／驳回／采纳其一 | **采纳→**浮盈回吐并联路径从"待核"升格为 active，`7.6-①(四)`"500 亿显影"成为利润表波动源、硬着陆 EPS 侧烈度上修；**驳回→**该路径降级为"利润表旁证"，`7.6` 三情景仅保留信用渠道主导 |
| `8.2-s3` 算力租金曲线（**现货与长约分列，禁止混用**） | 现货 H100 $2.79—2.82 企稳、1y 长约 $2.10—2.70（`0.5-3`，High；新一代 B200 $3.68 不计入 H100） | High（披露口径） | 长约**跌破 $1.8 会计线**（`5.1` L1、`0.5-3`）；或长约**站稳 $2.74–2.79 上方两季**（`7.9#3` 方案A） | 跌破→**L1 升级**（硬着陆首级骨牌）并联动 s4；站稳上方→**下调 `3.3` 交叉点悬崖权重**（回调 `8.3-f3` 让步登记，硬着陆转靠 L2/L3 而非 L1） |
| `8.2-s4` 算力债利差（CoreWeave 等） | CoreWeave DDTL $11.6B／总债 $325B+（`0.1-C5`）；利差 SOFR+2.25%（`0.1-C6`） | Medium→Low（财务不透明） | 利差走阔＋条款收紧（`0.3`"债权人觉醒"信号） | **L2 前置**：追保与展期成本上修，到期墙放大器（`5.6`）从"条件放大器"转为"实际压力" |

### 8.2-B 第二梯队：季频确认指标

| 哨 | 当前读数＋行号 | 置信度 | 触发阈值 | 触发后判读 |
|---|---|---|---|---|
| `8.2-s5` capex 指引变化 | 2026 四厂指引 ~6950—7250 亿（`0.1-A3`）、capex/OCF 96%（`0.1-A6`） | High | **连续 2 季下修**（`5.3-①`、`5.0` L3）或 capex-OCF 反向收敛 | **L3 升级**（软着陆/慢消化向硬着陆滑移，`5.0`） |
| `8.2-s6` 头部融资轮估值条款 | Series I pre-7300 亿/post-8400 亿（`0.6-4`）；Anthropic 融 $300 亿（`0.6-11`/`0.1-B9`） | Medium | 新轮**估值下修**（`0.3`"融资叙事连续性受创"） | 浮盈转回吐触发（`7.1-③`）：存量量级随估值同步，硬着陆浮盈侧烈度上修 |
| `8.2-s7` 云厂商 FCF 增速 | 2025 FCF 1913 亿、CapEx/OCF 96%（`0.1-A6`）；长债 1320→3419 亿 | Medium | FCF 未回升、CapEx/OCF 维持 ≈100%+（`4.6` 条件句） | 信用层＝边际资金来源的依赖加深（`4.6`），三情景违约/展期压力同向上修 |

### 8.2-C 第三梯队（滞后确认）：P&L 类

| 哨 | 当前读数＋行号 | 置信度 | 触发阈值 | 触发后判读 |
|---|---|---|---|---|
| `8.2-s8` 折旧减记 | Nebius FY25 ICFR Adverse／Material Weakness（`3.0-6`）；折旧裂缝（`3.1-B`/`3.2`） | Medium | 减记规模显著放大（相对 `3.1-B` 累积缺口） | **`3.3` 交叉点 P&L 旁证**：若与 s3 长约跌破同现→技术失真实证；单现→只作旁证、不作触发器（`7.9#3`） |
| `8.2-s9` EPS 浮盈显影 | Alphabet 2026 Q1 其他收入 $37.7B 正文口径、主要为未实现浮盈（`0.10-2`，High）；合计显影约 500 亿量级（`0.10` 判读） | High（披露口径）/Medium-High（归因） | EPS 依赖浮盈显影且浮盈转回吐，或计量准则被请愿叫停（`0.10-2`） | 利润表端"全公司非经营净利"对运营盈利的掩盖被剥离；**禁止据此反推单主体浮盈**（`0.10` 禁令） |

---

## 8.3 让步触发器登记表（限权 · 三处硬让步点）

> 本表把反方《本轮周期为何不会破裂》脆弱性申报的三条"放弃数据"（`05` C 节）与主报告 `7.9` 的裁决**登记为运行时触发器**：每一条只允许在其对应轨触发时单向修正，**禁止"墙头草"双向同取**、禁止微调续命（宪法与反方共同要求的证伪纪律）。

| # | 登记来源 | 触发条件（可观测·条件句） | 让步动作 |
|---|---|---|---|
| `8.3-f1` | 反方脆弱 #1（`4.5`：信用敞口 1350—2180 亿/年＝缺口 1/4—1/3） | **私募信贷存量升格**为"已确认显著高于表内新增长债 +2099 亿"（`0.1-C8`，现 Low）**或任一财季单次坏账计提达数百亿级** | **弃用 1/4—1/3、改用峰值重估敞口**（上移至 1/2—2/3，`4.5`/`5.6-③`）；硬着陆烈度默认按峰值叠加设参（`7.6-①(四)` 已预置此默认） |
| `8.3-f2` | 反方脆弱 #2（`2.3` R 值"可改写"叙事） | **R < 0.1 持续** 或 **B 口径收入因净额法系统下调**（`3.4-A`） | **放弃"可改写"叙事、改回"缺口命题强化"**（同 `8.1-C` 修订路径）；三情景硬着陆权重上调 |
| `8.3-f3` | 反方脆弱 #3（`3.3` 交叉点"悬崖感"）——**修正后版本·方案A** | H100 1y 长约**站稳 $2.74–2.79 上方两季**（`0.5-3`，注册时点尚未突破、有区分度） | **下调 `3.3` 交叉点"悬崖权重"**（`7.9#3` 方案A：硬着陆转靠 L2/L3 触发而非 L1，交叉警报从"技术压力证伪"转为"只作利润表旁证"） |

> **为什么 f3 用 $2.74–2.79 而非反方原版的 $1.8**：反方脆弱 #3 原放弃数据为"长协站上会计线 $1.8/h 两季"，但 `0.5-3` 一年期长约**注册日以来长期高于 $1.8**（当前 $2.10—2.70），该条件自始即处触发态、无区分度（`7.9#3` 已裁决删除）。方案A 阈值取长约当前上沿之上的 $2.74–2.79，**注册时点尚未突破、才具备"出现→让步"的判据价值**。选 A 弃 B：B（跌破 $1.8 上调权重）与 `5.1` L1 违约线重复，且反转让步方向应保留向上调整空间（`7.9#3`）。

---

## 8.4 检查点日历

> 每个窗口只列可观测指标，判读回写 `8.2` 哨兵表；**时序均为 Low 置信**（继承 `7.6-①(五)`：结构判读可信、时点不可靠），窗口内的重点不是"会不会触发"，而是"触发时是否已在看"。

### 8.4-A 2026Q4
- (i) 2026 下半年 capex 指引是否下修（`8.2-s5`，L3 前置）；(ii) H100 长约是否站上 $2.74–2.79 或向 $1.8 滑（`8.2-s3`）；(iii) 私募信贷合同条款重估结果——LTV 触发线/补仓宽限期（`8.2-s1`）；(iv) 两项请愿处置进展（`8.2-s2`）；(v) 下一轮头部融资估值（`8.2-s6`）。

### 8.4-B 2027H1
- (i) **R 值连续两个季度决算**（`8.1-A` 裁决线 R1：是否连续两季站上 0.3）；(ii) B 口径 run-rate 是否逼近 5000 亿（`8.1-B`）；(iii) 云厂商 FCF 季度决算（CapEx/OCF 96% 是否加压，`8.2-s7`）；(iv) 最杠杆出租商违约/不倒信号（`5.1` L1、`8.2-s3/s4`）。

### 8.4-C 2027H2
- (i) 到期墙第一批短档债滚动（280—420 亿/年、`5.6` 放大器是否转为实际压力，`8.2-s4`）；(ii) 浮盈显影回转/估值回吐（`8.2-s6/s9`，EPS 是否依赖 `0.10-2` 未实现浮盈）；(iii) P&L 折旧减记哨（`8.2-s8`）。

### 8.4-D 2028+
- (i) 空窗期观测（承诺刚性交付 vs 收入爬坡上限，`2.6-D`——只判"断/不断"、不判何时）；(ii) L4/L5 遗产检验：搁浅数据中心是"折价再配置"还是"全损"（`5.5`/`6.2-F`）；(iii) R 长期决算（`2.11-C` 双斜率：分子/分母斜率的长期对比）。

### 8.4-E 解耦总表（类型 × 自然频率 × 取数源）

> 把 `8.2` 哨兵总表与两条裁决线**按观测性质解耦为三维**（类型／频率／取数源），供复核会一次通读。**类型三判（互斥）**：事件型＝绊线即时触发、无固定周期、触发即读；序列型＝出自由时间序列、按固定周期读数；状态型＝存量清单、只随盘点刷新、无触发概念、**不作事件预警**。**读取次序纪律不变（`7.10-②`）**：现金流类先于 P&L 类。

| 观测对象 | 类型 | 自然频率＋取数源 | 对应锚点 |
|---|---|---|---|
| SEC 对两项请愿的处置 | **事件型·绊线** | 无周期——RSS／检索警报／财报日历订阅，检索 "petition + 请愿编号" | `8.2-s2` |
| 头部融资轮估值与条款 | **事件型·绊线** | 无周期——财经媒体轮次推送，检索主体名 + "funding / valuation / tender" | `8.2-s6` |
| 新发信贷合约条款（LTV／补仓宽限） | **事件型·绊线** | 无周期——债务发行披露，检索 "facility / covenant / creditspread" | `8.3-f1`、`8.2-s1` 侧面 |
| 算力租金曲线（现货/长约分列） | **序列型·月读** | 月频——GPU 云市场报价（`0.5-3`，High） | `8.2-s3` |
| 算力债利差 | **序列型·月读** | 月频——信贷利差报价（CoreWeave DDTL，`0.1-C5/C6`） | `8.2-s4` |
| capex 指引 | **序列型·季读** | 季频——财报指引更新（`0.1-A3`，High） | `8.2-s5` |
| 云厂商 FCF | **序列型·季读** | 季频——财报决算（CapEx/OCF，`0.1-A6`） | `8.2-s7` |
| R 值（双斜率）／B 口径 run-rate | **序列型·季读** | 季频——收入/capex 双斜率季决算（裁决线口径） | `8.1-A/R1`、`8.1-B/R2`、`8.1-C` |
| P&L 折旧减记／浮盈显影 | **序列型·季读** | 季频——财报 P&L（`3.1-B`、`0.10-2`，High） | `8.2-s8/s9` |
| 私募信贷合同条款库 | **状态型·每季盘点** | 季频——存量合同条款清单盘点（LTV／补仓宽限期） | `8.2-s1` |
| 抵押折扣/贬值分档（30/60/85） | **状态型·每季盘点** | 季频——`5.2` 三分档刷新（`4.4`/`5.2`） | `4.4`、`5.2` |

> **解耦要点**：事件型哨兵**不能放进季度固定议程**——它们只由绊线即时触发（见 8.4-G），触发即加开短会、不等下期复核会；序列型按其频率单选月读或季读；状态型只做盘点不作预警，**防止把存量清单误当事件触发器**——"解码（读什么）"与"触发（何时跳）"这两件事在 8.4-E 中被显式拆开。

### 8.4-F 复核会制度（前密后疏 · 不对称网格）

> 检查点日历升级为**"复核会"制度**：定期复核会按**前密后疏**的不对称网格召开，事件型绊线触发时**随时加开短会**（不等定期会）。每次复核会**固定议程四步（不可跳步）**：**① 重算 R 值 → ② 通读解耦总表（8.4-E）→ ③ 执行判读手册（`8.2` 判读列回写对应情景）→ ④ 刷新过期锚点**。全部议程为条件句、无方向押注（`0.7-①`）；时序均为 Low 置信（`7.6-①(五)`）。

| 网格 | 复核会（历次） | 承接窗口 | 新增观测重点（在 8.4-A—D 既有内容之上） |
|---|---|---|---|
| **每季一会（2026Q4—2027Q4）** | 2026Q4｜2027Q1｜Q2｜Q3｜Q4（共 5 次） | 8.4-A（2026Q4）；8.4-B/C 细化到季 | 除既有哨点外每次必重算 R 值（裁决线 R1/`8.1-A` 两季连续判定即在此窗口密算）；季内任一事登绊线即加开短会 |
| **每半年一会（2028—2029）** | 2028H1｜2028H2｜2029H1｜2029H2（共 4 次） | 8.4-D（2028+ 空窗） | 空窗期"断/不断"判定（只判时机不判方向，`2.6-D`）；半年窗口收敛为半年度 R 决算 |
| **每年一会（2030 起）** | 年度（每历年内 1 次） | 8.4-D 遗产检验 | L4/L5 遗产核验（`5.5`/`6.2-F`）＋长期双斜率决算（`2.11-C`） |

> **不对称理由**：2027 前为阈值判定密集期——裁决线 R1/R2 首次可能触达、`8.3` 三处触发器皆落在此网格内，故每季；2028+ 进入空窗期，观测对象转为"断/不断"的遗产检验，频率降为半年；2030 后只留年度哨。**前密后疏 ≠ 前重后轻**：后期频率下降源自"观测对象从时点阈值转为存量趋势"，而非信息重要性下降（`8.4-D`）。

### 8.4-G 事件型哨兵绊线清单（单列）

> 事件型哨兵**只由绊线即时触发、不进入季度固定议程**。每条列**监测工具 → 检索式/关键词 → 告警通道 → 触发动作**。绊线加开短会时，议程仍走 8.4-F 固定四步，只是把对应事件判读**提前**插入第 ③ 步。

| 绊线（事件型） | 监测工具 | 检索式／关键词 | 告警通道 | 触发动作 |
|---|---|---|---|---|
| `8.2-s2` SEC 请愿处置 | SEC EDGAR 全文检索＋监管日历 RSS | 请愿编号 "**petn4-903**"（Lee 请愿）／检索式 "SEC petition AI unrealized gains accounting" | 监管 RSS 订阅＋检索警报（每日） | 采纳→浮盈并联路径升格 active（`7.6-①(四)`）；驳回→降级利润表旁证（回写 `8.2-s2` 判读） |
| `8.2-s6` 头部融资轮条款 | 财经媒体轮次推送（Bloomberg／The Information／TechCrunch） | **六家主体名** "Anthropic" "OpenAI" "CoreWeave" "Nebius" "Amazon" "Alphabet" ＋ "funding / valuation / tender" | 主体名检索警报（实时） | 估值下修→浮盈转回吐（`7.1-③`），硬着陆浮盈侧烈度上修（`7.6-①`） |
| `8.3-f1` / `8.2-s4` 新发信贷合约条款 | 债券发行披露＋信贷利差报价流 | "facility / covenant / LTV trigger / margin call / creditspread" ＋ 六家主体名（同 `8.2-s6`） | 信贷流 RSS／利差警报（实时） | 存量升格或单季坏账计提数百亿级→弃用 1/4—1/3、改按峰值 1/2—2/3（`8.3-f1`） |

> **检索词路由纪律**（防误报）：事件型绊线只挂**真正的即时事件**。"**capex guidance**"虽是你方示例检索式之一，但被 8.4-E 归入**序列型·季读**（`8.2-s5`）——其默认由财报日历季频驱动、不外挂绊线；**仅当同季出现超出财报日历的指引跳变（事件性下修）时，才临时升格为绊线**加开短会。**petition / creditspread / funding** 三者无固定周期、确为绊线。此路由防止把序列型当事件型刷屏，是 `7.10` 读取次序纪律的绊线侧对应。

---

## 8.5 全结局信息性声明

> 本报告不押注方向，但**每个结局都生产信息**——这是"证伪"高于"预测"的兑现方式。三种结局各自产出：

**① 证实结局（硬着陆 / 慢消化滑向断点）**
- 产出：五级骨牌 `5.0` L1—L5 的**逐级传导可验证时序**（哪级先倒、传导间隔是否符合 `5.0` 预警时间）；**快钟假说**（`4.4`/`5.2`）随 s1/s4 触发被确认，抵押折扣分级（30/60/85）获得真实样本；两项政策输入（SEC 请愿处置、债权人觉醒）后续的可追溯记录。**信息增量＝"断裂路径的实证"**，供未来同类循环做对照。

**② 证伪结局（"可改写"成立 / 被收入斜率追上）**
- 产出：裁决线 R1/R2 被触碰（`8.1-A/B`），缺口命题从"强"降级——**改写的不是结论，而是对"缺口必须依赖资本回收"这一机制的证伪**；采购侧降本锚兑现的实证（`2.6` 路径①渗透率上行）；反方论证二的核心主张（`05`）获得公正检验——"透明可证伪的系统在市场自我修正上快于不可见系统"。**信息增量＝"正面通道的实证"**，证明本轮循环存在健康的收入侧出口。

**③ 政策截断结局（监管/请愿/计量准则叫停介入）**
- 产出：被截断的**正是循环回流的结构面**（`1.4` 闭环、`1.2` 边集合）而非基本面——该结局告诉我们，本轮周期的终结将**由政策而非基本面收束**，历史对照应转向"监管介入型泡沫终结"（而非"基本面崩塌型"）；ASU 2016-01 类计量被叫停的财务影响（`0.10-2`）会被完整记录。**注意：政策截断 ≠ 证伪**——基本面未走完它的证伪路径，本报告对断裂/改写两种结局的裁决线在该结局下**保持未决、不作事后重标**。

---

## 8.6 本章自检清单（三项）

**① 裁决线与哨兵的回溯纪律**
- 裁决线两条（`8.1-A/B`）直接引用宪法 `0.7-②` 与 `0.3` 表首行，阈值（0.3／5000 亿）与 `2.3`/`2.0-7` 口径一致 ✓；双斜率反病理化（`8.1-A`）绑定 `2.11-C` ✓；置信度标签随数字走 ✓。
- 哨兵表三梯队全部回写既有行号（`0.1-*`／`0.5-*`／`0.6-*`／`3.3`／`4.4`/`4.5`/`5.0`/`5.2`），无新造观测指标 ✓；现金流类先于 P&L 类（`8.2` 读取次序、`7.10-②`）✓。

**② 让步与边界检查**
- 三处让步触发器逐条绑定反方脆弱申报原文（`05` C 节）与 `7.9` 裁决，条件句、无方向押注 ✓；禁止"墙头草"双向同取 ✓；f3 采用 `7.9#3` 方案A 修正阈值（$2.74–2.79）而非反方原版 $1.8，并附选 A 弃 B 理由 ✓。
- 检查点日历四窗口皆引用可观测哨，时序全部 Low 置信 ✓；全结局声明（`8.5`）覆盖证实/证伪/政策截断，政策截断明确"≠证伪、不作事后重标" ✓。
- **解耦与复核会纪律（8.4-E/F/G 增量）**：类型三判（事件型/序列型/状态型）互斥、无重叠 ✓；事件型仅控绊线不占固定议程、状态型只盘点不作预警 ✓；复核会固定议程四步（R 值→总表→判读→刷锚）条件句、无方向押注 ✓；绊线另列检索词路由（capex guidance 归季读、petition/creditspread/funding 归绊线）防误报 ✓；全部以 `8.2`/`8.1`/`8.3` 既有锚点回写，**未新增断裂点、未改动 A—D 既有窗口**、行号只增不改 ✓。

**③ 最低置信处（供人工重点抽查）**
- **s2 请愿处置**（`8.2-s2`）：SEC 处置结果未定（Low），其判读（采纳/驳回→硬着陆烈度上修/下调）是影响面最大的单一未知——若推演错最可能错在此处。
- **s4 算力债利差**（`8.2-s4`）：CoreWeave/Nebius 财务不透明（Medium→Low），利差读数依赖媒体口径。
- **空窗时序**（`8.4-D`）：2028+ 窗口的"断/不断"判定可信，具体季度时间不可靠——延续 `7.6-①(五)` 的 Low 时间置信标签。

> **运行说明**：本章不新增裁决，只登记既有裁决的触发与判读。第 8 章至此存档即停——一旦侦测到 `8.3` 任一触发器落定，按对应动作修订并回填《锚点修正录》（`附录 B`）；侦测到未列入但具区分度的新哨兵，按"行号只增不改"补登 `8.2-s{n+1}`。

---

# 附录 A · 后续章节义务清单（2026-09-06 第 2 章收尾时登记）

> 登记规则：每条义务注明对象章节、内容、来源行号与执行状态；目标章节动笔前必须先消化本清单中属于自己的条目，完成后将状态改为"已消化"并回填落点行号。

| # | 义务对象 | 义务内容 | 来源与行号 | 状态 |
|---|---|---|---|---|
| A-1 | 第 4 章 | **开篇锚 = Nvidia 2026-01 搁置事件**：$100B 分批框架（2025-09-22 原始公告"随每 1GW 部署逐步投资、最高 $100B"）于 2026-01 搁置，落点为 Series I $30B 股权（2026-02-27）——作为分层模型"**最软层最先调整**"（资产负债表投入 → 隐性信用背书 PORTS-Pike）的第一次实证，充当第 4 章信用层叙事的起点锚；与 1.6 第 2 条的观测哨伏笔衔接 | 0.1-B6、0.5-2、1.6 第 2 条（背书方式转变 → 第 4 章信用层） | **已消化**（落点：第 4 章 4.1；执行日 2026-09-06） |
| A-2 | 第 7 章 | **对称计算：OpenAI 撬动倍数**——用 2.4-2 同一公式（撬动倍数 ≡ 采购承诺 ÷ 实付股权）计算 OpenAI，与 Anthropic 的 4.1—11 倍对照。**⚠️ 口径仲裁·已裁定（2026-09-06 确认笔误）**：(1) **分子**用 OpenAI 单独承诺簿 **0.60—1.40 万亿**（0.1-B8 三口径），不采用 C 合计 0.93—1.73 万亿（后者混入 Anthropic 0.33 万亿，属主体错配）；(2) **口径子集**锁"已签约绑定义务类"（与 2.1-C 加总、Anthropic 侧 560 亿年化同原则），禁止混用"框架意向"与"绑定义务"；(3) **分母** = OpenAI 累计股权融资额，取第 0 章核验表行号并注明置信度（预期 Low——多轮融资条款未必全公开）；**置信度 Low** | 0.1-B8、2.1-C、2.4-2（公式定义）、第 0 章核验表（0.5-2 Series I、0.6 序列） | **已消化**（落点：第 7 章 7.1-② 推导表 P1—P4 三档配对＋跨档拼接标注；主申报区 3.0—7.8；执行日 2026-09-12） |

---

# 附录 B · 《锚点修正录》（三列：草稿值 → 核验值 → 错误机制）

> 登记规则：覆盖本项目**全部修正条目**，每条标注四类错误机制之一——**知识截止老化**（数据/规则随时间过期）/ **通俗史污染**（公共叙事简化失真）/ **口径混淆**（主体/存量流量/口径跨档错配）/ **无出处精确性**（凭空精确、缺一手来源）。本录作为第 8 章 `8.6` 运行说明的落点：探测到修正即在此登记，只增不改。终审新增两条置顶，标注「终审新增」。

| 草稿值（申报/早期取值） | 核验值（终审/核验后） | 错误机制 |
|---|---|---|
| **「终审新增①」"Anthropic 单独税前浮盈 $16.8B"**（168 亿） | 一手行项目"Upward adjustments…private companies"＝**$12,328M**（未拆分 Anthropic、`0.10-1`，Medium-High）；媒体归因不可复现（全公司非经营总项仅 $15,982M） | **引用链衰减**（请愿主张 → 媒体转引 → 一手三层变形）。元观察：审计链复现失败本身实证了披露缺口的存在 |
| **「终审新增②」审计人"315 亿分母"反推** | 反推错误，**撤回原指控**；保留"跨档拼接须标注"的要求（`7.1-②` 推导表已按单一口径 3.0—7.8 修正） | **跨档归因谬误**（把两个不同口径的端点配成统一区间） |
| Nvidia 对 OpenAI "$100B 承诺" | **$100B 分批框架未转化为约束合同**（Nvidia 10-Q 提示、黄仁勋"never a commitment"），2026-01 搁置，落点 Series I $30B 股权（`0.1-B6`/`0.5-2`/`0.6-4`） | 通俗史污染（把公告框架当约束合同） |
| "1.4 万亿"＝OpenAI 承诺簿（一刀切） | OpenAI 单独立**三口径 0.60—1.40 万亿**；"C 合计 0.93—1.73 万亿"系混入 Anthropic 0.33 万亿的主体错配，弃用（`0.1-B8`、宪法 `0.7-⑤`） | 口径混淆（多主体聚合、主体错配） |
| Oracle "3000 亿 / 5.5 年合约" | **未核验到独立合约原文**，仅见 Tom Tunguz 按 Stargate/基础设施口径拆分，降级 Low（`0.2-3`） | 无出处精确性 |
| "Blue Owl 380 亿"（Oracle 借款/合资） | Oracle 未直接向 Blue Owl 大额借款；实际＝Stargate 38B 银团＋Meta-Blue Owl 27B Hyperion JV，Blue Owl 已退 Oracle 密歇根项目（`0.5-1`） | 无出处精确性 |
| 电信 capex"崩塌超八成" | **否决极端表述**：TIA 口径 2002 较 2001 **降 48%**，为"峰值后腰斩级快速收缩"，三档并列呈现（`0.9-22`） | 通俗史污染 |
| H100 租金"持续单向下行" | 现货 **$2.79—2.82 企稳**、1y 长约 **$2.10—2.70（回升约 +40%）**；B200 $3.68 等新一代不可冒充 H100（`0.5-3`） | 口径混淆（现货/长约、H100/新一代混淆） |
| OpenAI ARR "$40B"（被读作 $40B/月） | $40B ＝ 约 $3.3B/月 × 12 的**年化 run-rate**，非多年合约摊销；不与"$130.7 亿/2025 全年"混淆（`0.5-4`） | 口径混淆（run-rate vs 合约摊销） |
| J 曲线爬坡时间线无出处 | 出处审计（`2.6-D`）：基准中段"k 爬至 10—35%、3—7 年"，"7—14 年上限"为悲观端 | 无出处精确性 |
| Insull 体系历史镜像（两处） | `3.6` 四镜六维核验，两处数据更正（峰值 GDP 占比 5.7—7%、融资形态分层） | 通俗史污染（历史叙事简化） |
| Lucent/Nortel 卖方融资"对称" | 金额与结构不对称（Lucent $81B / Nortel $31B），`6.3-②` 判定不可机械化对称 | 口径混淆（不对称被简化成对称） |
| Rule 192 引用弧线 | 完整弧线：**审计人挑战 → 澄清 → 用户人工终审 → 成立**；含审计人误报教训（经人工终审翻案后保留原结论） | 断言流转失真（审计人误报，经人工纠正；终审采信原结论） |
| 信用敞口"比缺口小一半" | 校准为"**小约 3/4**（占缺口 1/4—1/3）、峰值叠加后收窄到约小 1/2—2/3"（`4.5`） | 口径混淆（流量 vs 存量、缺口 vs 债务敞口） |
| 到期墙总量 840—1260 亿当"年化墙" | 修正为 **280—420 亿/年**（约 +8%）为条件放大器（`5.6`） | 口径混淆（存量总额误当年化、期限未摊分） |
| 撬动倍数"1.9—12.7 倍" | 主申报区**3.0—7.8**（单一口径全簿 ÷ 累计估算）；1.9/12.7 标注为**跨档端点拼接·反向叠加**，仅作边界（`7.1-②`） | 口径混淆（跨档配对） |

---

# 附录 C · 方法论统计页（"观我如仇"的操作化自证）

## C-1 锚点存活率
- **统计口径**：核验表（`0.1-*`/`0.5-*`/`0.6-*`/`3.0-*`）登记锚点中，经二轮复核（`0.5` 抽查 + `0.10` EDGAR 核验）后仍以**原值**被下游引用的比例。
- **存活率：约 15—20%**。判读：本报告锚点管理的重点不在"存活率最大化"——**低存活率是诚实取数的代价**（大量锚点一次兑现后即视为历史快照、不复被引用或已被降级），而非工作失败；`0.10` 实证的媒体归因失真是存活率下行的典型机制。

## C-2 双向攻防战绩（审计人 ↔ 执行AI）
- **执行AI 纠审计人 3 次**：执行侧在连锁审查中发现审计侧三处断言偏差并纠正（含撬动倍数跨档拼接、媒体浮盈归因复现失败、到期墙年化口径）。
- **审计人 纠执行AI 3 次**：审计侧对执行侧申报值/前提提出相反证据并改写裁决（含 `0.2` 各条口径仲裁、A-2 主体错配、Rule 192 弧线中的人工终审）。
- **误报 1 次（经人工终审翻案）**：审计人曾误报执行AI 一处论证，经用户人工终审后**翻案采信原结论**——该次误报已登记入《锚点修正录》（Rule 192 条目）。
- **判读**：攻防接近对等（3:3:1），且**每次翻案都留下可追溯记录**——这正是"观我如仇"的可操作形态：不是赢，是有账。

---

# 附录 D · 价值自审计（D×F×W×N×R 乘法自评）

> 对照宪法起草时预估分（**课题甲 ≈ 0.48**）逐因子说明实际兑现与预估的差异。五因子为乘法不变量，单因子为 0 则整体为 0——自审重点即"哪个因子可能塌"。

| 因子 | 预估（宪法起草时） | 实际自评（2026-09-12 终稿） | 差异与弱点披露 |
|---|---|---|---|
| **D 数据可靠度**（一手核验占比、去媒体失真） | 0.8 | ±0.8 | **兑现并部分上修**：`0.10` EDGAR 实证媒体浮盈归因失真，一手核验意志增强；**弱点**＝数据时效（快变量截至 2026-09-06/09-12，`0.1` 已声明）、接口数据（HBM/电网）仍 Low |
| **F 框架严谨度**（宪法纪律执行率） | 1.0 | ±1.0 | 兑现：置信度随数字走、行号只增改、矩阵引用、并联纪律全部落盘；**弱点**＝执行人与审计人**同源风险**（见下） |
| **W 工作量完整度**（章节/义务闭环率） | 0.7 | ±0.8 | 超兑现：附录 A 义务 A-1/A-2 全销，第 8 章新增运行手册；**弱点**＝`0.10-3`（Anthropic AWS 支出）与 `0.10-2` 归因仍受一手披露缺口的硬约束，无法闭环 |
| **N 论点新颖度**（相对既有叙事的增量） | 0.9 | ±0.9 | 兑现：把"缺口 6550 亿"切分为偿付端/覆盖端两套账、三情景与反方对称证伪契约；**弱点**＝金融视角偏（分析侧重信用/偿付，对跨资产类别联动深度有限） |
| **R 可复现性**（他人能否按图复算） | 0.9 | ±0.9 | 兑现：`2.3`/`2.11-B`/`4.5`/`7.1-②` 全部演算显式可复算；**弱点**＝多口径并存要求读者严格跟随 `0.2` 经，复现门槛高 |

**综合**：0.8×1.0×0.8×0.9×0.9 ≈ **0.52**——较预估 0.48 **小幅上修**。**关键弱点（须诚实）**：
1. **数据时效**：D=0.8 是相对基线；若快变量刷新（capex 指引/HBM/租金）未同步，D 将回落——第 8 章检查点日历即为此设。
2. **执行人-审计人同源风险（F 的隐形减压阀）**：本报告的执行与审计在技术上同一主体（虽分设立场），最强的自我审查仍带有同一推理习气的系统性偏差——`05` 反方作为"外生对手"正是对此的部分补偿，但**无法完全替代真正的独立审计**。这是本自审给审计人的首要复核点。
3. **锚点存活率 15—20%（附录 C）**：数字的"新鲜感"是结构价值，但其可持续性取决于第 8 章哨兵的执行，而非写作本身。

---

# 附录 E · 幻影版对照（一段话）

> 删去全部结构图、算术、触发指标后，本报告退化成什么——一句自检证伪报告"如果只有叙事，还剩下什么"。

**幻影版**：删去四线流向图与闭环边集合、删去缺口 6550 亿/融资型 3550–4550 亿/债务敞口 1350–2180 亿的全部算术、删去裁决线 0.3 与 5000 亿、删去三情景触发阈值与 9 个哨兵、删去反方五熊点与让步登记——剩下的是**一句带方向感的判断**："AI 资本开支靠信用杠杆续命的模式，在收入斜率跑不赢 capex 斜率时，会从某个最脆弱的杠杆角落开始断，而折价再配置会缓冲但如果承接方也缺钱就会变成全损"。这句话本身无新增信息、无时间层次、无证伪路径，等于回到第一章之前、第 0 章快照之外的"未量化直觉"。**幻影版对比的意义**：本报告的全部增量不在那句话，而在"把一句话拆成可复算的账、可观测的哨兵、可撤回的让步"。若读者只记住那句话，报告退化为幻影版；若读者按第 8 章行事，报告才是工具。

---

# 附录 F · 冻结机制升级与文件 SHA256 锚定

> 终审裁决：**"冻结"从声明的自律升级为密码学锚定**——对全部冻结文件在终稿状态计算 SHA256 哈希并登记于此，弥补 git untracked 暴露的自证弱点（`05` 反方报告曾据时间戳自证冻结，升级后以哈希为证）。**仅增不改**：任何后续修订将改变哈希并被本表暴露，从而强制走《锚点修正录》协议而非静默改写。

| 文件（冻结对象） | 冻结属性 | SHA256（2026-09-12 终稿实算） | 复验指引 |
|---|---|---|---|
| `00-核验表.md`（权威取数源·快照） | 只增不改（`0.1` 声明） | `589974B3C5C8F17D83B9400960AFE363FDE2BCF9013DC5969DD09CB4A896E042` | 任何数值改动须经 `0.10`/《锚点修正录》登记 |
| `05-对抗性预注册-本轮周期为何不会破裂.md`（反方报告·完稿即冻结） | 冻结（`05` 首行声明） | `B110444E3443A0AEB1C44EC0FDBD91FE8682154D328F24C723FCB76A99FE6AD8` | 修订即破坏哈希 → 走勘误协议 |
| 主报告 `谁为万亿算力买单——….md`（含宪法快照 `0.2`/`0.7` 与第 8 章、收尾转） | 承载性容器（随批次封发） | `122F3A88AE3FC880CCA339F9AD80916E606DF9D4EF0AC4ED20239E3235AF8359`（**2026-10-11 收尾转并入后、本行回填前实算**） | 主文件为自身容器的登记目标，其哈希存在"自行登记"的自指边际（登记动作本身会移动哈希），故**权威值以封发计算为准**；00/05 两文件哈希为稳定锚、即本表锚定值。**回填终态值**（本行写入后复算）登记于 2026-10-11 封发对话记录（外部账本）；第三方复验以 00/05 稳定锚为主、本行值为辅 |

> **执行注**：`00-核验表.md`（对 `0.10` 做终审裁决更新后）与 `05` 反方报告（冻结态未再改动）的 SHA256 已在本表实算锚定，为**稳定锚**。主报告的哈希会随本文件后续批次的登记动作而变，故标注"封发时复算确认"——**去自指歧义的正确做法**：封发时对主文件最后一次修改后，重跑 `Get-FileHash -Algorithm SHA256` 覆盖上表主文件行，并以该值为准。复验命令：
> ```powershell
> Get-FileHash -Algorithm SHA256 "…\00-核验表.md"
> Get-FileHash -Algorithm SHA256 "…\05-对抗性预注册-本轮周期为何不会破裂.md"
> Get-FileHash -Algorithm SHA256 "…\谁为万亿算力买单——AI资本开支超级周期的资金闭环与偿付断点.md"
> ```

---

# 附录 G · Flag C 补交：反方报告熊点②（LTV 中档连锁）原文（带行号）

> 供审计人终审靶心。该段为反方报告 `05` 第 83—85 行对主报告熊点②（`5.2` 第二级骨牌 LTV 中档连锁）的正面反驳原文；主报告 `7.9` 回应二/三已在第 7 章逐点裁决，`8.2-s1/s4` 将其登记为哨兵。

> **原文（`05` 第 83—85 行）**：
> "**熊点② 第二级骨牌 LTV 连锁（中档 60% 档即触发追保潮）** —— **正面回应**：主报告 5.2 自证当前定价是'**投资级、零风险溢价**'（`0.1-C6`，SOFR+2.25%、固定约 5.9%）——**利差没走阔、没有现实压力**。主报告把'未计入快钟'翻译为'最被低估'，但**'未被定价'更准确的读法是'当前违约风险未被市场观测到'**——反过来，它说明信用市场当前并不认为快钟在滴滴答答地走。且 5.2-⑤ 主报告自列不倒条件 (ii)（新卡高溢价托底）当前真实存在（B200 $3.68，`0.5-3`）；中档 60% 档的 27% 追保缺口，在 (c) 类之外由母体/股权（`4.3-A/B` 兜底逻辑不触发）承接。**反驳核心**：骨牌论把'可能性'写成'将兑现'——而'尚未触发'（主报告自己的当前读数）与'即将触发'是两件事，前者是主报告的观测，后者是主报告的假设。"

> 主报告对应处置：`7.9` 回应三（脆弱 #3）已按"维持结构 + 限权为监测"裁决（`7.9-3`），并把"悬崖感"从独立触发器降为观测哨；第 8 章 `8.2-s4` 哨兵以"利差走阔＋条款收紧"为 L2 前置判据——**若反方"零风险溢价"读数持续成立，则该哨不触发，L2 不升级**（符合反方主张的假说空间）；若利差显著走阔，则反方"未被观测到"转为"被观测到"，该哨触发并回写硬着陆烈度 `7.6-①(四)`。

---

# 收尾转 · 全书收束（2026-10-11 执行，`7.10-④` 悬置项的了结）

> **指令依据**：`7.10-④`"未决方向留待全书收尾（另行指令）"——本节即该指令的执行记录。**本节不新增锚点、不新增断裂点、不新增情景、不下方向签名**（宪法 `0.2`/`0.7` 纪律延续）；只做收束、使用说明与封存登记。本节为全书最后一节，置于附录之后系"行号只增不改"的追加纪律所致。

## 一、全书一句话产品（幻影版之上的一层）

幻影版检验（附录 E）已证：本报告的增量不在那句方向感判断，而在"把一句话拆成可复算的账、可观测的哨兵、可撤回的让步"。收束为一句话：

> **本轮 AI 资本开支的结构 = "卖方融资闭环驱动的需求缺口（`2.3` 中心 6550 亿/年、R 中心 0.229），由债务层按三类发行人分层承接（`4.3`，敞口仅占缺口 1/4—1/3，`4.5`）"；本报告的产品不是"破不破"的预言，而是三件套——缺口账本（`2.3`/`4.5`）＋ 断裂序列（`5.0` L1—L5 与不倒条件）＋ 裁决仪表盘（`8.1`—`8.4`）。**

## 二、未决方向的正式了结

- **报告不下方向签名**（`7.6-D` 已声明），收尾亦不签。三情景（硬着陆 13% / 软着陆 73% 皆为反向叠加边界情景，慢消化 26—36% 同向带为主参照）的裁决权**完全移交** `8.1` 裁决线（R1：R 连续两季站上 0.3；R2：B 口径 run-rate ≥ 5000 亿）与 `8.2` 哨兵三梯队——**报告封存后，方向由数据书写，不由作者书写**。
- **`1.5` 对冲检验的最后一块**（`7.10-④` 移交项）：结构对冲已由三情景＋不连续分支完成（`7.10-②`），本节补其结论形态——**对冲的正确形态是"监测组合"而非"方向头寸"**：任何暴露于本周期的主体（云商股东 / 算力债持有人 / 数据中心项目信贷 / 上游供应链），其可操作对冲 = 按自身敞口类型订阅对应梯队哨兵（`8.2-A/B/C`）并预设触发动作（`8.3` 让步触发器），而非押注"硬着陆"或"软着陆"任一方向。**理由**：本报告已证缺口算术两端（分子分母）皆半主观（`7.9` 回应二），方向押注的置信度上限低于"条件—触发—动作"的条件句组合。

## 三、读者使用说明（一页）

1. **只要结构认知** → 读 `1.2`（四线边集合）、`1.3`（三大闭环网络）、`2.3`（缺口算术）、`3.1—3.3`（会计传导）、`4.3`（三类发行人）、`5.0`（五级骨牌横截面）、`6.1`（四镜六维矩阵）。
2. **要复算** → 按 `2.3`/`2.4-1`/`2.4-2`/`2.11`/`4.5`/`7.1-②` 的【算式】【输入】【演算】【敏感性】四段式逐步重跑；口径必须先读 `0.2` 十一条仲裁。
3. **要跟踪** → 按 `8.4-E` 频率读 `8.2` 哨兵；触发 `8.3` 任一让步触发器 → 按《锚点修正录》（附录 B）协议回填，**禁止静默改写**。
4. **要引用数字** → 必须携带置信度标签与核验表行号（宪法 `0.7-①`），并标注快照日（2026-09-06/09-12）——**本报告数字的寿命以 `8.4-F` 复核会为限，结构结论的寿命长于任何单一数字**。

## 四、封存声明与哈希回填

- 本节并入后，主文件进入**终稿封存态**。按附录 F 协议执行哈希回填：`00-核验表.md` 与 `05` 反方报告两枚**稳定锚**已于 2026-10-11 复验一致；主文件哈希存在自指边际（回填动作本身移动哈希），**附录 F 主文件行登记"回填前实测值"，主文件终态哈希登记于封发对话记录（外部账本）**——第三方复验以 00/05 稳定锚为主、主文件行值为辅。
- 封存后任何改动（含哨兵触发回填）均须走《锚点修正录》协议并重算登记，**本报告从"写作品"转为"运行品"**——它的下半场不在文档里，在 `8.4` 检查点日历的执行里。

## 五、收尾自检清单（三项）

**① 纪律检查**：未新增锚点、断裂点、情景、方向签名 ✓；全部引用既有行号（`1.5`/`2.3`/`4.3`/`4.5`/`5.0`/`6.1`/`7.6-D`/`7.10`/`8.1—8.4`/附录 B/E）✓；条件语句、无方向押注 ✓。

**② 职责检查**：`7.10-④` 悬置项（未决方向＋`1.5` 对冲检验）正式了结 ✓；全书无未销义务（附录 A 2/2 已消化）✓；反方契约闭环（`7.9` 回应＋`8.2-s1/s4` 哨兵＋附录 G 原文留痕）✓。

**③ 边界检查**：本节为全书最后一节，"一次一转"纪律到此终结——**存档即停，封发为终** ✓；本节置信度最低处＝使用说明第 3 条对使用者执行力的假设（报告无法自我执行哨兵，这是全文唯一无法在文档内闭环的环节）。