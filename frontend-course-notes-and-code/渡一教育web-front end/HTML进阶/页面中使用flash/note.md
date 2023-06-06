# 在页面中使用flash
以下两个元素任选其一
以下两者都是可替换元素

object

embed
MIME:多用途互联网邮件类型，即为，在互联网中通过文本的形式来确定资源的类型
比如：资源是一个jpg图片，mime:image/jepg
如何搜索？
百度mime，可以根据你要插入的文件格式，搜索对应的文本描述
示例代码：
1. 
 <object data='资源地址' type='文本描述'>
 下面的代码可以赋值：比如画面质量等
    <param name='quality' value='high'>
 </object> 

2. 
<embed quality='high'src='' type=''>

不同浏览器对于两者的兼容性不一样，为了保证能识别，这样写
<object data='资源地址' type='文本描述'>
    <param name='quality' value='high'>
    <embed quality='high'src='' type=''>
 </object> 