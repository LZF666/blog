# Linux命令行的简单使用



- **命令行需要牢记的基本单词**
- **命令行的缩写**
- **新建文件**
- **删除文件**
- **复制文件**
- **查找文件**


-------------------

## 命令行需要牢记的基本单词
哪怕英语再差也要死死牢记的单词哟

 - 文件夹    `directory` 
 - 文件    `file` 
 - 新建   `make`
 - 删除   `remove`
 - 移动   `move`
 - 复制    `copy`
 - 罗列    `list`
 - 链接    `link`
 - 查找    `find`
 - 触摸    `touch`

## 命令行的缩写

> 在Linux中，一般都使用缩写，缩写的规则是省略A,E,I,O,U五个元音字母，留下方便记忆的几个字母即可（会有例外）  。


### 表格

*如下*：

| 命令      |    全称 | 缩写  |
| :-------- | :--------:| :--: |
|创建文件夹  | make directory | mkdir   |
| 删除     |   remove |  rm  |
| 移动     |    move | mv  |
| 复制     |    copy | cp  |
| 罗列     |    list | ls  |
| 链接     |    link | ln  |

*需要注意的是windows系统默认不支持链接，所以这个可以忽略不看*

## 新建文件


**在C盘下新建一个文件夹**　
备注：作者使用的是git bash
> 从根目录下切换到C盘
![从根目录下切换到C盘](http://img.blog.csdn.net/20170805234204486?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaHVhbHVodWFsdQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

> 新建一个名字为projects的文件夹
![](http://img.blog.csdn.net/20170805234426507?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaHVhbHVodWFsdQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

这样我们就有了一个空文件夹
![这里写图片描述](http://img.blog.csdn.net/20170805234642528?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaHVhbHVodWFsdQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)


## 删除文件
> 删除projects这个文件夹
![](http://img.blog.csdn.net/20170805234919586?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaHVhbHVodWFsdQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

## 复制文件
> 复制projects这个文件夹，将它里面的内容全部复制到一个叫做b的文件夹内。
> 我事先在projects文件夹内放了个t叫做task的文件夹，这样它就不是空文件了。
![这里写图片描述](http://img.blog.csdn.net/20170805235532869?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaHVhbHVodWFsdQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

使用这个命令，打开c盘可以看见出现了一个b文件夹，它里面的内容和projects一模一样。
![这里写图片描述](http://img.blog.csdn.net/20170805235652237?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaHVhbHVodWFsdQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

## 查找文件
这里只介绍一种方法：按照文件名来查找
| 命令      |    意思解读| 
| :-------- | :--------:| 
|find / -name 1.txt  | 在根目录下查找一个叫做1.txt的文件 | 
| find /etc -name 1.txt    |  在根目录的下一级目录——etc目录下查找文件1.txt | 
| find /etc -name '\*my*'     |    在etc这个目录下查找文件名里还有my这个字符串的文件 | 

*转载请注明出处以及作者，相关来源：饥人谷*

---------

[1]: http://math.stackexchange.com/
[2]: https://github.com/jmcmanus/pagedown-extra "Pagedown Extra"
[3]: http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference
[4]: http://bramp.github.io/js-sequence-diagrams/
[5]: http://adrai.github.io/flowchart.js/
[6]: https://github.com/benweet/stackedit
