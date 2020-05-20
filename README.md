# HotLinux
个人常用的Linux操作

## 1.关闭Centos7防火墙  
```
systemctl stop firewalld #暂时关闭  
systemctl disable firewalld #禁止开机启动  
```
## 2.关闭Selinux  
```
vi /etc/sysconfig/selinux  
改#SELINUX=enforcing  
为SELINUX=disabled  
执行：setenforce 0  
查看：getenforce  
```
## 3.安装mongo  
见
```
https://github.com/BoolWang/PythonMongo  
```



  
