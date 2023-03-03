配置模板
===

⚠️Stash请使用`Config for Stash.yaml`，官方Clash(Premium内核)使用`Config for Clash.yaml`

不可混用，分别写有对方无法支持的字段，会报错

二者分流规则完全相同

本配置为自己写的自用配置改成的模板，未必适合所有人，请酌情使用，使用请详细阅读以下说明

使用
---
下载(View raw)`Config for Stash.yaml`导入，然后打开编辑，根据内容提示替换链接即可，一定要注意不要粘贴多余的空格之类的。

- 策略展示

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/celve.jpg)

策略组使用Stash的引用ICON功能，ICON(图标)库采用[Koolson的Qure Color](https://github.com/Koolson/Qure/tree/master/IconSet/Color)，在其它Clash客户端中使用不会显示图标

- 更新节点

后续更新节点通过启动后策略组左上角更新外部资源即可

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/Config1.jpg)

- 注

低于iOS15请不要使用本配置，由于iOS严格限制NE内存，iOS15以下NE内存仅为15M(iOS15为50M)，且Clash内核相对占用内存较大，规则过多在低于iOS15的设备上无法启动，低于iOS15的越狱设备可自行修改NE内存限制后使用，方法自行谷歌搜索，建议至少改成100M+

