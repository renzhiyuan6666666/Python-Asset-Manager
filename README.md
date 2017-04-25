# Python资产管理练习项目，用于后期练手。
 ![image](http://s4.51cto.com/wyfs02/M02/89/2F/wKioL1gK_jSxA1n8AAD1q6VEeeg989.png)

# 运行环境

Python2.7

Django1.9（pip install django==1.9）

依赖模块：

MySQLdb（apt-get install python-mysqldb）

# 部署步骤
1.下载源码

git clone https://github.com/lizhenliang/DevOps.git

cd DevOps

2.修改数据库连接地址

vi mysite/settings.py   

3.生成数据库表

python manage.py migrate 

4.修改salt rest api连接地址

vi devops/salt_api.py 

salt配置：https://github.com/lizhenliang/Shell-Scripts/blob/master/salt-api-config.sh

5.创建登录用户名

python manage.py createsuperuser 

6.启动服务

python manage.py runserver 0.0.0.0:8888 

7.生成PV/UV图表测试数据脚本

https://github.com/lizhenliang/Shell-Scripts/blob/master/pv_uv_test_data.sh


