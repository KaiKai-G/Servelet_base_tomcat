﻿# 用户信息管理系统  
## 架构：三层架构（MVC设计模式）  
  1. 表示层(Web)：用户看的到界面，用户可以通过界面上的组件和服务器进行交互（JSP+Servlet）
  2. 业务逻辑层（Service）：处理业务逻辑的,调用Dao层方法和View层的参数/数据进行处理。
  3. 数据访问层（Dao）：操作数据存储文件，一些增删改查的具体实现。
  *  实体库（Model）：用来封装数据的实体类，通过set/get方法存和取。  
  
## 功能：
  * 用户的登录：账号、密码、验证码
  * 用户信息的添加
  * 用户信息的修改: 通过查找进行页面信息的回显，选择性的修改
  * 用户信息的删除: 1.删除一条 2.通过复选框多选/全选删除
  * 用户的条件搜索: 回显用户查询条件 
  * 分页用户的信息: 1.显示全部/查询到的用户个数和页码数 2.根据页码点击遍历用户 3.点击前一页、后一页  
    
### 用到的技术有:Servlet+JS+JSP+MySQL+JDBCTempleat+Duird+BeanUtilS+tomcat

### 全部功能的架构图都放到了Process_image中