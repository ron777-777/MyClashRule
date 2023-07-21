# MyClashRule
MyClashRule

感谢  
不良林  
https://github.com/chinnsenn/ClashCustomRule  
提供方案  

ACL4SSR在线订阅转换  
https://acl4ssr-sub.github.io/  
orange订阅  
https://api.orangeapi.org/  
手搓地址  
https://raw.githubusercontent.com/ron777-777/MyClashRule/main/MyClashRule.ini  
完整订阅  

快游戏  
sub?target=clash&new_name=true&url=https%3A%2F%2Fapi.orangeapi.org%2Fsub%3Fsuburl%3Dhttps%253A%252F%252Fsub3.jie-quick.buzz%252Fapi%252Fv1%252Fclient%252Fsubscribe%253Ftoken%253D11a2015c8f7840530bda899adbfa50dd%26newhost%3Dm.iqiyi.com%26showhost%3Dtrue%26queryhost%3Dtrue&insert=false&config=https%3A%2F%2Fraw.githubusercontent.com%2Fron777-777%2FMyClashRule%2Fmain%2FMyClashRule.ini  

性价比机场  
sub?target=clash&new_name=true&url=https%3A%2F%2Fapi.orangeapi.org%2Fsub%3Fsuburl%3Dhttps%253A%252F%252F1.xn--xc3ao8r.top%252Fapi%252Fv1%252Fclient%252Fsubscribe%253Ftoken%253D1e555b60fa05eb9d6e423a96370cc994%26newhost%3Dm.iqiyi.com%26showhost%3Dtrue%26queryhost%3Dtrue&insert=false&config=https%3A%2F%2Fraw.githubusercontent.com%2Fron777-777%2FMyClashRule%2Fmain%2FMyClashRule.ini  

合并  
sub?target=clash&new_name=true&url=https%3A%2F%2Fapi.orangeapi.org%2Fsub%3Fsuburl%3Dhttps%253A%252F%252Fsub2.jie-quick.buzz%252Fapi%252Fv1%252Fclient%252Fsubscribe%253Ftoken%253D11a2015c8f7840530bda899adbfa50dd%26newhost%3Dm.iqiyi.com%26showhost%3Dtrue%26queryhost%3Dtrue%7Chttps%3A%2F%2Fapi.orangeapi.org%2Fsub%3Fsuburl%3Dhttps%253A%252F%252F1.xn--xc3ao8r.top%252Fapi%252Fv1%252Fclient%252Fsubscribe%253Ftoken%253D1e555b60fa05eb9d6e423a96370cc994%26newhost%3Dm.iqiyi.com%26showhost%3Dtrue%26queryhost%3Dtrue&insert=false&config=https%3A%2F%2Fraw.githubusercontent.com%2Fron777-777%2FMyClashRule%2Fmain%2FMyClashRule.ini  

前缀替换  
https://sub.xeton.dev/  
https://pi.dler.io/  
https://sub.maoxiongnet.com/  
https://sub.id9.cc/  


```[custom]
;解决DNS泄露，无分流群组
ruleset=🚀 节点选择,[]DOMAIN-SUFFIX,xn--ngstr-lra8j.com
ruleset=🚀 节点选择,[]DOMAIN-SUFFIX,services.googleapis.cn
ruleset=🚀 节点选择,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/GoogleCNProxyIP.list
ruleset=DOMESTIC,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/LocalAreaNetwork.list
ruleset=DOMESTIC,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/UnBan.list
ruleset=DOMESTIC,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaDomain.list
ruleset=DOMESTIC,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaMedia.list
ruleset=REJECT,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanAD.list
ruleset=REJECT,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanProgramAD.list
ruleset=DOMESTIC,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaCompanyIp.list
ruleset=DOMESTIC,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaIp.list
ruleset=DOMESTIC,[]GEOIP,CN,no-resolve
ruleset=🚀 节点选择,[]FINAL

custom_proxy_group=DOMESTIC`select`(^(?!.*(ipv6|443|香港|澳大利亚|印度|法国|巴西|加拿大|日本|新加坡|台湾|海外|德国|套餐|美国|韩国|网站|官网|校园|流量|所有|订阅)).*)
custom_proxy_group=🚀 节点选择`select`(^(?!.*(ipv6|443|四川|广东|广西|湖北|网站|武汉|海南|江苏|辽宁|内蒙|内蒙古|上海|套餐|官网|校园|剩余|加速|所有|订阅|分流)).*)`[]♻️ 自动选择`[]DIRECT
custom_proxy_group=♻️ 自动选择`url-test`(^(?!.*(ipv6|443|四川|广东|广西|湖北|网站|武汉|海南|江苏|辽宁|内蒙|内蒙古|上海|套餐|官网|校园|剩余|加速|所有|订阅|分流)).*)`http://www.gstatic.com/generate_204`300,,50

enable_rule_generator=true
overwrite_original_rules=true
```
