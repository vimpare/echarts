**legend:**
图例组件。

图例组件展现了不同系列的标记(symbol)，颜色和名字。可以通过点击图例控制哪些系列不显示。

**grid**
直角坐标系内绘图网格，单个 grid 内最多可以放置上下两个 X 轴，左右两个 Y 轴。可以在网格上绘制折线图，柱状图，散点图（气泡图）
grid.containLabel grid 区域是否包含坐标轴的刻度标签。
yAxis.axisTick.坐标轴刻度相关设置。yAxis.axisTick.show是否显示坐标轴刻度。
**series[i]**
系列列表。每个系列通过 type 决定自己的图表类型
series[i]-bar.label图形上的文本标签，可用于说明图形的一些数据信息，比如值，名称等
