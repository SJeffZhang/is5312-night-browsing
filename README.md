# 深夜刷淘宝，真的更容易下单吗？

用 1 亿条淘宝真实浏览记录，检验「深夜更容易冲动消费」这个直觉。

- 数据：天池 649（UserBehavior）公开镜像，100,095,182 条行为事件，2017-11-25 至 12-03
- 分析单位：用户 × 商品「首次可见浏览」（5,131 万个 episode）
- 方法：固定效应线性概率模型 / Cox 生存分析 / Causal Forest（DML）
- 在线报告：https://sjeffzhang.github.io/is5312-night-browsing/

内容为课程项目（IS5312 Analytical Programming with Python）中期汇报，全部为观察性关联。
