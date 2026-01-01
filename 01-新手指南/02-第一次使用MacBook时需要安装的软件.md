## 前言

> 第一天拿到MacBook时，我会立即安装这些软件，确保接下来的Mac使用的操作比较顺利。

涉及付费软件时，文中凡是标注了价格的，代表我是付费购买的。

## 前置软件

### 截图软件：[Snipaste](https://zh.snipaste.com/)

用于把电脑的序列号、配置信息、存储空间、等信息，截图存档。

### 磁盘分析：腾讯柠檬

用腾讯柠檬的深度清理，分析磁盘的文件占比。后续等电脑使用一两年之后，在对比一下磁盘空间。就知道哪些文件夹被挤得很满了。

### 科学上网

科学上网包括两步：代理工具+服务，缺一不可。（1）先安装代理工具；（2）然后购买服务。

1、下载代理工具 ClashX：

- 下载地址（第三方）：https://github.com/bannedbook/ClashX/releases

ClashX的官方项目已下架，可以在第三方网站下载安装包。


- 参考教程：https://github.com/githubvpn007/ClashX

2、上网服务：AgentNEO：

- 购买网址：[AgentNEO](https://niceneo.com/?rc=ut50176c)

把上网服务搭建之后，就可以下载  chrome、dropbox等后续软件了。

## 必备软件

### 浏览器：[chrome 浏览器](https://www.google.com/intl/zh-CN/chrome/)

打开互联网世界大门的入口。登录google账号之后，同步书签和浏览器插件。

### 输入法：[搜狗输入法](https://shurufa.sogou.com/mac)

用了十几年的搜狗输入法，写了400W字，积累了23W 个词条。

### 滚动截图软件+简单的录屏软件：iShot Pro

- 下载地址：App Sore
- 价格：￥78 买断制，一次购买，永久持续更新升级。

![image-20260102001935831](https://img.smyhvae.com/202601020019850.png)

把截图功能的快捷键从默认的「Ctrl + A」改成「F2」：

![image-20260102002406730](https://img.smyhvae.com/202601020024759.png)

因为 Snipaste的快捷键是 F1截图、F3贴图，再加上 iShot Pro的快捷键是F2贴图，这样的话，这两个软件的截图快捷键就都在一排、挨在一起了，方便记忆和连贯操作。

同时，在通用设置中，设置为开机自启动。

### 启动器：[Raycast](https://www.raycast.com/)

代替系统自带的 Spotlight。

通过 Raycast 可以快速启动任意软件，搜索本地的任意文件，甚至还可以作为计算器使用。它的历史剪贴板功能，尤为好用，用过就离不开了。

1、先把 Spotlight 的「cmd + 空格」快捷键取消，把这个快捷键让给 Raycast。

将 Spotlight 取消快捷键的操作路径如下：

在系统设置中搜索「聚焦」：

![image-20260101234701634](https://img.smyhvae.com/202601012347657.png)

然后进入「键盘快捷键」：

![image-20260101234923819](https://img.smyhvae.com/202601012349841.png)

上图中，把这两个都取消打钩。

2、给 Raycast 设置键盘快捷键：

打开 Raycast 的设置面板，将默认的「option + 空格」快捷键改成「cmd + 空格」快捷键。

![image-20260102000842828](https://img.smyhvae.com/202601020008849.png)

3、Raycast的历史剪贴板功能，默认没有快捷键，我们给它一个快捷键「option + cmd + C」，然后将保存历史从默认的7天改为一年（越长越好）：

![image-20260102002942898](https://img.smyhvae.com/202601020029918.png)

Raycast的历史剪贴板功能的使用效果：

![image-20260102003406683](https://img.smyhvae.com/202601020034704.png)

4、通过 Raycast 快捷启动电脑上的任意软件：

比如，我想通过 按下「Option + C」快捷键，就能打开 Chrome浏览器的话，可以在 Raycast 上这样配置：

![image-20260102003813057](https://img.smyhvae.com/202601020038080.png)

其他软件，我建立的快捷键映射如下：

- todo

### 同步网盘：dropbox

在别的电脑上写的内容，自动同步到新电脑。在新电脑上继续写。

### 写作： [Typora](https://typoraio.cn/)、图床上传工具：[PicGo](https://picgo.github.io/PicGo-Doc/zh/guide/)

Typora是很值得入手的付费软件。把 PicGo 作为Typora写作时的默认图片上传工具，很方便。

1、PicGo 配置：

![](https://img.smyhvae.com/202512300136285.png)

利用 PicGo 上传图片时，如果图片的后缀出现 `.pngundefined`这种多语的 undefined格式的话，解决办法是：先把`设定网址后缀`设置有值后再清空，就会正常。参考链接：[图片的后缀名不对的bug](https://github.com/Molunerfinn/PicGo/issues/1156)

2、在 Typora中把 PicGo作为上传图片的默认图床工具：

![](https://img.smyhvae.com/202512300140120.png)



### 版本控制：Git、GUI 工具：Tower

1、把markdown文章写在 GitHub 私有仓库中，用 Git 作为版本管理工具。

在 Mac 上安装 Git 有多种方式。 最简单的方法是直接安装 [Command Line Tools for Xcode](https://developer.apple.com/download/all/?q=command) 即可，安装完成后 Git 就有了。

还有一个方法：Mavericks （10.9） 或更高版本的系统中，在 Terminal 里尝试首次运行 'git' 命令即可，会提示你安装命令行开发者工具：

```console
$ git --version
```

2、另外再安装一个GUI软件做可视化管理。Git 官网推荐了[数十种GUI客户端](https://git-scm.com/download/gui/mac) 可以参考一下。我个人最喜欢用的 GUI客户端是 Tower。

打开tower之后，会弹出一个弹窗，需要配置用户名和邮箱：

![image-20260101143638827](https://img.smyhvae.com/202601011436846.png)

下面这张图用于配置与github的连接：

![image-20260101143653924](https://img.smyhvae.com/202601011436944.png)

token的配置参考：https://blog.csdn.net/weixin_41010198/article/details/119698015

### 写日记：day one

- 下载地址：App Store



## 按需安装

### 截图软件：iShot Pro



### 网盘：百度网盘

百度的大多数软件我都很鄙视，百度搜索引擎我基本不用。但是百度网盘还是很坚挺的。用它来存储一些临时文件或者网上的学习资料还是挺方便的。

就拿现在的摄影机构来说，大部分机构依然是用百度网盘给客户发照片资源。




## 进阶软件
