增强学习
---
# 基本概念
增强学习关注的是智能体如何在环境中采取一系列行为，从而获得最大的累积回报。

通过增强学习，一个智能体应该知道在什么状态下应该采取什么行为。RL是从环境状态到动作的映射的学习，我们把这个映射称为**策略**

增强学习和监督学习的区别主要有以下两点：

1.  增强学习是试错学习(Trail-and-error)，由于没有直接的指导信息，智能体要以不断与环境进行交互，通过试错的方式来获得最佳策略。

2.  延迟回报，增强学习的指导信息很少，而且往往是在事后（最后一个状态）才给出的，这就导致了一个问题，就是获得正回报或者负回报以后，如何将回报分配给前面的状态

在经典的增强学习中，玩家作为Agent，要和环境Environment做一系列的交互。在每一个时刻，环境将给出一个当前的状态，玩家将根据状态做出决策，这个决策会影响环境，使得环境发生一定的改变，改变后的环境会反馈给玩家一个“奖励”Reward，这个奖励可以是正向的，也可以是负向的，它用于反馈用户当前的表现。环境同时还会反馈下一时刻的状态给玩家，这样玩家就可以做新一轮的决策了。这个过程由图2所示。

![](https://pic4.zhimg.com/50/v2-d00561a78b2bdb348ea7def7634a44af_hd.jpg)

# 策略迭代法

# 价值迭代法

# 参考
无痛的机器学习第一季目录  
<https://zhuanlan.zhihu.com/p/22464594>  
无痛的机器学习第二季目录  
<https://zhuanlan.zhihu.com/p/26884917>  
增强学习（一） ----- 基本概念  
<http://www.cnblogs.com/jinxulin/p/3511298.html>  
增强学习入门1——基本概念  
<https://zhuanlan.zhihu.com/p/28062261>  
深度增强学习：走向通用人工智能之路  
<https://www.zybuluo.com/tinadu/note/629229>  