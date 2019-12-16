V2ray 是一款优秀的开源网络代理软件包，它的目标是提供常用的代理软件模块，简化网络代理软件的开发。目前提供支持的平台有Windows，[Linux](https://links.jianshu.com/go?to=https%3A%2F%2Flinux265.com%2F)，Mac，Android，IOS等操作系统，基本上全平台支持。对V2ray感兴趣的小伙伴可以去GitHub上start该项目，具体地址:[V2Ray-core](https://links.jianshu.com/go?to=https%3A%2F%2Fgithub.com%2Fv2ray%2Fv2ray-core)。

### 下载 支持Mac 的 V2Ray 软件

V2ray 的安装和配置并不简单，好在 GitHub 上有支持在 Mac 上运行的 V2RayX软件免去不少麻烦。可以在本站下载安装也可以去[GitHub](https://links.jianshu.com/go?to=https%3A%2F%2Fgithub.com%2FCenmrev%2FV2RayX%2Freleases)上下载最新版。

- V2RayX （最新版 Latest Version） [本地下载](https://links.jianshu.com/go?to=https%3A%2F%2Fguide.v2rayx.org%2Fdownload%2FV2RayX.app.zip) 
- V2RayX （Github所有release版本） [Github Here](https://links.jianshu.com/go?to=https%3A%2F%2Fgithub.com%2FCenmrev%2FV2RayX%2Freleases) 

### 解压下载的ZIP文件，获得V2RAYX文件

复制V2RayX.app文件到应用程序，然后直接点击打开，在弹出的窗口点击"install"进行安装，安装过程需要输入系统密码进行授权允许运行安装。



![img](https:////upload-images.jianshu.io/upload_images/5344101-0b93fbad9970dc59.png?imageMogr2/auto-orient/strip|imageView2/2/w/840/format/webp)

V2RayX 安装

因为软件不是来自于Mac自带的应用商店，打开程序时可能会有安全提示，如下：



![img](https:////upload-images.jianshu.io/upload_images/5344101-ddc526660c15c1cb.png?imageMogr2/auto-orient/strip|imageView2/2/w/840/format/webp)

V2RayX 安装提示

需要前往“系统偏好设置”－“安全性和隐私”，点“仍要打开”，再点"install"安裝。

安裝完成后，可进入 `launchpad`，找到V2RayX图标打开。

### 配置 V2RayX

点击应用打开后，V2RayX图标会出现在右上角的任务栏中，点击图标调出菜单，点"Configure"进行节点设置。目前V2RayX支持URL和手动配置的添加方式，暂不支持订阅和二维码方式。

- URL方式/URL：输入一个URL链接，即可完成一个节点配置，相对手动配置方便很多。
- 手动配置/Manually：增加新节点，並逐一配置相关节点信息，相对操作会比较繁琐。

### URL方式/URL配置方式

打开V2RayX应用程序，点击右上角任务栏中的图标，调用出菜单，点击“Configure”开始进行配置。



![img](https:////upload-images.jianshu.io/upload_images/5344101-05d50c17548527d8.png?imageMogr2/auto-orient/strip|imageView2/2/w/532/format/webp)

V2RayX URL 配置方式

点击上图中的标红图标，，弹出配置界面，然后点击界面上的"import customized config..."开始进行配置。



![img](https:////upload-images.jianshu.io/upload_images/5344101-8eab3de8c6b9dfa9.png?imageMogr2/auto-orient/strip|imageView2/2/w/1104/format/webp)

V2RayX URL 导入

复制V2Ray代理提供者提供节点URL，粘贴到弹出的输入框中，点击“OK”完成操作。



![img](https:////upload-images.jianshu.io/upload_images/5344101-cdd66bce092e9532.png?imageMogr2/auto-orient/strip|imageView2/2/w/1052/format/webp)

V2RayX URL 导入确认

返回节点配置页面，你可以看到自己导入的节点信息，点击页面上的“OK”按钮。

如果想导入多个节点，那么重复以上操作即可。



![img](https:////upload-images.jianshu.io/upload_images/5344101-ab4da73c7402db4d.png?imageMogr2/auto-orient/strip|imageView2/2/w/1104/format/webp)

V2RayX 完成导入后的界面

在此调出菜单，确保servers已经勾选可用节点，点击“Load core” 后代理生效，一般选择"PAC Mode"代理模式。



![img](https:////upload-images.jianshu.io/upload_images/5344101-cb2f8f15e9cf3f01.png?imageMogr2/auto-orient/strip|imageView2/2/w/762/format/webp)

V2RayX 代理模式

完成后，打开浏览器接口访问测试。

### 手动配置V2RayX

打开V2RayX程序，点击任务栏右上角的图标，点击图标调出菜单，点Configure，进行节点配置。



![img](https:////upload-images.jianshu.io/upload_images/5344101-1efec17fdfea6104.png?imageMogr2/auto-orient/strip|imageView2/2/w/532/format/webp)

V2RayX 手动配置

先点击弹出界面左下角`“+”`，增加节点。然后根据提供商提供的节点信息，填入address(服务器地址)，端口，User ID等一些列参数，界面其他参数如果没有提供，无需修改，默认即可。

DNS处填写`8.8.8.8,8.8.4.4`，点OK保存即可。



![img](https:////upload-images.jianshu.io/upload_images/5344101-3532f8cf6770a3eb.png?imageMogr2/auto-orient/strip|imageView2/2/w/1102/format/webp)

V2RayX 参数填写

再次调出菜单，确保servers已经勾选可用节点，点“Load core” 卡其V2RayX，选择PAC Mode代理模式。



![img](https:////upload-images.jianshu.io/upload_images/5344101-4e62baeb680aaed5.png?imageMogr2/auto-orient/strip|imageView2/2/w/762/format/webp)

V2RayX 代理模式

完成后，打开浏览器输入网址测试。

如果某些网址访问失败，可以尝试将代理模式设置为GLobal Mode测试下。

### 写在最后

如何在Mac OS 上安装即配置V2rayX已经讲解完成，希望你对V2rayX代理软件使用有所了解，不妨敢接尝试一下吧。

如果你要在CentOS上使用V2Ray，可以参看[[如何在CentOS上安装V2Ray]](https://github.com/lglHope/v2ray/blob/master/v2ray.md)。