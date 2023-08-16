# DML
This repository contains the materials of the  **Seminar Distributed Machine Learning Systems - fall 2023  at UNINE . 




##  1. <a name='Importantlinks'></a>Important links

- [Lectures notes](lecture.md)
- [Project description](project.md)
- [Homework assignments](homework.md)


##  2. <a name='Coursedescription'></a>Course description



##  3. <a name='Paper List'></a>paer
-  [Performance Modeling and Design of Computer Systems: Queuing Theory in Action]by Mor. Harchol-Balter 
-  [The Art of Computer Systems Performance Analysis](https://www.cse.wustl.edu/~jain/books/perfbook.htm) by Raj Jain
-  [The Elements of Statistical Learning: Data Mining, Inference, and Prediction](https://web.stanford.edu/~hastie/ElemStatLearn/), Springer Series in Statistics


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


###  Topic 5: Robustness:Adversarials in distributed/decentralized learning

- Neurotoxin: Durable Backdoors in Federated Learning https://arxiv.org/abs/2202.04856nips.cc/paper/2021/file/0d924f0e6b3fd0d91074c22727a53966-Paper.pdfhttps://icml.cc/virtual/2022/spotlight/18208

- Fishing for User Data in Large-Batch Federated Learning via Gradient Magnification&nbsp; https://proceedings.mlr.press/v162/wen22a.html

- A2: Efficient Automated Attacker for Boosting Adversarial Training&nbsp;https://nips.cc/virtual/2022/poster/55316

- Distributed Adversarial Training to Robustify Deep Neural Networks at Scale&nbsp; https://proceedings.mlr.press/v180/zhang22a/zhang22a.pdf

- PPA: Preference Profiling Attack Against Federated Learning &nbsp; https://arxiv.org/abs/2202.04856


###  Topic 6/7: Personalization: Specialized distributed learning systems (I,II)

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







##  4. <a name='Courseteam'></a>Course team
This course will be mainly taught by [Prof. Lydia Y Chen]([https://lydiaychen.github.io/])  The course team is composed of a number of PhDs  who support the course through guest lectures and project supervision.


[//]: # ( [Jeroen Galjaard](Jeroen Galjaard <J.M.Galjaard@tudelft.nl>l) (PhD student))

Lydia is the responsible instructors of this course and can jointly be reached at **lydiaychen@ieee.org**.

[//]: # (5. <a name='ECs'></a>ECs)

[//]: # (This is a **5 EC course**, with **140 hours** of course work in total. We expect you to spread the load evenly across the 9 course weeks.)

##  6. <a name='Learningobjectives'></a>Learning objectives
- L1
- L2
- L3
- L4
- L5


##  7. <a name='dart:Gradingpolicy'></a>:dart: Grading policy

There is no grade but pass/fail. 


**All assessment items (homework, and projects reports) have to be submitted via Brightspace.**




###  7.1. <a name='Groupprojects'></a>Group projects
<!-- 7 predefined project topics: evaluating the systems of 
-->
There are different aspects of performance  on modeling and optimizing the executions of deep neural network jobs. In this project, you will play with benchmarks that emulate the training jobs of deep neural networks on top of Spark platform - one of the most popular platform. You can build a model to predict the performance such jobs, to optimize their response times through resource allocations and scheduling, and to test the dependability of such a cluster against malicious attacks. You will do this project in a group with 1-2 other peers.

- Group size: 2-3 students
- Schedule: initial proposal , interim meeting, report due , and presentation/interview 

At the end of each project phase we will conduct a short interview (20 minutes per group) about the group project and its connection to the course content. Based on the project report and the interview, each member of the group receives a grade. 



In order to pass this course, you need to fullfil **all** of the following:
1. Receive an overall grade of 5.8 or higher (in alignment with TU Delft's exam regulations). 
2. Each homework and project at least a grade of 5.0.


##  8. <a name='Detailedschedule'></a>Detailed schedule
- Lecture 1
- Lecture 2
- Lecture 3
- Lecture 4



##  10. <a name='Relevantreferences'></a>Relevant references 

