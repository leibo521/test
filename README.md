# 这是学习git的测试库

Git是用来进行版本控制的工具,使用git可以很方便的进行文件版本的管理,但git只会监控__文本文件__的改变

## git的常用命令
```html
初始化仓库: git init
添加远程库: git remote add origin [远程库地址]
将文件添加到暂存区: git add [filename]/* (git会开始追踪文件的变化)
将文件提交到本地库: git commit -m "变更信息" [filename]/*
将文件提交推送的远程库: git push origin master
```