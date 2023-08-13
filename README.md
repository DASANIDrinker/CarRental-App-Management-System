# Management System

> A Vue.js project<br>
> <br>
> A Management System written in javascript. It is designed to help the employee at the car rental company to update, check and delete orders and other informations

## Build Setup

``` bash

# download Wechat Developer Tool
https://developers.weixin.qq.com/miniprogram/en/dev/devtools/stable.html

# open file inside Wechat Developer Tool and click on Compile button to run the code

```

## 项目简介
租车应用后台管理系统

## 分支管理
master/main：主分支，线上项目打包使用
develop：开发分支， 本地开发使用， 每一次发布新的版本前，需要将develop分支代码合并到master上
develop-> merge -> master:
  1. 保存develop代码，并提交到github
  2. git checkout master // 切换到master分支
  3. git pull origin master // 从github拉取master分支最新代码,确保没有任何冲突
  4. git merge develop // 本地master合并develop代码，确保没有任何冲突，有冲突的话以comming code为准
  5. git push origin master // 合并完代码，提交到github master 分支

创建其他分支：
git branch 分支名
git checkout 分支名 // 切换到该分支
