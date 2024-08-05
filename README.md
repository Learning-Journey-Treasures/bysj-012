![gh_17810254f3db_258](https://github.com/user-attachments/assets/9305b4d0-f1ac-4ce8-9da8-e2b285c971e9)

**郑重声明：项目经过本地测试，确保可以运行。由于精力有限，不提供调试服务。项目仅供学习和毕业设计参考~**

#### 1.项目介绍
技术栈+工具：SSM + vue + uniapp + MySQL5 + Maven + IDEA2022 

系统角色： 管理员、卖家、普通用户

管理员：用户管理、卖家管理、公告信息管理、商品管理、订单管理、发货管理、举报管理、评价管理、留言管理、系统管理

卖家：商品管理、订单管理、发货管理、仲裁申请、留言板

普通用户：订单信息、商品信息、发货信息、仲裁申请、留言板
#### 2.项目部署
##### 2.1 后端部署

- 创建数据库，导入项目中的sql

- 根据本地数据库环境，修改数据库的连接信息 src/main/resources/config.properties 3-5行

- 创建Tomcat server，设置deployment标签下的Application context 路径为： /ssm5noeq

- 启动后端项目

##### 2.2 管理web

- 在idea的终端中，通过cd指令进入到前端的项目目录，即 src/main/webapp/admin

- 执行npm install 

- 执行 npm run serve  本地的Node版本是12， 太高了会报错

- 启动后，点击url，登录即可， 管理员账号密码： abo/123456

##### 2.3 小程序端

- 项目内提供了uniapp项目，即目录src/main/webapp/front， 这个留着学习用即可，可以自行编译，我们采用另外的方式

- 打开微信开发工具，导入项目 mp-weixin

- 选择测试号即可（你需要登录微信开发工具哦~）

- 登录即可（记得按提示选角色）普通用户账号密码： 花花/123456  卖家用户账号密码： t小木/123456 ，可以去表里自行查看
