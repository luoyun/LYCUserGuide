LuoYunCloud 用户手册
===================

目前主要是 LuoYunCloud 的中文用户手册。使用 Publican 工具发布。

如何生成用户手册：

1. 安装 publican 工具 ( [安装方法](http://jfearn.fedorapeople.org/en-US/Publican/2.7/html/Users_Guide/chap-Users_Guide-Installing_Publican.html) )

2. 获取本项目

    git clone git://github.com/luoyun/LYCUserGuide.git

3. 进入 LYCUserGuide 目录，发布 html 格式：

    publican build --formats html --lang zh-CN 
