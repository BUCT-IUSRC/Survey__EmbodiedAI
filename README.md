# **Paper list for Embodied AI**
#### We appreciate any useful suggestions for improvement of this paper list or survey from peers. Please raise issues or send an email to tianyu.shen@buct.edu.cn. Thanks for your cooperation!
![](https://cdn.nlark.com/yuque/0/2024/png/38931856/1722944009414-628849b1-20f7-4036-a8e8-f82bd6818040.png#averageHue=%23f7f6f5&clientId=u4b45373f-e541-4&from=paste&height=198&id=u9aa8f1c9&originHeight=247&originWidth=1670&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=55186&status=done&style=none&taskId=udae2de75-ae51-49a1-8849-70e27dcb386&title=&width=1336#averageHue=%23f7f6f5&id=vkLsv&originHeight=247&originWidth=1670&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none)
## 🏠 About
Embodied intelligence aims to create intelligent entities that can learn and evolve autonomously based on the interaction between machines and the physical world, by emphasizing the interaction among the brain, body, and
environment. Currently, the rapid development of multidisciplinary technologies such as machine learning, robotics, and cognitive science has greatly promoted the research and application of embodied intelligence. Existing literature mainly focuses on technical and methodological classifications of embodied intelligence. From a new perspective, this paper
starts from the key problems involved in the research and application of embodied intelligence. By analyzing the general framework of embodied intelligence research, specific research ideas are proposed for the two kernel stages including embodied perception and execution, as well as embodied learning and evolution. Accordingly, detailed explanations of relevant technologies and research progress related to these key issues are provided. In addition, typical applications in mobile robots, bionic robots, and parallel robotics are exploited to illustrate how embodied intelligence inspires practical
robot systems in terms of perception and understanding, control and decision-making, interaction and learning. Finally, the prospects of embodied intelligence is discussed, considering the importance and potential of virtual-real fusion data intelligence, foundation intelligence, and parallel intelligence. This paper is expected to provide new inspiration and ideas for scholars and practitioners in related fields.
## 📚 Table of Contents

- [Surveys & Perspectives](#surveys--perspectives)
- [具身感知与执行](#具身感知与执行-)  
 &emsp;[环境与任务感知](#环境与任务感知)  
 [行为规划与控制](#行为规划与控制)  
 [具身模拟与AIGC](#具身模拟与AIGC)   
- [具身学习与进化](#具身学习与进化-)  
 [基础模型](#基础模型)  
 [增量学习](#增量学习)  
 [强化学习](#强化学习)    
- [多智能体协同](#多智能体协同-)
- [具身智能系统](#具身智能系统-)  
 [移动机器人](#移动机器人)  
 [仿生机器人](#仿生机器人)  
 [平行机器人](#平行机器人)  
 [特种机器人](#特种机器人)  
## Surveys & Perspectives[🔝](#-table-of-contents)

- [2]**Embodied intelligence weaves a better future. **Nature Machine Intelligence, 2020, 2(11): 663-664**.**Jin D, Zhang L.[[page]](https://www.nature.com/articles/s42256-020-00250-6)
- [5]**Evolving embodied intelligence from materials to machines**. Nature Machine Intelligence, 2019, 1(1): 12-19.Howard D, Eiben A E, Kennedy D F, et al. [[page]](https://www.nature.com/articles/s42256-018-0009-9)
- [6]**The journey/DAO/TAO of embodied intelligence: From large models to foundation intelligence and parallel intelligence**. IEEE/CAA Journal of Automatica Sinica, 2024, 11(6): 1313-1316.[[page]](https://ieeexplore.ieee.org/abstract/document/10539310/)
- [7]**Embodied intelligent driving: Concepts, methods, the state of the art and beyond. Chinese Journal of Intelligent Science and Technology**, 2024, 6(1): 17-32.Shen Tian-Yu, Li Zhi-Wei, Fan Li-Li, Zhang Ting-Zhen, Tang Dan-Dan, Zhou Mei-Hua, Liu Hua-Ping, Wang Kun-Feng.[[page]](https://www.infocomm-journal.com/znkx/EN/10.11959/j.issn.2096-6652.202404)
- [10]**Improving performance of robots using human-inspired approaches: A survey. Science China Information Sciences, **2022, 65(12): 221201**.**Qiao H, Zhong S, Chen Z, et al.[[page]](https://link.springer.com/article/10.1007/s11432-022-3606-1)
- [11]**AI robots and humanoid AI: Review, perspectives and directions. **2024.Cao L.[[page]](https://datasciences.org/publication/Humanoid-AI.pdf)
- [12]**A survey of embodied AI: From simulators to research tasks. IEEE Transactions on Emerging Topics in Computational Intelligence**, 2022, 6(2): 230-244.Duan J, Yu S, Tan H L, et al.[[page]](https://ieeexplore.ieee.org/abstract/document/9687596/)
- [13]**基于形态的具身智能研究: 历史回顾与前沿进展**. 自动化学报, 2023, 49(6):1131−1154.刘华平, 郭迪, 孙富春, 张新钰. [[page]](http://www.aas.net.cn/cn/article/doi/10.16383/j.aas.c220564?viewType=HTML&utm_source=TrendMD&utm_medium=cpc&utm_campaign=Acta_Automatica_Sinica_TrendMD_0)
- [69]**Evolutionary robotics: the Sussex approach. **Robotics and Autonomous Systems, 1997, 20(2-4): 205-224.Harvey I, Husbands P, Cliff D, et al.[[page]](https://www.sciencedirect.com/science/article/pii/S092188909600067X)
## 具身感知与执行[🔝](#-table-of-contents)
### 环境与任务感知

- [2]**Embodied intelligence weaves a better future. **Nature Machine Intelligence, 2020, 2(11): 663-664**.**Jin D, Zhang L.[[page]](https://www.nature.com/articles/s42256-020-00250-6)
- [18]**Planning-oriented autonomous driving**. In: Proceeding of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2023: 17853-17862.Hu Y, Yang J, Chen L, et al.
- [19]**Multimodal virtual point 3D detection**. Advances in Neural Information Processing Systems, 2021, 34: 16494-16507.Yin T, Zhou X, Krähenbühl P. 
- [20]**Sparse fuse dense:Towards high quality 3D detection with depth completion**[C]// Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2022: 5418-5427.Wu X, Peng L, Yang H, et al.
- [21]**Virtual sparse convolution for multimodal 3D object detection[C]**// Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2023: 21653-21662.Wu H, Wen C, Shi S, et al. 
- [22]**Bevfusion: Multi-task multi-sensor fusion with unified bird’s-eye view representation**[C]// Proceedings of the IEEE International Conference on Robotics and Automation, 2023: 2774-2781.Liu Z, Tang H, Amini A, et al. 
- [23]**BEV-CFKT: A LiDAR-camera cross-modality-interaction fusion and knowledge transfer framework with transformer for bev 3D object detection. **Neurocomputing, 2024, 582: 127527.Wei M, Li J, Kang H, et al. 
- [24]**DeepFusion: A robust and modular 3D object detector for LiDARs, cameras and radars**[C]// Proceedings of the IEEE/RSJ International Conference on Intelligent Robots and Systems, 2022: 560-567.Drews F, Feng D, Faion F, et al.
- [25]**AMMF: Attention-based multi-phase multi-task fusion for small contour object 3D detection.** IEEE Transactions on Intelligent Transportation Systems, 2022, 24(2): 1692-1701.Xie B, Yang Z, Yang L, et al. 
- [26]**Probabilistic 3D multi-modal, multi-object tracking for autonomous driving.** In: Proceeding of the IEEE International Conference on Robotics and Automation, 2021: 14227-14233.Chiu H, Li J, Ambruş R, et al.
- [27]**ACF-Net: Asymmetric cascade fusion for 3D detection with LiDAR point clouds and images. **IEEE Transactions on Intelligent Vehicles (Early Access),2023, 1-12.Tian Y, Zhang X, Wang X, et al.
- [28]**FusionFormer: A multi-sensory fusion in bird’s-eye-view and temporal consistent transformer for 3D objection.** arXiv preprint arXiv:2309.05257, 2023.Hu C, Zheng H, Li K, et al.
- [29]**Prototypical pseudo label denoising and target structure learning for domain adaptive semantic segmentation.** In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition, 2021, 12414-12424.Zhang P, Zhang B, Zhang T, et al. 
- [30]**“Dranet: Disentangling representation and adaptation networks for unsupervised cross-domain adaptation.”** Proceedings of the IEEE/CVF conference on computer vision and pattern recognition, 2021, 15252-15261.Lee S, Cho S, Im S.
- [31]**Unsupervised domain adaptation of object detectors: A survey**[J]. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023.Oza P, Sindagi V A, Sharmini V V, Patel V M.
- [32]**Domain-adversarial training of neural networks**[J]. Journal of Machine Learning Research, 2016, 17(59): 1-35.Ganin Y, Ustinova E, Ajakan H, et al.
- [33]**Exploring object relation in mean teacher for cross-domain detection[**C]//IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2019: 11457-11466.Cai Q, Pan Y, Ngo C W, Tian X, et al.
- [34]**Droid: Driver-centric risk object identification.** IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023, 45(11): 13683-13698.Li C, Chan S H, Chen Y T.
- [35]**A superposition assessment framework of multi-source traffic risks for mega-events using risk field model and time-series generative adversarial networks.** IEEE Transactions on Intelligent Transportation Systems, 2023, 24(11): 12736-12753.Cheng Z, Lu J, Ding H, et al.
- [36]**Probabilistic risk metric for highway driving leveraging multi-modal trajectory predictions.** IEEE Transactions on Intelligent Transportation Systems, 2022, 23(10): 19399-19412.Wang X, Alonso M J, Wang M.
- [37]**A multivariate-based conflict prediction model for a brazilian freeway. **Accident Analysis & Prevention, 2017, 98: 295-302.Caleffi F, Anzanello M J, Cybis H B B.
### 行为规划与控制

- [45]**A formal basis for the heuristic determination of minimum cost paths. **IEEE Transactions on Systems Science and Cybernetics, 1968, 4(2): 100-107.Hart P E, Nilsson N J, Raphael B.
- [46]**Sampling-based algorithms for optimal motion planning.** The International Journal of Robotics Research, 2011, 30(7): 846-894.Karaman S, Frazzoli E. 
- [47]**D* lite.**In: Proceeding of the Eighteenth National Conference on Artificial Intelligence，2002: 476-483.Koenig S, Likhachev M.
- [48]**Adaptation in natural and artificial systems: An introductory analysis with applications to biology**, control, and artificial intelligence. MIT press, 1992.Holland J H.
- [49]**Particle swarm optimization. In: Proceeding of the ICNN’95-International Conference on Neural Networks**, 1995: 1942-1948.Kennedy J, Eberhart R.
- [50]**Practical search techniques in path planning for autonomous driving.** Ann Arbor, 2008, 1001(48105): 18-80.Dolgov D, Thrun S, Montemerlo M, et al.
- [51]**Kinodynamic RRT*: Asymptotically optimal motion planning for robots with linear dynamics.** In: Proceeding of the 2013 IEEE international conference on robotics and automation, 2013: 5054-5061.Webb D J, Van Den Berg J.
- [52]**On Actor-Critic Algorithms. Society for Industrial and Applied Mathematics**, 2003.Konda V R, Tsitsiklis J N.
- [53]**Technical Note: Q-Learning**, 1992.Watkins C J C H. P.
- [54]**PILCO: A Model-based and data-efficient approach to policy search. **In: Proceeding of the 28th International Conference on Machine Learning, 2011.Deisenroth M P, Rasmussen C E.
- [55]**Generative adversarial lmitation learning**. 2016.Ho J, Ermon S.
- [56]**A review of PID control, tuning methods and applications.** International Journal of Dynamics and Control, 2021, 9: 818-827.Borase R P, Maghade D K, Sondkar S Y, et al.
- [57]**On the role of regularization in direct data-driven LQR control**. 2022 IEEE 61st Conference on Decision and Control (CDC). IEEE, 2022: 1091-1098.Dörfler F, Tesi P, De Persis C. 
- [58]**Robust data-driven state-feedback design. 2020 American Control Conference (ACC).** IEEE, 2020: 1532-1538.Berberich J, Koch A, Scherer C W, et al.
- [59]**Safe and fast tracking on a robot manipulator: Robust mpc and neural network control. **IEEE Robotics and Automation Letters, 2020, 5(2): 3050- 3057.Nubert J, Köhler J, Berenz V, et al. 
- [60]**Adaptive neural network control for a class of nonlinear systems with function constraints on states.** IEEE Transactions on Neural Networks and Learning Systems, 2021, 34(6): 2732-2741.Liu Y J, Zhao W, Liu L, et al.
- [61]**Interval type 2 fuzzy logic control for energy management of hybrid electric autonomous vehicles.** IEEE Transactions on Intelligent Vehicles, 2020, 6(2): 210-220.Phan D, Bab-Hadiashar A, Fayyazi M, et al.
- [62]**Cooperative co-evolution with differential grouping for large scale optimization.** IEEE Transactions on Evolutionary Computation, 2013, 18(3): 378- 393.Omidvar M N, Li X, Mei Y, et al.
- [63]**Particle swarm optimization algorithm and its applications: a systematic review**. Archives of Computational Methods in Engineering, 2022, 29(5): 2531-2561.Gad A G. 
- [64]**Distributed optimal control for multi-agent trajectory optimization.** Automatica, 2014, 50(1): 149-154.Foderaro G, Ferrari S, Wettergren T A. 
- [65]**A distributional perspective on reinforcement learning.** In: Proceeding of the International Conference on Machine Learning, 2017: 449-458.Bellemare M G, Dabney W, Munos R. 
- [66]**Finite-time consensus tracking neural network FTC of multi-agent systems.** IEEE Transactions on Neural Networks and Learning Systems, 2020, 32(2): 653-662.Dong G, Li H, Ma H, et al.
- [67]**Leader-following consensus of multi-agent systems under antagonistic networks. **Neurocomputing. 2020 Nov 6;413:339-47.Wang Q, Liu K, Wang X, Wu L, Lü J.
- [68]**Virtual target guidance-based distributed model predictive control for formation control of multiple UAVs**. Chinese Journal of Aeronautics, 2020, 33(3): 1037-1056.Zhihao C, Longhong W, Jiang Z, Kun W, Yingxun W.
### 具身模拟与AIGC

- [38]**High-resolution image synthesis with latent diffusion models.**Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2022: 10684-10695.Rombach R, Blattmann A, Lorenz D, et al.
- [39]**Photorealistic text-to image diffusion models with deep language understanding.** Advances in neural information processing systems, 2022, 35: 36479-36494.Saharia C, Chan W, Saxena S, et al.
- [40]**Zero-shot text-to image generation. International conference on machine learning.** Pmlr, 2021: 8821-8831.Ramesh A, Pavlov M, Goh G, et al.
- [41]**Hierarchical text-conditional image generation with clip latents.** arXiv preprint arXiv:2204.06125, 2022, 1(2): 3.Ramesh A, Dhariwal P, Nichol A, et al.
- [42]**A generalist agent**[J]. arXiv preprint arXiv:2205.06175, 2022.Reed S, Zolna K, Parisotto E, et al.
- [43]**Giraffe: Representing scenes as compositional generative neural feature fields**, Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2021: 11453-11464.Niemeyer M, Geiger A.
- [44]**Physically Embodied Gaussian Splatting: Embedding Physical Priors into a Visual 3D World Model For Robotics**, Conference on Robot Learning. 2023 (7th).Abou-Chakra J, Rana K, Dayoub F, et al.
- [145]**Palm-e: An embodied multimodal language model**. arXiv preprint arXiv:2303.03378, 2023.Driess D, Xia F, Sajjadi M S M, et al.
- [146]**Alfred: A benchmark for interpreting grounded instructions for everyday tasks**. In: Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2020: 10740-10749.Shridhar M, Thomason J, Gordon D, et al. 
- [147]**Visual room rearrangement.** In: Proceeding of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2021: 5922-5931.Weihs L, Deitke M, Kembhavi A, et al.
- [148]**Rearrangement: A challenge for embodied AI**. arXiv preprint arXiv:2011.01975, 2020.Batra D, Chang A X, Chernova S, et al.
- [149]**Igibson 1.0: A simulation environment for interactive tasks in large realistic scenes**. In: Proceeding of the International Conference on Intelligent Robots and Systems, 2021: 7520-7527.Shen B, Xia F, Li C, et al.
- [150]**Igibson 2.0: Objectcentric simulation for robot learning of everyday household tasks**. arXiv preprint arXiv:2108.03272, 2021.Li C, Xia F, Martín-Martín R, et al.
- [151]**Habitat: A platform for embodied AI research.** In: Proceeding of the IEEE/CVF International Conference on Computer Vision, 2019: 9339-9347.Savva M, Kadian A, Maksymets O, et al.
- [152]**Habitat-matterport 3D dataset (HM3D): 1000 large-scale 3D environments for embodied AI.** arXiv preprint arXiv:2109.08238, 2021.Ramakrishnan S K, Gokaslan A, Wijmans E, et al.
- [153]**Multion: Benchmarking semantic map memory using multi-object navigation.** Advances in Neural Information Processing Systems, 2020, 33: 9700-9712.Wani S, Patel S, Jain U, et al.
- [154]**Behavior-1k: A benchmark for embodied AI with 1,000 everyday activities and realistic simulation.** In: Proceeding of the Conference on Robot Learning, 2023: 80-93.Li C, Zhang R, Wong J, et al.
- [155]**Behavior: Benchmark for everyday household activities in virtual, interactive, and ecological environments.** In: Proceeding of the Conference on Robot Learning, 2022: 477-490.Srivastava S, Li C, Lingelbach M, et al. 
- [156]**Ai2-thor: An interactive 3d environment for visual AI.** arXiv preprint arXiv:1712.05474, 2017.Kolve E, Mottaghi R, Han W, et al. 
- [157]**Threedworld: A platform for interactive multi-modal physical simulation.** arXiv preprint arXiv:2007.04954, 2020.Gan C, Schwartz J, Alter S, et al.
- [158]**The threedworld transport challenge: A visually guided task-and-motion planning benchmark towards physically realistic embodied AI.** In: Proceeding of the 2022 International Conference on Robotics and Automation, 2022: 8847-8854.Gan C, Zhou S, Schwartz J, et al. 
- [159]**Habitat 2.0: Training home assistants to rearrange their habitat.** Advances in Neural Information Processing Systems, 2021, 34: 251-266.Szot A, Clegg A, Undersander E, et al. 
## 具身学习与进化 [🔝](#-table-of-contents)
### 基础模型

- [6]The journey/DAO/TAO of embodied intelligence: From large models to foundation intelligence and parallel intelligence. IEEE/CAA Journal of Automatica Sinica, 2024, 11(6): 1313-1316.Shen T, Sun J, Kong S, et al.
- [9]**LM-Nav: Robotic navigation with large pre-trained models of language, vision, and action.** In: Proceeding of the Conference on Robot Learning, 2023: 492-504.Shah D, Osiński B, Levine S.
- [111]**Voxposer: Composable 3D value maps for robotic manipulation with language models.** arXiv preprint arXiv:2307.05973, 2023.Huang W, Wang C, Zhang R, et al.
- [160]**Accurate medium-range global weather forecasting with 3D neural networks.** Nature, 2023, 619(7970): 533-538.Bi K, Xie L, Zhang H, et al.
- [161]**The emergence of intelligent enterprises: From CPS to CPSS**. IEEE Intelligent Systems, 2010, 25(4): 85-88.Wang F Y. 
- [162]  **Cyber-physical-social systems: The state of the art and perspectives**. IEEE Transactions on Computational Social Systems, 2018, 5(3): 829-840.Zhang J J, Wang F Y, Wang X, et al.
### 增量学习

- [70]**Overcoming catastrophic forgetting in neural networks.** Proceedings of the National Academy of Sciences, 2017, 114(13): 3521-3526.Kirkpatrick J, Pascanu R, Rabinowitz N, et al.
- [71]**Rotate your networks: Better weight consolidation and less catastrophic forgetting.** In: Proceeding of the International Conference on Pattern Recognition, 2018: 2262-2268.Liu X, Masana M, Herranz L, et al. 
- [72]**Re-evaluating continual learning scenarios: A categorization and case for strong baselines.** arXiv preprint arXiv:1810.12488, 2018.Hsu Y C, Liu Y C, Ramasamy A, et al.
- [73]**Distilling the knowledge in a neural network.** arXiv preprint arXiv:1503.02531, 2015.Hinton G, Vinyals O, Dean J. 
- [74]**Learning a unified classifier incrementally via rebalancing.** In: Proceeding of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2019: 831-839.Hou S, Pan X, Loy C C, et al.
- [75]**End-to-end incremental learning**. In: Proceeding of the European Conference on Computer Vision, 2018: 233-248.Castro F M, Marín-Jiménez M J, Guil N, et al.
- [76]**Class-incremental learning via deep model consolidation**. In: Proceeding of the IEEE/CVF Winter Conference on Applications of Computer Vision, 2020: 1131-1140.Zhang J, Zhang J, Ghosh S, et al.
- [77]**PODNet: Pooled outputs distillation for small-tasks incremental learning**. In: Proceeding of the European Conference on Computer Vision, 2020: 86-102.Douillard A, Cord M, Ollion C, et al.
- [78]**类别增量学习研究进展和性能评价**. 自动化学报, 2023, 49(3): 635-660.朱飞, 张煦尧, 刘成林. 
- [79]**Topology-preserving classincremental learning. **In: Proceeding of the European Conference on Computer Vision, 2020: 254-270.Tao X, Chang X, Hong X, et al. 
- [80]**Small-task incremental learning.** ArXiv abs/2004.13513 (2020): n. pag.Douillard A, Cord M, Ollion C, et al.
- [81]**Icarl: Incremetal classifier and representation learning**. In: Proceeding of the IEEE Conference on Computer Vision and Pattern Recognition, 2017: 2001-2010.Rebuffi S A, Kolesnikov A, Sperl G, et al.
- [82]**Generative adversarial networks**. Communications of the ACM, 2020, 63(11): 139-144.Goodfellow I, Pouget-Abadie J, Mirza M, et al. 
- [83]**Latent replay for real-time continual learning.** In: Proceeding of the International Conference on Intelligent Robots and Systems, 2020: 10203-10209.Pellegrini L, Graffieti G, Lomonaco V, et al.
- [84]**Large scale incremental learning**. In: Proceeding of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2019: 374-382.Wu Y, Chen Y, Wang L, et al.
- [85]**Overcoming catastrophic forgetting with hard attention to the task**. In: Proceeding of the International Conference on Machine Learning, 2018: 4548- 4557.
- [86]**Self-sustaining representation expansion for non-exemplar class-incremental learning. **In: Proceeding of the IEEE/CVF Conference on Computer Vision and Pattern Recognition，2022: 9296-9305.Zhu K, Zhai W, Cao Y, et al.
### 强化学习

- [13]
- [87]**An overview of reservoir computing: Theory, applications and implementations.** In: Proceedings of the 15th European Symposium on Artificial Neural Networks, 2007: 471-482.Schrauwen B, Verstraeten D, Van Campenhout J.
- [88]**The role of feedback in morphological computation with compliant bodies.** Biological Cybernetics, 2012, 106: 595-613.Hauser H, Ijspeert A J, Füchslin R M, et al. 
- [89]**Design and control of compliant tensegrity robots through simulation and hardware validation**. Journal of the Royal Society Interface, 2014, 11(98): 20140520.Caluwaerts K, Despraz J, Işçen A, et al.
- [90]**Developing an embodied gait on a compliant quadrupedal robot.** In: Proceeding of the International Conference on Intelligent Robots and Systems, 2015: 4486-4491.Degrave J, Caluwaerts K, Dambre J, et al.
- [91]**Stochastic optimal control methods for investigating the power of morphological computation.** Artificial Life, 2013, 19(1): 115-131.Rückert E A, Neumann G. 
- [92]**Algorithmic design for embodied intelligence in synthetic cells.** IEEE Transactions on Automation Science and Engineering, 2020, 18(3): 864-875.Pervan A, Murphey T D.
- [93]**Target-driven visual navigation in indoor scenes using deep reinforcement learning.** In: Proceeding of the 2017 IEEE International Conference on Robotics and Automation, 2017: 3357-3364.Zhu Y, Mottaghi R, Kolve E, et al.
- [94]Hardware conditioned policies for multi-robot transfer learning. Advances in Neural Information Processing Systems, 2018, 31.Chen T, Murali A, Gupta A. 
- [95]**Nervenet: Learning structured policy with graph neural networks.** In: Proceeding of the International Conference on Learning Representations, 2018.Wang T, Liao R, Ba J, et al. 
- [96]S**nowflake: Scaling GNNs to high-dimensional continuous control via parameter freezing**. Advances in Neural Information Processing Systems, 2021, 34: 23983-23992.Blake C, Kurin V, Igl M, et al. 
- [97]**Learning to control self-assembling morphologies: A study of generalization via modularity. **Advances in Neural Information Processing Systems, 2019, 32.Pathak D, Lu C, Darrell T, et al.
- [98]**Data-efficient co-adaptation of morphology and behaviour with deep reinforcement learning.** In: Proceeding of the Conference on Robot Learning, 2020: 854-869.Luck K S, Amor H B, Calandra R.
- [99]**Data-efficient co-adaptation of morphology and behaviour with deep reinforcement learning**. ArXiv abs/1911.06832 (2019): n. pag.Luck K S, Amor H B, Calandra R.
- [100]**Reinforcement learning for improving agent design.** Artificial Life, 2019, 25(4): 352-365.Ha D.
## 多智能体协同 [🔝](#-table-of-contents)

- [101]**Asynchronous methods for deep reinforcement learning**. In: Proceeding of the International Conference on Machine Learning, 2016: 1928-1937.Mnih V, Badia A P, Mirza M, et al.
- [102]**A multi-objective deep reinforcement learning framework.** Engineering Applications of Artificial Intelligence, 2020, 96: 103915.Nguyen T T, Nguyen N D, Vamplew P, et al.
- [103]**Learning from an automated training agent. Adaptation and Learning in Multiagent Systems**. Springer Verlag, 1996: 195.Clouse J A.
- [104]**Accelerating reinforcement learning through implicit imitation**. Journal of Artificial Intelligence Research, 2003, 19: 569-629.Price B, Boutilier C.
- [105]**Double Q-learning. Advances in Neural Information Processing Systems**, 2010, 23.Hasselt H. 
- [106]**Deep attention recurrent Q-network**. arXiv preprint arXiv:1512.01693, 2015.Sorokin I, Seleznev A, Pavlov M, et al. 
- [107]**Multiagent learning using a variable learning rate**. Artificial Intelligence, 2002, 136(2): 215-250.Bowling M, Veloso M.
- [108]**An algorithm for distributed reinforcement learning in cooperative multi-agent systems**. In: Proceeding of the Seventeenth International Conference on Machine Learning, 2000: 535-542.Lauer M, Riedmiller M A. 
- [109]**Multi-agent reinforcement learning in sequential social dilemmas.** arXiv preprint arXiv:1702.03037, 2017.Leibo J Z, Zambaldi V, Lanctot M, et al.
## 具身智能系统 [🔝](#-table-of-contents)
### 移动机器人

- [110]**Robot operating system 2: Design, architecture, and uses in the wild**. Science Robotics, 2022, 7(66): eabm6074.Macenski S, Foote T, Gerkey B, et al.
- [113]**Voxposer: Composable 3D value maps for robotic manipulation with language models**. arXiv preprint arXiv:2307.05973, 2023.Huang W, Wang C, Zhang R, et al.
- [114]**Design-to-test approach for programmable controllers in safety-critical automation systems**. IEEE Transactions on Industrial Informatics, 2020, 16(10): 6499-6508.Ma C, Provost J.
- [115]Binocular vision-based poleshaped obstacle detection and ranging study. Applied Sciences, 2023, 13(23): 12617.Cai L, Zhou C, Wang Y, et al.
- [116]**Reimagining an autonomous vehicle**. arXiv preprint arXiv:2108.05805, 2021.Hawke J, Badrinarayanan V, Kendall A, et al.
- [117]**Scalability in perception for autonomous driving: Waymo open dataset**. In: Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2020: 2446-2454.Sun P, Kretzschmar H, Dotiwalla X, et al.
- [118]**End-to-end autonomous driving: Challenges and frontiers.** arXiv preprint arXiv:2306.16927, 2023.Chen L, Wu P, Chitta K, et al.
- [119]**Mobile aloha: Learning bimanual mobile manipulation with low-cost whole-body teleoperation**. arXiv preprint arXiv:2401.02117, 2024.Fu Z, Zhao T Z, Finn C.
- [120]**Modelling time efficiency of cobot-supported kit preparation.** The International Journal of Advanced Manufacturing Technology, 2020, 106: 2227-2241.Fager P, Calzavara M, Sgarbossa F.
- [121]**基于具身智能的移动操作机器人系统发展研究**. 中国工程科学, 2024, 26(01): 139-148.兰沣卜, 赵文博, 朱凯, 等.
- [122]**Agent as cerebrum, controller as cerebellum: Implementing an embodied lmm-based agent on drones**. arXiv preprint arXiv:2311.15033, 2023.Zhao H, Pan F, Ping H, et al.
### 仿生机器人

- [123]**Integrated tracking control of an underwater bionic robot based on multimodal motions.** IEEE Transactions on Systems, Man, and Cybernetics: Systems, 2023, 54(3): 1599-1610.Wang J, Wu Z, Zhang Y, et al.
- [124]**NeuroDog: Quadruped embodiment using neural networks. **In：Proceedings of the ACM on Computer Graphics and Interactive Techniques, 2023: 1-19.Egan D, Cosker D, McDonnell, R.
- [125]**Advancements in humanoid robots: A comprehensive review and future prospects**. IEEE/CAA Journal of Automatica Sinica, 2024, 11(2): 301-328.Tong Y, Liu H, Zhang Z.Tong Y, Liu H, Zhang Z.
- [126]**Learning agile soccer skills for a bipedal robot with deep reinforcement learning.** Science Robotics, 2024, 9(89): eadi8022.Haarnoja T, Moran B, Lever G, et al. 
- [127]**Bringing robots home: The rise of AI robots in consumer electronics**. arXiv preprint arXiv:2403.14449, 2024.Dong H, Liu Y, Chu T, Saddik A E. 
- [128]**Predictive control of zero moment point for terrain robot kinematics**. Materials Today: Proceedings, 2023, 2023(80): 122-127.
- [129]**A survey of brain-inspired intelligent robots: Integration of vision, decision, motion control, and musculoskeletal systems**. IEEE Transactions on Cybernetics, 2021, 52(10): 11267-11280.Qiao H, Chen J, Huang X.
- [130]**Brain-inspired intelligent robotics: Theoretical analysis and systematic application.** Machine Intelligence Research, 2023, 20(1): 1-18.Qiao H, Wu Y X, Zhong S L, et al. 
- [131]**Design of topology optimized compliant legs for bio-inspired quadruped robots**. Scientific Reports, 2023, 13(1): 4875.Sun Y, Zong C, Pancheri F, et al.
- [132]**A study on quadruped mobile robots.** Mechanism and Machine Theory, 2023, 190: 105448.Taheri H, Mozayani N.
- [133]**Skin barrier reinforcement effect assessment of a spot-on based on natural ingredients in a dog model of tape stripping**. Veterinary Sciences, 2023, 9(8): 390.Idée A, Mosca M, Pin D.
- [134]**Multi-expert learning of adaptive legged locomotion**. Science Robotics, 2020, 5(49): eabb2174.Yang C, Yuan K, Zhu Q, et al. 
- [135]**Sailing through point clouds: Safe navigation using point cloud based control barrier functions**. arXiv preprint arXiv:2403.18206, 2024.Dai B, Khorrambakht R, Krishnamurthy P, et al.
- [136]**Modality plug-and-play: Elastic modality adaptation in multimodal llms for embodied AI**. arXiv preprint arXiv:2312.07886, 2023.Huang K, Yang B, Gao W.
- [137]**Three-dimensional kinematic modeling of helix-forming lamina-emergent soft smart actuators based on electroactive polymers**. IEEE Transactions on Systems, Man, and Cybernetics: Systems, 2017, 47(9): 2562-2573.Mutlu R, Alici G, Li W.
- [138]**Punyo-1: Soft tactile-sensing upper-body robot for large object manipulation and physical human interaction**. In: Proceedings of the 2022 IEEE 5th International Conference on Soft Robotics, 2022: 844-851.Goncalves A, Kuppuswamy N, Beaulieu A, et al. 
- [139]**Active entanglement enables stochastic, topological grasping.** Proceedings of the National Academy of Sciences, 2022, 119(42): e2209819119.Becker K, Teeple C, Charles N, et al. 
- [140]**Octopus-inspired sensorized soft arm for environmental interaction. **Science Robotics, 2023, 8(84): eadh7852.
- [141]**A concise guide to modelling the physics of embodied intelligence in soft robotics**. Nature Reviews Physics, 2022, 4(9): 595-610.Mengaldo G, Renda F, Brunton S L, et al.
### 平行机器人

- [142]**平行机器人与平行 无人系统: 框架、结构、过程、平台及其应用**. 自动化学报, 2017, 43(2): 161−175.）白天翔, 王帅, 沈震, 曹东璞, 郑南宁, 王飞跃.
- [143]**机器人的未来发展: 从工业自动化到知识自动化**. 科技导报, 2015, 33(21): 39−44.王飞跃.
- [144]**软件定义的系统与知识自动化: 从牛顿到默顿的平行升华**. 自动化学报, 2015, 41(1): 1−8.王飞跃.
### 特种机器人
 coming soon
## 📰 Citation
Submission in progress
## 👏 Acknowledgements
