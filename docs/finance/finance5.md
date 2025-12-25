# 货币时间价值与利率

## 章节概览

- 利息
  - 分类与体系
  - 使用
- 利益与利率

货币是现代信用活动中最为重要的载体之一，然而货币若不在手中，则失去了对债主的流动可用性。借贷时间直接影响了借贷的利息量。因此在货币信用活动中，时间长短成了影响利息多少的一个重要因素。

## 时间价值与利息

同等金额的货币，当前的货币比未来的更有价值，因为可以对其立刻进行使用、投资或转让。这种价值的差异在金融上就是**货币的时间价值**。理论上来说，货币的时间价值来源于对当前消费推迟的时间补偿。

货币的时间价值只有通过借贷才能实现。货币时间价值源于使用者支付的报酬，也是出借者暂时让渡货币的使用价值所要求得到的补偿。

衡量时间价值，定义货币的在当前的价值为**现值**(Present Value)，未来某时间的价值为**终值**(Final Value)。

<svg width="100%" height="400" viewBox="0 0 800 400" xmlns="http://www.w3.org/2000/svg">
<line x1="50" y1="300" x2="750" y2="300" stroke="#7f8c8d" stroke-width="2" />
<circle cx="100" cy="300" r="15" fill="#e74c3c" />
<text x="100" y="340" text-anchor="middle" font-weight="bold" fill="#e74c3c">现值 (PV)</text>
<text x="100" y="280" text-anchor="middle" font-weight="bold" fill="#e74c3c">¥10,000</text>
<circle cx="700" cy="300" r="15" fill="#2ecc71" />
<text x="700" y="340" text-anchor="middle" font-weight="bold" fill="#2ecc71">终值 (FV)</text>
<text x="700" y="280" text-anchor="middle" font-weight="bold" fill="#2ecc71">¥9000</text>
</svg>
### 利息

为了补偿时间价值，**利息**是借贷关系中资金借入方支付给资金贷出方的报酬。借贷期满的利息总额与贷出本金总额的比率称为**利率**。

**在社会主义市场经济中，利息就是资本按生产要素分配得到的报酬。**

中央财政为了筹集资金，会发行国债。国债与国家安全，财政安全绑定，因此风险极低，一般将国债利率视为无风险利率。对于非国债投资人，其投资行为相当于放弃国债无风险收益而承担一定风险。于是其选择的投资回报必然是：

$$\text{利率}=\text{无风险}+\text{风险溢价}$$

#### 利息的计算方式

金融量定义：将利息记作 $S$，本金记为 $P$，时间记为 $n$，利率记为 $r$

- 单利和复利

单利是只按照本金计算利息的计算方式：
$$
S=P(1+nr)
$$
复利就是利滚利，利息一并计入本金：
$$
S=P(1+r)^n
$$
连续时间利息公式：
$$
S=e^{rn}
$$
其中连续复利的推导：
$$
S=\lim_{n\to\infty}(1+\frac{r}{n})^n=e^{r}
$$

- **收益资本化规律**

记 $B$ 是收益，$P$ 是本金，$r$ 是利率则收益资本化规律公式为
$$
B=r \times P \to P = \frac{B}{r}
$$
看上去像句废话，但是实际上表示各种有收益的事物都可以通过收益与利率对比进行资本定价。

### 利率决定及其影响因素

- 马克思利率决定理论

在马克思看来，资金出借者的利息是资金获得者的利润的一部分，从而**利润必然是利息的一个上界**。

马克思基于剩余价值在资本家之间的传递分割理论，认为利息就是“借贷资本家”从“职能资本家”手中回收的（分割的）一部分产业价值。职能资本家剥削得到的剩余价值一部分用于还贷，一部分重新投入剥削。

所以，利率必然收到实际生产活动的影响。例如**供求关系，借贷双方的竞争**。

- 古典经济学利率决定理论

古典经济学更注重**非货币因素**对利率决定的影响，人们将此时期的利率称为：实际利率理论。

实际利率理论认为，投资流量 (*Invest*) 是资金的**需求**，储蓄 (*Storage*) 流量是资金的**供给**。二者的均衡点就是利率点。

提高投资的需求，$I$ 曲线就将上升；储蓄意愿增加，则 $S$ 曲线就将下降。

<center><svg width="450" height="350" viewBox="0 0 450 350" xmlns="http://www.w3.org/2000/svg" style="background-color: #f5f5f5; border: 1px solid #ccc;">
<defs>
        <marker id="arrow" markerWidth="10" markerHeight="10" refX="9" refY="3" orient="auto" markerUnits="strokeWidth">
            <path d="M0,0 L0,6 L9,3 z" fill="#000" />
        </marker>
    </defs>
    <line x1="60" y1="300" x2="60" y2="40" stroke="#000" stroke-width="1.5" marker-end="url(#arrow)" />
    <line x1="60" y1="300" x2="400" y2="300" stroke="#000" stroke-width="1.5" marker-end="url(#arrow)" />
    <text x="30" y="50" font-family="Times New Roman, serif" font-style="italic" font-size="18" fill="black">r</text>
    <text x="410" y="305" font-family="Times New Roman, serif" font-style="italic" font-size="18" fill="black">I/S</text>
    <line x1="110" y1="80" x2="350" y2="260" stroke="#000" stroke-width="2" />
    <line x1="110" y1="260" x2="350" y2="80" stroke="#000" stroke-width="2" />
    <text x="120" y="70" font-family="Times New Roman, serif" font-size="18" fill="black">
        <tspan font-style="italic">I</tspan>(<tspan font-style="italic">r</tspan>)
    </text>
    <text x="80" y="250" font-family="Times New Roman, serif" font-size="18" fill="black">
        <tspan font-style="italic">S</tspan>(<tspan font-style="italic">r</tspan>)
    </text>
    <line x1="60" y1="170" x2="230" y2="170" stroke="#000" stroke-width="1" stroke-dasharray="5,3" />
    <line x1="230" y1="300" x2="230" y2="170" stroke="#000" stroke-width="1" stroke-dasharray="5,3" />
    <text x="30" y="175" font-family="Times New Roman, serif" font-size="18" fill="black">
        <tspan font-style="italic">r</tspan>*
    </text>
    <text x="210" y="325" font-family="Times New Roman, serif" font-size="18" fill="black">
        <tspan font-style="italic">I = S</tspan>
    </text>
</svg></center>






- 货币供求与利率

凯恩斯提出了流动性偏好理论，此理论更加注重**货币因素**本身的影响。在货币的供给和需求上，凯恩斯认为，货币供给量取决于货币当局的发行量，货币需求量取决于人的流动性偏好。流动性偏好就是对更具有流动性的货币的需求偏好。

凯恩斯认为，货币需求是利率的减函数
$$
\frac{M_d}{P}=L(Y,r), L_r<0
$$
其中 $Y$ 是国民收入，$r$ 是利率，前者产生正相关，后者产生负相关。

- **流动性陷阱**

流动性陷阱：凯恩斯认为货币供给曲线是由货币当局决定的外生变量，在图像上应当垂直于横轴。

当货币供给量增加时，均衡利率走低，反之走高。

市场利率**降低到极低水平**（接近于零）时，人们预期未来利率**只会上升、不会下降**（债券价格只会跌、不会涨）。

随着货币当局买入债券拉低利率，以至于几乎不可以在下降时，人们就会产生货币利率将上升的投机性需求，流动性意愿大幅上升，货币需求的利率弹性趋于无穷大。

<center>
<svg width="500" height="350" viewBox="0 0 500 350" xmlns="http://www.w3.org/2000/svg" style="background-color: #f0f0f0; border: 1px solid #ccc;">
<defs>
<marker id="arrow" markerWidth="10" markerHeight="10" refX="9" refY="3" orient="auto" markerUnits="strokeWidth">
<path d="M0,0 L0,6 L9,3 z" fill="#000" />
</marker>
</defs>
<line x1="50" y1="300" x2="50" y2="30" stroke="#000" stroke-width="1.5" marker-end="url(#arrow)" />
<line x1="50" y1="300" x2="480" y2="300" stroke="#000" stroke-width="1.5" marker-end="url(#arrow)" />
<text x="25" y="40" font-family="Times New Roman, serif" font-weight="bold" font-size="18" fill="black">r</text>
<text x="460" y="325" font-family="Times New Roman, serif" font-weight="bold" font-size="16" fill="black">
<tspan font-style="italic">M/P</tspan>
</text>
<path d="M 140 80 C 150 200, 200 240, 420 240" stroke="#000" stroke-width="1.5" fill="none" />
<text x="85" y="70" font-family="Times New Roman, serif" font-style="italic" font-weight="bold" font-size="16" fill="black">
L(Y, r)
</text>
<line x1="180" y1="300" x2="180" y2="60" stroke="#000" stroke-width="1.5" />
<line x1="250" y1="300" x2="250" y2="60" stroke="#000" stroke-width="1.5" />
</svg>
</center>

**结果：** 所有人把手里的债券全卖了，换成现金死死攥在手里。不管央行再印多少钱，大家就把这新增的钱也攥在手里，不让它流回债券市场。

当经济掉入流动性陷阱时（如 90 年代的日本，或 2008 年后的部分时期），必须依靠 **财政政策**（政府直接花钱搞基建、减税）来拉动总需求，因为货币政策已经“推绳子”推不动了。

- 可贷资金利率理论

该理论承认实际利率理论和流动性偏好理论的现实意义，但是认为完全忽视货币因素与实际因素的作用是错误的。

- $IS-LM$ 模型

又称希克斯-汉森模型。该模型将市场划分为**商品市场**和货币市场，认为国民经济均衡是商品市场和货币市场同时出现均衡时才能出现。

$IS-LM$ 模型有两个重要曲线：$IS$ 曲线和 $LM$ 曲线。

$IS$ 曲线意味着投资-储蓄曲线，代表着**商品市场均衡**时的利率 $r$ 与收入 $Y$ 组合轨迹；$LM$ 曲线意味着流动性货币供给曲线，代表着**货币市场均衡**时的利率 $r$ 与收入 $Y$ 组合轨迹。

$IS$ 曲线中其中任何一点所对应的 $(r, Y)$，都满足 $I=S$ ，即 
$$
Y=C+I+G
$$
其中 $Y$ 代表国民收入，$I$ 代表投资，$G$ 代表政府购买，$C$ 代表消费。

$LM$ 曲线中其中任何一点所对应的 $(r, Y)$，都满足 $L={M}$ 

二者的交点，就是两个市场同时达到均衡时的利率和收入水平。

### 利率风险结构

利率风险包含违约风险，流动性风险，通胀风险。

- 违约风险：信用风险，指不能按期偿还本金和支付利息的风险。违约风险包含：**违约概率**和**损失挽回比**。所以，违约风险高的债务利率也相对较高。
- 流动性风险：资产流动性差，变现能力弱或慢导致的损失。一般来说流动性风险也会增加利率。
- 通胀风险：物价上涨导致货币购买力下降，货币面临着购买力风险，因此利率必须考虑预期通胀率。

**费雪效应**：预期通胀率上升，则名义利率会上升。
$$
R=r+\pi^e
$$


#### 期限结构

同质的金融工具随着不同的期限具有不同的金融价值，不难发现，利率的变化在图上有以下特点：

- 不同期限，利率随时间变化
- 短期利率低，收益率倾向于向上；短期利率高，收益率倾向于向下
- 收益率曲线通常向上倾斜。

### 利率作用

利率是社会主义市场经济的核心要素，在配置金融资源中发挥价格引导作用。利率作为联通宏观与微观经济的金融机制，既是影响微观主体决策的重要因素，也是宏观政策调控的重要手段。

发挥作用前提：

- 独立决策的市场主体
- 市场化利率决定机制
- 合理的利率弹性
