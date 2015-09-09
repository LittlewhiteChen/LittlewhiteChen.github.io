---
layout: post
title:  "强大的Git和Github，我学习的一些总结"
date:   2015-09-10 00:06:05
categories: Git Github
excerpt: Git以及Github，CMD命令行。
---

* content
{:toc}



#Git以及Github

接触Github的时间并不长，大概是今年暑假开始的吧，开始学的时候，因为英文不是很好，所以学的很艰难。但是有用的东西就是有很多困难也要攻克，学习git和github的过程中也是我提高英语的机会，正好六级还是要再刷分的。

**重点是整理一下学习Git和Github的一些知识**



## CMD命令行

因为这个两个软件或者说仓库（平台），离不开命令行的操作，命令行的话首先是做基本的`cmd`命令行，最初是会文件操作，比如如何进入到指定文件夹，那就是`cd`命令了
* 进入磁盘，cd c：
* 进入指定文件夹 cd kay/chen/me 
* 返回文件夹 cd..
* 创建文件夹 md 
* 递归删除文件夹 rd  
* 删除文件 del 
* 拷贝文件 copy 
* 拷贝目录  xcopy 
* 移动文件或者目录 move  
* 恢复被删的文件 undelete

## Git命令行


Git是一个分布式的版本控制系统。


### 初始化

我基本都是使用的github自带的git工具，首先的设置登陆信息了

    $ git config --global user.name "Your Name"
    $ git config --global user.email "email@example.com"

### 建立创库

版本库又名仓库，英文名repository

**创建版本库的步骤：**

在Git Shell进入工程项目的根目录；
输入git init，初始化该根目录为一个git repo，可以看到多了一个.git的文件夹
输入git add . ，将该目录下所有的文件及文件夹添加到本地的repo

1、先找一个合适的地方创建一个空白目录

> 创建本地仓库直接在本地建立文件夹

2、通过`git init`命令把这个目录变成Git可以管理的仓库：

    $ git init
    Initialized empty Git repository in /d/mygit/.git/

3、把文件添加到版本库

* 添加命令：


    $ git add (文件名.后缀）或者添加所有 git add ./* 
    

> 执行上面的命令，没有任何显示，这就对了，Unix的哲学是“没有消息就是好消息”，说明添加成功。

### 缓存区操作

4、提交版本到缓存区，通知命令：(通过commit命令告诉Git，已经将文件提交到仓库,)git 

    $ git commit -m "执行的操作描述"
    git commit -m 'description'
    **git add命令可多次使用，添加多个文件；git commit可一次提交很多文件**

### 远程创库操作

5、本地git仓库关联GitHub仓库 : 

    git remote add origin git@github.com:han1202012/TabHost_Test.git ;
    
6、 提交到GitHub中 : 
    
    git push -u origin master ;//操作主分支的话，直接git push

## 操作远程已经有的仓库

1、不用关联GitHub仓库, 直接从GitHub冲克隆源码到本地, 项目根目录也不用创建;

-- 从GitHub上克隆项目到本地 :

    git clone git@github.com:han1202012/NDKHelloworld.git , 
    
**注意克隆的时候直接在仓库根目录即可**


2、用再创建项目根目录 ;

-  添加文件 :git add ./* , 将目录中所有文件添加;
-  提交缓存 :git commit -m '提交';
-  提交到远程GitHub仓库 : git push -u origin master ;

3、之后修改提交 : 

-  与GitHub远程仓库同步 :git pull ;
-  查看文件变更 : git status ;
-  提交代码到本地缓存 : git commit -m 'description';
-  提交代码到远程GitHub仓库 :git push ;
