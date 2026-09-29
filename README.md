# web-learning

Web 前端学习练习仓库，用于记录 HTML / CSS 学习 Demo 与学习笔记。

## 📖 项目简介

本仓库用于存放个人 Web 前端学习练习代码，目前覆盖 **HTML 基础 → CSS 基础 → CSS 进阶 → CSS 盒子模型 → CSS 浮动与定位**，并包含一个综合项目练习。

项目按照不同知识点划分独立文件夹，每个目录包含对应的练习案例，部分章节配套 `study.md` 学习笔记，用于记录学习过程，方便后续复习与知识回顾。

后续将持续补充 **Flex / Grid 布局、JavaScript** 等前端相关学习内容。

## 📚 学习内容

**HTML 基础**

- HTML 基础结构
- 图片资源的使用
- 超链接与页面跳转
- 音频与视频标签
- 有序列表、无序列表、自定义列表
- HTML 表格、表格结构标签、单元格合并
- HTML 表单、`input` 输入控件、单选框、文本域、下拉菜单、`label` 标签、文件上传、`button` 按钮
- HTML 语义化标签
- HTML 字符实体
- HTML 综合案例

**CSS 基础**

- CSS 引入方式与基本语法
- 基本选择器：标签、类、id、通配符
- 字体样式：字号、文字粗细、字体倾斜、`font` 属性
- 文本样式：文本缩进、水平对齐、文本修饰、行高
- CSS 样式层叠问题
- CSS 综合案例

**CSS 进阶**

- 复合选择器：后代、子代、并集、交集、伪类
- Emmet 语法
- 背景：背景色、背景图、背景平铺、背景位置、复合属性
- 显示模式：块级、行内、行内块
- 标签嵌套拓展
- CSS 三大特性：继承、层叠、优先级

**CSS 盒子模型**

- 优先级与权重叠加计算
- 盒子模型：内容、边框线、尺寸
- 版心居中
- 外边距问题：外边距合并、外边距塌陷
- 行内元素的内外边距问题
- 综合案例：新闻列表

**CSS 浮动与定位**

- 结构伪类选择器、伪元素
- 浮动特点、浮动案例、受浮动影响的情况
- 清除浮动：额外标签法、单伪元素法、双伪元素法、`overflow`
- 相对定位、绝对定位、子绝父相
- 综合案例：小米产品、导航栏

**综合项目**

- 在线学习平台首页（`project_online Study`）

## 📂 目录结构

```text
web-learning/
├── HTML基础/                      # HTML 基础（demo1 ~ demo9）
│   ├── demo1_Study/
│   │   └── demo1.html
│   ├── demo2_招聘/
│   │   ├── demo2.html
│   │   └── 腾云大厦.png
│   ├── demo3_跳转/
│   │   ├── index.html
│   │   ├── one.html
│   │   ├── two.html
│   │   └── media/
│   │       ├── 千与千寻.mp3
│   │       └── 有一种悲伤.mp4
│   ├── demo4_列表/
│   │   ├── 有序列表.html
│   │   ├── 无序列表.html
│   │   ├── 自定义列表.html
│   │   └── study.md
│   ├── demo5_表格/
│   │   ├── 表格.html
│   │   ├── 表格标题和表头.html
│   │   ├── 表格-结构标签.html
│   │   ├── 合并单元格.html
│   │   └── study.md
│   ├── demo6_表单/
│   │   ├── 表单_input.html
│   │   ├── 表单占位符.html
│   │   ├── 表单_单选框.html
│   │   ├── 表单-文本域标签.html
│   │   ├── 表单-下拉菜单.html
│   │   ├── 表单-label.html
│   │   ├── 按钮_input.html
│   │   ├── button按钮标签.html
│   │   ├── 上传多个文件.html
│   │   └── study.md
│   ├── demo7_语义化标签/
│   │   ├── div.html
│   │   ├── phone.html
│   │   └── study.md
│   ├── demo8_字符实体/
│   │   └── 字符实体.html
│   └── demo9_综合案例/
│       ├── 表单.html
│       └── 学生信息表.html
│
├── CSS基础/                       # CSS 基础语法（demo1 ~ demo18）
│   ├── HTML/
│   │   ├── demo1-体验css.html
│   │   ├── demo2-css引入方式.html
│   │   ├── demo3-选择器-标签.html
│   │   ├── demo4-选择器-类选择器.html
│   │   ├── demo5-选择器-id.html
│   │   ├── demo6-选择器-通配符.html
│   │   ├── demo7-字号.html
│   │   ├── demo8-文字粗细.html
│   │   ├── demo9-字体倾斜.html
│   │   ├── demo10-字体样式.html
│   │   ├── demo11-样式层叠问题.html
│   │   ├── demo12-font属性-.html
│   │   ├── demo13-文本缩进.html
│   │   ├── demo14-文本水平对齐.html
│   │   ├── demo15文本修饰.html
│   │   ├── demo16-行高.html
│   │   ├── demo17-综合案例1.html
│   │   ├── demo18-综合案例2.html
│   │   ├── 浪淘沙·北戴河.png
│   │   ├── 腾云大厦.png
│   │   └── 小米商品.png
│   ├── CSS/
│   │   └── demo2.css ~ demo18.css（共 17 个）
│   └── study.md
│
├── CSS进阶/                       # CSS 进阶（demo1 ~ demo20）
│   ├── demo1-选择器-后代.html
│   ├── demo2-选择器-子代.html
│   ├── demo3-选择器-并集.html
│   ├── demo4-选择器-交集.html
│   ├── demo5-选择器-伪类.html
│   ├── demo6-emme语法.html
│   ├── demo7-背景-背景色.html
│   ├── demo8-背景-背景图.html
│   ├── demo9-背景-背景平铺.html
│   ├── demo10-背景-背景位置.html
│   ├── demo11-背景-复合属性.html
│   ├── demo12-显示模式-块.html
│   ├── demo13-显示模式-行内.html
│   ├── demo14-显示模式-行内块.html
│   ├── demo15-拓展-标签嵌套.html
│   ├── demo16-css特性-继承.html
│   ├── demo17-特性-注意.html
│   ├── demo18-特性-层叠.html
│   ├── demo19-综合案例1.html
│   ├── demo20-综合案例2.html
│   ├── demo1.css ~ demo14.css（共 14 个）
│   ├── images/
│   │   └── FZD.jpg
│   └── study.md
│
├── CSS盒子/                       # 盒子模型（demo1 ~ demo11）
│   ├── demo1-优先级.html
│   ├── demo2-权重叠加计算.html
│   ├── demo3-盒子.html
│   ├── demo4-盒子-内容.html
│   ├── demo5-盒子-边框线.html
│   ├── demo6-盒子-尺寸.html
│   ├── demo7-版心居中.html
│   ├── demo8-综合案例-新闻列表.html
│   ├── demo9-外边距问题-合并.html
│   ├── demo10-外边距问题-塌陷.html
│   └── demo11-行内元素的内外边距的问题.html
│
├── CSS浮动/                       # 伪元素与浮动（demo1 ~ demo14）
│   ├── demo1-选择器-结构为类.html
│   ├── demo2-选择器-结构伪类-公式.html
│   ├── demo3-伪元素.html
│   ├── demo4-浮动.html
│   ├── demo5-体验-浮动.html
│   ├── demo6-浮动-特点.html
│   ├── demo7-浮动-案例.html
│   ├── demo8-综合案例-小米产品.html
│   ├── demo9-综合案例-导航.html
│   ├── demo10-受浮动影响的情况.html
│   ├── demo11-清除浮动-额外标签法.html
│   ├── demo12-清除浮动-单伪元素法.html
│   ├── demo13-清除浮动-双伪元素法.html
│   └── demo14-清除浮动-overflow.html
│
├── 定位/                          # 定位（demo01 ~ demo3）
│   ├── demo01-定位--相对.html
│   ├── demo2-定位-绝对.html
│   └── demo3-定位-绝对-父级定位.html
│
├── project_online Study/          # 综合项目：在线学习平台首页
│   ├── index.html
│   ├── CSS/
│   │   └── index.css
│   └── images/
│       ├── logo.png / banner2.png / btn.png / pic.png / user.png
│       ├── course01.png ~ course08.png
│       ├── top.jpg / left.jpg
│       └── bottom01.jpg ~ bottom04.jpg
│
└── README.md
```

## 🗂️ 章节说明

| 目录 | Demo 数量 | 学习内容 |
| --- | --- | --- |
| `HTML基础/demo1_Study` | 1 | HTML 基础入门 |
| `HTML基础/demo2_招聘` | 1 | 招聘页面案例、图片资源 |
| `HTML基础/demo3_跳转` | 3 | 超链接、页面跳转、音频与视频 |
| `HTML基础/demo4_列表` | 3 | 有序列表、无序列表、自定义列表 |
| `HTML基础/demo5_表格` | 4 | 表格、表头、结构标签、单元格合并 |
| `HTML基础/demo6_表单` | 9 | input、单选框、文本域、下拉菜单、label、文件上传、button |
| `HTML基础/demo7_语义化标签` | 2 | HTML 语义化标签及页面结构 |
| `HTML基础/demo8_字符实体` | 1 | HTML 字符实体 |
| `HTML基础/demo9_综合案例` | 2 | 表单、学生信息表综合练习 |
| `CSS基础` | 18 | CSS 引入方式、选择器、字体与文本样式 |
| `CSS进阶` | 20 | 复合选择器、伪类、背景、显示模式、CSS 三大特性 |
| `CSS盒子` | 11 | 优先级与权重、盒子模型、内外边距、版心居中 |
| `CSS浮动` | 14 | 结构伪类、伪元素、浮动、清除浮动 |
| `定位` | 3 | 相对定位、绝对定位、子绝父相 |
| `project_online Study` | 1 | 综合项目：在线学习平台首页（HTML + CSS） |

## ✅ 仓库说明

1. 每个文件夹对应一个独立的知识点或练习案例，文件按 `demoN-知识点` 命名。
2. 部分目录包含 `study.md`，用于记录对应章节的学习笔记。
3. `CSS基础`、`CSS进阶` 将 HTML 与 CSS 分目录存放；其余章节为单文件练习。
4. 本仓库主要用于个人学习、代码练习和学习轨迹记录。
5. 项目会随着学习进度持续更新。

## 🚀 本地运行

### 1. 克隆仓库

```bash
git clone https://github.com/Ko-369/web-learning.git
```

### 2. 进入项目目录

```bash
cd web-learning
```

### 3. 使用 VS Code 打开项目

```bash
code .
```

也可以直接使用文件管理器打开项目目录。

### 4. 运行 HTML 文件

本项目目前主要为静态 HTML 页面，因此 **不需要安装额外依赖**。

直接使用浏览器打开对应的 `.html` 文件即可查看效果。

例如：

```text
HTML基础/demo3_跳转/index.html
```

也可以在 VS Code 中安装 **Live Server** 插件，通过本地服务器运行 HTML 页面。

## 📝 学习笔记

部分章节目录中包含：

```text
study.md
```

主要用于记录：

- HTML 标签的基本语法
- 标签属性及使用方式
- 学习过程中遇到的问题
- 示例代码
- 易错点
- 知识点总结

## 🎯 后续学习计划

后续计划继续补充：

- [x] HTML 基础
- [x] HTML 列表
- [x] HTML 表格
- [x] HTML 表单
- [x] HTML 字符实体
- [x] HTML 综合案例
- [x] CSS 基础
- [x] CSS 进阶（复合选择器 / 背景 / 显示模式 / 三大特性）
- [x] CSS 盒子模型
- [x] CSS 浮动与定位
- [x] 综合项目：在线学习平台首页
- [ ] Flex 布局
- [ ] Grid 布局
- [ ] JavaScript 基础
- [ ] DOM 操作
- [ ] JavaScript 综合案例

## 📌 项目用途

该仓库仅用于个人前端学习、练习及知识整理。
