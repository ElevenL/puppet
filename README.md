扯线木偶（puppetrader unity for ths client）

-- 用ctypes模块写的同花顺交易客户端遥控木偶。

2017/2/14 0.2版发布！提供后台获取持仓数据。鸣谢网友liuyukuan博文中提供的AHK代码“SendMessage,0x111,57634,0,CVirtualGridCtrl2,同花顺”。

1、支持同花顺的“所有”交易客户端：官方统一版或老版、券商定制版（银河、国泰君安、华泰、广发、东方财富等）。

2、支持多种交易模式：同一券商多个账户、多个券商多个账户同时登录一个（或多个）交易端，并且同时进行交易。

3、目前仅支持多个不同的交易客户端登录后同时交易，暂时不支持一个交易客户端多个账户登录后同时交易。

下一步计划：精简交易行为逻辑，重构新版本，支持同一股票多账户并发下单、多账户自动登录、掉线重登陆。
