# csub
利用CF Worker搭建的反代订阅转换工具，通过随机化服务器地址和节点账号密码，解决用户转换订阅的隐私问题  
## 演示网站  
https://psub.888005.xyz  
## 视频教程  
https://youtu.be/X7CC5jrgazo  
- 创建worker，复制代码`zhuanhuan.js`，命名为`csub`，保存并部署  
- 创建KV，命名为`csub或其他`  
- 设置worker环境变量1：`BACKEND`  https://api.v1.mk  
- 设置worker环境变量2：KV或R2变量：`SUB_BUCKET`  csub
- worker地址即为订阅转换器地址，可绑定自定义域名使用  
## 支持反代转换的协议
shadowsocks  
shadowsocksR  
vmess  
trojan  
vless(取决于后端)  
hysteria(取决于后端)  
