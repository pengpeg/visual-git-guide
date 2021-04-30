# 5h打通Git全套教程

## 内容

* **Git**
  1. Git介绍 分布式版本控制工具 VS 集中式版本控制工具
  2. Git安装 基于官网发布的最新版本2.31.1 安装讲解
  3. Git命令 基于开发案例 详细讲解git的常用命令
  4. Git分支 分支特性 分支创建 分支转换 分支合并 代码合并冲突
  5. IDE 集成Git

* **GitHub**
  1. 创建远程库
  2. 代码推送 Push
  3. 代码拉取 Pull
  4. 代码克隆 Clone
  5. SSH免密登录
  6. IDE集成Github
* **Gitee码云**
  1. 码云创建远程库
  2. IDE集成Gitee码云
  3. 码云连接GitHub 进行代码的复制和迁移
* **GitLab**
  1. GitLab服务器的搭建和部署
  2. IDE集成GitLab

## 第一章 Git概述

## 第二章 Git安装

## 第三章 Git常用命令

| 命令名称                                                  | 作用                                       |
| --------------------------------------------------------- | ------------------------------------------ |
| git config --global user.name 用户名                      | 设置用户签名                               |
| git config --global user.email 邮箱                       | 设置用户签名                               |
| <font color=#FF000>git init</font>                        | <font color=#FF000>初始化本地库</font>     |
| <font color=#FF000>git status</font>                      | <font color=#FF000>查看本地看状态</font>   |
| <font color=#FF000>git add 文件名</font>                  | <font color=#FF000>添加到暂存区</font>     |
| <font color=#FF000>git rm --cached 文件名</font>          |                                            |
| <font color=#FF0000>git restore --staged 文件名</font>    |                                            |
| <font color=#FF000>git restore 文件名</font>              |                                            |
| <font color=#FF000>git commit -m "日志信息" 文件名</font> | <font color=#FF000>提交到本地库</font>     |
| <font color=#FF000>git reflog</font>                      | <font color=#FF000>查看历史记录</font>     |
| <font color=#FF000>git log</font>                         | <font color=#FF000>查看详细历史记录</font> |
| <font color=#FF000>git reset --hard 版本号</font>         | <font color=#FF000>版本穿梭</font>         |

## 第四章 Git分支操作

同时并行推进多个功能开发，提高开发效率。

某一分支开发失败不会对其他分支有任何影响。

| 命令名称            | 作用                     |
| ------------------- | ------------------------ |
| git branch 分支名   | 创建分支                 |
| git branch -v       | 查看分支                 |
| git checkout 分支名 | 切换分支                 |
| git merge 分支名    | 把指定分支合并到当前分支 |



## 第五章 Git团队协作机制

## 第六章 GitHub操作

## 第七章 IDE集成Git

## 第八章 IDE集成GitHub

## 第九章 国内代码托管中心-码云

## 第十章 自建代码托管平台-GitLab



