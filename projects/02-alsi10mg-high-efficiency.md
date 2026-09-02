# Project 02 — AlSi10Mg High-Efficiency LPBF Printing

> Tags: `AlSi10Mg` `Large Layer Thickness` `High Productivity` `Process Window` `Cost Reduction`

## 1. Background

针对对制造成本与交付效率较敏感的结构件应用，开发 AlSi10Mg 大层厚 LPBF 工艺。项目重点不是单纯提高扫描速度，而是在成形质量、力学性能、稳定性和生产效率之间寻找可落地的平衡点。

## 2. Engineering Challenge

- 层厚增加后，单层熔化所需能量和熔池稳定性要求明显提高；
- 粉末粒度、铺粉稳定性与层厚匹配变得更加关键；
- 高效率参数更容易出现未熔合、表面粗糙、飞溅和层间波动；
- 工艺开发要避免“效率提升了，但后处理成本和报废率更高”。

## 3. My Role

- 设计不同层厚下的功率—速度—道间距参数矩阵；
- 规划从高目标层厚到备选层厚的风险降级路径；
- 组织粉末、成形质量、组织与拉伸验证；
- 对比打印效率与性能稳定性；
- 形成可用于工程制件验证的候选参数包。

## 4. Approach

### 4.1 Efficiency First, but Not Efficiency Only

将目标拆成三个评价维度：

1. 单位时间成形体积；
2. 缺陷与表面状态；
3. 热处理后力学性能。

只有三者同时满足要求的参数才进入下一阶段。

### 4.2 Layer-Thickness Strategy

优先验证更高层厚方案；若稳定窗口过窄或缺陷控制困难，则回退到次高层厚。这样可以避免在开发初期就保守地锁死效率上限。

### 4.3 Parameter Matrix

使用功率、速度、道间距和层厚构建矩阵，通过致密度、表面状态、打印过程记录和后续性能测试逐步缩小窗口，而不是一次性寻找“唯一最优点”。

### 4.4 Heat Treatment & Mechanical Check

候选参数进入统一热处理流程，再进行室温及必要的高温性能验证，确认效率提升没有以显著性能牺牲为代价。

## 5. Key Engineering Decisions

- 将“大层厚”视作完整工艺链变化，而不是只修改切片层厚；
- 粉末粒度与层厚匹配优先于盲目增加能量；
- 评价效率时同时考虑返工、后处理和报废风险；
- 对接近缺陷边界的高效率点谨慎使用，优先保留可重复窗口。

## 6. Result

形成大层厚 AlSi10Mg 的候选工艺窗口和验证路径，为高效率工程化打印提供参数基础。公开版本不披露具体客户、生产件及完整参数矩阵。

## 7. Deliverables

- 大层厚 DOE 矩阵；
- 工艺窗口筛选记录；
- 打印效率对比；
- 组织与性能验证汇总；
- 参数包和工程化风险说明。

## 8. Competencies Demonstrated

`Productivity Optimization` · `LPBF` · `AlSi10Mg` · `DOE` · `Cost Engineering` · `Process Scale-up`

## 9. Interview Questions

- 为什么层厚增加后不能只提高功率？
- 大层厚参数最容易出现哪些失效模式？
- 如何证明“更快”真的意味着“更便宜”？

## Confidentiality Note

案例中的客户身份、目标零件、原始参数和内部经济性数据均已移除或重构。
