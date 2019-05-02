# markdown2


## markdown之链接
- 外部链接： 语法 [name] (url地址) 两个括号要紧贴在一起  
如：[百度](http://www.baidu.com)

- 内部链接
  1. 链接仓库的其他文件： 语法[name] (path)  
如：[doc](./MarkDown.md)
  2. 链接本文档的其他部分：语法[name] (demo.md#代码块-demo)

## 引用式链接
同一地址出现多次；避免多次重复动作和修改;把链接原型写在另外的地方，直接引用就好  
* 外部链接  
如：[百度][baidu]

## 图片
语法：![alt] (url text)  
atl:如果图片不能正常显示就显示atl内容；text：提示文字，即鼠标移到图片时浮动的文字  
如：![百度](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1556810746381&di=8518bac011eeeef9ad59e1809a979020&imgtype=0&src=http%3A%2F%2Fa2.att.hudong.com%2F44%2F39%2F01300533954471133541393744904.jpg "百度网站")


<!-- 下面是本文档中用到的链接 -->
[百度]:http://www.baidu.com
[baidu]:http://www.baidu.com
[demo]:demo.md