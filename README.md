# git
git学习笔记


# git配置
git config --global user.name [username]
git config --global user.email [email]
git config --list 查看

```
在终端输入:git config --global credential.helper store
然后git pull一次，输入一次用户名密码就会自动保存该用户名密码；

````




# 本地分支

查看当前分支
git branch


创建分支   
git branch <branchName>分支名


推送到远程
git push origin 分支名
(远程没有此分支会自动创建)