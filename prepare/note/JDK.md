#JDK安装与使用

##JDK安装包

1. 下载地址：[http://www.oracle.com/technetwork/java/javase/downloads/index.html]

2. 执行安装包

## 配置环境

环境变量设置：JAVA_HOME,PATH

PATH：命令行执行路径设置

Classpath：JAVA程序执行时class文件的搜索路径，JDK6默认为当前路径和jdk lib目录

方式1，环境变量：
set CLASSPATH = %CLASSPATH%;classpath1;classpath2;

方式2，编译时指定：
javac -classpath classpath1;classpath2;... 

##常用命令

* javac
* java