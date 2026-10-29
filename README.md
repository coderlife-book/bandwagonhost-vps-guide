# 搬瓦工 VPS 怎么选？套餐价格、CN2 GIA 和购买教程

搬瓦工（BandwagonHost）卖的是需要自己管理的 VPS。选购时最容易纠结的，是普通 KVM 和 CN2 GIA 差在哪、机房怎么选，以及一年到底要花多少钱。

我把套餐价格和购买步骤放在这里。想快点选定，先看三款建议；想多比一比，下面有完整的价格表和按问题分类的文章。

## 它好在哪里

**线路。** 国内访问国外服务器，除了配置，还得看数据走哪条路。搬瓦工有普通线路，也有 CN2 GIA 等面向中国网络的线路选择，预算可以按用途来分。

**机房。** 洛杉矶、香港、东京、大阪等地都有选择。普通 KVM 和常规 CN2 GIA 套餐支持在各自可用的机房里免费迁移，买之前能选，买之后也能调整。

**面板。** KiwiVM 后台能重装系统、看流量、迁机房、打快照，都是点鼠标的事。装个系统一分钟，比发工单快多了。

**付款。** 支持支付宝、PayPal、信用卡，不用专门去办双币卡。

## 套餐怎么选

名字一大堆，其实就三类：普通线路的 KVM、回国线路的 CN2 GIA、带保障的 SLA。

普通线路便宜，放个博客、跑个脚本、当跳板都够用，一年五十美元起步。

CN2 GIA 配置和它一样，价格贵三倍，多出来的钱全花在回国线路上。网站主要给国内的人看，或者你要连上去写代码，就选这个。

还有个好处：**同一个价格能选 15 个机房**。洛杉矶三个、圣何塞、弗里蒙特、纽约两个、温哥华两个、阿姆斯特丹三个，再加迪拜、东京、大阪。后台随时能迁，不花钱，数据也不丢。买完发现机房不合用，换一个就是了。

SLA 多了 99.99% 的可用性承诺，还有每两周免费换一次 IP。适合正经跑业务的人，自己玩没必要。这档目前只有洛杉矶 USCA_5 一个机房。

香港、东京、大阪也有 CN2 GIA，起步就是 2G 内存，延迟比洛杉矶低，价格也高一截。只卖一个机房，迁不了。

## 不想挨个比，先看这三款

- **放个小站、学 Linux：KVM 20G。** 1 GB 内存、20 GB 硬盘，$49.99/年，适合先买一台入门。👉 [从这款看起](https://bandwagonhost.com/aff.php?aff=82279&pid=44)
- **主要给国内的人用：CN2 GIA 20G。** 同样是 1 GB 内存、20 GB 硬盘，$169.99/年，多花的钱用在线路上。👉 [看看这款 CN2 GIA](https://bandwagonhost.com/aff.php?aff=82279&pid=87)
- **跑业务，需要可用性承诺：SLA 20G。** $239.99/年，带 99.99% SLA 和每两周免费换一次 IP 的服务，机房是洛杉矶 USCA_5。👉 [看看 SLA 这一档](https://bandwagonhost.com/aff.php?aff=82279&pid=164)

## 搬瓦工套餐多少钱？常见配置价格表

| 套餐名称 | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- |
| KVM 20G | 1 GB | 20 GB SSD | 1 TB | 1 Gbps | $49.99/年 | [立即购买](https://bandwagonhost.com/aff.php?aff=82279&pid=44) |
| KVM 40G | 2 GB | 40 GB SSD | 2 TB | 1 Gbps | $52.99/半年，$99.99/年 | [立即购买](https://bandwagonhost.com/aff.php?aff=82279&pid=45) |
| KVM 80G | 4 GB | 80 GB SSD | 3 TB | 1 Gbps | $19.99/月 | [立即购买](https://bandwagonhost.com/aff.php?aff=82279&pid=46) |
| KVM 160G | 8 GB | 160 GB SSD | 4 TB | 1 Gbps | $39.99/月 | [立即购买](https://bandwagonhost.com/aff.php?aff=82279&pid=47) |
| KVM 320G | 16 GB | 320 GB SSD | 5 TB | 1 Gbps | $79.99/月 | [立即购买](https://bandwagonhost.com/aff.php?aff=82279&pid=48) |
| CN2 GIA 20G | 1 GB | 20 GB SSD | 1 TB | 2.5 Gbps | $49.99/季，$169.99/年 | [立即购买](https://bandwagonhost.com/aff.php?aff=82279&pid=87) |
| CN2 GIA 40G | 2 GB | 40 GB SSD | 2 TB | 2.5 Gbps | $89.99/季，$299.99/年 | [立即购买](https://bandwagonhost.com/aff.php?aff=82279&pid=88) |
| CN2 GIA 80G | 4 GB | 80 GB SSD | 3 TB | 2.5 Gbps | $56.99/月 | [立即购买](https://bandwagonhost.com/aff.php?aff=82279&pid=89) |
| 大阪 CN2 GIA 40G | 2 GB | 40 GB SSD | 500 GB | 1.5 Gbps | $49.99/月 | [立即购买](https://bandwagonhost.com/aff.php?aff=82279&pid=134) |
| 香港 CN2 GIA 40G | 2 GB | 40 GB SSD | 500 GB | 1 Gbps | $89.99/月，$899.99/年 | [立即购买](https://bandwagonhost.com/aff.php?aff=82279&pid=95) |
| 香港 CN2 GIA 80G | 4 GB | 80 GB SSD | 1 TB | 1 Gbps | $155.99/月，$1559.99/年 | [立即购买](https://bandwagonhost.com/aff.php?aff=82279&pid=96) |
| 东京 CN2 GIA 40G | 2 GB | 40 GB SSD | 500 GB | 1.2 Gbps | $89.99/月，$899.99/年 | [立即购买](https://bandwagonhost.com/aff.php?aff=82279&pid=108) |
| SLA 20G（DC5） | 1 GB | 20 GB NVMe | 1 TB | 2.5 Gbps | $65.89/季，$239.99/年 | [立即购买](https://bandwagonhost.com/aff.php?aff=82279&pid=164) |

价格是官网现在的标价，活动的时候会低一点，以结账页为准。限量版套餐库存不稳定，没列进来，需要的话直接去官网看。

## 我的建议

不知道自己要干什么，先买最便宜的 KVM 20G。一年三百多块，试错成本很低。

确定是给国内用户访问，直接上 CN2 GIA，省得来回折腾。

有一点要分清：迁机房只换位置，不换配置。机房选错了，后台免费迁，数据也不丢；配置买小了，只能补差价升级。所以机房可以慢慢试，配置最好一次想清楚。

只想临时用几天，那就别买年付，按小时计费的云平台更合适。

## 几个常问的

**IP 被封了怎么办？** 可以付费换 IP。想靠迁机房解决的话，得等这个 IP 连续七天不在黑名单里。

**能退款吗？** 有退款期，过了就不行，续费也不算新订单。买之前想清楚用途。

**快不快？** 我没法替你保证。同一个机房，电信、联通、移动的体验都不一样。自己拿测试 IP ping 一下最准。

**能建站吗？** 能。不过这是自己管的机器，系统更新、网站环境、备份都得自己弄，不像虚拟主机那样装好就能用。

## 现在去买

想好了就去看看。

👉 [去搬瓦工官网挑一台](https://bandwagonhost.com/aff.php?aff=82279)

第一次买，流程不复杂。选套餐、选机房、付款，十分钟的事。

## 选机器

- [搬瓦工套餐怎么选：KVM、CN2 GIA 和 SLA](articles/02-搬瓦工套餐评估.md)
- [便宜 VPS 怎么挑，搬瓦工入门款适合谁](articles/03-便宜VPS推荐榜单.md)
- [搬瓦工 CN2 GIA 是什么，比普通线路贵在哪](articles/04-CN2GIA线路VPS推荐.md)
- [搬瓦工和其他 VPS 怎么选](articles/05-搬瓦工对比其他VPS.md)
- [洛杉矶、香港、东京和大阪机房怎么选](articles/09-搬瓦工机房怎么选.md)
- [SLA 套餐多了什么，DC5 适合谁](articles/11-搬瓦工SLA套餐.md)

## 买和用

- [搬瓦工怎么买更划算](articles/06-搬瓦工优惠与省钱.md)
- [搬瓦工购买教程：注册、选套餐和支付宝付款](articles/07-搬瓦工注册购买教程.md)
- [搬瓦工可以月付吗，季付和年付怎么选](articles/10-搬瓦工月付季付年付.md)
- [连不上了先查这里](profile/README.md)
- [常见问题](articles/08-搬瓦工常见问题FAQ.md)

---

这里是我个人整理的内容，和搬瓦工官方没关系。价格和条款会变，下单前自己再核对一遍。
