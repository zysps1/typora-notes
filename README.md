### <center>Typora学习笔记

[TOC]

#### 标题

> 用“#”表示
>
> 快捷键：ctrl+1,2,3,4,5

#### 居中

> 居中可用center标签

#### 强调

> 使用*强调*

#### 加粗

> 使用**加粗**

#### 下划线

> 使用u标签：<u>下划线</u>

#### 有序列表

> 1. 输入数字+空格即可
> 2. 正常 

#### 无序列表

> 输入“-”+一个空格
>
> - 萝卜
> - 白菜

#### 代码块

> 语法高亮
>
> ```java
> public statc void main(String []args){
>  System.Out.PrintLn("生活不止眼前的苟且“)
> }
> ```

#### 引用

> 使用">"+空格

#### 代码一句

> 使用`，
>
> `code`

#### 转义

> 使用反斜杠\

#### 分隔线

> 使用多个“-”
>
> ------

#### 创建表格

> 使用快捷键：ctrl+T
>
> | 学科 | 姓名 | 成绩 |
> | :--- | ---- | ---- |
> |      |      |      |
> |      |      |      |
> |      |      |      |

#### 插入URL链接

> 使用尖角括号包裹
>
> <www.baidu.com>

#### 日期

> 2017.12.30
>
> 2017\.12\.30

#### 字体、字号与颜色

> <font face="宋体" size=3 color=#0099ff> 宋体字</font>
>
> <font color=#00ffff size=4 face="黑体">黑体字</font>
>
> ```html
> <font color=#00ffff size=3 face="黑体">黑体字</font>
> ```

#### 页内超链接-锚点

> 目录{#index}
>
> 跳转到[目录](#index)

#### emoji表情

> emoji表情使用:EMOJICODE:的格式，详细列表可见 
> <https://www.webpagefx.com/tools/emoji-cheat-sheet/>
>
> :dizzy:
>
> :sleeping:
>
> :wink:

#### 注释

> 对某个低于进行注释[^注]

率妻子[^1]邑人来此绝境

#### 数学表达式

> 输入“$“即可
> $$
> \sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}
> $$
> $\sqrt{x^{2}}$
>
> 具体可以参考 markdown编辑器使用LaTex数学公式（<https://link.jianshu.com/?t=http%3A%2F%2Fblog.csdn.net%2Ftestcs_dn%2Farticle%2Fdetails%2F44229085>）
>
> latex数学符号详见：[常用数学符号的 LaTeX 表示方法](https://www.mohu.org/info/symbols/symbols.htm)

#### 常用数学符号表示

> $a_{1}$ 
>
> $x^{2}$
>
> $e^{-\alpha t}$
>
> $a^{3}_{ij}$
>
> $ e^{x^2} \neq {e^x}^2$
>
> $\sqrt{x}$
>
> $\sqrt{x^{2}+\sqrt{y}}$
>
> $\sqrt[3]{2}$
>
> $\surd[x^2+y^2]$
>
> $ \overline {m+n}$
>
> $\underline{m+n}$
>
> $\underbrace{a+b+\cdots+z}_{26}$
>
> $\vec a$
>
> $\vec {AB}$
>
> $1\frac{1}{2}$
>
> $\frac{x^{2}}{k+1}$
>
> $\sum_{i=1}^{n}$
>
> $\int_{0}^{\frac{\pi}{2}}$
>
> $\prod_\epsilon$

#### 希腊字母

> $\alpha$
>
> $
>
> $\theta$
>
> $\beta$
>
> $\gamma$
>
> $\delta$
>
> $\epsilon$
>
> $\eta$
>
> $\mu$
>
> $\sigma$

#### 插入图片

> 直接拖进去就行
>
> ![微信公众号二维码](C:\Users\zysps\Desktop\微信公众号EYE视界AI世界\微信公众号二维码.jpg)

#### 删除线

> 两个波浪线
>
> ~~我被删除啦~~

#### 表情

> 使用“：+英文”，如`:happy`
>
> :happy:
>
> :cry:

#### 目录列表

> 输入“【toc】”生成目录

#### 绘制流程图

> ```mermaid
> graph LR
> A[方形] --> B[圆角]
> B --> C{条件a}
> C --> |a=1| D[结果1]
> C --> |a=2| E[结果2]
> F[横向流程图]
> ```
>
> ```mermaid
> graph TD
> A[方形] --> B(圆角)
> B --> C{条件a}
> C --> |a=1| D[结果1]
> C --> |a=2| e[结果2]
> F[竖向流程图]
> ```
>
> ```flow
> st=>start: 开始框
> op=>operation: 处理框
> cond=>condition: 判断框（是or否）
> sub1=>subroutine: 子流程
> io=>inputoutput: 输入输出框
> e=>end: 结束框
> st->op->cond
> cond(yes)->io->e
> cond(no)->sub1(right)->op
> ```
>
> ```sequence
> 对象A->对象B: 对象B你好吗？
> Note right of 对象B: 对象B的描述
> Note left of 对象A: 对象A的描述
> 对象B->对象A: 我很好
> 对象A->对象B: 嗯呐
> ```





