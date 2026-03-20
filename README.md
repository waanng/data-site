# Data Insights - 数据分析项目展示网站

## 🌐 在线访问

**网站地址**: https://data.waanng.cn

## 📁 项目结构

```
data-site/
├── index.html                   # 首页
├── projects/
│   └── index.html              # 项目列表页
├── ml-analysis/                # 机器学习项目
│   ├── index.html              # 项目介绍页
│   ├── notebook.html           # Notebook预览页
│   └── assets/                 # 项目资源
├── assets/
│   ├── css/main.css           # 主样式文件
│   └── js/main.js             # 主脚本文件
└── CNAME                       # 自定义域名配置
```

## 🎨 设计特点

- **现代简约**: 深蓝+科技青的配色方案
- **响应式设计**: 完美适配桌面、平板、手机
- **平滑动画**: 滚动显示、悬停效果
- **代码高亮**: Notebook页面支持代码语法高亮
- **目录导航**: Notebook页面左侧目录导航

## 🚀 部署指南

### 1. 启用 GitHub Pages

1. 进入 GitHub 仓库设置
2. 找到 Pages 选项
3. Source 选择 `Deploy from a branch`
4. Branch 选择 `main`，文件夹选择 `/ (root)`
5. 保存设置

### 2. 配置自定义域名

1. 确保 `CNAME` 文件内容为 `data.waanng.cn`
2. 在域名服务商处添加 CNAME 记录：
   - 主机记录: `data`
   - 记录类型: `CNAME`
   - 记录值: `waanng.github.io`

### 3. 等待生效

- GitHub Pages 部署通常需要 1-5 分钟
- DNS 解析可能需要 24-48 小时

## 📝 添加新项目

1. 在项目目录下创建新文件夹
2. 复制 `ml-analysis/index.html` 作为模板
3. 修改内容和样式
4. 在首页和项目列表页添加卡片

## 🛠️ 技术栈

- HTML5 + CSS3
- 原生 JavaScript
- Font Awesome 图标
- Google Fonts (Inter 字体)
- GitHub Pages 托管

## 📄 许可证

MIT License