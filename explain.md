# 自行车站点管理系统

## 运行登录
- 打开MongoDB
- 运行server.js
- 运行成功后会自动建立所需数据库以及相应书记
- 打开网页输入www.localhost:3000
- 注册账号
- 用注册的账号登录
- 注意：在有网络的情况下正常运行

## 表格介绍
该数据库总共分为4张表格位于myMongoose中
- users:骑行者表
- stations:站点信息表
- menber:会员信息表
- power:管理员信息表
密码存于mydb中
- login:密码信息

## 系统介绍
1. 系统界面分为登录页面和管理界面
2. 管理界面分为站点管理、会员管理、和管理员管理
3. 站点管理包括：骑行记录，站点信息
4. 会员管理包括：会员基本信息表
5. 管理员管理分为：权限分类以及权限管理（尚未完成）

骑行者信息界面包括增删改查功能，站点信息以及后面一系列表格都具有这样的功能应为代码重复就链接了骑行者信息

## 代码框架
- node.js+mongoose+layui+axios
- layui官方网址：
- https://www.layui.com/doc/
- axios官方网址：
- http://www.axios-js.com/docs/
- 系统github网址
- 


## 界面展示
### 登录界面
![Alt text](/images/login.png)
### 桌面
![Alt text](/images/desk.png)
### 骑行记录界面
![Alt text](/images/users.png)
### 站点信息
![Alt text](/images/station.png)
### 会员
![Alt text](/images/menbers.png)
### 管理员权限
![Alt text](/images/guan.png)
### 添加界面
![Alt text](/images/add.png)
### 修改界面
![Alt text](/images/change.png)