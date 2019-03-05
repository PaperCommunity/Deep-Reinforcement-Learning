# 多智能体强化学习
---
* **MADDPG《Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments》**
  - **创建时间**: 2019.01.24
  - **创建者**: [initial-h](https://github.com/initial-h)
  - **文章概述**: 由于多智能体的环境状态由多个agent的行为共同决定，本身具有不稳定性(non-stationarity)，Q-learning算法很难训练，policy gradient算法的方差会随着智能体数目的增加变得更大。作者提出了一种actor-critic方法的变体MADDPG，对每个agent的强化学习都考虑其他agent的动作策略，进行中心化训练和非中心化执行，在合作、竞争、混合场景下都取得了显著效果。
  * **相关链接**: [issue讨论区](https://github.com/PaperCommunity/Deep-Reinforcement-Learning/issues/2);&ensp;[MADDPG链接](https://arxiv.org/abs/1706.02275);&ensp;[DDPG链接](https://arxiv.org/abs/1509.02971);&ensp;[官方博客](https://blog.openai.com/learning-to-cooperate-compete-and-communicate/);&ensp;[论文解读](https://blog.csdn.net/qiusuoxiaozi/article/details/79066612);&ensp;[论文解读](https://www.jianshu.com/p/99a79cd08c72);&ensp;[论文解读](https://www.cnblogs.com/initial-h/p/9429632.html)
  
---
* **《Learning to Communicate with Deep Multi-Agent Reinforcement Learning》**
  - **创建时间**: 2019.02.25
  - **创建者**: [DreamChaser128](https://github.com/DreamChaser128)
  - **文章概述**: 考虑多智能体在环境里感知和行动，最大限度地发挥它们的共同效用，以实现相应的目标。在环境中，agent必须学会通信策略，以完成需要共享信息的任务。由于通过采用深度神经网络，使我们能够在复杂环境中通过端到端方式来学习，这些对于具有部分可观察性的多智能体计算机视觉和通信问题有一定启发。。在此领域，作者就提出了的两种通信学习方法：RIAL和DIAL，并对相应算法做了实验，结果可观。
  * **相关链接**: [issue讨论区](https://github.com/PaperCommunity/Deep-Reinforcement-Learning/issues/5);&ensp;[论文链接](https://arxiv.org/abs/1605.06676);&ensp;[ACCNet](https://arxiv.org/abs/1706.03235);&ensp;[论文解读](https://blog.csdn.net/qq_36616268/article/details/83277025);&ensp;

---
* **《EMERGENT COORDINATION THROUGH COMPETITION》**
  - **创建时间**: 2019.03.05
  - **创建者**: [initial-h](https://github.com/initial-h)
  - **文章概述**: 这篇文章deepmind发表在ICLR2019，文章构建了一个足球比赛的多智能体验证环境，并在2V2场景下进行训练，发现了智能体从随机动作到学会踢球再到配合踢球的过程。文中主要用到了PBT（population-based training）算法做shaping rewards, Retrace-SVG0训练网络参数，最后还用了几种不同的评价标准（Elo, Nash-Averaging Evaluators）对训练好的智能体进行强弱评估，并发现了类似‘石头剪刀布‘一样相生相克的现象。
  * **相关链接**: [issue讨论区](https://github.com/PaperCommunity/Deep-Reinforcement-Learning/issues/7);&ensp;[论文链接](https://arxiv.org/pdf/1902.07151.pdf);&ensp;[环境代码](https://github.com/deepmind/dm_control/tree/master/dm_control/locomotion/soccer);
  
  ---
  
  
  
  
  
  
