# DATA LABS - 数据分析项目展示网站

## 在线访问

网站地址: https://data.waanng.cn

## 项目概览

这是一个静态数据分析作品集网站，用于展示机器学习、描述型分析、时间序列等项目案例。网站托管在 GitHub Pages，主要由 HTML、CSS 和原生 JavaScript 组成。

## 项目结构

```text
data-site/
├── index.html                         # 首页
├── projects/index.html                # 项目列表页
├── ml-analysis/                       # 机器学习项目
│   ├── index.html
│   └── notebook.html
├── descriptive-analysis/              # 营销渠道效果分析
│   ├── index.html
│   └── notebook.html
├── time-series/                       # 时间序列分析
│   ├── index.html
│   └── notebook.html
├── assets/
│   ├── css/main.css                   # 全站样式
│   └── js/main.js                     # 导航与交互动效
└── CNAME                              # 自定义域名配置
```

## 设计方向

- 明亮、干净的数据作品集风格
- 蓝色作为主行动色，青绿色作为数据分析辅助色
- 卡片、指标、Notebook 查看器保持统一视觉语言
- 移动端优先兜底，避免网格挤压和导航消失

## 技术栈

- HTML5 + CSS3
- 原生 JavaScript
- Font Awesome 图标
- Google Fonts: Inter + JetBrains Mono
- GitHub Pages 托管

## 添加新项目

1. 新建项目目录，例如 `new-analysis/`
2. 复制现有项目详情页结构并替换内容
3. 在 `projects/index.html` 和首页项目区添加项目卡片
4. 如果需要展示 Notebook，新增对应的 `notebook.html`

## 部署

1. GitHub Pages 使用 `main` 分支根目录部署
2. `CNAME` 内容保持为 `data.waanng.cn`
3. 域名服务商配置 CNAME 到 `waanng.github.io`

## 注意事项

- Notebook 页面当前依赖 nbviewer 渲染远程 `.ipynb`
- 外部字体、图标和 nbviewer 均依赖网络环境
- 后续如果需要更稳定的离线展示，建议用 `jupyter nbconvert` 生成本地 HTML
