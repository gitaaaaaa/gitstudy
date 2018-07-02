```
$ git remote add origin git@github.com:lumeme/gitstudy.git
$ git push -u origin master // -u 关联, Git默认叫法origin远程库名字, 本地的master分支
 
```
登陆GitHub,创建一个空的仓库(右上角[+]按钮选[New repository]创建一个新的仓库-->添写仓库名称[Repository name]-->直接点击[Create repository]);

1. 一个已有的本地仓库 关联 一个远程库; git remote add origin <your repository>;

2. 把本地仓库的内容推送到GitHub仓库(第一次推送master分支的所有内容,远程库是空的),加上了-u参数,Git不但会把本地的master分支内容推送的远程新的master分支，还会把本地的master分支和远程的master分支关联起来。




   

