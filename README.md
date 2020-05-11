# 个人简介
## 基本信息
* 姓名：阮福伟
* 邮箱：ruanfwtop@163.com
* 联系电话：18768184438

## 职业技能
* 熟悉 JAVA 语言，理解并发、集合等框架，熟悉 JVM。
* 熟悉 Spring、Spring Boot、Mybatis 框架。
* 熟悉 MySQL 数据库、Redis 缓存技术。
* 熟悉 MQ 消息中间件、Dubbo、canal 等中间件。
* 熟悉常用的设计模式。

## 教育经历
杭州电子科技大学 电子信息科学与技术（2010-2014）

## 工作经历
#### 2018 年 6 月份 - 至今 杭州大搜车汽车服务有限公司
##### 工作内容
###### 准实时对账系统
* 功能：
    * 系统间调用发生后，及早发现系统间数据的缺失、不一致的状态，并发出告警，保证系统间数据的一致性，减少客户的影响，在线对账。
* 我的贡献：
    * 负责整体架构设计，功能开发，需求评估及版本迭代。
    * 引入ddd设计，使开发更注重于对账业务本身的逻辑。
    * 核对逻辑使用Grovvy脚本配置实现，支持自由定制核对脚本。
    * 给业务方提供jar包，方便将数据快速接入准实时对账系统。
* 关键成果：
    * 保障了账务域内出款场景、代扣场景、交易场景、记账场景等各个场景的数据一致性的监控，并具有一定的实时性。
    * 各个维度统计对账结果，展示各个业务场景的健康程度、修复情况。
* 发展方向：
    * 多流实时数据join处理，做到真正的实时对账。
    * 对账结果处理对接业务系统，形成闭环。

###### 业务核对系统
* 系统简介：
    * 针对账务域外业务系统开发，离线业务数据全量比对，实现业务数据海量回归，全方位核对，降低不一致数据的出现概率。
    * 对账结果按照开发者自定义转换规则，直接加工形成报表，生成第三方需要的格式文件。
    * 目前该系统分为调度服务、数据服务、数据处理服务、对账服务。
* 我的贡献：
    * 负责整体架构设计，数据模块、数据处理模块开发，需求评估及版本迭代。
    * 对账数据采用文件方式存储与对账，缓解数据库压力。
    * 引入QLExpress来配置核对规则，丰富对账功能，支持简单逻辑运算的对账。
    * 提供了配置页面简化业务方接入核对系统。
* 关键成果：
    * 支持了资管、弹个车、订单中心、代收付等各个业务线的大规模数据状态核对。
    * 接入公司各团队数十个对账任务，日核对数量达千万。
* 发展方向：
    * 接入大数据平台，离线处理对账数据。
    * 提供完整的业务数据对账方案，覆盖更多关键业务数据，从而发现资损点和异常数据。

###### 资金对账系统
* 系统简介：
    * 发现渠道方与我司业务系统的交易流水之间差异，差异数据可自动进行对应处理，对账方式为单向对账和双向对账，对账时机为 T+1 离线对账。
    * 目前该系统分为调度服务、数据服务、对账服务、差错处理服务。
* 我的贡献：
    * 负责整体架构设计，对账服务、差错处理服务的开发，需求评估及版本迭代。
    * 引入Redis，使用Redis的交集特性，可快速完成对账处理
    * 引入canal同步业务系统的交易流水，缓解业务库压力。
    * 差错自动处理，解决跨日自动调整等问题。
* 关键成果：
    * 支持了包括支付宝、微信、宝付、通联POS等各个渠道的对账，解决了业务系统的交易流水金额、手续费。
    * 每日运行对账任务50+，为财务人员减少了大量的人力和时间。
* 发展方向：
    * 对账结果处理接入账务系统，支持登账、挂账、销账等操作。
    * 登账、挂账、销账自动化，减少人工操作。
 
#### 2015 年 4 月份-2018 年 6 月份 杭州云贝网络科技有限公司
##### 工作内容
###### 叮咚云短信平台(dingdongcloud.com)
* 系统简介
    * 短信（语音）验证码、通知短信、营销短信的发送。
    * 支持 API 提交发送以及平台在线发送。
* 我的贡献：
    * 负责各个 模块的维护以及新需求的实现。
    
###### 叮咚 CRM 
* 系统简介：
    * 基于淘宝开放平台开发的第三方软件，帮助淘宝卖家进行精准会员营销，深度挖掘老客户
    * 支持会员群发、导入号码发送、优惠券及十多项订单短信关怀功能。
* 我的贡献：
    * 负责各个模块的维护以及新需求的实现。 

    
#### 2014 年 4 月份-2015 年 4 月份 恒生电子股份有限公司
##### 工作内容
###### 证券极速交易系统
* 系统简介
    * 毫秒级委托时延。
* 我的贡献：
    * 证券交易系统前后台功能的添加、修改，后台数据的处理。





