# XiaoMi-R4A-Gigabit-v2-ImmortalWrt        
针对校园网多设备检测的ImmortalWrt
内置插件包含：
- UA2F
- wget-nossl
- wget-ssl
- argon-theme
- argon-config

默认WebUI地址：192.168.1.1
默认用户名：root
无默认密码
## 刷入步骤（使用Breed）
**因为Breed不是为R4A定制的，所以不能使用Breed的网页刷入，会无限重启，因此需要手动刷入**
* 教程参考链接：https://www.right.com.cn/forum/thread-8298740-1-1.html

1.使用HFS架设web服务
2.在telnet中输入命令wget http://虚拟服务器ip/immortalwrt-ramips-mt7621-xiaomi_mi-router-4a-gigabit-v2-squashfs-sysupgrade.bin，将固件上传到路由器中
此时会显示如下类似的输出：

```
Connecting to 192.168.1.2:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: 6554224/0x640270 (6MB) [application/octet-stream]
Saving to address 0x80001000
```

其中的十六进制地址

3.
