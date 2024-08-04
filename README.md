# digisimlab-open

### 介绍
本项目是基于Digital仿真软件的计算机组成原理实验指导书及相关资源。

Digital仿真软件是一种用于设计和仿真数字逻辑电路的教育工具，它来自开源项目 [https://github.com/hneemann/Digital](https://github.com/hneemann/Digital/)，可从该项目的Release页面下载其最新发行版[Digital.zip](https://github.com/hneemann/Digital/releases/latest/download/Digital.zip/)，也可从本项目的software文件夹下载v0.30版。

### 在线阅读

在线阅读网址：[https://digisimlab-open.pages.dev/](https://digisimlab-open.pages.dev/)。
2024年5月Gitee Pages暂停服务之前发布在：[https://fpga-lab.gitee.io/digisimlab-open](https://fpga-lab.gitee.io/digisimlab-open)。

### 离线阅读

将项目代码下载到本地，进入`site`文件夹，双击`index.html`在浏览器中打开。

关于项目代码下载方法，建议在电脑中安装Git，以方便获得后续的更新。如果暂时不想安装Git，也可以直接登录Gitee或GitHub网站下载。下面分别介绍这两种方法。

#### 使用Git获取

1. 安装Git

    下载并安装 [Git for Windows](https://git-scm.com/download/win)。 
    如果遇到问题可阅读[官方文档](https://git-scm.com/book/zh/v2/%E8%B5%B7%E6%AD%A5-%E5%AE%89%E8%A3%85-Git)。

2. 打开GitBash终端

    在想要存放项目代码的文件夹上右键点击 `Git Bash Here` ，打开GitBash终端。或者从Windows开始菜单启动GitBash，用 `cd` 命令进入想要存放项目代码的文件夹。

3. 下载实验材料

    在GitBash终端中执行下面的命令。

    ```bash
    git clone https://gitee.com/fpga-lab/digisimlab-open.git
    ```
    或：
    ```bash
    git clone https://github.com/fpgaxlab/digisimlab-open.git
    ```

4. 更新实验材料

    以后如果需要获取最后的更新，在GitBash终端中执行下面的命令进入jurv-open文件夹后拉取更新的部分。

    ```bash
    cd digisimlab-open
    git pull
    ```
#### 从gitee或GitHub网站下载

以gitee网站为例。

1. 注册为[gitee](https://gitee.com)用户并登录；

2. 转到[digisimlab-open](https://gitee.com/fpga-lab/digisimlab-open)项目，点击 `克隆/下载` 按钮，再点击 `下载ZIP` 。

3. 将压缩包解压到本地。
   
4. 如果以后网站上有更新，重复上述操作。


### 许可 | License

[CC-BY-NC-SA：署名-非商业性使用-相同方式共享 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)