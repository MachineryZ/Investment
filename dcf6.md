# 预测三张财务报表

上一张的一些问题
1. 预测营收的增长，是如何确定的。如果是成本，我们可以用历史的平均值。但是营收是没有人用历史的数据来作为未来的预测的。
2. 零售类的预测，除了 revenue 不太一样，其他的地方是类似的，学完整个流程就可以举一反三
3. revenue 的预测，是没有统一的方式的，统一个公司

今天看成本端，
1. 成本构成有：销售费用，管理费用，研发费用（r & d），折旧，等等

revenue - cost of sales = 毛利润。每卖一件商品，需要的成本是 cost of sales。毛利润的变化一般不会特别大，可以用历史数据进行取平均。但是也可以做拆分。

total gross profit，总的毛利润。那么总的毛利润又可以拆分为 saas product 和 erp solutions 两个部分。
1. saas 部分
    1. staffing cost 员工福利费用
    2. information techonology cost 信息科技成本
    3. cogs 已售存货成本
    4. tax and others 税收以及其他
2. erp 
    1. staffing cost
    2. outsourcing cost 外包费用
    3. cogs
    4. others
3. 我们会发现，其实毛利率的变化并不是特别大，所以可以取平均

在预测的时候，成本的预测，也和 revenue 一样，也是一种艺术，大致的一个预测。
1. 已售存货成本和tax增长快的原因还是因为，和 revenue 是成一定比例的，revenue增长快，这两项就快

整个 cost of sale 的预测，其实就是和 revenue 非常类似

其他的成本：
1. 要么认为 depreciation 折旧，要么和 revenue 保持一致
    1. other income and gains，这个和 revenue 关系不大，单独预测
    2. selling and distribution expenses，这个和 revenue 保持一致
    3. general and administration，管理费用，认为和过去的增长率保持一致
    4. r & d，研发费用，和卖出费用也没太大关系
    5. dd & a，depreciation 最严格的方式是 ppe schedule 用固定资产表去计算，对于 depreciation 不太多的公司，可以认为占 revenue 的一定比例