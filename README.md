# swift 在线实验环境

## 软件简介

Swift是一种通用编程语言，采用现代化的方法构建安全，性能和软件设计模式。

Swift项目的目标是为系统编程，移动和桌面应用程序，扩展到云服务创建最佳可用语言。最重要的是，Swift旨在使开发人员更容易地编写和维护正确的程序

所属类别是编程语言

license:APACHE LICENSE, VERSION 2.0 

特点:

1.安全

2.快速

3.富有表现力

## 软件官网

https://swift.org/

## Dockerfile 使用方法

开始REPL

Swift需要一点额外的安全权限来运行REPL。以下命令创建一个短暂的容器，将终端连接到它并启动Swift REPL。尝试预发行版的好方法！
```
docker run --cap-add sys_ptrace -it --rm swift swift
```
从Docker Hub拉出Docker图像：
```
docker pull swift
```
从图像创建容器并附加它：
```
docker run  -it --name swiftfun swift:latest /bin/bash
```
开始并附上您的图片：

用名字开始你的形象 swiftfun
```
docker start swiftfun
```
然后附加它
```
docker attach swiftfun
```
## 资源链接

- http://www.runoob.com/swift/swift-tutorial.html
- https://swift.org/
