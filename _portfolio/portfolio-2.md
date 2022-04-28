---
title: "Edge Computing"
excerpt: "This is a recent and still evolving project exploring various problems that arise when deploying edge computing solutions"
collection: portfolio
date: 2021-01-02
---

This project grew out of an earlier project on cloud computing and is concerned with scenarios where different "tiers" of compute resources are available over a network and can be used to realize a given computational task.
A prime example is that of edge computing with local (IoT) devices not only acquiring data, but also capable of performing some limited computations, with edge and potentially cloud servers available to supplement those local computations.
Our first foray in exploring that space involved edge classification where cameras are responsible for both image capture and local classification, 
but with an accuracy limited by the camera's processing ability. Because classification results are accompanied by a confidence estimate, the camera can then offload loow confidence results to
an edge server equipped with greater compute resources capable of more accurate classification.  Such offloading decisions, however, have a (network and compute) cost, and therefore rate-controlled by way of a token bucket.
The goal is then to devise a simple algorithm for the camera to decide which images to offload so as to maximize classification accuracy under the constraints imposed by the token bucket.

### Current Contributors  

* [Roch Guerin](https://www.cse.wustl.edu/~guerin/) (WashU)
* [Chenyang Lu](https://www.cse.wustl.edu/~lu/) (WashU)
* [Jiaming Qiu](https://github.com/qiujiaming315/JiamingQiu-personal-webpage) (WashU)
* [Ruiqi Wang](https://www.linkedin.com/in/rickywrq/) (WashU)

### Former Contributors

* [Ayan Chakrabarti](https://projects.ayanc.org/) (formerly at WashU, but now at Google)

### Related Publications

* A. Chakrabarti, R. Guerin, C. Lu, and J. Liu [*"Real-Time Edge Classification: Optimal Offloading under Token Bucket Constraints."*](https://arxiv.org/abs/2010.13737) 
Proc. [2021 ACM/IEEE Symposium on Edge Computing (SEC)](http://acm-ieee-sec.org/2021/), San Jose, CA, December 2021.

-----------------------------

