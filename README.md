# 个人财务系统 (Personal Finance System)

[![Vue](https://img.shields.io/badge/Vue-3.x-brightgreen)](https://vuejs.org)
[![uniapp](https://img.shields.io/badge/uni-app-cross%20platform-blue)](https://uniapp.dcloud.io)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

基于 **uni-app** 构建的跨平台个人财务管理应用，支持 H5、微信小程序、Android 等多端运行。

## 功能特性

- **收支记录** — 快速记录每日收入与支出，支持分类管理
- **数据统计** — 图表化展示月度/年度消费趋势与分布
- **预算管理** — 设定月度预算，实时监控超支风险
- **账目分类** — 自定义分类标签，灵活管理资金流向
- **多端同步** — 基于 uni-app 实现一套代码多端运行

## 技术栈

| 技术 | 用途 |
|------|------|
| uni-app | 跨平台应用框架 |
| Vue 3 | 前端 UI 框架 |
| Vuex / Pinia | 状态管理 |
| uni-ui | UI 组件库 |
| ECharts | 数据可视化 |

## 快速开始

```bash
# 克隆仓库
git clone https://github.com/Fanhua041027/Personal-Finance-System-Based-on-uniapp.git
cd Personal-Finance-System-Based-on-uniapp

# 安装依赖
npm install

# 启动 H5 开发模式
npm run dev:h5

# 启动微信小程序
npm run dev:mp-weixin
```

## 项目结构

```
src/
├── pages/          # 页面
│   ├── index/      # 首页（账单列表）
│   ├── statistics/ # 统计页面
│   ├── budget/     # 预算管理
│   └── mine/       # 个人中心
├── components/     # 公共组件
├── store/          # 状态管理
├── utils/          # 工具函数
└── static/         # 静态资源
```

## 许可证

本项目仅供学习研究使用。
