# 实验一 MySQL的安装与使用
操作系统：ubuntu；使用docker安装mysql容器使用。

## Part1：使用Docker安装MySQL容器
* 下载mysql镜像
	
	> docker pull mysql:5.7
	
* 创建mysql容器
	
	> docker run -itd -v /home/zhangtingyi/ztyMySQL/:/workspace/ztyMySQL -p 33060:3306 -e MYSQL_ROOT_PASSWORD=root --name ztyMySQL mysql:5.7

	其中，-e：初始化mysql用户，并将root密码设置为root。

* 进入容器
	
	> docker exec -it ztyMySQL bash
	
* 登录
	
	> mysql -u root -p
	
* 使得mysql可以远程访问
	```sql
	#修改加密mysql规则
	代码区块
	#刷新
	flush
	```
## Part2: mysql的基本操作
### Step1：

## 遇到的问题

