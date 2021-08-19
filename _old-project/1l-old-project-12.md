---
title: "Exploring the Challenges of Network Migration - An IPv6 Case Study and its Consequences"
excerpt: "Supported by NSF grant CNS-1116039"
collection: old-project
---

This started as a joint project with Comcast that was subsequently supported by NSF. It was first introduced at the [Summer 2010 ESCC/Internet2 Joint Techs conference](https://meetings.internet2.edu/2010-07-JT/detail/10001250/),
but unfortunately the video was in flash format that is not accessible anymore.  The project's goals were to assess, understand, and encourage the adoption of IPv6. 
Specifically, as we were rapidly approach the date at which the current set of IPv4 addresses were going to be exhausted, i.e., in 2011, migrating to IPv6 was becoming 
increasingly important. This migration was, however, largely dependent on ensuring that the current IPv4 Internet, and in particular its content, became itself accessible over IPv6. 
Tracking the extent to which this was happening was the main purpose of this project. This tracking was performed by a monitoring client that queried the Domain Name System (DNS) 
for IPv4 and IPv6 addresses (A and quad-A records) for a number of known sites. The list of sites queried included the top one million (1M) web sites according to the ranking 
maintained by [Alexa](http://s3.amazonaws.com/alexa-static/top-1m.csv.zip), as well as a number of additional sites beyond the top 1M (the monitoring system was ultimately tracking the Ipv6 accessibility of over 6M web sites). 
Content was deemed IPv6 *accessible* if DNS returned a quad-A record for the site. Sites identified as being both IPv4 and IPv6 accessible were then queried for content, 
and deemed IPv4 and IPv6 *reachable* if the same content could be retrieved over both. The relative performance of content retrieval over IPv4 and IPv6 was also compared 
based on a succession of queries. One of the project's goals was to analyze this data to understand when, where and why differences exist between Ipv4 and IPv6 access, 
and how these should be addressed or used to foster a faster a migration to IPv6. 

To provide a comprehensive perspective on the level of IPv6 adoption across the Internet, the monitoring software was deployed at multiple locations, and
most of the data remains available on the [project web site](http://mnlab-ipv6.seas.wustl.edu/) that also boasts a ["query"](http://mnlab-ipv6.seas.upenn.edu/query) page that allows you to customize the type of data you want to retrieve. 

### Penn Contributors

* [Roch Guerin](https://www.cse.wustl.edu/~guerin/) 
* [Mehdi Nikkhah](https://www.linkedin.com/in/mehdi-nikkhah/)

### Publications

* M. Nikkhah and R. Guerin, [*"Migrating the Internet to IPv6: An Exploration of the When and Why."*](http://dl.acm.org/authorize?N21664)
IEEE/ACM Trans. Netw., Vol. 24, No. 4, August 2016, pp. 2291-2304.
* R. Guerin, J. C. de Oliveira, and S. Weber, [*"Adoption of Bundled Services With Network Externalities and Correlated Affinities."*](http://dl.acm.org/authorize?N83254) 
Special issue on Pricing and Incentives in Networks and Systems of the ACM Transactions on Internet Technologies (DOI:http://dx.doi.org/10.1145/2663493), Vol. 14, No. 2-3, pp. 13:1-13:32, October 2014.
* M. Nikkhah and R. Guerin, [*[Migrating to IPv6 – The role of basic coordination."*](http://openscholarship.wustl.edu/cse_research/113)
In Proc. [IFIP Networking 2014 conference](http://networking2014.item.ntnu.no/), Trondheim Norway, June 2014.
* M. Nikkhah, R. Guerin, Y. Lee, and R. Woundy, [*"Assessing IPv6 Through Web Access – A Measurement Study and Its Findings."*](http://repository.upenn.edu/ese_papers/602)
In Proc. [ACM CoNEXT 2011 Conference](http://conferences.sigcomm.org/co-next/2011/), Tokyo, Japan, December 2011.

-----------------------------

