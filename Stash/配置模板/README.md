配置模板
===

`Config-Stash.yaml`，可以用于所有Clash(Premium内核)客户端

本配置为自己写的自用配置改成的模板，未必适合所有人，请酌情使用，使用请详细阅读以下说明

使用
---
下载`Config-Stash.yaml`导入，然后打开编辑，根据内容提示替换链接即可，一定要注意不要粘贴多余的空格之类的。

- 策略展示

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/celve.jpg)

策略组使用Stash的引用ICON功能，ICON(图标)库采用[Koolson的Qure Color](https://github.com/Koolson/Qure/tree/master/IconSet/Color)，在其它Clash客户端中使用不会显示图标

- 更新节点

后续更新节点通过启动后策略组左上角更新外部资源即可

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/Config1.jpg)

- 注

低于iOS15请不要使用本配置，由于iOS严格限制NE内存，iOS15以下NE内存仅为15M(iOS15为50M)，且Clash内核相对占用内存较大，规则过多在低于iOS15的设备上无法启动，低于iOS15的越狱设备可自行修改NE内存限制后使用，方法自行谷歌搜索，建议至少改成100M+

报错处理
===
如果出现以下报错

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/%E7%AD%9B%E9%80%89%E9%94%99%E8%AF%AF.png)

是因为你的订阅链接里筛选不到US(美国)节点，删掉US相关信息就可以了，即以下三处：

proxy-providers中美国节点相关片段：
---
![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/%E7%AD%9B%E9%80%89%E5%88%A0%E9%99%A4.png)

proxy-groups中国外/国内网站策略组的proxies中美国节点删除掉：
--
![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/%E5%9B%BD%E5%86%85%E5%A4%96%E7%AD%96%E7%95%A5%E7%BB%84.jpg)

- 增加其它地区策略也只需在这两个策略组proxies中添加即可，其它策略组的策略均引用的这两个策略组的策略

proxy-groups中美国节点策略组删除掉：
---
![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/US%E7%AD%96%E7%95%A5%E7%BB%84.jpg)

以上为筛选不到时的处理方法，以US为例，如果是TW/JP等筛选不到也是同样的处理方法

若确定你的链接中包含相关节点，也可在proxy-providers里filter后自行增加节点名称关键词，每个关键词用竖杠|隔开

