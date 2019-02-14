# qiansionmall

resource download:
http://learning.happymmall.com/

1.安装centOS 6.8 64位
2.安装jdk
rpm -qa | grep jdk 查看已经自带的jdk 然后卸载

卸载命令：
sudo yum remove XXX(查询jdk的结果)

赋予权限: sudo chmod 777 jdk-7u80-linux-x64.rpm
安装完成之后 配置环境变量 /etc/profile
使配置生效 source /etc/profile

3.安装tomcat(必须保证jdk先安装)
类似安装jdk,不同的是tomcat还需要配置tomcat字符集
进入安装目录,找到conf/server.xml
找到8080端口，在后面添加URIEncoding ="UTF-8"

4.安装Maven
版本3.0.5
配置环境变量

5.安装vsftpd
基本配置
防火墙配置:开放端口

6.安装Nginx
版本1.10.2

查看进程命令：
ps -ef | grep nginx
防火墙配置:开放端口

7.安装mysql
字符集的设置
自启动
防火墙配置:端口开放




