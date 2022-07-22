## Rules

### 自用 Clash 规则集

| 文件名                                                                                                 | 包含内容                                                                                                 |
| ------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------|
| [Adblock.yaml](https://raw.githubusercontent.com/TakizawaAnn/Rules/release/Adblock.yaml)               | 常见广告域名（广告联盟 等）                                                                               |
| [App-Activation.list](https://github.com/LM-Firefly/Rules/blob/master/Special/App-Activation.list)     | 软件激活域名（Adobe 全家桶 等）                                                                           |
| [DNS.list](https://github.com/LM-Firefly/Rules/blob/master/Special/DNS.list)                           | 常用 DNS                                                                                                 |
| [Apple.yaml](https://raw.githubusercontent.com/TakizawaAnn/Rules/release/Apple.yaml)                   | 苹果公司服务, 详见 [Apple.md](https://github.com/LM-Firefly/Rules/blob/master/Apple.md)         |
| [GlobalMedia.list](https://github.com/LM-Firefly/Rules/blob/master/GlobalMedia.list)                   | 国外常见流媒体服务,详见 [GlobalMedia.md](https://github.com/LM-Firefly/Rules/blob/master/GlobalMedia.md)  |
| [Google.yaml](https://raw.githubusercontent.com/TakizawaAnn/Rules/release/Google.yaml)                 | Google 服务                                                                                             |
| [Microsoft.yaml](https://raw.githubusercontent.com/TakizawaAnn/Rules/release/Microsoft.yaml)           | 微软服务                                                                                                 |
| [Proxy.yaml](https://raw.githubusercontent.com/TakizawaAnn/Rules/release/Proxy.yaml)                   | 常见国外服务                                                                                             |
| [Domestic.list](https://github.com/LM-Firefly/Rules/blob/master/Domestic.list)                         | 中国大陆常见公司服务                                                                                       |
| [Video-Crack.list](https://github.com/LM-Firefly/Rules/blob/master/Special/Video-Crack.list)           | 盗版视频解析站                                                                                           |
| [DMCA-Sensitive.list](https://github.com/LM-Firefly/Rules/blob/master/Special/DMCA-Sensitive.list)     | DMCA 敏感域名（主要针对机场审计 tracker、迅雷）                                                             |
| [LAN-Special-Apps.list](https://github.com/LM-Firefly/Rules/blob/master/Special/LAN-Special-Apps.list) | 局域网特殊应用域名（投屏、广播 等）                                                                         |
| [Local-LAN.yaml](https://raw.githubusercontent.com/TakizawaAnn/Rules/release/Local-LAN.yaml)           | 局域网 IP 段 及保留地址列表                                                                               |
| [NTP-service.list](https://github.com/LM-Firefly/Rules/blob/master/Special/NTP-Service.list)           | 常见 NTP 服务列表，路由器可能需要加入 fake-ip-filter                                                       |
| [TeamViewer-CIDR.yaml](https://github.com/LM-Firefly/Rules/blob/master/Special/TeamViewer-CIDR.list)   | TeamViewer 远程 IP 段 需要直连 才能远程                                                                   |
| [SpeedTest.list](https://github.com/LM-Firefly/Rules/blob/master/SpeedTest.list)                       | Ookla SpeedTest 服务器                                                                                   |
| [CDN-CN.yaml](https://raw.githubusercontent.com/TakizawaAnn/Rules/release/CDN-CN.yaml)                 | CDN-CN 中国常见 云计算公司                                                                                 |
| [CDN-Global.yaml](https://raw.githubusercontent.com/TakizawaAnn/Rules/release/CDN-Global.yaml)         | 全球常见 云计算公司                                                                                       |

### 须知:

[Domestic-Services](https://github.com/LM-Firefly/Rules/tree/master/Domestic-Services) | [Global-Services](https://github.com/LM-Firefly/Rules/tree/master/Global-Services) 只是作为引用小切片列出, 与 [Domestic.list](https://github.com/LM-Firefly/Rules/blob/master/Domestic.list) | [GlobalMedia.list](https://github.com/LM-Firefly/Rules/blob/master/GlobalMedia.list) 并非相互对映，具体包含关系以列表注释为准。

### 灵活转换:

如果有特殊格式需要，可以尝试使用 [Subconverter](https://github.com/tindy2013/subconverter/blob/master/README-cn.md#%E8%A7%84%E5%88%99%E8%BD%AC%E6%8D%A2) 自行转换

### 相关参考：
https://docs.github.com/cn/repositories<br />
https://github.com/tindy2013/subconverter<br />
https://github.com/Dreamacro/clash/wiki/configuration<br />
https://github.com/Dreamacro/clash/wiki/premium-core-features#rule-providers<br />
https://github.com/ziishaned/learn-regex/blob/master/translations/README-cn.md

### 相关引用:

[Telegram CIDR](https://core.telegram.org/resources/cidr.txt)
