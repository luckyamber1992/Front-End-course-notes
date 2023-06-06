# 表单元素
一系列元素，主要用于收集用户数据

## input元素
输入框属性
- type属性：决定输入框的属性
- value属性：初始文本框内容信息
- placeholder:显示提示文本，文本框没有内容时显示，输入内容就会消失
* 针对单选框（radio）：通过设置name的值，让浏览器知道哪几个元素是一组

当type值为reset，button，submit时，input表示按钮

## select元素
下拉列表选择框
通常和option元素配合，用来表示选项
## textarea元素
文本域，多行文本框
## button
type:reset,submit,button
## 配合表单元素的其他元素
### label
- 显示关联
可以通过for属性将文字和input关联
<input id='radMale' name='gender' type='radio'>
<label for='radMale'>Male </label>
- 隐式关联
    在lebel中套input
    <label>
    <input name='' type=''>
    </label>

## datalist
数据列表
可以通过id将datalist与表单关联

### form 元素
包含其他表单元素
当提交表单时，会将form元素内部的内容以合适的方式提交到服务器
对开发静态页面意义不大

### fieldset元素
对表单元素进行分组

## 表达状态
readonly：只读，不会改变表单显示样式
disabled：禁用表单，会改变表单显示样式


