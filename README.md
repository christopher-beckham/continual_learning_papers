# Continual Learning Literature 
This repository is maintained by Massimo Caccia and Timothée Lesort don't hesitate to send us an email to collaborate or fix some entries ({massimo.p.caccia , t.lesort} at gmail.com). The automation script of this repo is adapted from [Automatic_Awesome_Bibliography](https://github.com/TLESORT/Automatic_Awesome_Bibliography).

 For contributing to the repository please follow the process [here](https://github.com/optimass/continual_learning_papers/blob/master/scripts/README.md) 

 You can directly use our bib.tex in overleaf [with this link](https://www.overleaf.com/project/606f5acf8bf59dcda3e66f9e) 

## Outline 
- [Classics](https://github.com/optimass/continual_learning_papers/blob/master/README.md#classics)
- [Empirical Study](https://github.com/optimass/continual_learning_papers/blob/master/README.md#empirical-study)
- [Surveys](https://github.com/optimass/continual_learning_papers/blob/master/README.md#surveys)
- [Influentials](https://github.com/optimass/continual_learning_papers/blob/master/README.md#influentials)
- [New Settings or Metrics](https://github.com/optimass/continual_learning_papers/blob/master/README.md#new-settings-or-metrics)
- [General Continual Learning Methods (SL and RL)](https://github.com/optimass/continual_learning_papers/blob/master/README.md#general-continual-learning-methods-(sl-and-rl))
- [Task-Agnostic Continual Learning](https://github.com/optimass/continual_learning_papers/blob/master/README.md#task-agnostic-continual-learning)
- [Regularization Methods](https://github.com/optimass/continual_learning_papers/blob/master/README.md#regularization-methods)
- [Distillation Methods](https://github.com/optimass/continual_learning_papers/blob/master/README.md#distillation-methods)
- [Rehearsal Methods](https://github.com/optimass/continual_learning_papers/blob/master/README.md#rehearsal-methods)
- [Generative Replay Methods](https://github.com/optimass/continual_learning_papers/blob/master/README.md#generative-replay-methods)
- [Dynamic Architectures or Routing Methods](https://github.com/optimass/continual_learning_papers/blob/master/README.md#dynamic-architectures-or-routing-methods)
- [Hybrid Methods](https://github.com/optimass/continual_learning_papers/blob/master/README.md#hybrid-methods)
- [Continual Few-Shot Learning](https://github.com/optimass/continual_learning_papers/blob/master/README.md#continual-few-shot-learning)
- [Meta-Continual Learning](https://github.com/optimass/continual_learning_papers/blob/master/README.md#meta-continual-learning)
- [Lifelong Reinforcement Learning](https://github.com/optimass/continual_learning_papers/blob/master/README.md#lifelong-reinforcement-learning)
- [Task-Agnostic Lifelong Reinforcement Learning](https://github.com/optimass/continual_learning_papers/blob/master/README.md#task-agnostic-lifelong-reinforcement-learning)
- [Continual Generative Modeling](https://github.com/optimass/continual_learning_papers/blob/master/README.md#continual-generative-modeling)
- [Biologically-Inspired](https://github.com/optimass/continual_learning_papers/blob/master/README.md#biologically-inspired)
- [Miscellaneous](https://github.com/optimass/continual_learning_papers/blob/master/README.md#miscellaneous)
- [Applications](https://github.com/optimass/continual_learning_papers/blob/master/README.md#applications)
- [Thesis](https://github.com/optimass/continual_learning_papers/blob/master/README.md#thesis)
- [Libraries](https://github.com/optimass/continual_learning_papers/blob/master/README.md#libraries)
- [Workshops](https://github.com/optimass/continual_learning_papers/blob/master/README.md#workshops)

## Classics
- [**Catastrophic forgetting in connectionist networks**](https://www.sciencedirect.com/science/article/abs/pii/S1364661399012942) , (1999) by *French, Robert M.* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1290-L1304) 
- [**Lifelong robot learning**](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.71.3723&rep=rep1&type=pdf) , (1995) by *Thrun, Sebastian and Mitchell, Tom M* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L378-L387) 
``` Argues knowledge transfer is essential if robots are to learn control with moderate learning times ``` 
- [**Catastrophic Forgetting, Rehearsal and Pseudorehearsal**](https://doi.org/10.1080/09540099550039318) , (1995) by * Anthony   Robins * [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2030-L2043) 
- [**Catastrophic interference in connectionist networks: The sequential learning problem**](https://www.sciencedirect.com/science/article/pii/S0079742108605368) , (1989) by *McCloskey, Michael and Cohen, Neal J* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L970-L980) 
``` Introduces CL and reveals the catastrophic forgetting problem ``` 

## Empirical Study
- [**Transfer without Forgetting**](https://arxiv.org/abs/2206.00388) , (ECCV 2022) by *Boschini, Matteo, Bonicelli, Lorenzo, Porrello, Angelo, Bellitto, Giovanni, Pennisi, Matteo, Palazzo, Simone, Spampinato, Concetto and Calderara, Simone* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1-L8) 
- [**Effects of Auxiliary Knowledge on Continual Learning**](https://arxiv.org/abs/2206.02577) , (ICPR 2022) by *Bellitto, Giovanni, Pennisi, Matteo, Palazzo, Simone, Bonicelli, Lorenzo, Boschini, Matteo, Calderara, Simone and Spampinato, Concetto* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L113-L120) 
- [**Rethinking Experience Replay: a Bag of Tricks for Continual Learning**](https://ieeexplore.ieee.org/abstract/document/9412614) , (ICPR 2021) by *Buzzega, Pietro, Boschini, Matteo, Porrello, Angelo and Calderara, Simone* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L212-L223) 
- [**A comprehensive study of class incremental learning algorithms for visual tasks**](https://www.sciencedirect.com/science/article/pii/S0893608020304202) , (Neural Networks 2021) by *Eden Belouadah, Adrian Popescu and Ioannis Kanellos* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2763-L2775) 
- **Online Continual Learning in Image Classification: An Empirical Survey**, (2021) by *Zheda Mai, Ruiwen Li, Jihwan Jeong, David Quispe, Hyunwoo Kim and Scott Sanner* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2777-L2785) 
- **GDumb: A simple approach that questions our progress in continual learning**, (ECCV 2020) by *Prabhu, Ameya, Torr, Philip HS and Dokania, Puneet K* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L237-L245) 
``` introduces a super simple methods that outperforms almost all methods in all of the CL benchmarks. We need new better benchamrks ``` 
- [**Continual learning: A comparative study on how to defy forgetting in classification tasks**](https://arxiv.org/abs/1909.08383) , (2019) by *Matthias De Lange, Rahaf Aljundi, Marc Masana, Sarah Parisot, Xu Jia, Ales Leonardis, Gregory Slabaugh and Tinne Tuytelaars* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L463-L472) 
``` Extensive empirical study of CL methods (in the multi-head setting) ``` 
- [**Three scenarios for continual learning**](https://arxiv.org/abs/1904.07734) , (arXiv 2019) by *van de Ven, Gido M and Tolias, Andreas S* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1002-L1009) 
``` An extensive review of CL methods in three different scenarios (task-, domain-, and class-incremental learning) ``` 
- **Continuous learning in single-incremental-task scenarios**, (Neural Networks 2019) by *Maltoni, Davide and Lomonaco, Vincenzo* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1317-L1326) 
- [**Towards Robust Evaluations of Continual Learning**](https://arxiv.org/abs/1805.09733) , (arXiv 2018) by *Farquhar, Sebastian and Gal, Yarin* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L390-L397) 
``` Proposes desideratas and reexamines the evaluation protocol ``` 
- **Catastrophic forgetting: still a problem for DNNs**, (ICANN 2018) by *Pf\"ulb, B, Gepperth, A, Abdullah, S and Krawczyk, A* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2181-L2187) 
- **Measuring Catastrophic Forgetting in Neural Networks**, (2017) by *Kemker, R., McClure, M., Abitino, A. and Hayes, T. and
Kanan, C.* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1329-L1342) 
- [**CORe50: a New Dataset and Benchmark for Continuous Object Recognition**](http://proceedings.mlr.press/v78/lomonaco17a.html) , (CoRL 2017) by *Vincenzo Lomonaco and Davide Maltoni* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1344-L1359) 
- [**An Empirical Investigation of Catastrophic Forgetting in Gradient-Based Neural Networks**](https://arxiv.org/abs/1312.6211) , (2013) by *Goodfellow, I.~J., Mirza, M., Xiao, D., Courville, A. and Bengio, Y.* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L447-L460) 
``` Investigates CF in neural networks ``` 

## Surveys
- [**An Investigation of Replay-based Approaches for Continual Learning**](https://arxiv.org/abs/2108.06758) , (IJCNN 2021) by *Bagus, Benedikt and Gepperth, Alexander* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L3250-L3259) 
- **Embracing Change: Continual Learning in Deep Neural Networks**, (2020) by *Hadsell, Raia, Rao, Dushyant, Rusu, Andrei and Pascanu, Razvan* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L122-L132) 
- **Towards Continual Reinforcement Learning: A Review and Perspectives**, (2020) by *Khimya Khetarpal, Matthew Riemer, Irina Rish and Doina Precup* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L248-L256) 
``` A review on continual reinforcement learning ``` 
- [**Continual learning for robotics: Definition, framework, learning strategies, opportunities and challenges**](http://www.sciencedirect.com/science/article/pii/S1566253519307377) , (Information Fusion 2020) by *Timothée Lesort, Vincenzo Lomonaco, Andrei Stoian, Davide Maltoni, David Filliat and Natalia Díaz-Rodríguez* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1276-L1287) 
- [**A Wholistic View of Continual Learning with Deep Neural Networks: Forgotten Lessons and the Bridge to Active and Open World Learning**](https://arxiv.org/abs/2009.01797) , (arXiv 2020) by *Mundt, Martin, Hong, Yong Won, Pliushch, Iuliia and Ramesh, Visvanathan* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2550-L2557) 
``` propose a consolidated view to bridge continual learning, active learning and open set recognition in DNNs ``` 
- [**Continual Lifelong Learning in Natural Language Processing: A Survey**](https://www.aclweb.org/anthology/2020.coling-main.574) , (2020) by *Magdalena Biesialska, Katarzyna Biesialska, Marta R. Costa-jussà* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2728-L2740) 
``` An extensive review of CL in Natural Language Processing (NLP) ``` 
- [**Continual lifelong learning with neural networks: A review**](http://www.sciencedirect.com/science/article/pii/S0893608019300231) , (Neural Networks 2019) by *German I. Parisi, Ronald Kemker, Jose L. Part, Christopher Kanan and Stefan Wermter* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L475-L486) 
``` An extensive review of CL ``` 
- [**Incremental learning algorithms and applications**](https://hal.archives-ouvertes.fr/hal-01418129) , (2016) by *Gepperth, Alexander and Hammer, Barbara* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1133-L1144) 
``` A survey on incremental learning and the various applications fields ``` 

## Influentials
- [**Efficient Lifelong Learning with A-GEM**](https://arxiv.org/abs/1812.00420) , (ICLR 2019) by *Chaudhry, Arslan, Ranzato, Marc’Aurelio, Rohrbach, Marcus and Elhoseiny, Mohamed* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L400-L407) 
``` More efficient GEM; Introduces online continual learning ``` 
- [**Towards Robust Evaluations of Continual Learning**](https://arxiv.org/abs/1805.09733) , (arXiv 2018) by *Farquhar, Sebastian and Gal, Yarin* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L390-L397) 
``` Proposes desideratas and reexamines the evaluation protocol ``` 
- [**Continual Learning in Practice**](https://arxiv.org/abs/1903.05202) , (NeurIPS Workshop 2018) by *Diethe, Tom, Borchert, Tom, Thereska, Eno, Pigem, Borja de Balle and Lawrence, Neil* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2282-L2289) 
``` Proposes a reference architecture for a continual learning system ``` 
- [**Overcoming catastrophic forgetting in neural networks**](https://www.pnas.org/content/pnas/114/13/3521.full.pdf) , (PNAS 2017) by *Kirkpatrick, James, Pascanu, Razvan, Rabinowitz, Neil, Veness, Joel, Desjardins, Guillaume, Rusu, Andrei A, Milan, Kieran, Quan, John, Ramalho, Tiago, Grabska-Barwinska, Agnieszka and others* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L410-L418) 
- [**Gradient Episodic Memory for Continual Learning**](http://papers.nips.cc/paper/7225-gradient-episodic-memory-for-continual-learning.pdf) , (NeurIPS 2017) by *Lopez-Paz, David and Ranzato, Marc-Aurelio* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L422-L432) 
``` A model that alliviates CF via constrained optimization ``` 
- [**Continual learning with deep generative replay**](https://arxiv.org/abs/1705.08690) , (NeurIPS 2017) by *Shin, Hanul, Lee, Jung Kwon, Kim, Jaehong and Kim, Jiwon* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L436-L444) 
``` Introduces generative replay ``` 
- [**An Empirical Investigation of Catastrophic Forgetting in Gradient-Based Neural Networks**](https://arxiv.org/abs/1312.6211) , (2013) by *Goodfellow, I.~J., Mirza, M., Xiao, D., Courville, A. and Bengio, Y.* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L447-L460) 
``` Investigates CF in neural networks ``` 

## New Settings or Metrics
- [**IIRC: Incremental Implicitly-Refined Classification**](https://chandar-lab.github.io/IIRC/) , (CVPR 2021) by *Mohamed Abdelsalam, Mojtaba Faramarzi, Shagun Sodhani and Sarath Chandar* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2716-L2724) 
``` A setup and benchmark to evaluate lifelong learning models in more real-life aligned scenarios. ``` 
- [**Sequoia - Towards a Systematic Organization of Continual Learning Research**](https://github.com/lebrice/Sequoia) , (2021) by *Fabrice Normandin, Florian  Golemo,  Oleksiy Ostapenko,  Matthew Riemer,  Pau Rodriguez,  Julio Hurtado,  Khimya Khetarpal, Timothée Lesort,  Laurent Charlin, Irina Rish and Massimo Caccia* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2906-L2915) 
``` A library that unifies Continual Supervised and Continual Reinforcement Learning research ``` 
- [**Wandering Within a World: Online Contextualized Few-Shot Learning**](https://arxiv.org/abs/2007.04546) , (2020) by *Mengye Ren, Michael L. Iuzzolino, Michael C. Mozer and Richard S. Zemel* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L280-L288) 
``` proposes a new continual few-shot setting where spacial and temporal context can be leveraged to and unseen classes need to be predicted ``` 
- [**Defining Benchmarks for Continual Few-Shot Learning**](https://arxiv.org/abs/2004.11967) , (arXiv 2020) by *Antoniou, Antreas, Patacchiola, Massimiliano, Ochal, Mateusz and Storkey, Amos* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L322-L329) 
``` (title is a good enough summary) ``` 
- [**Online Fast Adaptation and Knowledge Accumulation: a New Approach to Continual Learning**](https://arxiv.org/abs/2003.05856) , (2020) by *Caccia, Massimo, Rodriguez, Pau, Ostapenko, Oleksiy, Normandin, Fabrice, Lin, Min, Caccia, Lucas, Laradji, Issam, Rish, Irina, Lacoste, Alexandre, Vazquez, David and Charlin, Laurent* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1428-L1435) 
``` Proposes a new approach to CL evaluation more aligned with real-life applications, bringing CL closer to Online Learning and Open-World learning ``` 
- [**Compositional Language Continual Learning**](https://openreview.net/forum?id=rklnDgHtDS) , (ICLR 2020) by *Yuanpeng Li, Liang Zhao, Kenneth Church and Mohamed Elhoseiny* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1506-L1513) 
``` method for compositional continual learning of sequence-to-sequence models ``` 
- [**A Wholistic View of Continual Learning with Deep Neural Networks: Forgotten Lessons and the Bridge to Active and Open World Learning**](https://arxiv.org/abs/2009.01797) , (arXiv 2020) by *Mundt, Martin, Hong, Yong Won, Pliushch, Iuliia and Ramesh, Visvanathan* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2550-L2557) 
``` propose a consolidated view to bridge continual learning, active learning and open set recognition in DNNs ``` 
- **Don't forget, there is more than forgetting: new metrics for Continual Learning**, (arXiv 2018) by *D{\'\i}az-Rodr{\'\i}guez, Natalia, Lomonaco, Vincenzo, Filliat, David and Maltoni, Davide* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2897-L2903) 
``` introduces a CL score that takes more than just forgetting into account ``` 

## General Continual Learning Methods (SL and RL)
- [**Overcoming catastrophic forgetting in neural networks**](https://www.pnas.org/content/pnas/114/13/3521.full.pdf) , (PNAS 2017) by *Kirkpatrick, James, Pascanu, Razvan, Rabinowitz, Neil, Veness, Joel, Desjardins, Guillaume, Rusu, Andrei A, Milan, Kieran, Quan, John, Ramalho, Tiago, Grabska-Barwinska, Agnieszka and others* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L410-L418) 
- [**PathNet: Evolution Channels Gradient Descent in Super Neural Networks**](http://arxiv.org/abs/1701.08734) , (2017) by *Chrisantha Fernando and
Dylan Banarse and
Charles Blundell and
Yori Zwols and
David Ha and
Andrei A. Rusu and
Alexander Pritzel and
Daan Wierstra* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1751-L1771) 

## Task-Agnostic Continual Learning
- [**Task-agnostic Continual Learning with Hybrid Probabilistic Models**](https://arxiv.org/abs/2106.12772) , (2021) by *Polina Kirichenko, Mehrdad Farajtabar, Dushyant Rao, Balaji Lakshminarayanan, Nir Levine, Ang Li, Huiyi Hu, Andrew Gordon Wilson and Razvan Pascanu* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L181-L190) 
- [**Learning where to learn: Gradient sparsity in meta and continual learning**](https://proceedings.neurips.cc/paper/2021/hash/2a10665525774fa2501c2c8c4985ce61-Abstract.html) , (2021) by *Von Oswald, Johannes, Zhao, Dominic, Kobayashi, Seijin, Schug, Simon, Caccia, Massimo, Zucchet, Nicolas and Sacramento, Jo{\~a}o* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L202-L210) 
- [**Uncertainty-guided Continual Learning with Bayesian Neural Networks**](https://openreview.net/forum?id=HklUCCVKDB) , (ICLR 2020) by *Sayna Ebrahimi, Mohamed Elhoseiny, Trevor Darrell and Marcus Rohrbach* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L512-L519) 
``` Uses Bayes by Backprop for variational Continual Learning. ``` 
- [**Online Fast Adaptation and Knowledge Accumulation: a New Approach to Continual Learning**](https://arxiv.org/abs/2003.05856) , (2020) by *Caccia, Massimo, Rodriguez, Pau, Ostapenko, Oleksiy, Normandin, Fabrice, Lin, Min, Caccia, Lucas, Laradji, Issam, Rish, Irina, Lacoste, Alexandre, Vazquez, David and Charlin, Laurent* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1428-L1435) 
``` Proposes a new approach to CL evaluation more aligned with real-life applications, bringing CL closer to Online Learning and Open-World learning ``` 
- **iTAML: An Incremental Task-Agnostic Meta-learning Approach**, (CVPR 2020) by *Rajasegaran, Jathushan, Khan, Salman, Hayat, Munawar, Khan, Fahad Shahbaz and Shah, Mubarak* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2366-L2373) 
- [**Continual Unsupervised Representation Learning**](https://arxiv.org/pdf/1910.14481.pdf) , (2019) by *Dushyant Rao, Francesco Visin, Andrei A. Rusu, Yee Whye Teh, Razvan Pascanu and Raia Hadsell* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L897-L906) 
``` Introduces unsupervised continual learning (no task label and no task boundaries) ``` 
- [**A Neural Dirichlet Process Mixture Model for Task-Free Continual Learning**](https://arxiv.org/pdf/2001.00689.pdf) , (ICLR 2019) by *Lee, Soochan, Ha, Junsoo, Zhang, Dongsu and Kim, Gunhee* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1495-L1502) 
``` This paper introduces expansion-based approach for task-free continual learning ``` 
- [**Task Agnostic Continual Learning Using Online Variational Bayes**](https://arxiv.org/pdf/1803.10123.pdf) , (2018) by *Chen Zeno, Itay Golan, Elad Hoffer and Daniel Soudry* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L535-L544) 
``` Introduces an optimizer for CL that relies on closed form updates of mu and sigma of BNN; introduce label trick for class learning (single-head) but warning: it isn't really task-agnostic ``` 

## Regularization Methods
- [**Continual Learning in Deep Networks: an Analysis of the Last Layer**](https://arxiv.org/abs/2106.01834) , (arXiv 2021) by *Lesort, Timoth{\'e}e, George, Thomas and Rish, Irina* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L3200-L3207) 
- [**Continual Learning with Bayesian Neural Networks for Non-Stationary Data**](https://openreview.net/forum?id=SJlsFpVtDB) , (ICLR 2020) by *Richard Kurle, Botond Cseke, Alexej Klushyn, Patrick van der Smagt and Stephan Günnemann* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L843-L850) 
``` continual learning for non-stationary data using Bayesian neural networks and memory-based online variational Bayes ``` 
- [**Improving and Understanding Variational Continual Learning**](https://arxiv.org/abs/1905.02099) , (2019) by *Siddharth Swaroop, Cuong V. Nguyen, Thang D. Bui and Richard E. Turner* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L500-L508) 
``` Improved results and interpretation of VCL. ``` 
- [**Uncertainty-based Continual Learning with Adaptive Regularization**](http://papers.nips.cc/paper/8690-uncertainty-based-continual-learning-with-adaptive-regularization.pdf) , (NeurIPS 2019) by *Ahn, Hongjoon, Cha, Sungmin, Lee, Donggyu and Moon, Taesup* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L522-L532) 
``` Introduces VCL with uncertainty measured for neurons instead of weights. ``` 
- [**Functional Regularisation for Continual Learning with Gaussian Processes**](https://arxiv.org/abs/1901.11356) , (ICLR 2019) by *Titsias, Michalis K, Schwarz, Jonathan, Matthews, Alexander G de G, Pascanu, Razvan and Teh, Yee Whye* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1306-L1313) 
``` functional regularisation for Continual Learning: avoids forgetting a previous task by constructing and memorising an approximate posterior belief over the underlying task-specific function ``` 
- [**Task Agnostic Continual Learning Using Online Variational Bayes**](https://arxiv.org/pdf/1803.10123.pdf) , (2018) by *Chen Zeno, Itay Golan, Elad Hoffer and Daniel Soudry* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L535-L544) 
``` Introduces an optimizer for CL that relies on closed form updates of mu and sigma of BNN; introduce label trick for class learning (single-head) but warning: it isn't really task-agnostic ``` 
- [**Overcoming Catastrophic Interference using Conceptor-Aided Backpropagation**](https://openreview.net/forum?id=B1al7jg0b) , (ICLR 2018) by *Xu He and Herbert Jaeger* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L576-L583) 
``` Conceptor-Aided Backprop (CAB): gradients are shielded by conceptors against degradation of previously learned tasks ``` 
- [**Overcoming Catastrophic Forgetting with Hard Attention to the Task**](http://proceedings.mlr.press/v80/serra18a.html) , (ICML 2018) by *Serra, Joan, Suris, Didac, Miron, Marius and Karatzoglou, Alexandros* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L596-L612) 
``` Introducing a hard attention idea with binary masks ``` 
- [**Riemannian Walk for Incremental Learning: Understanding Forgetting and Intransigence**](https://arxiv.org/abs/1801.10112) , (ECCV 2018) by *Chaudhry, Arslan, Dokania, Puneet K, Ajanthan, Thalaiyasingam and Torr, Philip HS* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L615-L622) 
``` Formalizes the shortcomings of multi-head evaluation, as well as the importance of replay in single-head setup. Presenting an improved version of EWC. ``` 
- [**Variational Continual Learning**](https://arxiv.org/abs/1710.10628) , (ICLR 2018) by *Cuong V. Nguyen, Yingzhen Li, Thang D. Bui and Richard E. Turner* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L646-L653) 
- [**Progress \& compress: A scalable framework for continual learning**](https://arxiv.org/abs/1805.06370) , (ICML 2018) by *Schwarz, Jonathan, Luketina, Jelena, Czarnecki, Wojciech M, Grabska-Barwinska, Agnieszka, Teh, Yee Whye, Pascanu, Razvan and Hadsell, Raia* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L657-L664) 
``` A new P\&C architecture; online EWC for keeping the knowledge about the previous task, knowledge for keeping the knowledge about the current task (Multi-head setting, RL) ``` 
- **Online structured laplace approximations for overcoming catastrophic forgetting**, (NeurIPS 2018) by *Ritter, Hippolyt, Botev, Aleksandar and Barber, David* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2011-L2018) 
- [**Facilitating Bayesian Continual Learning by Natural Gradients and Stein Gradients**](https://arxiv.org/abs/1904.10644) , (NeurIPS Workshop 2018) by *Chen, Yu, Diethe, Tom and Lawrence, Neil* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2292-L2299) 
``` Improves on VCL ``` 
- [**Overcoming catastrophic forgetting in neural networks**](https://www.pnas.org/content/pnas/114/13/3521.full.pdf) , (PNAS 2017) by *Kirkpatrick, James, Pascanu, Razvan, Rabinowitz, Neil, Veness, Joel, Desjardins, Guillaume, Rusu, Andrei A, Milan, Kieran, Quan, John, Ramalho, Tiago, Grabska-Barwinska, Agnieszka and others* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L410-L418) 
- [**Memory Aware Synapses: Learning what (not) to forget**](http://arxiv.org/abs/1711.09601) , (2017) by *Rahaf Aljundi, Francesca Babiloni, Mohamed Elhoseiny, Marcus Rohrbach and Tinne Tuytelaars* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L628-L641) 
``` Importance of parameter measured based on their contribution to change in the learned prediction function ``` 
- [**Continual Learning Through Synaptic Intelligence**](http://proceedings.mlr.press/v70/zenke17a.html) , (ICML 2017) by *Zenke, Friedeman, Poole, Ben and Ganguli, Surya * [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L667-L682) 
``` Synaptic Intelligence (SI). Importance of parameter measured based on their contribution to change in the loss.  ``` 
- **Overcoming catastrophic forgetting by incremental moment matching**, (NeurIPS 2017) by *Lee, Sang-Woo, Kim, Jin-Hwa, Jun, Jaehyun, Ha, Jung-Woo and Zhang, Byoung-Tak* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1880-L1887) 

## Distillation Methods
- [**Transfer without Forgetting**](https://arxiv.org/abs/2206.00388) , (ECCV 2022) by *Boschini, Matteo, Bonicelli, Lorenzo, Porrello, Angelo, Bellitto, Giovanni, Pennisi, Matteo, Palazzo, Simone, Spampinato, Concetto and Calderara, Simone* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1-L8) 
- [**Self-Supervised Models are Continual Learners**](https://arxiv.org/abs/2112.04215) , (CVPR 2022) by *Fini, Enrico, da Costa, Victor G Turrisi, Alameda-Pineda, Xavier, Ricci, Elisa, Alahari, Karteek and Mairal, Julien* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L3385-L3392) 
``` Explores Continual Self-Supervised Learning and proposes a simple and effective feature distillation method ``` 
- [**Uncertainty-aware Contrastive Distillation for Incremental Semantic Segmentation**](https://arxiv.org/abs/2203.14098) , (TPAMI 2022) by *Yang, Guanglei, Fini, Enrico, Xu, Dan, Rota, Paolo, Ding, Mingli, Nabi, Moin, Alameda-Pineda, Xavier and Ricci, Elisa* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L3395-L3403) 
- [**Continual Attentive Fusion for Incremental Learning in Semantic Segmentation**](https://arxiv.org/abs/2202.00432) , (TMM 2022) by *Yang, Guanglei, Fini, Enrico, Xu, Dan, Rota, Paolo, Ding, Mingli, Hao, Tang, Alameda-Pineda, Xavier and Ricci, Elisa* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L3405-L3413) 
- [**Dark Experience for General Continual Learning: a Strong, Simple Baseline**](https://papers.nips.cc/paper/2020/file/b704ea2c39778f07c617f6b7ce480e9e-Paper.pdf) , (NeurIPS 2020) by *Buzzega, Pietro, Boschini, Matteo, Porrello, Angelo, Abati, Davide and Calderara, Simone* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L225-L235) 
- [**Online Continual Learning under Extreme Memory Constraints**](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730715.pdf) , (ECCV 2020) by *Fini, Enrico, Lathuilière, Stèphane, Sangineto, Enver, Nabi, Moin and Ricci, Elisa* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2452-L2459) 
``` Introduces Memory-Constrained Online Continual Learning, a setting where no information can be transferred between tasks, and proposes a distillation-based solution (Batch-level Distillation) ``` 
- [**PODNet: Pooled Outputs Distillation for Small-Tasks Incremental Learning**](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650086.pdf) , (ECCV 2020) by *Douillard, Arthur, Cord, Matthieu, Ollion, Charles, Robert, Thomas and Valle, Eduardo* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2521-L2528) 
``` Novel knowledge distillation that trades efficiently rigidity and plasticity to learn large amount of small tasks ``` 
- [**Overcoming Catastrophic Forgetting With Unlabeled Data in the Wild**](https://arxiv.org/abs/1903.12648) , (ICCV 2019) by *Lee, Kibok, Lee, Kimin, Shin, Jinwoo and Lee, Honglak* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1012-L1020) 
``` Introducing global distillation loss and balanced finetuning; leveraging unlabeled data in the open world setting (Single-head setting) ``` 
- [**Large scale incremental learning**](https://arxiv.org/abs/1905.13260) , (CVPR 2019) by *Wu, Yue, Chen, Yinpeng, Wang, Lijuan, Ye, Yuancheng, Liu, Zicheng, Guo, Yandong and Fu, Yun* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1023-L1031) 
``` Introducing bias parameters to the last fully connected layer to resolve the data imbalance issue (Single-head setting) ``` 
- **Continual Reinforcement Learning deployed in Real-life using PolicyDistillation and Sim2Real Transfer**, (ICML Workshop 2019) by *Kalifou, René Traoré, Caselles-Dupré, Hugo, Lesort, Timothée, Sun, Te, Diaz-Rodriguez, Natalia and Filliat, David * [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1208-L1214) 
- [**Lifelong learning via progressive distillation and retrospection**](https://arxiv.org/abs/1905.13260) , (ECCV 2018) by *Hou, Saihui, Pan, Xinyu, Change Loy, Chen, Wang, Zilei and Lin, Dahua* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1034-L1042) 
``` Introducing an expert of the current task in the knowledge distillation method (Multi-head setting) ``` 
- [**End-to-end incremental learning**](https://arxiv.org/abs/1807.09536) , (ECCV 2018) by *Castro, Francisco M, Marin-Jimenez, Manuel J, Guil, Nicolas, Schmid, Cordelia and Alahari, Karteek* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1045-L1053) 
``` Finetuning the last fully connected layer with a balanced dataset to resolve the data imbalance issue (Single-head setting) ``` 
- [**Learning without forgetting**](https://arxiv.org/abs/1606.09282) , (TPAMI 2017) by *Li, Zhizhong and Hoiem, Derek* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L685-L693) 
``` Functional regularization through distillation (keeping the output of the updated network on the new data close to the output of the old network on the new data) ``` 
- [**icarl: Incremental classifier and representation learning**](https://arxiv.org/abs/1611.07725) , (CVPR 2017) by *Rebuffi, Sylvestre-Alvise, Kolesnikov, Alexander, Sperl, Georg and Lampert, Christoph H* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1056-L1064) 
``` Binary cross-entropy loss for representation learning \& exemplar memory (or coreset) for replay (Single-head setting) ``` 

## Rehearsal Methods
- [**Transfer without Forgetting**](https://arxiv.org/abs/2206.00388) , (ECCV 2022) by *Boschini, Matteo, Bonicelli, Lorenzo, Porrello, Angelo, Bellitto, Giovanni, Pennisi, Matteo, Palazzo, Simone, Spampinato, Concetto and Calderara, Simone* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1-L8) 
- [**Effects of Auxiliary Knowledge on Continual Learning**](https://arxiv.org/abs/2206.02577) , (ICPR 2022) by *Bellitto, Giovanni, Pennisi, Matteo, Palazzo, Simone, Bonicelli, Lorenzo, Boschini, Matteo, Calderara, Simone and Spampinato, Concetto* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L113-L120) 
- [**Rethinking Experience Replay: a Bag of Tricks for Continual Learning**](https://ieeexplore.ieee.org/abstract/document/9412614) , (ICPR 2021) by *Buzzega, Pietro, Boschini, Matteo, Porrello, Angelo and Calderara, Simone* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L212-L223) 
- [**Graph-Based Continual Learning**](https://openreview.net/forum?id=HHSEKOnPvaO) , (ICLR 2021) by *Binh Tang and David S. Matteson* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2596-L2603) 
``` Use graphs to link saved samples and improve the memory quality. ``` 
- [**Online Class-Incremental Continual Learning with Adversarial Shapley Value**](https://arxiv.org/pdf/2009.00093.pdf) , (2021) by *Dongsub Shim, Zheda Mai, Jihwan Jeong\*, Scott Sanner, Hyunwoo Kim and Jongseong Jang* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2753-L2760) 
``` Use Shapley Value adversarially to select which samples to relay ``` 
- [**Dark Experience for General Continual Learning: a Strong, Simple Baseline**](https://papers.nips.cc/paper/2020/file/b704ea2c39778f07c617f6b7ce480e9e-Paper.pdf) , (NeurIPS 2020) by *Buzzega, Pietro, Boschini, Matteo, Porrello, Angelo, Abati, Davide and Calderara, Simone* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L225-L235) 
- **GDumb: A simple approach that questions our progress in continual learning**, (ECCV 2020) by *Prabhu, Ameya, Torr, Philip HS and Dokania, Puneet K* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L237-L245) 
``` introduces a super simple methods that outperforms almost all methods in all of the CL benchmarks. We need new better benchamrks ``` 
- [**Continual Learning: Tackling Catastrophic Forgetting in Deep Neural Networks with Replay Processes**](https://arxiv.org/abs/2007.00487) , (2020) by *Timothée Lesort* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L292-L301) 
- [**Imbalanced Continual Learning with Partitioning Reservoir Sampling**](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580409.pdf) , (ECCV 2020) by *Kim, Chris Dongjoo, Jeong, Jinseo and Kim, Gunhee* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2425-L2432) 
- [**PODNet: Pooled Outputs Distillation for Small-Tasks Incremental Learning**](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650086.pdf) , (ECCV 2020) by *Douillard, Arthur, Cord, Matthieu, Ollion, Charles, Robert, Thomas and Valle, Eduardo* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2521-L2528) 
``` Novel knowledge distillation that trades efficiently rigidity and plasticity to learn large amount of small tasks ``` 
- [**{REMIND Your Neural Network to Prevent Catastrophic Forgetting}**](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650681.pdf) , (ECCV 2020) by *Hayes, Tyler L., Kafle, Kushal, Shrestha, Robik and
Acharya, Manoj and Kanan, Christopher* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2540-L2548) 
- [**Efficient Lifelong Learning with A-GEM**](https://arxiv.org/abs/1812.00420) , (ICLR 2019) by *Chaudhry, Arslan, Ranzato, Marc’Aurelio, Rohrbach, Marcus and Elhoseiny, Mohamed* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L400-L407) 
``` More efficient GEM; Introduces online continual learning ``` 
- [**Orthogonal Gradient Descent for Continual Learning**](https://arxiv.org/abs/1910.07104) , (2019) by *Mehrdad Farajtabar, Navid Azizan, Alex Mott and Ang Li* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L754-L763) 
``` projecting the gradients from new tasks onto a subspace in which the neural network output on previous task does not change and the projected gradient is still in a useful direction for learning the new task ``` 
- [**Gradient based sample selection for online continual learning**](http://papers.nips.cc/paper/9354-gradient-based-sample-selection-for-online-continual-learning.pdf) , (NeurIPS 2019) by *Aljundi, Rahaf, Lin, Min, Goujaud, Baptiste and Bengio, Yoshua* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L767-L777) 
``` sample selection as a constraint reduction problem based on the constrained optimization view of continual learning ``` 
- [**Online Continual Learning with Maximal Interfered Retrieval**](http://papers.nips.cc/paper/9357-online-continual-learning-with-maximal-interfered-retrieval.pdf) , (NeurIPS 2019) by *Aljundi, Rahaf and
, Lucas, Belilovsky, Eugene, Caccia, Massimo, Lin, Min, Charlin, Laurent and Tuytelaars, Tinne* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L781-L792) 
``` Controlled sampling of memories for replay to automatically rehearse on tasks currently undergoing the most forgetting ``` 
- [**Online Learned Continual Compression with Adaptative Quantization Module**](https://arxiv.org/abs/1911.08019) , (arXiv 2019) by *Caccia, Lucas, Belilovsky, Eugene, Caccia, Massimo and Pineau, Joelle* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L796-L803) 
``` Uses stacks of VQ-VAE modules to progressively compress the data stream, enabling better rehearsal ``` 
- [**Large scale incremental learning**](https://arxiv.org/abs/1905.13260) , (CVPR 2019) by *Wu, Yue, Chen, Yinpeng, Wang, Lijuan, Ye, Yuancheng, Liu, Zicheng, Guo, Yandong and Fu, Yun* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1023-L1031) 
``` Introducing bias parameters to the last fully connected layer to resolve the data imbalance issue (Single-head setting) ``` 
- **Learning a Unified Classifier Incrementally via Rebalancing**, (CVPR 2019) by *Hou, Saihui, Pan, Xinyu, Loy, Chen Change, Wang, Zilei and Lin, Dahua* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1068-L1075) 
- **Continual Reinforcement Learning deployed in Real-life using PolicyDistillation and Sim2Real Transfer**, (ICML Workshop 2019) by *Kalifou, René Traoré, Caselles-Dupré, Hugo, Lesort, Timothée, Sun, Te, Diaz-Rodriguez, Natalia and Filliat, David * [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1208-L1214) 
- [**Experience replay for continual learning**](https://arxiv.org/abs/1811.11682) , (NeurIPS 2019) by *Rolnick, David, Ahuja, Arun, Schwarz, Jonathan, Lillicrap, Timothy and Wayne, Gregory* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1416-L1424) 
- [**Gradient Episodic Memory for Continual Learning**](http://papers.nips.cc/paper/7225-gradient-episodic-memory-for-continual-learning.pdf) , (NeurIPS 2017) by *Lopez-Paz, David and Ranzato, Marc-Aurelio* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L422-L432) 
``` A model that alliviates CF via constrained optimization ``` 
- [**icarl: Incremental classifier and representation learning**](https://arxiv.org/abs/1611.07725) , (CVPR 2017) by *Rebuffi, Sylvestre-Alvise, Kolesnikov, Alexander, Sperl, Georg and Lampert, Christoph H* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1056-L1064) 
``` Binary cross-entropy loss for representation learning \& exemplar memory (or coreset) for replay (Single-head setting) ``` 
- [**Catastrophic Forgetting, Rehearsal and Pseudorehearsal**](https://doi.org/10.1080/09540099550039318) , (1995) by * Anthony   Robins * [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2030-L2043) 

## Generative Replay Methods
- [**Continual Learning: Tackling Catastrophic Forgetting in Deep Neural Networks with Replay Processes**](https://arxiv.org/abs/2007.00487) , (2020) by *Timothée Lesort* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L292-L301) 
- [**Brain-Like Replay For Continual Learning With Artificial Neural Networks**](https://baicsworkshop.github.io/pdf/BAICS_8.pdf) , (2020) by *van de Ven, Gido M, Siegelmann, Hava T and Tolias, Andreas S* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L370-L376) 
- [**Learning to remember: A synaptic plasticity driven framework for continual learning**](https://openaccess.thecvf.com/content_CVPR_2019/html/Ostapenko_Learning_to_Remember_A_Synaptic_Plasticity_Driven_Framework_for_Continual_CVPR_2019_paper.html) , (CVPR 2019) by *Ostapenko, Oleksiy, Puscas, Mihai, Klein, Tassilo, Jahnichen, Patrick and Nabi, Moin* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L260-L268) 
``` introdudes Dynamic generative memory (DGM) which relies on conditional generative adversarial networks with learnable connection plasticity realized with neural masking ``` 
- [**Generative Models from the perspective of Continual Learning**](https://hal.archives-ouvertes.fr/hal-01951954) , (IJCNN 2019) by *Lesort, Timothée, Caselles-Dupré, Hugo, Garcia-Ortiz, Michael, Goudou, Jean-Fran{\c c}ois and Filliat, David* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L909-L921) 
``` Extensive evaluation of CL methods for generative modeling ``` 
- [**Closed-loop Memory GAN for Continual Learning**](http://dl.acm.org/citation.cfm?id=3367471.3367504) , (IJCAI 2019) by *Rios, Amanda and Itti, Laurent* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1216-L1230) 
- [**Marginal replay vs conditional replay for continual learning**](https://arxiv.org/abs/1810.12069) , (ICANN 2019) by *Lesort, Timothée, Gepperth, Alexander, Stoian, Andrei and Filliat, David* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1361-L1370) 
``` Extensive evaluation of generative replay methods ``` 
- [**Generative replay with feedback connections as a general strategy for continual learning**](https://arxiv.org/abs/1809.10635) , (2018) by *Michiel van der Ven and Andreas S. Tolias* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L807-L815) 
``` smarter Generative Replay ``` 
- [**Continual learning with deep generative replay**](https://arxiv.org/abs/1705.08690) , (NeurIPS 2017) by *Shin, Hanul, Lee, Jung Kwon, Kim, Jaehong and Kim, Jiwon* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L436-L444) 
``` Introduces generative replay ``` 

## Dynamic Architectures or Routing Methods
- [**Avoiding Catastrophe: Active Dendrites Enable Multi-Task Learning in Dynamic Environments**](https://www.frontiersin.org/articles/10.3389/fnbot.2022.846219/full) , (2022) by *Iyer, Abhiram, Grewal, Karan, Velu, Akash, Souza, Lucas Oliveira, Forest, Jeremy and Ahmad, Subutai* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L32-L41) 
``` bio-inspired method which dynamically restrict and route information in a context-specific manner ``` 
- [**DyTox: Transformers for Continual Learning with DYnamic TOken eXpansion**](https://arxiv.org/abs/2111.11326) , (arXiv 2021) by *Douillard, Arthur, Ram{\'e}, Alexandre, Couairon, Guillaume and Cord, Matthieu* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L3268-L3275) 
- [**Supermasks in superposition**](https://arxiv.org/abs/2006.14769) , (2020) by *Wortsman, Mitchell, Ramanujan, Vivek, Liu, Rosanne, Kembhavi, Aniruddha, Rastegari, Mohammad, Yosinski, Jason and Farhadi, Ali* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L20-L29) 
``` a binary mask over the network is inferred based on the input, and only the masked part of the network is used to train/infer ``` 
- [**ORACLE: Order Robust Adaptive Continual Learning**](http://arxiv.org/abs/1902.09432) , (2019) by *Jaehong Yoon and
Saehoon Kim and
Eunho Yang and
Sung Ju Hwang* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L547-L563) 
- [**Learn to Grow: {A} Continual Structure Learning Framework for Overcoming
Catastrophic Forgetting**](http://arxiv.org/abs/1904.00310) , (2019) by *Xilai Li and
Yingbo Zhou and
Tianfu Wu and
Richard Socher and
Caiming Xiong* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2161-L2179) 
- [**Alleviating catastrophic forgetting using context-dependent gating and synaptic stabilization**](https://www.pnas.org/doi/pdf/10.1073/pnas.1803839115) , (2018) by *Masse, Nicolas Y, Grant, Gregory D and Freedman, David J* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L45-L56) 
``` a network trained to do CL where select subnetworks are used to learn each task; these subnetworks are chosen a priori ``` 
- [**Incremental Learning through Deep Adaptation**](https://openreview.net/forum?id=ryj0790hb) , (2018) by *Amir Rosenfeld and John K. Tsotsos* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L708-L714) 
- **Packnet: Adding multiple tasks to a single network by iterative pruning**, (CVPR 2018) by *Mallya, Arun and Lazebnik, Svetlana* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1078-L1085) 
- **Piggyback: Adapting a single network to multiple tasks by learning to mask weights**, (ECCV 2018) by *Mallya, Arun, Davis, Dillon and Lazebnik, Svetlana* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1087-L1094) 
- [**Continual Learning in Practice**](https://arxiv.org/abs/1903.05202) , (NeurIPS Workshop 2018) by *Diethe, Tom, Borchert, Tom, Thereska, Eno, Pigem, Borja de Balle and Lawrence, Neil* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2282-L2289) 
``` Proposes a reference architecture for a continual learning system ``` 
- **Growing a brain: Fine-tuning by increasing model capacity**, (CVPR 2017) by *Wang, Yu-Xiong, Ramanan, Deva and Hebert, Martial* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1096-L1103) 
- [**PathNet: Evolution Channels Gradient Descent in Super Neural Networks**](http://arxiv.org/abs/1701.08734) , (2017) by *Chrisantha Fernando and
Dylan Banarse and
Charles Blundell and
Yori Zwols and
David Ha and
Andrei A. Rusu and
Alexander Pritzel and
Daan Wierstra* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1751-L1771) 
- **Lifelong learning with dynamically expandable networks**, (arXiv 2017) by *Yoon, Jaehong, Yang, Eunho, Lee, Jeongtae and Hwang, Sung Ju* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2021-L2027) 
- [**Progressive Neural Networks**](https://arxiv.org/abs/1606.04671) , (2016) by *Rusu, A.~A., Rabinowitz, N.~C., Desjardins, G. and
Soyer, H., Kirkpatrick, J., Kavukcuoglu, K. and
Pascanu, R. and Hadsell, R.* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L716-L731) 
``` Each task have a specific model connected to the previous ones ``` 

## Hybrid Methods
- [**Continual learning with hypernetworks**](https://openreview.net/forum?id=SJgwNerKvB) , (ICLR 2020) by *Johannes von Oswald, Christian Henning, João Sacramento and Benjamin F. Grewe* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L960-L967) 
``` Learning task-conditioned hypernetworks for continual learning as well as task embeddings; hypernetwors offers good model compression. ``` 
- [**Compacting, Picking and Growing for Unforgetting Continual Learning**](https://arxiv.org/abs/1910.06562) , (NeurIPS 2019) by *Hung, Ching-Yi, Tu, Cheng-Hao, Wu, Cheng-En, Chen, Chien-Hung, Chan, Yi-Ming and Chen, Chu-Song* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L489-L497) 
``` Approach leverages the principles of deep model compression, critical weights selection, and progressive networks expansion. All enforced in an iterative manner ``` 
- [**A Neural Dirichlet Process Mixture Model for Task-Free Continual Learning**](https://arxiv.org/pdf/2001.00689.pdf) , (ICLR 2019) by *Lee, Soochan, Ha, Junsoo, Zhang, Dongsu and Kim, Gunhee* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1495-L1502) 
``` This paper introduces expansion-based approach for task-free continual learning ``` 

## Continual Few-Shot Learning
- [**Learning where to learn: Gradient sparsity in meta and continual learning**](https://proceedings.neurips.cc/paper/2021/hash/2a10665525774fa2501c2c8c4985ce61-Abstract.html) , (2021) by *Von Oswald, Johannes, Zhao, Dominic, Kobayashi, Seijin, Schug, Simon, Caccia, Massimo, Zucchet, Nicolas and Sacramento, Jo{\~a}o* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L202-L210) 
- [**Wandering Within a World: Online Contextualized Few-Shot Learning**](https://arxiv.org/abs/2007.04546) , (2020) by *Mengye Ren, Michael L. Iuzzolino, Michael C. Mozer and Richard S. Zemel* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L280-L288) 
``` proposes a new continual few-shot setting where spacial and temporal context can be leveraged to and unseen classes need to be predicted ``` 
- [**Defining Benchmarks for Continual Few-Shot Learning**](https://arxiv.org/abs/2004.11967) , (arXiv 2020) by *Antoniou, Antreas, Patacchiola, Massimiliano, Ochal, Mateusz and Storkey, Amos* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L322-L329) 
``` (title is a good enough summary) ``` 
- [**Online Fast Adaptation and Knowledge Accumulation: a New Approach to Continual Learning**](https://arxiv.org/abs/2003.05856) , (2020) by *Caccia, Massimo, Rodriguez, Pau, Ostapenko, Oleksiy, Normandin, Fabrice, Lin, Min, Caccia, Lucas, Laradji, Issam, Rish, Irina, Lacoste, Alexandre, Vazquez, David and Charlin, Laurent* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1428-L1435) 
``` Proposes a new approach to CL evaluation more aligned with real-life applications, bringing CL closer to Online Learning and Open-World learning ``` 
- [**Learning from the Past: Continual Meta-Learning via Bayesian Graph Modeling**](https://arxiv.org/abs/1911.04695) , (2019) by *Yadan Luo, Zi Huang, Zheng Zhang, Ziwei Wang, Mahsa Baktashmotlagh and Yang Yang* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L831-L840) 
- [**Online Meta-Learning**](http://proceedings.mlr.press/v97/finn19a.html) , (ICML 2019) by *Finn, Chelsea, Rajeswaran, Aravind, Kakade, Sham and Levine, Sergey* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L853-L868) 
``` defines Online Meta-learning; propsoses Follow the Meta Leader (FTML) (~ Online MAML) ``` 
- [**Reconciling meta-learning and continual learning with online mixtures of tasks**](http://papers.nips.cc/paper/9112-reconciling-meta-learning-and-continual-learning-with-online-mixtures-of-tasks.pdf) , (NeurIPS 2019) by *Jerfel, Ghassen, Grant, Erin, Griffiths, Tom and Heller, Katherine A* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L872-L882) 
``` Meta-learns a tasks structure; continual adaptation via non-parametric prior ``` 
- [**Deep Online Learning Via Meta-Learning: Continual Adaptation for Model-Based RL**](https://openreview.net/forum?id=HyxAfnA5tm) , (ICLR 2019) by *Anusha Nagabandi, Chelsea Finn and Sergey Levine* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L887-L894) 
``` Formulates an online learning procedure that uses SGD to update model parameters, and an EM with a Chinese restaurant process prior to develop and maintain a mixture of models to handle non-stationary task distribution ``` 
- [**Task Agnostic Continual Learning via Meta Learning**](https://arxiv.org/abs/1906.05201) , (2019) by *Xu He, Jakub Sygnowski, Alexandre Galashov, Andrei A. Rusu, Yee Whye Teh and Razvan Pascanu* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L983-L991) 
``` Introduces What \& How framework; enables Task Agnostic CL with meta learned task inference ``` 

## Meta-Continual Learning
- [**Learning where to learn: Gradient sparsity in meta and continual learning**](https://proceedings.neurips.cc/paper/2021/hash/2a10665525774fa2501c2c8c4985ce61-Abstract.html) , (2021) by *Von Oswald, Johannes, Zhao, Dominic, Kobayashi, Seijin, Schug, Simon, Caccia, Massimo, Zucchet, Nicolas and Sacramento, Jo{\~a}o* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L202-L210) 
- [**La-MAML: Look-ahead Meta Learning for Continual Learning**](https://arxiv.org/abs/2007.13904) , (2020) by *Gunshi Gupta, Karmesh Yadav and Liam Paull* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L271-L277) 
``` Proposes an online replay-based meta-continual learning algorithm with learning-rate modulation to mitigate catastrophic forgetting ``` 
- [**Learning to Continually Learn**](https://arxiv.org/abs/2002.09571) , (arXiv 2020) by *Beaulieu, Shawn, Frati, Lapo, Miconi, Thomas, Lehman, Joel, Stanley, Kenneth O, Clune, Jeff and Cheney, Nick* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1386-L1393) 
``` Follow-up of OML. Meta-learns an activation-gating function instead. ``` 
- [**Meta-Learning Representations for Continual Learning**](http://papers.nips.cc/paper/8458-meta-learning-representations-for-continual-learning.pdf) , (NeurIPS 2019) by *Javed, Khurram and White, Martha* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L818-L828) 
``` Introduces Learns how to continually learn (OML) i.e. learns how to do online updates without forgetting. ``` 
- [**Meta-learnt priors slow down catastrophic forgetting in neural networks**](https://arxiv.org/pdf/1909.04170.pdf) , (arXiv 2019) by *Spigler, Giacomo* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1396-L1403) 
``` Learning MAML in a Meta continual learning way slows down forgetting ``` 
- [**Learning to Learn without Forgetting By Maximizing Transfer and Minimizing Interference**](https://openreview.net/forum?id=B1gTShAct7) , (ICLR 2019) by *Matthew Riemer, Ignacio Cases, Robert Ajemian, Miao Liu, Irina Rish, Yuhai Tu and and Gerald Tesauro* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1407-L1414) 

## Lifelong Reinforcement Learning
- [**A Study of Continual Learning Methods for Q-Learning**](https://arxiv.org/abs/2206.03934) , (arXiv 2022) by *Bagus, Benedikt and Gepperth, Alexander* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L10-L17) 
``` Studies Q-Learning methods in CRL environments. When there's no task interference, (A-)GEM can outperform Experience Replay ``` 
- [**Co{MPS}: Continual Meta Policy Search**](https://openreview.net/forum?id=PVJ6j87gOHz) , (ICLR 2022) by *Glen Berseth, Zhiwei Zhang, Grace Zhang, Chelsea Finn and Sergey Levine* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L81-L88) 
``` Co{MPS} is a novel meta-policy search algorithm for task-agnostic continual RL ``` 
- [**Task-Agnostic Continual Reinforcement Learning: In Praise of a Simple Baseline**](https://arxiv.org/abs/2205.14495) , (arXiv 2022) by *Caccia, Massimo, Mueller, Jonas, Kim, Taesup, Charlin, Laurent and Fakoor, Rasool* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L91-L98) 
``` combines replay and an RNN to set a simple baseline for TACRL: shows that the baselines matches and surpasses previously thought upper bounds ``` 
- [**Modular Lifelong Reinforcement Learning via Neural Composition**](https://openreview.net/forum?id=5XmLzdslFNN) , (ICLR 2022) by *Jorge A Mendez, Harm van Seijen and ERIC EATON* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L135-L142) 
- [**Same State, Different Task: Continual Reinforcement Learning without Interference**](https://arxiv.org/abs/2106.02940) , (2021) by *Samuel Kessler, Jack Parker-Holder, Philip J. Ball, Stefan Zohren and Stephen J. Roberts* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L69-L77) 
``` learns multiple policies and cast policy-retrieval as a multi-arm bandit problem ``` 
- [**CoMPS: Continual Meta Policy Search**](https://arxiv.org/abs/2112.04467) , (2021) by *Glen Berseth, Zhiwei Zhang, Grace Zhang, Chelsea Finn and Sergey Levine* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L144-L153) 
- [**Reset-Free Lifelong Learning with Skill-Space Planning**](https://openreview.net/forum?id=HIGSa_3kOx3) , (ICLR 2021) by *Kevin Lu, Aditya Grover, Pieter Abbeel and Igor Mordatch* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2680-L2687) 
- [**Task-Agnostic Online Reinforcement Learning with an Infinite Mixture of Gaussian Processes**](https://arxiv.org/abs/2006.11441) , (2020) by *Mengdi Xu, Wenhao Ding, Jiacheng Zhu, Zuxin Liu, Baiming Chen and Ding Zhao* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L101-L109) 
``` uses an infinite mixture of Gaussian Processes to learn a task-agnostic policy ``` 
- [**Lifelong Policy Gradient Learning of Factored Policies for Faster Training Without Forgetting**](https://arxiv.org/abs/2007.07011) , (2020) by *Jorge A. Mendez, Boyu Wang and Eric Eaton* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L155-L165) 
- **Towards Continual Reinforcement Learning: A Review and Perspectives**, (2020) by *Khimya Khetarpal, Matthew Riemer, Irina Rish and Doina Precup* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L248-L256) 
``` A review on continual reinforcement learning ``` 
- [**Continual learning for robotics: Definition, framework, learning strategies, opportunities and challenges**](http://www.sciencedirect.com/science/article/pii/S1566253519307377) , (Information Fusion 2020) by *Timothée Lesort, Vincenzo Lomonaco, Andrei Stoian, Davide Maltoni, David Filliat and Natalia Díaz-Rodríguez* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1276-L1287) 
- [**Deep Online Learning Via Meta-Learning: Continual Adaptation for Model-Based RL**](https://openreview.net/forum?id=HyxAfnA5tm) , (ICLR 2019) by *Anusha Nagabandi, Chelsea Finn and Sergey Levine* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L887-L894) 
``` Formulates an online learning procedure that uses SGD to update model parameters, and an EM with a Chinese restaurant process prior to develop and maintain a mixture of models to handle non-stationary task distribution ``` 
- **Continual Reinforcement Learning deployed in Real-life using PolicyDistillation and Sim2Real Transfer**, (ICML Workshop 2019) by *Kalifou, René Traoré, Caselles-Dupré, Hugo, Lesort, Timothée, Sun, Te, Diaz-Rodriguez, Natalia and Filliat, David * [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1208-L1214) 
- [**Experience replay for continual learning**](https://arxiv.org/abs/1811.11682) , (NeurIPS 2019) by *Rolnick, David, Ahuja, Arun, Schwarz, Jonathan, Lillicrap, Timothy and Wayne, Gregory* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1416-L1424) 
- [**PathNet: Evolution Channels Gradient Descent in Super Neural Networks**](http://arxiv.org/abs/1701.08734) , (2017) by *Chrisantha Fernando and
Dylan Banarse and
Charles Blundell and
Yori Zwols and
David Ha and
Andrei A. Rusu and
Alexander Pritzel and
Daan Wierstra* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1751-L1771) 
- **Incremental robot learning of new objects with fixed update time**, (2017) by *R. {Camoriano}, G. {Pasquale}, C. {Ciliberto}, L. {Natale}, L. {Rosasco} and G. {Metta}* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1889-L1901) 

## Task-Agnostic Lifelong Reinforcement Learning
- [**Co{MPS}: Continual Meta Policy Search**](https://openreview.net/forum?id=PVJ6j87gOHz) , (ICLR 2022) by *Glen Berseth, Zhiwei Zhang, Grace Zhang, Chelsea Finn and Sergey Levine* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L81-L88) 
``` Co{MPS} is a novel meta-policy search algorithm for task-agnostic continual RL ``` 
- [**Task-Agnostic Continual Reinforcement Learning: In Praise of a Simple Baseline**](https://arxiv.org/abs/2205.14495) , (arXiv 2022) by *Caccia, Massimo, Mueller, Jonas, Kim, Taesup, Charlin, Laurent and Fakoor, Rasool* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L91-L98) 
``` combines replay and an RNN to set a simple baseline for TACRL: shows that the baselines matches and surpasses previously thought upper bounds ``` 
- [**Same State, Different Task: Continual Reinforcement Learning without Interference**](https://arxiv.org/abs/2106.02940) , (2021) by *Samuel Kessler, Jack Parker-Holder, Philip J. Ball, Stefan Zohren and Stephen J. Roberts* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L69-L77) 
``` learns multiple policies and cast policy-retrieval as a multi-arm bandit problem ``` 
- [**CoMPS: Continual Meta Policy Search**](https://arxiv.org/abs/2112.04467) , (2021) by *Glen Berseth, Zhiwei Zhang, Grace Zhang, Chelsea Finn and Sergey Levine* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L144-L153) 
- [**Task-Agnostic Online Reinforcement Learning with an Infinite Mixture of Gaussian Processes**](https://arxiv.org/abs/2006.11441) , (2020) by *Mengdi Xu, Wenhao Ding, Jiacheng Zhu, Zuxin Liu, Baiming Chen and Ding Zhao* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L101-L109) 
``` uses an infinite mixture of Gaussian Processes to learn a task-agnostic policy ``` 
- [**Deep Online Learning Via Meta-Learning: Continual Adaptation for Model-Based RL**](https://openreview.net/forum?id=HyxAfnA5tm) , (ICLR 2019) by *Anusha Nagabandi, Chelsea Finn and Sergey Levine* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L887-L894) 
``` Formulates an online learning procedure that uses SGD to update model parameters, and an EM with a Chinese restaurant process prior to develop and maintain a mixture of models to handle non-stationary task distribution ``` 

## Continual Generative Modeling
- [**Continual Unsupervised Representation Learning**](https://arxiv.org/pdf/1910.14481.pdf) , (2019) by *Dushyant Rao, Francesco Visin, Andrei A. Rusu, Yee Whye Teh, Razvan Pascanu and Raia Hadsell* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L897-L906) 
``` Introduces unsupervised continual learning (no task label and no task boundaries) ``` 
- [**Generative Models from the perspective of Continual Learning**](https://hal.archives-ouvertes.fr/hal-01951954) , (IJCNN 2019) by *Lesort, Timothée, Caselles-Dupré, Hugo, Garcia-Ortiz, Michael, Goudou, Jean-Fran{\c c}ois and Filliat, David* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L909-L921) 
``` Extensive evaluation of CL methods for generative modeling ``` 
- [**Closed-loop Memory GAN for Continual Learning**](http://dl.acm.org/citation.cfm?id=3367471.3367504) , (IJCAI 2019) by *Rios, Amanda and Itti, Laurent* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1216-L1230) 
- [**Lifelong Generative Modeling**](https://arxiv.org/abs/1705.09847) , (arXiv 2017) by *Ramapuram, Jason, Gregorova, Magda and Kalousis, Alexandros* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L924-L931) 

## Biologically-Inspired
- [**Avoiding Catastrophe: Active Dendrites Enable Multi-Task Learning in Dynamic Environments**](https://www.frontiersin.org/articles/10.3389/fnbot.2022.846219/full) , (2022) by *Iyer, Abhiram, Grewal, Karan, Velu, Akash, Souza, Lucas Oliveira, Forest, Jeremy and Ahmad, Subutai* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L32-L41) 
``` bio-inspired method which dynamically restrict and route information in a context-specific manner ``` 
- [**A rapid and efficient learning rule for biological neural circuits**](https://www.biorxiv.org/content/10.1101/2021.03.10.434756v1.full.pdf) , (2021) by *Eren Sezener, Agnieszka Grabska-Barwinska, Dimitar Kostadinov, Maxime Beau, Sanjukta Krishnagopal, David Budden, Marcus Hutter, Joel Veness, Matthew M. Botvinick, Claudia Clopath, Michael H{\"a}usser and Peter E. Latham* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L59-L66) 
- [**Alleviating catastrophic forgetting using context-dependent gating and synaptic stabilization**](https://www.pnas.org/doi/pdf/10.1073/pnas.1803839115) , (2018) by *Masse, Nicolas Y, Grant, Gregory D and Freedman, David J* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L45-L56) 
``` a network trained to do CL where select subnetworks are used to learn each task; these subnetworks are chosen a priori ``` 

## Miscellaneous
- [**Learning causal models online**](https://arxiv.org/abs/2006.07461) , (arXiv 2020) by *Javed, Khurram, White, Martha and Bengio, Yoshua* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L192-L199) 

## Applications
- [**CLOPS: Continual Learning of Physiological Signals**](https://arxiv.org/abs/2004.09578) , (arXiv 2020) by *Kiyasseh, Dani, Zhu, Tingting and Clifton, David A* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L359-L366) 
``` a healthcare-specific replay-based method to mitigate destructive interference during continual learning ``` 
- [**LAMAL: LAnguage Modeling Is All You Need for Lifelong Language Learning**](https://openreview.net/forum?id=Skgxcn4YDS) , (ICLR 2020) by *Fan-Keng Sun, Cheng-Hao Ho and Hung-Yi Lee* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1477-L1484) 
- [**Compositional Language Continual Learning**](https://openreview.net/forum?id=rklnDgHtDS) , (ICLR 2020) by *Yuanpeng Li, Liang Zhao, Kenneth Church and Mohamed Elhoseiny* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1506-L1513) 
``` method for compositional continual learning of sequence-to-sequence models ``` 
- [**Incremental Lifelong Deep Learning for Autonomous Vehicles**](https://ieeexplore.ieee.org/document/8569992) , (2018) by *Pierre, John M.* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L167-L178) 
- [**Unsupervised real-time anomaly detection for streaming data**](https://www.sciencedirect.com/science/article/pii/S0925231217309864) , (2017) by *Ahmad, Subutai, Lavin, Alexander, Purdy, Scott and Agha, Zuha* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L332-L342) 
``` HTM applied to real-world anomaly detection problem ``` 
- [**Continuous online sequence learning with an unsupervised neural network model**](https://arxiv.org/abs/1512.05463) , (2016) by *Cui, Yuwei, Ahmad, Subutai and Hawkins, Jeff* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L345-L356) 
``` HTM applied to a prediction problem of taxi passenger demand ``` 

## Thesis
- [**Continual Learning: Tackling Catastrophic Forgetting in Deep Neural Networks with Replay Processes**](https://arxiv.org/abs/2007.00487) , (2020) by *Timothée Lesort* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L292-L301) 
- [**Continual Learning with Deep Architectures**](http://amsdottorato.unibo.it/9073/1/vincenzo_lomonaco_thesis.pdf) , (2019) by *Vincenzo Lomonaco* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1643-L1649) 
- [**Continual Learning in Neural Networks**](https://arxiv.org/abs/1910.02718) , (arXiv 2019) by *Aljundi, Rahaf* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2115-L2122) 
- [**Continual learning in reinforcement environments**](https://www.cs.utexas.edu/~ring/Ring-dissertation.pdf) , (1994) by *Ring, Mark Bishop* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1716-L1723) 

## Libraries
- [**Sequoia - Towards a Systematic Organization of Continual Learning Research**](https://github.com/lebrice/Sequoia) , (2021) by *Fabrice Normandin, Florian  Golemo,  Oleksiy Ostapenko,  Matthew Riemer,  Pau Rodriguez,  Julio Hurtado,  Khimya Khetarpal, Timothée Lesort,  Laurent Charlin, Irina Rish and Massimo Caccia* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2906-L2915) 
``` A library that unifies Continual Supervised and Continual Reinforcement Learning research ``` 
- [**Avalanche: an End-to-End Library for Continual Learning**](https://avalanche.continualai.org/) , (2021) by *Vincenzo Lomonaco, Lorenzo Pellegrini, Andrea Cossu, Gabriele Graffieti and Antonio Carta* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2928-L2936) 
``` A library for Continual Supervised Learning ``` 
- [**Continuous Coordination As a Realistic Scenario for Lifelong Learning**](https://github.com/chandar-lab/Lifelong-Hanabi) , (2021) by *Hadi Nekoei, Akilesh Badrinaaraayanan, Aaron Courville and Sarath Chandar* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2939-L2948) 
``` a multi-agent lifelong learning testbed that supports both zero-shot and few-shot settings. ``` 
- **River: machine learning for streaming data in Python**, (2020) by *Jacob Montiel, Max Halford, Saulo Martiello Mastelini
and Geoffrey Bolmier, Raphael Sourty, Robin Vaysse
and Adil Zouitine, Heitor Murilo Gomes, Jesse Read
and Talel Abdessalem and Albert Bifet* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2561-L2572) 
``` A library for online learning. ``` 
- **Continuum, Data Loaders for Continual Learning**, (2020) by *Douillard, Arthur and Lesort, Timothée* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2575-L2583) 
``` A library proposing continual learning scenarios and metrics. ``` 
- [**Framework for Analysis of Class-Incremental Learning**](https://github.com/mmasana/FACIL) , (arXiv 2020) by *Masana, Marc, Liu, Xialei, Twardowski, Bartlomiej, Menta, Mikel, Bagdanov, Andrew D and van de Weijer, Joost* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2918-L2925) 
``` A library for Continual Class-Incremental Learning ``` 

## Workshops
- [**Workshop on Continual Learning at ICML 2020**](https://sites.google.com/view/cl-icml/organizers?authuser=0) , (2020) by *Rahaf Aljundi, Haytham Fayek, Eugene Belilovsky, David Lopez-Paz, Arslan Chaudhry, Marc Pickett, Puneet Dokania, Jonathan Schwarz and Sayna Ebrahimi* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L303-L310) 
- [**4th Lifelong Machine Learning Workshop at ICML 2020**](https://openreview.net/group?id=ICML.cc/2020/Workshop/LifelongML#accept) , (2020) by *Shagun Sodhani, Sarath Chandar, Balaraman Ravindran and Doina Precup* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L313-L320) 
- **CVPR 2020 Continual Learning in Computer Vision Competition: Approaches, Results, Current Challenges and Future Directions**, (arXiv 2020) by *Lomonaco, Vincenzo, Pellegrini, Lorenzo, Rodriguez, Pau, Caccia, Massimo, She, Qi, Chen, Yu, Jodelet, Quentin, Wang, Ruiping, Mai, Zheda, Vazquez, David and others* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1517-L1523) 
``` surveys the results of the first CL competition at CVPR ``` 
- [**1st Lifelong Learning for Machine Translation Shared Task at WMT20 (EMNLP 2020)**](http://www.statmt.org/wmt20/lifelong-learning-task.html) , (2020) by *Loïc Barrault, Magdalena Biesialska, Marta R. Costa-jussà, Fethi Bougares and  Olivier Galibert* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2744-L2746) 
