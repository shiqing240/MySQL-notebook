# MySQL数据库

## 01.MySQL课程介绍

为什么学？数据

怎么学，收获？

SQL、事务、存储引擎、索引、SQL优化、锁、日志、主从复制、读写分离、分库分表


## 02.基础-课程内容-数据库相关概念

数据库 DataBase(DB)

存储数据的仓库，数据是有组织的进行存储。



数据库管理系统 DataBase Management System(DBMS)

操纵和管理数据库的大型软件



SQL  Structured Query Lanague(SQL)

操作关系型数据库的编程语言，定义了一套操作关系型数据库统一**标准**



主流的关系型数据库管理系统

Oracle、MySQL、SQL Server

## 03.基础-概述-MySQL安装及启动

版本：社区版，商业版

启动与停止

方式一：在命令行窗口输入service.msc，找到MySQL进程，直接点击启动或停止。

方式二：在命令行窗口输入net start mysql80和net stop mysql80



客户端连接

方式一：MySQL提供的客户端命令行工具

方式二：系统自带的命令行工具执行指令

mysql [-h 127.0.0.1] [-p 3306] -u root -p

**注意：使用这种方式需要配置环境变量**

## 04.基础-概述-数据模型

![image-20240427102730391](C:\Users\史庆\AppData\Roaming\Typora\typora-user-images\image-20240427102730391.png)

关系型数据库(RDBMS)

概念：建立在关系模型基础上，由多张相互连接的**二维表**组成的数据库。

二维表：![image-20240427111226567](C:\Users\史庆\AppData\Roaming\Typora\typora-user-images\image-20240427111226567.png)

特点：

1、使用表存储数据，格式统一，便于维护。

2、使用SQL语言操作，标准统一，使用方便。



![image-20240427111658128](C:\Users\史庆\AppData\Roaming\Typora\typora-user-images\image-20240427111658128.png)


