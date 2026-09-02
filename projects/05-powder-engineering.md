# Project 05 — Metal Powder Engineering for LPBF

> Tags: `Powder` `Flowability` `Particle Size` `Oxygen/Nitrogen` `Process Compatibility`

## 1. Background

LPBF 工艺稳定性不仅由激光参数决定，粉末状态同样会影响铺粉、熔池、孔隙、表面质量和批次一致性。本项目方向聚焦铝合金等金属粉末的工程评价，以及粉末指标与打印表现之间的关联。

## 2. Engineering Challenge

- 粉末“化学成分合格”不代表一定适合稳定打印；
- 粒度、球形度、卫星粉、空心粉、流动性和松装密度会共同影响铺展；
- 回收粉、混批粉和储存状态可能带来氧氮变化与批次波动；
- 单一粉末指标异常时，需要判断它是否真的会成为当前零件的主导风险。

## 3. My Role

- 整理粉末检测项目与判定逻辑；
- 关联粉末状态、铺粉现象和打印缺陷；
- 参与粉末批次评价、使用边界和异常排查；
- 将粉末质量控制要求转化为项目可执行检查项。

## 4. Approach

### 4.1 Powder Quality Framework

从五类指标评价粉末：

1. 化学成分与气体元素；
2. 粒度分布；
3. 形貌与球形度；
4. 流动与堆积特性；
5. 实际铺粉与打印表现。

### 4.2 Link Test Data to Printing Behavior

不孤立解释检测值，而是建立对应关系：

- 流动性偏差 → 铺粉均匀性风险；
- 松装 / 振实变化 → 实际层内粉末体积分数变化；
- 粒度尾部异常 → 表面粗糙与局部熔化风险；
- 氧含量上升 → 需要关注材料性能与重复使用边界；
- 形貌恶化 → 铺展和批次稳定性风险。

### 4.3 Incoming / Reuse / Release Logic

将粉末管理分为：

`来料评价 → 上机前确认 → 使用过程记录 → 回收 / 筛分 → 复检 → 放行或隔离`

使粉末问题可以追溯，而不是打印失败后再猜测粉末是否有问题。

## 5. Key Engineering Decisions

- 不用单一流动时间决定粉末是否可用；
- 对不同材料体系采用不同风险重点；
- 粉末检测数据必须和实际铺粉、打印日志联动；
- 对临界批次设置隔离和验证，而不是直接混入正常批次；
- 将粉末状态纳入打印异常 RCA 的固定检查项。

## 6. Result

建立了面向 LPBF 的粉末质量评价框架，并将检测指标与打印现场表现连接起来，使粉末问题能够在打印前或异常早期被识别，而不是只在最终性能失败后发现。

## 7. Deliverables

- 粉末检测项目清单；
- 粉末放行 / 隔离逻辑；
- 粉末—铺粉—缺陷关联表；
- 批次记录模板；
- 异常复盘与使用边界说明。

## 8. Competencies Demonstrated

`Powder Metallurgy` · `Quality Control` · `LPBF` · `Root Cause Analysis` · `Process Control`

## 9. Interview Questions

- 为什么流动性合格仍可能铺粉不好？
- 松装密度变化为什么会影响打印？
- 回收粉应该看哪些风险？
- 如何证明某次缺陷确实来自粉末而不是激光参数？

## Confidentiality Note

未公开企业内部粉末放行限值、供应商名称、批次编号及受控检测数据。
