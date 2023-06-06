## 透明度
1. opacity，它设置的是整个元素的透明度，取值0-1
见test1.html
2. rgba
## 鼠标样式
cursor：pointer/auto（让浏览器自己控制样式）/e-size（调整大小）
如果用图片作为格式：图片后缀设置为ico，如：target.ico，应用方式：cursor:url(图片路径),auto(如果图片链接失效，使用浏览器默认样式)
## 盒子隐藏
1. display：none
如果属性值为none，可能影响页面上其他盒子的排列
2. visibility:hidden生成盒子，只是从视觉上移除盒子，盒子仍然占据空间
## 背景图
何时使用？
1. 当图片属于网页内容时，必须使用img元素
2. 当图片仅用于美化页面时，必须使用背景图
### 背景图涉及的css属性
1. background-image
见bg1.html
url:要相对于css文件路径来书写
默认情况下，背景图会无限重复
2. background-repeat
: no repeat禁止图片重复
3. background-size
预设值:contain保证图片一定在框里；cover
或者：百分数
4. background- position：center
雪碧图：为了减少渲染时间，散落的小图会被合并为一张图，并且被浏览器缓存起来
利用background- position选取雪碧图中的小图标
5. background-attachment
：fixed可以将其固定位置于视口
见bg2.html
6. 背景颜色和背景图混用
7. 速写属性
background：接各种属性

