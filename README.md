KBEngine-Python-Tips
===================================

github地址（海外）:https://github.com/likecg2010/KBEngine-Python-Tips

开源中国地址(中国镜像):http://git.oschina.net/likecg/KBEngine-Python-Tips



这个项目是为了给KBEngine服务端编写Python脚本的时候，让IDE有语法提示。

## 1.用法
1.1下载项目之后，把tips目录下的所有文件拷贝到python安装目录的Lib下即可使用，比如windows平台上的，C:\Python34\Lib。


1.2使用Python IDE编辑器就可以出现语法提示了。


1.3写Baseapp的python脚本的时候，导入请写


from  BaseApp import KBEngine #IDE语法提示时候用，放入服务端时候，注释掉这行


\#import KBEngine #放入服务端时候，启用这行



语法提示的时候请用第一行的导入语句，完成脚本编写之后，注释掉，用启用第二行的语句。因为实际源于KBEngine模块

1.4写Cellapp的python脚本的时候，导入请写

from  CellApp import KBEngine #IDE语法提示时候用，放入服务端时候，注释掉这行


\#import KBEngine #放入服务端时候，启用这行

语法提示的时候请用第一行的导入语句，完成脚本编写之后，注释掉，用启用第二行的语句。因为实际源于KBEngine模块

1.5建议是使用Pycharm做Python IDE编辑器，提示效果最好，可以提高开发效率。

## 2.Pycharm语法提示效果
2.1 想要重写继承父类的子类的函数，鼠标右键Generate,可以选择重写哪个函数。

2.1图

列表列出父类可供重写的方法
![](http://t2.qpic.cn/mblogpic/e40d9421ab85418772a0/2000)

点击想要重写的方法，Pycharm生成重写的方法
![](http://t2.qpic.cn/mblogpic/b4cb7833b91f6aa7788e/2000)




2.2 调用父类函数，可以语法提示

2.2图
语法提示效果
![](http://t2.qpic.cn/mblogpic/5e88bbe757ce36afbdbe/2000)



2.3 在函数上按住Ctrl+Q键可以看到函数的相关文档

2.3图
文档提示效果
![](http://t2.qpic.cn/mblogpic/8f48fd6888c3a9f366a6/2000)

#### **备注，项目中的两个Python脚本文件只是用于IDE提示，里面只是函数的签名和文档，没有实际运行的效果，如果项目存在错漏，请大家帮助完善。
