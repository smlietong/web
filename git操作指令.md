<ArticleTopAd></ArticleTopAd>

## 安装并配置git

### 1.在Windows中下载并安装git

git官网：<https://git-scm.com/downloads>

### 2.配置用户信息

```
git config --global user.name "用户名"

git config --global user.email "你的邮箱"

```

### 3.检查配置信息

```
<!-- 查看所有的全局配置项 -->
git config --list --global

<!-- 查看指定的全局配置 -->
git confit user.name
git config user.email

```
### 4.获取帮助信息

```
<!-- 想要打开git config 命令的帮助手册 -->
git help config

<!-- 想要获取 git config 命令的快速参考 -->
git config -h
```
## git 的基本操作

### 1.在现有目录中初始化git仓库

> 1.在项目目录中，通过鼠标右键打开 “git bush”

>  2、执行 **git init** 命令

### 2.检查文件的状态

>可以使用 **git status** 命令行查看文件处于什么状态。

```bash
git status
```
>用精简的方式显示文件状态
```bash
git status -s // -s 是 --short 的简写形式
```
### 3.跟踪新文件

>使用命令 **git add** 开始跟踪一个文件

```bash
git add 文件名 // 你想添加的文件的名字

git add .  // 一次性将文件加入到暂存区
```
### 4.提交更新

> 将暂存区的文件提交到Git仓库

```bash
git commit -m "提交消息（一般是文件的备注信息）"
```
