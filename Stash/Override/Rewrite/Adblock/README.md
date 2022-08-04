重写去广告
===
规则众多，千万不要使用重写(Rewrite)导入，建议统一使用覆写(Override)导入

Advertising与AdvertisingLite二选一使用，不可同时使用

**Advertising完全包含AdvertisingLite，重复使用只是白白占用系统资源**

AdvertisingLite为去除一些过于宽泛的匹配规则，减少MITM的数量(即规则数量相对少点，去广告效果差点，减少误杀)，更推荐使用此版本

建议配合分流去广告使用，若你的配置中没有分流去广告规则，可以通过覆写添加我[Rule](https://github.com/Infatuation-Fei/rule/tree/main/Stash/Rule)文件夹下的分流去广告，若配置中已有去广告规则，则切勿再添加分流去广告
