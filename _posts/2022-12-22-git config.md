# 设置命令 git config ：

## 仓库级别：仅在当前本地库范围内有效

* git config user.name  "xxx"
* git config user.email ""xx@sample.com"

*设置后信息保存于：项目路径/.git/config*

## 系统用户级别（--global）：登陆当前操作系统的用户范围

git config --global user.name  "xxx"
git config --global user.email  "xx@sample.com"

*设置后信息保存于：~/.gitconfig*

**注意：**

* 级别优先级：就近原则，仓库级别优于系统用户级别

* git设置的用户名和邮件地址和远程仓库github的账号是没有任何关系的！
