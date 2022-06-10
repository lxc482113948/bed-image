# markdown 语法实例

[Taio 官网教程可以绘制图表等等](https://docs.taio.app/#/cn/)

## 1 强调

星号与下划线都可以，单是斜体，双是粗体，符号可跨行，符号可加空格

```js

**一个人来到田纳西**
__毫无疑问__

*我做的馅饼
是全天下*

_最好吃的_
```

## 2 分割线

```js

---
***
___

```

## 3 引用

，符号后的空格可不要

```js
   >
```

内层符号前的空格必须要

```js
>引用
 >>引用中的引用
```

## 4 标题：Setext 方式

```js

大标题
===
小标题
---
```

## 5 标题：Atx 方式

```js

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

```

## 6 无序列表

符号之后的空格不能少，-+\*效果一样，但不能混合使用，因混合是嵌套列表，内容可超长

```js

- 无序列表
- 无序列表
- 无序列表
- 无序列表：我很长。我也很长！那比一比啊

```

## 7 有序列表

数字不能省略但可无序，点号之后的空格不能少

```js

1. 有序列表
2. 有序列表
3. 有序列表
8. 有序列表
```

## 8 文字超链：Inline 方式

[github](https://github.com/)

## 10 自动链接

尖括号
<https://github.com/ >

## 11 代码：行内代码

在第一行后指定编程语言，也可以不指定

```js

```

## 15 表格

| Tables        |      Are      |   Cool |
| ------------- | :-----------: | -----: |
| col 3 is      | right-aligned | \$1600 |
| col 2 is      |   centered    |   \$12 |
| zebra stripes |   are neat    |    \$1 |

- 或者

| 项目     | 价格   |
| -------- | ------ |
| Computer | \$1600 |
| Phone    | \$12   |
| Pipe     | \$1    |

## 16 其他

## 段落缩进（空格）

```js

半方大的空白&ensp;或&#8194;看，飞碟
全方大的空白&emsp;或&#8195;看，飞碟
不断行的空白格&nbsp;或&#160;看，飞碟
&emsp;&emsp;段落从此开始。

```

## 更改字体、大小、颜色

<font color=Blue> Markdown 语法 </font>
`size：规定文本的尺寸大小。 color：要渲染的颜色`

```js

<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=red>我是红色</font>
<font color=#008000>我是绿色</font>
<font color=Blue>我是蓝色</font>
<font size=5>我是尺寸</font>
<font face="黑体" color=green size=5>我是黑体，绿色，尺寸为 5</font>

```

<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=red>我是红色</font>
<font color=#008000>我是绿色</font>
<font color=Blue>我是蓝色</font>
<font size=5>我是尺寸</font>
<font face="黑体" color=green size=5>我是黑体，绿色，尺寸为 5</font>

### 标签

`行内标签 `

## 为文字添加背景色

由于 style 标签和标签的 style 属性不被支持，所以这里只能是借助 table, tr, td 等表格标签的 bgcolor 属性来实现背景色。故这里对于文字背景色的设置，只是将那一整行看作一个表格，更改了那个格子的背景色（bgcolor）

<font color=Blue> Markdown 语法 </font>

```js

<table><tr><td bgcolor=yellow>背景色yellow</td>
 <td bgcolor=#FF4500>这里的背景色是：OrangeRed，  十六进制颜色值：#FF4500， rgb(255, 69, 0)</td>
</tr></table>

<p align="right">右对齐</p>
<center>居中</center>
<p align="left">左对齐</p>
```

<font color=Blue> Markdown 语法 </font>

<table><tr><td bgcolor=yellow>背景色yellow</td>
 <td bgcolor=#FF4500>这里的背景色是：OrangeRed，  十六进制颜色值：#FF4500， rgb(255, 69, 0)</td>
</tr></table>

## 对齐方式

```js

<p align="right">右对齐</p>
<center>居中</center>
<p align="left">左对齐</p>

```

<p align="right">右对齐</p>
<center>居中</center>
<p align="left">左对齐</p>

你可以联系“Xuechao”以了解更多细节。 **邮箱**：<font color=Blue size=6> myxuechao163.com </font>
