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

日期：2026年7月18日

学习内容：

1. HTML表单基础

- 学习form标签
  - 理解form用于收集用户输入信息
  - 了解表单是登录、注册等页面的基础结构

- 学习input标签
  - text：普通文本输入
  - password：密码输入
  - email：邮箱输入
  - radio：单选按钮
  - checkbox：多选按钮
  - button：按钮

- 学习label标签
  - 理解label用于描述输入框
  - 掌握for属性与input的id进行关联

- 学习textarea标签
  - 用于输入多行文本
  - 适用于个人简介、留言等内容

- 学习select和option
  - 制作下拉选择框
  - 理解option作为选择项

2. HTML表单结构设计

- 学习如何组织注册页面结构
- 理解HTML标签嵌套规则
- 了解页面结构应该保持清晰

3. Flex布局复习

- 复习display:flex
- 理解默认flex-direction为row
- 学习使用flex-direction:column让表单内容垂直排列
- 复习justify-content和align-items的作用


完成项目：

项目名称：

注册页面 HTML版


完成内容：

- 使用form创建注册表单
- 创建用户名输入框
- 创建密码输入框
- 添加性别选择
- 添加兴趣选择
- 添加个人介绍输入区域
- 添加注册按钮
- 添加兴趣下拉选择


项目中使用到：

HTML标签：

- form
- label
- input
- textarea
- select
- option
- button


CSS知识：

- display:flex
- flex-direction


遇到问题：

1. HTML标签关闭顺序错误

问题：

form和div嵌套时：

先打开的标签没有最后关闭，导致结构混乱。


2. 不理解radio和checkbox区别

问题：

一开始使用checkbox制作性别选择。

原因：

不知道checkbox用于多选，而radio用于单选。


3. id重复问题

问题：

男女两个选项使用了相同id：

gender

导致页面中id不唯一。


4. 个人介绍使用input

问题：

使用input制作个人简介。

原因：

不了解input只能输入单行文本。


5. Flex布局方向理解不足

问题：

使用：

justify-content:center

后发现表单元素全部横向排列。


原因：

没有理解Flex默认主轴方向为水平。


解决方案：

1. 学习HTML标签嵌套规则：

原则：

后打开的标签先关闭。


正确：

<div>

<form>

</form>

</div>


2. 理解表单控件区别：

radio：

用于互斥选择，只能选择一个。


checkbox：

用于多选，可以选择多个。


3. 保证id唯一：

修改重复id：

gender

为不同元素使用不同id。


4. 使用正确标签：

单行输入：

input


多行输入：

textarea


5. 理解Flex方向：

默认：

flex-direction:row

元素横向排列。


表单布局需要：

flex-direction:column

让元素上下排列。


明天计划：

Day5：HTML综合项目 + HTML知识整理


学习内容：

1. 复习HTML完整知识体系

- 基础结构
- 文本标签
- 图片
- 链接
- 列表
- 表单
- 语义化标签


2. 学习如何组合多个HTML模块


项目：

个人博客主页 HTML版


要求包含：

- header
- nav
- main
- section
- footer
- 图片
- 文章列表
- 技能列表
- 联系表单


目标：

能够独立使用HTML搭建完整网页结构，为后续CSS美化和JavaScript交互打基础。
