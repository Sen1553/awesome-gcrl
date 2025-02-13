# GCRL algorithms

## 1. Survey

1. Liu M, Zhu M, Zhang W. **Goal-conditioned reinforcement learning: Problems and solutions**[C]. International Joint Conference on Artificial Intelligence. **IJCAI, 2022**. [[Paper]](https://arxiv.org/abs/2201.08299) [[Code]](https://github.com/apexrl/GCRL-Collection)

## 2. Curriculum Learning

1. Gong X, Feng D, Xu K, et al. **Goal-Conditioned On-Policy Reinforcement Learning**[C]//The Thirty-eighth Annual Conference on Neural Information Processing Systems. **NeurIPS, 2024**. [[Paper]](https://openreview.net/forum?id=KP7EUORJYI) [[Code]](https://github.com/GongXudong/GCPO)

2. Zhang T, Eysenbach B, Salakhutdinov R, et al. **C-Planning: An Automatic Curriculum for Learning Goal-Reaching Tasks**[C]//International Conference on Learning Representations. **ICLR, 2022**. [[Paper]](https://openreview.net/forum?id=h6OdyxD1bxs)

3. Pitis S, Chan H, Zhao S, et al. **Maximum entropy gain exploration for long horizon multi-goal reinforcement learning**[C]//International Conference on Machine Learning. PMLR, 2020: 7750-7761. **ICML, 2020**. [[Paper]](http://proceedings.mlr.press/v119/pitis20a/pitis20a.pdf)

4. Florensa C, Held D, Geng X, et al. **Automatic goal generation for reinforcement learning agents**[C]//International conference on machine learning. PMLR, 2018: 1515-1528. **ICML, 2018**. [[Paper]](http://proceedings.mlr.press/v80/florensa18a/florensa18a.pdf)

    `TL;DR: Propose to employ a generator to produce tasks that are always at the appropriate level of difficulty for the agent, thus automatically producing a curriculum.`

5. Ren Z, Dong K, Zhou Y, et al. **Exploration via hindsight goal generation**[C]. Advances in Neural Information Processing Systems, 2019, 32. **NeurIPS, 2019**. [[Paper]](https://proceedings.neurips.cc/paper/2019/file/57db7d68d5335b52d5153a4e01adaa6b-Paper.pdf)

    `TL;DR: Propose an algorithm to generate valuable hindsight goals which are easy for an agent to achieve in the short term and are also potential for guiding the agent to reach the actual goal in the long term.`

6. Zhao R, Sun X, Tresp V. **Maximum entropy-regularized multi-goal reinforcement learning**[C]//International Conference on Machine Learning. PMLR, 2019: 7553-7562. **ICML, 2019**. [[Paper]](http://proceedings.mlr.press/v97/zhao19d/zhao19d.pdf)

    `TL;DR: Propose a novel multi-goal RL objective based on weighted entropy. This objective encourages the agent to maximize the expected return, as well as to achieve more diverse goals`

7. Castanet N, Lamprier S, Sigaud O. **Stein Variational Goal Generation For Reinforcement Learning in Hard Exploration Problems**[C]//International Conference on Machine Learning. **ICML, 2023**. [[Paper]](https://openreview.net/forum?id=c0NG640B-LO)

    `TL;DR: propose Stein Variational Goal Generation (SVGG), which samples goals of intermediate difficulty for the agent, by leveraging a learned predictive model of its goal reaching capabilities.`

8. Li Q, Zhai Y, Ma Y, et al. **Understanding the complexity gains of single-task rl with a curriculum**[C]//International Conference on Machine Learning. PMLR, 2023: 20412-20451. **ICML, 2023**. [[Paper]](https://proceedings.mlr.press/v202/li23as/li23as.pdf)

    `TL;DR: provide a theoretical framework that reformulates a single-task RL problem as a multi-task RL problem defined by a curriculum.`

9. Nair A V, Pong V, Dalal M, et al. **Visual reinforcement learning with imagined goals**[C]. Advances in neural information processing systems, 2018, 31. **NeurIPS, 2018**. [[Paper]](https://proceedings.neurips.cc/paper/2018/file/7ec69dd44416c46745f6edd947b470cd-Paper.pdf)

10. Niu Y, Jin S, Zhang Z, et al. **Goats: Goal sampling adaptation for scooping with curriculum reinforcement learning**[C]//2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). IEEE, 2023: 1023-1030. **IROS, 2023**. [[Paper]](https://ieeexplore.ieee.org/abstract/document/10342221)

## 3. Sub-goal Generation

1. Nasiriany S, Pong V, Lin S, et al. **Planning with goal-conditioned policies**[C]. Advances in neural information processing systems, 2019, 32. **NeurIPS, 2019**. [[Paper]](https://proceedings.neurips.cc/paper/2019/file/c8cc6e90ccbff44c9cee23611711cdc4-Paper.pdf)

2. Chane-Sane E, Schmid C, Laptev I. **Goal-conditioned reinforcement learning with imagined subgoals**[C]//International Conference on Machine Learning. PMLR, 2021: 1430-1440. **ICML, 2024**. [[Paper]](http://proceedings.mlr.press/v139/chane-sane21a/chane-sane21a.pdf)

3. Chane-Sane E, Schmid C, Laptev I. **Goal-conditioned reinforcement learning with imagined subgoals**[C]//International conference on machine learning. PMLR, 2021: 1430-1440. **ICML, 2012**. [[Paper]](http://proceedings.mlr.press/v139/chane-sane21a/chane-sane21a.pdf)

4. Wang F, Duan A, Zhou P, et al. **Implicit Subgoal Planning with Variational Autoencoders for Long-Horizon Sparse Reward Robotic Tasks**[J]. arxiv preprint arxiv:2312.15578, 2023. [[Paper]](https://arxiv.org/pdf/2312.15578)

## 4. Representation Learning

1. Duan Y, Cui G, Zhu H. **Exploring the Edges of Latent State Clusters for Goal-Conditioned Reinforcement Learning**[C]//The Thirty-eighth Annual Conference on Neural Information Processing Systems. **NeurIPS, 2024**. [[Paper]](https://openreview.net/forum?id=9hKN99RNdR) [[Code]](https://github.com/RU-Automated-Reasoning-Group/CE2)

## 5. Offline

1. Park S, Ghosh D, Eysenbach B, et al. **Hiql: Offline goal-conditioned rl with latent states as actions**[C]. Advances in Neural Information Processing Systems. **NeurIPS, 2024**. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/file/6d7c4a0727e089ed6cdd3151cbe8d8ba-Paper-Conference.pdf) [[Code]](https://github.com/seohongpark/HIQL)

2. Yang R, Yong L, Ma X, et al. **What is essential for unseen goal generalization of offline goal-conditioned rl?**[C]//International Conference on Machine Learning. PMLR, 2023: 39543-39571. **ICML, 2023**. [[Paper]](https://proceedings.mlr.press/v202/yang23q/yang23q.pdf) [[Code]](https://github.com/YangRui2015/GOAT)

## 6. Supervised

1. Ghosh D, Gupta A, Reddy A, et al. **Learning to Reach Goals via Iterated Supervised Learning**[C]//International Conference on Learning Representations. **ICLR, 2021**. [[Paper]](https://openreview.net/forum?id=rALA0Xo6yNJ) [[Code]](https://github.com/dibyaghosh/gcsl)

2. Yang R, Lu Y, Li W, et al. **Rethinking Goal-Conditioned Supervised Learning and Its Connection to Offline RL**[C]//International Conference on Learning Representations. **ICLR, 2022**. [[Paper]](https://openreview.net/forum?id=KJztlfGPdwW) [[Code]](https://github.com/YangRui2015/AWGCSL)

3. Ding Y, Florensa C, Abbeel P, et al. **Goal-conditioned imitation learning**[C]. Advances in neural information processing systems, 2019, 32. **NeurIPS, 2019**. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2019/file/c8d3a760ebab631565f8509d84b3b3f1-Paper.pdf) [[Code]](https://sites.google.com/view/goalconditioned-il/)

    `TL;DR: GAIL + HER`

## 7. Unsupervised RL / Pre-train

1. Yuan H, Mu Z, Xie F, et al. **Pre-training goal-based models for sample-efficient reinforcement learning**[C]//The Twelfth International Conference on Learning Representations. 2024. **ICLR, 2024**. [[Paper]](https://openreview.net/forum?id=o2IEmeLL9r)

2. Jacq A D, Orsini M, Dulac-Arnold G, et al. **On the importance of data collection for training general goal-reaching policies**[C]//Sixteenth European Workshop on Reinforcement Learning. **NeurIPS 2023 workshop ALOE**. [[Paper]](https://openreview.net/forum?id=vaJCmIf54d)

3. Lynch C, Khansari M, Xiao T, et al. **Learning latent plans from play**[C]//Conference on robot learning. PMLR, 2020: 1113-1132. **CORL, 2020**. [[Paper]](http://proceedings.mlr.press/v100/lynch20a/lynch20a.pdf)

    `TL;DR: Propose self-supervising control on top of human teleoperated play data as a way to scale up skill learning, which tries to learn to organize play behaviors in a latent space, then reuse them at test time to achieve specific goals.`

## 8. Model-Based

1. Hu E S, Chang R, Rybkin O, et al. **Planning Goals for Exploration**[C]//The Eleventh International Conference on Learning Representations. **ICLR, 2023**. [[Paper]](https://openreview.net/forum?id=6qeBuZSo7Pr)

## 9. Exploration

1. Forestier S, Portelas R, Mollard Y, et al. **Intrinsically motivated goal exploration processes with automatic curriculum learning**[J]. Journal of Machine Learning Research, 2022, 23(152): 1-41. **JMLR, 2022**. [[Paper]](https://www.jmlr.org/papers/volume23/21-0808/21-0808.pdf)

2. Hu E S, Chang R, Rybkin O, et al. **Planning Goals for Exploration**[C]//The Eleventh International Conference on Learning Representations. **ICLR, 2023**. [[Paper]](https://openreview.net/forum?id=6qeBuZSo7Pr)

3. Bagaria A, Schaul T. **Scaling goal-based exploration via pruning proto-goals**[C]//Proceedings of the Thirty-Second International Joint Conference on Artificial Intelligence. 2023: 3451-3460. **IJCAI, 2023**. [[Paper]](https://dl.acm.org/doi/abs/10.24963/ijcai.2023/384)

    `TL;DR: Propose a method that enables the human designer to specify a vast but meaningful proto-goal space, and an autonomous discovery process to refine this to a narrower space of controllable, reachable, novel, and relevant goals.`

4. Xu J, Li S, Yang R, et al. **Efficient multi-goal reinforcement learning via value consistency prioritization**[J]. Journal of Artificial Intelligence Research, 2023, 77: 355-376. **JAIR, 2023**. [[Paper]](https://www.jair.org/index.php/jair/article/view/14398)

    `TL;DR: Concentrate on prioritizing both original and relabeled samples for efficient goal-conditioned RL for HER.`

5. Andrychowicz M, Wolski F, Ray A, et al. **Hindsight experience replay**[C]. Advances in neural information processing systems, 2017, 30. **NeurIPS, 2017**. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2017/file/453fadbd8a1a3af50a9df4df899537b5-Paper.pdf)

## 10. Optimization

1. Tang Y, Kucukelbir A. **Hindsight expectation maximization for goal-conditioned reinforcement learning**[C]//International Conference on Artificial Intelligence and Statistics. PMLR, 2021: 2863-2871. **AISTATS, 2021**. [[Paper]](http://proceedings.mlr.press/v130/tang21b/tang21b.pdf)

    `TL;DR: Propose a graphical model framework for goal-conditioned RL, with an expectation maximization (EM) algorithm that operates on the lower bound of the rl objective.`

## 11. Metric Learning / Quasimetric Learning

1. Hartikainen K, Geng X, Haarnoja T, et al. **Dynamical Distance Learning for Semi-Supervised and Unsupervised Skill Discovery**[C]//International Conference on Learning Representations. **ICLR, 2020**. [[Paper]](https://openreview.net/forum?id=H1lmhaVtvr)

2. Wang T, Torralba A, Isola P, et al. **Optimal goal-reaching reinforcement learning via quasimetric learning**[C]//International Conference on Machine Learning. PMLR, 2023: 36411-36430. **ICML, 2023**. [[Paper]](https://proceedings.mlr.press/v202/wang23al.html)

## 12. Applications

1. Wu J, Wang Y, Li L, et al. **Goal Conditioned Reinforcement Learning for Photo Finishing Tuning**[C]//The Thirty-eighth Annual Conference on Neural Information Processing Systems. **NeurIPS, 2024**. [[Paper]](https://openreview.net/forum?id=4kVHI2uXRE)

2. Shah D, Eysenbach B, Rhinehart N, et al. **Rapid Exploration for Open-World Navigation with Latent Goal Models**[C]//Conference on Robot Learning. PMLR, 2022: 674-684. **CORL, 2022**. [[Paper]](https://proceedings.mlr.press/v164/shah22a.html)

    `TL;DR: Employ an information bottleneck to regularize the learned policy, such to achieve (i) a compact visual representation of goals, (ii) improved generalization capabilities, and (iii) a mechanism for sampling feasible goals for exploration.`


## 13. my test pr