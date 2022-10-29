---
title: "Traffic engineering in IP networks"
excerpt: "Supported in part by NSF grants ANI-9902943 & ITR-0085930 as well as by a gift from Sprint ATL"
collection: old-project
---

This work was aimed at better understanding what is achievable using different traffic engineering techniques, 
and more important how one can devise solutions that are not highly sensitive to the quality of the "input" on 
which traffic engineering decisions are based. One problem that was investigated included how to best group 
traffic flows to minimize the number of distinct paths that had to be established in order to achieve optimal 
performance, and how this grouping affected both long term and short term performance. Another problem focused 
on devising minor modification to existing IP forwarding in order to allow the implementation of near optimal 
traffic distribution over existing IP networks. Yet another area of investigation involved evaluating traffic 
engineering solutions that can provide resilience to changes caused by link or node failures or by fluctuations 
in traffic patterns. The work was partly carried out in collaboration with Christophe Diot (now at Google) and 
his former group at Sprint ATL. Another aspect of this work, investigated the use of overlay networks to deliver 
better service "guarantees" over IP networks by leveraging the (path) diversity offered by the availability of a 
large number of peers. Part of this investigation was carried in the context of real-time applications such as 
VoIP and video (see above), but another area of focus was to develop simple techniques for quickly identifying 
peers that could act as "good" relay nodes for alternate overlay paths, i.e., overlay paths with performance that 
was largely uncorrelated with that of the default path. The challenge was to retain the benefits of having access 
to a very large number of possible choices, while devising simple and scalable solutions, i.e., that required 
little processing and only minimal storage.  

### Penn Contributors

* [Roch Guerin](https://www.cse.wustl.edu/~guerin/) 
* [Yaqing Huang](https://www.linkedin.com/in/yaqing-huang-a346a8a0/)
* [Ashwin Sridharan](https://www.linkedin.com/in/ashwin-sridharan-0128043/)
* [Shu Tao](https://www.linkedin.com/in/shu-tao-8940a54/)   

### Publications

* A. Sridharan, S. Bhattacharyya, C. Diot, R. Guerin, J. Jetcheva, and N. Taft, [*"On The Impact of Aggregation on The Performance of Traffic Aware Routing."*](http://seas.upenn.edu/~guerin/publications/aggreg.pdf) Technical Report, University of Pennsylvania, June 2000 (short version presented at [ITC'17](https://itc-conference.org/itc-library/itc17.html), Salvador da Bahia, Brazil, September 24-28, 2001).
* R. Guerin and A. Orda, [*"Computing Shortest Paths for Any Number of Hops."*](http://repository.upenn.edu/ese_papers/28) IEEE/ACM Transactions on Networking, Vol. 10, No. 5, pp. 613-620, October 2002.
* A. Sridharan, R. Guerin and C. Diot, [*"Achieving Near-Optimal Traffic Engineering Solutions for Current OSPF/IS-IS Networks."*](http://repository.upenn.edu/ese_papers/106) IEEE/ACM Trans. Netw. Vol. 13, No. 2, April 2005. For a [short version](http://repository.upenn.edu/ese_papers/26), see also the proceedings of [INFOCOM 2003](http://www.ieee-infocom.org/2003/), San Francisco, CA, April 2003.
* A. Sridharan and R. Guerin, [*"Making IGP Routing Robust to Link Failures."*](http://repository.upenn.edu/ese_papers/108) In Proceedings of [Networking'2005](http://www.cs.uwaterloo.ca/conferences/networking2005/), University of Waterloo, Ontario, Canada, May 2005.
* Y. Huang and R. Guerin, [*"Does Over-Provisioning Become More or Less Efficient as Networks Grow Larger?"*](http://repository.upenn.edu/ese_papers/112) In Proceedings [ICNP’2005](http://csr.bu.edu/icnp2005/), Boston, MA, November 2005.
* T. Fei, S. Tao, L. Gao, and R. Guerin, [*"How to Select a Good Alternate Path in Large Peer-to-Peer Systems?"*](http://repository.upenn.edu/ese_papers/149) In Proceedings [INFOCOM 2006](http://www.ieee-infocom.org/2006/), Barcelona, Spain, April 2006.
* T. Fei, S. Tao, L. Gao, R. Guerin, and Z.-L. Zhang, [*"Light-Weight Overlay Path Selection in a Peer-to-Peer Environment."*](http://repository.upenn.edu/ese_papers/170) In Proceedings [2006 Global Internet Workshop](https://infocom2006.ieee-infocom.org/global_internet.htm), Barcelona, Spain, April 2006.
