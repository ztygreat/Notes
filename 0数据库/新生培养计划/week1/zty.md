## 一、四个数据库的安装与简单使用
### 1、MySQL
#### 1、获取mysql镜像
指令：docker pull mysql:5.7
#### 2、创建mysql容器
指令：docker run -itd -v /home/zhangtingyi/ztyMySQL/:/workspace/ztyMySQL -p 33060:3306 -e MYSQL_ROOT_PASSWORD=root --name ztyMySQL mysql:5.7

其中，-e：初始化mysql用户，并将root密码设置为root。
#### 3、登录
指令：mysql -u root -p
#### 4、简单使用
测试git分支合并
