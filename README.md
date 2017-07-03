
## html课程：
1. 前端所用的三种语言以及三者之间的关系：html（内容）\css（样式）\js（行为）
2. 使用标签编辑页面内容，常用标签

#### 目标：
1. 熟悉常用的标签及其对应的语义；
2. 能够针对不同布局写出对应的结构

#### 任务：
在百度脑图上记录知识点：  http://naotu.baidu.com/

=================================

## css课程：

1. 引入规则：css样式文件三种引入方式，css文件，style标签，style属性（内联样式）
2. 选择器：id、class、tag、子选择器、其他选择器
3. 样式覆盖规则
	a. 后面样式覆盖前面样式（书写顺序: 同一文件内样式的书写顺序，不同文件引入顺序）
	b. 内联样式优先级高于style标签和css文件
	c. id > class > div (权重叠加规则， 选择器种类（id选择器，class选择器，标签选择器）)
	d. !important
	e. 如何排查写的样式没有应用到页面上（通过浏览器查看样式保存到样式文件，样式是否被覆盖）
4. 常用css样式：
	a. css盒模型
	b. width，heigh，margin，padding，line-height， font-size， font-weight，color，text-align，background，border
	c. 块级元素水平居中
	d. 行内元素水平居中
	e. 行内元素垂直居中
5. 布局：a. 整体布局，局部布局;  b. 一栏布局、两栏布局、三栏布局 c. 布局用到的css

#### 目标：
1. 熟悉常用样式属性；
2. 能够完成一个普通页面的排版

=================================

## js课程：
1. js基础：
	- 命名规则，
	- 算术运算符：`+、-、*、/、% 、++、 — `
	- 逻辑运算符`& 、||、 !`
	- 比较运算符：`<、 >、 <=、 >=、 !=、 ==、！==、===`
	- 三目运算符：`？ ：`
	- 基本数据类型：`boolean、number、string、null、undefined`
	- 复杂数据类型：`object、function、array`
	- 控制语句：`if...else 、 while、switch…case 、for、for…in、break、continue、return`
	- 注释：单行、多行
	- 报错： throw、try…catch
2. Function
3. Dom:
	- 获取DOM: getElementById/getElementsByClass/getElementsByTag/querySelector/querySelectorAll
	- DOM方法：操作html和css
	- jquery: 如何引入、如何使用
4. jquery常用方法、jquery插件

#### 目标：
1. 可以书写常用js效果（下拉框、选项卡切换、其他）

=================================

#### 作业1：
1. Js由那几部分组成
2. 请写出两种将js应用到网页的方式
3. 如何定义一个变量？ 变量的命名规则有哪些？
4. js的常用几种数据类型有哪些？
5. 写出js的算术运算符
6. 写出js的比较运算符
7. 写出js的逻辑运算符
8. js的注释有几种？分别写出对应的注释符
9.  如题：
  `var i = 100;
	i++;
	j = i++;
	y = ++j;`请问： y和j分别是多少
10. 请写出break和continue的区别

==================================

#### 作业2：
1. 保存个人信息，包括姓名，性别，职位，个人简介（要求：使用保存；明明要有意义，禁止使用a/b/c/d）;
2. 保存微信群里所有学员信息（要求：使用数组保存；）
3. 在保存的学员信息中，如果是男，输出1；如果是女，输出2（要求：分别使用if...else/switch...case写出对应的代码段）
3. 将所有学员信息通过for循环的方式打印出来
