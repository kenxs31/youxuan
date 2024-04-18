## 大佬订阅器  
- cm.godns.onflashdrive.app  &ensp;  `天城大佬` &ensp;  暂时不知道订阅入口  
- https://3k.fxxk.dedyn.io/auto  &ensp;  `3K大佬`
- https://VLESS.fxxk.dedyn.io/auto  &ensp;  `CM大佬-vless 订阅器`
- https://VMESS.fxxk.dedyn.io/auto  &ensp;  `CM大佬-vmess 订阅器`
- https://vless-4ca.pages.dev/auto  &ensp;  `CM大佬-vless 订阅器`
- https://WARP.fxxk.dedyn.io/auto  &ensp;  `CM大佬-Warp+ 订阅器`
- https://yusub.yutian81.top    &ensp;  `自行搭建的`  &ensp;  隐藏订阅入口  
## 自定义订阅，手动使用上述订阅器
#### vless pages
- https://VLESS.fxxk.dedyn.io/sub?host=[你的VLESS域名]&uuid=[你的UUID]&path=[你的ws路径]
#### vless workers
- https://VLESS.fxxk.dedyn.io/sub?host=[你的Worker域名]&uuid=[你的UUID]
#### vmess pages
- https://VMess.fxxk.dedyn.io/sub?cc=[VMess服务名字]&host=[你的VMess域名]&uuid=[你的UUID]&path=[你的ws路径]&alterid=[额外ID]&security=[加密方式]  
*cc 非必填项，可能会影响使用在线订阅转换,推荐使用地区代号，例如HK、SG、US*  
*alterid 非必填项，默认0*  
*security 非必填项，默认auto*  
- https://VMess.fxxk.dedyn.io/sub?host=[你的VMess域名]&uuid=[你的UUID]&path=[你的ws路径]  
*worker不支持VMess！*
## 订阅器变量说明
- UUID=UUID  
- HOST=伪装域名  `cf pages或workers地址`  
- PATH=路径  `填写/?ed=2048即可，或自定义，但最前面一定要带 / `;cm的脚本可以直接填写反代IP &nbsp; `/proxyIP=`
- TOKEN=订阅入口  `默认为auto`  
- ADD=优选域名，每行1个，对应addresses字段  `带TLS`  
- ADDNOTLS=优选域名，每行1个，对应addressesnotls字段  `不带TLS`  
- ADDAPI=优选IP直链地址，有多条则每行1条，对应addressesapi字段  `带TLS`
- ADDAPINOTLS=优选IP直链地址，有多条则每行1条，对应addressesnotlsapi字段  `不带TLS`  
- SUBAPI=订阅转换器后端，默认`apiurl.v1.mk`，自建前端`csub.yutian81.top`，教程https://github.com/bulianglin/psub   
- SUBCONFIG=订阅转换器配置文件  
https://ghproxy.net/https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/config/ACL4SSR_Online_Full_MultiMode.ini  
`带负载均衡`  
- ADDCSV=IP测速文件直链地址，有多条则每行一条，对应addressescsv字段  
- DLS=测速下限值，默认单位m/秒， `如：10`
- 优选订阅地址：https://HOST域名/TOKEN `clash则加上?format/clash` &ensp; `singbox则加上?format/singbox`  
- 手动填写：https://生成器地址/sub?host=伪装域名&uuid=你的UUID&path=路径
- **[订阅器变量内容](https://github.com/yutian81/freefq/blob/main/bianliang.md)**
## cf 自建节点变量
- SUB=订阅器地址  
- UUID=UUID  
- PROXYIP=反代IP或域名,可填写多个用英文`,`分隔
- **[反代域名搜集](https://github.com/yutian81/freefq/blob/main/PROXYIP.md)**
## 托管在 CF CDN 上的网站，可通过工具解析获得优选IP
- **[已解析出IP的CF CDN域名](https://github.com/yutian81/freefq/blob/main/souji/cf-domain.md)**
## 其他文件说明
- yip：**[优选IP列表](https://github.com/yutian81/freefq/blob/main/yip)**
- IPtest文件夹：存放优选IP测速文件`csv文件`，没有维护，请自行获取
- zhuanhuan文件夹：节点转换器搭建脚本文件，[教程](https://github.com/yutian81/freefq/blob/main/zhuanhuan/README.md)
- 测速链接地址 [mingyu大佬提供](https://github.com/yutian81/freefq/blob/main/IPtest/README.md)
