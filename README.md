# Sequelize-Auto-egg

本库仅为生成`egg-sequelize`中可用的model而建立,详细使用方式请见 [https://github.com/sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto)

## bug

存在问题：
[mssql用户名和密码未传递提示无法连接数据库](https://github.com/sequelize/sequelize-auto/issues/360)
临时解决解决方法：
修改 tedious 库，lib/connection.js
将默认参数连接身份验证加上
