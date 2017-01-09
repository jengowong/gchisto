# gchisto


#####Gchisto:
用于分析gc日志的一款强大工具。


Gchisto的maven版本。
svn官方地址：[https://svn.java.net/svn/gchisto~svn](https://svn.java.net/svn/gchisto~svn)

更多说明：
[http://wengyingjian.github.io/blog/2015/12/29/java-performance-gclog/](http://wengyingjian.github.io/blog/2015/12/29/java-performance-gclog/)

不过这个工具似乎没怎么维护了，存在不少 bug，
使用过程发现识别不了 JDK 1.7 GC 日志的 Young GC，
还有一些 NullPointer 错误。
整体来说，只能观察某些参数。