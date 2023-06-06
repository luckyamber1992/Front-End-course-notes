# 更多选择器

## 更多伪类选择器
1. first-child
选择第一个子元素,范围很广，只要是父元素的第一个子元素都会被选中
应用：li:first-child选中子元素li中的第一个子元素li。对于这个例子，选中目标元素要同时满足两个条件：（1）有li（2）li是父元素的第一个子元素
first-of-type：
选中子元素中，第一个type，比如：a:first-of-type,表示选择中子元素中第一个a元素
2. last-child
跟上面对应
3. nth-child
选中指定的第几个子元素
4. nth-of-type
a:nth-child(5):表示选中a元素，且为第五个子元素
## 伪元素选择器
1. first-letter
选中元素中的第一个字母
如：p::first-letter{}
2. first-line
3. selection
选中被用户框选的文字
p::selection{
    此处可以设置用户框选文字格式
}