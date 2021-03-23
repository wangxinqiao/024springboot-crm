# 024springboot客户关系管理系统
024springboot客户关系管理系统


#### 介绍
CRM客户关系管理系统。本系统共分为三种角色：超级管理员、经理、销售人员；
超级管理员的功能主要有：
  公司资料：部门结构、销售目录；
  人员资料：销售人员、账号权限；
  客户资料：客户列表；
  销售跟踪：订单列表、报表统计；
  图表分析:销售与客户分析、销售失败分析；

源码获取： [**点此下载** ](http://www.shuyue.fun/?type=productinfo&id=173)

#### 环境需要
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目 
6.数据库：MySql 5.7版本；

#### 技术栈
1. 后端：SpringBoot;
2. 前端：layui+html

#### 使用说明
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中application.yml配置文件中的数据库配置改为自己的配置
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4. 运行项目，输入localhost:8080 登录
5. 管理员账户：superAdmin  密码123456  
   经理账户：user 密码：123456
   销售人员账户：laji_ma  密码：123456

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/093934_6f4f6ebd_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/093946_ccc89e66_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/093957_665800ca_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/094005_2deaa39c_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/094015_5eb3d6cc_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/094023_60becb5c_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/094032_2c0de97e_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/094041_eb6d528a_863230.png "屏幕截图.png")
