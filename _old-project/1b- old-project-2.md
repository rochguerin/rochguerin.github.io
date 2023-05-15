---
title: "Application versus network level performance"
excerpt: "Supported in part by NSF grants ANI-9906855 & ITR-0085930"
collection: old-project
---

This work aimed at a better understanding of how changes in network performance (and service parameters) affect the performance seen by applications.
One suite of experiments involved passing packet video streams through policers with different combination of parameters, and evaluating (quantitatively and qualitatively) 
the evolution of application level performance. The quantitative evaluation of video quality was done using the [VQM tool](http://www.its.bldrdoc.gov/n3/video/Default.htm) developed by 
[The Institute for Telecommunications Science](http://www.its.bldrdoc.gov/) and was carried out over both a local testbed and the wide area [QBone testbed](https://web.archive.org/web/20100311063500/http://www.isoc.org/isoc/conferences/inet/99/proceedings/4f/4f_1.htm).
Testing over the QBone infrastructure was done in collaboration with members of the [PennNet](https://www.isc.upenn.edu/pennnet) and [Computing](https://cets.seas.upenn.edu/) departments 
of the [University of Pennsylvania](http://www.upenn.edu/) and with researchers at [iCAIR](https://www.icair.org/) and the [IBM T.J. Watson Research Center](https://www.research.ibm.com/labs/watson/). 
Additional experiments were conducted for both voice and video application in collaboration with other researchers at UMass and UMinn. over a wide-area testbed connecting all three sites. 
Exploring how to accurately and easily monitor the quality of video transmissions over packet networks was also investigated in collaboration with John Apostolopoulos from HP Labs.  

Another set of experiments carried out with collaborators at [AT&T Research](https://about.att.com/sites/labs_research) focused on the use of aggregate and "non-intrusive" performance measures for 
estimating the actual throughput experienced by TCP based applications. Non-intrusive refers to measures that are readily available from routine network monitoring, 
e.g., from routers MIBs, and do not require any flow specific awareness. The work involved the development of models (modification of existing models) that were capable 
of accurately predicting TCP throughput on the basis of such information, and the evaluation of their accuracy using both simulations and testbed experiments. 

### Penn Contributors

* Wael Ashmawi 
* [Roch Guerin](https://www.cse.wustl.edu/~guerin/) 
* [Shu Tao](https://www.linkedin.com/in/shu-tao-8940a54/) 

### Publications

* W. Ashmawi, R. Guerin, S. Wolf, and M. Pinson, [*"On the impact of policing and rate guarantees in Diff-Serv networks: A video streaming application perspective."*](http://repository.upenn.edu/ese_papers/77)
In Proceedings ACM SIGCOMM'2001, UC San Diego, CA, August 2001.
* M. Goyal, R. Guerin, and R. Rajan, [*"Predicting TCP Throughput From Non-invasive Data."*](http://www.seas.upenn.edu/~guerin/publications/TCP_report.pdf) 
Technical Report, University of Pennsylvania, November 2000 (updated August 2001). [Short version](http://repository.upenn.edu/ese_papers/92) presented at INFOCOM'2002, New York, NY, June 2002.
* X.Lu, S. Tao, M. El Zarki, and R. Guerin, [*"Quality-based Adaptive Video Over the Internet."*](http://einstein.seas.upenn.edu/mnlab/papers/Tao_cnds03.pdf) In Proceedings of CNDS'2003, Orlando, FL, January 2003.
* S. Tao and R. Guerin, [*"On-line Estimation of Internet Path Performance: An Application Perspective."*}(http://repository.upenn.edu/ese_papers/78) In Proceedings of IEEE INFOCOM'2004, Hong Kong, March 2004.
* S. Tao and R. Guerin, [*"Application-Specific Path Switching: A Case Study for Streaming Video."*](http://repository.upenn.edu/ese_papers/79) In Proceedings of ACM Multimedia 2004, October 10-16, 2004, New York, NY.
* S. Tao, K. Xu, Y. Xu, T. Fei, L. Gao, R. Guerin, J. Kurose, D. Towsley, Z.-L. Zhang, [*"Exploring the Performance Benefits of End-to-End Path Switching."*](http://repository.upenn.edu/ese_papers/80) In Proceedings of IEEE ICNP 2004, Berlin, Germany, Oct, 2004.
* S. Tao, K. Xu, A. Estepa, T. Fei, L. Gao, R. Guerin, J. Kurose, D. Towsley, and Z.-L. Zhang, [*"Improving VoIP Quality Through Path Switching."*](http://repository.upenn.edu/ese_papers/109) In Proceedings of IEEE INFOCOM'2005, Miami, FL, March 2005.
* S. Tao, J. Apostolopoulos and R. Guerin, [*"Real-Time Monitoring of Video Quality in IP Networks."*](http://repository.upenn.edu/ese_papers/422) IEEE/ACM Trans. Netw., Vol. 16, No. 6, December 2008. Short version was presented at NOSSDAV’05, Skamania, OR, June 2005.

