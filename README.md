# 夸克区块链用户指南

### 一.简介

夸克区块链是国内仓舟公司主导开发和维护的区块链项目。

本项目17年11月底开始开发，2018年2月8日正式上线，已经有五千多名活跃用户。

### 二.规则

1. 积分的产出规则

- 每天限量产出7200分，团队获得10%，即720分，剩余的6480分按用户各自算力分配给全体用户。

- 每个用户每天获得的积分数=个人算力/总算力*6480。

- 个人算力占总算力的比重越大，每天获得的积分越多。

（以下图为例，左上方为个人算力，左下方为总算力）



2. 节点开通规则

夸克拥有两种不同的节点性质：

- 物理节点：拥有真实的服务器，支持微/小/中/大型节点。
开通方式：需要在官方网站缴纳一定费用的租赁费用，可以运行三十天。

- 虚拟节点：没有真实的服务器，目前节点数量上限为10个，支持微/小/中型节点。
开通方式：在APP中申请「支付宝认证」，即可用积分开通。
3. 节点升级规则

升级不区分节点的性质，物理节点和虚拟节点的升级方式一致，仅需要缴纳一定的积分作为保证金即可升级，作为保证金的积分将会暂时冻结，在下个月归还。

| 节点类型        | 需要积分           | 拥有算力  | 支持类型|
| ------------- |:-------------:| -----:|  -------------|
| 微型         | 1               | 1 | 物理/虚拟|
| 小型      | 10      |   10 |物理/虚拟|
| 中型 | 100      |   100 |物理/虚拟|
|大型| 1000|1000|物理|

每个节点运行时长均为30天。
不同节点运行时，所需积分会被被冻结在账户内，账户积分余额不低于所拥有的算力。

*注：未来将逐渐取消虚拟节点，会逐步支持个人用户自行搭设节点*

4. 节点回报利润

理论月回报率=（6480*30）/总算力 * 100%

由于每天都有新的产出的积分，用户可以将这部分积分继续冻结转换成算力以获得更多的收益。

如果每天都将所有产出冻结，那么实际月回报率将会比理论月回报率高

### 三. 与其他区块链项目的不同

- 夸克区块链是一种基于PHP语言的区块链，最终是希望通过区块链技术提供分布式web和分布式储存以及分布式流媒体播放服务。

- 夸克区块链团队承诺没有进行任何的积分预挖和积分抛售

- 目标是做成一个属于所有人的区块链项目。

## 附录一：夸克区块链基本使用说明

1.注册指南

进入：http://www.quarkblockchain.com/login 进行注册

![](https://upload-images.jianshu.io/upload_images/10632197-cad89ac0ac0626bf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


如果英文看不懂，点击左上角的「English」，即可切换为中文界面

![](https://upload-images.jianshu.io/upload_images/10632197-86ab2e87f6ab3fee.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

点击右上角的注册按钮，会进入一个新的界面
![](https://upload-images.jianshu.io/upload_images/10632197-a6ba75ba96e26b87.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


输入完用户名以及密码后，直接点提交，然后进行登录。
![](https://upload-images.jianshu.io/upload_images/10632197-a3134be768d69125.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

登陆后可以保存自己的私钥，点击右上角的齿轮。

![](https://upload-images.jianshu.io/upload_images/10632197-29b04d7dbcec38dc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

点击查看私钥即可保存，请勿泄露给他人。
![](https://upload-images.jianshu.io/upload_images/10632197-80e73652e9dbea0b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


**请一定要牢记密码，密码丢失无法找回**


2.转账步骤

登陆的你的夸克账号：https://www.quarkblockchain.com/


向下的箭头为他人转入积分给你（告诉他人你的地址）
![](https://upload-images.jianshu.io/upload_images/10632197-d56c45360ba2d873.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

向上的箭头为你转出积分给别人
![](https://upload-images.jianshu.io/upload_images/10632197-2ce0399447ae0272.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


如图操作即可

3.节点申请
虚拟节点申请点击底部「我的」，之后进行如图操作

![](https://upload-images.jianshu.io/upload_images/10632197-f0c89fc478c451d5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

物理节点请到：http://share_node.quarkblockchain.com/node进行相关申请

4.节点升级

点击主节点>节点升级即可（需要满足升级条件数量积分）

5.增加算力

当积分不足以升级节点时，可以通过增加算力来进行算力的增加，点击主节点>增加算力即可，一分对应一算力




## 附录二：常见问题问答

Q：什么是区块链

A：一句话，它是一种特殊的分布式数据库。首先，区块链的主要作用是储存信息。任何需要保存的信息，都可以写入区块链，也可以从里面读取，所以它是数据库。其次，任何人都可以架设服务器，加入区块链网络，成为一个节点。区块链的世界里面，没有中心节点，每个节点都是平等的，都保存着整个数据库。你可以向任何一个节点，写入/读取数据，因为所有节点最后都会同步，保证区块链一致。

Q：夸克区块链的积分有什么用

A：目前可以供用户交流学习/开通节点服务器等作用，夸克本身的价值由大家的共识决定，更多功能等待你发掘。

Q：我如何进行积分的转入和转出？

A：参考附录一

Q：一个用户能开多少节点？算力上限多少？

A：一个用户初始拥有1个虚拟微型节点，点击主节点页面右上方“加号”可以增加1个虚拟节点，最多增加至10个，每个虚拟节点最多可以升到中型（100算力），也就是一个账号的虚拟节点最多提供1000算力；物理节点可以升级至大型节点，单独可供1000算力（详见规则）

Q：积分冻结是什么意思，冻结的积分还能使用吗？

A：节点运行需要一定的积分当作保证金，防止恶意多开，而这部分冻结的积分就是你的保证金。算力即是节点服务器的权重，保证金等于权重，积分和算力数值上相等，当节点运行时，这些积分就被当作保证金运行冻结了，无法转账，但是依然属于用户。等待节点运行到期后，积分便会自动解冻。

Q：一个节点能运行多久？

A：一个节点能够运行的时间是720小时，也就是30天，当节点运行了30天后将虚拟节点会自动销毁（物理节点会停止运行）

Q：续期需要费用么？

A：在节点运行到期前3天，可以免费续期。

Q：物理节点怎么开通？我有服务器，可以自己搭建物理节点么？

A：目前物理节点需要租用服务器，月租金50元，开通链接如下：开通链接。目前不支持自行搭建，后期将会逐步开放

Q：为什么我的产出不如别人？

A：用户可以通过开通或者升级节点来获得相应的算力，算力将决定获得的积分多少。每个用户的产出率相等。

Q：如何联系开发团队

A：www.quarkblockchain.com
