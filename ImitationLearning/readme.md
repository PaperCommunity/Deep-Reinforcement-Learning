## 模仿学习
---

* **《Playing hard exploration games by watching YouTube》**

  * **创建时间**: 2019.01.24
  * **创建者**: [initial-h](https://github.com/initial-h)
  * **文章概述**: 当环境奖励特别稀疏的时候，强化学习方法通常很难训练(traditionally struggle)。一个有效的方式是通过人类示范者(human demonstrator)提供模仿轨迹(imitate trajectories)来指导强化学习的探索方向，通常的做法是观看人类高手玩游戏的视频。这里的问题是演示的素材(demonstrations)，即人类高手的视频，通常不能直接使用。因为不同的视频来源通常有细微的差异(domain gap)，只有在完全相同的环境中(尺寸、分辨率、横纵比、颜色等等)获得状态信息`S`，同时获得对应需要模仿的动作信息`a`，甚至环境回报`r`，然后构成状态动作对`(S,a)`才能进行模仿学习。比如，人类在观察一段游戏视频后，不管游戏是否存在色差、显示大小是否一样，都可以大致知道自己该如何操作(上下左右等)，但是把这段视频提供给智能体(agent)，微小的色差等显示变化都会让智能体误解成不同的状态，同时智能体也无法直接从视频中悟出该采取什么动作。归结起来就是两点：1. 游戏镜头不匹配(unaligned gameplay footage); 2. 没有动作标签(unlabeled)。文章提出了一种分两步解决该问题的方法。1.通过自监督(self-supervised)的学习方式构造视频到状态抽象特征的映射，消除不同视频来源的细微差异造成的影响。2.用输出的抽象特征作为状态`S`，结合模仿学习和强化学习探索最优动作。该方法在Montezuma's Revenge、Pitfall、Private Eye三个游戏中取得了超越人类水平的效果。
  * **相关链接**: [issue讨论区](https://github.com/PaperCommunity/Deep-Reinforcement-Learning/issues/1);&ensp;[论文下载](https://arxiv.org/abs/1805.11592v1);&ensp;[官方博客](https://www.youtube.com/playlist?list=PLZuOGGtntKlaOoq_8wk5aKgE_u_Qcpqhu);&ensp;[论文解读](https://www.cnblogs.com/initial-h/p/9381226.html);
  
---
