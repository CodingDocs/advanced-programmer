昨天晚上下班之后，突然想整理一下自己离不开的哪些 Mac 软件，想着以后有个记录也方便自己日后查阅。之前我也整理过，不过都不是很全面，就是碰到一两个觉得还不错的就加进了自己的收藏夹。

因为分享的过于仓促（见文末），本期内容一定还有很漏掉了很多优秀的工具/软件。欢迎在评论区留言补充，另外本文也同步到了我的仓库：https://github.com/Snailclimb/programmer-advancement ，点击阅读原文即可访问！

### 命令行工具

1. **[iTerm2](https://www.iterm2.com/)**  : 终端工具 替代 Mac 自带的 Terminal
2. **Zsh** :交互式命令行 shell。查看当前安装版本：`zsh --version `。
3. **[Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh)** :更优雅地管理 zsh 配置。伟大的工具！说白了就是 **zsh**  的基础上扩展了一些功能，让你使用起来更加舒服！如果需要安装  Oh My Zsh 的需要首先安装 Zsh 。
4. **[FinalShell](http://www.hostbuf.com/t/988.html)** ：SSH工具,服务器管理,远程桌面加速软件,支持Windows,macOS,Linux。被朋友圈的众多人安利的一个工具（ps:我目前还没玩转，没感觉特别强大的地方，感觉一个软件功能太多实际上不是一件好事，这个软件占用的内存也比较大，然后就卸载了）。

### 开发工具

**IDE:**

1. **IDEA** :这个用来写 Java 最牛逼的开发工具，不用多说了吧！
2. **[VSCode](https://code.visualstudio.com/)** :强大的编辑器！不只是前端开发利器，里面提供的插件也很多。

**数据库：**

1. **[Sequel Pro](https://www.sequelpro.com/)** ：简单小巧的MySQL数据库管理工具。个人觉得是Mac中MySQL数据库管理工具中最好用的一个，不过有一些可以容忍的小bug比如关闭一个页面导致其他页面闪退。
2.  **[Robo 3T](https://robomongo.org/)**:  非常好用的 MongoDB 数据库可视化管理工具。
3. **[Postico](https://eggerapps.at/postico/)** : PostgreSQL  数据库管理工具。
4. **[TablePlus](https://tableplus.com/)** ：强大的关系型数据库管理工具。支持常见的关系型数据库入 MySQL, PostgreSQL, SQLite 等等。
5. **[DataGrip](https://www.jetbrains.com/datagrip/)** ：jetbrains 旗下跨平台的数据库管理工具(Win、 Mac OS、Linux皆适用)。同时支持多种数据库：Oracle，PostgreSQL，MySQL、SQL Server等等。SQL 工程师级别的专业数据库管理工具，不过需要收费！

> 拓展： **如何使用Sequel Pro 导出表结构图？**
>
> 前置条件：**安装graphviz：** brew install graphviz即可（需要提前安装homebrew）
>
> 1. 用Sequel Pro导出Dot文件
>
>    ```
>    File-> Export... -> Dot
>    ```
>
> 2. 用dot命令（需要先安装graphviz）将dot转为图片
>
> ```
> dot -Tjpg test.dot > test.jpg
> ```
>

**API测试：**

1. **[Insomnia](https://insomnia.rest/)** :API接口测试。美观小巧大方，非常适合个人使用。我平时自己写小项目的时候就用的这个来测试 API 的。
2. **[PostMan](https://www.postman.com/)** ：这个不用多说了。毕竟算是用的非常多的 API 测试工具了。

**Git:**

1. **[Github Desktop](https://desktop.github.com/)**：Github 可视化桌面端。无论您是Git的新手还是经验丰富的用户，GitHub Desktop都可以简化您的开发工作流程。
2. **[Sourcetree](https://www.sourcetreeapp.com/)** ：Sourcetree简化了你与Git仓库的交互，这样你就可以专注于编码了。通过Sourcetree的简单的Git GUI来可视化和管理你的存储库。

**其他：**

1. **[Docker](https://www.docker.com/)** 
2. **Docker Desktop** :Docker 桌面可视化管理工具。

### 写作

1. **[Typora](https://typora.io/)** ： Markdown 编辑器。简单好用，支持树形结构文件夹展示。
2. **[PicGo](https://github.com/Molunerfinn/PicGo)** :图床管理工具。支持多种存储方式比如阿里云 oss、七牛云 oss。

### 效率工具/提高生产力

> 很多人推荐了 **Afred** 这个效率工具，我觉得 Mac 自带的 **Spotlight Search** （也就是聚焦搜索，快捷键command+space） 更强大，无论是反应速度、效率还是颜值。

1. **Spotlight Search(聚焦搜索)** : 不只是搜索那么简单！非常强大！另外，聚焦搜索输入关键词按command+B可以调用默认浏览器的搜素引擎搜索哦！
2. **[shuttle](https://github.com/fitztrev/shuttle)** ：让我们更加方便地远程登录某台机器。
3. **[XMind](https://www.xmind.net/zen/)** :思维导图。
4. **[Axure](https://www.axure.com/)** ： 最强大的原型图制作工作，可以共享协作；
5. **Magnet** :简单好用且强大的分屏软件，不过需要 12 元，我觉得很值 。
6. **[uTools](https://u.tools/)** :*uTools*是一个极简、插件化、跨平台的现代化桌面软件。通过自由选配丰富的插件，打造你得心应手的工具集合。
7. **[motrix](https://motrix.app/zh-CN/)** ：一款全能的下载工具。支持下载 HTTP、FTP、BT、磁力链、百度网盘等资源。
8. **[WeChatExtension-ForMac](https://github.com/MustangYM/WeChatExtension-ForMac)** ：Mac版微信的功能拓展：消息防撤回、微信多开、自动登录、远程控制等等。
9. **[SwitchHosts](https://github.com/oldj/SwitchHosts)** : 这是一个用于快速切换 hosts 文件的小程序，基于 [Electron](http://electron.atom.io/) 开发，同时使用了 [React](https://facebook.github.io/react/)、[Ant Design](https://ant.design/) 以及 [CodeMirror](http://codemirror.net/) 等框架/库。

### 其他

1. **解压缩**：Archiver 、BetterZip。
2. **gif截图工具**：[Gifox](https://gifox.io/)。**截图工具** ： Xnip（command+shift+4是mac自带的截图也很好用）。
3. **Mac APP 卸载：** AppCleaner。

为了完善这期分享我将自己的这个想法也发到了朋友圈，成功吊了很多人的胃口，也顺带完善了一下这期分享内容。非常感谢各位老哥！好东西就要拿来分享。

![](https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-11/mac-sdasfa.jpg)

另外，着重感谢一下微信名称为  Chin 的这位老哥，老哥推荐给了我很多实用的 Mac 软件。

<img src="https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-11/chin-man.jpeg" style="zoom:50%;" />

**推荐：**

1. [Awesome Mac](https://wangchujiang.com/awesome-mac/index.zh.html)