## 交叉领域
---

* **《Population Based Training of Neural Networks》**

  * **创建时间**: 2019.03.14
  * **创建者**: [initial-h](https://github.com/initial-h)
  * **文章概述**: 文章提出了一种简单的异步优化方法PBT(population based training)，主要用来自适应调节超参数。通常的深度学习，超参数都是凭经验预先设计好的，会花费大量精力且不一定有好的效果，特别是在深度强化学习这种非静态(non-stationary)的环境中，要想得到SOTA效果，超参数还应随着环境变化而自适应调整，比如探索率等等。这种基于种群(population)的进化方式，淘汰差的模型，利用(exploit)好的模型并添加随机扰动(explore)进一步优化，最终得到最优的模型。作者分别从强化学习,监督学习,GAN三个方面做实验，论证了这个简单但有效的算法。
  </br>&emsp;&emsp;作者认为本文主要做了三点改进:(a)训练过程超参数的自动选择。(b)模型的在线淘汰和选择，让计算资源最大化用在更有希望的模型上(promising models)。(c)超参数在线自适应调节，以适应非静态场景的超参数规划调节(hyperparameter schedules)。

  * **相关链接**: [issue讨论区](https://github.com/PaperCommunity/Deep-Reinforcement-Learning/issues/9);&ensp;[论文下载](https://arxiv.org/abs/1711.09846);&ensp;[官方博客](https://deepmind.com/blog/population-based-training-neural-networks/);&ensp;[论文解读](https://www.cnblogs.com/initial-h/p/10519150.html);
  
---
