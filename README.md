# 前言
**java的编辑器市面上有很多，不过我对eclipse相对熟一点。每次配置eclipse都需要去找博客和重新配置一些插件，自我感觉有点麻烦，所以在这里将经常用的插件的安装，使用和配置文件记录下来以便以后可以快速进入开发节奏。这里重点关注的是编码规范和查找bug,至于JDK、TOMCAT、maven这些就不在赘述了。**

## 资源下载
github:https://github.com/flypangzhi/eclipse_plug-in

## 插件具体配置

### 1、checkstyle

CheckStyle是SourceForge下的一个项目，提供了一个帮助JAVA开发人员遵守某些编码规范的工具。它能够自动化代码规范检查过程，从而使得开发人员从这项重要但枯燥的任务中解脱出来。它可以根据设置好的编码规则来检查代码。比如符合规范的变量命名，方法体的最大行数，重复代码检查等等。

安装使用可参考：

[在eclipse上Checkstyle的安装和使用](https://blog.csdn.net/ccboy2009/article/details/32318781)

备注：在我的资源中有离线安装包和阿里的模板xml文件，xml文件直接配置即可。

### 2、阿里巴巴Java开发规约
阿里出品的规约主要包含格式化规范、注释规范和代码编写规范，里面有个插件可以帮助我们扫描代码并给出一些实质性的建议，这个对于写出优质的代码十分有帮助。

[p3c插件安装和使用教程](https://www.cnblogs.com/lsysy/p/9954785.html)

其中在我的git资源中，ali_eclipse_codeStyle_codeTemplate.xml 和 ali_eclipse_codeStyle_formatter.xml 代表的是阿里的注释模板和格式化模板；my_eclipse_codeStyle_codeTemplate.xml 和 my_eclipse_codeStyle_formatter.xml 代表的是自定义的注释模板和格式化模板


### 3、Eclipse安装FindBugs插件与使用
FindBugs 是一个静态分析工具，它检查类或者 JAR 文件，将字节码与一组缺陷模式进行对比以发现可能的问题。有了静态分析工具，就可以在不实际运行程序的情况对软件进行分析。

[FindBugs插件与使用](https://blog.csdn.net/inforstack/article/details/69388759)

### 4、对于eclipse的字体设置操作，好像不能配置成xml文件导入，所以每次都得手动去调整。如果哪位发现了快速调整字体的资源，麻烦告诉我下，感激不尽。

# 结语
随着工作年限的增加，感觉养成良好的工作态度和编码习惯非常重要。一旦养成了良好的习惯，你将受用无穷。
