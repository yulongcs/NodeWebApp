
作者：Endy Yu
Email：yulongcs@hotmail.com

慕课网bootstrap+node.js+express+jade+mongodb打造下一代web应用程序。

架构•自动化流程：grunt、grunt-concurrent、grunt-contrib-watch、grunt-nodemon
•前端：Bootstrap、jQuery  后面会采用angular做为前端MVC 
•后端：node.js、express、jade、moment、underscore、mongoose、bcrypt、cookie-parser、express-session
•数据库：MongoDB



本地开发和运行1.安装 nodejs 环境和 npm，具体方法请自行参考其官网文档。
2.在项目根目录依次执行  npm install  和  bower install 安装依赖项，然后执行  grunt  即可启动开发服务器并调用系统浏览器打开 http://localhost:3000。
  a.npm install  async bcrypt-nodejs body-parser connect-mongo connect-multiparty cookie-parser crypto express express-session grunt grunt-concurrent grunt-contrib-jshint grunt-contrib-less grunt-contrib-uglify grunt-contrib-watch grunt-mocha-test grunt-nodemon jade moment mongoose morgan serve-static underscore --save
  b.bower install bootstrap (文件已存在，以可以省略)
  c.启动 MongoDB
  d.grunt 启动 app
  
3.默认数使用的 MongoDB 服务器地址为  mongodb://localhost/imooc 


功能模块• 首页电影展示 
• 电影查看 
• 用户的注册与登录 
• 后台电影录入 
• 后台电影管理列表 
• 后台注册用户列表 
• 搜索
