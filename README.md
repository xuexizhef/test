README
===
简介:GitHub的markdown语法在标准的markdown语法基础上做了扩充，称之为`GitHub Flavored Markdown`。简称`GFM`.<br>
为了更好的展示，文章中是展示效果，实现代码看源码。

# 目录
* [分割线](#分割线)</br>
* [标题](#标题)</br>
* [文本](#文本)</br>
    * 普通文本
    * 单行文本
    * 多行文本
    * 文字高亮
    * 换行
    * 斜体
    * 粗体
    * 删除线



## 文本
### 1. 换行
结尾加两个空格  
+回车
\<br\>，<br>
\<br\>
### 2. 文字加高亮  
* 语法  
	>键盘左上角，数字1左边的点号来标记\`高亮\`
* 效果  
	>`高亮`  
### 3. 单行文本
* 语法  
	>在一行开头加1个Tab或4个空格
* 效果  
	单行文本








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

### 表格：
* 语法  
   >表头\|表头\|  
   >----\|---\|  
   >内容\|内容\|  
* 效果  
   >表头 | 表头|  
   >--------|-------|  
   >内容|内容|  

### 分割线：
* 语法
   >\*\*\*
   >\-\-\-
   >\_\_\_
* 效果  
   >***  
   >---  
   >___  
### 标题：
* 语法
   >\#  
   >\#\#  
   >\#\#\#  
* 效果  
   ># 一级标题  
   >## 二级标题  
   >### 三级标题  
   >#### 四级标题  
   >##### 五级标题  
   >###### 六级标题  
