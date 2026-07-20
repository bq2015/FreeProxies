# FreeProxies
永久免费翻墙/科学上网，节点每10分钟自动更新，仅保留可用节点。订阅链接可一键导入，无需频繁更换。如果觉得有帮助，请点个星星支持一下。为了防止链接丢失，建议fork到自己的仓库。

由于近期用户激增，导致服务稳定性变差，因此时有出现无法自动更新到github，如发现无当日订阅链接，则可前往如下链接去获取：
https://blue2sea.com/order/querySubscriptionLink/%20

---

## 订阅链接&加时卡
当前最新公共订阅链接为（每日21点30分更新第二天的链接）：
```
https://blue2sea.com/clash/7a3974c59adf06a86a3769254fb1ef8e
```
当前最新加时卡代码为（每30分钟更新1次）：
```
0c9a3
```

为防止恶意使用，影响大家使用。公共节点，只是作为一个入口，需要每天更换。不想更换，可以按下一步说明生成私有链接，并每天加时3次，订阅链接就不会失效，如发现失效，再加时即可（无限续杯）。
>
> [!TIP]
> ### 😮‍💨 唉，终于坚持测了整整 5 年……推荐给老朋友们。
> 
> 这个项目一直是我个人在维护，说白了就是用网上的免费节点玩玩。但大家都懂，万人共用、晚高峰卡成 PPT、IP 被 ChatGPT/OpenAI 封锁、每天还得手动更新订阅……折腾到掉头发，一点不夸张。
> 
> 果你是做 AI 开发的、需要稳定跨境办公，或者常看海外视频，那真别浪费时间在这些免费节点上了。时间比什么都值钱。
> 
> 下面这个服务商是我自己用了 5 年的主力，从当年挑来挑去到现在稳定养老，一直没让我失望（高峰期也很稳，ChatGPT 解锁毫无压力）,关键是每个月不到 8 块钱，跟一瓶饮料差不多，就能毫无限制地畅享世界顶尖的 AI 模型，工作效率一下子提升。对我来说，这笔投入很值，省下的时间和精力远比花出去的成本更划算。：
> 
> 👉 **[专属商业私有通道（支持一键导入 Clash）](https://blue2sea.com/#pricing)**
> 
> 🎁 **给兄弟们争取的一点福利：**
> 顺便说下，我去找老板要了个优惠码，下单的时候输入能直接 **立减 10 元**。大家用的时候也算帮我分担点测速服务器的成本，感谢！
> 
> ```text
> Kylin888
> ```
>

----

## 使用说明

1. 下载代理工具clash,关于下载地址和下载、下载使用说明参考
https://blue2sea.com/order/querySubscriptionLink/%20


2. 复制公共订阅链接放到浏览器打开，在其页面中找到“个人订阅”，以生成属于自己的订阅链接。这样做，方便省去后续更换订阅链接的烦恼。当然，如果你不嫌麻烦，你也可以直接每天手动更换链接使用公共订阅链接。

3. 将属于自己的订阅链接粘贴到clash进导入，即可正常使用。

4. 每天使用免费领取加时卡代码进行加时（加时见上节），实现永久免费翻墙/科学上网。

5. 欢迎分享你发现的公开节点，我们会对其进行测速并考虑将其添加到订阅服务中。[前往>](https://github.com/bq2015/FreeProxies/issues/1)
---

## 基本实现原理

1. 从网络获取公开任意协议（torjan、ssh、vless、vmess）节点并转化成clash类型代理数据，然后加入数据库存档。

2. 定时从数据库提取节点，通过clashspeedtest进行测速，剔除已失效的节点。

3. 开启订阅链接服务，获取可用节点。

---

## 关于科学上网工具/软件的一切

> 强烈推荐：[Clash-verge](https://github.com/clash-verge-rev/clash-verge-rev) 开源、更新快，技术大佬用爱发电、持续维护

### Windows (7/8/10) 电脑客户端

| 客户端名称 | 下载链接 |
| --- | --- |
| V2rayN | [官网下载](https://github.com/2dust/v2rayN/releases) |
| V2rayW | [官网下载](https://github.com/Cenmrev/V2RayW/releases) |
| Clash | [官网下载](https://github.com/Fndroid/clash_for_windows_pkg/releases) |
| V2rayS | [官网下载](https://github.com/Shinlor/V2RayS/releases) |
| Mellow | [官网下载](https://github.com/mellow-io/mellow/releases) |
| Qv2ray | [官网下载](https://github.com/Qv2ray/Qv2ray) |

### Android (Android/小米/华为) 手机客户端

| 客户端名称 | 下载链接 |
| --- | --- |
| V2rayNG | [官网下载](https://github.com/2dust/v2rayNG/releases) |
| 安卓小火箭 | [官网下载](https://github.com/Pawdroid/shadowrocket_for_android/releases) |
| BifrostV | [市场下载](https://www.appsapk.com/downloading/latest/com.github.dawndiy.bifrostv-0.6.8.apk) |
| Clash | [官网下载](https://github.com/Kr328/ClashForAndroid/releases) |
| Kitsunebi | [市场下载](https://apkpure.com/kitsunebi/fun.kitsunebi.kitsunebi4android) |

### MacOS 苹果电脑客户端

| 客户端名称 | 下载链接 |
| --- | --- |
| V2rayU | [官网下载](https://github.com/yanue/V2rayU/releases) |
| V2rayX | [官网下载](https://github.com/Cenmrev/V2RayX/releases) |
| ClashX | [官网下载](https://github.com/yichengchen/clashX/releases) |

### Linux (Ubuntu/Centos) 电脑客户端

| 客户端名称 | 下载链接 |
| --- | --- |
| Qv2ray | [官网下载](https://github.com/Qv2ray/Qv2ray) |
| Mellow | [官网下载](https://github.com/mellow-io/mellow/releases) |
| V2rayL | [官方安装文档](https://github.com/jiangxufeng/v2rayL) |

> 💡 **iOS (苹果手机) 说明：**
> 苹果 App Store 暂无免费的 V2ray iOS 客户端。目前付费可用的 App 有：**Shadowrocket（小火箭）**、**pepi**、**i2Ray**、**Kitsunebi** 和 **Quantumult（圈、圈叉）**。

---

## ShadowsocksR (SSR) 客户端下载

| 适用平台 | 客户端说明 | 下载链接 |
| --- | --- | --- |
| **Windows (7/8/10)** | SSR小飞机 WinPC 电脑客户端 | [官网下载](https://github.com/shadowsocksrr/shadowsocksr-csharp/releases) |
| **Android** | SSR小飞机 安卓手机客户端 Apk | [官网下载](https://github.com/shadowsocksrr/shadowsocksr-android/releases) |
| **MacOS** | SSR小飞机 苹果电脑客户端 | [官网下载](https://github.com/qinyuhang/ShadowsocksX-NG-R/releases) |

> 💡 **iOS (苹果手机/iPad) 说明：**
> 请打开苹果 App Store，直接搜索以下关键词下载：**Mume(暮梅)**、**Potatso Lite**、**FastSocks**、**Shadowrocket（小火箭）**。

---

## 一些注意事项

使用过程请遵纪守法，建议仅用于学习和研究，一切风险自行承担。
