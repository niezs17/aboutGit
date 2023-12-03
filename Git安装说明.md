# Git安装说明

## 引言

### Git和GitHub概述

Git是一种分布式版本控制系统，用于跟踪、管理和协调项目中的变更。GitHub是一个基于云端的代码托管平台，它提供了许多与Git相关的功能，如代码托管、团队协作、问题跟踪等。本文将引导初学者使用Git和GitHub来管理项目。

### 为什么要进行版本控制？

版本控制是一种记录文件更改历史的系统，以便将来查看和回溯。对于软件开发来说，版本控制是至关重要的，因为它允许团队成员同时工作在同一个项目上，而不会互相干扰。它还使得跟踪和修复错误、回退到旧版本和理解项目历史变得更加容易。



## 准备工作

### 注册你的Github账号

1. 首先进入github官网 https://github.com/

   ![image-20231202163647275](C:\Users\NIEZS\AppData\Roaming\Typora\typora-user-images\image-20231202163647275.png)

2. 点击右上角的sign up(注册)，sign in是登录。

3.  填写自己的邮箱、密码、用户名等信息，然后用邮箱验证即可完成。



### Git的安装

我们需要在计算机上安装Git。以下是不同操作系统的安装方法：

- #### Windows

1. 访问Git官方网站：https://git-scm.com/downloads
2. 下载适用于Windows的Git安装程序。
3. 执行安装程序并按照指示完成安装。保留默认设置即可。

- #### macOS

1. 打开终端。
2. 使用Homebrew包管理器安装Git，输入命令：`brew install git`

- #### Linux（Ubuntu为例）

1. 打开终端。

2. 输入以下命令安装Git：`sudo apt-get update && sudo apt-get install git`

   

在windows环境下，具体安装步骤可以参考如下网址，一步一步来：https://blog.csdn.net/mukes/article/details/115693833。按照步骤完成后，右键任意一个文件夹，得到菜单中的以下内容，说明你已经安装成功了！！

![image-20231202163145351](C:\Users\NIEZS\AppData\Roaming\Typora\typora-user-images\image-20231202163145351.png)



### Visual Studio Code的安装

​	Visual Studio Code（VSCode）是一个流行的代码编辑器，支持Git和许多其他开发工具。

直接搜索Microsoft VSCode官网，从官网下载，确保万无一失。

#### 	为什么我们要安装vscode呢？

​	与传统的IDE相比，VSCode具有以下优点：

1. **轻量快速**：VSCode 启动迅速，占用资源相对较少，是一款轻量级的编辑器。
2. **丰富的扩展生态系统**：VSCode 支持丰富的扩展，几乎可以满足任何开发需求。你可以根据你的项目和语言选择安装相关的扩展，使得编辑器更符合你的工作流程。
3. **智能代码补全**：VSCode 提供强大的代码补全功能，可以根据你的代码上下文智能地补全代码，提高编码效率。
4. **内置 Git 支持**：VSCode 集成了 Git，你可以直接在编辑器中进行版本控制操作，查看提交历史，解决冲突等。



#### 在VSCode中安装Git Graph插件

安装 Visual Studio Code（VSCode）插件非常简单，下面是安装GitGraph的基本步骤，以后安装任何插件都同理。

打开 Visual Studio Code：启动你的 Visual Studio Code 编辑器。

打开扩展视图：在 VSCode 的左侧边栏中，点击活动栏中的 "扩展" 图标（或者按 `Ctrl+Shift+X` 或 `Cmd+Shift+X`）。

![image-20231202164202349](C:\Users\NIEZS\AppData\Roaming\Typora\typora-user-images\image-20231202164202349.png)

搜索插件：在 Extensions 视图的搜索框中输入你想要安装的插件的名称或关键字，这里我们输入Gitgraph。VSCode 将会显示相关的插件列表。

![image-20231202164343754](C:\Users\NIEZS\AppData\Roaming\Typora\typora-user-images\image-20231202164343754.png)

安装插件：在插件详细信息页面，你会看到一个安装按钮。点击该按钮，VSCode 将开始下载并安装插件。安装完毕后，插件一般会立即启用，若未启用，就在上面同意界面点击启用。

![image-20231202164517165](C:\Users\NIEZS\AppData\Roaming\Typora\typora-user-images\image-20231202164517165.png)

重启 VSCode：在插件安装完成后，VSCode 通常会提示你重新启动以应用插件的更改。重启后，随便打开一个文件夹，如果能在左下角看到如图所示GitGraph按钮，说明安装成功。

![image-20231202164838214](C:\Users\NIEZS\AppData\Roaming\Typora\typora-user-images\image-20231202164838214.png)

