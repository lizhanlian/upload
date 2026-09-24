# 资料库（upload）

本仓库用于集中保存电动汽车、充电基础设施、能源管理、强化学习、智能优化算法及相关国家标准资料。文件以 PDF 原始文件形式保存，便于下载、阅读和后续研究引用。

## 目录

- [资料分类](#资料分类)
- [电动汽车充电与能源管理](#电动汽车充电与能源管理)
- [算法与优化](#算法与优化)
- [国家标准](#国家标准)
- [文件完整性与注意事项](#文件完整性与注意事项)
- [使用与引用](#使用与引用)

## 资料分类

| 类别 | 内容 |
|---|---|
| 电动汽车充电与能源管理 | 区域充电需求预测、UrbanEV 数据集、V2G、电动公交车充电、多微电网能源管理、主动配电网控制 |
| 算法与优化 | 自动算法配置、多智能体强化学习、进化计算、无免费午餐定理 |
| 国家标准 | 电动汽车传导充电系统安全要求、交流充电桩电能计量 |

## 电动汽车充电与能源管理

| 文件 | 说明 | 页数 | 大小 |
|---|---|---:|---:|
| [A_Physics-Informed_and_Attention-Based_Graph_Learning_Approach_for_Regional_Electric_Vehicle_Charging_Demand_Prediction.pdf](A_Physics-Informed_and_Attention-Based_Graph_Learning_Approach_for_Regional_Electric_Vehicle_Charging_Demand_Prediction.pdf) | 面向区域电动汽车充电需求预测的物理信息与注意力图学习方法。发表信息：*IEEE Transactions on Intelligent Transportation Systems*, 2024, 25(10)，DOI：[10.1109/TITS.2024.3401850](https://doi.org/10.1109/TITS.2024.3401850)。 | 14 | 12.29 MB |
| [UrbanEV An Open Benchmark Dataset for Urban Electric Vehicle Charging Demand Prediction.pdf](UrbanEV%20An%20Open%20Benchmark%20Dataset%20for%20Urban%20Electric%20Vehicle%20Charging%20Demand%20Prediction.pdf) | UrbanEV 城市电动汽车充电需求预测开放基准数据集论文。发表信息：*Scientific Data*，DOI：[10.1038/s41597-025-04874-4](https://doi.org/10.1038/s41597-025-04874-4)。 | 10 | 8.42 MB |
| [Constraint-guided Multi-Agent Deep Reinforcement Learning for Multi-Microgrid Energy Management with Mobile Electric Vehicles.pdf](Constraint-guided%20Multi-Agent%20Deep%20Reinforcement%20Learning%20for%20Multi-Microgrid%20Energy%20Management%20with%20Mobile%20Electric%20Vehicles.pdf) | 约束引导的多智能体深度强化学习，用于含移动电动汽车的多微电网能源管理。发表信息：*Applied Energy*, 427 (2027), 128833，DOI：[10.1016/j.apenergy.2026.128833](https://doi.org/10.1016/j.apenergy.2026.128833)。 | 21 | 5.61 MB |
| [Electric Bus Coordinated Charging Strategy Considering V2G and Battery Degradation.pdf](Electric%20Bus%20Coordinated%20Charging%20Strategy%20Considering%20V2G%20and%20Battery%20Degradation.pdf) | 考虑 V2G 和电池退化的电动公交车协调充电策略。发表信息：*Energy*, 254 (2022), 124252，DOI：[10.1016/j.energy.2022.124252](https://doi.org/10.1016/j.energy.2022.124252)。 | 11 | 2.20 MB |
| [基于多智能体强化学习的主动配电网异质性协同分布式控制方法研究.pdf](基于多智能体强化学习的主动配电网异质性协同分布式控制方法研究.pdf) | 面向主动配电网异质性协同控制的多智能体强化学习研究，中文学位论文。 | 62 | 10.79 MB |

## 算法与优化

| 文件 | 说明 | 页数 | 大小 |
|---|---|---:|---:|
| [A Multi-Agent Self-Supervised State Representation Framework for Automated Algorithm Configuration.pdf](A%20Multi-Agent%20Self-Supervised%20State%20Representation%20Framework%20for%20Automated%20Algorithm%20Configuration.pdf) | 面向自动算法配置的多智能体自监督状态表示框架。论文标注为 *IEEE Transactions on Evolutionary Computation* 接收版本，DOI：[10.1109/TEVC.2026.3732483](https://doi.org/10.1109/TEVC.2026.3732483)。 | 14 | 2.14 MB |
| [No_free_lunch_theorems_for_optimization.pdf](No_free_lunch_theorems_for_optimization.pdf) | 优化领域的无免费午餐定理相关论文，标题为 “No Free Lunch Theorems For Optimization”。 | 16 | 0.72 MB |

## 国家标准

| 文件 | 标准名称 | 发布/实施信息 | 页数 | 大小 |
|---|---|---|---:|---:|
| [GB+44263-2024.pdf](GB%2B44263-2024.pdf) | **GB 44263—2024 电动汽车传导充电系统安全要求**（Safety requirements for electric vehicle conductive charging system） | 2024-07-24 发布；2025-08-01 实施 | 35 | 1.25 MB |
| [GBT+28569-2024.pdf](GBT%2B28569-2024.pdf) | **GB/T 28569—2024 电动汽车交流充电桩电能计量**，代替 GB/T 28569—2012 | 2024 年版 | 23 | 0.49 MB |

## 文件完整性与注意事项

当前仓库中的有效资料包括 9 份 PDF。各 PDF 均小于 GitHub 单文件 100 MB 限制，可以直接下载。

仓库中另有一个名为 [`pdf`](pdf) 的 1 字节文件。该文件不具有 PDF 文件头，也不是有效 PDF，当前仅保留以避免未经确认删除用户资料；如确认该文件无用，可在后续提交中删除或替换。

建议下载后使用以下命令检查 PDF 是否可读取：

```bash
pdfinfo "文件名.pdf"
```

对于需要长期引用的论文或标准，请优先通过文中 DOI、标准编号或原始发布机构获取正式版本，并遵守相应的版权、许可和使用规定。本仓库仅作为个人资料整理与研究参考，不替代正式出版物或标准原文。

## 使用与引用

- 论文引用应以论文首页、期刊页面或 DOI 页面显示的作者、题目、期刊、年份和 DOI 为准。
- 国家标准引用应使用标准编号、标准名称、版本年份及发布/实施日期。
- UrbanEV 数据集及相关代码请同时参考对应的 [UrbanEV GitHub 仓库](https://github.com/lizhanlian/UrbanEV) 和 [Dryad 数据集页面](https://doi.org/10.5061/dryad.np5hqc04z)。

## 更新记录

- 2026-09-24：新增区域电动汽车充电需求预测论文，并整理仓库资料目录、分类和文件说明。
