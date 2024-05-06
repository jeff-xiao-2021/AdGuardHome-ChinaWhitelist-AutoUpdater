# AdGuardHome-ChinaWhitelist-AutoUpdater
本项目提供如何安装AdGuardHome、如何设置AdGuardHome域名解析策略以及ChinaWhitelist自动更新策略。
因为导入了ChinaWhitelist白名单数据，不建议在内存太小的机器上运行。本项目实际部署在CentOS7系统上(并没有部署在Docker上)，系统内存为4G。

## 文件说明
### install.sh


## 去广告规则
### HalfLifeList
[https://github.com/o0HalfLife0o/list](https://github.com/o0HalfLife0o/list)
> 合并自乘风视频广告过滤规则、EasylistChina、EasylistLite、CJX'sAnnoyance，以及补充的一些规则

### AntiAD

[https://github.com/privacy-protection-tools/anti-AD](https://github.com/privacy-protection-tools/anti-AD)
> 致力于成为中文区命中率最高的广告过滤列表，实现精确的广告屏蔽和隐私保护。anti-AD现已支持AdGuardHome，dnsmasq， Surge，Pi-Hole，smartdns等网络组件。完全兼容常见的广告过滤工具所支持的各种广告过滤列表格式
