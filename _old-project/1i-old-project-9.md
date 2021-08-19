---
title: "Exploring Market Approaches to Networking Problems"
excerpt: "Supported in part by NSF grant CNS-0915982"
collection: old-project
---

This project investigated a number of questions at the intersection of networking and economics, i.e., how to apply tools and techniques
from the field of economics to networking problems.

One such question involved developing mechanism to address the growth of core Internet routing tables.
The growth of core Internet routing tables is obviously a direct consequence of the growth of the Internet itself. However, it has been proceeding at a pace that 
far exceeds that of the Internet growth, and this is threatening the scalability of the Internet routing system, both in the short-term (most routers have hard 
limits on the number of routes they can store) and in the long-term (it out-paces the rate of improvement from technology itself). The main culprit behind this trend 
is the desire for individual "sites" to improve the reliability of their Internet connectivity; clearly a natural desire given the growing dependency on Internet connectivity. 
This desire for better reliability commonly manifests itself through multi-homing decisions, i.e., connectivity to the Internet through more than one provider to enjoy the 
benefits of greater path diversity, and herein lies the problem. When sites are multi-homed, their individual address sub-block are advertised by the different providers to 
which they connect, and this typically affects the ability of upstream providers to aggregate those routes; hence creating additional entries in core Internet routing tables.
One approach we investigated is the use of market mechanisms to better redistribute the cost of additional routing entries caused by multi-homing to the sites responsible for those new entries. 
The hope is that this redistribution can help control the growth of routing tables or at least ensure that their growth is borne by those that are causing it and benefit from it.

The project also sought to more broadly explore the use of market mechanisms, and in particular pricing, to tackle a number of technical networking problems, including aspects related to promoting the adoption 
of those solutions.  A case in point was "user-provided connectivity", or in other words, leveraging the connectivity of users in lieu of network infrastructure, where one important issue
was how to incentivize the sharing this required.  

### Penn Contributors

* [Hadi Afrasiabi](https://www.linkedin.com/in/afrasiabi/)
* [Roch Guerin](https://www.cse.wustl.edu/~guerin/) 
* [Kin-Wah (Eric) Kwong](https://www.linkedin.com/in/kkw825/) 

### Publications

* M. H. Afrasiabi and R. Guerin, *"Exploring User-Provided Connectivity"* [(long-version)](http://openscholarship.wustl.edu/cse_research/157) [(ToN version)](http://dl.acm.org/authorize?N21662). 
IEEE/ACM Transactions on Networking, Vol. 24, No. 1, February 2016, pp. 542-554.
* M. H. Afrasiabi and R. Guerin, [*"Pricing Strategies for User-Provided Connectivity Services."*](http://repository.upenn.edu/ese_papers/603) 
Proc. [IEEE INFOCOM 2012 mini-conference](http://www.ieee-infocom.org/), Orlando, FL, March 2012.
* M. H. Afrasiabi and R. Guerin, [*"Exploring User-Provided Connectivity - A Simple Model."*](http://repository.upenn.edu/ese_papers/600) 
Proc. [ICQT'11 Workshop](http://userver.ftw.at/ICQT/ICQT11.htm), Paris, France, October 2011.
* K.-W. Kwong and R. Guerin, [*"Controlling the Growth of Internet Routing Tables Through Market Mechanisms."*](http://repository.upenn.edu/ese_papers/561) 
Proc. ACM ReArch 2010 Workshop, Philadelphia, PA, November 2010
