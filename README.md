# Front-End-Final-Assignment

> 前端期末作业集合 - Bootstrap 5 与 jQuery 实战练习

## 项目简介

本项目是一个前端期末作业的集合网站，展示了多种 Web 前端技术的学习和实践成果。网站包含多个独立模块，涵盖 CSS 特效、组件使用、API 调用等多种前端技能。

## 技术架构

### 核心技术栈

| 技术 | 说明 |
|------|------|
| **HTML5 + CSS3** | 语义化标签与现代化 CSS |
| **JavaScript** | 原生 JavaScript |
| **jQuery 3.7.1** | JavaScript 函数库，简化 DOM 操作 |
| **Bootstrap 5.3.0** | UI 框架，响应式组件库 |
| **Less** | CSS 预处理器 |

### 开发工具

- **日期选择器**: bootstrap-datepicker
- **图标**: Bootstrap Icons
- **字体**: 系统字体 + Bootstrap 默认字体

## 目录结构

```
front_end_final_assignment/
├── index.html                      # 入口首页
├── favicon.ico                     # 网站图标
├── bootstrap/                      # Bootstrap 5 库
│   ├── css/
│   │   ├── bootstrap.css          # 完整 CSS
│   │   ├── bootstrap-grid.css     # 栅格系统
│   │   ├── bootstrap-reboot.css   # 样式重置
│   │   └── bootstrap-utilities.css # 工具类
│   └── js/
│       ├── bootstrap.js           # 主文件
│       ├── bootstrap.bundle.js    # 捆绑包(含 Popper)
│       └── bootstrap.esm.js       # ESM 版本
├── css/                            # 样式文件
│   ├── common.css                  # 公共样式
│   ├── index.css                   # 首页样式
│   ├── get_in.css                  # 入会表单样式
│   ├── floating_input_demo.css    # 浮动输入框演示
│   └── homeBtn.css                 # 按钮样式
├── js/                             # 脚本文件
│   ├── index.js                    # 首页逻辑
│   ├── get_in.js                   # 入会表单逻辑
│   ├── common_btn.js               # 公共按钮逻辑
│   └── themeSwitch.js              # 主题切换
├── jQuery/                         # jQuery 库
│   ├── jquery-3.7.1.js             # 完整版
│   ├── jquery-3.7.1.min.js        # 压缩版
│   └── awesome-jquery-3.7.1.js     # slim 版
├── datepicker/                     # 日期选择器
│   ├── css/
│   │   ├── bootstrap-datepicker.css
│   │   ├── bootstrap-datepicker3.css
│   │   └── *.min.css              # 各版本压缩
│   └── js/
│       ├── bootstrap-datepicker.js
│       ├── bootstrap-datepicker.min.js
│       └── bootstrap-datepicker.zh-CN.min.js # 中文语言包
├── less/                           # Less 源文件
│   ├── common.less                 # 公共样式
│   ├── index.less                  # 首页样式
│   ├── get_in.less                 # 入会表单
│   ├── floating_input_demo.less   # 浮动输入框
│   └── homeBtn.less                # 按钮样式
├── html/                           # 演示页面
│   ├── get_in.html                 # 加入我们/入会表单
│   ├── floating_input_demo.html   # Bootstrap 浮动输入框兼容性测试
│   └── pc_demo.html               # PC 端完整演示
├── img/                            # 图片资源
│   ├── lilac.jpg                  # 背景装饰
│   ├── mint_green.jpg             # 主题图片
│   ├── heral_positioning_system.png
│   ├── awesome_pictures_videos.png
│   ├── floating_input.png
│   ├── pc_demo.png
│   ├── playing_god.jpg            # 音乐视频封面
│   ├── 40oz.jpg                   # Polyphia 乐队
│   ├── i_miss_you.jpg             # ichika
│   ├── Picturesque.jpg            # ichika
│   └── ...
├── video/                          # 视频资源
│   ├── floating_input_demo.mp4    # 浮动输入框演示视频
│   └── pc_demo.mp4               # PC 端演示视频
├── test/                           # 测试页面
│   ├── bilibili_iframe_test.html
│   ├── button_radio_checkbox_test.html
│   ├── card.html
│   ├── carousel.html
│   ├── common_btn.html
│   ├── datalist_test.html
│   ├── datepicker_test.html
│   ├── glow_button_test.html
│   ├── masonry/
│   │   ├── css_column.html
│   │   └── js.html
│   ├── select_test.html
│   ├── toast_test.html
│   └── validation_test.html
└── requirements/                   # 作业要求文档
    ├── 期末作业要求【本次作业占本门课40%成绩】.html
    └── 期末作业要求【本次作业占本门课40%成绩】.md
```

## 模块详解

### 1. 首页 (index.html)

#### 轮播展示

展示两张幻灯片：
- 标题: "LILAC"
- 颜色信息: HEX / RGB / HSL 值

#### 实用项目卡片 (useful-cards)

| 项目 | 链接 | 说明 |
|------|------|------|
| 中草药定位系统 | [在线预览](https://keen-tartufo-d1e080.netlify.app/) | 基于百度地图 API |
| API调用实验 | [在线预览](https://awesome-pictures-videos.netlify.app/) | AJAX 和 API 调用 |
| 浮动输入框兼容性 | [本地演示](html/floating_input_demo.html) | Bootstrap 5 特性测试 |
| PC端演示 | [本地演示](html/pc_demo.html) | 浏览器兼容性参考 |

#### 音乐/视频卡片 (useless-cards)

展示音乐人和视频链接：
- Playing God - Tim Henson
- 40oz - Polyphia
- i miss you - ichika
- Picturesque - ichika

#### 底部导航按钮

| 按钮 | 位置 | 功能 |
|------|------|------|
| 加入我们 | 右下角 | 跳转入会表单 |
| 信息 | 右下角 | 显示更多信息 |
| 主题切换 | 右下角 | 亮/暗模式切换 |
| 播放音乐 | 右下角 | 音频播放器控制 |

### 2. 加入我们 (html/get_in.html)

入会表单页面，包含：
- 表单验证
- 浮动输入框标签
- 主题切换功能

### 3. PC 端演示 (html/pc_demo.html)

完整的功能演示页面，作为浏览器兼容性参考标准。

### 4. 浮动输入框测试 (html/floating_input_demo.html)

测试 Bootstrap 5 浮动输入框特性在不同浏览器的兼容性。

## 快捷键功能

首页支持多个快捷键操作：

| 快捷键 | 功能 | 作用域 |
|--------|------|--------|
| `g` | 跳转到"加入我们"页面 | 全局 |
| `i` | 打开/关闭信息弹窗 | 全局 |
| `m` | 播放/暂停音乐 | 全局 |
| `t` | 切换亮/暗主题 | 全局 |
| `G` | 打开使用指南 | 全局 |
| `d` | 清除 localStorage 中的 theme | 全局 |
| `v` | 清除 localStorage 中的 isVisited | 全局 |

### 使用指南

页面内置引导功能，首次访问时自动弹出，或通过信息按钮查看。

### 主题系统

支持亮/暗模式切换：
- **亮模式**: 白色背景，深色文字
- **暗模式**: 深色背景，浅色文字

主题偏好保存在 localStorage 中。

## 第三方资源

### 外部链接

| 资源 | 链接 |
|------|------|
| 中草药定位系统 | https://keen-tartufo-d1e080.netlify.app/ |
| API调用实验 | https://awesome-pictures-videos.netlify.app/ |
| Bilibili 视频 | https://www.bilibili.com/video/BV1hU4y117vv |
| Polyphia | https://www.bilibili.com/video/BV1JE411o7Nz |
| ichika | https://www.bilibili.com/video/BV11441137zA |
| ichika 官网 | http://ichika-official.com |

### 字体图标

使用 Bootstrap Icons：
```html
<link rel="stylesheet" href="bootstrap-5.3.0-alpha1-dist/font/bootstrap-icons.min.css">
```

## 组件演示

### 日期选择器

路径: `test/datepicker_test.html`

演示 bootstrap-datepicker 的使用：
- 基本用法
- 中文语言支持
- 日期范围选择

### 卡片组件

路径: `test/card.html`

Bootstrap 卡片组件的各种用法。

### 轮播组件

路径: `test/carousel.html`

Bootstrap 轮播（Carousel）组件演示。

### 按钮样式

路径: `test/common_btn.html`, `test/glow_button_test.html`

自定义发光按钮样式：
- 基础样式
- 悬停效果
- 激活状态

### 栅栏布局

路径: `test/masonry/`

两种瀑布流布局实现：
- CSS 多列方式
- JavaScript 方式

### Toast 提示

路径: `test/toast_test.html`

Bootstrap Toast 组件演示。

### 表单验证

路径: `test/validation_test.html`

HTML5 原生表单验证样式展示。

### Select 下拉框

路径: `test/select_test.html`

下拉选择框的各种样式。

### Datalist 输入建议

路径: `test/datalist_test.html`

HTML5 datalist 组件实现输入建议功能。

## 开发指南

### 运行方式

直接用浏览器打开 `index.html` 即可。

### 本地服务器（可选）

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000
```

### Less 编译

如需修改 Less 源文件：

```bash
lessc less/index.less css/index.css
```

## 浏览器兼容性

| 功能 | 兼容性 |
|------|--------|
| Bootstrap 5 | 现代浏览器 |
| 浮动输入框 | Chrome 90+, Edge 90+ |
| CSS Grid | 现代浏览器 |
| ES6+ JavaScript | Chrome 60+, Firefox 55+, Safari 11+ |

## 版权信息

```
Copyright © Jason Liu
```

## 联系方式

- **作者**: Jason Liu

## 学习收获

通过本项目掌握了以下前端技能：

- [x] Bootstrap 5 栅格系统和组件使用
- [x] jQuery DOM 操作和事件处理
- [x] CSS 预处理器 Less 基础
- [x] 响应式设计原理
- [x] 表单验证
- [x] 第三方库集成
- [x] 主题切换系统实现
- [x] 键盘快捷键功能
- [x] 平滑滚动效果
