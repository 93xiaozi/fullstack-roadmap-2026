# fullstack-roadmap-2026
编程成长档案 + AI 导师的教学记录 + 项目作品集

fullstack-roadmap-2026
│
├── README.md              # 我的学习路线
│
├── learning-log           # 每日学习记录
│
├── javascript              # JS学习代码
│
├── react                   # React项目
│
├── nodejs                  # 后端代码
│
├── database                # 数据库练习
│
└── projects                # 完整项目

```markdown
日期：2026年7月18日

学习内容：

1. CSS基础
- 理解CSS作用：
  - HTML负责网页结构
  - CSS负责网页样式

2. CSS引入方式
- 学习外部CSS文件引入
- 掌握HTML通过<link>连接CSS文件

3. CSS选择器
- 标签选择器
- class选择器
- 理解选择器如何定位HTML元素

4. CSS常用样式
- color：设置文字颜色
- background-color：设置背景颜色
- width：设置元素宽度
- height：设置元素高度
- font-size：设置字体大小
- font-weight：设置字体粗细
- text-align：设置文字对齐

5. CSS盒模型
- 理解网页元素本质是一个盒子
- 学习：
  - content（内容区域）
  - padding（内边距）
  - border（边框）
  - margin（外边距）

6. CSS装饰效果
- border-radius：设置圆角
- box-shadow：设置阴影效果

7. Flex布局
- 理解Flex作用：
  - 控制父元素中子元素的排列方式
- 学习：
  - display:flex 开启Flex布局
  - flex-direction 控制排列方向
  - justify-content 控制主轴排列
  - align-items 控制交叉轴排列
  - gap 控制元素间距

8. Flex重点理解：
- justify-content:
  - flex-start：靠左排列
  - center：居中排列
  - space-between：两端对齐
  - space-around：元素周围自动分配空间

- align-items:
  - 控制元素垂直方向对齐


完成项目：

项目名称：

个人开发者主页 v2.0


完成内容：

- 使用HTML搭建个人主页结构
- 创建独立style.css文件
- 使用CSS美化页面
- 添加：
  - 页面背景
  - 卡片宽高
  - 字体样式
  - 圆角效果
  - 阴影效果
- 使用Flex布局完成：
  - 头像和个人信息横向排列
  - 内容垂直居中


遇到问题：

1. Flex布局理解不清楚

问题：

使用：

justify-content: space-around

无法让头像顶格排列。


2. 不理解不同Flex属性的区别

例如：

- justify-content
- align-items
- gap


3. CSS练习中发现：
只学习选择器无法完成完整页面设计。

项目中需要使用：

- 宽高
- 背景
- 圆角
- 阴影

但是这些知识需要提前学习。


解决方案：

1. 理解Flex布局核心概念：

Flex作用于父元素，用来控制子元素排列。


2. 明白属性作用：

- justify-content：
控制主轴方向排列

- align-items：
控制交叉轴方向排列

- gap：
控制子元素之间距离


3. 解决头像无法顶格问题：

space-around会自动给元素两侧添加空间，因此不会贴边。


改为：

```css
.profile{
    display:flex;
    align-items:center;
    gap:20px;
}
```

或者：

```css
justify-content:flex-start;
```

实现靠左排列。


4. 调整学习方式：

以后学习顺序改为：

知识点学习
→ 对应小练习
→ 使用已学知识完成项目

避免项目出现未学习知识。


明天计划：

Day3：JavaScript基础入门

学习内容：

1. JavaScript是什么
2. JS如何连接HTML
3. 变量和数据类型
4. 基础运算
5. 函数初步理解
6. DOM基础

练习：

- 修改网页文字
- 点击按钮改变内容

项目：

制作第一个交互网页：

网页计数器 v1.0

目标：

让网页从“静态页面”变成“可以操作的页面”。
```

