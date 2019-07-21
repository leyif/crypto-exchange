# crypto-exchange

# 项目介绍 -- 24MEX 24mex

目前最火的差价合约交易所系统、获客最快盈利最快的新型交易所

指数型差价合约交易所系统、ICFD 指数型差价合约交易所、BTC 比特币杠杠交易、领先数字货币杠杆交易所（高达 100 倍杠杆）

BTC 杠杆交易,比特币杠杆交易，ETH 杠杆交易,以太坊杠杆交易,数字货币杠杆交易、支持比特币杠杆交易、以太坊杠杆交易，等各类主流货币杠杆交易。最高百倍杠杆、边挖 BTC、ETH、BCH、LTC、XRP，边交易。数字货币比特币 BTC 微盘交易系统开发、数字货币比特币 BTC 微交易系统，数字货币比特币 BTC 合约系统

24MEX 交易所系统软件开发,全部源码开放对接

# 平台交易介绍

平台交易模式的特点是平台自身不产生价格，从而保证价格的公正性，交易用户及流动性供应商之间只围绕指数价格进行报价和撮合，系统平仓采用指数价格，从而避免期货类交易所因价格偏离或被操纵而被迫爆仓。

指数型差价合约使用杠杠交易，最高 100 倍，以少量的保证金购买 N 倍的数字货币，同股票期货交易一样，盈利或者亏损由您买入和卖出价格决定，同时支持买涨和买跌。最大优势是最少的钱，买最多的币，赚更多的钱！

支持多空双向交易，保证金低至 1%，收益放大 100 倍。

# 产品优势

### 1.强制平仓

爆仓率 80%，极大的保证客户交易安全。

### 2.连续报价

全年无休，7×24 小时连续报价自由交易。

### 3.USDT 出入金

规避政策风险，支持 24 小时无忧出入金，场外交易系统自动审核。

### 4.无涨跌幅

数字货币没有涨跌幅限制，无强制交割机制，是永续合约交易机制。

### 5.安全可靠

资产存储多重签名冷钱包 保障资金安全。

### 6.交易便捷

部署平台覆盖 iOS、Android、PC、H5 多个平台

### 7.用户体验强

客户使用门槛低，只需判断趋势买涨买跌既有机会盈利。

# 系统涵盖
vuejs前后端分离设计，由15个子系统构成，确保系统灵活安全独立运行


# 代理商功能

## 需求实现：
用户只需通过代理商提供的安装包下载安装即可。
用户直接注册后会自动成为该代理商的用户，不用填写邀请码（邀请码可以跟普通注册一样填其他用户的邀请码，不影响代理商的统计关系）

## 代理商可以登录代理商后台，查看其邀请的用户情况
包括：基础统计、订单查看（订单盈亏情况，带统计）、流水记录查看、用户信息（脱敏）查看、经理人关系查看、充币记录查看、提币记录查看。
查看的信息均为该代理商邀请的旗下用户信息，无法查看其他用户的信息。

## 可建N个代理商账号，进行分发下载，各代理商之间独立管理和统计，方便运营市场扩张

# 支持功能：

## 罗列已全部实现完成

> 多交易对

- [x] 目前支持 USDT、BTC 为计价币的交易对

> 实盘交易

- [x] 支持十余种数字货币（BTC、ETH、EOS、LTC、USDT、XRP、BCH 等）
- [x] K 线绘制 (自实现非插件)
- [x] 下单模式：市价下单、触发下单；
      1、市价下单:不需要设定成交价格，直接按当时市场的对手价成交。
      2、触发下单:当您指定的价格到达后，按当时市场的对手价成交。

- [x] 下单(买涨、买跌)；
      1、标准版下单。
      2、专业版下单。
      3、快速版下单。

- [x] 撤单
- [x] 批量撤单
- [x] 最高 100 倍下单，
- [x] 自定义止损止盈设置
- [x] 自动平仓
- [x] 收取手续费
- [x] 过夜费收取
- [x] 过夜费不足平仓
- [x] 止盈止损触发平仓
- [x] 实盘持仓
- [x] 支持红包抵扣

> 模拟交易

- [x] 功能同实盘交易
- [x] 采用平台币交易的方式模拟交易

> 数字货币挖矿

- [x] 支持 6 种主流数字货币挖矿（BTC、ETH、EOS、LTC、USDT、XRP）
- [x] 支持平台自身币挖矿
- [x] 支持主流数字一键兑换稳定币
- [x] 支持配置任务，定时、定量挖矿奖励
- [x] 支持配置用户任务挖矿奖励（注册、模拟、充值、交易等）

> 行情对接

- [x] 火币交易行情
- [x] OKEX 交易行情
- [x] 币安交易行情

> 快讯

- [x] 快讯列表+推送
- [x] 快讯爬虫抓取自动更新

> 用户

- [x] 多重模式注册（手机、邮箱）
- [x] 登录、退出
- [x] 找回密码
- [x] 修改密码
- [x] 资金明细
- [x] 实名认证
- [x] 邮箱绑定
- [x] 手机绑定
- [x] 绑定银行卡
- [x] 绑定微信支付宝支付
- [x] 绑定提币地址
- [x] 交易设置

> 充值

- [x] 数字货币钱包充值
- [x] C2C 法币直接购买数字货币
- [x] 充值记录

> 提币

- [x] 数字货币钱包提币
- [x] C2C 出售数字货币直接换法币
- [x] 站内账号简划转
- [x] 提币记录

> C2C 交易状态管理

- [x] 充币确认数
- [x] 提币确认

> 客服系统

- [x] 客服在线聊天(一对一)
- [x] 用户通知机制
- [x] 状态通知（交易、平仓、充币、提币）

> 帮助中心

- [x] 列表模式

> 邀请机制

- [x] 邀请佣金奖励机制
- [x] 邀请好友列表
- [x] 邀请海报自动生成
- [x] 邀请口令
- [x] 邀请好友可获得手续费 30%返佣
- [x] 等级返佣 L1-10%、L2-20%、L3-30%，根据不同的等级进行设置返佣

# 新增活动落地页 6 个

方便直接可以用于市场推广及宣传，可直接与广告商接入使用

- [x] 活动宣传页
- [x] 广告注册页
- [x] 抽奖引导页

# 行情管理

## 行情一键恢复
可快速一键恢复行情（K线），适用服务终止或出问题等情况的修复

## 行情修正（价格发布）
可定制化的修复价格行情

注：该功能主要是用于修正剧烈行情震荡给用户来带不必要的损失，请勿做他用


# 流水复核
> 可针对所有用户进行多维度的流水校验和复核，自动计算复核结果，用于用户提币转账等关键操作校验

# 报表统计导出
> 关键数据统计，均有可筛选条件的数据统计及数据导出功能
> 自选时间段和数据类型，进行数据统计导出，包括下单、盈亏、手续费、充、提、奖、穿仓等分类选择

## 后台管理

> 数据统计

- [x] 用户统计
- [x] 订单统计
- [x] 资产统计

> 交易管理

- [x] 币种管理
- [x] 订单管理
- [x] 流水管理
- [x] 交易设置

> 用户管理

- [x] 用户管理
- [x] 用户认证
- [x] 支付管理
- [x] 验证码管理
- [x] 用户日志
- [x] 分类管理

> 挖币管理

- [x] 币种管理
- [x] 挖币记录

> 平台币生态

- [x] 平台币挖矿
- [x] 商品兑换

> 财务管理

- [x] 资产总览
- [x] 充币审核
- [x] 充币记录
- [x] 提币审核
- [x] 提币记录
- [x] 发放奖励

> OTC商家

- [x] OTC商家管理
- [x] OTC买卖管理

> 钱包管理

- [x] 充值钱包管理
- [x] 提币钱包管理

> 行情管理

- [x] 行情设置
- [x] 测算发布

> 新闻管理

- [x] 新闻列表
- [x] 爬虫设置
- [x] 发布新闻

> 客服管理

- [x] 消息设置
- [x] 客户对话，实时客户对话解答

> 社区管理

- [x] 消息设置
- [x] 客服管理


> 系统设置
- [x] 全站交易设置
- [x] 管理员设置，创建、修改密码、冻结账号
- [x] 代理商管理

# 聊天社区

在线实时聊天系统，参考gateio功能（websocket版）
1、含文字、表情、图片、VIP标识、敏感词过滤
2、可禁言用户XX分钟
3、可随意创建马甲账号聊天
4、创建客服账号聊天及互动

# 平台币发行

基于以太坊的标准智能合约系统发行的平台币，目前已实现平台币挖矿、兑换等基础功能。后期将考虑加入抵扣、挖矿、交易等，逐步完善。

# 钱包管理

## 自动分配（账户注册后自动分配冷钱包地址）

## 自动充值（充值自动入账到用户账号，自动扫描区块）

## 自动提币，自动风控校验出币（多重签名、单笔转币、批量合并转币），可设置人工审核出币


# 说明

该系统考虑周全，有自己团队折腾，所以从开发、设计、效率、运营、成本等情况都有做优化，基本技术上只要简单 1-2 维护人即可平稳运行。

项目意向，技术及运营, 如果您也看好该模式，欢迎来撩

合作交流 QQ：1480285853 (诚意交流)


# 合约交易介绍

平台交易模式的特点是平台自身不产生价格，从而保证价格的公正性，交易用户及流动性供应商之间只围绕指数价格景象报价和撮合，系统平仓采用指数价格，从而避免期货类交易所因价格偏离或被操纵而被迫爆仓。

指数型差价合约使用杠杠交易，最高 100 倍，以少量的保证金购买 N 倍的数字货币，同股票期货交易一样，盈利或者亏损由您买入和卖出价格决定，同时支持买涨和买跌。最大优势是最少的钱，买最多的币，赚更多的钱！

支持多空双向交易，保证金低至 1%，收益放大 100 倍。

<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/def.png" width="720" height="300"/>

## 交易举例

### 买涨举例：

<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/buy1.png" width="558" height="413"/>
比特币价格 50000，
您有 50000，

现货交易：
50000 只能购买 1 个比特币，当比特币上涨 10%，您的收益为 5000

差价合约交易：
1 个比特币的购买保证金按 1000 算，50000 元能买 50 个比特币，当比特币上涨 10%后，您的收益为 250000，收益翻 50 倍

### 买跌举例：

<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/buy2.png" width="558" height="413"/>
比特币价格 50000，
您有 50000，

现货交易：
不支持买跌，无法进行交易！

差价合约交易：
1 个比特币的购买保证金按 1000 算，50000 元能买 50 个比特币，当比特币下跌 10%后，您又赚了 250000

# 部分截图

## 前端展示

### 交易页面

<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/trade.png" width="365" height="619"/>
<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/trade.gif" width="365" height="619"/>

### 登录注册

<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/login.gif" width="365" height="619"/>

### 挖矿页面

<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/mine.png" width="365" height="619"/>

### 充值提币

<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/sell.png" width="365" height="619"/>
<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/buy.png" width="365" height="619"/>
<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/tibi.png" width="365" height="619"/>

## 后台管理

### 交易对管理

<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/contract.png" width="975" height="468"/>
### 流水管理
<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/record.png" width="975" height="468"/>
### 用户充值
<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/recharge.png" width="975" height="468"/>
### 订单管理
<img src="https://github.com/freedom-is-life/crypto-exchange/blob/master/demo/images/order.png" width="975" height="468"/>
