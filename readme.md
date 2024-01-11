# 基于SSM的宿舍管理系统1

## 1、项目介绍

基于SSM的宿舍管理系统拥有两种角色，分别为管理员和宿管，具体功能如下：

管理员：学生管理、班级管理、宿舍管理、卫生管理、访客管理、用户管理等

宿管：宿舍管理（人员信息管理、维修登记）、卫生管理、访客管理等


## 2、项目技术

后端框架：SSM（Spring、SpringMVC、Mybatis）

前端框架：Layui、jsp、css、JavaScript、JQuery

## 3、开发环境

- JAVA版本：JDK1.8，其它版本理论上可以
- IDE类型：IDEA、Eclipse、Myeclipse都可以。推荐IDEA与Eclipse
- tomcat版本：Tomcat 7.x、8.x、9.x、10.x版本均可
- 数据库版本：MySql 5.x
- 是否为maven：否
- 硬件环境：Windows 或者 Mac OS


## 4、功能介绍

### 4.1 登录

![登录](https://www.codeshop.fun/Typora-Images/20220519211525.jpg)

管理员和宿管可以通过此界面登录系统，后台将自动识别用户类型

### 4.2 管理员模块

![管理员-班级管理](https://www.codeshop.fun/Typora-Images/20220519211617.jpg)

![管理员-宿舍管理](https://www.codeshop.fun/Typora-Images/20220519211619.jpg)

![管理员-访客管理](https://www.codeshop.fun/Typora-Images/20220519211621.jpg)

![管理员-学生管理](https://www.codeshop.fun/Typora-Images/20220519211627.jpg)

![管理员-用户管理](https://www.codeshop.fun/Typora-Images/20220519211628.jpg)

- 班级管理：管理员可以通过班级编号、班级名字、辅导员名字筛选班级信息，并能增加、删除和修改班级信息，还能够导出为excel文件
- 宿舍列表管理：管理员可以通过宿舍编号、宿舍楼名字、管理员姓名筛选宿舍信息，并能增加、删除和修改宿舍信息
- 访客管理：管理员可以通过姓名和电话筛选访客记录，并能够添加访客记录
- 用户管理：管理员可以通过用户名和用户级别筛选用户，并能增加、删除和修改用户
- 学生管理：管理员可以通过学号等筛选学生，并能增加、删除和修改学生信息

### 4.3 宿管模块

![宿管-访客管理](https://www.codeshop.fun/Typora-Images/20220519212205.jpg)

![宿管-宿舍卫生管理](https://www.codeshop.fun/Typora-Images/20220519212208.jpg)

![宿管-宿舍信息](https://www.codeshop.fun/Typora-Images/20220519212210.jpg)

![宿管-维修登记](https://www.codeshop.fun/Typora-Images/20220519212213.jpg)

![宿管-学生卫生](https://www.codeshop.fun/Typora-Images/20220519212216.jpg)

- 卫生管理：卫生管理分为宿舍卫生管理和学生卫生管理：
  * 宿舍卫生：宿管可以通过宿舍编号和宿舍楼筛查宿舍信息，并能添加、删除、修改宿舍的卫生记录
  * 学生卫生：宿管可以通过学号、姓名和寝室编号筛查学生，并能增删改查学生卫生记录
- 访客管理：宿管可以通过姓名和电话筛选访客记录，并能够添加访客记录



## 6、获取方式

关注公众号： **程序员王不二**，回复 “ **宿舍1**” ，即可获取完整版的项目代码。

 ![](https://www.codeshop.fun/Typora-Images/202205281253739.png)

* [springboot项目](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzkwMjM1MjM0Ng==&action=getalbum&album_id=2387377898791223296#wechat_redirect)

* [简单无框架项目](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzkwMjM1MjM0Ng==&action=getalbum&album_id=2387378317047218183#wechat_redirect)

  

