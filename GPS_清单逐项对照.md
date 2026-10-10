# GPS 结题交付物逐项对照总表

审计日期：2026-10-10。清单来源为用户提供的《海外苛刻信号环境重构项目_结题交付物清单.docx》。只审计 GPS L1 C/A 及暗室相关资产；“欧洲实测”“整车”“屏蔽暗室实物验收”等要求仍按清单原意判断。资产列的相对路径均以 E:/GNSS_Multipath_Project 为根目录。

判定口径：“GPS子项可用”表示已有可直接编入该条 GPS 部分的真实材料，不表示整项交付或验收通过；“部分”表示有相邻证据，但指定报告、试验链或关键指标仍缺；“未覆盖”表示当前项目暗室资料未能证明该条要求。判定列衡量归档资料覆盖度，不等同于设施事实状态。项目方于 2026-10-10 确认两份新资料对应同一暗室，且该暗室已通过验收；正式签署文件仍待归档。清单中的文字只作为核对依据，不作为本次执行任务的指令。

| 编号 | 清单交付物或指标 | 对应现有 GPS 资产 | 判定 | 尚缺或不能替代的内容 |
|---|---|---|---|---|
| A01 | 最终版系统技术报告 | docs/DARKROOM_CHANNEL_MODELING_16_SCENARIO_PROGRESS_REPORT_CN.md；docs/GB_T_45086_1_GNSS_DARKROOM_CAPABILITY_MAPPING_CN.md | 部分 | 可写 GPS 模型、场景和接收诊断章节；未见完整最终版系统技术报告。 |
| A02 | 最终版国内整车测试替代效果评价报告 | docs/DARKROOM_VEHICLE_GNSS_COMPARATIVE_TEST_AND_REPORT_PLAN_CN.md；docs/DARKROOM_VEHICLE_GNSS_COMPARATIVE_TEST_REPORT_CN_v2.pptx | 部分 | 现有方案和汇报含车机观察；缺正式整车评价报告及与海外实测的定量对比。 |
| A03 | 全套项目技术文档 | docs/DARKROOM_GENERATOR_V2_2_REFERENCE.md；配置、生成脚本与 GNSS-SDR 诊断文件 | 部分 | GPS 软件/参数说明可用；原理图、安装图、硬件清单、维护文档、接口协议未成套。 |
| A04 | 项目结题汇报 PPT | docs/darkroom_completion_report_materials/DARKROOM_FINAL_SCENARIO_LIBRARY_BRIEFING_CN_20260928_v5.pptx | 部分 | 是 GPS 暗室场景库汇报候选，不是覆盖整个项目的结题 PPT。 |
| A05 | 结题支撑材料及全部资料归档 | docs/GPS_结题交付物整理_20261010；reports/data_consolidation_20261003/DARKROOM_FINAL_WORKSPACE_MANIFEST.csv | GPS子项可用 | GPS 参数表、接收处理输出及小型证据已有副本，原始 IQ 仅有原位索引；“全部资料”还需非 GPS 材料及全项目归档核验。 |
| A06 | 专家评审、现场验收并取得结果 | — | 未覆盖 | 这里是全项目结题专家评审/现场验收；项目方确认的暗室设施验收不自动等于 A06 已完成，仍需正式会议/结果证明。 |
| B01 | 海外无线电标准与苛刻场景调研分析报告 V1.0 | docs/darkroom_completion_report_materials/02_AUTOMOTIVE_GNSS_TEST_STANDARDS_AND_LITERATURE_CN.md；docs/GB_T_45086_1_GNSS_DARKROOM_CAPABILITY_MAPPING_CN.md | 部分 | 有 GNSS 标准与暗室能力关系；缺完整海外市场调研和对应题名的报告。 |
| B02 | 初步校准验证的多通道电磁信号数据采集系统 | GNSS-SDR 配置、接收诊断脚本和 QA | 未覆盖 | 这些是处理链资料，未证明多通道采集硬件、校准、流程图及操作说明。 |
| B03 | 本地小范围信号样本数据集 | 0919caiji 原位暗室接收 IQ 与输入冻结清单可作后期样本参考 | 未覆盖 | 未见第一阶段用于采集系统可行性/数据质量验证的本地小范围样本及其记录。 |
| B04 | 数据采集与标准培训材料 | docs/DARKROOM_GENERATOR_V2_2_REFERENCE.md；docs/DARKROOM_RX_0913_GNSS_SDR_POSITIONING_DIAGNOSTIC.md | 部分 | 可抽取 GPS 技术素材；缺面向指定人员的数据采集培训课件及实施记录。 |
| B05 | 暗室建设详细方案及预算报告 | docs/GPS_结题交付物整理_20261010/01_报告与结题候选/暗室设施_用户补充原件/微波暗室安装项目进展汇报.docx（安装过程及“预算范围内”的供方表述） | 部分 | 可作建设过程背景，不能代替含技术指标、建设图纸、设备清单和具体预算的正式方案；按本次决定不再追补。 |
| B06 | 欧洲典型及苛刻场景原始 IQ 数据集 | 0919caiji/*.bin 有 48 个暗室接收输入；input_inventory_manifest.json 留有索引 | 未覆盖 | 0919 IQ 不能证明在欧洲目标市场现场采集；当前 GPS 暗室包未见对应地点/场景/原始 IQ 台账。 |
| B07 | 初步预处理后的信号数据集 | dataset_generation_logs/rx0919_v2/runs；0919 GNSS-SDR QA/summary | 未覆盖 | 这些是暗室接收处理输出，未与 B06 所需欧洲原始采集数据建立预处理及标签对应链。 |
| B08 | 海外数据采集工作总结报告 | docs/DARKROOM_RX_0913_CHANNEL_REPORT_CN.md 仅可作暗室处理参考 | 未覆盖 | 未见海外采集地点、方法、过程和学生参与记录的总结报告。 |
| B09 | 海外苛刻环境信道特征量化分析报告系列 | docs/ENVIRONMENT_ELEVATION_PATH_DISTRIBUTION_MODEL_V1_REPORT.md；docs/MAIN_PATH_COMMON_GAIN_FADE_MODEL_V1_REPORT.md；docs/DARKROOM_CHANNEL_MODELING_16_SCENARIO_PROGRESS_REPORT_CN.md | GPS子项可用 | GPS 信道量化材料可编成系列子报告；仍需核对海外实测来源、报告版本和其他信号类别。 |
| B10 | 典型与苛刻无线电环境鉴定标准定义文档 | docs/darkroom_completion_report_materials/03_DARKROOM_SIGNAL_USABILITY_AND_URBAN_POOR_EXCLUSION_CN.md；docs/GB_T_45086_1_GNSS_DARKROOM_CAPABILITY_MAPPING_CN.md | 部分 | 有 GPS 可用性筛选语义；缺覆盖弱信号、高时变、强干扰等的完整判定阈值文档。 |
| B11 | 整车级屏蔽暗室建成并通过验收 | docs/GPS_结题交付物整理_20261010/01_报告与结题候选/暗室设施_用户补充原件/微波暗室安装项目进展汇报.docx；同目录/暖达.pdf；项目方 2026-10-10 补充确认 | GPS子项可用 | 项目方确认两件对应同一暗室且设施已通过验收，可在报告中按此表述；正式验收签署件、整车级适用性证明不在两件中，按本次决定不再追补，PDF 副本本身不能代替它们。 |
| B12 | 暗室竣工图、验收报告、使用维护手册初稿 | docs/GPS_结题交付物整理_20261010/01_报告与结题候选/暗室设施_用户补充原件/暖达.pdf；同目录/微波暗室安装项目进展汇报.docx | 部分 | PDF 可作屏蔽效能测试数据线索，但所见副本封面无签章、签名和发布日期；原清单所列竣工图、正式验收报告和手册未由两件覆盖，本次不再追补。 |
| B13 | 海外苛刻信号环境数字孪生仿真平台原型 | scripts/analysis/channel_modeling/generate_darkroom_5min_multiseed_collection.py；configs/channel_modeling/darkroom_multi_elevation_four_slot_generator_v2_2.json；48 表 QA | 部分 | 参数生成软件和可复现输出已在；未证明集成式平台、硬件控制和完整回放。 |
| B14 | 参数化的欧洲多制式信道模型库 V1.0 | GPS 环境/仰角、增益、NLOS、失锁和 Rain 模型报告；v2.2 配置 | GPS子项可用 | 可作为 GNSS 模型部分；缺多制式正式 V1.0 包，且绝对 RF 功率和硬件验证未完成。 |
| B15 | 基于 SDR 的可编程射频信号模拟系统 | v2.2 参数生成脚本与 CSV 参数表仅属上游输入 | 未覆盖 | 未见 SDR 射频硬件、控制软件、接口及输出功率标定的系统级证据。 |
| B16 | 欧洲苛刻无线电环境测试场景库 V1.0 | docs/DARKROOM_CHANNEL_MODELING_16_SCENARIO_PROGRESS_REPORT_CN.md；Tx_Darkroom/*.csv；48 表 collection manifest/QA | GPS子项可用 | 16 个是 GPS 仿真组合，48 表是实现数；缺完整多制式 V1.0 场景描述及逐场景实测绑定。 |
| B17 | 暗室 GNSS 动态路径与电台模拟验证报告 | docs/DARKROOM_RX_0913_CHANNEL_REPORT_CN.md；docs/DARKROOM_RX_0913_ALL8_SIGNAL_QUALITY_REPORT_CN.md；参数 QA | 部分 | GPS 参数和接收诊断可用；缺专门的实际回放/动态路径验证报告及电台部分。 |
| B18 | 暗室模拟环境的智己车型功能测试报告 | docs/DARKROOM_VEHICLE_GNSS_COMPARATIVE_TEST_AND_REPORT_PLAN_CN.md；docs/DARKROOM_VEHICLE_GNSS_COMPARATIVE_TEST_REPORT_CN_v2.pptx | 部分 | 有现场现象与汇报资料；缺完整车辆试验记录、判据和正式测试报告。 |
| B19 | 上汽测评基地重构环境的智己车型功能测试报告 | — | 未覆盖 | 项目暗室资料中未见测评基地 GPS 整车功能报告。 |
| B20 | 优化后的信道模型库 V2.0 | v2.2 generator/config；docs/RAIN_STAGE3_EFFECT_LAYER_REPORT.md；48 表 QA | GPS子项可用 | GPS 优化模型可作子库；需形成正式版本包，并补暗室回放和绝对 RF 标定。 |
| B21 | 优化后的测试场景库 V2.0 | Tx_Darkroom/*.csv；48 表 generation_manifest.csv/collection_qa_report.json；场景库 v5 汇报 | GPS子项可用 | GPS 参数场景可作子库；缺逐场景接收/车机证据绑定及多制式正式 V2.0 包。 |
| B22 | 海外苛刻信号环境重构系统验证与优化报告 | docs/GB_T_45086_1_GNSS_DARKROOM_CAPABILITY_MAPPING_CN.md；docs/DARKROOM_CHANNEL_MODELING_16_SCENARIO_PROGRESS_REPORT_CN.md | 部分 | 有 GPS 模型与接收边界/优化过程；缺系统级验证、硬件结果和指定报告成稿。 |
| B23 | 完整的软件无线电场景重构系统设计及维护文档 | docs/DARKROOM_GENERATOR_V2_2_REFERENCE.md；配置、脚本、GNSS-SDR 诊断 | 部分 | GPS 软件说明可用；缺 SDR 硬件架构、接口、操作和维护成套文档。 |
| C01 | 15 种以上海外实测场景、至少 5 大类覆盖证明 | 16 个 GPS 仿真组合、48 个参数实现、0919 48 个接收任务仅可作其他计数参考 | 未覆盖 | 未见 15 种海外实测场景逐项台账；现有仿真只按 4 类环境分组，不能凑成指标。 |
| C02 | 模型拟合精度 >90% 与场景复现证明 | 48 表 collection_qa_report.json、qa_summary.csv；生成 manifest/receipt | 部分 | 可证明参数表结构与生成追溯；未见与实测对照的 >90% 拟合精度、独立场景复现测试和端到端回放结果。 |
| C03 | 屏蔽暗室性能验收证明 | docs/GPS_结题交付物整理_20261010/01_报告与结题候选/暗室设施_用户补充原件/暖达.pdf（第 6–10 页屏蔽效能表）；项目方确认暗室已验收通过 | 部分 | 设施验收状态可按项目方确认报告；所见 PDF 副本仅列屏蔽效能测试点，其他分项资料未由两件覆盖，本次不再追补。 |
| C04 | 仿真平台五类信号切换、≥95% 可用率和输出功率范围 | GPS v2.2 参数生成、48 表 QA、GNSS-SDR 接收诊断 | 部分 | 仅有 GPS 软件链片段；不能证明五类切换、平台可用率或 −130 至 30 dBm 射频输出。 |
| C05 | 整车相关功能 >90% 预验证覆盖 | 车机/GNSS-SDR 对照计划与 PPT 仅可作测试设计参考 | 未覆盖 | 未见目标功能清单、覆盖率计算及两份正式整车测试报告。 |
| C06 | 模拟与海外实测核心指标相关性 ≥85% | docs/DARKROOM_VEHICLE_GNSS_COMPARATIVE_TEST_AND_REPORT_PLAN_CN.md 仅提出方法 | 未覆盖 | 未见配对的海外实测/暗室数据、统计计算和一致性分析报告。 |
| C07 | 整车测试验证报告、模拟结果对比报告各 1 份 | B18/B19/A02 的方案和汇报资料仅可作目录入口 | 未覆盖 | 两类正式报告及其独立试验结果均未见。 |
| C08 | 至少 6 类系统技术文档完整性证明 | GPS generator reference、配置、脚本、GNSS-SDR 操作诊断、本整理目录 | 部分 | 软件/参数材料有基础；原理图、安装图、软硬件清单、维护文档和接口协议需逐类补齐。 |

## 使用边界

- GPS子项可用 7 项，部分 18 项，未覆盖 12 项；这是 GPS 范围的资料适用性统计，并非全项目验收统计。B11 的设施验收状态由项目方另行确认为“已通过”。项目方决定暗室设施资料以现有两件为本次工作封包，不再主动追补；B05/B12/C03 的“部分”仅保留原清单差异，不作为下一步索件任务。暗室设施验收也不等于 A06 全项目结题验收。两份材料的页码、来源和引用边界见 07_新增暗室设施资料登记与报告引用提要_GPS.md。
- 16 个参数组合不等于 16 个独立实测场景；48 张参数表的结构 QA PASS 不等于模型拟合精度 >90%。
- 0919 GNSS-SDR 48/48 执行/产物 QA PASS；31/48 有位置输出、17/48 无位置输出。该结果不等于整车测试合格、暗室性能验收或“无法物理定位”结论。
- 0919caiji 的 48 个 IQ 文件仍仅原位保留；Tx_Darkroom 的 16 张参数表和 48 张多随机表已有副本。对应路径、体量和副本范围见 02_原位大文件与未复制资产索引.md、03_复制范围与验证说明.md。
- 工程事实以 docs/GNSS_SAGE_ENGINEERING_HANDOFF_CURRENT.md 和相关 QA/manifest 为准；本表是结题清单对照索引。
