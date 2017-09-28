README
===
简介:GitHub的markdown语法在标准的markdown语法基础上做了扩充，称之为`GitHub Flavored Markdown`。简称`GFM`.<br>
为了更好的展示，文章中是展示效果，实现代码看源码。

## 目录
*[分割线](#分割线)

********
### 分割线
***
---
___


大标题
===
中标题
---

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

这是文本，
普通换行无法换行的，<br>
要使用\<br>

  全角文本前面有空格，方便排版

    前面加两个TAB，实现单行文本

文字加背景，1左边的`高亮`点号

[文字超链接](www.baidu.com)

\*表示原点符，例如：
*苹果
*梨子

前面加TAB分级
*水果
  *梨子
  *葡萄
  
缩进效果符号 >
>数据结构
>>树
>>>二叉树
>>>>平衡二叉树
>>>>满二叉树

>也可以给文本加竖杠
>就像这样
>标记它了
>不一样了吧

引入图片：
![图片信息](www.baidu.com/img/bdlogo.gif)
引用自己git的图片：https://github.com/ 你的用户名 / 你的项目名 / raw / 分支名 / 存放图片的文件夹 / 该文件夹下的图片

给图片加上超链接：baidu标识符是自己起的，但是上下一定一样
[![baidu]](http://baidu.com)
[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo" 

代码高亮：代码开头和结尾，加数字1左边的三个点
```
<html>
    <head></head>
    <body></body>
</html>
```

