# Drag-and-drop-report
打造拖拽式报表 Dashboard 搭建器
Vue 3.4+ + Composition API
拖拽布局用 GridStack.js
图表用 ECharts 5，每种图表封装为独立组件
状态管理 reactive 保存组件树
样式 Tailwind CSS

左侧组件库：折线图、饼图、柱状图、指标卡、表格
拖拽到中间画布生成组件，可调整大小
右侧属性面板：选中组件后显示可配置项（标题、数据源、颜色）
数据源：Mock 随机数据 + 支持输入 API 地址（GET）
