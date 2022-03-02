注
===
由于目前覆写不支持策略组，导入其它分流规则相对繁琐，所以仅写了一份去广告分流，若你的配置中已包含去广告分流请不要再添加此分流，且此规则已包含于我的配置模板[Config-Stash](https://github.com/Infatuation-Fei/rule/blob/main/Stash/Config-Stash.yaml)中，避免规则重复

由于raw链接被墙，请开启代理后导入

使用方法
===
① 获取raw链接(由于raw链接被墙，请开启代理后导入)：

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/%E8%8E%B7%E5%8F%96Raw%E9%93%BE%E6%8E%A5.jpg)

进入任意stoverride文件后，点击Raw(手机上点击右上三个点然后View Raw)后进入链接，把链接复制出来即可

② 通过首页覆写安装

(Stash 1.4.0 Bulid160+ 版本支持覆写导入规则)

![](https://raw.githubusercontent.com/Infatuation-Fei/explain/main/Picture/fuxie.jpg)

- 注

由于Stash统计的是拆分后的规则，即 +.example.com = example.com + *.example.com ，所以Stash显示本规则约为5W条规则，实际规则量约为3.7W
