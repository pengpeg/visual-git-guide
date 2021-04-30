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

git合并冲突：

当当前分支和要合并的分支对一个文件有不同修改时，进行merge时文件内出现

```
<<<<<<< HEAD
当前分支内容
=======
要合并的分支内容
>>>>>>> 要合并的分支名
```

可以使用`git merge --abort`退出合并，或

直接在冲突文件内将上面`<<<<<<<`和`>>>>>>>`这部分内容手动修改为最终结果，然后使用`git add`和`git commit`提交此文件，然后再合并分支，手动修改的结果就是合并结果。

## 第五章 Git团队协作机制

* **团队内协助**

* **跨团队协助**

  fork仓库

## 第六章 GitHub操作

1. 创建远程仓库（推荐与本地库同名）

2. 远程仓库操作

   | 命令名称                                                     | 作用                                                         |
   | ------------------------------------------------------------ | ------------------------------------------------------------ |
   | git remote -v                                                | 查看当前所有远程地址别名                                     |
   | git remote add 别名 远程地址                                 | 起别名                                                       |
   | <font color=#FF0000>git push 别名 分支</font>                | <font color=#FF0000>推送本地分支上的内容到远程仓库</font>    |
   | <font color=#FF0000>git clone 远程地址</font>                | <font color=#FF0000>将远程仓库的内容克隆到本地</font>        |
   | <font color=#FF0000>git pull 远程库地址别名 远程分支名</font> | <font color=#FF0000>将远程仓库对于分支最新内容拉下来后与当前本地分支直接合并</font> |

   `git remote add vgg-1 https://github.com/pengpeg/visual-git-guide.git` : 直接使用地址过长，使用别名代替

   `git push vgg-1 master`: 将本地库的master分支推送到远程库上（vgg-1可以直接使用地址）

   `git pull vgg-1 master`: 将远程端的master分支拉取到本地仓库

3. 克隆远程仓库

   `git clone https://github.com/pengpeg/visual-git-guide.git`: 拉取代码、初始化本地库、创建别名（默认别名origin）

4. 

## 第七章 IDE集成Git

## 第八章 IDE集成GitHub

## 第九章 国内代码托管中心-码云

## 第十章 自建代码托管平台-GitLab



