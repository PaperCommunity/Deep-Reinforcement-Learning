# 多智能体强化学习
---
* **MADDPG《Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments》**
  - **创建时间**: 2019.01.24
  - **创建者**: [initial-h](https://github.com/initial-h)
  - **文章概述**: 由于多智能体的环境状态由多个agent的行为共同决定，本身具有不稳定性(non-stationarity)，Q-learning算法很难训练，policy gradient算法的方差会随着智能体数目的增加变得更大。作者提出了一种actor-critic方法的变体MADDPG，对每个agent的强化学习都考虑其他agent的动作策略，进行中心化训练和非中心化执行，在合作、竞争、混合场景下都取得了显著效果。
  * **相关链接**:[issue讨论区](https://github.com/PaperCommunity/Deep-Reinforcement-Learning/issues/2);[MADDPG链接](https://arxiv.org/abs/1706.02275);[DDPG链接](https://arxiv.org/abs/1509.02971)
- **博客链接**: [OpenAI bog](https://blog.openai.com/learning-to-cooperate-compete-and-communicate/)
- **论文解读链接**: [CSDN](https://blog.csdn.net/qiusuoxiaozi/article/details/79066612);[简书](https://www.jianshu.com/p/99a79cd08c72);[博客园](https://www.cnblogs.com/initial-h/p/9429632.html)

  * **相关链接**: [issue讨论区](https://github.com/PaperCommunity/Deep-Reinforcement-Learning/issues/2);&ensp;[MADDPG链接](https://arxiv.org/abs/1706.02275);&ensp;[DDPG链接](https://arxiv.org/abs/1509.02971);&ensp;[官方博客](https://blog.openai.com/learning-to-cooperate-compete-and-communicate/);&ensp;[论文解读](https://blog.csdn.net/qiusuoxiaozi/article/details/79066612);&ensp;[论文解读](https://www.jianshu.com/p/99a79cd08c72);&ensp;[论文解读](https://www.cnblogs.com/initial-h/p/9429632.html)
  
---
