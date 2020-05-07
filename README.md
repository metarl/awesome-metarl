# Awesome Meta Reinforcement Learning [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


## Table of Contents

* [Papers](#Papers)
* [Lectures](#Lectures)
* [Blogs](#Blogs)
* [Datasets](#Datasets)


## Papers

### Model-Free Meta Reinforcement Learning

* __Learning to Reinforcement Learn__ (2016) _Jane X Wang, Z Kurth-Nelson, D Tirumala, H Soyer, JZ Leibo, R Munois, C Blundell, D Kumaran, M Botvinick_. [[arXiv]](https://arxiv.org/abs/1611.05763) (recurrent meta-RL)
* __RL^2: Fast Reinforcement Learning via Slow Reinforcement Learning__ (2016) _Yan Duan, John Schulman, Xi Chen, Peter Bartlett_. [[arXiv]](https://arxiv.org/abs/1611.02779) Algorithm: RL^2.
* __A Simple Neural Attentive Meta-Learner__ (2017) _Nikhil Mishra, Mostafa Rohaninejad, Xi Chen, Pieter Abbeel_. [[arXiv]](https://arxiv.org/abs/1707.03141) Algorithm: SNAIL. (soft attention)
* __Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks__ (2017) _Chelsea Finn, Pieter Abbeel, Sergey Levine_. [[arXiv]](https://arxiv.org/abs/1703.03400) [[GitHub]](https://github.com/cbfinn/maml_rl) Algorithm: MAML. (gradient-based meta-RL)
* __ProMP: Proximal Meta-Policy Search__ (2018) _Jonas Rothfuss, Dennis Lee, Ignasi Clavera, Tamin Asfouir, Pieter Abbeel_. [[arXiv]](https://arxiv.org/abs/1810.06784) [[GitHub]](https://github.com/jonasrothfuss/ProMP) Algorithm: ProMP. (gradient-based meta-RL)
* __Meta-Learning Structured Exploration Strategies__ (2018) _Abhishek Gupta, Russell Mendonca, Yuxuan Liu, Pieter Abbeel, Sergey Levine_. [[arXiv]](https://arxiv.org/abs/1802.07245) [[GitHub]](https://github.com/russellmendonca/maesn_suite) Algorithm: MAESN. (gradient-based meta-RL, exploration with latent variables)
* __Efficient Off-Policy Meta-Reinforcement Learning via Probabilistic Context Variables__ (2019) _Kate Rakelly, Aurick Zhou, Deirdre Quillen, Chelsea Finn, Sergey Levine_. [[arXiv]](https://arxiv.org/abs/1903.08254) [[GitHub]](https://github.com/katerakelly/oyster) Algorithm: PEARL. (off-policy meta-RL with posterior sampling for exploration)
* __VariBAD: A Very Good Method for Bayes-Adaptive Deep RL via Meta-Learning__ (2019) _Luisa Zintgraf, Kyriacos Shialis, Maximilian Igl, Sebastian Schulze, Yarin Gal, Katja Hofmann, Shimon Whiteson_. [[arXiv]](https://arxiv.org/abs/1910.08348) [[GitHub]](https://github.com/lmzintgraf/varibad) Algorithm: variBAD. (PEARL + update the latent state every timestep)
* __Generalizing Skills with Semi-Supervised Reinforcement Learning__ (2017) _Chelsea Finn, Tianhe Yu, Justin Fu, Pieter Abbeel, Sergey Levine_. [[arXiv]](https://arxiv.org/abs/1612.00429) [[GitHub]](https://github.com/cbfinn/gps/tree/ssrl)
* __Learning Latent Plans from Play__ (2019) _Corey Lynch, Mohi Khansari, Ted Xiao, Vikash Kumar, Janathan Tompson, Sergey Levine, Pierre Sermanet_. [[arXiv]](https://arxiv.org/abs/1903.01973)
* __Deep Variational Reinforcement Learning for POMDPs__ (2018) _Maximilian Igl, Luisa Zintgraf, Tuan Anh Le, Frank Wood, Shimon Whiteson_. [[arXiv]](https://arxiv.org/abs/1806.02426) [[GitHub]](https://github.com/maximilianigl/DVRL) Algorithm: DVRL. (variational inference for POMDPs)
* __Some Considerations on Learning to Explore with Meta-RL__ (2018) _Bradly C. Stadie, Ge Yang, Rein Houthooft, Xi Chen, Yan Duan, Yuhuai Wu, Pieter Abbeel, Ilya Sutskever_. [[arXiv]](https://arxiv.org/abs/1803.01118) [[GitHub]](https://github.com/geyang/e-maml) Algorithm: E-MAML & E-RL2. (treat the adaptation step as part of the unknown dynamics of environment)
* __Learning to Explore via Meta-Policy Gradient__ (2018) _Tianbing Xu, Qiang Liu, Liang Zhao, Jian Peng_. [[arXiv]](https://arxiv.org/abs/1803.05044) (learn the exploration policy in single task algorithms such as DDPG)
* __Guided Meta-Policy Search__ (2019) _Russell Mendonca, Abhishek Gupta, Rosen Kralev, Pieter Abbeel, Sergey Levine, Chelsea Finn_. [[arXiv]](https://arxiv.org/abs/1904.00956) [[GitHub]](https://github.com/RussellM2020/GMPS)
* __End-to-End Robotic Reinforcement Learning without Reward Engineering__ (2019) _Avi Singh, Larry Yang, Kristian Hartikainen, Chelsea Finn, Sergey Levine_. [[arXiv]](https://arxiv.org/abs/1904.07854) [[GitHub]](https://github.com/avisingh599/reward-learning-rl)
* __Task-Agnostic Dynamics Priors for Deep Reinforcement Learning__ (2019) _Yilun Du, Karthik Narasimhan_. [[arXiv]](https://arxiv.org/abs/1905.04819) [[GitHub]](https://github.com/yilundu/task_agnostic_dynamics_prior) Algorithm: SpatialNet.
* __Meta Reinforcement Learning with Task Embedding and Shared Policy__(2019) _Lin Lan, Zhenguo Li, Xiaohong Guan, Pinghui Wang_. [[arXiv]](https://arxiv.org/abs/1905.06527)
* __Adaptive Guidance and Integrated Navigation with Reinforcement Meta-Learning__ (2019) _Brian Gaudet, Richard Linares, Roberto Furfaro_. [[arXiv]](https://arxiv.org/abs/1904.09865)
* __Learning Latent State Representation for Speeding Up Exploration__ (2019) _Giulia Vezzani, Abhishek Gupta, Lorenzo Natale, Pieter Abbeel_. [[arXiv]](https://arxiv.org/abs/1905.12621)
* __Beyond Exponentially Discounted Sum: Automatic Learning of Return Function__ (2019) _Yufei Wang, Qiwei Ye, Tie-Yan Liu_. [[arXiv]](https://arxiv.org/abs/1905.11591)
* __Learning Efficient and Effective Exploration Policies with Counterfactual Meta Policy__ (2019)  _Ruihan Yang, Qiwei Ye, Tie-Yan Liu_. [[arXiv]](https://arxiv.org/abs/1905.11583)
* __NoRML: No-Reward Meta Learning__ (2019) _Yuxiang Yang, Ken Caluwaerts, Atil Iscen, Jie Tan, Chelsea Finn_. [[arXiv]](https://arxiv.org/abs/1903.01063) [[GitHub]](https://github.com/google-research/google-research/tree/master/norml) Algorithm: NoRML. (MAML + environment dynamics)

### Model-Based Meta Reinforcement Learning

* __Learning to Adapt in Dynamic, Real-World Environments through Meta-Reinforcement Learning__ (2018) _Anuesha Nagabandi, Ignasi Clavera, Simin Liu, Ronald S. Fearing, Pieter Abbeel, Sergey Levine, Chelsea Finn_. [[arXiv]](https://arxiv.org/abs/1803.11347) [[GitHub]](https://github.com/iclavera/learning_to_adapt)
* __Few-Shot Goal Inference for Visuomotor Learning and Planning__ (2018) _Annie Xie, Avi Singh, Sergey Levine, Chelsea Finn_. [[arXiv]](https://arxiv.org/abs/1810.00482) [[GitHub]](https://github.com/anxie/meta_classifier)

### Meta Imitation Learning

* __One-Shot High-Fidelity Imitation: Training Large-Scale Deep Nets with RL__ (2018) _Tom Le Paine, Sergio Gomez Colmenarejo, Ziyu Wang, Scott Reed, Yusuf Aytar, Tobias Pfaff, Matt W. Hoffman, Gabriel Barth-Maron, Serkan Cabi, David Budden, Nando de Freitas_. [[arXiv]](http://arxiv.org/abs/1810.05017) Algorithm: MetaMimic.
* __Watch, Try, Learn: Meta-Learning from Demonstrations and Reward__ (2019) _Allan Zhou, Eric Jang, Daniel Kappler, Alex Herzog, Mohi Khansari, Paul Wohlhart, Yunfei Bai, Mrinal Kalakrishnan, Sergey Levine, Chelsea Finn_. [[arXiv]](https://arxiv.org/abs/1906.03352) [[GitHub]](https://github.com/google-research/tensor2robot/tree/master/research/vrgripper) (demonstrateion + trial-and-error)

### Unsupervised Meta Reinforcement Learning

* __Unsupervised Meta-Learning for Reinforcement Learning__ (2018) _Abhishek Gupta, Benjamin Eysenbach, Chelseas Finn, Sergey Levine_. [[arXiv]](https://arxiv.org/abs/1806.04640)
* __Skew-Fit: State-Covering Self-Supervised Reinforcement Learning__ (2019) _Vitchyr H. Pong, Murtaza Dalal, Steven Lin, Ascvin Nair, Shikhar Bahl, Sergey Levine_. [[arXiv]](https://arxiv.org/abs/1903.03698) Algorithm: Skew-Fit. (maximize entropy)

### Meta Lifelong Reinforcement Learning

* __Gradient Episodic Memory for Continual Learning__ (2017) _David Lopez-Paz, Marc Aurelio Ranzato_. [[arXiv]](https://arxiv.org/abs/1706.08840)
* __Deep Online Learning via Meta-Learning__ (2019) _Nagabandi, Finn, Levine_. [[arXiv]](https://arxiv.org/abs/1812.07671)


## Lectures

* [Stanford CS330: Multi-Task and Meta-Learning](https://cs330.stanford.edu) _Chelsea Finn_.


## Blogs

* [Meta Reinforcement Learning](https://blog.floydhub.com/meta-rl/) _Michaël Trazzi_.
* [Meta Reinforcement Learning](https://lilianweng.github.io/lil-log/2019/06/23/meta-reinforcement-learning.html) _Lilian Weng_.


## Datasets

* [MetaWorld](https://github.com/rlworkgroup/metaworld)
* [Gym (Mojocu/Atari/...)](https://github.com/openai/gym)


Contributions to this repo are welcome.
