# typechoSticky
**Typecho 文章置顶插件。支持分类置顶。**

原作者: http://kan.willin.org/typecho/ (网站不可访问) ,已经停止更新了。在Github也没有找到源码，于是重新修改上传了一份。

重新修改增加了 分类文章置顶、单独分类文章置顶的功能。
优化了一下原有默认[置顶]的CSS风格

### 使用方法
下载解压至 ** usr/plugins ** 目录，文件夹重命名为：**Sticky**

代码很简单，修改的话，也有相应的注释。

### 最终样式
![置顶风格](http://og5z0vu2y.bkt.clouddn.com/typecho/typechozd.jpg)

如须显示，加一段代码在 article 后面

类似<br>
` <article class="post" itemscope itemtype="http://schema.org/BlogPosting"><?php $this->sticky() ?>`

记得在首页(index.php)和(archive.php)页都加上
