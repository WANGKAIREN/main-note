# 关于数据ID

比如一个用户表，每个用户都需要一个唯一ID，而这个ID不可以用自增ID，在库迁移的时候会有问题，比如说每条短信的任务ID，在关联关系上库迁移或表有所变化时，自增ID都不是很好维护。

> 为什么需要 userId，而不是 userName，如果应用如微信，那么 userName 相当于微信号，微信号是可更改的，需要一个不会变的用户标识。
