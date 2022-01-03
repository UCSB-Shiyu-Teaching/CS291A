# CS291: Adversarial Machine Learning

Instructor: [Dr. Shiyu Chang](https://code-terminator.github.io)

* Lecture time: Tuesday and Thursday 3pm - 5pm

* Office hours: After class or by appointment

## Course prerequisites

* Machine learning and deep learning (we will not cover what is classification or what is ResNet 50)
* Math: multivariate calculus, linear algebra, probability theory, and optimization 
* Programing: Python and deep learning tools (e.g., Pytorch/Tensorflow) 
* Document editing: LaTex 

## Topics we plan to cover
* Reviews: 
    * Optimization (convexity, KKT conditions, first-order optimization methods)

* Attack methods: 
    * Prediction-evasion attack (FGSM, PGD, physical attack, white-box v.s. black-box)
    * Data-poisoning attack (clean-label backdoor attack, feature collision attack, general bi-level formulation)

* Defense methods: 
    * Adversarial training (algorithms and min-max optimization)
    * Certified defense (robust certification and randomized smoothing)
    * Semi-supervised/unsupervised defense (self-supervision and contrastive learning)
    * Fast adversarial training (pros and cons, robust overfitting and gradient alignment)

* Other aspects of trustworthy machine learning:
    * Attack and defense beyond continuous inputs (discrete inputs, text, graph, program)
    * Connections and trade-offs between different trustworthy metrics (accuracy, explanation, fairness and robustness)
    
**Lecture slides will be posted on GauchoSpace.**

## Grading policy
* Homework (65%): 
    * Two homework total (hw1 due around midterm, hw2 hue at final week)
    * Expect homework to be long (but you will have 3 - 4 weeks for each homework)
    * No handwritten homework: LaTex generated pdf report (NeurIPS template) + code (Colab notebook or python code)
    * Due at 11:59 pm PST on the due date (**absolutely no late homework**)

* Final project (35%): 
    * Team presentation (2-3 students per team, 30 minutes, in-class)
    * Course-related research paper from: recent work accepted by ICLR, submission to ICML, or interesting work on arXiv 
    * Presentation format:  introduction, related work, problem statement/formulation, proposed methods, experiment justification, ablation studies, and **your own thinking and validation (enhanced solution / formulation to improve the proposed method)**. 
    * Ambitious goal: novel project can be shaped and extended for submission to conferences/workshops
