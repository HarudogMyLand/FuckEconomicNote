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

### 现代投资组合理论

如图所示是不同投资组合下的收益率与风险组合。

由于**系统风险**的存在，某些收益率与风险的组合是投资组合无法覆盖的，即无法通过分散化投资来消除。

我们把投资组合覆盖区域的边界视为我们投资组合的一个极端。而**有效边界**是风险相同、收益最大，或收益相同、风险最小组合点的连线。有效边界上的资产组合为有效组合。

<center><svg width="600" height="400" viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg" style="background-color: #f5f5f5; border: 1px solid #ccc;">     <defs>         <marker id="arrow" markerWidth="10" markerHeight="10" refX="9" refY="3" orient="auto" markerUnits="strokeWidth">             <path d="M0,0 L0,6 L9,3 z" fill="#000" />         </marker>     </defs>     <line x1="60" y1="350" x2="60" y2="60" stroke="#000" stroke-width="1.5" marker-end="url(#arrow)" />     <line x1="60" y1="350" x2="530" y2="350" stroke="#000" stroke-width="1.5" marker-end="url(#arrow)" />     <text x="20" y="50" class="axis-label" fill="black">期望收益率</text>     <text x="20" y="80" class="math-label" fill="black">E(r)</text>     <text x="500" y="380" class="axis-label" fill="black">风险σ</text>     <path d="M 230 330 C 130 280 100 240 100 200 C 100 160 130 120 520 80" stroke="#000" stroke-width="2" fill="none" />     <circle cx="100" cy="200" r="4" fill="black" />     <text x="75" y="205" class="point-label" fill="black">A</text>     <circle cx="300" cy="122" r="4" fill="black" />          <circle cx="115" cy="165" r="4" fill="black" />     <text x="100" y="160" class="point-label" fill="black">D</text>     <circle cx="300" cy="165" r="4" fill="black" />     <text x="310" y="185" class="point-label" fill="black">C</text>         <circle cx="180" cy="220" r="3" fill="black" />     <circle cx="210" cy="250" r="3" fill="black" />     <circle cx="260" cy="230" r="3" fill="black" />     <circle cx="330" cy="210" r="3" fill="black" />     <circle cx="400" cy="190" r="3" fill="black" />     <circle cx="450" cy="150" r="3" fill="black" />     <circle cx="380" cy="140" r="3" fill="black" />     <circle cx="220" cy="180" r="3" fill="black" />     <circle cx="280" cy="190" r="3" fill="black" />     <circle cx="350" cy="260" r="3" fill="black" />     <circle cx="420" cy="280" r="3" fill="black" />     <circle cx="320" cy="290" r="3" fill="black" />     <circle cx="250" cy="280" r="3" fill="black" />     <circle cx="140" cy="225" r="3" fill="black" />     <circle cx="480" cy="180" r="3" fill="black" />     <circle cx="350" cy="150" r="3" fill="black" />     <circle cx="420" cy="110" r="3" fill="black" />     <circle cx="250" cy="150" r="3" fill="black" />     <circle cx="480" cy="90" r="3" fill="black" />     <circle cx="220" cy="130" r="3" fill="black" />     <circle cx="180" cy="190" r="3" fill="black" />     <circle cx="400" cy="240" r="3" fill="black" />     <circle cx="115" cy="210" r="3" fill="black" />     <circle cx="440" cy="220" r="3" fill="black" /> </svg></center>

如图所示，其中 $A$ 点以上就是有效边界的示意。

## 利率与有价证券价值评估

### 有价证券价值评估原理

l证券的内在价值，是证券未来收益的现值，取决于预期收益与市场收益率水平，也称证券的理论价值。证券的内在价值采用**现金流折现法**计算。

- 绝对价值评估：指将公司未来可能创造的现金流或公司未来可能分配的股息，按一定折现率进行折现，来评估公司的内在价值。
- 相对价值评估：是通过比较公司的基本面数据和市场数据来确定股票的相对价值。有价证券的相对价值评估通常使用市盈率、市净率等指标。

### 绝对价值评估与相对价值评估

绝对价值评估

- 股票价值评估：股票收益是不稳定的，现金流折现法计算需要更多工作。对于优先股，价值评估类似于永续债权，而普通股需要全部折算为现值。

$$
P=\sum^{\infty}_{i=1}\frac{C_i}{(1+e)^i}=\frac{(1+g)D_0}{r-g}
$$

相对价值评估

- 市盈率 (PE) = 股票市价 / 每股盈余：越低，回收期越短，投资价值越大
- 市净率 (PB) = 股票市价 / 每股净资产：越低，投资价值越高，反之则反

### 金融市场定价模型

#### 马科维茨模型 MPT

核心思想是分散化投资，构建不同资产组合降低**整体风险**。

- 风险估计：使用 $\sigma$ 和 $\sigma^2$ 度量
- 相关组合：相关系数 $\rho<1$ 分散化就能起作用
- 有效边界：所有最优组合

这就是我们刚刚提及的有效边界理论。

缺点在于：计算量巨大，不可能简便计算 $N$ 个元素的数学期望，方差和 $N(N-1)/2$ 个协方差。同时，找了半天有效前沿，但**没告诉投资者到底该选哪一个点**。

#### 资本资产定价模型 CAPM

核心思想是风险定价，市场只为**系统性风险**提供回报。

- 风险拆分：风险分为系统性和非系统性
- 贝塔值$\beta$：系统性风险度量
- 资本市场线：CML描述**有效组合**的风险收益关系
- 证券市场线：SML描述**所有资产**的风险收益关系

缺点在于：假设太多，市场有效、投资者同质、市场组合也可知（然而谁也不知道真正的市场组合将会是什么）；同时，某些实证检验效果也不好，$\beta$ 不完全能解释股票收益率差异

#### 有效市场假说 EMH

核心思想是信息有效性，假定资产价格已经充分反映了所有**可获取的信息**。