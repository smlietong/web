<ArticleTopAd></ArticleTopAd>

## 安装并配置git

### 1.在Windows中下载并安装git

-git官网：<https://git-scm.com/downloads>

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
> 2、执行 *git init* 命令

### 2.检查文件的状态


