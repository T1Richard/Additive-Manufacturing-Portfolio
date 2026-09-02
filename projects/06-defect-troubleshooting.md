# Project 06 — LPBF Defect Troubleshooting & Root Cause Analysis

> Tags: `Defects` `RCA` `Warping` `Cracking` `Lack of Fusion` `Spatter`

## 1. Background

金属 LPBF 项目中，异常往往不是单一原因造成。翘曲、开裂、未熔合、球化、飞溅、铺粉异常、风场异常、尺寸偏差和表面粗糙度等问题，常常由材料、设备、参数、扫描策略、支撑和后处理共同作用。

## 2. Engineering Challenge

- 同一种表面现象可能对应完全不同根因；
- 参数、粉末、风场和铺粉问题之间会相互放大；
- 如果只靠经验“改几个参数再试”，容易产生大量无效试验；
- 项目现场往往需要快速判断“是否还能继续打印”和“是否影响最终交付”。

## 3. My Role

- 收集和分类典型打印异常；
- 建立现象—原因—排查—解决方案框架；
- 参与现场问题判断和验证试验设计；
- 将单次异常沉淀为可复用的问题案例库。

## 4. Approach

### 4.1 Define the Symptom First

先描述可观察事实，而不是直接写结论。例如：

- 缺陷位于迎风侧还是背风侧？
- 是整层出现还是局部出现？
- 从哪一层开始恶化？
- 是否与零件高度、扫描面积或铺粉方向相关？

### 4.2 Build a Cause Tree

固定从六类因素检查：

`Material → Machine → Parameter → Gas Flow → Recoating → Geometry/Support`

必要时再扩展到热处理和后处理。

### 4.3 Minimum Verification Experiment

每次修改尽量只验证少数关键变量，避免同时改变多个条件后无法确认根因。

例如对于强度偏低：

1. 先确认取样方向和测试条件；
2. 检查致密度 / 缺陷类型；
3. 查看打印日志和风场状态；
4. 核对粉末和热处理批次；
5. 最后再决定是否需要重新调整参数。

### 4.4 Standardize the Learning

每个问题最终沉淀成：

`现象 → 可能原因 → 快速检查 → 深度验证 → 纠正措施 → 预防措施`

## 5. Typical Cases

### Warping / 翘曲

重点检查残余应力、支撑刚度、热积累、扫描策略、底板预热和零件方向。

### Cracking / 开裂

区分热裂、应力裂纹与后处理裂纹，结合材料裂纹敏感性、热输入、几何约束和热处理路径判断。

### Lack of Fusion / 未熔合

重点检查能量输入不足、铺粉缺失、层厚异常和污染层。

### Spatter / 飞溅

结合能量输入、气流方向、烟尘清除和熔池不稳定性判断。

### Recoating Abnormality / 铺粉异常

检查粉末流动、刮刀状态、局部凸起、零件翘曲和设备铺粉系统。

### Low Mechanical Properties / 性能偏低

不能只归因于参数，需要同时排查孔隙、组织、热处理、粉末、方向性和测试条件。

## 6. Result

将分散的现场经验整理为结构化缺陷排查框架，使异常处理从“凭经验试参数”转变为可记录、可验证、可复用的工程流程。

## 7. Deliverables

- 打印问题案例库；
- RCA 检查表；
- 缺陷分类与决策树；
- 异常验证记录；
- 纠正与预防措施清单。

## 8. Competencies Demonstrated

`Root Cause Analysis` · `LPBF Defects` · `Problem Solving` · `Process Control` · `Knowledge Management`

## 9. Interview Questions

- 风场为什么会影响力学性能？
- 如何区分未熔合和气孔？
- 一旦发生翘曲，你如何判断还能不能继续打印？
- 为什么不能一遇到强度低就直接改参数？

## Confidentiality Note

本页为多个项目经验的通用化总结，不包含任何客户可识别信息或企业内部故障记录。
