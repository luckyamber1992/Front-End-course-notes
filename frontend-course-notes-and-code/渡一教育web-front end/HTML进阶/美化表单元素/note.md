# 新的伪类
1. focus
元素聚焦时的样式
- tabindex：通过设置tabindex的值决定切换focus的顺序
2. checked:单选或者多选框被选中的样式
该属性无法控制颜色本身，因为他是可替换元素
可以通过设定其下一个兄弟元素的颜色来控制
## 常见用法
1. 应用到重置代码中
2. 设置textarea是否允许调整页面
- textarea属性resize：
- both两个方向都可以调整尺寸
- ：none都不可以
- ：horizontal
- ：vertical
3. 文本框边缘到内容的距离
调整方式1:
pading
方式2:
text- indent（首行缩进）
4. 

## 几个非相关‼️知识点
1. 表单元素都是行盒
2. text-align可以设置行盒/行块盒居中
3.+选择器：选中下一个兄弟元素；～选中后面所有的兄弟元素