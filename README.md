
### **世界杯赔率计算方法**

#### **项目背景**
在卡塔尔世界杯期间，观察到众多人参与赌球活动，引发了对赌场如何设置不同玩法赔率的好奇心。特别是，如何通过数学模型来预测或验证这些赔率的形成机制。

#### **泊松分布的应用**
本项目基于泊松分布模型，这是一种广泛用于估算在固定时间或空间内发生特定次数事件的概率分布。在足球比赛中，泊松分布特别适用于预测比赛的进球数，因为进球事件在时间上的分布具有一定的随机性。

通过假设A队和B队的平均进球数（λ值），泊松分布可以计算出任何特定进球数（0球、1球、2球等）发生的概率。这些概率可以进一步用来计算比赛的各种可能结果（如胜、平、负）、让球、总进球数等的概率。

#### **赔率计算与抽水分析**
赔率反映了某个事件发生的概率，而通过上述方法计算得到的概率可以直接转化为对应的赔率。此外，通过分析赔率，我们还可以揭示赌场在每项赌注中抽取的佣金比例（抽水），这对于理解赌场如何从赌博活动中盈利提供了洞见。

#### **下注策略的制定**
项目的另一个目的是为参与者提供一个量化的方法，来判断是否应该下注。通过猜测或计算比赛双方的平均进球数，参与者可以使用这一模型来预测各种赔率，并结合实际赔率来决定下注是否具有价值。

#### **结论**
尽管看似复杂，赔率背后实际上隐藏着简单的数学原理。通过泊松分布和平均进球数，我们可以解码足球赌博中的赔率设置。

这种方法为量化的计算赔率是否应该下注提供了一个基础，只要通过其他数据量化平均进球数的范围就好了。

我还意外的发现了，赌场认为上半场的平均进球数和下半场的有明显的区别，下半场的稍多


数据来源：
https://www.sporttery.cn/jc/jsq/zqbf/

