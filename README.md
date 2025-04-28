# Paperflow
- [Paperflow](#paperflow)
  - [SRpapers](#srpapers)
    - [Introduction](#introduction)
    - [Papers on NN-based SR Models](#papers-on-nn-based-sr-models)
    - [Papers on SINDy-based SR Models](#papers-on-sindy-based-sr-models)
    - [Papers on DRL-based SR Models](#papers-on-drl-based-sr-models)
    - [Papers on Transformer-based SR Models](#papers-on-transformer-based-sr-models)
    - [Papers on Applications](#papers-on-applications)
    - [Papers that I haven't decided the label yet](#papers-that-i-havent-decided-the-label-yet)
## SRpapers
### Introduction

For centuries, physicists and mathematicians have pursued the elegant simplicity of symbolic equations to describe complex phenomena—from Newton's laws of motion to Maxwell's electromagnetic field equations. Yet when confronting ​​multiscale systems​ or ​​nonlinear dynamics​ (e.g. neuroscience, climate science, and financial markets), traditional derivation methods encounter an exponential explosion in the hypothesis space. The combinatorial complexity of potential governing equations renders brute-force symbolic search computationally prohibitive. 

The advent of data-driven discovery offers a paradigm shift. Machine learning (ML) techniques seem to be a powerful tool to uncover underlying physical laws or governing equations from sparse/noisy observations. So, how can we use machine learning to accelerate model discovery in the physical sciences?

In this repo, I list some representative work on SR and give some personal comment. Let's collectively decode the algorithms accelerating scientific discovery!

### Papers on NN-based SR Models
1. **Learning Equations for Extrapolation and Control**, *Subham Sahoo, Christoph Lampert, Georg Martius*, ICML, 2018. [[paper](https://proceedings.mlr.press/v80/sahoo18a.html)][[code](https://github.com/martius-lab/EQL)]
2. **NOMTO: Neural Operator-based symbolic Model approximaTion and discOvery**, *Sergei Garmaev, Siddhartha Mishra, Olga Fink*, arXiv, 2025. [[paper](https://arxiv.org/abs/2501.08086)][No code now]
3. **KAN: Kolmogorov\textendashArnold Networks**, *Ziming Liu, Yixuan Wang, Sachin Vaidya, Fabian Ruehle, James Halverson, Marin Soljacic, Thomas Y. Hou, Max Tegmark*, ICLR, 2025. [[paper](https://openreview.net/forum?id=Ozo7qJ5vZi)][[code](https://github.com/KindXiaoming/pykan)]
4. **KAN 2.0: Kolmogorov-Arnold Networks Meet Science**, *Ziming Liu, Pingchuan Ma, Yixuan Wang, Wojciech Matusik, Max Tegmark*, arXiv, 2024. [[paper](https://arxiv.org/abs/2408.10205)][[code](https://github.com/KindXiaoming/pykan)]

### Papers on SINDy-based SR Models
1. **Discovering governing equations from data by sparse identification of nonlinear dynamical systems**, *Steven L. Brunton, Joshua L. Proctor, J. Nathan Kutz*, Proceedings of the National Academy of Sciences, 2016. [[paper](https://www.pnas.org/doi/abs/10.1073/pnas.1517384113)][[code](https://github.com/mjsiers/practice-data-goveqpaper)]\
2. **Sparse identification of nonlinear dynamics for model predictive control in the low-data limit**, *Kaiser E., Kutz J. N. and Brunton S. L.*, Proc. R. Soc. 2018. [[paper](https://royalsocietypublishing.org/doi/full/10.1098/rspa.2018.0335)][[code](https://github.com/eurika-kaiser/SINDY-MPC)]
3. **Data-driven discovery of partial differential equations**, *Samuel H. Rudy, Steven L. Brunton, Joshua L. Proctor, J. Nathan Kutz*, Science Advances, 2017. [[paper](https://www.science.org/doi/abs/10.1126/sciadv.1602614)][[code](https://github.com/snagcliffs/PDE-FIND)]
4. **SINDy-RL: Interpretable and Efficient Model-Based Reinforcement Learning**, *Nicholas Zolman, Urban Fasel, J. Nathan Kutz, Steven L. Brunton*, arXiv, 2024. [[paper](https://arxiv.org/abs/2403.09110)][[code](https://github.com/nzolman/sindy-rl)]

<!-- ### Papers on Autoregression-based SR Models -->
### Papers on DRL-based SR Models
1. **Deep symbolic regression: Recovering mathematical expressions from data via risk-seeking policy gradients**, *Brenden K. Petersen, Mikel L, ajuela, T. Nathan Mundhenk, Claudio P. Santiago, Soo K. Kim, Joanne T. Kim*, ICLR, 2021. [[paper](https://arxiv.org/abs/1912.04871)][[code](https://github.com/TommasoBendinelli/deep-symbolic-regression)]
2.  **Symbolic Regression via Neural-Guided Genetic Programming Population Seeding**, *T. Nathan Mundhenk, Mikel L, ajuela, Ruben Glatt, Claudio P. Santiago, Daniel M. Faissol, Brenden K. Petersen*, NIPS, 2021. [[paper](https://arxiv.org/abs/2111.00053)][[code](https://github.com/dso-org/deep-symbolic-optimization)]
3.  **AI Feynman: a Physics-Inspired Method for Symbolic Regression**, *Silviu-Marian Udrescu, Max Tegmark*, Science Advances, 2020. [[paper](https://arxiv.org/abs/1905.11481)][[code](https://github.com/SJ001/AI-Feynman)]
4.  **A Unified Framework for Deep Symbolic Regression**, *Mikel L, ajuela, Chak Lee, Jiachen Yang, Ruben Glatt, Claudio P. Santiago, Ignacio Aravena, Terrell N. Mundhenk, Garrett Mulcahy, Brenden K. Petersen*, NIPS, 2022. [[paper](https://openreview.net/forum?id=2FNnBhwJsHK)][[code](https://github.com/brendenpetersen/deep-symbolic-optimization)]
5.  **Discovering symbolic policies with deep reinforcement learning**, *L, Mikel ajuela, Brenden K Petersen, Sookyung Kim, Claudio P Santiago, Ruben Glatt, Nathan Mundhenk, Jacob F Pettit, Daniel Faissol*, ICML, 2021. [[paper](https://proceedings.mlr.press/v139/landajuela21a/landajuela21a.pdf)][[code](https://github.com/dso-org/deep-symbolic-optimization)]

### Papers on Transformer-based SR Models
1. **SymbolicGPT: A Generative Transformer Model for Symbolic Regression**, *Mojtaba Valipour, Bowen You, Maysum Panju, Ali Ghodsi*, arXiv, 2021. [[paper](https://arxiv.org/abs/2106.14131)][[code](https://github.com/mojivalipour/symbolicgpt)]
2. **Neural Symbolic Regression that scales**, *Luca Biggio, Tommaso Bendinelli, Alex Neitz, er, Aurelien Lucchi, Parasc, Giambattista olo*, ICML, 2021. [[paper](https://proceedings.mlr.press/v139/biggio21a.html)][[code](https://github.com/SymposiumOrganization/NeuralSymbolicRegressionThatScales)]
3. **End-to-end symbolic regression with transformers**, *Pierre-Alex Kamienny, re, Stéphane d'Ascoli, Guillaume Lample, François Charton*, NIPS, 2022. [[paper](https://dl.acm.org/doi/10.5555/3600270.3601016)][[code](https://github.com/facebookresearch/symbolicregression)]
4. **Transformer-based Planning for Symbolic Regression**, *Parshin Shojaee, Kazem Meidani, Amir Barati Farimani, Ch Reddy, an*, NIPS, 2023. [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/8ffb4e3118280a66b192b6f06e0e2596-Paper-Conference.pdf)][[code](https://github.com/deep-symbolic-mathematics/TPSR)]
5. **Controllable neural symbolic regression**, *Tommaso Bendinelli, Luca Biggio, Pierre-Alex Kamienny, re*, ICML, 2023. [[paper](https://dl.acm.org/doi/10.5555/3618408.3618496)][[code](https://github.com/SymposiumOrganization/ControllableNeuralSymbolicRegression)]
6. **SNIP: Bridging Mathematical Symbolic and Numeric Realms with Unified Pre-training**, *Kazem Meidani, Parshin Shojaee, Ch, an K. Reddy, Amir Barati Farimani*, ICLR, 2024. [[paper](https://openreview.net/forum?id=KZSEgJGPxu)][[code](https://github.com/deep-symbolic-mathematics/Multimodal-Math-Pretraining)]
7. **In-Context Symbolic Regression: Leveraging Large Language Models for Function Discovery**, *Matteo Merler, Katsiaryna Haitsiukevich, Nicola Dainese, Pekka Marttinen*, arXiv, 2024. [[paper](http://dx.doi.org/10.18653/v1/2024.acl-srw.49)][[code](https://github.com/merlerm/In-Context-Symbolic-Regression)]
8. **MMSR: Symbolic regression is a multi-modal information fusion task**, *Yanjie Li, Jingyi Liu, Min Wu, Lina Yu, Weijun Li, Xin Ning, Wenqiang Li, Meilan Hao, Yusong Deng, Shu Wei*, Information Fusion, 2025. [[paper](https://www.sciencedirect.com/science/article/pii/S1566253524004597)][[code](https://github.com/1716757342/MMSR)]
9. **LLM-SR: Scientific Equation Discovery via Programming with Large Language Models**, *Parshin Shojaee, Kazem Meidani, Shashank Gupta, Amir Barati Farimani, Ch, an K. Reddy*, ICLR, 2025. [[paper](https://openreview.net/forum?id=m2nmp8P5in)][[code](https://github.com/deep-symbolic-mathematics/LLM-SR)]
10. **PROSE: Predicting Multiple Operators and Symbolic Expressions using multimodal transformers**, *Yuxuan Liu, Zecheng Zhang, Hayden Schaeffer*, Neural Networks, 2024. [[paper](https://www.sciencedirect.com/science/article/pii/S0893608024006312)][[code](https://github.com/felix-lyx/prose)]
11.  **Transformer-based model for symbolic regression via joint supervised learning**, *Wenqiang Li, Weijun Li, Linjun Sun, Min Wu, Lina Yu, Jingyi Liu, Yanjie Li, Songsong Tian*, **UNKNOWN_JOURNAL**, 2023. [[paper](https://openreview.net/forum?id=ULzyv9M1j5)][[code](https://github.com/AILWQ/Joint_Supervised_Learning_for_SR)]
12.  **A Neural Symbolic Model for Space Physics**, *Jie Ying, Haowei Lin, Chao Yue, Yajie Chen, Chao Xiao, Quanqi Shi, Yitao Liang, Shing-Tung Yau, Yuan Zhou, Jianzhu Ma*, arXiv, 2025. [[paper](https://arxiv.org/abs/2503.07994)][[code](https://github.com/Jie0618/PhysicsRegression)]
13.  **Deep Generative Symbolic Regression**, *Samuel Holt, Zhaozhi Qian, Mihaela van der Schaar*, ICLR, 2023. [[paper](https://openreview.net/pdf?id=o7koEEMA1bR)][[code](https://github.com/samholt/DeepGenerativeSymbolicRegression)]

### Papers on Applications
1. **Rediscovering the Mullins effect with deep symbolic regression**, *Rasul Abdusalamov, Jendrik Weise, Mikhail Itskov*, International Journal of Plasticity, 2024. [[paper](https://www.sciencedirect.com/science/article/pii/S0749641924001645)][[code]()]
2. **Identification of control equations using low-dimensional flow representations of pitching airfoil**, *Zihao Wang, Guiyong Zhang, Bo Zhou, Tiezhi, Sun, Jinxin Wu*, Physics of Fluids, 2024. [[paper](https://doi.org/10.1063/5.0205170)][[code]()]
3. **Development of a Generalizable Data-Driven Turbulence Model: Conditioned Field Inversion and Symbolic Regression**, *Chenyu Wu, Shaoguang Zhang, Yufei Zhang*, AIAA Journal, 2025. [[paper](https://doi.org/10.2514/1.J064416)][[code]()]

 
### Papers that I haven't decided the label yet
1. **Contemporary Symbolic Regression Methods and their Relative Performance**, *William La Cava, Patryk Orzechowski, Bogdan Burlacu, Fabricio Olivetti de Franca, Marco Virgolin, Ying Jin, Michael Kommenda, Jason H. Moore*, NIPS, 2021. [[paper](https://openreview.net/forum?id=xVQMrDLyGst)][[code](https://github.com/cavalab/srbench/)]
2. **SRBench++: Principled Benchmarking of Symbolic Regression With Domain-Expert Interpretation**, *F. O. de Franca, M. Virgolin, M. Kommenda, M. S. Majumder, M. Cranmer, G. Espada, L. Ingelse, A. Fonseca, L, M. ajuela, B. Petersen, R. Glatt, N. Mundhenk, C. S. Lee, J. D. Hochhalter, R, D. L. all, P. Kamienny, H. Zhang, G. Dick, A. Simon, B. Burlacu, Jaan Kasak, Meera Machado, Casper Wilstrup, W. G. La Cavaz*, IEEE Transactions on Evolutionary Computation, 2024. [[paper](https://doi.org/10.1109/TEVC.2024.3423681)][[code](https://github.com/cavalab/srbench/tree/Competition2022)]
3. **Grammar variational autoencoder**, *Matt J. Kusner, Brooks Paige, Jos\'{e} Miguel Hern\'{a}ndez-Lobato*, ICML, 2017. [[paper](https://dl.acm.org/doi/pdf/10.5555/3305381.3305582)][[code](https://github.com/mkusner/grammarVAE)]
