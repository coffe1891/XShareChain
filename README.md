# XShareChain全球闲置物品共享链白皮书
<div style="text-align:center">
<img src="XShare-logo.jpg" width="480px">
</div>
<br/>
全球网民参与共治的闲置物品共享链

## 目录
* 1、前言
  * 1.1 项目背景
  * 1.2 机遇 
* 2、XShareChain全球闲置物品共享链
  * 2.1 区块链是什么
  * 2.2 智能合约是什么
  * 2.3 XShareChain整体架构
  * 2.4 XShareChain核心技术特性
      * 2.4.1 保值货币XShareCoin
      * 2.4.2 共识系统
      * 2.4.3 志愿巡警XSharePolice
      * 2.4.4 交易机制
      * 2.4.5 评价机制
      * 2.4.6 交易有效性自动审核机制
      * 2.4.7 奖励&惩罚机制
  * 2.5 边界异常处理 
      * 2.5.1 51%攻击 
      * 2.5.2 用户疯狂上链闲置物品导致货币XShareCoin价格暴涨
      * 2.5.3 用户结盟下链闲置物品导致货币XShareCoin价格暴跌
      * 2.5.4 投机者操纵货币XShareCoin价格导致暴涨暴跌
      * 2.5.5 其他技术故障
  * 2.6 路线图
  * 2.7 生态&矩阵
* 3、治理&架构哲学
  * 3.1 XShareChain自治委员会
  * 3.2 选举机制
      * 3.3.1 周期
      * 3.3.2 主席
      * 3.3.3 委员 
  * 3.3 经济
      * 3.2.1 资金来源
      * 3.2.2 使用预算
      * 3.2.3 财务计划
      * 3.2.4 定期报告
      * 3.2.5 数字资产管理
* 4、团队介绍
  * 4.1 项目顾问
  * 4.2 项目贡献者
* 5、实施计划
* 6、联系信息
* 7、参考文献

## 1、前言
基于区块链技术的比特币从2009年的0.003美元涨到2017年12月18日 19013美元，上涨600多万倍，创造了一个又一个财富传奇，证明去中心化的区块链价值观得到了全球网民的认可。

2010年，美国的程序员拉丝勒•豪涅茨(Laszlo Hanyecz)用1万枚比特币交换了两块价值25美金的披萨，现在看来相当于用了1亿美元买了一块披萨，成为“史上最贵披萨”。

XShareChain是基于区块链技术打造的全新的公链，也即不依赖于任何已有的公链。因为kenny（XShareChain的发起人）不希望因为依赖某个公链，实际上加重了那些公链的中心化地位，导致垄断和不公正发生。

### 1.1 项目背景
**互联网第一波只是交换信息，但到了第二波希望能够交换价值**。

交换价值的核心前提就是要参与者要有一个**共识机制**。在区块链之前的 Distributive System（分布式）系统里面，达到共识是一个非常难的事情，每个网络的节点都有时间的延迟，计算能力也不一样。有的计算机有良好的行为，有的计算机确实有一些不良行为。在一个复杂的网络系统里面，如何达到一个共同的价值，这在那个计算机科学里面也是一直没有解决的问题。因此计算机科学中有一个 Fischer-Lynch-Paterson 定理，在采取一种完全 Deterministic（固定）算法的时候，共识是永远无法达到的，因为这个网络的系统实在太复杂。

后来，大家就想到区块链的技术可以把经济行为加上随机的数学算法使得网络达到共识，比如说通过计算一个 Hash 函数的办法，对共识进行投票，这就是整个区块链上面达到了一个新共识的机制。

为什么这个共识的机制本身会有很大的价值？

事实上物理学里面有一个非常深刻的概念叫熵增，就是物理世界看起来是总是走向无序。但是生命世界和物理世界不太一样，生命世界确实越来越走向有序。走向有序的行为是把熵减少的一个行为，但是整个系统的熵还是在增大。因此，生命行为就是把自己的熵减小了，使周围的熵增大了。
这在共识机制上也是一样。如果我们要达到共识就是要把熵减少，大家如果意见非常不一样的话，熵也就很大，因为非常无序。但是如果能够统一意见，达到一种非常有序的状态，它必然是减小熵的一种行为。然而，减少熵的行为必然会增高周围世界的熵。

因此，当时提出来的算法是通过一些 Hash 函数的计算，这虽然看起来是浪费了一些周围世界的能量，其实得到了一种更可贵的财富，也就是共识。

在这个意义下，区块链的共识系统有点像生命系统本身，自己的熵在减弱，它达到了共识，但使得周围的系统熵变大。这是一个代价，但相比别的系统来讲，这个代价还是非常小。

所以，一旦我们有了共识之后，就会有一种信任，人和人之间会有一个新的合作机会。所以，我把这个新的时代称为：我们的信念是建筑在一个数学的算法上面，In math we trust。在今后的系统中，中心化平台就不再需要，取而代之的是我们能够建立一些P2P的区块。通过开源的投票模式，大家可以用透明的算法，定义这个Community 里面的游戏规则。这就更能导致一个新的互联网的革命，一个合久必分的时代就又会到来。

### 1.2 机遇
现有的中心化闲置物品共享经济平台，比如滴滴打车、闲鱼，存在一系列问题，严重列举如下：

* 中心化平台佣金比例过高，普通用户很难挣钱；
* 中心化平台利用垄断优势对平台用户推行霸权条款；
* 恶意用户刷信誉刷评论虚假宣传，骗取普通用户信任；
* 黑客利用中心化平台漏洞，侵占平台用户的利益；
* 中心化平台客服服务水平普遍不高；
* 中心化平台为了实现更高的经济效益，暗箱操作，更改排名、等级、交易数据等，甚至明码标价出售各种广告位；
* 中心化平台可能会在某些高峰期吞吐量不够而短暂性崩溃，比如春节12306订票网站；

以上所有问题，造成现有中心化的共享经济平台共享物品成本极高，除了极少数头部用户能实现盈利，大多数用户是赔钱买乐趣。因此，很多普通用户不愿意将家里的闲置物品共享出来，宁可放在家里不断折旧贬值，这导致社会资源巨大浪费。

因此，我们提出“XShareChain”这一“全球闲置物品共享链”，依靠区块链技术和智能合约，以期打造一个人人参与、透明公正、互惠多赢的生态链。

## 2、XShareChain全球闲置物品共享链
### 2.1 区块链是什么
@ZH
### 2.2 智能合是什么
@ZH
### 2.3 XShareChain整体架构
（图）
### 2.4 XShareChain核心技术特性
#### 2.4.1 保值货币XShareCoin
**为实现价值交换，必须有货币。**
为方便用户在XShareChain上交易，XShareChain会基于全球闲置物品价值总量发行一种货币，名字叫XShareCoin。

> 全球顶级战略管理咨询公司罗兰贝格2016年底发布共享经济报告指出，至2018年，全球共享经济规模有望达到5200亿美元（约36000亿人民币）。

因此，XShareChain理论上可以发行5200亿美元估值规模的XShareCoin数量。考虑到市场将上不只存在一个共享链（人们也不期望一个垄断链存在导致中心化），按10%市场占有率做预估，发行量为：

*5000万枚 XshareCoin = 500亿美元*

*1枚XshareCoin = 1000美元*

### 2.4.2 共识机制
既然XShareChain不依赖于任何已有的公链，那么XShareChain的共识机制也是与其他公链不一样的。

（以下暂不公开）