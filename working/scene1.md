```
$ git init //初始化git仓库

$ git st // 查询有变更的文件

$ git add  <file> 或者 . // 增加文件到暂存区 (file 文件名, '点'提交全部变更的文件)

$ git st // 查询待提交的文件

$ git commit -m "" // 提交暂存区到仓库区(引号内填写本次提交的说明)
 
```
在本地创建一个空目录(进入该目录-->鼠标右键-->点击git dash here);

1. 通过git init命令把这个目录变成Git可以管理的仓库,当前目录下多了一个.git的目录;

添加文件到Git仓库，分两步：

2. - 用命令git add告诉Git，把文件添加到仓库;

   - 用命令git commit告诉Git，把文件提交到仓库.

![工作区和暂存区](https://cdn.liaoxuefeng.com/cdn/files/attachments/001384907702917346729e9afbf4127b6dfbae9207af016000/0)
   

