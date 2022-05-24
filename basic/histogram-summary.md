## Histogram & Summary


- Summary 和 Histogram的不同点

| | Histogram | Summary
----|-----|-----
$\phi$-quantiles 计算| 需要在server端通过histogram_quantile()函数实现 |客户端直接计算
能获取到的值 | 每个桶的累计值| $\phi$ 在客户端就确定了


