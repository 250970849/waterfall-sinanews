## 瀑布流新闻站
http://js.jirengu.com/furefoyuxi
## 懒加载原理
事件监听 当视窗外的img开始进入视窗时执行函数 修改接下来进入视窗的标签img属性
## 瀑布流原理
图片列数根据浏览器视窗宽度变化 每组图片从上一排图片中高度最低的一个开始定位 图片采用绝对定位 修改css中的left top来定位图片的位置 
## 实现原理
整体思路: 1.获取数据 2.将数据变为DOM结构,以瀑布流的方式部署到页面上 3.当页面滚动至底部再次获取数据循环
