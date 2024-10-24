---
title: "Exploring the Benefits of Non-Work-Conserving Networking"
excerpt: "Supported by NSF CNS-2006530 and previously a gift from Google"
collection: portfolio
date: 2021-01-01
---

This project was originally initiated through a gift from Google and is currently supported by NSF grant CNS-2006530.
Its focus is on exploring options for meeting the performance requirement of different traffic types on a shared
network, while minimizing the amount of bandwidth that the network requires to achieve this goal.  Performance metric
of interest are in the form of delay bound, and it is assumed that all traffic entering the netwoor is rate controlled,
e.g., through a token bucket.  One of the project's goal is to explore the trade-off associated with using simple
schedulers in terms of the added bandwidth they require.  Another goal is to investigate the extent to which ingress
reshaping of traffic flows can be of benefit in reducing bandwidth requirements.

### Main Results
* Established the benefits of reprofiling for FIFO and static priority schedulers in the single hop case, and developed
algorithms for "optimal" reprofiling solutions.  The addition of (judicious) reprofiling allowed those simpler schedulers
to perform nearly as well as optimal (EDF) schedulers in most configurations. (See papers 1. and 2. below for details).
* Established that, in the multiple hop setting, (judicious) reprofiling can be of benefit even when using optimal schedulers
such as EDF.  The intuition is that the cost (delay) of reprofiling is incurred once, but its benefits (from smoother traffic)
accrue at every hop.  Computing optimal reprofiling solutions is intractable, but efficient heuristics were developed and validated 
on a range of different configurations. (See paper 3. below for details).  

### Contributors
* [Roch Guerin](https://www.cse.wustl.edu/~guerin/) (WashU)
* [Jiaming Qiu](https://qiujiaming315.github.io/#/) (WashU)
* [Henry Sariowan](https://www.linkedin.com/in/sariowan/) (Google)

### Former Contributors
* [Jiayi Song](https://www.linkedin.com/in/jiayi-song-1163a0137/) (graduated Feb. 2022, now at Byte Dance)

### Publications

1. J. Song, R. Guerin, and H. Sariowan, ["*Minimizing network bandwidth under latency constraints: The single node case.*"](https://arxiv.org/abs/2104.02222) 
Proc. [ITC'33](https://itc33.org/), Avignon, France, August 2021.
2. J. Song, J. Qiu, R. Guerin, and H. Sariowan, ["*On the Benefits of Traffic `Reprofiling’ The Single Hop Case.*"](https://arxiv.org/abs/2104.02222)
[IEEE/ACM Transactions in Networking](https://sites.google.com/view/ieee-acm-ton/home), 2024
    - [Extended arXiv version](https://arxiv.org/pdf/2104.02222)
3. J. Qiu, J. Song, R. Guerin, and H. Sariowan, ["*On the Benefits of Traffic `Reprofiling’ The Multiple Hops Case - Part I.*"](https://doi.org/10.1109/TNET.2024.3392030)
[IEEE/ACM Transactions in Networking](https://sites.google.com/view/ieee-acm-ton/home), 2024
    - [Extended arXiv version](https://arxiv.org/pdf/2404.09087)
    - [Code](https://github.com/qiujiaming315/traffic-reprofiling)