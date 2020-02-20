1.  ## git 是什么 ?
    git 是一个开源的分不式版在控制系统，代码管理工具
2. ## 什么情况需要版本控制 ？
   备份文件
   记录历史
   回到过去
   团队协作
3. svn 是集中式的  git 是分布式的

4. ## git 分哪几个区
1.可以将git简单的分为三个区域 1、工作区(working directory) 2、暂缓区(stage index) 3、历史记录区(history)

5. git init 初始化本地版本库  
   git status  查看你的工作区的文件上传状态
   add . 全部上传 (提交到暂存区)  绿色说明暂存区发生变化 红色说明工作区反生变化
   git commit -m 添加描述信息 (本地版本库)  提交代码
   <!-- git push origin master 推送到远程仓库 github -->
   git remote  add origin 仓库地址 (远端的仓库地址) (查看关联的状态 git remote -v)
   码云管理工具需要 拉取远端代码 git pull origin master  从远端拉取  (如果拉去失败的话 )
   git  push  origin  master  推送到远程仓库

## 提交作业
1. git clone 地址
2. cd (进入文件)
3. git checkout -b 刘慧宇 创建并切换分支  git checkout
作业文件夹 
add .
 git commit -m ""
git push origin 

##  npm 是什么 ？
node package manger (版管理器)

## nodejs 
- COMMONJS规范,只能用在服务端，只能用在服务端
- nodejs里面一个js文件及模块，require  exports  module.exports


- exports


                                        