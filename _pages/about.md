---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Binghui Li. I am a fourth-year Ph.D. student in [The Center for Machine Learning Research (CMLR)](https://cmlr.pku.edu.cn/About/Introduction/index.htm), Peking University, where I am extremely fortunate to be advised by [Prof. Liwei Wang](http://www.liweiwang-pku.com/) and [Prof. Lei Wu](https://leiwu0.github.io/). I am also pleased to have worked closely with [Prof. Yuanzhi Li](https://scholar.google.com/citations?user=aHtfItQAAAAJ&hl=en), [Prof. Ruoyu Sun](https://ruoyus.github.io/), [Prof. Jian Li](https://people.iiis.tsinghua.edu.cn/~jianli/) and [Prof. Kaifeng Lyu](https://kaifeng.ac/). Before joining CMLR, I received my Bachelor’s degree in Intelligence Science and Technology (Honor Track) from [Turing Class](https://cfcs.pku.edu.cn/english/research/turing_program/introduction1/index.htm), Peking University. My research area is machine learning, with special interests in understanding deep learning and algorithms inspired by theoretical insights.

I currently focus on the theoretical foundations of large language model (LLM) pre-training, particularly scaling laws and optimization dynamics. My recent work explores optimizers [[14](#paper-14), [17](#paper-17), [18](#paper-18)], learning-rate schedules [[10](#paper-10), [15](#paper-15)], batch-size schedules [[12](#paper-12)], and data reuse [[11](#paper-11)]. In particular, I lead a line of research on **functional scaling laws (FSL)** [[10](#paper-10), [12](#paper-12), [15](#paper-15), [17](#paper-17)], developing a framework to characterize learning dynamics and understand how optimization choices shape scaling behavior. Through these efforts, I aim to provide principled guidance for efficient LLM pre-training.
 
If you are interested, please feel free to contact me (libinghui@pku.edu.cn or [WeChat](https://libinghui0000.github.io/WeChat.png))!

Education
=====
- Ph.D. in Data Science (Computer Science and Technology), Peking University, 2023-2028 (Expected).
  
- B.S. in Intelligence Science and Technology (Summa Cum Laude), Peking University, 2019-2023.
  <br/>
  _Overall GPA: 3.82 / 4.00, Average Score: 90.2 / 100, Rank: 2 / 81_

Research Experience
=====

- **(Research Intern) ByteDance Seed, Edge Group, 2026.2-now**
  <br/>
  Research on scaling laws and optimization dynamics for large language model pre-training.

Research Highlights
=====

## LLM Pre-training: Scaling Laws & Optimization

I study the theoretical foundations of efficient LLM pre-training, connecting learning dynamics with practical training decisions.

- **Functional scaling laws and training schedules.** I lead a line of research on functional scaling laws (FSL), developing a framework to characterize learning dynamics and the effects of learning-rate schedules [[10](#paper-10)]. Building on this framework, we study optimal learning-rate schedules [[15](#paper-15)], batch-size scheduling [[12](#paper-12)], and the differences in scaling behavior between SignSGD and SGD [[17](#paper-17)].
- **Optimization dynamics and parameterization.** My work investigates Muon's training dynamics and scaling laws in associative memory learning [[14](#paper-14)], as well as when and how it acts as a preconditioner in the presence of structured gradient noise [[18](#paper-18)]. I also explore the role of scale vectors in LLMs—parameters that are small in number but significant in their effects [[16](#paper-16)].
- **Data reuse and multi-epoch scaling.** We study how repeated training on finite datasets affects scaling behavior, showing how the benefits of data reuse depend on dataset size and distribution [[11](#paper-11)].

## AI Safety: Foundations of Adversarial Robustness

My work on AI safety focuses on adversarial robustness: understanding why neural networks are vulnerable to small input perturbations and when robust learning is possible.

- **Limits of robust generalization.** We investigate the expressive power required for robust learning, identifying fundamental barriers that help explain why robust generalization can be substantially harder than standard generalization [[3](#paper-3)].
- **Feature learning and adversarial training.** We study how adversarial training can improve robustness through feature learning [[4](#paper-4)], and how the implicit bias of gradient descent can lead to non-robust representations [[5](#paper-5)].
- **Robust overfitting and training dynamics.** We examine generalization and robust overfitting in adversarial training through the complementary perspectives of representation complexity and training dynamics [[7](#paper-7)].

My other research interests include **multimodal retrieval-augmented generation** [[6](#paper-6), [9](#paper-9)] and **mathematical discovery**, including sphere-packing constructions [[8](#paper-8)].

Publications & Preprints
=====
\* indicates equal contribution, &dagger; means project lead.

- <span id="paper-18"></span>**[18] (Preprint) [When and How Does Muon Precondition? The Role of Structured Gradient Noise](https://arxiv.org/abs/2610.31728)**
  <br/>
  _Xiaoran Chen\*, **Binghui Li**\* &dagger; , Liwei Wang, Pinyan Lu_

- <span id="paper-17"></span>**[17] (NeurIPS 2026, Spotlight) [How Can SignSGD Outperform SGD? A Functional Scaling Law Perspective](https://openreview.net/forum?id=g7xKEe1njs)**
  <br/>
  _Zilin Wang\*, **Binghui Li**\*, Jia-Nan Wang\*, Lean Wang\*, Jinbo Wang\*, Lei Wu_

- <span id="paper-16"></span>**[16] (Preprint) [Negligible in Size, Significant in Effect: On Scale Vectors in Large Language Models](https://arxiv.org/abs/2605.26895)**
  <br/>
  _Mingze Wang, Shuchen Zhu, Yuxin Fang, **Binghui Li**, Kai Shen, Shu Zhong_

- <span id="paper-15"></span>**[15] (COLT 2026) [Optimal Learning-Rate Schedules under Functional Scaling Laws: Power Decay and Warmup-Stable-Decay](https://arxiv.org/abs/2602.06797)**
  <br/>
  _**Binghui Li**\*, Zilin Wang\*, Fengling Chen, Shiyang Zhao, Ruiheng Zheng, Lei Wu_

- <span id="paper-14"></span>**[14] (ICML 2026) [Muon in Associative Memory Learning: Training Dynamics and Scaling Laws](https://arxiv.org/abs/2602.05725)**
  <br/>
  _**Binghui Li**\* &dagger; , Kaifei Wang\*, Han Zhong, Pinyan Lu, Liwei Wang_

- <span id="paper-13"></span>**[13] (ICLR 2026 Sci4DL Workshop) [Scaling-Law Analysis of SignSGD: From Feature-Space Linear Regression to LLM Pre-training](https://openreview.net/forum?id=KQfV97S12I)**
  <br/>
  _(&alpha;-&beta; order) **Binghui Li** &dagger;, Jianan Wang, Jinbo Wang, Lean Wang, Zilin Wang, Lei Wu_

- <span id="paper-12"></span>**[12] (ICLR 2026) [Fast Catch-Up, Late Switching: Optimal Batch Size Scheduling via Functional Scaling Laws](https://arxiv.org/abs/2602.14208)**
  <br/>
  _Jinbo Wang\*, **Binghui Li**\*, Zhanpeng Zhou, Mingze Wang, Yuxuan Sun, Jiaqi Zhang, Xunliang Cai, Lei Wu_

- <span id="paper-11"></span>**[11] (ICLR 2026) [Larger Datasets Can Be Repeated More: A Theoretical Analysis of Multi-Epoch Scaling in Linear Regression](https://arxiv.org/abs/2511.13421)**
  <br/>
  _Tingkai Yan\*, Haodong Wen\*, **Binghui Li**\*, Kairong Luo, Wenguang Chen, Kaifeng Lyu_
  
- <span id="paper-10"></span>**[10] (NeurIPS 2025, Spotlight) [Functional Scaling Laws in Kernel Regression: Loss Dynamics and Learning Rate Schedules](https://arxiv.org/abs/2509.19189)**
  <br/>
  _**Binghui Li**\* &dagger; , Fengling Chen\*, Zixun Huang\*, Lean Wang\*, Lei Wu_

- <span id="paper-9"></span>**[9] (Preprint) [M2IO-R1: An Efficient RL-Enhanced Reasoning Framework for Multimodal Retrieval Augmented Multimodal Generation](https://arxiv.org/abs/2508.06328)**
  <br/>
  _Zhiyou Xiao\*, Qinhan Yu\*, **Binghui Li**\* &dagger; , Geng Chen, Chong Chen, Wentao Zhang_

- <span id="paper-8"></span>**[8] (Preprint) [New Sphere Packings from the Antipode Construction](https://arxiv.org/abs/2505.02394)**
  <br/>
  _(&alpha;-&beta; order) Ruitao Chen, Jiachen Hu, **Binghui Li**, Liwei Wang, Tianyi Wu_

- <span id="paper-7"></span>**[7] (ICML 2025) [On the Clean Generalization and Robust Overfitting in Adversarial Training from Two Theoretical Views: Representation Complexity and Training Dynamics](https://arxiv.org/abs/2306.01271)**
  <br/>
  _**Binghui Li**, Yuanzhi Li_
  
- <span id="paper-6"></span>**[6] (SIGIR 2025) [MRAMG-Bench: A Comprehensive Benchmark for Advancing Multimodal Retrieval-Augmented Multimodal Generation](https://arxiv.org/abs/2502.04176)**
  <br/>
  _Qinhan Yu\*, Zhiyou Xiao\*, **Binghui Li**\*, Zhengren Wang, Chong Chen, Wentao Zhang_

- <span id="paper-5"></span>**[5] (ICLR 2025) [Feature Averaging: An Implicit Bias of Gradient Descent Leading to Non-Robustness in Neural Networks](https://arxiv.org/abs/2410.10322)**
  <br/>
  _**Binghui Li**\*, Zhixuan Pan\*, Kaifeng Lyu, Jian Li_

- <span id="paper-4"></span>**[4] (ICLR 2025) [Adversarial Training Can Provably Improve Robustness: Theoretical Analysis of Feature Learning Process Under Structured Data](https://arxiv.org/abs/2410.08503)**
  <br/>
  _**Binghui Li**, Yuanzhi Li_

- <span id="paper-3"></span>**[3] (NeurIPS 2022) [Why Robust Generalization in Deep Learning is Difficult: Perspective of Expressive Power](https://arxiv.org/abs/2205.13863)**
  <br/>
  _**Binghui Li**\*, Jikai Jin\*, Han Zhong, John E. Hopcroft, Liwei Wang_
  
- <span id="paper-2"></span>**[2] (Preprint) [Reconstruction Task Finds Universal Winning Tickets](https://arxiv.org/abs/2202.11484)**
  <br/>
  _Ruichen Li, **Binghui Li**, Qi Qian, Liwei Wang_

- <span id="paper-1"></span>**[1] (Preprint) [Boosting Certified ℓ<sub>∞</sub> Robustness with EMA Method and Ensemble Model](https://arxiv.org/abs/2107.00230)**
  <br/>
  _**Binghui Li**\*, Shiji Xin\*, Qizhe Zhang\*_

Invited Talks
=====
- 2026.05, At the Fifth Turing Student Research Forum, Peking University, **A Functional Perspective on Scaling Laws in LLM Pre-Training [[Event](https://eecs.pku.edu.cn/info/1040/11563.htm)]**

- 2026.05, At the [FAI Seminar](https://www.fai-seminar.ac.cn/) (International Seminar on Foundational Artificial Intelligence), **Understanding LLM Pre-Training Dynamics via Functional Scaling Laws [[Video](https://www.bilibili.com/video/BV1hM5v6REvJ/)]**

- 2025.11, At the Eleventh Beijing Computational Mathematics Postgraduate Forum, Peking University, **Functional Scaling Laws in Kernel Regression: Loss Dynamics and Learning Rate Schedules [[Slides](https://libinghui0000.github.io/)]**

- 2025.11, At the Yao Class Seminar, Tsinghua University, **Functional Scaling Laws in Kernel Regression: Loss Dynamics and Learning Rate Schedules [[Slides](https://libinghui0000.github.io/)]**

- 2025.06, At the [FAI Seminar](https://www.fai-seminar.ac.cn/) (International Seminar on Foundational Artificial Intelligence), **Theoretical Understanding of Adversarial Examples in Deep Learning: Expressive Power and Training Dynamics [[Video](https://www.bilibili.com/video/BV1tmMtzYEiv/)]**

- 2025.04, At the Applied Mathematics Youth Seminar, Peking University, **Theoretical Understanding of Adversarial Examples: 
Expressive Power and Training Dynamics [[Slides](0402_Slides.pdf)]**

- 2024.11, At the Turing Student CS Frontier Tutorial, Peking University, **Theoretical Understanding of Adversarial Examples: 
Expressive Power and Training Dynamics [[Slides](CS_Frontier_Tutorial_Slides.pdf)]**
  
- 2024.11, At the Tenth Beijing Computational Mathematics Postgraduate Forum, Peking University, **Theoretical Understanding of Adversarial Examples: 
Expressive Power and Training Dynamics [[Slides](Math_Slides.pdf)]**

- 2024.05, At the Turing Student Research Forum, Peking University, **Understanding Adversarial Examples and Adversarial Training in Deep Learning: A Feature Learning View [[Slides](Adv_Training_Sildes.pdf)]**

- 2023.08, At International Joint Conference on Theoretical Computer Science – Frontier of Algorithmic Wisdom (IJTCS-FAW 2023), **Robust Generalization Requires Exponentially Large Models [[Slides](IJTCS_Slides.pdf)]**

- 2023.05, At the Turing Student Research Forum, Peking University, **Robust Generalization Requires Exponentially Large Models [[Video](https://www.bilibili.com/video/BV1mL411v7wx/?share_source=copy_web&vd_source=15ace44d20f0ecdd743e4865b78e402f)]**

- 2022.05, At the Fourth BAAI Conference, **Robust Generalization Requires Exponentially Large Models [[Slides](Robust_Generalization_Slides.pdf)] [[Video](https://www.bilibili.com/video/BV17B4y1Y7dP/?spm_id_from=333.337.search-card.all.click)]**

Selected Awards
=====
- [The CAST Youth Science and Technology Talent Cultivation Program for Doctoral Students](https://kecaihui-tm-zz.cast.org.cn/specialPage/web?type=qtgc), 2025
- [National Scholarship](https://www.ds.pku.edu.cn/xwdt/939331.htm), 2025, 2026 (top 1% in the nation)
- [Peking University Elite Student Program for Applied Mathematics](https://cmlr.pku.edu.cn/Graduate/ElitePhDProgram/index.htm), 2024-2028 (Expected)
- [President Scholarship of PKU](https://www.ds.pku.edu.cn/xwdt/935745.htm), 2023
- Weiming Scholar of PKU, 2023 (top 1%, the highest honor for undergraduates in Peking University)
- [Top 10 Bachelor Thesis of School of EECS, PKU](https://eecs.pku.edu.cn/info/1046/5671.htm), 2023
- Third Class Scholarship of PKU, 2022
- [John Hopcroft Scholarship](https://cfcs.pku.edu.cn/english/research/turing_program/john_hopcroft_foundation/index.htm), 2021
- Peking University Collegiate Programming Contest, Third Prize, 2021
- Third Class Scholarship of PKU, 2020
- Chinese Mathematical Olympiad, Bronze Medal, 2018
- Chinese Southeast Mathematical Olympiad, Gold Medal, 2017
- Physics Olympiad of Shaanxi, Third Prize, 2017

Teaching
=====
- 2025 Fall: CS 34100 Mathematical Foundations for the Information Age, PKU (TA, with [Prof. Yuqing Kong](https://cfcs.pku.edu.cn/yuqkong/))

- 2025 Fall: CS 33400 Discrete Mathematics and Structures, PKU (TA, with [Prof. Tianren Liu](https://liutianren.com/))

- 2025 Spring: CS 34010 Randomness and Computation, PKU (TA, with [Prof. Yuqing Kong](https://cfcs.pku.edu.cn/yuqkong/))

- 2024 Fall: CS 33400 Discrete Mathematics and Structures, PKU (TA, with [Prof. Tianren Liu](https://liutianren.com/))
  
- 2023 Fall: CS 33400 Discrete Mathematics and Structures, PKU (TA, with [Prof. Tianren Liu](https://liutianren.com/))
  
- 2022 Fall: CS 33400 Discrete Mathematics and Structures, PKU (TA, with [Prof. Xiaotie Deng](https://cfcs.pku.edu.cn/english/people/faculty/xiaotiedeng/index.htm))

- 2021 Fall: CS 33400 Discrete Mathematics and Structures, PKU (TA, with [Prof. Xiaotie Deng](https://cfcs.pku.edu.cn/english/people/faculty/xiaotiedeng/index.htm))

Professional Service
=====
- Conference reviewer of ICLR 2023/ NeurIPS 2024/ ICLR 2025/ AISTATS 2025/ ICML 2025/ NeurIPS 2025/ AAAI 2026/ AISTATS 2026/ ICLR 2026/ CVPR 2026/ ICML 2026/ ECCV 2026/ NeurIPS 2026/ AAAI 2027/ ICLR 2027/ AISTATS 2027
- Committee member of Turing Class Research Committee since 2020

Selected Courses
=====
- Machine Learning: 93/100
- Numerical Methods (B): 95/100
- High-Dimensional Probability: 90/100
- Study and Practice on Topics of Frontier Computing (II): 96/100
- Introduction to the Theory of Computation: 92/100
- Mathematical Analysis (I): 97.5/100
- Discrete Mathematics and Structures (I): 97/100
- Probability Theory and Statistics (A): 96/100
- Python Programming and Application: 96/100
- Advanced Algebra (II): 99/100
- Practice of Programming in C&C++: 93/100
- Algorithm Design and Analysis (Honor Track): 91.5/100
- Information Theory: 90/100
- Mathematical Foundations for the Information Age: 92/100
- The Brain and Cognitive Science: 91/100

