已有内容
==
- Rewrite(重写)

配置模板
===
`Config-Stash.yaml`

自己写的自用配置改成的模板

策略组已使用引用ICON功能，需要Stash 1.3.1 Build 147+版本，低于这个版本不显示图标

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/Config-Stash.PNG)

报错处理
----
如果出现以下报错

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/cuowu.jpg)

是因为你的订阅链接里筛选不到JP(日本)节点，删掉JP的信息就可以了，即以下图上两处：

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/shan1.jpg)
![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/shan.jpg)

以上为筛选不到时的处理方法，以JP为例，如果是TW/US等筛选不到也是同样的处理方法，删除Proxy-Providers里一整段与策略组使用的use引用就可以了
