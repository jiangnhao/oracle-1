# Oracle 数据库应用


## 内容说明

- PPT目录：各章节的PPT
- script目录：各章节的SQL语句及源码
- doc目录：参考文档
- book.pdf： 本书的PDF文档

## 实验服务器地址

```flow js
地址：202.115.82.8
数据库：pdborcl
system密码:123，所有密码都为123

成绩网址：http://202.115.82.8:1522

```
## SSH登录
```shell
$ ssh student@202.115.82.8
student@202.115.82.8's password:
[student@deep02 ~]$cat readme.txt

```
密码是123321qweewq
在Windows上登录需要ssh客户端，可以下载安装 : 
https://github.com/zwdcdu/oracle/raw/master/gitgfb_ttrar.rar

```sql
sqlplus system/123@pdborcl
sqlplus 你的用户名/123@pdborcl
```

## 网址
- Oracle Database 下载地址:

    http://www.oracle.com/technetwork/database/enterprise-edition/downloads/index.html

- SQL Developer 客户端工具下载地址:

    https://www.oracle.com/technetwork/developer-tools/sql-developer/downloads/index.html
    
- Oracle 12.2安装示例schema
    https://www.linuxidc.com/Linux/2017-08/146337.htm
    
## Git命令参考

### create a new repository on the command line
```shell
echo "# oracle" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/zwdcdu/oracle.git
git push -u origin master
```

### push an existing repository from the command line
```shell
git remote add origin https://github.com/zwdcdu/oracle.git
git push -u origin master
```