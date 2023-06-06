# 伪类选择器nth-child
## 示例
.mian .container .movies .movie-item:nth-child(2n) {
}表示只选中第2n个子元素
.mian .container .movies .movie-item:nth-child(2n+1) {
}表示只选中奇数个子元素
## 特殊元素选择器
选中元素中的第一个字母,从而改变其字体/大小
.mian .container .movies .movie-item .score::first-letter{}
## display:list-item和display:block区别
display:list-item为元素内容生成一个块型盒，随后再生成一个列表型的行内盒。其效果就和ul中出现项目列表符号一样。通俗地说就是会在内容前面自动加上黑点，而display:block则不会出现黑点。
