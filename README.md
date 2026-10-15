# VisData · 可视化数据分析平台 / Visual Data Analysis Platform

VisData 是一个**无需写代码**的可视化数据分析平台。它把 Python pandas 的各类数据操作，转化为鼠标点击即可完成的图形界面；每一步操作的背后，都对应一个真实的 pandas 函数。平台为**中英双语**界面，内容完全对应。

VisData is a **no-code** visual data analysis platform. It turns the data operations of Python pandas into point-and-click graphical interactions — every step maps to a real pandas function under the hood. The UI is fully bilingual (Chinese / English).

## 核心特点 / Key Features

- 🖱️ 全程图形化操作，无需编写任何代码 / Fully graphical, no code required
- 🌐 中英双语界面，一键切换 / Bilingual UI with one-click language switch
- 📊 每次操作实时刷新「表格 + 图表」/ Every operation live-updates both table and charts
- 📁 支持 CSV / Excel / JSON 加载与导出 / Load & export CSV, Excel, JSON
- ↩️ 完整操作历史，可撤销 / Redo Undo operation history
- 🗺️ 每个菜单都提示对应的 pandas 函数 / Every menu shows its pandas counterpart

## 功能模块 / Feature Modules

| 模块 Module | 功能 Functions |
|---|---|
| 数据 IO / Data I/O | 导入、导出、粘贴表格、URL 加载 / Import, Export, Paste table, Load from URL |
| 数据探索 / Explore | 数据概览、数据表 / Data overview, Data table |
| 选取与筛选 / Select & Filter | 布尔筛选、行切片、字段选择 / Boolean filter, row slicing, column selection |
| 索引操作 / Index Ops | 设置 / 重置索引 / Set / reset index |
| 数据清洗 / Cleaning | 缺失值、重复值、类型转换、字符串工具 / Missing & duplicate values, type cast, string tools |
| 结构重塑 / Reshape | 宽转长、重命名、删除、移动、替换、映射 / Melt, rename, drop, move, replace, map |
| 合并数据 / Merge | inner / left / right / outer 连接，追加、拼接 / Joins, append, concat |
| 采样 / Sampling | 随机抽样、分层抽样 / Random & stratified sampling |
| 计算变换 / Compute | 排序、排名、自定义函数、统计 / Sort, rank, custom function, statistics |
| 聚合分析 / Aggregate | 分组聚合、透视表 / GroupBy, Pivot table |
| 时间序列 / Time Series | 提取日期字段、重采样、滚动窗口、IQR 离群检测 / Date extraction, resample, rolling window, IQR outliers |
| 可视化 / Visualize | 9 种图表：折线、柱状、堆叠、散点、直方、密度、箱线、饼图、热力图 / 9 chart types |

## 使用方法 / Usage

直接打开 `index.html` 即可使用（单文件应用，无依赖、无构建步骤）。默认自带样例数据集，也可加载你自己的数据。

Open `index.html` directly in a browser — it's a single-file app with no dependencies and no build step. A sample dataset is preloaded, and you can also load your own data.

---

*VisData · Visualize your pandas workflow*
