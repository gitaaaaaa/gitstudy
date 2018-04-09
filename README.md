### 安装Git

```
$ git config --list  显示当前Git配置
$ git config -e  查看url及分支
$ git config -e --global  编辑Git配置文件（user/alias/？filter "lfs"）
```
### 创建版本库

```
$ git init  初始化git仓库
```
### 增加文件

```
$ git add [file] [file]...  添加指定文件到暂存区，或指定文件夹（且子目录下必须有子文件）
$ git add .  添加当前目录的所有文件到暂存区
```
