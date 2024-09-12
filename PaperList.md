### Topic 1: Distributed Learning and  Accelration

  1. Unbiased Compression Saves Communication in Distributed Optimization: When and How Much
https://arxiv.org/abs/2305.16297

  2. Varuna: scalable, low-cost training of massive deep learning model
https://arxiv.org/abs/2111.04007

3. Decentralized Training of Foundation Models in Heterogeneous Environments
https://arxiv.org/abs/2206.01288

4. Communication-efficient Distributed Learning for Large Batch Optimization
https://icml.cc/virtual/2022/spotlight/17002

5. FwdLLM: Efficient Federated Finetuning of Large Language Models with Perturbed Inferences
https://www.usenix.org/conference/atc24/presentation/xu-mengwei

6. MegaBlocks: Efficient Sparse Training with Mixture-of-Experts
https://proceedings.mlsys.org/paper_files/paper/2023/hash/5a54f79333768effe7e8927bcccffe40-Abstract-mlsys2023.html

### Topic 2: Federated Learning 


1. FLuID: Mitigating Stragglers in Federated Learning Using Invariant Dropout
https://arxiv.org/pdf/2307.02623.pdf

2. DFRD: Data-Free Robustness Distillation for Heterogeneous Federated Learning
https://arxiv.org/abs/2309.13546

3. Multimodal Federated Learning via Contrastive Representation Ensemble
https://openreview.net/forum?id=Hnk1WRMAYqg

4. PrE-Text: Training Language Models on Private Federated Data in the Age of LLMs
https://arxiv.org/abs/2406.02958

5. FedMBridge: Bridgeable Multimodal Federated Learning
https://arxiv.org/abs/2402.15858

<!--Tree-Ring Watermarks: Fingerprints for Diffusion Images that are Invisible and Robust
https://arxiv.org/abs/2305.20030
- Diffusion Models and Semi-Supervised Learners Benefit Mutually with Few Labels
https://arxiv.org/abs/2302.10586
-->

6.  SiloFuse: SiloFuse: Cross-silo Synthetic Data Generation with Latent Tabular Diffusion Model
https://arxiv.org/abs/2404.03299

### Topic 3: Attacks and Defenses in ML Systems

1. Understanding and Mitigating Copying in Diffusion Models
https://arxiv.org/pdf/2210.10880.pdf
- Learning to Invert: Simple Adaptive Attacks for Gradient Inversion in Federated Learning
https://arxiv.org/abs/2210.10880

2. Privacy Attacks in Decentralized Learning
https://proceedings.mlr.press/v235/mrini24a.html

3. The Stronger the Diffusion Model, the Easier the Backdoor: 
https://arxiv.org/html/2401.04136v2

4. Lockdown: Backdoor Defense for Federated Learning with Isolated Subspace Training
 https://proceedings.neurips.cc/paper_files/paper/2023/hash/2376f25ef1725a9e3516ee3c86a59f46-Abstract-Conference.html
 
 5.  Stealing part of a production language model
  https://arxiv.org/pdf/2403.06634

6. DeTA: Minimizing Data Leaks in Federated Learning via Decentralized and Trustworthy Aggregation
https://gzs715.github.io/pubs/DETA_EUROSYS24.pdf

### Topic 4: Scalable Inference and Fine-tuning

1. QLORA: Efficient Finetuning of Quantized LLMs
https://openreview.net/pdf?id=OUIFPHEgJU

2. MatFormer: Nested Transformer for Elastic Inference
https://arxiv.org/abs/2310.07707

3. Efficient Memory Management for Large Language Model Serving with PagedAttention
https://arxiv.org/abs/2309.06180

4. PUZZLE: Efficiently Aligning Large Language Models through Light-Weight Context Switch
https://www.usenix.org/conference/atc24/presentation/lei

5. Model Selection for Latency-Critical Inference Serving
https://cs.stanford.edu/people/dmendo/papers/eurosys24-final.pdf

6. Optimus: Warming Serverless ML Inference via Inter-Function Model Transformation
  https://tik-db.ee.ethz.ch/file/aac002beed0a1a9c9640746841d50c40/



<!--
###  Topic 1: Distributed machine learning -- Going parallel

- Asynchronous SGD Beats Minibatch SGD Under Arbitrary Delays https://proceedings.neurips.cc/paper_files/paper/2022/hash/029df12a9363313c3e41047844ecad94-Abstract-Conference.html

- Varuna: scalable, low-cost training of massive deep learning models https://dl.acm.org/doi/abs/10.1145/3492321.3519584

- DRAGONN: Distributed Randomized Approximate Gradients of Neural Networks https://proceedings.mlr.press/v162/wang22aj.html

- Communication-efficient Distributed Learning for Large Batch Optimization&nbsp; https://icml.cc/virtual/2022/spotlight/17002

###  Topic 2: Federated learning -- Going decentralized

- Communication-Efficient Adaptive Federated Learning https://icml.cc/virtual/2022/spotlight/18274

- VF-PS: How to Select Important Participants in Vertical Federated Learning, Efficiently and Securely? https://nips.cc/virtual/2022/poster/53772

- Disentangled Federated Learning for Tackling Attributes Skew via Invariant Aggregation and Diversity Transferring https://icml.cc/virtual/2022/spotlight/16882&nbsp;&nbsp;

- Federated Learning with Label Distribution Skew via Logits Calibration&nbsp; https://icml.cc/virtual/2022/spotlight/16222

###  Topic 3: Accelerating machine learning system-- Going specialized

- Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning&nbsp; https://www.usenix.org/conference/osdi22/presentation/zheng-lianmin

- Out-of-order backprop: an effective scheduling technique for deep learning https://dl.acm.org/doi/abs/10.1145/3492321.3519563

- Resource-Adaptive Federated Learning with All-In-One Neural Composition https://proceedings.mlsys.org/paper/2020/hash/f7e6c85504ce6e82442c770f7c8606f0-Abstract.html &nbsp;

- XTC: Extreme Compression for Pre-trained Transformers Made Simple and Efficient&nbsp; https://arxiv.org/abs/2206.01859

- Decentralized Training of Foundation Models in Heterogeneous Environments&nbsp; https://arxiv.org/abs/2206.01288


###  Topic 4: Robustness:Adversarials in distributed/decentralized learning

- Neurotoxin: Durable Backdoors in Federated Learning https://arxiv.org/abs/2202.04856nips.cc/paper/2021/file/0d924f0e6b3fd0d91074c22727a53966-Paper.pdfhttps://icml.cc/virtual/2022/spotlight/18208

- Fishing for User Data in Large-Batch Federated Learning via Gradient Magnification&nbsp; https://proceedings.mlr.press/v162/wen22a.html

- A2: Efficient Automated Attacker for Boosting Adversarial Training&nbsp;https://nips.cc/virtual/2022/poster/55316

- Distributed Adversarial Training to Robustify Deep Neural Networks at Scale&nbsp; https://proceedings.mlr.press/v180/zhang22a/zhang22a.pdf

- PPA: Preference Profiling Attack Against Federated Learning &nbsp; https://arxiv.org/abs/2202.04856


###  Topic 5/6: Personalization: Specialized distributed learning systems (I,II)

- FairVFL: A Fair Vertical Federated Learning Framework with Contrastive Adversarial Learning&nbsp; https://proceedings.neurips.cc/paper_files/paper/2022/hash/333a7697dbb67f09249337f81c27d749-Abstract-Conference.html

- IFL-GAN: Improved Federated Learning Generative Adversarial Network With Maximum Mean Discrepancy Model Aggregation&nbsp; https://ieeexplore.ieee.org/abstract/document/9763075?casa_token=NzH2dxZSvb0AAAAA:gYjvYJ_IPhGdxKgmTFbTatHHlixbx-s83HdNrxU9VqMFtB67AyVhyYOxFdyUdRN58GG-8-qj1g

- Personalized Federated Learning through Local Memorization&nbsp; https://icml.cc/virtual/2022/spotlight/18222

- Orchestra: Unsupervised Federated Learning via Globally Consistent Clustering&nbsp; https://icml.cc/virtual/2022/spotlight/18302

- Personalized Federated Learning towards Communication Efficiency, Robustness and Fairness&nbsp; https://nips.cc/virtual/2022/poster/53283

- DENSE: Data-Free One-Shot Federated Learning&nbsp; https://arxiv.org/abs/2112.12371

- Reprogrammable-FL: Improving Utility-Privacy Tradeoff in Federated Learning via Model Reprogramming https://openreview.net/pdf?id=00EiAK1LHs

- Interesting studies (NOT for reviews or project reproducing)
JAHS-Bench-201: A Foundation For Research On Joint Architecture And Hyperparameter Search https://nips.cc/virtual/2022/poster/55729

- Scaling Distributed Machine Learning with the Parameter Server https://web.eecs.umich.edu/~mosharaf/Readings/Parameter-Server.pdf

-->