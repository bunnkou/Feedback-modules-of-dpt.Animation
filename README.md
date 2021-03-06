# 客户反馈系统
![image](https://github.com/bunnkou/DHProjectApp/blob/master/Preview_1.png)
![image](https://github.com/bunnkou/DHProjectApp/blob/master/Preview_2.png)
![image](https://github.com/bunnkou/DHProjectApp/blob/master/Preview_3.png)

# 功能
1. 发布客户反馈信息，支持富文本编辑器、上传图片压缩、项目归类、指派查看人员等功能
2. 待阅视图，发布反馈后会根据指派人员生成对应通知，并且在指派人员登录系统后，可进入待阅视图中查看所有待阅信息
3. 查阅情况记录，当这些指派人员查阅过相关反馈后，记录其行为，管理员在此视图中查看所有项目的查阅情况
4. 群组功能，管理人员可对群组进行人员维护，群组可以在指派人员中选取
5. 工时表功能，管理人员可以对某段时间内的项目人员进行维护操作，可按时间段添加项目周期及人员；并可以选择时间段查看每个项目中的人员情况
6. 权限管理，管理人员对人员权限进行指派发布、查看、管理等权限

# 依赖
1. springmvc<br>
2. shiro<br>
3. alibaba.simpleimage<br>
4. ueditor<br>
5. mybatis<br>
6. bootstrap<br>
7. jquery<br>

# 开发工具
1. mysql 5.7<br>
2. tomcat 8.5<br>
3. eclipse<br>
4. notepad++<br>
5. chrome<br>

# 170624修改记录
1. 新增了权限管理视图，人员对应多角色的查询功能<br>

# 170720修改记录
1. 新增了工时表功能
2. 新增了插件 timecard.js

# 170727修改记录
1. 调整了工时表逻辑，按照时间段进行项目管理
2. 引入了 daterangepicker 插件用于时间段选择
3. 调整了 dh_timecard 表结构
4. 大幅度调整了 vwTimecard.jsp 视图内容
5. 修改了 timecard.js 插件，详情见 jquery-plugin-timecard 项目
