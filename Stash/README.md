已有内容
==
- Rewrite(重写规则)
- Rule(分流规则)
- Script(脚本)

**均为可通过覆写导入的规则**

**使用请详细阅读每个内容里的说明**

配置模板
===

本配置为自己写的自用配置改成的模板，未必适合所有人，请酌情使用，使用请详细阅读以下说明

由于iOS严格限制NE内存，iOS15之前NE内存仅为15M，iOS15后NE内存为50M，且Clash内核相对占用内存较大，所以规则过多可能导致低于iOS15的设备上无法启动

故建议iOS15以下用户使用规则少的精简模板`ConfigLite-Stash.yaml`，iOS15以上的设备推荐使用`Config-Stash.yaml`

使用
---
下载`Config-Stash.yaml`或`ConfigLite-Stash.yaml`导入，然后打开编辑，根据内容提示替换链接即可，一定要注意不要粘贴多余的空格之类的。

- 策略展示

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/celve.jpg)

策略组已使用引用ICON功能，ICON(图标)采用[Koolson的Qure Color(点击跳转)](https://github.com/Koolson/Qure/tree/master/IconSet/Color)，需要Stash 1.3.1 Build 147+版本，低于这个版本不显示图标

- 更新节点

后续更新节点通过启动后策略组左上角更新外部资源即可

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/Config1.jpg)

报错处理
----
如果出现以下报错

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/cuowu.jpg)

是因为你的订阅链接里筛选不到JP(日本)节点，删掉JP的信息就可以了，即以下图上两处：

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/shan.jpg)

以上为筛选不到时的处理方法，以JP为例，如果是TW/US等筛选不到也是同样的处理方法，删除`Proxy-Providers`里一整段与策略组使用的`use引用`就可以了
