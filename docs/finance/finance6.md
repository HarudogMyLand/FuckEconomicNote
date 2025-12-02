# 利率与金融资产定价

## 金融资产收益和风险的衡量

利率是连接金融资产未来现金流和当前资产价格的纽带。对于任何一种资产或者投资几乎，其当前价值就是未来所有现金流贴现和：
$$
P_0 = \sum^T_{i=1}\frac{B_i}{(1+r)^i}
$$
因此，收益率：
$$
r=\frac{C}{P_0}+\frac{P_1-P_0}{P_0}
$$
然而未来价格 $P_1$ 是不确定的，因此预期收益率计算为：
$$
\bar{r} = \sum^n_{i=1}p_ir_i
$$
风险使用标准差计算：
$$
\sigma = \sqrt{\sum^n_{i=1}p_i(r_i -\bar{r})}
$$

### 组合投资收益与风险

以各资产占比为权重 $\omega$ 收益率期望为
$$
r_p = \sum^n_{i=1}\omega_i \bar{r_i}
$$
风险为：
$$
\sigma = \sqrt{\sum^n_{i=1}\omega^2_i\sigma^2_i + \sum_{1\le i \lt j\le n} \omega_i \omega_j \sigma_i \sigma_j \rho_{ij}}
$$
其中 $\rho_{ij}$ 是相关系数。