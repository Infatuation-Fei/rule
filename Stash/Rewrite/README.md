使用方法
===

（以Tiktok解锁为例，其它的同理）

请自行安装好mitm证书，以下方法任取其一即可

  方法1
  ----
① 获取raw链接：

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/jiaoxue.png)

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/jiaoxue2.png)

点击Raw(手机上点击右上三个点然后View Raw)后进入链接，把链接复制出来即可

② 通过首页覆写安装

(Stash 1.4.0 Bulid159+ 版本支持)

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/fuxie.jpg)

- `注`：

一般推荐使用此方法导入，简单方便，但由于覆写导入的内容无法修改，像Tiktok解锁修改观看地区的话需要修改重写规则，建议使用方法2，方法2导入后可自行修改重写规则内容，方便tiktok换区

  方法2
----
① 分别通过软件主页重写规则与MITM模块将获取的raw链接使用URL导入

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/Tiktokyanshi0.jpg)

② 效果图：

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/IMG_1716.JPG)

  方法3
  -----
 如果你会编写配置文件，将链接中http及后面的内容整个复制出来，放到你自己的配置文件中即可
 
 可以像图上一样整段放到最后面，也可以插入中间，注意不要破坏掉其它字段即可
 
 ![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/jiaoxue3.jpg)
 
 再添加更多的规则时仅需要再将其它的mitm和rewrite复制出来添加上即可。
 
 目前软件主页的mitm和重写模块与配置文件是独立的，所以放在配置文件里的重写规则是不会在首页显示的，首页添加的也不会写入配置文件。
 
附
=

  软件降级方法：

  使用自己的ID抓包
 
  抓包工具：
  [点击下载](https://raw.githubusercontent.com/Semporia/TikTok-Unlock/master/iOS%E6%8A%93%E5%8C%85/iOS%E6%97%A7%E7%89%88%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BDv5.1.exe)

  老版iTunes：
  [点击下载](https://secure-appldnld.apple.com/itunes12/091-87819-20180912-69177170-B085-11E8-B6AB-C1D03409AD2A6/iTunes64Setup.exe)

  视频：https://b23.tv/FM1h5BD
