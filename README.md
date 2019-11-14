# Reflection_Summary

我觉得，一个合格的算法工程师，需要掌握：
- [扎实的数据结构能力](https://github.com/sladesha/LeetCode)
- [大量的机器学习实操经验](https://github.com/sladesha/machine_learning)
- [大量的深度学习项目经验](https://github.com/sladesha/deep_learning)
- 有一个相对精通的语言，比如python    
    - [靠谱底层机制的理解](https://github.com/sladesha/sladeRode2)
    - [动手做过一些demo](https://github.com/sladesha/PyTls)
    - [有一些成功的经验](https://github.com/sladesha/Frcwp)
    - [贡献过一些开源项目](https://github.com/brennerm/PyTricks)
- [靠谱的java编码能力](https://github.com/sladesha/sladeRode)
- [了解java工程](https://github.com/sladesha/sladeRode4)
- [了解C++](https://github.com/sladesha/sladeRode3)
- [总结表述沉淀能力](http://www.shataowei.com)

1. 以下内容为我作为面试管的提问，以及陪伴实习生同学@[tcandzq](https://github.com/tcandzq)参加2020届校招面试各类算法问题及个人理解的汇总
2. 各种解答均为我的理解和看法，一定有存疑和不完善的地方，欢迎大家补充和质疑打脸
3. 另外，恭喜[tcandzq](https://github.com/tcandzq)收割到腾讯UGC，阿里算法中台，头条广告推荐offer，:clap:

***
# 基础概念
trick:大概率会穿插在机器学习或者深度学习算法中提问，要站到你当时在聊的那个算法外再说，否则你很容易把自己绕进去

- 方差和偏差
    - [解释方差](基础概念/方差与偏差/方差与偏差.md#L1)
    - [解释偏差](基础概念/方差与偏差/方差与偏差.md#L4)
    - [模型训练为什么要引入偏差和方差？请理论论证](基础概念/方差与偏差/方差与偏差.md#L7)
    - [什么情况下引发高方差](基础概念/方差与偏差/方差与偏差.md#L26)
    - [如何解决高方差问题](基础概念/方差与偏差/方差与偏差.md#L31)
    - [以上方法是否一定有效](基础概念/方差与偏差/方差与偏差.md#L36)
    - [如何解决高偏差问题](基础概念/方差与偏差/方差与偏差.md#L44)
    - [以上方法是否一定有效](基础概念/方差与偏差/方差与偏差.md#L51)
    - [遇到过的机器学习中的偏差与方差问题](基础概念/方差与偏差/方差与偏差.md#L56)
    - [就理论角度论证Bagging、Boosting的方差偏差问题](基础概念/方差与偏差/方差与偏差.md#L60)
    - [遇到过的深度学习中的偏差与方差问题](基础概念/方差与偏差/方差与偏差.md#L88)
    - [方差、偏差与模型的复杂度之间的关系](基础概念/方差与偏差/方差与偏差.md#L96)
- 生成与判别模型
    - [什么叫生成模型](基础概念/生成与判别模型/生成与判别模型.md#L96)
    - [什么叫判别模型](基础概念/生成与判别模型/生成与判别模型.md#L96)
    - [什么时候会选择生成/判别模型](基础概念/生成与判别模型/生成与判别模型.md#L96)
    - [CRF/朴素贝叶斯/EM/最大熵模型/马尔科夫随机场/混合高斯模型](基础概念/生成与判别模型/生成与判别模型.md#L96)
    - [我的理解](基础概念/生成与判别模型/生成与判别模型.md#L96)
- 先验概率和后验概率
    - [写出全概率公式&贝叶斯公式](基础概念/先验概率和后验概率/先验概率和后验概率.md#L96)
    - [说说你怎么理解为什么有全概率公式&贝叶斯公式](基础概念/先验概率和后验概率/先验概率和后验概率.md#L96)
    - [什么是先验概率](基础概念/先验概率和后验概率/先验概率和后验概率.md#L96)
    - [什么是后验概率](基础概念/先验概率和后验概率/先验概率和后验概率.md#L96)
    - [经典概率题](基础概念/先验概率和后验概率/先验概率和后验概率.md#L96)
- 正则化

# 数学
trick1:数学知识一般比较难，回答过程中，请理解面试官的意图。如果是理论派就背概念，如果是实战派就以通俗易懂的例子去表述

trick2:先有再优化，数分、高等数学、拓扑、复变、实变、泛函等等，有无数的概念，你不可能全部都会，但是0.1和0之间差的不是0.1，是无穷

trick3:至少**精通**一个领域，保证你在这里可以有两句说的，尽量让数学话题围绕你熟悉的话题展开

- 数据质量
    - [期望](数学/数据质量/期望、方差、标准差和协方差.md#L1)
    - [方差](数学/数据质量/期望、方差、标准差和协方差.md#L4)
    - [标准差](数学/数据质量/期望、方差、标准差和协方差.md#L9)
    - [协方差](数学/数据质量/期望、方差、标准差和协方差.md#L11)
- 最大公约数问题
    - [辗转相除法](数学/最大公约数问题/gcd.md#L1)
    - [其他方法](数学/最大公约数问题/gcd.md#L1)
- 泰勒展开
- 牛顿法
- 拟牛顿法
- 分布    
- 平面曲线的切线和法线
    - [平面曲线的切线](数学/平面曲线的切线和法线/平面曲线的切线和法线.md#L1)
    - [平面曲线的法线](数学/平面曲线的切线和法线/平面曲线的切线和法线.md#L1)
- 导数
    - [四则运算](数学/导数/导数.md#L1)
    - [常见导数](数学/导数/导数.md#L1)
    - [复合函数的运算法则](数学/导数/导数.md#L1)
    - [莱布尼兹公式](数学/导数/导数.md#L1)
- 微分中值定理
    - [费马定理](数学/微分中值定理/微分中值定理.md#L1)
    - [拉格朗日中值定理](数学/微分中值定理/微分中值定理.md#L1)
    - [柯西中值定理](数学/微分中值定理/微分中值定理.md#L1)
- 泰勒公式
    - [泰勒公式](数学/泰勒公式/泰勒公式.md#L1)

# 数据预处理
trick1:回答过程中请时刻注意面试官表情，部分面试官会认为业务理解最重要，如果他表示出一定的不耐烦的态度请停止背书

trick2:不要背书，数据预处理答题需要用心，尤其是社招，这完全决定了你是否是一个熟练工，是否能入职帮忙干活

trick3:针对单点细问的时候，多结合实际项目中的例子，概念+正例子+反例子+总结，是答题规范

- 数据平衡
    - [为什么要对数据进行采样](数据预处理/数据平衡/采样.md#L1)
    - [是否一定需要对原始数据进行采样平衡](数据预处理/数据平衡/采样.md#L6)
    - [有哪些常见的采样方法](数据预处理/数据平衡/采样.md#L11)
    - [能否避免采样](数据预处理/数据平衡/采样.md#L36)
    - [你平时怎么用采样方法](数据预处理/数据平衡/采样.md#L39)
- 异常点处理
    - [统计方法](数据预处理/异常点处理/异常点识别.md#L1)
    - [矩阵分解方法](数据预处理/异常点处理/异常点识别.md#L21)
    - [特征值和特征向量的本质是什么](数据预处理/异常点处理/异常点识别.md#L33)
    - [矩阵乘法的实际意义](数据预处理/异常点处理/异常点识别.md#L37)
    - [密度的离群点检测](数据预处理/异常点处理/异常点识别.md#L41)
    - [聚类的离群点检测](数据预处理/异常点处理/异常点识别.md#L52)
    - [如何处理异常点](数据预处理/异常点处理/异常点识别.md#L56)
- 缺失值处理
    - [是不是一定需要对缺失值处理](数据预处理/缺失值处理/缺失值处理.md#L1)
    - [直接填充方法有哪些](数据预处理/缺失值处理/缺失值处理.md#L4)
    - [模型插值方法有哪些？及方法的问题](数据预处理/缺失值处理/缺失值处理.md#L10)
    - [如何直接离散化](数据预处理/缺失值处理/缺失值处理.md#L14)
    - [hold位填充方法有哪些](数据预处理/缺失值处理/缺失值处理.md#L17)
    - [怎么理解分布补全](数据预处理/缺失值处理/缺失值处理.md#L22)
    - [random方法使用前提](数据预处理/缺失值处理/缺失值处理.md#L25)
    - [总结](数据预处理/缺失值处理/缺失值处理.md#L28)
- 特征选择
    - [为什么要做特征选择](数据预处理/特征选择/特征选择.md#L1)
    - [从哪些方面可以做特征选择](数据预处理/特征选择/特征选择.md#L6)
    - [既然说了两个方向，分别介绍一些吧](数据预处理/特征选择/特征选择.md#L10)
- 特征提取
    - [为什么需要对数据进行变换](数据预处理/特征提取/数据变换.md#L1)
    - [归一化和标准化之间的关系](数据预处理/特征提取/数据变换.md#L6)
    - [连续特征常用方法](数据预处理/特征提取/数据变换.md#L20)
    - [离散特征常用方法](数据预处理/特征提取/数据变换.md#L71)
    - [文本特征](数据预处理/特征提取/数据变换.md#L88)
    - [画一个最简单的最快速能实现的框架](数据预处理/特征提取/数据变换.md#L164)

# 机器学习
- 逻辑回归
    - [LR推导，基础5连问](机器学习/逻辑回归/lr.md#L164)
    - [LR明明是分类模型为什么叫回归](机器学习/逻辑回归/lr.md#L164)
    - [为什么LR可以用来做CTR预估](机器学习/逻辑回归/lr.md#L164)
    - [满足什么样条件的数据用LR最好](机器学习/逻辑回归/lr.md#L164)
    - [LR为什么使用sigmoid函数作为激活函数？其他函数不行吗](机器学习/逻辑回归/lr.md#L164)
    - [Sigmoid函数到底起了什么作用](机器学习/逻辑回归/lr.md#L164)
    - [LR为什么要使用极大似然函数作为损失函数？那为什么不选平方损失函数的呢](机器学习/逻辑回归/lr.md#L164)
    - [LR中若标签为+1和-1，损失函数如何推导？](机器学习/逻辑回归/lr.md#L164)
    - [如果有很多的特征高度相关或者说有一个特征重复了100遍，会造成怎样的影响](机器学习/逻辑回归/lr.md#L164)
    - [为什么要避免共线性](机器学习/逻辑回归/lr.md#L164)
    - [LR可以用核么？可以怎么用](机器学习/逻辑回归/lr.md#L164)
    - [LR中的L1/L2正则项是啥](机器学习/逻辑回归/lr.md#L164)
    - [lr加l1还是l2好](机器学习/逻辑回归/lr.md#L164)
    - [正则化是依据什么理论实现模型优化](机器学习/逻辑回归/lr.md#L164)
    - [LR可以用来处理非线性问题么](机器学习/逻辑回归/lr.md#L164)
    - [为什么LR需要归一化或者取对数](机器学习/逻辑回归/lr.md#L164)
    - [为什么LR把特征离散化后效果更好？离散化的好处有哪些](机器学习/逻辑回归/lr.md#L164)
    - [逻辑回归估计参数时的目标函数逻辑回归的值表示概率吗](机器学习/逻辑回归/lr.md#L164)
    - [LR对比万物](机器学习/逻辑回归/lr.md#L164)
    - [LR梯度下降方法](机器学习/逻辑回归/lr.md#L164)
    - [LR的优缺点](机器学习/逻辑回归/lr.md#L164)
    - [我的总结](机器学习/逻辑回归/lr.md#L164)
- 决策树
- GBDT
- FM/FFM
- SVM

# 深度学习
- dropout
- batchnormalization
- bp过程
- embedding
- softmax
- 梯度消失/爆炸

# 自然语言处理
- 朴素贝叶斯
- N-Grams
- LDA
- Attention
- LSTM
- GRU
- Bert
- Transfer

# 推荐
- DIN
- DeepFM
- YoutubeNet
- Wide&Deep
- MLR
- Neural Network全家桶

# 风控
- 孤立森林
- 评分卡

# 评价指标
- 二分类
- 多分类
- 回归指标
- 聚类指标
- 排序指标