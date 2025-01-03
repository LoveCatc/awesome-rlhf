# awesome-rlhf
Welcome to our curated collection of research and review papers focused on Reinforcement Learning from Human Feedback (RLHF). We encourage you to star, fork, and contribute to this repository. We're actively seeking additional contributors and maintainers! 

Maintained by:

- [Li Jiang](https://louieworth.github.io/), McGill University

Please follow this format for contributions:
```
- [Paper Title](paper link) [Additional Links]
  - Author1, Author2, and Author3. arXiv/Conference/Journal, Year.
```

For any inquiries, don't hesitate to contact: li.jiang3@mail.mcgill.ca

Some notes:

- This resource is dedicated to the latest papers and does not include past academic works, even those published earlier in 2023. For a review of prominent historical papers and other sources, please refer to [hugging face blog](https://huggingface.co/blog/rlhf#further-reading) and [this link](https://github.com/opendilab/awesome-RLHF) from OpendiLab.
- Most of the paper collections is credited to [RLHF papers](https://www.craft.me/s/NHvR6dsCVNNW8L).

## Table of Contents
- [Papers](https://github.com/louieworth/awesome-rlhf#papers)
  - [Review/Survey/Position Papers](https://github.com/louieworth/awesome-rlhf#reviewsurveyposition-papers)
  - [RLHF for LLMs: Theory / Methods](https://github.com/louieworth/awesome-rlhf#rlhf-for-llms-theory--methods)
  - [RLHF for Other Domains](https://github.com/louieworth/awesome-rlhf#rlhf-for-other-domains)
  - [Datasets](https://github.com/louieworth/awesome-rlhf#datasets)
- [Blogs/Talks/Reports](https://github.com/louieworth/awesome-rlhf#blogstalksreports)
  - [Blogs](https://github.com/louieworth/awesome-rlhf#blogs)
  - [Talks](https://github.com/louieworth/awesome-rlhf#talks)
  - [Reports](https://github.com/louieworth/awesome-rlhf#reports)
- [Open Source Software/Implementations](https://github.com/louieworth/awesome-rlhf#open-source-softwareimplementations)


## Papers

### Review/Survey
- [Foundational Challenges in Assuring Alignment and Safety of Large Language Models](https://arxiv.org/abs/2404.09932).
    -  Usman Anwar, Abulhair Saparov, Javier Rando, Daniel Paleka, Miles Turpin, Peter Hase, Ekdeep Singh Lubana, Erik Jenner, Stephen Casper, Oliver Sourbut, Benjamin L. Edelman, Zhaowei Zhang, Mario Günther, Anton Korinek, Jose Hernandez-Orallo, Lewis Hammond, Eric Bigelow, Alexander Pan, Lauro Langosco, Tomasz Korbak, Heidi Zhang, Ruiqi Zhong, Seán Ó hÉigeartaigh, Gabriel Recchia, Giulio Corsi, Alan Chan, Markus Anderljung, Lilian Edwards, Yoshua Bengio, Danqi Chen, Samuel Albanie, Tegan Maharaj, Jakob Foerster, Florian Tramer, He He, Atoosa Kasirzadeh, Yejin Choi, David Krueger. arXiv, 2024.
- [Negating Negatives: Alignment without Human Positive Samples via Distributional Dispreference Optimization](https://arxiv.org/abs/2403.03419)
    - Shitong Duan, Xiaoyuan Yi, Peng Zhang, Tun Lu, Xing Xie, Ning Gu. arXiv 2024.
- [AI Alignment: A Comprehensive Survey](https://arxiv.org/abs/2310.19852)
  - Jiaming Ji, Tianyi Qiu, Boyuan Chen, Borong Zhang, Hantao Lou, Kaile Wang, Yawen Duan, Zhonghao He, Jiayi Zhou, Zhaowei Zhang, Fanzhi Zeng, Kwan Yee Ng, Juntao Dai, Xuehai Pan, Aidan O'Gara, Yingshan Lei, Hua Xu, Brian Tse, Jie Fu, Stephen McAleer, Yaodong Yang, Yizhou Wang, Song-Chun Zhu, Yike Guo, Wen Gao. arXiv, 2024.
- [Aligning Large Language Models with Human: A Survey](https://arxiv.org/abs/2307.12966)
  - Yufei Wang, Wanjun Zhong, Liangyou Li, Fei Mi, Xingshan Zeng, Wenyong Huang, Lifeng Shang, Xin Jiang, Qun Liu. arXiv, 2024.
- [Open Problems and Fundamental Limitations of Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2307.15217)
  - Stephen Casper, Xander Davies, Claudia Shi, Thomas Krendl Gilbert, Jérémy Scheurer, Javier Rando, Rachel Freedman, Tomasz Korbak, David Lindner, Pedro Freire, Tony Wang, Samuel Marks, Charbel-Raphaël Segerie, Micah Carroll, Andi Peng, Phillip Christoffersen, Mehul Damani, Stewart Slocum, Usman Anwar, Anand Siththaranjan, Max Nadeau, Eric J. Michaud, Jacob Pfau, Dmitrii Krasheninnikov, Xin Chen, Lauro Langosco, Peter Hase, Erdem Bıyık, Anca Dragan, David Krueger, Dorsa Sadigh, and Dylan Hadfield-Menell. arXiv, 2024.

### RLHF for LLMs: Theory / Methods
- [Reward Modeling with Ordinal Feedback: Wisdom of the Crowd](https://arxiv.org/abs/2411.12843)
    - Shang Liu, Yu Pan, Guanting Chen, Xiaocheng Li. arXiv, 2024.
- [Learn Your Reference Model for Real Good Alignment](https://arxiv.org/abs/2404.09656)
    - Alexey Gorbatovski, Boris Shaposhnikov, Alexey Malakhov, Nikita Surnachev, Yaroslav Aksenov, Ian Maksimov, Nikita Balagansky, Daniil Gavrilov. arXiv, 2024.
- [Dataset Reset Policy Optimization for RLHF](https://arxiv.org/abs/2404.08495)
    -  Jonathan D. Chang, Wenhao Zhan, Owen Oertell, Kianté Brantley, Dipendra Misra, Jason D. Lee, Wen Sun. arXiv, 2024.
- [Back to Basics: Revisiting REINFORCE Style Optimization for Learning from Human Feedback in LLMs](https://arxiv.org/abs/2402.14740)
    -  Arash Ahmadian, Chris Cremer, Matthias Gallé, Marzieh Fadaee, Julia Kreutzer, Olivier Pietquin, Ahmet Üstün, Sara Hooker. ICLR, 2024.
- [CPPO: Continual Learning for Reinforcement Learning with Human Feedback](https://openreview.net/forum?id=86zAUE80pP)
    -  Han Zhang, Yu Lei, Lin Gui, Min Yang, Yulan He, Hui Wang, Ruifeng Xu. ICLR, 2024.
- [Leftover-Lunch: Advantage-based Offline Reinforcement Learning for Language Models](https://arxiv.org/abs/2305.14718)
    - Ashutosh Baheti, Ximing Lu, Faeze Brahman, Ronan Le Bras, Maarten Sap, Mark Riedl. arXiv, 2024.
- [Proxy-RLHF: Decoupling Generation and Alignment in Large Language Model with Proxy](https://arxiv.org/abs/2403.04283)
    - Yu Zhu, Chuxiong Sun, Wenfei Yang, Wenqiang Wei, Bo Tang, Tianzhu Zhang, Zhiyu Li, Shifeng Zhang, Feiyu Xiong, Jie Hu, Mingchuan yang. arXiv, 2024. 
- [KTO: Model Alignment as Prospect Theoretic Optimization](https://arxiv.org/abs/2402.01306).
    -  Kawin Ethayarajh, Winnie Xu, Niklas Muennighoff, Dan Jurafsky, Douwe Kiela. arXiv, 2024.
- [Human Alignment of Large Language Models through Online Preference Optimisation](https://arxiv.org/abs/2403.08635)
    -  Daniele Calandriello, Daniel Guo, Remi Munos, Mark Rowland, Yunhao Tang, Bernardo Avila Pires, Pierre Harvey Richemond, Charline Le Lan, Michal Valko, Tianqi Liu, Rishabh Joshi, Zeyu Zheng, Bilal Piot. arXiv, 2024.
- [Learn Your Reference Model for Real Good Alignment](https://arxiv.org/abs/2404.09656)
    -  Alexey Gorbatovski, Boris Shaposhnikov, Alexey Malakhov, Nikita Surnachev, Yaroslav Aksenov, Ian Maksimov, Nikita Balagansky, Daniil Gavrilov. arXiv, 2024.
- [Direct Nash Optimization: Teaching Language Models to Self-Improve with General Preferences](https://arxiv.org/abs/2404.03715)
    -  Corby Rosset, Ching-An Cheng, Arindam Mitra, Michael Santacroce, Ahmed Awadallah, Tengyang Xie. arXiv, 2024.
- [MaxMin-RLHF: Towards Equitable Alignment of Large Language Models with Diverse Human Preferences](https://arxiv.org/abs/2402.08925)
    -  Souradip Chakraborty, Jiahao Qiu, Hui Yuan, Alec Koppel, Furong Huang, Dinesh Manocha, Amrit Singh Bedi, Mengdi Wang. arXiv, 2024.
- [Supervised Fine-Tuning as Inverse Reinforcement Learning](https://arxiv.org/pdf/2403.12017.pdf).
    - Hao Sun. arXiv, 2024.
- [Easy-to-Hard Generalization: Scalable Alignment Beyond Human Supervision](https://arxiv.org/abs/2403.05534)
    - Zhiqing Sun, Longhui Yu, Yikang Shen, Weiyang Liu, Yiming Yang, Sean Welleck, Chuang Gan. arXiv, 2023.
- [Bayesian Preference Elicitation with Language Models](https://arxiv.org/abs/2403.05534)
    -  Kunal Handa, Yarin Gal, Ellie Pavlick, Noah Goodman, Jacob Andreas, Alex Tamkin, Belinda Z. Li. arXiv, 2024.
- [Direct Preference Optimization with an Offset](https://arxiv.org/abs/2402.10571)
    -  Afra Amini, Tim Vieira, Ryan Cotterell. arXiv, 2024.
- [Self-Rewarding Language Models](https://arxiv.org/abs/2401.10020).
    - Weizhe Yuan, Richard Yuanzhe Pang, Kyunghyun Cho, Xian Li, Sainbayar Sukhbaatar, Jing Xu, Jason Weston. arXiv, 2024.
- [Self-Alignment of Large Language Models via Monopolylogue-based Social Scene Simulation](https://arxiv.org/abs/2402.05699).
    -  Xianghe Pang, Shuo Tang, Rui Ye, Yuxin Xiong, Bolun Zhang, Yanfeng Wang, Siheng Chen. arXiv, 2024.
- [Aligner: Achieving Efficient Alignment through Weak-to-Strong Correction](https://arxiv.org/abs/2402.02416).
    - Jiaming Ji, Boyuan Chen, Hantao Lou, Donghai Hong, Borong Zhang, Xuehai Pan, Juntao Dai, Yaodong Yang. arXiv, 2024.
- [A Minimaximalist Approach to Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2401.04056)
  - Gokul Swamy, Christoph Dann, Rahul Kidambi, Zhiwei Steven Wu, Alekh Agarwal. arXiv, 2024.
- [Preference as Reward, Maximum Preference Optimization with Importance Sampling](https://arxiv.org/abs/2312.16430).
  - Zaifan Jiang, Xing Huang, Chao Wei. arXiv, 2023.
- [Uncertainty-Penalized Reinforcement Learning from Human Feedback with Diverse Reward LoRA Ensembles](https://arxiv.org/abs/2401.00243)
  - Yuanzhao Zhai, Han Zhang, Yu Lei, Yue Yu, Kele Xu, Dawei Feng, Bo Ding, Huaimin Wang. arXiv, 2023.
- [Aligning Large Language Models with Human Preferences through Representation Engineering](https://arxiv.org/abs/2312.15997)
  - Wenhao Liu, Xiaohua Wang, Muling Wu, Tianlong Li, Changze Lv, Zixuan Ling, Jianhao Zhu, Cenyuan Zhang, Xiaoqing Zheng, Xuanjing Huang. arXiv, 2023.
- [The Alignment Ceiling: Objective Mismatch in Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2311.00168).
  - Nathan Lambert, Roberto Calandra. arXiv, 2023.
- [Sample Efficient Reinforcement Learning from Human Feedback via Active Exploration](https://arxiv.org/abs/2312.00267)
  - Viraj Mehta, Vikramjeet Das, Ojash Neopane, Yijia Dai, Ilija Bogunovic, Jeff Schneider, Willie Neiswanger. arXiv, 2023.
- [On the Exploitability of Reinforcement Learning with Human Feedback for Large Language Models](https://arxiv.org/abs/2311.09641)
  - Jiongxiao Wang, Junlin Wu, Muhao Chen, Yevgeniy Vorobeychik, Chaowei Xiao. arXiv, 2023.
- [Policy Optimization in RLHF: The Impact of Out-of-preference Data](https://arxiv.org/pdf/2312.10584.pdf).
  - Ziniu Li, Tian Xu, Yang Yu. arXiv, 2023.
- [Interpreting Reward Models in RLHF-Tuned Language Models Using Sparse Autoencoders](https://arxiv.org/abs/2310.08164).
  - Luke Marks, Amir Abdullah, Luna Mendez, Rauno Arike, Philip Torr, Fazl Barez. arXiv, 2023.
- [SteerLM: Attribute Conditioned SFT as an (User-Steerable) Alternative to RLHF](https://arxiv.org/abs/2310.05344).
  - Yi Dong, Zhilin Wang, Makesh Narsimhan Sreedhar, Xianchao Wu, Oleksii Kuchaiev. arXiv, 2023.
- [Beyond Human Data: Scaling Self-Training for Problem-Solving with Language Models](https://arxiv.org/abs/2312.06585).
  - Avi Singh, John D. Co-Reyes, Rishabh Agarwal, Ankesh Anand, Piyush Patil, Peter J. Liu, James Harrison, Jaehoon Lee, Kelvin Xu, Aaron Parisi, Abhishek Kumar, Alex Alemi, Alex Rizkowsky, Azade Nova, Ben Adlam, Bernd Bohnet, Hanie Sedghi, Igor Mordatch, Isabelle Simpson, Izzeddin Gur, Jasper Snoek, Jeffrey Pennington, Jiri Hron, Kathleen Kenealy, Kevin Swersky, Kshiteej Mahajan, Laura Culp, Lechao Xiao, Maxwell L. Bileschi, Noah Constant, Roman Novak, Rosanne Liu, Tris Warkentin, Yundi Qian, Ethan Dyer, Behnam Neyshabur, Jascha Sohl-Dickstein, Noah Fiedel. arXiv, 2023.
- [Nash Learning from Human Feedback](https://arxiv.org/abs/2312.00886v2).
  - Rémi Munos, Michal Valko, Daniele Calandriello, Mohammad Gheshlaghi Azar, Mark Rowland, Zhaohan Daniel Guo, Yunhao Tang, Matthieu Geist, Thomas Mesnard, Andrea Michi, Marco Selvi, Sertan Girgin, Nikola Momchev, Olivier Bachem, Daniel J. Mankowitz, Doina Precup, Bilal Piot. arXiv, 2023.
- [Interpreting Reward Models in RLHF-Tuned Language Models Using Sparse Autoencoders](https://arxiv.org/abs/2310.08164).
  - Luke Marks, Amir Abdullah, Luna Mendez, Rauno Arike, Philip Torr, Fazl Barez. arXiv, 2023.
- [Adversarial Preference Optimization](https://arxiv.org/abs/2311.08045)
  - Pengyu Cheng, Yifan Yang, Jian Li, Yong Dai, Nan Du. arXiv, 2023. 
- [Black-Box Prompt Optimization: Aligning Large Language Models without Model Training](https://arxiv.org/abs/2311.04155)
  - Jiale Cheng, Xiao Liu, Kehan Zheng, Pei Ke, Hongning Wang, Yuxiao Dong, Jie Tang, Minlie Huang. arXiv, 2023.
- [Fake Alignment: Are LLMs Really Aligned Well?](https://arxiv.org/abs/2311.05915)
  - Yixu Wang, Yan Teng, Kexin Huang, Chengqi Lyu, Songyang Zhang, Wenwei Zhang, Xingjun Ma, Yu-Gang Jiang, Yu Qiao, Yingchun Wang. arXiv, 2023.
- [Beyond Imitation: Leveraging Fine-grained Quality Signals for Alignment](https://arxiv.org/abs/2311.04072)
  - Geyang Guo, Ranchi Zhao, Tianyi Tang, Wayne Xin Zhao, Ji-Rong Wen. arXiv, 2023.
- [Loose lips sink ships: Mitigating Length Bias in Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2310.05199)
  - Wei Shen, Rui Zheng, Wenyu Zhan, Jun Zhao, Shihan Dou, Tao Gui, Qi Zhang, Xuanjing Huang. arXiv, 2023.
- [Is RLHF More Difficult than Standard RL?](http://arxiv.org/abs/2306.14111)
  - Yuanhao Wang, Qinghua Liu, Chi Jin. arXiv, 2023.
- [A General Theoretical Paradigm to Understand Learning from Human Preferences](http://arxiv.org/abs/2310.12036)
- Mohammad Gheshlaghi Azar, Mark Rowland, Bilal Piot, Daniel Guo, Daniele Calandriello, Michal Valko, R´emi Munos. arXiv, 2023.
- [COPF: Continual Learning Human Preference through Optimal Policy Fitting](http://arxiv.org/abs/2310.15694)
  - Han Zhang, Lin Gui, Yuanzhao Zhai, Hui Wang, Yu Lei, Ruifeng Xu. arXiv, 2023.
- [SuperHF: Supervised Iterative Learning from Human Feedback](https://arxiv.org/abs/2310.16763).
  - Gabriel Mukobi, Peter Chatain, Su Fong, Robert Windesheim, Gitta Kutyniok, Kush Bhatia, Silas Alberti. arXiv, 2023.
- [Gaining Wisdom from Setbacks: Aligning Large Language Models via Mistake Analysis](https://export.arxiv.org/abs/2310.10477)
  - Kai Chen, Chunwei Wang, Kuo Yang, Jianhua Han, Lanqing Hong, Fei Mi, Hang Xu, Zhengying Liu, Wenyong Huang, Zhenguo Li, Dit-Yan Yeung, Lifeng Shang, Xin Jiang, Qun Liu. arXiv, 2023.
- [Entangled Preferences: The History and Risks of Reinforcement Learning and Human Feedback](https://arxiv.org/abs/2310.13595)
  - Nathan Lambert, Thomas Krendl Gilbert, Tom Zick. arXiv, 2023.
- [Group Preference Optimization: Few-Shot Alignment of Large Language Models](https://arxiv.org/abs/2310.11523)
  - Siyan Zhao, John Dang, Aditya Grover. arXiv, 2023.
- [Safe RLHF: Safe Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2310.12773)
  - Josef Dai, Xuehai Pan, Ruiyang Sun, Jiaming Ji, Xinbo Xu, Mickel Liu, Yizhou Wang, Yaodong Yang. arXiv, 2023.
- [ReMax: A Simple, Effective, and Efficient Reinforcement Learning Method for Aligning Large Language Models](https://arxiv.org/abs/2310.10505).
  - Ziniu Li, Tian Xu, Yushun Zhang, Yang Yu, Ruoyu Sun, Zhi-Quan Luo. arXiv, 2023.
- [Stabilizing RLHF through Advantage Model and Selective Rehearsal](https://arxiv.org/abs/2309.10202)
  - Baolin Peng, Linfeng Song, Ye Tian, Lifeng Jin, Haitao Mi, Dong Yu. arXiv, 2023.
- [Beyond One-Preference-for-All: Multi-Objective Direct Preference Optimization for Language Models](https://arxiv.org/abs/2310.03708).
  - Zhanhui Zhou, Jie Liu, Chao Yang, Jing Shao, Yu Liu, Xiangyu Yue, Wanli Ouyang, Yu Qiao. arXiv, 2023.
- [A General Theoretical Paradigm to Understand Learning from Human Preferences](https://arxiv.org/abs/2310.12036).
  -  Mohammad Gheshlaghi Azar, Mark Rowland, Bilal Piot, Daniel Guo, Daniele Calandriello, Michal Valko, Rémi Munos. arXiv, 2023.
- [Pairwise Proximal Policy Optimization: Harnessing Relative Feedback for LLM Alignment](https://arxiv.org/abs/2310.00212)
  - Tianhao Wu, Banghua Zhu, Ruoyu Zhang, Zhaojin Wen, Kannan Ramchandran, Jiantao Jiao. arXiv, 2023.
- [Understanding the Effects of RLHF on LLM Generalisation and Diversity](https://arxiv.org/abs/2310.06452)
  - Robert Kirk, Ishita Mediratta, Christoforos Nalmpantis, Jelena Luketina, Eric Hambro, Edward Grefenstette, Roberta Raileanu. arXiv, 2023.
- [Improving Language Models with Advantage-based Offline Policy Gradients](https://arxiv.org/abs/2305.14718)
  - Ashutosh Baheti, Ximing Lu, Faeze Brahman, Ronan Le Bras, Maarten Sap, Mark Riedl. arXiv, 2023.
- [SALMON: Self-Alignment with Principle-Following Reward Models](https://arxiv.org/abs/2310.05910)
  - Zhiqing Sun, Yikang Shen, Hongxin Zhang, Qinhong Zhou, Zhenfang Chen, David Cox, Yiming Yang, Chuang Gan. arXiv, 2023.
- [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](http://arxiv.org/abs/2305.18290)
  - Rafael Rafailov, Archit Sharma, Eric Mitchell, Stefano Ermon, Christopher D. Manning, Chelsea Finn. NeurIPS, 2023.
- [RAFT: Reward rAnked FineTuning for Generative Foundation Model Alignment](https://arxiv.org/abs/2304.06767).
  - Hanze Dong, Wei Xiong, Deepanshu Goyal, Yihan Zhang, Winnie Chow, Rui Pan, Shizhe Diao, Jipeng Zhang, Kashun Shum, Tong Zhang. arXiv, 2023.
- [Preference Ranking Optimization for Human Alignment](https://arxiv.org/abs/2306.17492).
  - Feifan Song, Bowen Yu, Minghao Li, Haiyang Yu, Fei Huang, Yongbin Li, Houfeng Wang. arXiv, 2023.
- [RRHF: Rank Responses to Align Language Models with Human Feedback without tears](https://arxiv.org/abs/2304.05302) 
  - Zheng Yuan, Hongyi Yuan, Chuanqi Tan, Wei Wang, Songfang Huang, Fei Huang. NeurIPS, 2023.
- [Reward Model Ensembles Help Mitigate Overoptimization](https://arxiv.org/abs/2310.02743)
  - Thomas Coste, Usman Anwar, Robert Kirk, David Krueger. arXiv, 2023.
- [Learning Optimal Advantage from Preferences and Mistaking it for Reward](https://arxiv.org/abs/2310.02456)
  - W. Bradley Knox, Stephane Hatgis-Kessell, Sigurdur Orn Adalgeirsson, Serena Booth, Anca Dragan, Peter Stone, Scott Niekum. arXiv, 2023.
- [Enable Language Models to Implicitly Learn Self-Improvement From Data](https://arxiv.org/abs/2310.00898)
  - Ziqi Wang, Le Hou, Tianjian Lu, Yuexin Wu, Yunxuan Li, Hongkun Yu, Heng Ji. arXiv, 2023.
- [The Trickle-down Impact of Reward (In-)consistency on RLHF](https://arxiv.org/abs/2309.16155v1)
  - Lingfeng Shen, Sihao Chen, Linfeng Song, Lifeng Jin, Baolin Peng, Haitao Mi, Daniel Khashabi, Dong Yu. arXiv, 2023.
- [Aligning Language Models with Offline Reinforcement Learning from Human Feedback](http://arxiv.org/abs/2308.12050)
  - Jian Hu, Li Tao, June Yang, Chandler Zhou. arXiv, 2023.
- [Human Feedback is not Gold Standard](https://arxiv.org/abs/2309.16349)
  - Tom Hosking, Phil Blunsom, Max Bartolo. arXiv, 2023.
- [Fine-Tuning Language Models with Advantage-Induced Policy Alignment](http://arxiv.org/abs/2306.02231)
  - Banghua Zhu, Hiteshi Sharma, Felipe Vieira Frujeri, Shi Dong, Chenguang Zhu, Michael I. Jordan, Jiantao Jiao. arXiv, 2023. 
- [Principled Reinforcement Learning with Human Feedback from Pairwise or $K$-wise Comparisons](http://arxiv.org/abs/2301.11270).
  - Banghua Zhu, Jiantao Jiao, Michael I. Jordan. arXiv, 2023.
- [Making PPO even better: Value-Guided Monte-Carlo Tree Search decoding](https://arxiv.org/abs/2309.15028)
  - Jiacheng Liu, Andrew Cohen, Ramakanth Pasunuru, Yejin Choi, Hannaneh Hajishirzi, Asli Celikyilmaz. arXiv, 2023.
- [Stabilizing RLHF through Advantage Model and Selective Rehearsal](https://arxiv.org/abs/2309.10202)
  - Baolin Peng, Linfeng Song, Ye Tian, Lifeng Jin, Haitao Mi, Dong Yu. arXiv, 2023.
- [Exploring the impact of low-rank adaptation on the performance, efficiency, and regularization of RLHF](https://arxiv.org/abs/2309.09055)
  - Simeng Sun, Dhawal Gupta, Mohit Iyyer. arXiv, 2023.
- [RAIN: Your Language Models Can Align Themselves without Finetuning](https://arxiv.org/abs/2309.07124)
  - Yuhui Li, Fangyun Wei, Jinjing Zhao, Chao Zhang, Hongyang Zhang, arXiv, 2023.
- [Statistical Rejection Sampling Improves Preference Optimization](https://arxiv.org/pdf/2309.06657.pdf)
  - Tianqi Liu, Yao Zhao, Rishabh Joshi, Misha Khalman, Mohammad Saleh, Peter J. Liu, Jialu Liu. arXiv, 2023.
- [RLAIF: Scaling Reinforcement Learning from Human Feedback with AI Feedback](https://arxiv.org/abs/2309.00267)
  - Harrison Lee, Samrat Phatale, Hassan Mansoor, Kellie Lu, Thomas Mesnard, Colton Bishop, Victor Carbune, Abhinav Rastogi. arXiv, 2023.
- [Reinforced Self-Training (ReST) for Language Modeling](http://arxiv.org/abs/2308.08998)
  - Caglar Gulcehre, Tom Le Paine, Srivatsan Srinivasan, Ksenia Konyushkova, Lotte Weerts, Abhishek Sharma, Aditya Siddhant, Alex Ahern, Miaosen Wang, Chenjie Gu, Wolfgang Macherey, Arnaud Doucet, Orhan Firat, Nando de Freitas. arXiv, 2023.
- [Peering Through Preferences: Unraveling Feedback Acquisition for Aligning Large Language Models](https://arxiv.org/abs/2308.15812)
  - Hritik Bansal, John Dang, Aditya Grover. arXiv, 2023.
- [Let Me Teach You: Pedagogical Foundations of Feedback for Language Models](https://arxiv.org/abs/2307.00279)
  - Beatriz Borges, Niket Tandon, Tanja Käser, Antoine Bosselut. arXiv, 2023.
- [Generalized Knowledge Distillation for Auto-regressive Language Models](https://arxiv.org/abs/2306.13649)
  - Rishabh Agarwal, Nino Vieillard, Yongchao Zhou, Piotr Stanczyk, Sabela Ramos, Matthieu Geist, Olivier Bachem. arXiv, 2023.
- [Secrets of RLHF in Large Language Models Part I: PPO](http://arxiv.org/abs/2307.04964)
  - Rui Zheng, Shihan Dou, Songyang Gao, Yuan Hua, Wei Shen, Binghai Wang, Yan Liu, Senjie Jin, Qin Liu, Yuhao Zhou, Limao Xiong, Lu Chen, Zhiheng Xi, Nuo Xu, Wenbin Lai, Minghao Zhu, Cheng Chang, Zhangyue Yin, Rongxiang Weng, Wensen Cheng, Haoran Huang, Tianxiang Sun, Hang Yan, Tao Gui, Qi Zhang, Xipeng Qiu, Xuanjing Huang. arXiv, 2023.
- [Learning to Generate Better Than Your LLM](https://arxiv.org/abs/2306.11816)
  - Jonathan D. Chang, Kiante Brantley, Rajkumar Ramamurthy, Dipendra Misra, Wen Sun. arXiv, 2023.
- [Fine-Grained Human Feedback Gives Better Rewards for Language Model Training](https://arxiv.org/abs/2306.01693)
  - Zeqiu Wu, Yushi Hu, Weijia Shi, Nouha Dziri, Alane Suhr, Prithviraj Ammanabrolu, Noah A. Smith, Mari Ostendorf, Hannaneh Hajishirzi. NeurIPS, 2023.
- [Continually Improving Extractive QA via Human Feedback](https://arxiv.org/abs/2305.12473)
  - Ge Gao, Hung-Ting Chen, Yoav Artzi, Eunsol Choi. arXiv, 2023.
- [SLiC-HF: Sequence Likelihood Calibration with Human Feedback](https://arxiv.org/abs/2305.10425)
  - Yao Zhao, Rishabh Joshi, Tianqi Liu, Misha Khalman, Mohammad Saleh, Peter J. Liu. arXiv, 2023.
- [The Wisdom of Hindsight Makes Language Models Better Instruction Followers](http://arxiv.org/abs/2302.05206)
  - Tianjun Zhang, Fangchen Liu, Justin Wong, Pieter Abbeel, Joseph E. Gonzalez. arXiv, 2023.

### RLHF for Other Domains
- [Contrastive Preference Learning: Learning from Human Feedback without RL](https://arxiv.org/abs/2310.13639).
  - Joey Hejna, Rafael Rafailov, Harshit Sikchi, Chelsea Finn, Scott Niekum, W. Bradley Knox, Dorsa Sadigh. arXiv, 2023.
- [Beyond Reward: Offline Preference-guided Policy Optimization](http://arxiv.org/abs/2305.16217).
  - Yachen Kang, Diyuan Shi, Jinxin Liu, Li He, Donglin Wang. arXiv, 2023.
- [PanGu-Coder2: Boosting Large Language Models for Code with Ranking Feedback](https://arxiv.org/abs/2307.14936)
  - Bo Shen, Jiaxin Zhang, Taihong Chen, Daoguang Zan, Bing Geng, An Fu, Muhan Zeng, Ailun Yu, Jichuan Ji, Jingyang Zhao, Yuenan Guo, Qianxiang Wang. arXiv, 2023.
- [WizardMath: Empowering Mathematical Reasoning for Large Language Models via Reinforced Evol-Instruct](https://arxiv.org/abs/2308.09583)
  - Haipeng Luo, Qingfeng Sun, Can Xu, Pu Zhao, Jianguang Lou, Chongyang Tao, Xiubo Geng, Qingwei Lin, Shifeng Chen, Dongmei Zhang. arXiv, 2023.
- [Shepherd: A Critic for Language Model Generation](https://arxiv.org/abs/2308.04592)
  - Tianlu Wang, Ping Yu, Xiaoqing Ellen Tan, Sean O'Brien, Ramakanth Pasunuru, Jane Dwivedi-Yu, Olga Golovneva, Luke Zettlemoyer, Maryam Fazel-Zarandi, Asli Celikyilmaz. arXiv, 2023.
- [Reinforcement Learning with Human Feedback for Realistic Traffic Simulation](https://arxiv.org/abs/2309.00709)
  - Yulong Cao, Boris Ivanovic, Chaowei Xiao, Marco Pavone. arXiv, 2023.
- [Aligning Large Multimodal Models with Factually Augmented RLHF](https://arxiv.org/abs/2309.14525)
  - Zhiqing Sun, Sheng Shen, Shengcao Cao, Haotian Liu, Chunyuan Li, Yikang Shen, Chuang Gan, Liang-Yan Gui, Yu-Xiong Wang, Yiming Yang, Kurt Keutzer, Trevor Darrell. arXiv, 2023.
- [Motif: Intrinsic Motivation from Artificial Intelligence Feedback](https://arxiv.org/abs/2310.00166)
  - Martin Klissarov, Pierluca D'Oro, Shagun Sodhani, Roberta Raileanu, Pierre-Luc Bacon, Pascal Vincent, Amy Zhang, Mikael Henaff. arXiv, 2023.

### Datasets

- [UltraFeedback: Boosting Language Models with High-quality Feedback](https://arxiv.org/abs/2310.01377)
  - Ganqu Cui, Lifan Yuan, Ning Ding, Guanming Yao, Wei Zhu, Yuan Ni, Guotong Xie, Zhiyuan Liu, Maosong Sun. arXiv, 2023.
- [OpenAssistant Conversations - Democratizing Large Language Model Alignment](https://openreview.net/forum?id=VSJotgbPHF).
  - Andreas Köpf, Yannic Kilcher, Dimitri von Rütte, Sotiris Anagnostidis, Zhi Rui Tam, Keith Stevens, Abdullah Barhoum, Duc Minh Nguyen, Oliver Stanley, Richárd Nagyfi, Shahul ES, Sameer Suri, David Alexandrovich Glushkov, Arnav Varma Dantuluri, Andrew Maguire, Christoph Schuhmann, Huu Nguyen, Alexander Julian Mattick. NeurIPS 2023.

## Blogs/Talks/Reports

### Blogs
- [The N Implementation Details of RLHF with PPO](https://huggingface.co/blog/the_n_implementation_details_of_rlhf_with_ppo)
  - Tianlin Liu, Tianlin Liu, Leandro von Werra. Hugging Face blog, 2023.
- [Illustrating Reinforcement Learning from Human Feedback (RLHF)](https://huggingface.co/blog/rlhf)
  - Nathan Lambert, Hugging Face blog, 2022.
- [Reinforcement Learning for Language Models](https://gist.github.com/yoavg/6bff0fecd65950898eba1bb321cfbd81#reinforcement-learning-for-language-models)
  - Yoav Goldberg, April 2023.
- [RLHF: Reinforcement Learning from Human Feedback](https://huyenchip.com/2023/05/02/rlhf.html)
  - Chip Huyen, 2023.

### Talks
- [Reinforcement Learning from Human Feedback: From Zero to chatGPT](https://www.youtube.com/watch?v=2MBJOuVq380&t=2641s)
- Nathan Lambert, Hugging Face, 2022.
- [Reinforcement Learning from Human Feedback: Progress and Challenges](https://www.youtube.com/watch?v=hhiLw5Q_UFg&t=3206s)
  - John Schulman, OpenAI, 2023.
- [Scalable Oversight for Large Language Models](https://www.youtube.com/watch?v=0tRAhi4g0QA) 
  - Samuel Bowman, New York University, 2023

### Reports

- [Llama 2: Open Foundation and Fine-Tuned Chat Models](https://arxiv.org/abs/2307.09288)
  - Meta, 2023.
- [GPT-4 Technical Report](https://arxiv.org/abs/2303.08774)
  - OpenAI, 2023.

## Open Source Software/Implementations
- [trl](https://github.com/huggingface/trl/tree/main)
  - Train transformer language models with reinforcement learning.
- [OpenRLHF](https://github.com/OpenLLMAI/OpenRLHF)
  - A Ray-based High-performance RLHF framework (for 34b+ models)
