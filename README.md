# Additive Manufacturing Portfolio

> 脱敏版金属增材制造工程项目作品集｜SLM / LPBF · Process Development · Materials · Quality · Delivery

本仓库用于展示我在金属增材制造工程中的项目方法、技术判断与交付能力，面向工程师职称评审、技术面试、岗位申请与专业交流。

> **Confidentiality Notice**  
> 所有案例均经过脱敏与重构：客户、公司、项目编号、设备编号、原始模型、报价、完整参数窗口及受限性能数据均不公开。文中数据仅用于展示工程方法，不应视为任何企业内部工艺规范或可直接复现的生产参数。

## Engineering Profile

我的工作重点是将“材料—粉末—工艺—组织—性能—制件—交付”串成完整工程闭环，而不是只做单点参数试验。

核心方向：

- 金属 SLM / LPBF 工艺开发与参数窗口设计
- 铝合金、钛合金、镍基高温合金等材料工程化应用
- 大层厚 / 高效率成形与工艺降本
- 开裂、未熔合、球化、飞溅、翘曲等缺陷分析与治理
- 热处理制度与力学性能验证
- 粉末质量评价与工艺适配
- DFM、排版、打印、热处理、后处理、检测与交付管理
- 报价、周期、风险、客户技术对接与跨部门项目推进

## Portfolio Map

| Project | Topic | Core capability |
|---|---|---|
| [01](projects/01-high-strength-aluminum-lpbf.md) | 高强铝 LPBF 工艺开发 | DOE、参数窗口、热处理、拉伸验证 |
| [02](projects/02-alsi10mg-high-efficiency.md) | AlSi10Mg 大层厚高效率成形 | 效率提升、稳定性、参数边界 |
| [03](projects/03-titanium-100um-process.md) | 钛合金 100 μm 工艺开发 | 高风险参数开发、粉末适配、可制造性 |
| [04](projects/04-complex-part-delivery.md) | 复杂制件工程交付 | DFM、全流程协同、质量与交期 |
| [05](projects/05-powder-engineering.md) | 金属粉末工程 | 流动性、松装/振实、粒度、氧氮控制 |
| [06](projects/06-defect-troubleshooting.md) | LPBF 缺陷治理 | 根因分析、验证闭环、问题库 |
| [07](projects/07-superalloy-engineering.md) | 高温合金工程化 | 参数、热处理、HIP、性能与风险 |
| [08](projects/08-project-management.md) | 增材项目管理 | 报价、排产、交期、机台占用与客户对接 |

## Engineering Method

我习惯用同一套工程闭环处理项目：

`需求澄清 → DFM / 风险识别 → 试验设计 → 参数筛选 → 缺陷与组织分析 → 热处理 → 性能验证 → 制件放大 → 质量复核 → 参数包 / 报告 / 交付`

对于异常问题，则使用：

`现象定义 → 证据收集 → 假设树 → 最小验证试验 → 根因确认 → 工艺修正 → 复验 → 标准化沉淀`

## What I Can Demonstrate in an Interview

- 如何从零搭一套 LPBF 参数开发矩阵，而不是“盲扫参数”
- 如何判断强度偏低、孔隙异常、翘曲或开裂究竟来自能量输入、粉末、风场、扫描策略还是热处理
- 如何把实验室参数放大到实际复杂零件
- 如何在性能、效率、成本、交期之间做工程权衡
- 如何将单次项目经验沉淀为参数包、问题库、DFM 规则与项目管理工具

## Repository Structure

```text
.
├── README.md
├── CONFIDENTIALITY.md
├── projects/
│   ├── README.md
│   ├── 01-high-strength-aluminum-lpbf.md
│   ├── 02-alsi10mg-high-efficiency.md
│   ├── 03-titanium-100um-process.md
│   ├── 04-complex-part-delivery.md
│   ├── 05-powder-engineering.md
│   ├── 06-defect-troubleshooting.md
│   ├── 07-superalloy-engineering.md
│   └── 08-project-management.md
└── templates/
    └── project-case-template.md
```

## Status

第一版以 Markdown 案例为主，后续可逐步增加：

- 脱敏工艺窗口图、DOE 示意图与流程图
- 典型缺陷实物图 / 金相图的公开版替代图
- 性能对比雷达图、参数地图、鱼骨图
- 中英文双语版项目摘要
- 面向职称评审的“业绩成果映射表”
- 面向求职的 1 页 Resume Project Highlights

---

如果你是招聘经理或技术面试官：本作品集重点展示的是**工程方法、问题解决能力和项目闭环能力**，而不是公开任何受保密约束的生产参数。