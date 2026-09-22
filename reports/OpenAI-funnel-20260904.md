# OpenAI / 前沿基础模型平台漏斗筛选

**数据截止**：2026-09-04；行情统一采用最近完整收盘日 2026-09-03，财务数据采用截至 2026-09-04 已披露的最新季报/年报  
**研究范围**：以 OpenAI 为锚点，覆盖前沿基础模型、模型分发平台及具有明确 OpenAI 经济权益的上市公司  
**重要边界**：OpenAI 尚未公开交易。本报告不是“怎么买 OpenAI 股票”，而是比较 OpenAI、竞争者和上市映射的经济质量与价格。本文仅供学习研究，不构成投资建议。

## 一、结论先行

1. **OpenAI 是强公司，但 8520 亿美元私募估值不是安全边际。** 2026 年 3 月完成 1220 亿美元融资；8 月媒体口径的年化收入超过 400 亿美元，对应约 21.3 倍年化收入。增长惊人，但没有公开毛利、经营现金流、承诺算力负债和客户集中度，无法完成价值投资硬筛。
2. **OpenAI 的护城河从“模型领先”转向“用户、开发者、企业工作流、资本与算力”的组合。** API 超过每分钟 150 亿 token、Codex 周用户超过 200 万、企业收入占比超过 40%，证明商业化成立；反面是 Anthropic 的最新披露/报道显示收入增速更快，开源模型持续压低单位 token 价格。
3. **普通投资者最干净的映射不是同一家公司。** 微软有历史权益、IP、Azure API 与收入分成；亚马逊新增 500 亿美元投资及 AWS 分发；软银预计累计投入 646 亿美元、完成后约持有 13%。三者承担的风险完全不同，不能统称“OpenAI 概念股”。
4. **终选：微软（核心）、Alphabet（竞争对手对冲）、软银集团（高风险直投映射）。** Alphabet 不持有 OpenAI，却是最强的纵向一体化替代；它能对冲 OpenAI 失速。软银最接近 OpenAI 股权 beta，但依靠桥贷投入、NAV 波动大，只能是期权仓。
5. **当前没有“闭眼买”。** 微软 28.4 倍 FY2026 PE 尚可但不便宜；Alphabet 的 GAAP PE 被股权投资浮盈严重扭曲，正常化约 30 倍上下；软银必须按 NAV 折价与 LTV 买，不能按 OpenAI 故事追价。

## 二、口径与覆盖度

跨美、港、A、日、韩、欧市场无法从同一免费数据源严格复现“各市场 30 日成交额前 30、30/90 日涨幅前 20、市值前 30”的完整并集。因此本轮以 Nasdaq 2026-09-03 行情、东方财富港股快照、AIQ/CHAT 官方持仓、公司 IR 和监管披露重建 36 家唯一上市主体；A/B/C 分别表示成交活跃、30/90 日动量或主题热度、市值锚。**覆盖度评级 B，不伪造全球排名。**

美股样本的 90 日信号可复现：6 月 1 日至 9 月 3 日，CRM、SNOW、PLTR、MSFT 较强；ORCL、IBM、CRWV、ARM 明显回撤。它只用于发现候选，不替代基本面。

## 三、第一层：全市场扫描（36 家）

市值为 2026-09-03 附近快照或量级估计；“行业占比”指基础模型、AI 云、AI 代理或 OpenAI 权益对集团价值的估计影响，不是公司披露分部。

| # | 公司（代码） | 市场 | 市值快照/量级 | 主业与 OpenAI/模型关系 | 行业占比 | 类别 |
|---:|---|---|---:|---|---:|---|
| 1 | NVIDIA `NVDA` | 美股 | US$5.51tn | GPU、网络、模型工具；向 OpenAI 投资 US$30bn | 50%+，卖铲人 | A/B/C |
| 2 | Alphabet `GOOGL` | 美股 | US$4.19tn | Gemini、Cloud、TPU、搜索 AI | 30%-45%估 | A/C |
| 3 | Microsoft `MSFT` | 美股 | US$3.79tn | OpenAI 股权、IP、收入分成、Azure API、Copilot | 25%-35%估 | A/B/C |
| 4 | Amazon `AMZN` | 美股 | US$2.79tn | 投资 OpenAI US$50bn、Anthropic、AWS/Bedrock/Trainium | 15%-25%估 | A/C |
| 5 | Meta `META` | 美股 | US$1.56tn | 自研模型与 AI 推荐，模型收入未单列 | 20%-30%估 | A/C |
| 6 | AMD `AMD` | 美股 | US$744.7bn | AI 加速器与模型软件，不拥有头部模型平台 | 30%-40%估 | A/C |
| 7 | Oracle `ORCL` | 美股 | US$443.7bn | OCI、Stargate 技术伙伴、模型托管 | 20%-30%估 | A/C |
| 8 | Palantir `PLTR` | 美股 | US$438.4bn | 企业 AI 操作平台，非基础模型 | 30%-50%估 | A/B/C |
| 9 | Alibaba `BABA/09988` | 港/美 | US$270.9bn / HK$2.22tn | Qwen、阿里云、AI 应用 | 20%-30%估 | A/B/C |
| 10 | Arm `ARM` | 美股 | US$258.1bn | AI CPU/IP，OpenAI/软银基础设施映射 | 20%-30%估 | A/C |
| 11 | IBM `IBM` | 美股 | US$221.1bn | watsonx 与企业混合云 | 10%-20%估 | A/C |
| 12 | Salesforce `CRM` | 美股 | US$217.6bn | Agentforce，采购多家模型 | 20%-30%估 | A/B/C |
| 13 | 腾讯 `00700` | 港股 | HK$4.06tn | 混元、元宝、微信分发 | 10%-20%估 | A/C |
| 14 | ServiceNow `NOW` | 美股 | US$150.5bn | 企业工作流代理，非模型公司 | 20%-30%估 | A/B/C |
| 15 | Snowflake `SNOW` | 美股 | US$123.6bn | 数据云、Cortex、模型调用入口 | 20%-30%估 | A/B/C |
| 16 | Adobe `ADBE` | 美股 | US$113.6bn | Firefly 与创意工作流 | 20%-30%估 | A/B/C |
| 17 | SAP `SAP` | 德/美 | 超大软件平台 | Joule 与企业数据分发 | 10%-20%估 | A/C |
| 18 | 软银集团 `9984.T` | 日本 | 大型投资控股 | OpenAI 累计计划投入 US$64.6bn，预计约 13% | 30%+ NAV估 | A/B/C |
| 19 | CoreWeave `CRWV` | 美股 | US$46.6bn | AI 云，OpenAI 重要算力供应商 | 90%+ | A/B/C |
| 20 | 百度 `BIDU/09888` | 美/港 | US$32.5bn | 文心、AI 云、应用与萝卜快跑 | 40%-55%估 | A/C |
| 21 | 商汤 `00020` | 港股 | 中型 | 日日新大模型与视觉 AI | 60%+ | B/C |
| 22 | 智谱 `02513` | 港股 | 高波动成长股 | GLM 模型及企业服务 | 90%+ | A/B/C |
| 23 | MiniMax `00100` | 港股 | 高波动成长股 | 多模态模型、海螺 AI | 90%+ | A/B/C |
| 24 | 第四范式 `06682` | 港股 | 中小型 | 企业 AI 平台，非通用前沿模型 | 70%+ | B/C |
| 25 | 金山云 `KC/03896` | 美/港 | 中小型 | 中国云基础设施与 AI 算力 | 20%-30%估 | B/C |
| 26 | 科大讯飞 `002230` | A股 | 大型 AI 公司 | 星火模型、教育与医疗 AI | 30%-40%估 | A/B/C |
| 27 | 金山办公 `688111` | A股 | 大型软件 | WPS AI，模型来自自研与外部 | 10%-20%估 | A/C |
| 28 | 三六零 `601360` | A股 | 中型 | 360 智脑与安全，模型收入很低 | <20%估 | A/B/C |
| 29 | 万兴科技 `300624` | A股 | 中小型 | 创意 AI 应用，不是基础模型 | 20%-30%估 | B/C |
| 30 | 拓尔思 `300229` | A股 | 中小型 | NLP/行业模型与数据服务 | 30%-50%估 | B/C |
| 31 | Samsung Electronics `005930.KS` | 韩国 | 超大硬件 | 存储、代工、端侧模型 | 10%-20%估 | A/C |
| 32 | NAVER `035420.KS` | 韩国 | 大型互联网 | HyperCLOVA X、搜索和云 | 20%-30%估 | A/C |
| 33 | Kakao `035720.KS` | 韩国 | 中型互联网 | Kanana 模型与通讯分发 | 10%-20%估 | B/C |
| 34 | ASML `ASML` | 欧/美 | 超大设备 | Mistral 战略股东，核心仍是光刻机 | <10% | A/C |
| 35 | Siemens `SIE.DE` | 德国 | 超大工业 | 工业 AI/代理，采购外部模型 | <10% | A/C |
| 36 | C3.ai `AI` | 美股 | 中小软件 | 企业 AI 应用平台，持续亏损 | 70%+ | B/C |

### 未上市 / IPO 候选

| 公司 | 最新已核信息 | 估值/收入 | IPO 状态 | 判断 |
|---|---|---|---|---|
| **OpenAI** | 2026-03 完成 US$122bn 融资；企业收入占比 >40%；API >150 亿 token/分钟 | US$852bn 投后；8 月年化收入 >US$40bn 为媒体/公司内部口径 | 已确认秘密递表，但未决定时间 | 头部，价格与现金流待招股书 |
| **Anthropic** | 2026-05 Series H 融资 US$65bn；公司称当时年化收入跨过 US$47bn | US$965bn 投后；8 月报道年化收入 >US$65bn | 已启动 IPO 准备 | 企业/编码强，收入确认口径待招股书 |
| **xAI / SpaceXAI** | 2026-01 融 US$20bn；2 月被 SpaceX 收购 | 交易估值未在官方公告披露 | 已并入 SpaceXAI | 用户分发强，治理与资本消耗高 |
| **Mistral AI** | 2025-09 融资 EUR1.7bn；2026 推主权 AI | EUR11.7bn 投后 | 未定 | 欧洲主权 AI 稀缺，但规模落后 |
| **字节跳动/豆包** | 消费分发、广告和模型一体化 | 最新可靠估值/模型收入未公开 | 未定 | 中国最强未上市映射之一 |
| **DeepSeek** | 低成本开源模型，财务未公开 | 无可靠官方估值 | 未定 | 技术冲击大，可投资性证据不足 |
| **Moonshot/Kimi** | 中国长上下文和代理产品 | 最新可靠估值/收入未公开 | 未定 | 高增长，披露不足 |
| **Cohere** | 企业与主权 AI | 最新财务未公开 | 未定 | 企业定位清晰，规模证据不足 |

### 第一层淘汰记录

| 淘汰组 | 公司 | 理由 |
|---|---|---|
| 卖铲人，不是模型平台 | NVIDIA、AMD、Arm、Samsung、ASML | 受益确定，但收益来自硬件供需，已属于算力漏斗；不能拿芯片收入冒充模型经济性 |
| AI 应用/工作流，不是基础模型 | Palantir、Salesforce、ServiceNow、Snowflake、Adobe、SAP、IBM、金山办公、万兴、Siemens | 模型可替换，核心护城河在数据与工作流；应放入 AI 应用赛道 |
| 主题暴露过低 | 腾讯、三六零、Kakao | 集团价值仍由游戏、广告、安全或通讯主业决定 |
| 规模/盈利证据不足 | 商汤、智谱、MiniMax、第四范式、金山云、科大讯飞、拓尔思、C3.ai | 至少估值、ROE、现金流三项中的两项失败或未披露 |
| 算力租赁高杠杆 | CoreWeave | 高纯度不等于高质量；资本开支、债务和客户集中度超过模型护城河 |

## 四、第二层：五项硬指标粗筛（10 家）

标准：合理 PE 或高成长 PEG <1.5；ROE >15% 或趋势改善；OCF 为正且 OCF/净利 >70%；负债率 <60%；护城河至少三星。股权浮盈造成的净利润必须正常化，不能直接拿 headline PE。

| 公司 | 估值 | ROE | OCF/净利 | 负债率 | 护城河 | 结论 | 留/弃理由 |
|---|---|---:|---:|---:|:---:|---|---|
| Microsoft | US$510.12；FY26 PE 28.42x | 34.04% | 136.77% | 41.67% | ★★★★★ | **留** | 五项通过；AI 资本开支与 OpenAI 依赖是主要折价项 |
| Alphabet | US$342.48；GAAP PE 失真，正常化约 30x上下估 | >20%正常化估 | >70%正常化估 | 30.53% | ★★★★★ | **留黄** | 业务强，价格只算合理；股权浮盈不能当经常利润 |
| Meta | US$610.68；TTM PE 约 22.3x | 35.63%年化 | 150.37% | 41.95% | ★★★★ | **留黄** | 财务过关，但 Q2 FCF 仅 US$0.784bn，资本开支陡增 |
| Amazon | US$258.90；GAAP PE 被 Anthropic 浮盈扭曲 | ROE失真 | 119.31%但净利失真 | 49.66% | ★★★★★ | **留黄** | AWS/AI 商业化强；TTM FCF -US$7.6bn，不能按表面 PE 通过 |
| Alibaba | HK$111.40；市值 HK$2.22tn | <15%，趋势改善 | FY26 74.6% | <60% | ★★★★ | **留黄** | 云增 45%，但集团利润承压且新配股稀释 |
| Baidu | US$95.58；低估值 | <15% | Q2 OCF转正 | 37.2% | ★★★ | **留黄** | AI 云增 50%，但 Q2 FCF -RMB7.95bn，盈利质量未过关 |
| SoftBank Group | NAV 折价法，PE 无效 | 波动，PE无效 | 投资控股口径不适用 | LTV 管理而非资产负债率 | ★★★ | **留黄** | OpenAI 映射最直接；桥贷与单一资产集中度高 |
| Oracle | US$154.04；估值需等最新年度口径 | 高杠杆型 ROE | OCF为正 | 债务压力偏高 | ★★★★ | **弃** | Stargate/OCI 暴露高，但 90 日股价从 US$248.15 跌至 US$154.04，需先核合同回报与融资 |
| CoreWeave | US$84.56；亏损 | 负 | 不稳定 | 高 | ★★★ | **弃** | 只过主题纯度与部分规模壁垒 |
| OpenAI | 私募 P/S 约 21.3x | 未披露 | 未披露 | 未披露 | ★★★★★ | **观察** | 只过护城河；招股书前不满足价值投资信息标准 |

严格规则下直接通过的是微软。Alphabet、Meta、Amazon、Alibaba、Baidu、SoftBank 均因正常化估值、FCF、ROE或杠杆存在一项关键缺口而“留黄”，不是降低标准后的强买名单。

## 五、第三层：八家精细分析

### 5.1 Microsoft（MSFT）

**商业模式**：向企业和个人出售云、软件订阅与开发工具，OpenAI 同时贡献股权价值、模型供给、Azure API 和 Copilot 能力。FY2026 收入 US$331.8bn、营业利润 US$155.2bn、净利 US$133.7bn；Azure 年收入首次超过 US$100bn，增长 41%。OCF US$182.9bn，但资本开支 US$115.9bn，AI 正把高毛利软件公司部分改造成重资产公用设施。护城河来自企业身份、数据、渠道和开发者工作流，不只来自 GPT。风险是 OpenAI 多云化、自研 MAI 与 OpenAI 关系竞合、算力回报下降。US$510.12 对应 28.42 倍 FY26 PE，合理偏贵。**进入终选核心，但不追高。**

### 5.2 Alphabet（GOOGL）

**商业模式**：搜索广告提供现金，Gemini、Cloud、TPU、Workspace 和 Android 形成全栈模型分发。Q2 收入 US$119.8bn、增长 24%，Cloud 收入 US$24.8bn、增长 82%，Gemini App 月活 9.5 亿。反面是 Q2 US$98.0bn 其他收益主要来自股权浮盈，导致 GAAP EPS 和 PE 失真；半年资本开支 US$80.6bn，Q2 FCF 转负。护城河是全球搜索意图、YouTube、Android、TPU 和 DeepMind 的组合。风险是 AI 搜索蚕食广告单位经济、监管拆分与资本开支。正常化约 30 倍上下只算合理。**进入终选，用来对冲 OpenAI 单一赢家假设。**

### 5.3 Amazon（AMZN）

**商业模式**：AWS 出售计算、芯片和模型平台，同时持有 Anthropic，并承诺向 OpenAI 投资 US$50bn。Q2 AWS 收入 US$42.2bn、增长 37%，AWS AI 业务年化收入超过 US$25bn；但 TTM FCF 为 -US$7.6bn，资本开支大增。Q2 净利包含约 US$53.4bn 的 Anthropic 相关非经营收益，表面 PE 没有分析价值。优势是 Bedrock 多模型分发、Trainium 成本控制和企业渠道；风险是同时资助互相竞争的模型、基础设施回收期过长及零售业务稀释。**保留观察，不进终选：OpenAI 敞口真实，但价格与现金流不够干净。**

### 5.4 Meta Platforms（META）

**商业模式**：广告现金流补贴模型研发，AI 首先提高推荐和广告效率，企业模型收入尚未成为独立分部。Q2 收入 US$60.8bn、增长 28%，但成本增长 55%、营业利润下降 8%；季度 OCF US$31.9bn，FCF 仅 US$0.784bn，2026 capex 指引 US$130-145bn。社交图谱与 36 亿日活构成分发护城河，开源策略则削弱模型直接定价权。风险是资本开支失控、开源收益归外部、治理权集中。TTM PE 约 22.3 倍不贵，但“便宜”建立在广告利润可持续上。**第一观察，不进终选。**

### 5.5 Alibaba（09988/BABA）

**商业模式**：电商现金流支撑 Qwen、阿里云与 AI 应用，模型收入通过云计算、广告效率和消费入口兑现。2026 年 6 月季度集团收入约 US$39.6bn、增长 9%；AI Cloud and Compute Services 收入 US$7.1bn、增长 45%，调整 EBITA 增长 133%。反面是 FY2026 OCF 同比下降 53%，6 月季度非 GAAP 净利下降 38%，8 月又公布 HK$80bn 配股，资本纪律必须打折。Qwen 开源生态、中文数据、电商与钉钉分发是护城河。**中国模型首选观察，但不进入本次 OpenAI 主题终选。**

### 5.6 Tencent（00700）

**商业模式**：游戏、广告与支付现金流支撑混元和元宝，AI 主要提高现有业务效率。Q2 收入约 RMB204.8bn、增长 11%，利润增长接近停滞；市场关注点转向 AI 投入对 FCF 的挤压。微信是中国最强分发入口之一，管理层却没有把基础模型单列成可验证收入。买腾讯主要是在买社交、游戏和支付，不是买 OpenAI 同类平台。**公司质量高，主题纯度低，退出精析。**

### 5.7 Baidu（BIDU/09888）

**商业模式**：搜索广告供血，AI 云、GPU 云、文心应用和自动驾驶寻找第二曲线。Q2 AI Cloud Infra 收入 RMB7.3bn、增长 50%，GPU Cloud 增长 283%；集团 OCF RMB3.44bn，但 capex RMB11.39bn，FCF -RMB7.95bn。优势是中文搜索数据、PaddlePaddle 和企业云；反面是消费入口弱于字节/腾讯，资本开支先于现金回报。低市值提供期权，低 ROE 与负 FCF说明它还不是巴菲特型资产。**观察，不买便宜陷阱。**

### 5.8 SoftBank Group（9984.T）

**商业模式**：投资控股，通过 OpenAI、Arm 与 AI 基础设施提升 NAV。软银 2026 年追加承诺 US$30bn，完成后累计投入预计 US$64.6bn、约持有 OpenAI 13%；按 US$852bn 估值机械计算权益价值约 US$110.76bn，但这不是可立即变现净值。第三笔 US$10bn 计划 10 月交割，投资使用桥贷，OpenAI 估值回撤会同时打击 NAV 与融资能力。优势是直接权益稀缺；风险是杠杆、孙正义关键人、估值集中和税负。**进入终选期权，只在足够 NAV 折价且 LTV 可控时配置。**

## 六、第四层：终选三家四大师分析

### 6.1 Microsoft：核心仓

**段永平视角**：它卖的不是“某个模型”，而是企业持续使用的数字基础设施。客户已经把身份、文档、代码、数据库和协作放在微软体系里，模型只是把这些存量资产重新货币化。好生意的关键是重复收费、低流失和交叉销售。管理层主动建设 MAI、同时保留多模型目录，说明它知道不能把命门完全交给 OpenAI。反面是资本开支从软件式增长转向电力、机房和芯片式增长，边际资本回报会下降。

**巴菲特视角**：

| 护城河 | 强度 | 证据 |
|---|:---:|---|
| 品牌/定价权 | ★★★★★ | Microsoft 365、Azure、GitHub 已成为企业标准采购 |
| 转换成本 | ★★★★★ | 身份、合规、数据、代码和工作流深度绑定 |
| 网络效应 | ★★★★ | Windows/Office/GitHub 开发者与企业生态互相增强 |
| 规模效应 | ★★★★★ | FY26 Azure 收入超 US$100bn，全球数据中心摊薄模型成本 |
| 技术/IP | ★★★★★ | OpenAI IP 权利延至 2032，并有自研 MAI 与 Maia 芯片 |

十年后护城河大概率仍在，即使 OpenAI 不是赢家，微软也可替换模型。安全边际来自企业分发，而不是把 2025 年披露的 27% OpenAI 持股机械外推到 2026 年；新融资后当前持股比例未获官方重述，必须等下一份披露。

**芒格视角**：失败路径一是 AI capex 回报低于折旧；二是 OpenAI 将非 API 产品迁往其他云，微软只剩昂贵基础设施；三是 Copilot 席位增长但使用深度不足。聪明人不买的理由是 US$3.79tn 市值已反映大量成功。三年悲观情景按 EPS 年增 6%、20 倍 PE，目标约 US$427.6，较现价低 16.2%。

**李录视角**：企业知识工作进入“自然语言调用软件”的范式变化，类似 GUI 与互联网叠加。赢家未必只有一个模型，但企业控制面可能更集中。微软最接近“无论哪个模型赢都收租”的位置。

**推荐度**：★★★★☆；**仓位类型**：核心；**主题仓位**：45%-55%；**价格纪律**：US$450 以下开始有吸引力，US$420 附近更安全，US$550 以上不追；**监测**：Azure 增速、Copilot 付费席位及使用深度、AI capex/增量营业利润、OpenAI 协议变化。

### 6.2 Alphabet：成长型对冲

**段永平视角**：本质是用最强的信息分发入口卖广告，再把算力、模型和数据工具卖给企业。Gemini 的价值不是聊天机器人排名，而是能否提高搜索次数、广告转化和 Cloud 收入。Q2 已出现商业化证据。反面是搜索答案化可能减少网页点击，监管也可能拆掉默认分发优势。

**巴菲特视角**：

| 护城河 | 强度 | 证据 |
|---|:---:|---|
| 品牌/定价权 | ★★★★★ | 全球搜索意图与广告主预算入口 |
| 转换成本 | ★★★★ | Workspace、Cloud、Android 和数据工具形成企业粘性 |
| 网络效应 | ★★★★★ | 查询、内容、广告主和开发者数据飞轮 |
| 规模效应 | ★★★★★ | 自研 TPU、全球数据中心、Gemini 每分钟 220 亿 API token |
| 技术/IP | ★★★★★ | DeepMind、Gemini、TPU 全栈，减少对单一供应商依赖 |

十年后信息检索仍在，但入口形态会变。安全边际不能看被 SpaceX/Anthropic 浮盈压低的 headline PE，必须看正常化经营利润。当前价格约在正常化 30 倍上下，质量高、折价不深。

**芒格视角**：失败路径是 AI 搜索单位成本上升而广告收入被蚕食、监管强制分发改变、US$195-205bn 年 capex 不能形成相称现金流。三年悲观情景按正常化 EPS US$10.47、年增 8%、20 倍 PE，目标约 US$263.8，较现价低 23.0%。

**李录视角**：AI 是计算界面变化，Google 同时拥有研究、芯片、云和十亿级入口，类似电气化时代既有电厂又有终端网络。它不是 OpenAI 映射，而是“OpenAI 不是唯一赢家”的保险。

**推荐度**：★★★★☆；**仓位类型**：卫星/竞争对冲；**主题仓位**：25%-35%；**价格纪律**：US$300 以下再积极，US$265 附近才有明显悲观安全边际；**监测**：AI 搜索商业查询、Cloud 利润率、正常化 FCF、capex 指引、反垄断裁决。

### 6.3 SoftBank Group：OpenAI 股权期权

**段永平视角**：软银不是好生意本身，而是带杠杆的资产配置器。买它是在押孙正义能以合理融资成本长期持有 OpenAI 与 Arm。OpenAI 若成功，NAV 弹性巨大；若私募估值回撤，集团没有软件订阅现金流替投资者兜底。

**巴菲特视角**：

| 护城河 | 强度 | 证据 |
|---|:---:|---|
| 品牌/定价权 | ★★ | 投资品牌强，但融资定价受市场周期约束 |
| 转换成本 | ★ | 投资者可买其他科技资产 |
| 网络效应 | ★★★ | OpenAI、Arm、Stargate 产业关系形成资源网络 |
| 规模效应 | ★★★★ | 能筹集数百亿美元参与稀缺轮次 |
| 技术/IP | ★★★ | 权益来自被投公司，集团自身技术壁垒有限 |

所谓安全边际只有两个：软银市值对可核 NAV 的折价，以及集团 LTV。按 13% 乘 US$852bn 得到 US$110.76bn 只是毛权益，不可忽略尚未交割资金、债务、税、少数股东和估值流动性折扣。

**芒格视角**：失败路径是 OpenAI IPO 定价低于私募轮、桥贷再融资成本上升、单一资产集中叠加孙正义关键人风险。聪明人不买的理由很直接：用上市控股公司包装私募高估值，并没有创造安全边际。

**李录视角**：若 OpenAI 成为全球智能操作层，13% 左右权益具有文明级非线性；若模型商品化，资本提供者承担最大损失。它是期权，不是复利核心。

**推荐度**：★★★☆☆；**仓位类型**：期权；**主题仓位**：5%-10%；**价格纪律**：仅当经债务和税调整后的可核 NAV 折价至少 30%，且 LTV 明显低于公司 25%常态上限时考虑；**监测**：OpenAI IPO 招股书、第三笔投资交割、SBG LTV、Arm 市值、桥贷置换。

## 七、组合、估值与操作信号

| 公司 | 类型 | 推荐度 | 建议主题仓位 | 核心逻辑 | 关键风险 |
|---|---|:---:|---:|---|---|
| Microsoft | 核心 | ★★★★☆ | 45%-55% | 企业分发、Azure、OpenAI 权利与自研模型同时存在 | capex 回报、伙伴多云化 |
| Alphabet | 卫星/对冲 | ★★★★☆ | 25%-35% | Gemini+TPU+Cloud+搜索，全栈对冲 OpenAI 单押 | 正常化估值高、搜索被自我蚕食 |
| SoftBank Group | 期权 | ★★★☆☆ | 5%-10% | 上市市场最直接的 OpenAI 大额股权映射之一 | 杠杆、NAV 波动、私募估值回撤 |
| 现金/短债 | 等待 | — | 10%-20% | 等估值或招股书提供更清晰赔率 | 错过继续上涨 |

### 三情景估值复算

| 公司 | 基准 | 乐观 | 中性 | 悲观 |
|---|---|---:|---:|---:|
| Microsoft | FY26 EPS US$17.95，三年 | 18%增速/32x：US$943.8 | 12%/27x：US$680.9 | 6%/20x：US$427.6 |
| Alphabet | 正常化 EPS US$10.47估，三年 | 22%增速/32x：US$608.4 | 15%/27x：US$429.9 | 8%/20x：US$263.8 |

Alphabet 的 US$10.47 是剔除重大股权浮盈后的估计口径，不是公司披露的 non-GAAP EPS；因此情景只用于纪律，不是目标价承诺。

### OpenAI IPO 观察门槛

- **可研究，不等于可买**：以年化收入 US$40bn 计，US$852bn 对应约 21.3x P/S；US$1tn 对应 25x P/S。
- **必须看到**：按消费者/API/企业拆分的收入，云渠道收入确认口径，毛利率，推理与训练成本，算力最低采购承诺，SBC，经营现金流，客户留存与集中度。
- **价格纪律**：若无正向经营现金流和稳定毛利，不以超过 15x 可比口径收入承接 IPO；若招股书证明高毛利、净收入留存和 FCF 路径，再重估。
- **证伪信号**：企业收入占比停止提升、API token 增长低于单位价格下降、前沿能力连续 12 个月无差异、算力承诺增长快于收入。

## 八、ETF 替代与行业位置

| ETF | 适合谁 | 主要问题 |
|---|---|---|
| Roundhill Generative AI & Technology ETF `CHAT` | 接受主动管理、希望集中生成式 AI | 年换手率高，持仓混入芯片和软件，不能纯映射 OpenAI |
| Global X AI & Technology ETF `AIQ` | 要求全球、规则化分散 | 88 只左右持仓，OpenAI 私股不在其中，主题被稀释 |
| Global X AI & Innovative Technology Active ETF `3006.HK` | 需要港股交易时段的全球 AI 敞口 | 规模、流动性与费率需下单前复核 |

**行业阶段：商业化扩张中期，资本周期偏后段。** 需求仍在加速：OpenAI 年化收入超过 US$40bn 的最新口径、Anthropic 超 US$65bn 的报道口径、Google Cloud +82%、AWS +37%、阿里 AI 云 +45%。反面同样明确：四家 hyperscaler 的 capex 激增，Meta、Alphabet、Amazon 的季度或 TTM FCF 已受明显压制。技术采用仍早，股票定价与资本投入却不早。

无法获得统一的“全球基础模型行业 PE/PB 历史分位”；用 AIQ 代替会混入硬件和应用，属于错误精度。本报告以终选公司正常化估值、ETF 持仓和资本开支周期替代，行业估值充分度评为 C。

## 九、信息充分度与待更新

| 维度 | 等级 | 说明 |
|---|:---:|---|
| 上市公司财务数据 | A | 终选核心财务来自公司 IR/SEC，行情锁定 9 月 3 日 |
| OpenAI/私企财务 | C | 估值官方，收入多为公司口径或媒体转述；无完整三表 |
| 估值时效性 | B | 美股和主要港股价格已锁定；跨市场 PE 无统一正常化口径 |
| 行业格局 | B | 头部公司与产品覆盖充分；30/90 日全球排名不能完整复现 |
| 管理层与治理 | B | 上市公司披露充分；OpenAI PBC 与私企治理仍需招股书 |

待更新数据：OpenAI S-1 与 IPO 时间；微软在 2026 融资后的实际持股比例；软银第三笔 US$10bn 是否于 10 月交割及最新 LTV；OpenAI/Anthropic 云渠道收入确认差异；Alphabet 股权浮盈正常化；阿里 HK$80bn 配股完成后的每股口径；所有终选公司的下一季度 capex 与 FCF。

## 十、数据复算记录

- Microsoft PE：`510.12 / 17.95 = 28.42x`
- Microsoft ROE：`133749 / ((343479 + 442387) / 2) = 34.04%`
- Microsoft OCF/净利：`182935 / 133749 = 136.77%`
- Microsoft 负债率：`315989 / 758376 = 41.67%`
- Alphabet 负债率：`281503 / 921983 = 30.53%`
- Meta H1 年化 ROE：`42621 / ((217243 + 261221) / 2) * 2 = 35.63%`
- Meta H1 OCF/净利：`64088 / 42621 = 150.37%`
- Meta 负债率：`188735 / 449956 = 41.95%`
- Amazon TTM OCF/净利：`161403 / 135281 = 119.31%`，但净利含 Anthropic 浮盈，不能直接解释经营质量
- OpenAI 私募 P/S：`852 / 40 = 21.30x`
- SoftBank 13% OpenAI 毛权益：`852 * 13% = US$110.76bn`

以上算术均由 `python3 tools/financial_rigor.py` 复算；输入单位分别为公司披露的百万美元、十亿美元或每股美元。

## 十一、资料来源

### 官方公司与监管披露

- OpenAI：[2026 年 3 月融资](https://openai.com/index/accelerating-the-next-phase-ai/)、[与 Amazon 合作及投资](https://openai.com/index/amazon-partnership/)、[与 Microsoft 协议](https://openai.com/index/next-chapter-of-microsoft-openai-partnership/)、[公司结构](https://openai.com/our-structure/)
- Microsoft：[FY2026 Q4 与全年业绩](https://www.microsoft.com/en-us/investor/earnings/fy-2026-q4/press-release-webcast)
- Alphabet：[2026Q2 SEC Exhibit 99.1](https://www.sec.gov/Archives/edgar/data/1652044/000165204426000066/googexhibit991q22026.htm)
- Meta：[2026Q2 业绩](https://investor.atmeta.com/investor-news/press-release-details/2026/Meta-Reports-Second-Quarter-2026-Results/default.aspx)
- Amazon：[2026Q2 业绩](https://ir.aboutamazon.com/news-release/news-release-details/2026/Amazon-com-Announces-Second-Quarter-Results/default.aspx)
- Alibaba：[2026 年 6 月季度 SEC 披露](https://www.sec.gov/Archives/edgar/data/1577552/000110465926099220/tm2623667d1_ex99-1.htm)、[FY2026 年报](https://www.sec.gov/Archives/edgar/data/1577552/000119312526274928/d133513dex991.pdf)
- Baidu：[2026Q2 业绩](https://ir.baidu.com/news-releases/news-release-details/baidu-announces-second-quarter-2026-results)
- Tencent：[2026 年中期报告入口](https://www.tencent.com/investors/announcements/)
- SoftBank：[2026 年追加投资条款](https://group.softbank/en/news/press/20260227)、[OpenAI 风险披露](https://group.softbank/en/ir/investors/management_policy/risk_factor)
- Anthropic：[Series G](https://www.anthropic.com/news/anthropic-raises-30-billion-series-g-funding-380-billion-post-money-valuation)、[Series H](https://www.anthropic.com/news/series-h)
- xAI：[Series E](https://x.ai/news/series-e)、[并入 SpaceX](https://x.ai/news/xai-joins-spacex)
- Mistral：[Series C](https://mistral.ai/news/mistral-ai-raises-1-7-b-to-accelerate-technological-progress-with-ai/)
- NVIDIA：[FY2027 Q2](https://investor.nvidia.com/news/press-release-details/2026/NVIDIA-Announces-Financial-Results-for-Second-Quarter-Fiscal-2027/default.aspx)

### 行情、ETF 与二次交叉

- Nasdaq API：2026-09-03 收盘价、市值、成交量及 30/90 日历史行情，访问模板 `https://api.nasdaq.com/api/quote/{ticker}/summary?assetclass=stocks`
- 东方财富公开行情：腾讯、阿里港股 2026-09-04 盘前快照，仅用于市值交叉
- [AIQ 官方持仓与行情](https://www.globalxetfs.com/funds/aiq)
- [CHAT 2026 年度股东报告（SEC）](https://www.sec.gov/Archives/edgar/data/1924868/000199937126014632/chat-ncsr_043026.htm)
- [OpenAI 年化收入口径比较（Axios，2026-09-03）](https://www.axios.com/2026/09/03/anthropic-and-openais-revenue-chasm-explained)
- [OpenAI 秘密递交 IPO 文件（AP，2026-06-08）](https://apnews.com/article/c7583994426b1b097120786d6a0b8308)

## 十二、偏误自查

- **龙头偏好**：未因资料多直接选大厂；Meta、Amazon 虽强，仍因 FCF 和利润失真退出终选。
- **故事偏好**：OpenAI 模型领先不等于 US$852bn 有安全边际；缺三表就不通过硬筛。
- **上市偏好**：单列 OpenAI、Anthropic、xAI、Mistral、字节、DeepSeek、Moonshot、Cohere。
- **英文偏好**：覆盖阿里、腾讯、百度、商汤、智谱、MiniMax、第四范式和 A 股公司；但中国私企财务披露不足，明确降级。
- **当下偏好**：保留 Baidu、Alibaba 的趋势改善，但没有用趋势替代现金流和 ROE。

## 十三、数据抽检准出记录

执行命令：`python3 tools/report_audit.py extract --report reports/OpenAI-funnel-20260904.md --ratio 0.15 --seed 42 --dry-run`。工具从 55 个数据点抽取 9 个样本，其中 6 个属于可核验外部事实：OpenAI 估值、Mistral 估值、Microsoft 收盘价、Alphabet 负债率、Meta 年化 ROE、Gemini API token 处理量；均经两来源交叉核验，**有效样本 6/6 通过，准出**。

其余 3 个样本分别是“至少三项失败”的规则描述、70% 的筛选阈值和 Microsoft 中性情景 12% 增速假设，均不是外部财务数据，按审计工具规则跳过。准出只证明抽样数字和算术一致，不证明情景假设、护城河评分或投资结论必然正确。
