Repository for the Oxford reading group on Theoretical Machine Learning 

## Schedule
+ Week 1: 18/10/2019 [[notes](./notes/low_rank_jac_thm.pdf)] Generalization Guarantees for Neural Networks via Harnessing the Low-rank Structure of the Jacobian ( Samet Oymak, Zalan Fabian, Mingchen Li, Mahdi Soltanolkotabi).
+ Week 2: 25/10/2019 [[notes](./notes/offset_rademacher_complexity.pdf)] Learning with Square Loss: Localization through Offset Rademacher Complexity (Tengyuan Liang, Alexander Rakhlin, Karthik Sridharan).
+ Week 3: 01/11/2019  [[notes](./notes/Double_Descent_for_Reading_Group.pdf)] The generalization error of random features regression: Precise asymptotics and double descent curve (Song Mei and Andrea Montanari).
+ Week 4: 08/11/2019 [[notes]](./notes/badtrainingdata_notes.pdf)  Learning with Bad Training Data via Iterative Trimmed Loss Minimization. (Yanyao Shen, Sujay Sanghavi)
+ Week 6: 22/11/2019  Learning to Optimize via Information-Directed Sampling (Daniel Russo, Benjamin Van Roy).
+ Week 7: 29/11/2019  [[notes]](./notes/compression_based_bounds.pdf) Compression based bound for non-compressed network: unified generalization error analysis of large compressible deep neural network (Taiji Suzuki)

We will meet every Friday from 10am to 11.30am in LG03 but on Oct 25. We will meet in LG04 on that day. 

### Other papers suggested (open to more suggestions)

+ What Can ResNet Learn Efficiently, Going Beyond Kernels? (Zeyuan Allen-Zhu, Yuanzhi Li) https://arxiv.org/abs/1905.10337
   + "We prove  neural  networks  can efficiently  learn  a  notable  class  of  functions,  including  those  defined  by  three-layer  residual networks with smooth activations, without any distributional assumption".
   + "We prove there are simple functions in this class such that with the same number of trainingexamples,  the  test  error  obtained  by  neural  networks  can  bemuch  smaller than any kernel method."

+ Online learning:
   + Matrix-Free Preconditioning in Online Learning (Ashok Cutkosky, Tamas Sarlos) https://arxiv.org/abs/1905.12721 
      + They rely heavily on the coin betting technique
      + They use online learning inside their online learning algorithm to find the optimal value of a parameter.
   + "EFFICIENT ONLINE LEARNING WITH KERNELS FOR ADVERSARIAL LARGE SCALE PROBLEMS" (Jézéquel et al.  2019): https://arxiv.org/pdf/1902.09917.pdf
      + Online Learning with Kernels

+ Algorithms for estimators with samples from heavy tailed distributions i.e. only finite mean and variance:
   + MEAN ESTIMATION WITH SUB-GAUSSIAN RATES INPOLYNOMIAL TIME" (Hopkins et al. 2019) https://arxiv.org/pdf/1809.07425.pdf
   + "Fast Mean Estimation with Sub-Gaussian Rates" (Cherapanamjeri et. al. 2019) https://arxiv.org/pdf/1902.01998.pdf

Other things from here?: Comprehensive list of papers about provable nonconvex methods/algorithms: https://sunju.org/research/nonconvex/ 




