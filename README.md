# Front-End-Final-Assignment

> 前端期末作业集合 — Bootstrap 5 与 jQuery 实战练习

## 项目简介

本项目是一个前端期末作业的集合网站，展示了多种 Web 前端技术的学习和实践成果。涵盖 CSS 特效、组件使用、API 调用等多种前端技能。

## 技术架构

| 技术 | 说明 |
|------|------|
| **HTML5 + CSS3** | 语义化标签与现代化 CSS |
| **JavaScript** | 原生 JavaScript |
| **jQuery 3.7.1** | JavaScript 函数库 |
| **Bootstrap 5.3.0** | UI 框架，响应式组件库 |
| **Less** | CSS 预处理器 |

## 目录结构

```
front-end-final-assignment/
├── index.html              # 入口首页
├── bootstrap/              # Bootstrap 5 库
├── css/                    # 样式文件
├── js/                     # 脚本文件
├── jQuery/                 # jQuery 库
├── datepicker/             # 日期选择器
├── less/                   # Less 源文件
├── html/                   # 演示页面
├── img/                    # 图片资源
├── video/                  # 视频资源
├── test/                   # 测试页面
└── requirements/           # 作业要求文档
```

## 模块详解

### 首页 (index.html)

- 轮播展示
- 实用项目卡片（中草药定位系统、API 调用实验等）
- 音乐/视频卡片
- 底部导航按钮

### 加入我们 (html/get_in.html)

入会表单页面，包含表单验证、浮动输入框标签、主题切换。

### PC 端演示 (html/pc_demo.html)

完整功能演示页面，浏览器兼容性参考标准。

### 浮动输入框测试 (html/floating_input_demo.html)

Bootstrap 5 浮动输入框特性兼容性测试。

## 快捷键功能

| 快捷键 | 功能 |
|--------|------|
| `g` | 跳转到"加入我们"页面 |
| `i` | 打开/关闭信息弹窗 |
| `m` | 播放/暂停音乐 |
| `t` | 切换亮/暗主题 |
| `G` | 打开使用指南 |

### 主题系统

支持亮/暗模式切换，偏好保存在 localStorage 中。

## 组件演示

| 演示 | 路径 |
|------|------|
| 日期选择器 | `test/datepicker_test.html` |
| 卡片组件 | `test/card.html` |
| 轮播组件 | `test/carousel.html` |
| 按钮样式 | `test/glow_button_test.html` |
| 瀑布流布局 | `test/masonry/` |
| Toast 提示 | `test/toast_test.html` |
| 表单验证 | `test/validation_test.html` |

## 开发环境

直接用浏览器打开 `index.html` 即可。

```bash
python -m http.server 8000
npx serve .
```

## 浏览器兼容性

| 功能 | 兼容性 |
|------|--------|
| Bootstrap 5 | 现代浏览器 |
| 浮动输入框 | Chrome 90+, Edge 90+ |
| ES6+ JavaScript | Chrome 60+, Firefox 55+ |

## 作者

- **GitHub**: [bigmanBass666](https://github.com/bigmanBass666)

---

*云中医大二下学期前端期末作业*
