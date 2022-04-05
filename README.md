# 项目说明

基于hdfs的分布式可扩展文件管理系统设计与开发

本课程分为三个阶段：

1.阶段一：利用docker，以集群（或伪集群）的方式搭建hdfs分布式文件系统；

2.阶段二：熟悉利用python/golang接口向阶段一搭建的文件系统进行文件上传、下载、查询、删除；

3.阶段三：利用web技术及阶段二成果建立小型网盘，实现文件的可视化上传、下载、查询、删除；
<<<<<<< HEAD

使用技术：hdfs、docker、python/golang、http、python.flask(原javascript（es6）、html5、css3)等；
后端运行环境：X86_X64、Hadoop3.X；
管理端运行环境：基于H5的WebApp，仅需支持PC分辨率；"	无（可做需求确认沟通）	工程代码一套、操作手册、测试用例、需求规格说明书、建设方案、汇报PPT	

文件增删改查接口

阿里对象存储接口

使用web接上网盘

前端javascript

硬件x86

## 问题

### 需求

全部文件都做成二进制

文件上传形式：IO流

### 后端

后端运行环境：Hadoop3.X

docker打包，直接上传到公司服务器

结点数量建议在 3-4 个，每个结点都放单独的docker

使用 python/golang 做接口

### 前端

实现点击上传就行，上传下载

不需要文件预览（后期可添加图片预览和视频预览）